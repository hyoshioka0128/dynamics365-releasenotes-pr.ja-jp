---
title: 階層メニューの実装
description: ''
author: mikebcMSFT
ms.reviewer: edupont
ms.date: 09/02/2019
ms.assetid: 9e23ce60-4abb-e911-a966-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 09cc813793a5ebd3af94bbe983ca4cc4bc1e8014
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140559"
---
# <a name="implementing-hierarchical-menus"></a><span data-ttu-id="26ed7-102">階層メニューの実装</span><span class="sxs-lookup"><span data-stu-id="26ed7-102">Implementing hierarchical menus</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="26ed7-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="26ed7-103">Enabled for</span></span>    |  <span data-ttu-id="26ed7-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="26ed7-104">Public preview</span></span> | <span data-ttu-id="26ed7-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="26ed7-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="26ed7-106">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="26ed7-106">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="26ed7-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="26ed7-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="26ed7-108">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="26ed7-108">Aug 1, 2019</span></span>| <span data-ttu-id="26ed7-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="26ed7-109">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="26ed7-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="26ed7-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="26ed7-111">アプリ開発者はしばしば、ソリューションで何ができるかをユーザーや見込顧客が理解できるようにするために、ソリューションで提供されるビジネス機能の全体的なカタログを示すように求められます。</span><span class="sxs-lookup"><span data-stu-id="26ed7-111">App developers are often asked to present the entire catalog of business functionality that is offered by their solution so that their users or prospects understand what it can do.</span></span> <span data-ttu-id="26ed7-112">同様に、再販業者は多くの場合、顧客の部署またはユーザー ロールの固有のニーズに一致する論理的なグループ化によってビジネス機能を実装したいと考えます。</span><span class="sxs-lookup"><span data-stu-id="26ed7-112">Similarly, resellers often want to implement business features by some logical grouping that matches the unique needs of their customers' departments or user roles.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="26ed7-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="26ed7-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="26ed7-114">AL では、開発者はセクション領域コントロールをさらにサブグループに分割して、より複雑なリンクの階層をナビゲーション メニュー内に作成することができます。</span><span class="sxs-lookup"><span data-stu-id="26ed7-114">In AL, developers can split the sections area control into further subgroups to create more complex hierarchies of links in the navigation menu.</span></span> <span data-ttu-id="26ed7-115">リンクから、ページ、レポート、XmlPort、Codeunit などのさまざまな AL オブジェクトを実行できます。</span><span class="sxs-lookup"><span data-stu-id="26ed7-115">Links can run a variety of AL objects including Pages, Reports, XmlPorts, and Codeunits.</span></span>

<span data-ttu-id="26ed7-116">以前のバージョンの Dynamics NAV では、メニュー スイートと部署を通じてこれを実現していました。</span><span class="sxs-lookup"><span data-stu-id="26ed7-116">In earlier versions of Dynamics NAV, this was achieved through MenuSuites and Departments.</span></span> <span data-ttu-id="26ed7-117">Business Central では、これらの新しい機能によって開発者はより充実したロール ベースのナビゲーション メニューを設計でき、ユーザーはそれを使って、他のロールが利用できる関心のある機能を探索できます。</span><span class="sxs-lookup"><span data-stu-id="26ed7-117">In Business Central, these new abilities allow developers to design richer, role-based navigation menus where users can explore functionality available to other roles that might be of interest to them.</span></span>
<!--feature detail end -->

<span data-ttu-id="26ed7-118">![一般的なナビゲーション メニューのサブグループを示したスクリーンショット](media/subgroups-3000x2000.png "一般的なナビゲーション メニューのサブグループを示したスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="26ed7-118">![A screenshot showing subgrouping of a typical navigation menu](media/subgroups-3000x2000.png "A screenshot showing subgrouping of a typical navigation menu")</span></span>
<!-- Picture 1 -->







## <a name="tell-us-what-you-think"></a><span data-ttu-id="26ed7-119">フィードバック</span><span class="sxs-lookup"><span data-stu-id="26ed7-119">Tell us what you think</span></span>
<span data-ttu-id="26ed7-120">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="26ed7-120">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="26ed7-121">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="26ed7-121">Use the forum at https://aka.ms/bcideas.</span></span>



