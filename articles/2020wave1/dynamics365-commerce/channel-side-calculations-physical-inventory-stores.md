---
title: 店舗で利用可能な現物在庫のチャネル側での計算
description: この機能により、POS (販売時点管理) アプリケーションのユーザーは、リアルタイムのサービス呼び出しを使用しなくても、店舗の手持在庫データにアクセスできるようになります。
author: hhainesms
ms.reviewer: josaw
ms.date: 01/28/2020
ms.assetid: 988847a0-0300-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 37c06c554a73ab03b984c0c0ab271dfc9c42c5df
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3031695"
---
# <a name="channel-side-calculations-for-available-physical-inventory-for-stores"></a><span data-ttu-id="13486-103">店舗で利用可能な現物在庫のチャネル側での計算</span><span class="sxs-lookup"><span data-stu-id="13486-103">Channel-side calculations for available physical inventory for stores</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="13486-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="13486-104">Enabled for</span></span>    |  <span data-ttu-id="13486-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="13486-105">Public preview</span></span> | <span data-ttu-id="13486-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="13486-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="13486-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="13486-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="13486-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="13486-108">Feb 2020</span></span>| <span data-ttu-id="13486-109">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="13486-109">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="13486-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="13486-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="13486-111">本社 (HQ) にリアルタイム サービス (RTS) コールバックを実行することなく、推定手持店舗在庫の値を取得することを希望する多くの小売業者がいます。</span><span class="sxs-lookup"><span data-stu-id="13486-111">We have many retailers who would prefer to get an estimated on-hand value for their store inventory without having to perform real-time service (RTS) calls back to headquarters (HQ) to obtain this data.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="13486-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="13486-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="13486-113">"利用可能な現物" のチャネル側計算ロジックは、店舗在庫検索関連タスクでの使用のために追加されます。</span><span class="sxs-lookup"><span data-stu-id="13486-113">Channel-side calculation logic for "physical available" will be added for use with store inventory lookup-related tasks.</span></span> <span data-ttu-id="13486-114">この計算を実行するには、製品使用可能性ジョブを通じて、HQ からの在庫データを定期的に "同期" する必要があります。</span><span class="sxs-lookup"><span data-stu-id="13486-114">This calculation will require a periodic "sync" of inventory data from HQ through product availability jobs.</span></span> <span data-ttu-id="13486-115">店舗のチャネル データベースでは、HQ からこの情報が取得されていないと、店舗に転記された在庫トランザクション (HQ から店舗倉庫に対して処理された領収書、棚卸仕訳帳、販売注文など) を把握できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="13486-115">The store channel database might not know about inventory transactions posted for the store (such as receipts, count journals, or sales orders processed against the store warehouse from HQ) without getting this information from HQ.</span></span>

<span data-ttu-id="13486-116">このチャネル側計算は、HQ によって提供されたデータを取得し、店舗のチャネル データベースで "利用可能な現物" に影響する可能性がある未転記のトランザクションをチェックした後、必要に応じて在庫を追加または削除して、HQ がまだ把握していないトランザクションを把握するというものです。</span><span class="sxs-lookup"><span data-stu-id="13486-116">This channel-side calculation will take the data provided by HQ and check for unposted transactions in the store's channel database that might impact "physical available," and add or remove inventory as necessary to account for those transactions that HQ does not know about yet.</span></span>

<span data-ttu-id="13486-117">この計算は、あくまで利用可能な在庫の推定数を割り出すことを目的としたものです。</span><span class="sxs-lookup"><span data-stu-id="13486-117">This calculation is meant to provide an estimated available inventory only.</span></span> <span data-ttu-id="13486-118">HQ データベースは在庫マスターではないため、店舗データベースの手持在庫について常に 100% の信頼性を保証することはできません。</span><span class="sxs-lookup"><span data-stu-id="13486-118">Due to the fact that the HQ database is the inventory master, it will not be possible to ensure 100 percent reliability at all times for inventory on hand in the store database.</span></span> <span data-ttu-id="13486-119">HQ で店舗の在庫に影響を与えるイベントが発生する場合がありますが、これはチャネル データベースによって認識されない場合があります。</span><span class="sxs-lookup"><span data-stu-id="13486-119">Events might happen in HQ that affect a store's inventory that might not be known by the channel database.</span></span>

<span data-ttu-id="13486-120">この機能を正常に動作させるには、トリクル フィード明細転記の使用も必要になります。</span><span class="sxs-lookup"><span data-stu-id="13486-120">In order for this feature to work, the use of trickle feed statement posting will also be required.</span></span>
<!--feature detail end -->









