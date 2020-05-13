---
title: 階層メニューの実装
description: 新しい機能によって開発者はより充実したロール ベースのナビゲーション メニューを設計でき、ユーザーはそれを使って、他のロールで利用できる機能を探索できます。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/08/2020
ms.assetid: 9e23ce60-4abb-e911-a966-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 8b306f0d4f03f00977a8e229e9335391c6ea2cee
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320536"
---
# <a name="implementing-hierarchical-menus"></a><span data-ttu-id="5506a-103">階層メニューの実装</span><span class="sxs-lookup"><span data-stu-id="5506a-103">Implementing hierarchical menus</span></span>


| <span data-ttu-id="5506a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="5506a-104">Enabled for</span></span>    |  <span data-ttu-id="5506a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5506a-105">Public preview</span></span> | <span data-ttu-id="5506a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="5506a-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5506a-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="5506a-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="5506a-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5506a-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5506a-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5506a-109">Aug 1, 2019</span></span>| <span data-ttu-id="5506a-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5506a-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5506a-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5506a-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="5506a-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5506a-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5506a-113">アプリ開発者は、ソリューションでできることをユーザーや見込顧客が理解できるように、ソリューションで提供されるビジネス機能の全体的なカタログを示すように求められることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="5506a-113">App developers are often asked to present the entire catalog of business functionality that is offered by their solution so that their users or prospects understand what it can do.</span></span> <span data-ttu-id="5506a-114">同様に、再販業者は多くの場合、顧客の部署またはユーザー ロールの固有のニーズに一致する論理的なグループ化によってビジネス機能を実装したいと考えます。</span><span class="sxs-lookup"><span data-stu-id="5506a-114">Similarly, resellers often want to implement business features by some logical grouping that matches the unique needs of their customers' departments or user roles.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5506a-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5506a-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5506a-116">AL では、開発者はセクション領域コントロールをさらにサブグループに分割して、より複雑なリンクの階層をナビゲーション メニュー内に作成することができます。</span><span class="sxs-lookup"><span data-stu-id="5506a-116">In AL, developers can split the sections area control into further subgroups to create more complex hierarchies of links in the navigation menu.</span></span> <span data-ttu-id="5506a-117">リンクから、ページ、レポート、XmlPort、Codeunit などのさまざまな AL オブジェクトを実行できます。</span><span class="sxs-lookup"><span data-stu-id="5506a-117">Links can run a variety of AL objects including Pages, Reports, XmlPorts, and Codeunits.</span></span>

<span data-ttu-id="5506a-118">以前のバージョンの Dynamics NAV では、メニュー スイートと部署を通じてこれを実現していました。</span><span class="sxs-lookup"><span data-stu-id="5506a-118">In earlier versions of Dynamics NAV, this was achieved through MenuSuites and Departments.</span></span> <span data-ttu-id="5506a-119">Business Central では、これらの新しい機能によって開発者はより充実したロール ベースのナビゲーション メニューを設計でき、ユーザーはそれを使って、他のロールが利用できる関心のある機能を探索できます。</span><span class="sxs-lookup"><span data-stu-id="5506a-119">In Business Central, these new abilities allow developers to design richer, role-based navigation menus where users can explore functionality available to other roles that might be of interest to them.</span></span>

<span data-ttu-id="5506a-120">![一般的なナビゲーション メニューのサブグループ化](media/subgroups-3000x2000.png "一般的なナビゲーション メニューのサブグループ化")</span><span class="sxs-lookup"><span data-stu-id="5506a-120">![A subgrouping of a typical navigation menu](media/subgroups-3000x2000.png "A subgrouping of a typical navigation menu")</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="5506a-121">フィードバック</span><span class="sxs-lookup"><span data-stu-id="5506a-121">Tell us what you think</span></span>
<span data-ttu-id="5506a-122">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="5506a-122">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="5506a-123">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="5506a-123">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="5506a-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="5506a-124">See also</span></span>

<!--docs start-->
<span data-ttu-id="5506a-125">[ページへのアクションの追加](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-adding-actions-to-a-page) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="5506a-125">[Adding Actions to a Page](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-adding-actions-to-a-page) (docs)</span></span>
<!--docs end-->
