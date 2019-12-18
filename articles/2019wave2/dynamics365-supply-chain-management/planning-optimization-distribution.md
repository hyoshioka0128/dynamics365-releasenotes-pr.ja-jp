---
title: 配布の計画の最適化
description: 計画の最適化により、迅速なマスター計画が促進され、大量のデータが個別のサービスとしてサポートされます。
author: relnotes
ms.reviewer: josaw
ms.date: 12/02/2019
ms.assetid: 9ba08c76-37d6-e911-a812-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: crytt
dynamics365pdf: true
ms.openlocfilehash: 78c8bed462b75a70dfd10adcb6fa087f29515048
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889796"
---
# <a name="planning-optimization-for-distribution"></a><span data-ttu-id="c8452-103">配布の計画の最適化</span><span class="sxs-lookup"><span data-stu-id="c8452-103">Planning optimization for distribution</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="c8452-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c8452-104">Enabled for</span></span>    |  <span data-ttu-id="c8452-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c8452-105">Public preview</span></span> | <span data-ttu-id="c8452-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c8452-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c8452-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="c8452-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c8452-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c8452-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c8452-109">2019 年 11 月 29 日</span><span class="sxs-lookup"><span data-stu-id="c8452-109">Nov 29, 2019</span></span>| <span data-ttu-id="c8452-110">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="c8452-110">Feb 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="c8452-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c8452-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c8452-112">計画の最適化は、大量のデータを迅速に処理するために特別に設計されています。</span><span class="sxs-lookup"><span data-stu-id="c8452-112">Planning optimization is specifically designed for very fast calculations with massive data volume.</span></span> <span data-ttu-id="c8452-113">これはスケーラビリティの非常に高いマルチテナント型のサービスとして構築されています。つまり、複数のテナントを同時に連携させて計画を処理できます。</span><span class="sxs-lookup"><span data-stu-id="c8452-113">It’s built as a hyper-scalable multitenant service, meaning that multiple tenants can cooperate simultaneously to calculate the plan.</span></span> <span data-ttu-id="c8452-114">また、計画サービスは ERP システムからマスター プラン実行の負荷を取り除き、サーバーの負荷を最小に抑えるようデータ ストリームを処理します。</span><span class="sxs-lookup"><span data-stu-id="c8452-114">Also, the planning service will remove the load of master planning from your ERP system and work with a data stream that minimizes the server load.</span></span>

### <a name="customer-benefits"></a><span data-ttu-id="c8452-115">お客様のメリット</span><span class="sxs-lookup"><span data-stu-id="c8452-115">Customer benefits</span></span>

<span data-ttu-id="c8452-116">**バッチ ジョブを計画するために毎日時間を確保する必要がなくなる**</span><span class="sxs-lookup"><span data-stu-id="c8452-116">**Eliminate daily time reserved for planning batch job**</span></span>

- <span data-ttu-id="c8452-117">大規模なデータセットを持つお客様は、すべてのバッチ ジョブを夜間に完了するのに問題があります。</span><span class="sxs-lookup"><span data-stu-id="c8452-117">Customers with large data sets have issues completing all batch jobs at night.</span></span>
- <span data-ttu-id="c8452-118">時間帯を取得するのが難しい 週 7 日 24 時間体制のビジネス。</span><span class="sxs-lookup"><span data-stu-id="c8452-118">24/7 business where it is hard to get any time slots.</span></span>

<span data-ttu-id="c8452-119">**将来の事業の成長により計画システムが過負荷にならないという安心感を与える**</span><span class="sxs-lookup"><span data-stu-id="c8452-119">**Comfort that future business growth will not overload the planning system**</span></span>

- <span data-ttu-id="c8452-120">ハイパースケーラブルなサービスにより、計画が迅速に行われ、パフォーマンスに影響を与えることがなくなります。</span><span class="sxs-lookup"><span data-stu-id="c8452-120">A hyper-scalable service ensures that planning will be fast and not have performance implications.</span></span>
- <span data-ttu-id="c8452-121">ダウンタイムなしでの最新バージョンへの自動アップグレード。</span><span class="sxs-lookup"><span data-stu-id="c8452-121">Automated upgrade to latest version without downtime.</span></span>

<span data-ttu-id="c8452-122">**日次または週次よりも高い頻度で計画を実行できる**</span><span class="sxs-lookup"><span data-stu-id="c8452-122">**More frequent planning runs – not just daily or weekly**</span></span>

