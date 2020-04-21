---
title: UI カスタマイズの回復性
description: UI カスタマイズの変更に対する回復性が向上します
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: a90ae6a5-851a-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 2b8540f167bb760af3293d0ea2da92a25d6611fe
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232695"
---
# <a name="resiliency-of-ui-customizations"></a><span data-ttu-id="e78de-103">UI カスタマイズの回復性</span><span class="sxs-lookup"><span data-stu-id="e78de-103">Resiliency of UI customizations</span></span>


| <span data-ttu-id="e78de-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="e78de-104">Enabled for</span></span>    |  <span data-ttu-id="e78de-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e78de-105">Public preview</span></span> | <span data-ttu-id="e78de-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="e78de-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="e78de-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="e78de-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="e78de-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e78de-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e78de-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="e78de-109">Feb 1, 2020</span></span>| <span data-ttu-id="e78de-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e78de-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e78de-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="e78de-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="e78de-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e78de-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e78de-113">管理者とサポート チームの安心感が高まります。</span><span class="sxs-lookup"><span data-stu-id="e78de-113">Increased peace of mind for administrators and support teams.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e78de-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e78de-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e78de-115">2020 年リリース ウェーブ 1 では、UI カスタマイズ機能が強化され、ユーザーのパーソナル化とロールのカスタマイズのマイナーおよびメジャー更新での変更に対する回復性が向上します。</span><span class="sxs-lookup"><span data-stu-id="e78de-115">In 2020 release wave 1, we are hardening our UI customization features to make user personalization and role customization more resilient to changes in minor and major updates.</span></span> <span data-ttu-id="e78de-116">Business Central プラットフォームとビジネス アプリケーションが時間と共に進化するにつれて、UI カスタマイズ、その対象となる UI 要素、およびその解釈方法の間のマッピングに問題が生じることがあります。</span><span class="sxs-lookup"><span data-stu-id="e78de-116">As the Business Central platform and business application evolve over time, some mappings between UI customizations, their target UI elements, and how they are interpreted become problematic.</span></span> <span data-ttu-id="e78de-117">この更新は、ユーザーに次のメリットをもたらします。</span><span class="sxs-lookup"><span data-stu-id="e78de-117">With this update users:</span></span>

 - <span data-ttu-id="e78de-118">UI カスタマイズで重大なエラーが発生した場合に、Business Central へのサインインを妨げられることがなくなる。</span><span class="sxs-lookup"><span data-stu-id="e78de-118">are no longer prevented from signing into Business Central if a severe error occurs with UI customization.</span></span>
 - <span data-ttu-id="e78de-119">環境がアップグレードされた後で問題が発生する UI カスタマイズの数が大幅に減る。</span><span class="sxs-lookup"><span data-stu-id="e78de-119">experience significantly less problematic UI customizations after their environment is upgraded.</span></span>

<span data-ttu-id="e78de-120">また、管理者には、環境内の UI カスタマイズの正常性をいつでも評価できる新しい診断ツールが提供されます。</span><span class="sxs-lookup"><span data-stu-id="e78de-120">Administrators also get a new diagnostic tool to assess the health of UI customizations in an environment at any time.</span></span> <span data-ttu-id="e78de-121">このツールを使用して、以下のトラブルシューティングを実行できます。</span><span class="sxs-lookup"><span data-stu-id="e78de-121">They use the tool to troubleshoot:</span></span>

 - <span data-ttu-id="e78de-122">ユーザーのパーソナル化。**パーソナル化されたページ** リスト (以前の*ユーザーによるページのパーソナル化*) から行います。</span><span class="sxs-lookup"><span data-stu-id="e78de-122">user personalization from the **Personalized Pages** list (formerly *User Page Personalizations*).</span></span>
 - <span data-ttu-id="e78de-123">ロールのカスタマイズ。**カスタマイズされたページ** リスト (以前の*プロファイルのカスタマイズ*) から行います。</span><span class="sxs-lookup"><span data-stu-id="e78de-123">role customization from the **Customized Pages** list (formerly *Profile Customizations*).</span></span>

<span data-ttu-id="e78de-124">問題のある UI カスタマイズがユーザーに影響を与えている場合、管理者は問題のあるページの UI カスタマイズを特定し、削除することができます。</span><span class="sxs-lookup"><span data-stu-id="e78de-124">If any problematic UI customizations are impacting users, administrators are now able to identify and delete UI customizations for the problematic page.</span></span>  

<span data-ttu-id="e78de-125">![問題をスキャンした後のカスタマイズされたページ リスト](media/troubleshoot-customization.png "問題をスキャンした後の [カスタマイズされたページ] リスト")</span><span class="sxs-lookup"><span data-stu-id="e78de-125">![The Customized Pages list after scanning for problems](media/troubleshoot-customization.png "The Customized Pages list after scanning for problems")</span></span>

### <a name="try-it-now"></a><span data-ttu-id="e78de-126">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="e78de-126">Try it now</span></span>
<span data-ttu-id="e78de-127">[https://businesscentral.dynamics.com/?page=9191](https://businesscentral.dynamics.com/?page=9191) でオンライン環境にサインインして、すべてのユーザーのパーソナル化に対して一連の診断テストを実行してみてください。</span><span class="sxs-lookup"><span data-stu-id="e78de-127">Run a series of diagnostic tests against all users' personalizations by signing into your online environment at [https://businesscentral.dynamics.com/?page=9191](https://businesscentral.dynamics.com/?page=9191).</span></span>  
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="e78de-128">フィードバック</span><span class="sxs-lookup"><span data-stu-id="e78de-128">Tell us what you think</span></span>
<span data-ttu-id="e78de-129">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="e78de-129">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="e78de-130">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="e78de-130">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="e78de-131">関連項目</span><span class="sxs-lookup"><span data-stu-id="e78de-131">See also</span></span>


<!--docs start-->
<span data-ttu-id="e78de-132">[プロファイルを管理する](https://docs.microsoft.com/dynamics365/business-central/admin-users-profiles-roles) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="e78de-132">[Manage Profiles](https://docs.microsoft.com/dynamics365/business-central/admin-users-profiles-roles) (docs)</span></span>
<!--docs end-->

