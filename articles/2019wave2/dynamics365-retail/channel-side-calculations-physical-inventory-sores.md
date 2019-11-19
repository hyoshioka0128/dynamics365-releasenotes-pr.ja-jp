---
title: 店舗で利用可能な現物在庫のチャネル側での計算
description: この機能により、POS (販売時点管理) アプリケーションのユーザーは、リアルタイムのサービス呼び出しを使用しなくても、店舗の手持在庫データにアクセスできるようになります。
author: hhainesms
ms.reviewer: josaw
ms.date: 10/02/2019
ms.assetid: 6663278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 538c556bf8420e931febe088bd94d37b567cb4ad
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2659916"
---
# <a name="channel-side-calculations-for-available-physical-inventory-for-stores"></a><span data-ttu-id="7637f-103">店舗で利用可能な現物在庫のチャネル側での計算</span><span class="sxs-lookup"><span data-stu-id="7637f-103">Channel-side calculations for available physical inventory for stores</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="7637f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7637f-104">Enabled for</span></span>    |  <span data-ttu-id="7637f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7637f-105">Public preview</span></span> | <span data-ttu-id="7637f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7637f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7637f-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="7637f-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="7637f-108">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="7637f-108">Nov 2019</span></span>| <span data-ttu-id="7637f-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="7637f-109">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="7637f-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7637f-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7637f-111">この機能は、HQ への安定した接続がなく、店舗で利用可能な現物在庫データを表示したい一部のお客様をサポートするものです。</span><span class="sxs-lookup"><span data-stu-id="7637f-111">This feature supports some of our customers who may not have reliable connectivity to HQ and wish to be able to view physical available inventory data for their stores.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7637f-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7637f-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7637f-113">"利用可能な現物" のチャネル側計算ロジックは、店舗在庫検索関連タスクでの使用のために、小売サーバーに追加されます。</span><span class="sxs-lookup"><span data-stu-id="7637f-113">A channel-side calculation logic for "physical available" will be added to the retail server for use with store inventory lookup-related tasks.</span></span> <span data-ttu-id="7637f-114">この計算を実行するには、製品使用可能性ジョブを通じて、HQ からの在庫データを定期的に "同期" する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7637f-114">This calculation will require a periodic "sync" of inventory data from HQ through product availability jobs.</span></span> <span data-ttu-id="7637f-115">店舗のチャネル データベースでは、HQ からこの情報が取得されていないと、店舗に転記された在庫トランザクション (HQ から店舗倉庫に対して処理された領収/棚卸仕訳帳や販売注文など) を把握できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="7637f-115">The store channel database may not know about inventory transactions posted for the store (such as receipts or count journals or sales orders processed against the store warehouse from HQ) without getting this information from HQ.</span></span>

<span data-ttu-id="7637f-116">このチャネル側計算は、HQ によって提供されたデータを取得し、店舗のチャネル DB で "利用可能な現物" に影響する可能性がある未転記のトランザクションをチェックした後、必要に応じて在庫を追加/削除して、HQ がまだ把握していないトランザクションを把握するというものです。</span><span class="sxs-lookup"><span data-stu-id="7637f-116">This channel-side calculation will take the data provided by HQ and check for unposted transactions in the store's channel DB that may impact "physical available," and add/remove inventory as necessary to account for those transactions that HQ does not know about yet.</span></span>

<span data-ttu-id="7637f-117">この計算は、あくまで利用可能な在庫の推定数を割り出すことを目的としたものです。</span><span class="sxs-lookup"><span data-stu-id="7637f-117">This calculation is meant to provide an estimated available inventory only.</span></span> <span data-ttu-id="7637f-118">ERP/HQ は在庫マスターではないため、常に 100% の信頼性を保証することはできません。店舗在庫に影響を与える事象が HQ で発生した場合に、そのことがチャネル データベースで認識されない可能性もあります。</span><span class="sxs-lookup"><span data-stu-id="7637f-118">Due to the fact that the ERP/HQ is out inventory master, it will not be possible to ensure 100% reliability at all times as things may happen in HQ that affect a store's inventory that may not be known by the channel database.</span></span>

<span data-ttu-id="7637f-119">この機能を正常に動作させるには、トリクル フィード明細転記の使用も必要になります。</span><span class="sxs-lookup"><span data-stu-id="7637f-119">In order for this feature to work, the use of trickle feed statement posting will also be required.</span></span>
<!--feature detail end -->