- <span data-ttu-id="c8452-123">夜間の実行を待たずに、営業時間中に計画を更新します。</span><span class="sxs-lookup"><span data-stu-id="c8452-123">Update plan during office hours, without having to wait for the nightly run.</span></span>
- <span data-ttu-id="c8452-124">変更された計画パラメーターは数分で反映されます。</span><span class="sxs-lookup"><span data-stu-id="c8452-124">Changed planning parameters are reflected in minutes.</span></span>
- <span data-ttu-id="c8452-125">計画のシミュレーションの結果をすぐに確認し、目的の結果が得られるまでパラメーターをオンザフライで調整し続けます。</span><span class="sxs-lookup"><span data-stu-id="c8452-125">See the result of planning simulations right away and keep tweaking parameters on the fly until you get the desired result.</span></span>

<span data-ttu-id="c8452-126">**総リードタイムの短縮による顧客サービスの向上**</span><span class="sxs-lookup"><span data-stu-id="c8452-126">**Improved customer service with shorter total lead time**</span></span>

- <span data-ttu-id="c8452-127">新しい需要がより早く検出され、管理されます。</span><span class="sxs-lookup"><span data-stu-id="c8452-127">New demands are detected and managed earlier.</span></span>
- <span data-ttu-id="c8452-128">夜間の計画を待つ必要がないため、同日に注文できます。</span><span class="sxs-lookup"><span data-stu-id="c8452-128">Order same day because you don’t have to wait for the nightly plan.</span></span>
- <span data-ttu-id="c8452-129">供給がすぐに注文されるため、多くのお客様がリード タイムを 1 日短縮できます。</span><span class="sxs-lookup"><span data-stu-id="c8452-129">Many customers can save one day of lead time as supply is ordered right away.</span></span>

<span data-ttu-id="c8452-130">**在庫レベルの削減によるコストと資本の節約**</span><span class="sxs-lookup"><span data-stu-id="c8452-130">**Cost and capital savings by reduced inventory levels**</span></span>

- <span data-ttu-id="c8452-131">補充が速くなるため、必要な安全在庫が少なくなります。</span><span class="sxs-lookup"><span data-stu-id="c8452-131">Less safety stock is needed due to faster replenishment.</span></span>

### <a name="availability"></a><span data-ttu-id="c8452-132">利用可能性</span><span class="sxs-lookup"><span data-stu-id="c8452-132">Availability</span></span>

