---
title: レポートをより効率的にフィルター処理する
description: より多くのフィルター フィールドを追加できるようにするなど、コミュニティのトップ リクエストのいくつかに対処して、レポートのフィルター処理エクスペリエンスを改善しています。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 09/12/2019
ms.assetid: b863278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: bfac591e7a0bd49dc57bfdd3debbafd13acd585b
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140405"
---
# <a name="filter-reports-more-efficiently"></a><span data-ttu-id="4db73-103">レポートをより効率的にフィルター処理する</span><span class="sxs-lookup"><span data-stu-id="4db73-103">Filter reports more efficiently</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="4db73-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="4db73-104">Enabled for</span></span>    |  <span data-ttu-id="4db73-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="4db73-105">Public preview</span></span> | <span data-ttu-id="4db73-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="4db73-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="4db73-107">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="4db73-107">Users, automatically</span></span>|<span data-ttu-id="4db73-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="4db73-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="4db73-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="4db73-109">Aug 1, 2019</span></span>| <span data-ttu-id="4db73-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="4db73-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="4db73-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="4db73-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="4db73-112">ビジネスが拡大するにつれて、データ ソースを利用するレポートも拡大します。</span><span class="sxs-lookup"><span data-stu-id="4db73-112">As the business grows, so do the data sources powering reports.</span></span> <span data-ttu-id="4db73-113">これにより、処理されるデータ量を正確に制御する必要性が高まります。</span><span class="sxs-lookup"><span data-stu-id="4db73-113">This increases the need for control over precisely how much data is processed.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="4db73-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="4db73-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="4db73-115">Business Central でレポートを実行するときは、さまざまなオプションやフィルターを指定できるリクエスト ページが表示されます。</span><span class="sxs-lookup"><span data-stu-id="4db73-115">When running a report in Business Central, users are presented with a request page where they can specify various options and filters.</span></span>

### <a name="filtering-report-data"></a><span data-ttu-id="4db73-116">レポート データのフィルター処理</span><span class="sxs-lookup"><span data-stu-id="4db73-116">Filtering report data</span></span>
<span data-ttu-id="4db73-117">以下の操作を行えるリストのフィルター処理に似た機能により、フィルター エクスペリエンスが大幅に向上しました。</span><span class="sxs-lookup"><span data-stu-id="4db73-117">The filter experience has been greatly improved with features similar to filtering lists that allow you to:</span></span>

 - <span data-ttu-id="4db73-118">ソース テーブルから任意のフィールドを選択するか、入力してフィールドをすばやく検索することにより、フィルター処理されたフィールドを好きなだけ追加します。</span><span class="sxs-lookup"><span data-stu-id="4db73-118">Add as many filtered fields as you like by choosing any field from the source table or typing to quickly find the field.</span></span>
 - <span data-ttu-id="4db73-119">ルックアップおよび類似のピッカーを使用して、複数オプション フィールド値でのフィルター処理など、フィルター値の指定に関するヘルプを入手します。</span><span class="sxs-lookup"><span data-stu-id="4db73-119">Get assistance with specifying filter values using look-ups and similar pickers, including filtering on multiple option-field values.</span></span>
 - <span data-ttu-id="4db73-120">演算子、範囲、数式、フィルター トークンを使用して、複雑なフィルターを作成します。</span><span class="sxs-lookup"><span data-stu-id="4db73-120">Create complex filters using operators, ranges, formulas, and filter tokens.</span></span>

<span data-ttu-id="4db73-121">Business Central では、適用したフィルターが記憶され、以前に行ったレポート設定から選択することもできます。</span><span class="sxs-lookup"><span data-stu-id="4db73-121">Business Central remembers the filters you applied and also allows you to choose from report settings you made earlier.</span></span>

### <a name="filtering-totals"></a><span data-ttu-id="4db73-122">合計のフィルター処理</span><span class="sxs-lookup"><span data-stu-id="4db73-122">Filtering totals</span></span>
<span data-ttu-id="4db73-123">Dynamics NAV の最も人気のある機能の 1 つをレポートにも使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4db73-123">One of the most popular features of Dynamics NAV is now also available for reports.</span></span> <span data-ttu-id="4db73-124">レポートでは、合計金額など、集計値や計算値が FlowField で表示されることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="4db73-124">Reports often display aggregated or computed values through FlowFields, such as currency amount totals.</span></span> <span data-ttu-id="4db73-125">このリリースの Business Central では、計算される値に影響する 1 つ以上のディメンションにフィルターを適用できます。</span><span class="sxs-lookup"><span data-stu-id="4db73-125">With this release, Business Central allows you to apply filters to one or more dimensions that influence computed values.</span></span>

#### <a name="consistently-powerful"></a><span data-ttu-id="4db73-126">一貫して強力</span><span class="sxs-lookup"><span data-stu-id="4db73-126">Consistently powerful</span></span>
<span data-ttu-id="4db73-127">改善されたエクスペリエンスは、RunRequestPage コマンドまたは FilterPageBuilder コマンドから生成される XMLport オブジェクトと画面だけでなく、レポート オブジェクト全体で一貫しています。</span><span class="sxs-lookup"><span data-stu-id="4db73-127">The improved experience is consistent across report objects as well as XmlPort objects and screens originating from the RunRequestPage command or FilterPageBuilder command.</span></span>

<!--feature detail end -->

<span data-ttu-id="4db73-128">![さまざまなフィルター処理されたフィールドを示す顧客レポート](media/report-3000x2000.png "さまざまなフィルター処理されたフィールドを示す顧客レポート")</span><span class="sxs-lookup"><span data-stu-id="4db73-128">![A customer report exhibiting various filtered fields](media/report-3000x2000.png "A customer report exhibiting various filtered fields")</span></span>
<!-- Picture 1 -->







## <a name="tell-us-what-you-think"></a><span data-ttu-id="4db73-129">フィードバック</span><span class="sxs-lookup"><span data-stu-id="4db73-129">Tell us what you think</span></span>
<span data-ttu-id="4db73-130">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="4db73-130">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="4db73-131">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="4db73-131">Use the forum at https://aka.ms/bcideas.</span></span>



