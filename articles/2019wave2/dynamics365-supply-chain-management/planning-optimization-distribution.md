---
title: 配布の計画の最適化
description: 計画の最適化により、迅速なマスター計画が促進され、大量のデータが個別のサービスとしてサポートされます。
author: relnotes
ms.reviewer: josaw
ms.date: 10/07/2019
ms.assetid: 9ba08c76-37d6-e911-a812-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: crytt
dynamics365pdf: true
ms.openlocfilehash: ea1faa84563c98f350b9c1a41cd767e17e4d095a
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660594"
---
# <a name="planning-optimization-for-distribution"></a><span data-ttu-id="14b90-103">配布の計画の最適化</span><span class="sxs-lookup"><span data-stu-id="14b90-103">Planning optimization for distribution</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="14b90-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="14b90-104">Enabled for</span></span>    |  <span data-ttu-id="14b90-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="14b90-105">Public preview</span></span> | <span data-ttu-id="14b90-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="14b90-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="14b90-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="14b90-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="14b90-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="14b90-108">Oct 2019</span></span>| <span data-ttu-id="14b90-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="14b90-109">Feb 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="14b90-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="14b90-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="14b90-111">計画の最適化は、大量のデータを迅速に処理するために特別に設計されています。</span><span class="sxs-lookup"><span data-stu-id="14b90-111">Planning optimization is specifically designed for very fast calculations with massive data volume.</span></span> <span data-ttu-id="14b90-112">これはスケーラビリティの非常に高いマルチテナント型のサービスとして構築されています。つまり、複数のテナントを同時に連携させて計画を処理できます。</span><span class="sxs-lookup"><span data-stu-id="14b90-112">It’s built as a hyper-scalable multitenant service, meaning that multiple tenants can cooperate simultaneously to calculate the plan.</span></span> <span data-ttu-id="14b90-113">また、計画サービスは ERP システムからマスター プラン実行の負荷を取り除き、サーバーの負荷を最小に抑えるようデータ ストリームを処理します。</span><span class="sxs-lookup"><span data-stu-id="14b90-113">Also, the planning service will remove the load of master planning from your ERP system and work with a data stream that minimizes the server load.</span></span>

## <a name="customer-benefits"></a><span data-ttu-id="14b90-114">お客様のメリット</span><span class="sxs-lookup"><span data-stu-id="14b90-114">Customer benefits</span></span>

<span data-ttu-id="14b90-115">**バッチ ジョブを計画するために毎日時間を確保する必要がなくなる**</span><span class="sxs-lookup"><span data-stu-id="14b90-115">**Eliminate daily time reserved for planning batch job**</span></span>

- <span data-ttu-id="14b90-116">大規模なデータセットを持つお客様は、すべてのバッチ ジョブを夜間に完了するのに問題があります。</span><span class="sxs-lookup"><span data-stu-id="14b90-116">Customers with large data sets have issues completing all batch jobs at night.</span></span>

- <span data-ttu-id="14b90-117">時間帯を取得するのが難しい 週 7 日 24 時間体制のビジネス。</span><span class="sxs-lookup"><span data-stu-id="14b90-117">24/7 business where it is hard to get any time slots.</span></span>

<span data-ttu-id="14b90-118">**将来の事業の成長により計画システムが過負荷にならないという安心感を与える**</span><span class="sxs-lookup"><span data-stu-id="14b90-118">**Comfort that future business growth will not overload the planning system**</span></span>

- <span data-ttu-id="14b90-119">ハイパースケーラブルなサービスにより、計画が迅速に行われ、パフォーマンスに影響を与えることがなくなります。</span><span class="sxs-lookup"><span data-stu-id="14b90-119">A hyper-scalable service ensures that planning will be fast and not have performance implications.</span></span>

- <span data-ttu-id="14b90-120">ダウンタイムなしでの最新バージョンへの自動アップグレード。</span><span class="sxs-lookup"><span data-stu-id="14b90-120">Automated upgrade to latest version without downtime.</span></span>

<span data-ttu-id="14b90-121">**日次または週次よりも高い頻度で計画を実行できる**</span><span class="sxs-lookup"><span data-stu-id="14b90-121">**More frequent planning runs – not just daily or weekly**</span></span>

- <span data-ttu-id="14b90-122">夜間の実行を待たずに、営業時間中に計画を更新します。</span><span class="sxs-lookup"><span data-stu-id="14b90-122">Update plan during office hours, without having to wait for the nightly run.</span></span>

- <span data-ttu-id="14b90-123">変更された計画パラメーターは数分で反映されます。</span><span class="sxs-lookup"><span data-stu-id="14b90-123">Changed planning parameters are reflected in minutes.</span></span>

