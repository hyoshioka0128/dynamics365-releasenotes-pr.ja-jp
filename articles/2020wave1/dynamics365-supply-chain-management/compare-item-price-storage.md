---
title: 品目価格の比較の格納
description: 品目価格の比較の格納機能を使用すると、品目価格の比較レポートを実行して、Dynamics 365 Supply Chain Management 内で出力にアクセスできるようにしたり、外部アプリケーションで使用するためにデータ エンティティを通じて出力のエクスポートに使用できるようにしたりできます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 02/18/2020
ms.assetid: 77df9cfb-2831-ea11-a810-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: aevengir
dynamics365pdf: true
ms.openlocfilehash: c11eb5af7b70a48cecfdee7ef1e096337ea77223
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3080184"
---
# <a name="compare-item-price-storage"></a><span data-ttu-id="62371-103">品目価格の比較の格納</span><span class="sxs-lookup"><span data-stu-id="62371-103">Compare item price storage</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="62371-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="62371-104">Enabled for</span></span>    |  <span data-ttu-id="62371-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="62371-105">Public preview</span></span> | <span data-ttu-id="62371-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="62371-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="62371-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="62371-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="62371-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="62371-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="62371-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="62371-109">Feb 1, 2020</span></span>| <span data-ttu-id="62371-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="62371-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="62371-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="62371-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="62371-112">この新しい品目価格の比較レポートの実行方法は、出力に多数の行が含まれる場合に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="62371-112">This new way of executing the Compare item price report is useful in cases where the output contains a large number of lines.</span></span> <span data-ttu-id="62371-113">たとえば、60,000 品目に対する現在のアクティブな標準原価と来年の保留中の標準原価の比較を要求すると、データを確認するのが難しい非常に長いレポートが生成されます。</span><span class="sxs-lookup"><span data-stu-id="62371-113">For example, requesting a comparison of the current active standard cost against next year's pending standard cost for 60,000 items would yield a very long report, where data is difficult to review.</span></span> <span data-ttu-id="62371-114">結果を並べ替えてフィルター処理したり、結果を外部システムにエクスポートしたりできると、レポートをすばやく簡単に確認できます。</span><span class="sxs-lookup"><span data-stu-id="62371-114">Being able to sort and filter the results, or to export the results to an external system, makes the report faster and easier to navigate.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="62371-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="62371-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="62371-116">品目価格の比較の格納用の新しい機能を導入しています。</span><span class="sxs-lookup"><span data-stu-id="62371-116">We are introducing new functionality for comparing item price storage.</span></span> <span data-ttu-id="62371-117">「品目価格の比較」レポートを実行するときは、特定の実行に対して一意の名前を指定する必要があり、レポートの結果はその名前で保存されます。</span><span class="sxs-lookup"><span data-stu-id="62371-117">When you execute the "Compare item price" report, you must provide a unique name for the specific execution, and the results of the report will be stored under this name.</span></span>

<span data-ttu-id="62371-118">出力には、**品目価格の比較の格納**ページでアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="62371-118">The output will be accessible on the **Compare item price storage** page.</span></span> <span data-ttu-id="62371-119">このページでは、ユーザーが行った構成に応じて列が動的に調整され、残高が集計されます。</span><span class="sxs-lookup"><span data-stu-id="62371-119">This page dynamically adjusts columns and aggregates balances depending on the configuration made by the user.</span></span> <span data-ttu-id="62371-120">フィルターを追加して、価格の純変動額が最大の品目がグリッドの上部に表示されるようにできます。</span><span class="sxs-lookup"><span data-stu-id="62371-120">You can add a filter so the items with the largest net change in price are listed at the top of the grid.</span></span> <span data-ttu-id="62371-121">ドリルスルー機能を使用すると、原価グループ タイプまたは原価グループごとに純変動額を確認できます。</span><span class="sxs-lookup"><span data-stu-id="62371-121">A drill-through function provides the ability to see the net change by cost group type or cost group.</span></span> <span data-ttu-id="62371-122">特定の価格をさらに分析する必要がある場合は、実際原価計算へのリンクを利用できます。</span><span class="sxs-lookup"><span data-stu-id="62371-122">In case a specific price requires further analysis, a link to the actual cost calculation is available.</span></span>

<span data-ttu-id="62371-123">また、新しい「品目価格の比較」データ エンティティも導入しています。</span><span class="sxs-lookup"><span data-stu-id="62371-123">We are also introducing a new "Compare item price" data entity.</span></span> <span data-ttu-id="62371-124">このデータ エンティティを使用すると、特定の「品目価格の比較」レポートの出力をデータ管理でサポートされる任意の形式にエクスポートして、データを外部アプリケーションで使用できるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="62371-124">This data entity enables you to export the output of a specific, named "Compare item price" report to any format supported by data management, making the data available for use with external applications.</span></span>
<!--feature detail end -->

<span data-ttu-id="62371-125">![品目が原価グループ タイプおよび原価グループ別の内訳でフィルターされた、比較チャートの表示](media/compare-chart.png "品目が原価グループ タイプおよび原価グループ別の内訳でフィルターされた、比較チャートの表示")</span><span class="sxs-lookup"><span data-stu-id="62371-125">![View comparison chart, filtered by item with breakdown by Cost group type and Cost group](media/compare-chart.png "View comparison chart, filtered by item with breakdown by Cost group type and Cost group")</span></span>
<!-- Picture 1 -->

<span data-ttu-id="62371-126">![品目が原価グループ別の内訳でフィルターされた、品目価格の比較の格納の詳細](media/compare-details.png "品目が原価グループ別の内訳でフィルターされた、品目価格の比較の格納の詳細")</span><span class="sxs-lookup"><span data-stu-id="62371-126">![Compare item prices storage details, filtered by item with a breakdown by Cost group](media/compare-details.png "Compare item prices storage details, filtered by item with a breakdown by Cost group")</span></span>
<!-- Picture 2 -->









## <a name="see-also"></a><span data-ttu-id="62371-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="62371-127">See also</span></span>

<span data-ttu-id="62371-128">[品目価格の比較の格納レポート](https://docs.microsoft.com/dynamics365/supply-chain/cost-management/compare-item-price) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="62371-128">[Compare item prices storage report](https://docs.microsoft.com/dynamics365/supply-chain/cost-management/compare-item-price) (docs)</span></span>
