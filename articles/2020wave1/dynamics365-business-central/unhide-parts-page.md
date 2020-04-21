---
title: ページ上のパーツの再表示
description: ページ上のパーツの再表示
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: d92d468f-14e1-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 934e59228a30ce2008869371bd1eda3386fa7c07
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232607"
---
# <a name="unhide-parts-on-a-page"></a><span data-ttu-id="7668b-103">ページ上のパーツの再表示</span><span class="sxs-lookup"><span data-stu-id="7668b-103">Unhide parts on a page</span></span>


| <span data-ttu-id="7668b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7668b-104">Enabled for</span></span>    |  <span data-ttu-id="7668b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7668b-105">Public preview</span></span> | <span data-ttu-id="7668b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7668b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7668b-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="7668b-107">End users, automatically</span></span>|<span data-ttu-id="7668b-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7668b-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7668b-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7668b-109">Feb 1, 2020</span></span>| <span data-ttu-id="7668b-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7668b-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7668b-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7668b-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="7668b-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7668b-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7668b-113">Business Central は、ユーザー、部門、または組織に固有のニーズに適応できます。</span><span class="sxs-lookup"><span data-stu-id="7668b-113">Business Central is able to adapt to the unique needs of the user, department, or organization.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7668b-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7668b-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7668b-115">ユーザーは Business Central でページをパーソナライズする際に、ページの非表示部分を表示することができます。</span><span class="sxs-lookup"><span data-stu-id="7668b-115">When personalizing pages in Business Central, users can show a hidden part on any page.</span></span> <span data-ttu-id="7668b-116">これにより、次の 2 つの一般的なシナリオに対応できます。</span><span class="sxs-lookup"><span data-stu-id="7668b-116">This unlocks two common scenarios:</span></span>

- <span data-ttu-id="7668b-117">ビジネス ユーザーは、ページをパーソナライズして、以前に非表示にした部分を元に戻すことができます。</span><span class="sxs-lookup"><span data-stu-id="7668b-117">Business users can personalize their pages and bring back a part that they have previously hidden.</span></span> <span data-ttu-id="7668b-118">同様に、パワーユーザーとコンサルタントは、以前に非表示にした部分を再表示できます。</span><span class="sxs-lookup"><span data-stu-id="7668b-118">Similarly, power users and consultants can unhide parts that they have previously hidden.</span></span>
- <span data-ttu-id="7668b-119">開発者は、ページ オブジェクト上に補助的なコンテンツを配置して非表示にすることを選択できるようになりました。これにより、顧客はそのページから簡単に開始し、ビジネス プロセスに関連する場合にはそのコンテンツの非表示を解除できます。</span><span class="sxs-lookup"><span data-stu-id="7668b-119">Developers can now choose to place secondary content on a page object and hide it, giving their customers a simple starting point with the page and the ability to unhide that content if it is relevant to their business processes.</span></span>

<span data-ttu-id="7668b-120">![非表示の部分が表示されようとしているロール センター](media/unhide-rolecenter-part.png "非表示の部分が表示されようとしているロール センター")</span><span class="sxs-lookup"><span data-stu-id="7668b-120">![The Role Center displaying a hidden part that is about to be shown](media/unhide-rolecenter-part.png "The Role Center displaying a hidden part that is about to be shown")</span></span>

<span data-ttu-id="7668b-121">ページ上で再表示できる部分の例として、次のものがあります。</span><span class="sxs-lookup"><span data-stu-id="7668b-121">Examples of parts that can be brought into view on a page:</span></span>

- <span data-ttu-id="7668b-122">ロール センターのホーム画面上の見出し</span><span class="sxs-lookup"><span data-stu-id="7668b-122">The headlines on a Role Center home screen</span></span>
- <span data-ttu-id="7668b-123">顧客リスト上の関連する詳細情報ボックス</span><span class="sxs-lookup"><span data-stu-id="7668b-123">A related details FactBox on the Customer list</span></span>
- <span data-ttu-id="7668b-124">カード ページのキャンバス上のグラフ パーツ (直接表示)</span><span class="sxs-lookup"><span data-stu-id="7668b-124">A chart part directly on the canvas of a card page</span></span>

<span data-ttu-id="7668b-125">![非表示の情報ボックスが再表示された品目リスト](media/hidden-factbox-on-items-list.png "非表示の情報ボックスが再表示された品目リスト")</span><span class="sxs-lookup"><span data-stu-id="7668b-125">![The Items list with a hidden FactBox that can now be shown](media/hidden-factbox-on-items-list.png "The Items list with a hidden FactBox that can now be shown")</span></span>   

### <a name="try-it-now"></a><span data-ttu-id="7668b-126">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="7668b-126">Try it now</span></span>
<span data-ttu-id="7668b-127">[こちら](https://businesscentral.dynamics.com/?page=22) でオンライン環境にサインインして、顧客カードなどの情報ボックスを非表示にして戻す操作をお試しください。</span><span class="sxs-lookup"><span data-stu-id="7668b-127">Experience hiding and reverting a FactBox, such as on the Customer card, by signing into your online environment [here](https://businesscentral.dynamics.com/?page=22).</span></span>  
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="7668b-128">フィードバック</span><span class="sxs-lookup"><span data-stu-id="7668b-128">Tell us what you think</span></span>
<span data-ttu-id="7668b-129">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="7668b-129">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="7668b-130">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="7668b-130">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="7668b-131">関連項目</span><span class="sxs-lookup"><span data-stu-id="7668b-131">See also</span></span>


<!--docs start-->
<span data-ttu-id="7668b-132">[ワークスペースのパーソナライズ](https://docs.microsoft.com/dynamics365/business-central/ui-personalization-user) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="7668b-132">[Personalize Your Workspace](https://docs.microsoft.com/dynamics365/business-central/ui-personalization-user) (docs)</span></span>
<!--docs end-->

