---
title: 階層メニューの実装
description: ''
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 09/25/2019
ms.assetid: 9e23ce60-4abb-e911-a966-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: f14b63255c893e0a24a1db252e9b826c40a3df11
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2667347"
---
# <a name="implementing-hierarchical-menus"></a><span data-ttu-id="807b9-102">階層メニューの実装</span><span class="sxs-lookup"><span data-stu-id="807b9-102">Implementing hierarchical menus</span></span>


| <span data-ttu-id="807b9-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="807b9-103">Enabled for</span></span>    |  <span data-ttu-id="807b9-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="807b9-104">Public preview</span></span> | <span data-ttu-id="807b9-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="807b9-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="807b9-106">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="807b9-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="807b9-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="807b9-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="807b9-108">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="807b9-108">Aug 1, 2019</span></span>| <span data-ttu-id="807b9-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="807b9-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="807b9-110">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="807b9-110">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="807b9-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="807b9-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="807b9-112">アプリ開発者は、ソリューションでできることをユーザーや見込顧客が理解できるように、ソリューションで提供されるビジネス機能の全体的なカタログを示すように求められることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="807b9-112">App developers are often asked to present the entire catalog of business functionality that is offered by their solution so that their users or prospects understand what it can do.</span></span> <span data-ttu-id="807b9-113">同様に、再販業者は多くの場合、顧客の部署またはユーザー ロールの固有のニーズに一致する論理的なグループ化によってビジネス機能を実装したいと考えます。</span><span class="sxs-lookup"><span data-stu-id="807b9-113">Similarly, resellers often want to implement business features by some logical grouping that matches the unique needs of their customers' departments or user roles.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="807b9-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="807b9-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="807b9-115">AL では、開発者はセクション領域コントロールをさらにサブグループに分割して、より複雑なリンクの階層をナビゲーション メニュー内に作成することができます。</span><span class="sxs-lookup"><span data-stu-id="807b9-115">In AL, developers can split the sections area control into further subgroups to create more complex hierarchies of links in the navigation menu.</span></span> <span data-ttu-id="807b9-116">リンクから、ページ、レポート、XmlPort、Codeunit などのさまざまな AL オブジェクトを実行できます。</span><span class="sxs-lookup"><span data-stu-id="807b9-116">Links can run a variety of AL objects including Pages, Reports, XmlPorts, and Codeunits.</span></span>

<span data-ttu-id="807b9-117">以前のバージョンの Dynamics NAV では、メニュー スイートと部署を通じてこれを実現していました。</span><span class="sxs-lookup"><span data-stu-id="807b9-117">In earlier versions of Dynamics NAV, this was achieved through MenuSuites and Departments.</span></span> <span data-ttu-id="807b9-118">Business Central では、これらの新しい機能によって開発者はより充実したロール ベースのナビゲーション メニューを設計でき、ユーザーはそれを使って、他のロールが利用できる関心のある機能を探索できます。</span><span class="sxs-lookup"><span data-stu-id="807b9-118">In Business Central, these new abilities allow developers to design richer, role-based navigation menus where users can explore functionality available to other roles that might be of interest to them.</span></span>

<span data-ttu-id="807b9-119">![一般的なナビゲーション メニューのサブグループを示したスクリーンショット](media/subgroups-3000x2000.png "一般的なナビゲーション メニューのサブグループを示したスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="807b9-119">![A screenshot showing subgrouping of a typical navigation menu](media/subgroups-3000x2000.png "A screenshot showing subgrouping of a typical navigation menu")</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="807b9-120">フィードバック</span><span class="sxs-lookup"><span data-stu-id="807b9-120">Tell us what you think</span></span>
<span data-ttu-id="807b9-121">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="807b9-121">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="807b9-122">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="807b9-122">Use the forum at https://aka.ms/bcideas.</span></span>



