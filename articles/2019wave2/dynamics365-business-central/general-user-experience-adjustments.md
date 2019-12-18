---
title: 一般的なユーザー エクスペリエンスの調整
description: Dynamics 365 および Office 365 に対する熟知を維持する一般的なユーザー エクスペリエンスの調整。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 12/04/2019
ms.assetid: 8b58ce5a-6a6c-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 074bf1e92aaf6cdcafb38fda43d85baf544f9384
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892154"
---
# <a name="general-user-experience-adjustments"></a><span data-ttu-id="ad6eb-103">一般的なユーザー エクスペリエンスの調整</span><span class="sxs-lookup"><span data-stu-id="ad6eb-103">General user experience adjustments</span></span>


| <span data-ttu-id="ad6eb-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ad6eb-104">Enabled for</span></span>    |  <span data-ttu-id="ad6eb-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ad6eb-105">Public preview</span></span> | <span data-ttu-id="ad6eb-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ad6eb-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ad6eb-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="ad6eb-107">End users, automatically</span></span>|<span data-ttu-id="ad6eb-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ad6eb-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ad6eb-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="ad6eb-109">Aug 1, 2019</span></span>| <span data-ttu-id="ad6eb-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ad6eb-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ad6eb-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="ad6eb-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="ad6eb-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ad6eb-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ad6eb-113">ビジネス ユーザーはタスク完遂のために、生産性アプリとビジネス アプリを併用することがよくあります。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-113">Business users often work across productivity and business apps to complete their tasks.</span></span> <span data-ttu-id="ad6eb-114">アプリを行き来するとき、ユーザー エクスペリエンスの違いによりストレスが生じ、生産性が低下します。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-114">As they transition back and forth, differences in user experiences cause friction and lost productivity.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ad6eb-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ad6eb-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ad6eb-116">このアップデートでは Dynamics 365 と Office 365 で使い慣れたルック アンド フィールを維持しつつ、いっそうわかりやすいデザイン要素の追加と、ボタン、リストのヘッダー、パーツのキャプションに対する微細なスタイルの変更が行われています。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-116">Continuing our familiar look and feel across Dynamics 365 and Office 365, this update includes the addition of more fluent design elements and subtle stylistic changes to buttons, list headers, and captions on parts.</span></span>

<span data-ttu-id="ad6eb-117">行のスタイルが若干改善され、複数のレコードを選択する際の新しいインジケーターが追加されました。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-117">Rows have minor stylistic improvements and a new indicator when selecting multiple records.</span></span>

<span data-ttu-id="ad6eb-118">ブロックとして表示されるレコードの見え方やユーザービリティの問題にも対処しました。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-118">A number of aesthetic and usability issues were also addressed for records shown as bricks:</span></span>

- <span data-ttu-id="ad6eb-119">ブロックが水平方向の空きスペースに合わせて入るようになります。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-119">Bricks adapt to fill the available horizontal space.</span></span>
- <span data-ttu-id="ad6eb-120">過去のリリースでは、ブロック上の任意の場所をクリックすると、レコードの詳細にドリルダウンされることがありました。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-120">In past releases, clicking anywhere on a brick would drill down to the details of the record.</span></span> <span data-ttu-id="ad6eb-121">これには、関連する FactBox が表示されるようブロックにフォーカスを設定するためには正確にクリックする必要があるなど、さまざまな欠点がありました。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-121">This had various shortcomings such as requiring precision-clicking to set focus to the brick so that related FactBoxes can be displayed.</span></span> <span data-ttu-id="ad6eb-122">新しいクリック ターゲットにより、選択のためのクリックとドリルダウンのためのクリックがより明確に区別されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-122">New click targets now provide more clear differentiation between clicking to select and clicking to drill down.</span></span> 
- <span data-ttu-id="ad6eb-123">また、Ctrl + C キーボード ショートカットで 1 つのブロックをコピーできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-123">The Ctrl+C keyboard shortcut to copy a single brick has also been enabled.</span></span>

<span data-ttu-id="ad6eb-124">ロール センターでは、ルートレベルのアクションがアクション グループから自動的に分離されなくなります。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-124">Role Centers no longer automatically separate root-level actions from action groups.</span></span> <span data-ttu-id="ad6eb-125">コード内で定義された順序が尊重され、クライアントで各アクション領域に反映されます。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-125">The sequence in which they were defined in code is respected and reflected in the client for each action area.</span></span> <span data-ttu-id="ad6eb-126">たとえば、ロール センターでは、アクション、アクション グループ、アクションの順にアクションを表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-126">For example, on a Role Center, actions can now be displayed in the sequence of action, then action group, then action.</span></span>


<span data-ttu-id="ad6eb-127">![スタイルが変更されたブロック レイアウトのスクリーンショット](media/bricks-3000x2000.png "スタイルが変更されたブロック レイアウトのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="ad6eb-127">![A screenshot of the restyled brick layout](media/bricks-3000x2000.png "A screenshot of the restyled brick layout")</span></span>


<span data-ttu-id="ad6eb-128">![新しい行選択インジケーターを示すリスト ページのスクリーンショット](media/rows-3000x2000.png "新しい行選択インジケーターを示すリスト ページのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="ad6eb-128">![A screenshot of a list page demonstrating the new row selection indicators](media/rows-3000x2000.png "A screenshot of a list page demonstrating the new row selection indicators")</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="ad6eb-129">フィードバック</span><span class="sxs-lookup"><span data-stu-id="ad6eb-129">Tell us what you think</span></span>
<span data-ttu-id="ad6eb-130">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-130">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="ad6eb-131">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="ad6eb-131">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="ad6eb-132">関連項目</span><span class="sxs-lookup"><span data-stu-id="ad6eb-132">See also</span></span>

<span data-ttu-id="ad6eb-133">[Business Central での作業](https://docs.microsoft.com/dynamics365/business-central/ui-work-product) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="ad6eb-133">[Working with Business Central](https://docs.microsoft.com/dynamics365/business-central/ui-work-product) (docs)</span></span>
