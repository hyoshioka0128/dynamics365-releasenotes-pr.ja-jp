---
title: 店舗で利用可能な現物在庫のチャネル側での計算
description: この機能により、POS (販売時点管理) アプリケーションのユーザーは、リアルタイムのサービス呼び出しを使用しなくても、店舗の手持在庫データにアクセスできるようになります。
author: hhainesms
ms.reviewer: josaw
ms.date: 03/24/2020
ms.assetid: 988847a0-0300-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 72d63d72fe8796c1758ba5b13910bf940e501f05
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232585"
---
# <a name="channel-side-calculations-for-available-physical-inventory-for-stores"></a><span data-ttu-id="fa490-103">店舗で利用可能な現物在庫のチャネル側での計算</span><span class="sxs-lookup"><span data-stu-id="fa490-103">Channel-side calculations for available physical inventory for stores</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="fa490-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="fa490-104">Enabled for</span></span>    |  <span data-ttu-id="fa490-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="fa490-105">Public preview</span></span> | <span data-ttu-id="fa490-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="fa490-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="fa490-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="fa490-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="fa490-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="fa490-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="fa490-109">2020 年 2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="fa490-109">Feb 24, 2020</span></span>| <span data-ttu-id="fa490-110">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="fa490-110">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="fa490-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="fa490-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="fa490-112">多くの小売業者は、Commerce Headquarters (HQ) にリアルタイム サービス (RTS) コールバックを実行することなく、推定手持店舗在庫の値を取得することを希望します。</span><span class="sxs-lookup"><span data-stu-id="fa490-112">Many retailers prefer to get an estimated on-hand value for their store inventory without having to perform real-time service (RTS) calls back to Commerce Headquarters (HQ) to obtain this on-hand data.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="fa490-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="fa490-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="fa490-114">物理的に利用可能な推定手持在庫の値を提供するチャネル側の計算ロジックは、販売時点管理 (POS) アプリケーションの構成に使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="fa490-114">Channel-side calculation logic that provides an estimated physical available on-hand value will be available for configuration for the point of sale (POS) application.</span></span> <span data-ttu-id="fa490-115">チャネル側の推定在庫計算では、製品使用可能性バッチおよびデータ同期ジョブを通じて、Commerce Headquarters (HQ) からの在庫データの定期的な "同期" が必要になります。</span><span class="sxs-lookup"><span data-stu-id="fa490-115">The channel-side estimated inventory calculation will require a periodic "sync" of inventory data from Commerce Headquarters (HQ) through product availability batch and data sync jobs.</span></span> <span data-ttu-id="fa490-116">店舗のチャネル データベースでは、Commerce Headquarters (HQ) からこの情報が取得されていないと、店舗に転記された在庫トランザクション (Commerce Headquarters (HQ) から店舗倉庫に対して処理された領収書、棚卸仕訳帳、販売注文など) を把握できない場合があるため、この同期が必要です。</span><span class="sxs-lookup"><span data-stu-id="fa490-116">The sync is required as the store channel database might not know about inventory transactions posted for the store (such as receipts, count journals, or sales orders processed against the store warehouse from Commerce Headquarters (HQ)) without getting this information from Commerce Headquarters (HQ).</span></span>

<span data-ttu-id="fa490-117">チャネル側の計算では、Commerce Headquarters (HQ) から提供されたデータを使用し、特定の品目の店舗の物理的な在庫に影響を与える可能性のあるチャネル データベース内の未転記の売上または返品トランザクションについてチャネル側のデータ チェックを実行します。</span><span class="sxs-lookup"><span data-stu-id="fa490-117">The channel-side calculation will use the data provided by Commerce Headquarters (HQ) and do a channel-side data check for any unposted sales or returns transactions in the channel database that might impact the store's physical availability for a particular item.</span></span> <span data-ttu-id="fa490-118">計算ロジックは、店舗在庫、およびその店舗のフルフィルメント グループにリンクされている他の店舗または倉庫の推定手持在庫の値を導き出します。</span><span class="sxs-lookup"><span data-stu-id="fa490-118">The calculation logic will derive an estimated on-hand value for the store inventory as well as any other stores or warehouses that are linked to that store's fulfillment group.</span></span>

<span data-ttu-id="fa490-119">計算では、利用可能な在庫の推定数のみを割り出します。</span><span class="sxs-lookup"><span data-stu-id="fa490-119">The calculation provides an estimated available inventory only.</span></span> <span data-ttu-id="fa490-120">Commerce Headquarters (HQ) データベースは在庫マスターではないため、店舗データベースの手持在庫について常に 100% の信頼性を保証することはできません。</span><span class="sxs-lookup"><span data-stu-id="fa490-120">Because the Commerce Headquarters (HQ) database is the inventory master, it is not possible to ensure 100% reliability at all times for inventory on hand in the store database.</span></span> <span data-ttu-id="fa490-121">Commerce Headquarters (HQ) で店舗の在庫に影響を与えるイベントが発生する場合がありますが、これはチャネル データベースによって認識されない場合があります。</span><span class="sxs-lookup"><span data-stu-id="fa490-121">Events can happen in Commerce Headquarters (HQ) that affect a store's inventory and might not be known by the channel database.</span></span>

<span data-ttu-id="fa490-122">この機能には、トリクル フィード明細転記の使用も必要になります。</span><span class="sxs-lookup"><span data-stu-id="fa490-122">The use of trickle feed statement posting is also required for this functionality.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="fa490-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="fa490-123">See also</span></span>


<!--docs start-->
<span data-ttu-id="fa490-124">[小売チャネルの引当可能在庫数量の計算](https://docs.microsoft.com/dynamics365/commerce/calculated-inventory-retail-channels) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="fa490-124">[Calculate inventory availability for retail channels](https://docs.microsoft.com/dynamics365/commerce/calculated-inventory-retail-channels) (docs)</span></span>
<!--docs end-->

