---
title: ページ上のスペースの最適化された使用
description: ページ上のスペースの最適化された使用
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: f4392522-13cb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 8cf205007d94d1003d23dc0db7ff1a5def24be65
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232167"
---
# <a name="optimized-use-of-space-on-a-page"></a><span data-ttu-id="5c97a-103">ページ上のスペースの最適化された使用</span><span class="sxs-lookup"><span data-stu-id="5c97a-103">Optimized use of space on a page</span></span>


| <span data-ttu-id="5c97a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="5c97a-104">Enabled for</span></span>    |  <span data-ttu-id="5c97a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5c97a-105">Public preview</span></span> | <span data-ttu-id="5c97a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="5c97a-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5c97a-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="5c97a-107">End users, automatically</span></span>|<span data-ttu-id="5c97a-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5c97a-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5c97a-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5c97a-109">Feb 1, 2020</span></span>| <span data-ttu-id="5c97a-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5c97a-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5c97a-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5c97a-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="5c97a-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5c97a-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5c97a-113">一部のビジネス タスクには、タスクの性質とタスクに関連したデータの量を反映した高度な画面レイアウトが必要です。</span><span class="sxs-lookup"><span data-stu-id="5c97a-113">Some business tasks require advanced screen layouts that reflect the nature of the task and the volume of data associated with the task.</span></span> <span data-ttu-id="5c97a-114">高度に最適化されたレイアウトを使用することで、ユーザーはデータの最適な概要を取得して迅速な意思決定と行動が可能になり、タスクを完了するためのスクロールやナビゲートの必要性が減少します。</span><span class="sxs-lookup"><span data-stu-id="5c97a-114">By having highly optimized layouts, users get the best overview of their data to quickly make decisions and act, reducing the need to scroll and navigate to get the task done.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5c97a-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5c97a-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5c97a-116">**複数の部分で構成されるページの改善**</span><span class="sxs-lookup"><span data-stu-id="5c97a-116">**Improvements to pages composed of multiple parts**</span></span>

<span data-ttu-id="5c97a-117">デスクトップ クライアントには、ListParts や CardParts などの複数のパーツで構成されるページ オブジェクトの完全なサポートが追加されます。</span><span class="sxs-lookup"><span data-stu-id="5c97a-117">The desktop client adds full support for page objects that are composed of multiple parts, such as ListParts or CardParts.</span></span> <span data-ttu-id="5c97a-118">この機能は、Role Center または FactBox ペインでは既に可能でした。</span><span class="sxs-lookup"><span data-stu-id="5c97a-118">This capability was already possible on a Role Center or FactBox pane.</span></span> <span data-ttu-id="5c97a-119">しかし、他のページ タイプのキャンバスは、他のコンテンツと一緒にパーツを表示するのに最適ではなかったため、UI 要素が重複したり、データに到達できなかったりしました。</span><span class="sxs-lookup"><span data-stu-id="5c97a-119">But the canvas of other page types wasn't optimal for displaying parts alongside other content, resulting in overlapping UI elements or unreachable data.</span></span>

<span data-ttu-id="5c97a-120">開発者は、予測可能な結果を提供する事前定義された AL パターンから選択することで、ページを実装できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5c97a-120">Developers are now able to implement pages by choosing from prescribed AL patterns that give predictable outcomes.</span></span> <span data-ttu-id="5c97a-121">たとえば、ListPlus ページに 2 つのリストを並べて表示できます。</span><span class="sxs-lookup"><span data-stu-id="5c97a-121">For example, they can display two lists side by side on a ListPlus page.</span></span> <span data-ttu-id="5c97a-122">または、ドキュメント ページで複数の依存リストを重ねて表示します。</span><span class="sxs-lookup"><span data-stu-id="5c97a-122">Or, have multiple dependent lists shown above each other on a Document page.</span></span> <span data-ttu-id="5c97a-123">これらの制御パターンを既に使用しているページは、追加の開発作業を必要とせずに、自動的にこの変更の恩恵を受けます。</span><span class="sxs-lookup"><span data-stu-id="5c97a-123">Pages already using these control patterns will automatically benefit from this change with no further development effort needed.</span></span>