- <span data-ttu-id="14b90-124">計画のシミュレーションの結果をすぐに確認し、目的の結果が得られるまでパラメーターをオンザフライで調整し続けます。</span><span class="sxs-lookup"><span data-stu-id="14b90-124">See the result of planning simulations right away and keep tweaking parameters on the fly until you get the desired result.</span></span>

<span data-ttu-id="14b90-125">**総リードタイムの短縮による顧客サービスの向上**</span><span class="sxs-lookup"><span data-stu-id="14b90-125">**Improved customer service with shorter total lead time**</span></span>

- <span data-ttu-id="14b90-126">新しい需要がより早く検出され、管理されます。</span><span class="sxs-lookup"><span data-stu-id="14b90-126">New demands are detected and managed earlier.</span></span>

- <span data-ttu-id="14b90-127">夜間の計画を待つ必要がないため、同日に注文できます。</span><span class="sxs-lookup"><span data-stu-id="14b90-127">Order same day because you don’t have to wait for the nightly plan.</span></span>

- <span data-ttu-id="14b90-128">供給がすぐに注文されるため、多くのお客様がリード タイムを 1 日短縮できます。</span><span class="sxs-lookup"><span data-stu-id="14b90-128">Many customers can save one day of lead time as supply is ordered right away.</span></span>

<span data-ttu-id="14b90-129">**在庫レベルの削減によるコストと資本の節約**</span><span class="sxs-lookup"><span data-stu-id="14b90-129">**Cost and capital savings by reduced inventory levels**</span></span>

- <span data-ttu-id="14b90-130">補充が速くなるため、必要な安全在庫が少なくなります。</span><span class="sxs-lookup"><span data-stu-id="14b90-130">Less safety stock is needed due to faster replenishment.</span></span>

## <a name="availability"></a><span data-ttu-id="14b90-131">利用可能性</span><span class="sxs-lookup"><span data-stu-id="14b90-131">Availability</span></span>

