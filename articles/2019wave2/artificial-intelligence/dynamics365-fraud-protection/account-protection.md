---
title: アカウントの保護
description: アカウント保護のためのサインアップとサインインのリスク評価
author: relnotes
ms.reviewer: v-jegrif
ms.date: 10/07/2019
ms.assetid: 75a5392d-c56d-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: amyhre
dynamics365pdf: true
ms.openlocfilehash: 065fb381cbf39c7a063e388859f1b1e9d47a1a53
ms.sourcegitcommit: b0fef00d4f04f2507056a10ecce699767c669119
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2661611"
---
# <a name="account-protection"></a><span data-ttu-id="ac7a7-103">アカウントの保護</span><span class="sxs-lookup"><span data-stu-id="ac7a7-103">Account protection</span></span>
[!include[artificial-intelligence/dynamics365-fraud-protection banner](../includes/artificial-intelligence/dynamics365-fraud-protection.md)]

| <span data-ttu-id="ac7a7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ac7a7-104">Enabled for</span></span>    |  <span data-ttu-id="ac7a7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ac7a7-105">Public preview</span></span> | <span data-ttu-id="ac7a7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ac7a7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ac7a7-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="ac7a7-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ac7a7-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ac7a7-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ac7a7-109">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="ac7a7-109">Oct 1, 2019</span></span>| <span data-ttu-id="ac7a7-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="ac7a7-110">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="ac7a7-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ac7a7-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ac7a7-112">企業が eコマースに重点を移すにつれて、従来の実店舗での販売チャネルにはなかった新たな詐欺問題に直面しています。</span><span class="sxs-lookup"><span data-stu-id="ac7a7-112">As businesses shift focus to e-commerce, they are facing new fraud challenges that didn’t exist with the traditional brick-and-mortar sales channel.</span></span> <span data-ttu-id="ac7a7-113">このような環境において、顧客アカウントを保護することはますます難しくなっています。</span><span class="sxs-lookup"><span data-stu-id="ac7a7-113">In this environment, protecting customer accounts is a growing challenge.</span></span> <span data-ttu-id="ac7a7-114">アカウントの乗っ取り (ATO) は、企業にとって金銭的損失と評判の低下につながる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="ac7a7-114">Account Takeover (ATO) can lead to financial and reputation loss for merchants.</span></span> <span data-ttu-id="ac7a7-115">Dynamics 365 Fraud Protection は、顧客のアカウントを保護するための機能を企業に提供し、既存の購入保護機能を強化します。</span><span class="sxs-lookup"><span data-stu-id="ac7a7-115">Dynamics 365 Fraud Protection will provide features to businesses to protect their customers' accounts and will augment existing purchase protection capabilities.</span></span>

### <a name="account-sign-in-assessment"></a><span data-ttu-id="ac7a7-116">アカウント ログイン評価</span><span class="sxs-lookup"><span data-stu-id="ac7a7-116">Account sign-in assessment</span></span>
<span data-ttu-id="ac7a7-117">ATO は、企業にとってますます大きな課題となっており、チャージバック レートの増加、収益の損失、評判の低下につながっています。</span><span class="sxs-lookup"><span data-stu-id="ac7a7-117">ATO is becoming a growing challenge for merchants, leading to increased chargeback rates, revenue loss, and reputation damage.</span></span> <span data-ttu-id="ac7a7-118">Dynamics 365 Fraud Protection では、エコシステム内のサインイン イベントを評価する機能、および資格情報のテストやアカウントへの不正アクセスを目的としている可能性がある不正なログイン活動を検出する機能が、企業に提供されます。</span><span class="sxs-lookup"><span data-stu-id="ac7a7-118">Dynamics 365 Fraud Protection will provide merchants the ability to assess sign-in events within their ecosystem and detect fraudulent sign-in activity that might be intended to test credentials and get unauthorized access to accounts.</span></span> <span data-ttu-id="ac7a7-119">企業は受け取った ATO 評価スコアを利用して、そのような不正なログインの試みをブロックしたり、疑わしい試みに 2 要素認証やその他の対策をトリガーしたりすることができます。</span><span class="sxs-lookup"><span data-stu-id="ac7a7-119">Merchants will receive an ATO assessment score that they can leverage to block such fraudulent sign-in attempts or trigger two-factor authentication or other challenges on suspicious attempts.</span></span>

### <a name="fraud-protection-network"></a><span data-ttu-id="ac7a7-120">詐欺防止ネットワーク</span><span class="sxs-lookup"><span data-stu-id="ac7a7-120">Fraud protection network</span></span>
<span data-ttu-id="ac7a7-121">Dynamics 365 Fraud Protection には、複数の企業にまたがる不正パターンを検出し、重大な損害が発生する前にそれらを防ぐことができる、既存の詐欺防止ネットワークがあります。</span><span class="sxs-lookup"><span data-stu-id="ac7a7-121">Dynamics 365 Fraud Protection has an existing fraud protection network that can detect fraud patterns across multiple businesses and protect them before there is any significant damage.</span></span> <span data-ttu-id="ac7a7-122">このネットワークでは、Dynamics 365 Fraud Protection の対象となるすべての既存と新規の詐欺シナリオに対する保護を強化するアカウント保護固有の知識がエンリッチされます。</span><span class="sxs-lookup"><span data-stu-id="ac7a7-122">We will enrich account protection-specific knowledge in this network that will enhance protection for all existing and new fraud scenarios covered by Dynamics 365 Fraud Protection.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="ac7a7-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="ac7a7-123">See also</span></span>

<span data-ttu-id="ac7a7-124">[アカウントの保護](https://docs.microsoft.com/en-us/dynamics365/fraud-protection/account-protection) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="ac7a7-124">[Account protection](https://docs.microsoft.com/en-us/dynamics365/fraud-protection/account-protection) (docs)</span></span>