- <span data-ttu-id="5c97a-124">**2020 年 4 月に利用可能**: リスト ページ、ドキュメント ページ、カード ページ、および ListPlus ページで使用される ListPart の最適化。</span><span class="sxs-lookup"><span data-stu-id="5c97a-124">**Available April 2020**: Optimizations for ListParts as used on List pages, Document pages, Card pages, and ListPlus pages.</span></span>
- <span data-ttu-id="5c97a-125">**2020 年 4 月以降に利用可能**: ワークシート ページで使用される ListPart と、さまざまなページ タイプで使用される CardPart の最適化。</span><span class="sxs-lookup"><span data-stu-id="5c97a-125">**Available after April 2020**: Optimizations for ListParts as used on Worksheet pages, and CardParts as used on various page types.</span></span>

<span data-ttu-id="5c97a-126">![複数の ListPart を表示する ListPlus ページの例](media/listplus-example-demonstrating-multiple-lists.png "複数の ListPart を表示する ListPlus ページの例")</span><span class="sxs-lookup"><span data-stu-id="5c97a-126">![Example ListPlus page displaying multiple ListParts](media/listplus-example-demonstrating-multiple-lists.png "Example ListPlus page displaying multiple ListParts")</span></span>

<span data-ttu-id="5c97a-127">**画面上のコンテンツの増加**</span><span class="sxs-lookup"><span data-stu-id="5c97a-127">**More content on screen**</span></span>

- <span data-ttu-id="5c97a-128">ユーザーが画面全体にページを表示すると、ページ キャプションがコンパクトになり、サイドのグレースペースが減少するというメリットがあります。</span><span class="sxs-lookup"><span data-stu-id="5c97a-128">When users display a page wide across the screen, they'll benefit from more compact page captions and reduced gray-space along the sides.</span></span> <span data-ttu-id="5c97a-129">例として、基本的なリスト ページを取り上げます。</span><span class="sxs-lookup"><span data-stu-id="5c97a-129">Take a basic list page as an example.</span></span> <span data-ttu-id="5c97a-130">Business Central Web クライアントの過去のバージョンと比較して、コンテンツ用に約 15% の左右の間隔と 5% の上下の間隔が確保されます。</span><span class="sxs-lookup"><span data-stu-id="5c97a-130">Compared to past versions of the Business Central Web client, it gains approximately 15% horizontal space and 5% vertical space for content.</span></span> <span data-ttu-id="5c97a-131">これらの確保により、さらに 2 列と 1 行が表示されます。</span><span class="sxs-lookup"><span data-stu-id="5c97a-131">These gains result in two more columns and one more row being displayed.</span></span>
- <span data-ttu-id="5c97a-132">キャプションが指定されていない FastTab は、ページの構造を定義するグループとして扱われます。</span><span class="sxs-lookup"><span data-stu-id="5c97a-132">FastTabs with no specified caption are treated as groups that define the structure of a page.</span></span> <span data-ttu-id="5c97a-133">その結果、"キャプションのない" FastTab は空白が減らされ、ユーザーが折りたたむことができなくなります。</span><span class="sxs-lookup"><span data-stu-id="5c97a-133">As a result, "caption-less" FastTabs have reduced whitespace and can no longer be collapsed by users.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="5c97a-134">フィードバック</span><span class="sxs-lookup"><span data-stu-id="5c97a-134">Tell us what you think</span></span>
<span data-ttu-id="5c97a-135">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="5c97a-135">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="5c97a-136">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="5c97a-136">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="5c97a-137">関連項目</span><span class="sxs-lookup"><span data-stu-id="5c97a-137">See also</span></span>


<!--docs start-->
<span data-ttu-id="5c97a-138">[パーツの概要](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-designing-parts) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="5c97a-138">[Parts overview](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-designing-parts) (docs)</span></span>
<!--docs end-->

