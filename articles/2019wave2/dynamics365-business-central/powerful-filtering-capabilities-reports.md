---
title: レポートをより効率的にフィルター処理する
description: より多くのフィルター フィールドを追加できるようにするなど、コミュニティのトップ リクエストのいくつかに対処して、レポートのフィルター処理エクスペリエンスを改善しています。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 11/15/2019
ms.assetid: b863278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: c9131442e91cb9d6a55d9513a14d06a25a838c47
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892011"
---
# <a name="filter-reports-more-efficiently"></a><span data-ttu-id="b6eee-103">レポートをより効率的にフィルター処理する</span><span class="sxs-lookup"><span data-stu-id="b6eee-103">Filter reports more efficiently</span></span>


| <span data-ttu-id="b6eee-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b6eee-104">Enabled for</span></span>    |  <span data-ttu-id="b6eee-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b6eee-105">Public preview</span></span> | <span data-ttu-id="b6eee-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b6eee-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b6eee-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="b6eee-107">End users, automatically</span></span>|<span data-ttu-id="b6eee-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b6eee-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b6eee-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b6eee-109">Aug 1, 2019</span></span>| <span data-ttu-id="b6eee-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b6eee-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b6eee-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b6eee-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="b6eee-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b6eee-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b6eee-113">ビジネスが拡大するにつれて、データ ソースを利用するレポートも拡大します。</span><span class="sxs-lookup"><span data-stu-id="b6eee-113">As the business grows, so do the data sources powering reports.</span></span> <span data-ttu-id="b6eee-114">これにより、処理されるデータ量を正確に制御する必要性が高まります。</span><span class="sxs-lookup"><span data-stu-id="b6eee-114">This increases the need for control over precisely how much data is processed.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b6eee-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b6eee-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b6eee-116">Business Central でレポートを実行するときは、さまざまなオプションやフィルターを指定できるリクエスト ページが表示されます。</span><span class="sxs-lookup"><span data-stu-id="b6eee-116">When running a report in Business Central, users are presented with a request page where they can specify various options and filters.</span></span>

### <a name="filtering-report-data"></a><span data-ttu-id="b6eee-117">レポート データのフィルター処理</span><span class="sxs-lookup"><span data-stu-id="b6eee-117">Filtering report data</span></span>
<span data-ttu-id="b6eee-118">以下の操作を行えるリストのフィルター処理に似た機能により、フィルター エクスペリエンスが大幅に向上しました。</span><span class="sxs-lookup"><span data-stu-id="b6eee-118">The filter experience has been greatly improved with features similar to filtering lists that allow you to:</span></span>

- <span data-ttu-id="b6eee-119">ソース テーブルから任意のフィールドを選択するか、入力してフィールドをすばやく検索することにより、フィルター処理されたフィールドを好きなだけ追加します。</span><span class="sxs-lookup"><span data-stu-id="b6eee-119">Add as many filtered fields as you like by choosing any field from the source table or typing to quickly find the field.</span></span>
- <span data-ttu-id="b6eee-120">ルックアップおよび類似のピッカーを使用して、複数オプション フィールド値でのフィルター処理など、フィルター値の指定に関するヘルプを入手します。</span><span class="sxs-lookup"><span data-stu-id="b6eee-120">Get assistance with specifying filter values using look-ups and similar pickers, including filtering on multiple option-field values.</span></span>
- <span data-ttu-id="b6eee-121">演算子、範囲、数式、フィルター トークンを使用して、複雑なフィルターを作成します。</span><span class="sxs-lookup"><span data-stu-id="b6eee-121">Create complex filters using operators, ranges, formulas, and filter tokens.</span></span>

<span data-ttu-id="b6eee-122">Business Central では、適用したフィルターが記憶され、以前に行ったレポート設定から選択することもできます。</span><span class="sxs-lookup"><span data-stu-id="b6eee-122">Business Central remembers the filters you applied and also allows you to choose from report settings you made earlier.</span></span>

### <a name="filtering-totals"></a><span data-ttu-id="b6eee-123">合計のフィルター処理</span><span class="sxs-lookup"><span data-stu-id="b6eee-123">Filtering totals</span></span>
<span data-ttu-id="b6eee-124">Dynamics NAV の最も人気のある機能の 1 つをレポートにも使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="b6eee-124">One of the most popular features of Dynamics NAV is now also available for reports.</span></span> <span data-ttu-id="b6eee-125">レポートでは、合計金額など、集計値や計算値が FlowField で表示されることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="b6eee-125">Reports often display aggregated or computed values through FlowFields, such as currency amount totals.</span></span> <span data-ttu-id="b6eee-126">このリリースの Business Central では、計算される値に影響する 1 つ以上のディメンションにフィルターを適用できます。</span><span class="sxs-lookup"><span data-stu-id="b6eee-126">With this release, Business Central allows you to apply filters to one or more dimensions that influence computed values.</span></span>

#### <a name="consistently-powerful"></a><span data-ttu-id="b6eee-127">一貫して強力</span><span class="sxs-lookup"><span data-stu-id="b6eee-127">Consistently powerful</span></span>
<span data-ttu-id="b6eee-128">改善されたエクスペリエンスは、RunRequestPage コマンドまたは FilterPageBuilder コマンドから生成される XMLport オブジェクトと画面だけでなく、レポート オブジェクト全体で一貫しています。</span><span class="sxs-lookup"><span data-stu-id="b6eee-128">The improved experience is consistent across report objects as well as XmlPort objects and screens originating from the RunRequestPage command or FilterPageBuilder command.</span></span>

<!--feature detail end -->

<span data-ttu-id="b6eee-129">![さまざまなフィルター処理されたフィールドを示す顧客レポート](media/report-3000x2000.png "さまざまなフィルター処理されたフィールドを示す顧客レポート")</span><span class="sxs-lookup"><span data-stu-id="b6eee-129">![A customer report exhibiting various filtered fields](media/report-3000x2000.png "A customer report exhibiting various filtered fields")</span></span>
<!-- Picture 1 -->





## <a name="tell-us-what-you-think"></a><span data-ttu-id="b6eee-130">フィードバック</span><span class="sxs-lookup"><span data-stu-id="b6eee-130">Tell us what you think</span></span>
<span data-ttu-id="b6eee-131">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="b6eee-131">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="b6eee-132">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="b6eee-132">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="b6eee-133">関連項目</span><span class="sxs-lookup"><span data-stu-id="b6eee-133">See also</span></span>
<span data-ttu-id="b6eee-134">[機能の探索](https://aka.ms/ROGBC19RW2ROV9) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="b6eee-134">[Feature exploration](https://aka.ms/ROGBC19RW2ROV9) (video)</span></span>

<span data-ttu-id="b6eee-135">[レポート、バッチ ジョブ、XMLport でフィルターを設定する](https://docs.microsoft.com/dynamics365/business-central/ui-enter-criteria-filters#setting-filters-in-reports-batch-jobs-and-xmlports) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b6eee-135">[Setting Filters in Reports, Batch Jobs, and XMLports](https://docs.microsoft.com/dynamics365/business-central/ui-enter-criteria-filters#setting-filters-in-reports-batch-jobs-and-xmlports) (docs)</span></span>
