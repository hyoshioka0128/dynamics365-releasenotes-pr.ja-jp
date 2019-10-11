---
title: 複数ページにわたるマルチタスク
description: ユーザーはアプリケーション全体で同時に複数のページを開いて、マルチタスク処理をサポートできます。
author: kotelko
ms.reviewer: sgroespe
ms.date: 09/15/2019
ms.assetid: bc63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: c391233dab5c93a56788b220583b268590068eca
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140471"
---
# <a name="multitask-across-multiple-pages"></a><span data-ttu-id="5fc62-103">複数ページにわたるマルチタスク</span><span class="sxs-lookup"><span data-stu-id="5fc62-103">Multitask across multiple pages</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="5fc62-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="5fc62-104">Enabled for</span></span>    |  <span data-ttu-id="5fc62-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5fc62-105">Public preview</span></span> | <span data-ttu-id="5fc62-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="5fc62-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5fc62-107">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="5fc62-107">Users, automatically</span></span>|<span data-ttu-id="5fc62-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5fc62-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5fc62-109">2019 年 8 月 15 日</span><span class="sxs-lookup"><span data-stu-id="5fc62-109">Aug 15, 2019</span></span>| <span data-ttu-id="5fc62-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="5fc62-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="5fc62-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5fc62-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5fc62-112">多くの場合、Business Central ユーザーは一度に複数のタスクを処理しており、電話を受けながらアクションを実行するなど、割り込みを管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5fc62-112">Business Central users often work on multiple tasks at a time and have to manage interruptions, such as when a call comes in that they have to take action on.</span></span> <span data-ttu-id="5fc62-113">ユーザーのブロックを解除し、ブラウザー タブ/ウィンドウで同時に作業できるようにするかポップアウトでミニ ページを開くことでアイドル時間を短縮することは、これらの忙しい時間帯では非常に重要です。</span><span class="sxs-lookup"><span data-stu-id="5fc62-113">Unblocking users and shortening idle time by allowing them to work in concurrent browser tabs/windows or opening a mini page in a pop-out is very important in these busy times.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5fc62-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5fc62-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5fc62-115">このリリースでは、ユーザーは複数のページを同時に開いて、複数のタスクを同時に実行できます。</span><span class="sxs-lookup"><span data-stu-id="5fc62-115">In this release, users can open several pages at the same time to perform multiple tasks at the same time.</span></span> <span data-ttu-id="5fc62-116">新しい機能では 2 つのシナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="5fc62-116">The new functionality supports two scenarios.</span></span>

### <a name="new-browser-tab"></a><span data-ttu-id="5fc62-117">新しいブラウザー タブ</span><span class="sxs-lookup"><span data-stu-id="5fc62-117">New browser tab</span></span>
<span data-ttu-id="5fc62-118">この機能により、ユーザーは同じ会社で作業しながら複数のブラウザー タブまたはウィンドウを開くことができます。</span><span class="sxs-lookup"><span data-stu-id="5fc62-118">This functionality allows users to open several browser tabs or windows while working in the same company.</span></span> <span data-ttu-id="5fc62-119">これを行うには、ユーザーは新しいブラウザー ウィンドウを開き (Ctrl+N)、Business Central ブックマークまたはデスクトップ上のアイコンを使用して、新しいブラウザーで Business Central を開きます。</span><span class="sxs-lookup"><span data-stu-id="5fc62-119">To do this, users can open a new browser window (Ctrl+N) and then use a Business Central bookmark or an icon on the desktop to open Business Central in a new browser.</span></span> <span data-ttu-id="5fc62-120">これは、同じ会社と別の会社の両方で複数回使用しても安全です。</span><span class="sxs-lookup"><span data-stu-id="5fc62-120">This is safe to use several times, both for the same and another company.</span></span> 