<span data-ttu-id="14b90-132">計画最適化のプレビューを開始する方法の詳細については、「[概要](https://aka.ms/poGetStarted)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="14b90-132">For more information on how to get started with the planning optimization preview, see [Get Started](https://aka.ms/poGetStarted).</span></span>

## <a name="feature-highlights"></a><span data-ttu-id="14b90-133">主な機能</span><span class="sxs-lookup"><span data-stu-id="14b90-133">Feature highlights</span></span>

- <span data-ttu-id="14b90-134">計画サービスの最初のバージョンは、購入と供給の転送で流通業者と卸売業者の両方のニーズに対応する。</span><span class="sxs-lookup"><span data-stu-id="14b90-134">The first version of the planning service will address the needs of both distributors and wholesalers with purchase and transfer supply.</span></span>

- <span data-ttu-id="14b90-135">Dynamics 365 Supply Chain Management とそのまま統合できる。</span><span class="sxs-lookup"><span data-stu-id="14b90-135">Out-of-the-box integration with Dynamics 365 Supply Chain Management.</span></span>

- <span data-ttu-id="14b90-136">購入をサポートし、供給提案を転送する。</span><span class="sxs-lookup"><span data-stu-id="14b90-136">Support purchase and transfer supply suggestions.</span></span>

- <span data-ttu-id="14b90-137">手元にある在庫レベルと将来の需要に基づいて、固定の安全在庫レベルを維持するための供給提案を確保する。</span><span class="sxs-lookup"><span data-stu-id="14b90-137">Ensure supply suggestions to maintain fixed safety stock levels, based on on-hand levels and future demand.</span></span>

- <span data-ttu-id="14b90-138">需要の変動と季節性に対応する時間ベースの安全在庫オプション。</span><span class="sxs-lookup"><span data-stu-id="14b90-138">Time-based safety stock option, to support fluctuation and seasonality in demand.</span></span>

- <span data-ttu-id="14b90-139">期間や注文日の計算のために、購入や移動のリード時間を含める。</span><span class="sxs-lookup"><span data-stu-id="14b90-139">Include purchase and transfers lead times, for duration and order date calculation.</span></span>

- <span data-ttu-id="14b90-140">需要と供給を紐付け、特定の需要がどのようにして満たされるか、特定の供給がどのような需要を満たすかについて完全に視覚化できる。</span><span class="sxs-lookup"><span data-stu-id="14b90-140">Pegging between supply and demand, providing full visibility for how a given demand is fulfilled or what demand a given supply fulfills.</span></span>

- <span data-ttu-id="14b90-141">ロットごとの再注文ポリシーに対応。定義された期間内のすべての需要を 1 つの供給提案にまとめます。</span><span class="sxs-lookup"><span data-stu-id="14b90-141">Lot-for-lot reordering policy support, combining all demand within a defined period into one supply suggestion.</span></span>

- <span data-ttu-id="14b90-142">注文候補を希望の最小数量、倍数、最大数量に調整する注文数量修飾子。</span><span class="sxs-lookup"><span data-stu-id="14b90-142">Order quantity modifiers that adjust order suggestions to a desired minimum, multiple, and/or maximum quantity.</span></span>

- <span data-ttu-id="14b90-143">特定の計画実行に含まれる製品をフィルターすることで、1 つの品目または全製品のサブセットのみを計画する。</span><span class="sxs-lookup"><span data-stu-id="14b90-143">Plan just one item or a subset of all products by filtering the products included in a given planning run.</span></span>

- <span data-ttu-id="14b90-144">特定の設定を持つ複数の計画により、プランナーは複数の計画を同時に操作できる。</span><span class="sxs-lookup"><span data-stu-id="14b90-144">Multiple plans with specific setup, allowing the planner to simultaneously operate with multiple plans.</span></span>

- <span data-ttu-id="14b90-145">計画がすべての需要に合わせて最適化できないときに、注文の遅延を検出して履行日の候補を通知する。</span><span class="sxs-lookup"><span data-stu-id="14b90-145">Detect and communicate order delays and possible fulfillment dates, when the plan can’t be optimized to fit all demands.</span></span>

- <span data-ttu-id="14b90-146">倉庫、仕入先、顧客などに関連する利用できる期間と利用できない期間の処理をカレンダーで対応。</span><span class="sxs-lookup"><span data-stu-id="14b90-146">Calendar support to handle available and closed periods related to warehouses, vendors, customers, and more.</span></span>

- <span data-ttu-id="14b90-147">計画エンジンにより需要と供給間の予約のサポートが記録され考慮される。</span><span class="sxs-lookup"><span data-stu-id="14b90-147">Support for reservations between supply and demand are recorded and respected by the planning engine.</span></span>

- <span data-ttu-id="14b90-148">記録された需要に基づいて削減を伴う需要予測を含めるオプション。</span><span class="sxs-lookup"><span data-stu-id="14b90-148">Option to include demand forecast with reduction based on recorded demand.</span></span>

- <span data-ttu-id="14b90-149">事前定義された最大在庫レベルへの補充に対応する再注文ポリシー。</span><span class="sxs-lookup"><span data-stu-id="14b90-149">Reordering policy that supports refilling to a predefined maximum inventory level.</span></span>
<!--feature detail end -->




## <a name="geographic-areas"></a><span data-ttu-id="14b90-150">地域</span><span class="sxs-lookup"><span data-stu-id="14b90-150">Geographic areas</span></span>
<span data-ttu-id="14b90-151">この機能は、以下の Microsoft Azure 地域でリリースされる予定です。</span><span class="sxs-lookup"><span data-stu-id="14b90-151">This feature will be released into the following Microsoft Azure geographic areas:</span></span>

- <span data-ttu-id="14b90-152">米国</span><span class="sxs-lookup"><span data-stu-id="14b90-152">United States</span></span>
- <span data-ttu-id="14b90-153">ヨーロッパ</span><span class="sxs-lookup"><span data-stu-id="14b90-153">Europe</span></span>
- <span data-ttu-id="14b90-154">オーストラリア</span><span class="sxs-lookup"><span data-stu-id="14b90-154">Australia</span></span>
- <span data-ttu-id="14b90-155">カナダ</span><span class="sxs-lookup"><span data-stu-id="14b90-155">Canada</span></span>


<span data-ttu-id="14b90-156">地域、データ センター (リージョン)、データ ストレージ、レプリケーションの詳細については、[データの場所のページ](https://www.microsoft.com/trust-center/privacy/data-location)で**すべて展開**を選択して、この機能に対する Microsoft Cloud Service を確認してください。</span><span class="sxs-lookup"><span data-stu-id="14b90-156">For more information about geographic areas, data centers (regions), data storage, and replication, select **expand all** on the [Where your data is located page](https://www.microsoft.com/trust-center/privacy/data-location) and find the Microsoft cloud service for this feature.</span></span> 





## <a name="see-also"></a><span data-ttu-id="14b90-157">関連項目</span><span class="sxs-lookup"><span data-stu-id="14b90-157">See also</span></span>

<span data-ttu-id="14b90-158">[計画の最適化](https://aka.ms/podocs) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="14b90-158">[Planning optimization](https://aka.ms/podocs) (docs)</span></span>
