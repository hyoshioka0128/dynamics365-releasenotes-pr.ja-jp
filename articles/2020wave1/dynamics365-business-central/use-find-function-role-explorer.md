---
title: ロール エクスプローラーで検索機能を使用する
description: 検索機能により、ロール エクスプローラー使用時の機能の検索がはるかに簡単になります。
author: kotelko
ms.reviewer: jswymer
ms.date: 03/25/2020
ms.assetid: a43619a1-4e1b-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: 9f36056372a5523a9fb5b49d49c6826042a0fdfc
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232596"
---
# <a name="use-the-find-function-on-the-role-explorer"></a><span data-ttu-id="c083d-103">ロール エクスプローラーで検索機能を使用する</span><span class="sxs-lookup"><span data-stu-id="c083d-103">Use the Find function on the Role Explorer</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="c083d-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c083d-104">Enabled for</span></span>    |  <span data-ttu-id="c083d-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c083d-105">Public preview</span></span> | <span data-ttu-id="c083d-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c083d-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c083d-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="c083d-107">End users, automatically</span></span>|<span data-ttu-id="c083d-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c083d-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c083d-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c083d-109">Feb 1, 2020</span></span>| <span data-ttu-id="c083d-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="c083d-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c083d-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c083d-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c083d-112">製品の機能は、さまざまな領域の数百のオプションにわたることがあります。</span><span class="sxs-lookup"><span data-stu-id="c083d-112">Your product functions might span several hundred options across different areas.</span></span> <span data-ttu-id="c083d-113">それらをロール エクスプローラーで視覚的に見つけられると、顧客は必要なページやモジュールにより簡単に移動できるようになります。</span><span class="sxs-lookup"><span data-stu-id="c083d-113">Finding them in a visual format on the Role Explorer makes it easier for customers to navigate and go to the requested page or module.</span></span> <span data-ttu-id="c083d-114">また、ロール エクスプローラーでユーザーに検索機能が提供されることで、レポートの検索がはるかに簡単になります。</span><span class="sxs-lookup"><span data-stu-id="c083d-114">Also, finding reports is much easier now that users have a Find function in the Role Explorer.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c083d-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c083d-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c083d-116">Business Central のロール エクスプローラーで、手動によるナビゲーションとメニュー グループの展開/折りたたみを補完する新しい追加機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="c083d-116">The Business Central Role Explorer has a new addition that complements manual navigation and expanding or collapsing menu groups.</span></span> <span data-ttu-id="c083d-117">ユーザーはロール エクスプローラーを開き、検索する内容の入力を開始できます。</span><span class="sxs-lookup"><span data-stu-id="c083d-117">Users can now open the Role Explorer and start typing they're looking for.</span></span> <span data-ttu-id="c083d-118">入力した文字は、ページ上部の**検索**ボックスに表示されます。</span><span class="sxs-lookup"><span data-stu-id="c083d-118">The text they type appears in the **Find** box at the top of the page.</span></span> <span data-ttu-id="c083d-119">**検索**アクションを選択するか、F3 キーを押して、検索機能を開始することもできます。</span><span class="sxs-lookup"><span data-stu-id="c083d-119">Selecting the **Find** action or pressing F3 also starts the Find function.</span></span>

<span data-ttu-id="c083d-120">ロール エクスプローラーでは結果がフィルター処理されませんが、代わりに下の図に示すようにヒットが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="c083d-120">The Role Explorer doesn't filter the results but instead highlights the hits, as shown in the image below.</span></span> <span data-ttu-id="c083d-121">結果が折りたたまれたグループに含まれている場合は、検索機能により、そのグループに青緑色の円で注釈が付けられます。</span><span class="sxs-lookup"><span data-stu-id="c083d-121">When a result is contained in a collapsed group, the Find function annotates the group using a teal-colored circle.</span></span> <span data-ttu-id="c083d-122">ユーザーは矢印アイコンまたはキーボード キー (Ctrl + 上矢印/下矢印および F3/Shift + F3) を使用して結果を参照できます。</span><span class="sxs-lookup"><span data-stu-id="c083d-122">Users can browse through the results using arrow icons or keyboard keys (Ctrl+ArrowUp/ArrowDown and F3/Shift+F3).</span></span> <span data-ttu-id="c083d-123">**Esc** キーを押すと**検索**ボックスが閉じて入力した値が削除され、新しい検索や閲覧を開始できます。</span><span class="sxs-lookup"><span data-stu-id="c083d-123">The **Esc** key closes the **Find** box and removes the value typed, so that a new search or browsing can be started.</span></span> <span data-ttu-id="c083d-124">また、**すべて探索**ビューに切り替えると検索値が保持されるため、必要なページのナビゲートと検索がさらに簡単になります。</span><span class="sxs-lookup"><span data-stu-id="c083d-124">Also, switching to the **Explore all** view keeps the find value, making it even easier to navigate and find a necessary page.</span></span>
<!--feature detail end -->

<span data-ttu-id="c083d-125">![Business Central のロール エクスプローラーでの機能の検索](media/explorer-find.png "Business Central のロール エクスプローラーでの機能の検索")</span><span class="sxs-lookup"><span data-stu-id="c083d-125">![Find function in the Business Central Role Explorer](media/explorer-find.png "Find function in the Business Central Role Explorer")</span></span>
<!-- Picture 1 -->





## <a name="tell-us-what-you-think"></a><span data-ttu-id="c083d-126">フィードバック</span><span class="sxs-lookup"><span data-stu-id="c083d-126">Tell us what you think</span></span>
<span data-ttu-id="c083d-127">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="c083d-127">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="c083d-128">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="c083d-128">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="c083d-129">関連項目</span><span class="sxs-lookup"><span data-stu-id="c083d-129">See also</span></span>


<!--docs start-->
<span data-ttu-id="c083d-130">[ロール エクスプローラーでのページの検索](https://docs.microsoft.com/dynamics365/business-central/ui-role-explorer) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c083d-130">[Finding Pages with the Role Explorer](https://docs.microsoft.com/dynamics365/business-central/ui-role-explorer) (docs)</span></span>
<!--docs end-->

