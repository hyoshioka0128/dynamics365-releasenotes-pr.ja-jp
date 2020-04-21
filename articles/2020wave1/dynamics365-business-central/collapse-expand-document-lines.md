---
title: ドキュメント行の折りたたみと展開
description: ドキュメント行の折りたたみと展開
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: 0e767ab1-14e1-e911-a812-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: ce5ec4442e71003b756643d3eb3e40e66b921048
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232949"
---
# <a name="collapse-and-expand-document-lines"></a><span data-ttu-id="7a6dc-103">ドキュメント行の折りたたみと展開</span><span class="sxs-lookup"><span data-stu-id="7a6dc-103">Collapse and expand document lines</span></span>


| <span data-ttu-id="7a6dc-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7a6dc-104">Enabled for</span></span>    |  <span data-ttu-id="7a6dc-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7a6dc-105">Public preview</span></span> | <span data-ttu-id="7a6dc-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7a6dc-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7a6dc-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="7a6dc-107">End users, automatically</span></span>|<span data-ttu-id="7a6dc-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7a6dc-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7a6dc-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7a6dc-109">Feb 1, 2020</span></span>| <span data-ttu-id="7a6dc-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7a6dc-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7a6dc-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7a6dc-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="7a6dc-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7a6dc-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7a6dc-113">ビジネス ユーザーは、データの読み取りと入力のためのワークスペースを最適化できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="7a6dc-113">Business users must be able to optimize their workspace for reading and entering data.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7a6dc-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7a6dc-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7a6dc-115">営業および購入ドキュメントやその他の同様のドキュメント ページでは、ユーザーがページのドキュメント明細セクションを折りたたむことができます。</span><span class="sxs-lookup"><span data-stu-id="7a6dc-115">On sales and purchase documents, and similar document pages, users can collapse the document lines section on the page.</span></span> <span data-ttu-id="7a6dc-116">ユーザーが管理しています。</span><span class="sxs-lookup"><span data-stu-id="7a6dc-116">Users are in control.</span></span> <span data-ttu-id="7a6dc-117">明細セクションの下のコンテンツにより多くのスペースを与えることにより、タスクを実行するときにスペースを最適化します。</span><span class="sxs-lookup"><span data-stu-id="7a6dc-117">They optimize their space as they work through a task by giving more space to the content below the lines section.</span></span> <span data-ttu-id="7a6dc-118">この機能は、実質的に、明細に完全に焦点を合わせる機能を含め、明細セクションが表示される方法が 3 つあることを意味します。</span><span class="sxs-lookup"><span data-stu-id="7a6dc-118">This feature effectively means there are now three ways in which the lines section is displayed, including the ability to focus entirely on lines.</span></span> 

<span data-ttu-id="7a6dc-119">![折りたたまれた明細セクションのある販売ドキュメント](media/collapsed-lines-on-invoice.png "折りたたまれた明細セクションのある販売ドキュメント")</span><span class="sxs-lookup"><span data-stu-id="7a6dc-119">![A sales document with collapsed lines section](media/collapsed-lines-on-invoice.png "A sales document with collapsed lines section")</span></span>

<span data-ttu-id="7a6dc-120">明細を折りたたむ機能は、カードまたはドキュメント ページのグループの外に表示されるすべての ListPart に拡張されました。</span><span class="sxs-lookup"><span data-stu-id="7a6dc-120">The ability to collapse lines has been extended to any ListPart displayed outside of a group on a Card or Document page.</span></span>   

<span data-ttu-id="7a6dc-121">同様に、ページ上の他の折りたたみ可能なコンテンツに対して、Business Central は最後の設定をデバイスに保存することで記憶します。</span><span class="sxs-lookup"><span data-stu-id="7a6dc-121">Similarly, to other collapsible content on the page, Business Central remembers your last preference by storing it on your device.</span></span>

### <a name="try-it-now"></a><span data-ttu-id="7a6dc-122">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="7a6dc-122">Try it now</span></span>
<span data-ttu-id="7a6dc-123">[こちら](https://businesscentral.dynamics.com/?page=43)でオンライン環境にログインして、請求書の明細パーツなどのパーツの折りたたみと展開を体験します。</span><span class="sxs-lookup"><span data-stu-id="7a6dc-123">Experience collapsing and expanding parts, such as the Lines part on an Invoice, by signing into your online environment [here](https://businesscentral.dynamics.com/?page=43).</span></span>  
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="7a6dc-124">フィードバック</span><span class="sxs-lookup"><span data-stu-id="7a6dc-124">Tell us what you think</span></span>
<span data-ttu-id="7a6dc-125">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="7a6dc-125">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="7a6dc-126">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="7a6dc-126">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="7a6dc-127">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="7a6dc-127">Thank you for your idea</span></span>
<span data-ttu-id="7a6dc-128">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=d8474ae2-e16b-e911-b047-0003ff688f46)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="7a6dc-128">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=d8474ae2-e16b-e911-b047-0003ff688f46).</span></span> <span data-ttu-id="7a6dc-129">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="7a6dc-129">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="7a6dc-130">関連項目</span><span class="sxs-lookup"><span data-stu-id="7a6dc-130">See also</span></span>


<!--docs start-->
<span data-ttu-id="7a6dc-131">[Business Central での作業](https://docs.microsoft.com/dynamics365/business-central/ui-work-product) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="7a6dc-131">[Working with Business Central](https://docs.microsoft.com/dynamics365/business-central/ui-work-product) (docs)</span></span>
<!--docs end-->