<span data-ttu-id="c8452-133">計画最適化のプレビューを開始する方法の詳細については、「[概要](https://aka.ms/poGetStarted)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c8452-133">For more information on how to get started with the planning optimization preview, see [Get Started](https://aka.ms/poGetStarted).</span></span>

### <a name="feature-highlights"></a><span data-ttu-id="c8452-134">主な機能</span><span class="sxs-lookup"><span data-stu-id="c8452-134">Feature highlights</span></span>
- <span data-ttu-id="c8452-135">計画サービスの最初のバージョンは、購入と供給の転送で流通業者と卸売業者の両方のニーズに対応する。</span><span class="sxs-lookup"><span data-stu-id="c8452-135">The first version of the planning service will address the needs of both distributors and wholesalers with purchase and transfer supply.</span></span>
- <span data-ttu-id="c8452-136">Dynamics 365 Supply Chain Management とそのまま統合できる。</span><span class="sxs-lookup"><span data-stu-id="c8452-136">Out-of-the-box integration with Dynamics 365 Supply Chain Management.</span></span>
- <span data-ttu-id="c8452-137">購入をサポートし、供給提案を転送する。</span><span class="sxs-lookup"><span data-stu-id="c8452-137">Support purchase and transfer supply suggestions.</span></span>
- <span data-ttu-id="c8452-138">手元にある在庫レベルと将来の需要に基づいて、固定の安全在庫レベルを維持するための供給提案を確保する。</span><span class="sxs-lookup"><span data-stu-id="c8452-138">Ensure supply suggestions to maintain fixed safety stock levels, based on on-hand levels and future demand.</span></span>
- <span data-ttu-id="c8452-139">需要の変動と季節性に対応する時間ベースの安全在庫オプション。</span><span class="sxs-lookup"><span data-stu-id="c8452-139">Time-based safety stock option, to support fluctuation and seasonality in demand.</span></span>
- <span data-ttu-id="c8452-140">期間や注文日の計算のために、購入や移動のリード時間を含める。</span><span class="sxs-lookup"><span data-stu-id="c8452-140">Include purchase and transfers lead times, for duration and order date calculation.</span></span>
- <span data-ttu-id="c8452-141">需要と供給を紐付け、特定の需要がどのようにして満たされるか、特定の供給がどのような需要を満たすかについて完全に視覚化できる。</span><span class="sxs-lookup"><span data-stu-id="c8452-141">Pegging between supply and demand, providing full visibility for how a given demand is fulfilled or what demand a given supply fulfills.</span></span>
- <span data-ttu-id="c8452-142">ロットごとの再注文ポリシーに対応。定義された期間内のすべての需要を 1 つの供給提案にまとめます。</span><span class="sxs-lookup"><span data-stu-id="c8452-142">Lot-for-lot reordering policy support, combining all demand within a defined period into one supply suggestion.</span></span>
- <span data-ttu-id="c8452-143">注文候補を希望の最小数量、倍数、最大数量に調整する注文数量修飾子。</span><span class="sxs-lookup"><span data-stu-id="c8452-143">Order quantity modifiers that adjust order suggestions to a desired minimum, multiple, and/or maximum quantity.</span></span>
- <span data-ttu-id="c8452-144">特定の計画実行に含まれる製品をフィルターすることで、1 つの品目または全製品のサブセットのみを計画する。</span><span class="sxs-lookup"><span data-stu-id="c8452-144">Plan just one item or a subset of all products by filtering the products included in a given planning run.</span></span>
- <span data-ttu-id="c8452-145">特定の設定を持つ複数の計画により、プランナーは複数の計画を同時に操作できる。</span><span class="sxs-lookup"><span data-stu-id="c8452-145">Multiple plans with specific setup, allowing the planner to simultaneously operate with multiple plans.</span></span>
- <span data-ttu-id="c8452-146">計画がすべての需要に合わせて最適化できないときに、注文の遅延を検出して履行日の候補を通知する。</span><span class="sxs-lookup"><span data-stu-id="c8452-146">Detect and communicate order delays and possible fulfillment dates, when the plan can’t be optimized to fit all demands.</span></span>
- <span data-ttu-id="c8452-147">倉庫、仕入先、顧客などに関連する利用できる期間と利用できない期間の処理をカレンダーで対応。</span><span class="sxs-lookup"><span data-stu-id="c8452-147">Calendar support to handle available and closed periods related to warehouses, vendors, customers, and more.</span></span>
- <span data-ttu-id="c8452-148">計画エンジンにより需要と供給間の予約のサポートが記録され考慮される。</span><span class="sxs-lookup"><span data-stu-id="c8452-148">Support for reservations between supply and demand are recorded and respected by the planning engine.</span></span>
- <span data-ttu-id="c8452-149">記録された需要に基づいて削減を伴う需要予測を含めるオプション。</span><span class="sxs-lookup"><span data-stu-id="c8452-149">Option to include demand forecast with reduction based on recorded demand.</span></span>
- <span data-ttu-id="c8452-150">事前定義された最大在庫レベルへの補充に対応する再注文ポリシー。</span><span class="sxs-lookup"><span data-stu-id="c8452-150">Reordering policy that supports refilling to a predefined maximum inventory level.</span></span>
<!--feature detail end -->




## <a name="geographic-areas"></a><span data-ttu-id="c8452-151">地域</span><span class="sxs-lookup"><span data-stu-id="c8452-151">Geographic areas</span></span>
<span data-ttu-id="c8452-152">この機能は、以下の Microsoft Azure 地域でリリースされる予定です。</span><span class="sxs-lookup"><span data-stu-id="c8452-152">This feature will be released into the following Microsoft Azure geographic areas:</span></span>

- <span data-ttu-id="c8452-153">米国</span><span class="sxs-lookup"><span data-stu-id="c8452-153">United States</span></span>
- <span data-ttu-id="c8452-154">ヨーロッパ</span><span class="sxs-lookup"><span data-stu-id="c8452-154">Europe</span></span>
- <span data-ttu-id="c8452-155">オーストラリア</span><span class="sxs-lookup"><span data-stu-id="c8452-155">Australia</span></span>
- <span data-ttu-id="c8452-156">カナダ</span><span class="sxs-lookup"><span data-stu-id="c8452-156">Canada</span></span>


<span data-ttu-id="c8452-157">地域、データ センター (リージョン)、データ ストレージ、レプリケーションの詳細については、[データの場所のページ](https://www.microsoft.com/trust-center/privacy/data-location)で**すべて展開**をクリックして、この機能に対する Microsoft Cloud Service を確認してください。</span><span class="sxs-lookup"><span data-stu-id="c8452-157">For more information about geographic areas, data centers (regions), data storage, and replication, click **expand all** on the [Where your data is located page](https://www.microsoft.com/trust-center/privacy/data-location) and find the Microsoft cloud service for this feature.</span></span> 





## <a name="see-also"></a><span data-ttu-id="c8452-158">関連項目</span><span class="sxs-lookup"><span data-stu-id="c8452-158">See also</span></span>

<span data-ttu-id="c8452-159">[計画の最適化](https://aka.ms/podocs) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c8452-159">[Planning Optimization](https://aka.ms/podocs) (docs)</span></span>
