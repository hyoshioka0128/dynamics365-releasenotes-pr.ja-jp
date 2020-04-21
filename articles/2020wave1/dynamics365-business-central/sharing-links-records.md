---
title: レコードへのリンクの共有
description: レコードへのリンクの共有
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: 90d4c4a7-3068-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 8f1ce627dd895aca21111be5be631a60357d6d94
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232662"
---
# <a name="sharing-links-to-records"></a><span data-ttu-id="b1637-103">レコードへのリンクの共有</span><span class="sxs-lookup"><span data-stu-id="b1637-103">Sharing links to records</span></span>


| <span data-ttu-id="b1637-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b1637-104">Enabled for</span></span>    |  <span data-ttu-id="b1637-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b1637-105">Public preview</span></span> | <span data-ttu-id="b1637-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b1637-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b1637-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="b1637-107">End users, automatically</span></span>|<span data-ttu-id="b1637-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b1637-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b1637-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b1637-109">Feb 1, 2020</span></span>| <span data-ttu-id="b1637-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b1637-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b1637-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b1637-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="b1637-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b1637-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b1637-113">ビジネス ユーザーは、しばしばビジネス データへの直接リンクをメール、Microsoft Teams チャネル、または Office 365 ドキュメントで同僚と共有する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b1637-113">Business users often need to share direct links to business data with their colleagues over email, in Microsoft Teams channels, or in Office 365 documents.</span></span> <span data-ttu-id="b1637-114">このリリースでは、レコードおよびリスト ビューへのリンクを共有する機能が強化されました。</span><span class="sxs-lookup"><span data-stu-id="b1637-114">In this release, we've strengthened the ability to share links to records and list views.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b1637-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b1637-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b1637-116">Business Central でデータを探索してナビゲートする際に、ブラウザーの URL がより頻繁に自動更新されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="b1637-116">Business Central will now automatically update the URL in your browser more frequently as you explore and navigate your data.</span></span> <span data-ttu-id="b1637-117">その結果、Web クライアントの URL を共有したりお気に入りに追加したりする必要がある場合に、現在のコンテキストに関するヒントがより多く含まれるようになります。</span><span class="sxs-lookup"><span data-stu-id="b1637-117">As a result, the web client URL includes more hints about your current context whenever you need to share it or add it to your favorites.</span></span> <span data-ttu-id="b1637-118">これはさまざまなシナリオで役立ちます。</span><span class="sxs-lookup"><span data-stu-id="b1637-118">This is beneficial in numerous scenarios:</span></span>

- <span data-ttu-id="b1637-119">リスト内のレコードにフォーカスを設定し、URL をコピーして共有するか、お気に入りに追加した場合、この URL を使用するとリスト ページに移動し、そのレコードが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="b1637-119">When you have set focus to a record in a list, copied and shared the URL, or add it to your favorites, this URL will navigate to the list page and highlight that record.</span></span>

- <span data-ttu-id="b1637-120">カードまたはドキュメント ページに移動するか**次のレコード**または**前のレコード** ボタンを使用し、URL をコピーして共有するか、お気に入りに追加した場合、この URL を使用するとそのレコードの詳細ページに移動します。</span><span class="sxs-lookup"><span data-stu-id="b1637-120">When you have navigated to a card or document page or used the **Next record** or **Previous record** buttons, copied and shared the URL (or added it to your favorites), this URL will now navigate to the details page for that record.</span></span>

- <span data-ttu-id="b1637-121">リスト ビューに移動するかビューを保存し、URL をコピーして共有するか、お気に入りに追加した場合、この URL を使用するとその特定のビューに移動します。</span><span class="sxs-lookup"><span data-stu-id="b1637-121">When you have navigated to a list view or saved a view, copied and shared the URL, or added it to your favorites, this URL will navigate to that specific view.</span></span>

- <span data-ttu-id="b1637-122">リストを操作しているときに接続が切れるかブラウザーの Web ページを再読み込みした場合、</span><span class="sxs-lookup"><span data-stu-id="b1637-122">When working with lists, you were disconnected or reloaded the browser web page.</span></span> <span data-ttu-id="b1637-123">Business Central は最後にアクセスしたビューに戻ろうと試み、中断したところから再開しやすくします。</span><span class="sxs-lookup"><span data-stu-id="b1637-123">Business Central will help you pick up where you left off by trying to return to the last view you visited.</span></span>

### <a name="try-it-now"></a><span data-ttu-id="b1637-124">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="b1637-124">Try it now</span></span>
<span data-ttu-id="b1637-125">[https://businesscentral.dynamics.com/?page=31](https://businesscentral.dynamics.com/?page=31) でオンライン環境にサインインして、さまざまな項目ビューや項目へのリンクをブラウザーのお気に入りに追加してみてください。</span><span class="sxs-lookup"><span data-stu-id="b1637-125">Have a go at adding links to different Item views or Items as browser Favorites, by signing into your online environment at [https://businesscentral.dynamics.com/?page=31](https://businesscentral.dynamics.com/?page=31).</span></span>  

<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="b1637-126">フィードバック</span><span class="sxs-lookup"><span data-stu-id="b1637-126">Tell us what you think</span></span>
<span data-ttu-id="b1637-127">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="b1637-127">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="b1637-128">フォーラム (https://aka.ms/bcIdeas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="b1637-128">Use the forum at https://aka.ms/bcIdeas.</span></span>




## <a name="see-also"></a><span data-ttu-id="b1637-129">関連項目</span><span class="sxs-lookup"><span data-stu-id="b1637-129">See also</span></span>


<!--docs start-->
<span data-ttu-id="b1637-130">[Business Central での作業](https://docs.microsoft.com/dynamics365/business-central/ui-work-product) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b1637-130">[Working with Business Central](https://docs.microsoft.com/dynamics365/business-central/ui-work-product) (docs)</span></span>
<!--docs end-->

