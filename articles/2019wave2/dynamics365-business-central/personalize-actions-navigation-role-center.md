---
title: ロール センターでのアクションのパーソナライズ
description: アクションやナビゲーション メニューなど、ロール センターでより多くのコンテンツを再編成して、ワークスペースをさらにパーソナライズします。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 11/15/2019
ms.assetid: 23b6ec94-e46b-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: e7f07abe6cd0994f29673b9a97ade48ab943589d
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892022"
---
# <a name="personalize-actions-on-your-role-center"></a><span data-ttu-id="c6827-103">ロール センターでのアクションのパーソナライズ</span><span class="sxs-lookup"><span data-stu-id="c6827-103">Personalize actions on your Role Center</span></span>


| <span data-ttu-id="c6827-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c6827-104">Enabled for</span></span>    |  <span data-ttu-id="c6827-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c6827-105">Public preview</span></span> | <span data-ttu-id="c6827-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c6827-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c6827-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="c6827-107">End users, automatically</span></span>|<span data-ttu-id="c6827-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c6827-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c6827-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c6827-109">Aug 1, 2019</span></span>| <span data-ttu-id="c6827-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c6827-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c6827-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c6827-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="c6827-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c6827-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c6827-113">Business Central は、各企業、部門、ユーザーに固有のニーズに簡単に適応できます。</span><span class="sxs-lookup"><span data-stu-id="c6827-113">Business Central is ready to adapt to the unique needs of each business, department, and user.</span></span> <span data-ttu-id="c6827-114">デスクトップ ユーザーには、日常の作業や使用する最も一般的なデータをサポートするようにワークスペースを最適化するための、あらゆる機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="c6827-114">Desktop users are fully empowered to optimize their workspace to support their daily tasks and the most common data that they work with.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c6827-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c6827-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c6827-116">ナビゲーション メニューのパーソナライズには、次のものがあります。</span><span class="sxs-lookup"><span data-stu-id="c6827-116">Personalizing the navigation menu includes:</span></span>

 - <span data-ttu-id="c6827-117">メニュー リンクを同じグループ内の別の位置または異なるグループやサブグループに移動する。</span><span class="sxs-lookup"><span data-stu-id="c6827-117">Moving menu links to another position within the same group or a different group or subgroup.</span></span>
 - <span data-ttu-id="c6827-118">メニュー グループを別の位置に移動する。</span><span class="sxs-lookup"><span data-stu-id="c6827-118">Moving menu groups to another position.</span></span>
 - <span data-ttu-id="c6827-119">メニュー リンクまたはグループ全体を非表示にする。</span><span class="sxs-lookup"><span data-stu-id="c6827-119">Hiding menu links or entire groups.</span></span>
 - <span data-ttu-id="c6827-120">個人用設定をクリアして、ロール センターを元のナビゲーション メニュー レイアウトに効果的に戻す。</span><span class="sxs-lookup"><span data-stu-id="c6827-120">Clearing your personalization, effectively returning the Role Center to its original navigation menu layout.</span></span>
 
   <span data-ttu-id="c6827-121">![ナビゲーション メニューのパーソナライズ](media/personalize-navigation.png "ナビゲーション メニューのパーソナライズ")</span><span class="sxs-lookup"><span data-stu-id="c6827-121">![Personalizing the navigation menu](media/personalize-navigation.png "Personalizing the navigation menu")</span></span>

<span data-ttu-id="c6827-122">ロール センターのアクションをパーソナライズする方法は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="c6827-122">Personalizing Role Center actions includes:</span></span>

 - <span data-ttu-id="c6827-123">アクションを同じグループ内の別の位置または異なるグループに移動する。</span><span class="sxs-lookup"><span data-stu-id="c6827-123">Moving actions to another position within the same or different group.</span></span>
 - <span data-ttu-id="c6827-124">アクション グループを別の位置に移動する。</span><span class="sxs-lookup"><span data-stu-id="c6827-124">Moving action groups to another position.</span></span>
 - <span data-ttu-id="c6827-125">アクションまたはアクション グループ全体を非表示にする。</span><span class="sxs-lookup"><span data-stu-id="c6827-125">Hiding actions or entire groups of actions.</span></span>
 - <span data-ttu-id="c6827-126">アクションの個人用設定をクリアして、ロール センターを元のアクション レイアウトに効果的に戻す。</span><span class="sxs-lookup"><span data-stu-id="c6827-126">Clearing action personalization, effectively returning the Role Center to its original action layout.</span></span>

   <span data-ttu-id="c6827-127">![アクション メニューのパーソナライズ](media/personalize-actions.png "アクション メニューのパーソナライズ")</span><span class="sxs-lookup"><span data-stu-id="c6827-127">![Personalizing the action menu](media/personalize-actions.png "Personalizing the action menu")</span></span>

<span data-ttu-id="c6827-128">他のすべての個人用設定と同様に、変更はすぐに有効になり、ログインしているデバイスに関係なく、ユーザーと共に移動します。</span><span class="sxs-lookup"><span data-stu-id="c6827-128">As with all other personalization, the changes are effective immediately and roam with the user, no matter which device they sign in to.</span></span>


> [!NOTE]
> <span data-ttu-id="c6827-129">Business Central 2019 リリース ウェーブ 2 がオンプレミスに展開されると、すべての新しい個人用設定機能が既定で有効になります。</span><span class="sxs-lookup"><span data-stu-id="c6827-129">When Business Central 2019 release wave 2 is deployed on-premises, all new personalization features are enabled by default.</span></span> <span data-ttu-id="c6827-130">個人用設定はオプトイン機能ではなくなり、オンラインとオンプレミスのエクスペリエンス全体で完全に連携するようになりました。</span><span class="sxs-lookup"><span data-stu-id="c6827-130">Personalization is no longer an opt-in feature, and is now fully aligned across online and on-premises experiences.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="c6827-131">フィードバック</span><span class="sxs-lookup"><span data-stu-id="c6827-131">Tell us what you think</span></span>
<span data-ttu-id="c6827-132">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="c6827-132">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="c6827-133">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="c6827-133">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="c6827-134">関連項目</span><span class="sxs-lookup"><span data-stu-id="c6827-134">See also</span></span>

<span data-ttu-id="c6827-135">[ワークスペースのパーソナライズ](https://docs.microsoft.com/dynamics365/business-central/ui-personalization-user) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c6827-135">[Personalize Your Workspace](https://docs.microsoft.com/dynamics365/business-central/ui-personalization-user) (docs)</span></span>