<span data-ttu-id="5fc62-121">ユーザーが複数のブラウザー ウィンドウを開いている場合、それぞれが別の接続またはセッションとして機能しています。</span><span class="sxs-lookup"><span data-stu-id="5fc62-121">When a user has several browser windows open, each is acting as another connection or session.</span></span> <span data-ttu-id="5fc62-122">これは、1 人のユーザーが一度に複数のコンピューターから Business Central に接続する場合と基本的に同じように機能します。</span><span class="sxs-lookup"><span data-stu-id="5fc62-122">This works basically in the same way as if one user connects to Business Central from several computers at once.</span></span> <span data-ttu-id="5fc62-123">これらの個別のブラウザー ウィンドウを使用すると、標準のネットワーク データロック メカニズムまたはビジネス データ検証を除き、制限なしで任意の 2 つ以上のページで同時に作業できます。</span><span class="sxs-lookup"><span data-stu-id="5fc62-123">Those separate browser windows allow you to work concurrently on any two or more pages without restrictions, except for any standard network data-locking mechanism or business data validation.</span></span> <span data-ttu-id="5fc62-124">ユーザーは、さまざまなブラウザー ウィンドウを展開したり、さまざまなモニターに配置したりして、タスク間をすばやく切り替えたり、データを相互に検証したりすることもできます。</span><span class="sxs-lookup"><span data-stu-id="5fc62-124">Users can also expand the different browser windows or put them on different monitors to quickly switch between tasks or validate data against each other.</span></span>

### <a name="open-page-in-a-new-window"></a><span data-ttu-id="5fc62-125">新しいウィンドウでページを開く</span><span class="sxs-lookup"><span data-stu-id="5fc62-125">Open page in a new window</span></span>
<span data-ttu-id="5fc62-126">この機能により、ユーザーはカードまたはドキュメントを小さな接続されたウィンドウにポップアウトできます。</span><span class="sxs-lookup"><span data-stu-id="5fc62-126">This functionality allows users to pop out a card or document into a smaller, connected window.</span></span> <span data-ttu-id="5fc62-127">これを行うには、すべてのカードまたはドキュメント ページの右上隅にある**このページを新しいウィンドウで開く**ボタンを選択するか、Alt+Shift+W を押します。</span><span class="sxs-lookup"><span data-stu-id="5fc62-127">You do this by choosing the **Open this page in a new window** button in the upper-right corner of every card or document page, or by pressing Alt+Shift+W.</span></span>

<span data-ttu-id="5fc62-128">![顧客カードを新しいウィンドウで開く](media/new-window.png "顧客カードを新しいウィンドウで開く")</span><span class="sxs-lookup"><span data-stu-id="5fc62-128">![Open the customer card in a new window](media/new-window.png "Open the customer card in a new window")</span></span>

<span data-ttu-id="5fc62-129">このため、ユーザーは別のポップアウト ウィンドウでページを開くことができ、迅速かつ簡単にデータを比較できます。</span><span class="sxs-lookup"><span data-stu-id="5fc62-129">Users can thereby open a page in a separate pop-out window for quick and easy data comparison.</span></span> <span data-ttu-id="5fc62-130">これにより、複数の画面で作業する場合と、ユーザーが 1 つの画面で新しいウィンドウを重ねて配置する場合の生産性が向上します。</span><span class="sxs-lookup"><span data-stu-id="5fc62-130">This enhances productivity both when working with multiple screens and if users want to place the new windows on top of each other on one screen.</span></span>

<span data-ttu-id="5fc62-131">![ウィンドウ間でのマルチタスク](media/multitasking.png "ウィンドウ間でのマルチタスク")</span><span class="sxs-lookup"><span data-stu-id="5fc62-131">![Multitasking across windows](media/multitasking.png "Multitasking across windows")</span></span>

<span data-ttu-id="5fc62-132">この機能を使用してポップアウトされるすべてのページはメイン ページにリンクされているため、ユーザーは両方のウィンドウで更新されるデータを確認できます。</span><span class="sxs-lookup"><span data-stu-id="5fc62-132">Note that all pages that are popped out using this functionality are linked to the main page so that users can observe data being updated across both windows.</span></span> <span data-ttu-id="5fc62-133">ページは同じコンテキスト内で開かれるため、この機能は、2 つの転記された売上請求書を比較する、顧客カードを開いた状態で請求書のデータを編集する、販売注文の編集中に品目カードをポップアウトして更新するなどの同様のタスクで作業する場合により便利です。</span><span class="sxs-lookup"><span data-stu-id="5fc62-133">Since the pages are opened within the same context, this functionality is more useful when working on similar tasks, such as comparing two posted sales invoices, editing data for an invoice while having the customer card open, or popping out an item card to update it while editing a sales order.</span></span>

<!--feature detail end -->











