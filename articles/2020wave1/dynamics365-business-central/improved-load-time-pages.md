---
title: ページをよりすばやく開く
description: ページをよりすばやく開きます。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: c9b05388-851a-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: e16698993c0f1d5fd75686e478c3dfddef495628
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232222"
---
# <a name="pages-open-faster"></a><span data-ttu-id="f8e98-103">ページをよりすばやく開く</span><span class="sxs-lookup"><span data-stu-id="f8e98-103">Pages open faster</span></span>


| <span data-ttu-id="f8e98-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f8e98-104">Enabled for</span></span>    |  <span data-ttu-id="f8e98-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f8e98-105">Public preview</span></span> | <span data-ttu-id="f8e98-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f8e98-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f8e98-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="f8e98-107">End users, automatically</span></span>|<span data-ttu-id="f8e98-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="f8e98-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="f8e98-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="f8e98-109">Feb 1, 2020</span></span>| <span data-ttu-id="f8e98-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="f8e98-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="f8e98-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="f8e98-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="f8e98-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f8e98-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f8e98-113">ビジネス ユーザーは、タスクを完了するためにページ間を移動するとき、ページとダイアログ ボックスがすばやく読み込まれることを期待します。</span><span class="sxs-lookup"><span data-stu-id="f8e98-113">When navigating across pages to complete their tasks, business users expect snappy loading of pages and dialog boxes.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f8e98-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f8e98-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f8e98-115">ユーザーは、頻繁に使用するページが前より速く開くようになったことがわかります。</span><span class="sxs-lookup"><span data-stu-id="f8e98-115">Users will find that the pages they use often are now quicker to open.</span></span> <span data-ttu-id="f8e98-116">最初にページの構造が表示され、データが読み込まれるまでのコンテキストが示されます。</span><span class="sxs-lookup"><span data-stu-id="f8e98-116">The structure of the page is shown first, giving context until data is loaded.</span></span>

<span data-ttu-id="f8e98-117">技術的には、レンダリングされたページは、最初に開かれたときにキャッシュされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f8e98-117">Technically, the rendered page is now cached the first time it is opened.</span></span> <span data-ttu-id="f8e98-118">これを行うために、ビジネス データや機密情報がユーザーのデバイスに永続化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="f8e98-118">This is done without persisting any business data or sensitive information to the user's device.</span></span> <span data-ttu-id="f8e98-119">次にページが開いたときに、サービスから最新のデータがフェッチされている間、キャッシュからすぐにレンダリングされます。</span><span class="sxs-lookup"><span data-stu-id="f8e98-119">The next time the page opens, it will immediately render from the cache while the latest data is fetched from the service.</span></span>

- <span data-ttu-id="f8e98-120">Update 16.0 では、ユーザーのセッションの間、ページがキャッシュされます。</span><span class="sxs-lookup"><span data-stu-id="f8e98-120">In Update 16.0, pages are cached for the duration of the user's session.</span></span> <span data-ttu-id="f8e98-121">ユーザーは、ログインしたままの状態でのみ、パフォーマンス向上のメリットを得られます。</span><span class="sxs-lookup"><span data-stu-id="f8e98-121">Users will only benefit from the performance gains while they remain signed in.</span></span>
- <span data-ttu-id="f8e98-122">Update 16.1 では、セッション間でページをキャッシュすることで機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="f8e98-122">Update 16.1 improves the functionality by caching pages across sessions.</span></span> <span data-ttu-id="f8e98-123">ユーザーは、ブラウザーを閉じたりログアウトした後に再度ログインした場合にも、読み込み時間が改善されるというメリットがあります。</span><span class="sxs-lookup"><span data-stu-id="f8e98-123">Users benefit from improved load-time even when they sign in again after they close the browser or sign out.</span></span>

<span data-ttu-id="f8e98-124">サービスからのデータの取得でビジーな間、Business Central には、データがまだ読み込まれていないことを示す独特な脈動 UI 要素が表示されます。</span><span class="sxs-lookup"><span data-stu-id="f8e98-124">While it is busy fetching data from the service, Business Central displays distinctive, pulsating UI elements to indicate that data has not yet been loaded.</span></span>

<span data-ttu-id="f8e98-125">![UI には、独特の脈動視覚化要素が表示されます](media/ghosted-ui.png "UI には、独特の脈動視覚化要素が表示されます")</span><span class="sxs-lookup"><span data-stu-id="f8e98-125">![The UI displays distinctive, pulsating visual elements](media/ghosted-ui.png "The UI displays distinctive, pulsating visual elements")</span></span>

### <a name="try-it-now"></a><span data-ttu-id="f8e98-126">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="f8e98-126">Try it now</span></span>
<span data-ttu-id="f8e98-127">[こちらで](https://businesscentral.dynamics.com/?page=9301)オンライン環境にログインすることで、さまざまな売上請求書を開くときなど、ページを開く時間の向上を体験してください。</span><span class="sxs-lookup"><span data-stu-id="f8e98-127">Experience improved time to open a page, for example when opening different Sales Invoices, by signing into your online environment [here](https://businesscentral.dynamics.com/?page=9301).</span></span>  
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="f8e98-128">フィードバック</span><span class="sxs-lookup"><span data-stu-id="f8e98-128">Tell us what you think</span></span>
<span data-ttu-id="f8e98-129">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="f8e98-129">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="f8e98-130">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="f8e98-130">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="f8e98-131">関連項目</span><span class="sxs-lookup"><span data-stu-id="f8e98-131">See also</span></span>


<!--docs start-->
<span data-ttu-id="f8e98-132">[開発者向けのパフォーマンス記事](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/performance/performance-developer) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="f8e98-132">[Performance Articles For Developers](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/performance/performance-developer) (docs)</span></span>
<!--docs end-->

