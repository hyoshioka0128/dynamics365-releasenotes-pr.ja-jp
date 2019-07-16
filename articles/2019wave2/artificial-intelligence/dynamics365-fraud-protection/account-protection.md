---
title: アカウントの保護
description: アカウント保護のためのサインアップとサインインのリスク評価
author: relnotes
ms.reviewer: v-jegrif
ms.date: 06/19/2019
ms.assetid: 75a5392d-c56d-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: amyhre
dynamics365pdf: true
ms.openlocfilehash: f12e0711424210ce29319b258b375baafe1e550b
ms.sourcegitcommit: 38a8478625bbe51d90e5b9d2af65933331c1fdb6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/02/2019
ms.locfileid: "1718910"
---
# <a name="account-protection"></a><span data-ttu-id="f730b-103">アカウントの保護</span><span class="sxs-lookup"><span data-stu-id="f730b-103">Account protection</span></span>
[!include[artificial-intelligence/dynamics365-fraud-protection banner](../includes/artificial-intelligence/dynamics365-fraud-protection.md)]

| <span data-ttu-id="f730b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f730b-104">Enabled for</span></span>    |  <span data-ttu-id="f730b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f730b-105">Public preview</span></span> | <span data-ttu-id="f730b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f730b-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="f730b-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="f730b-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="f730b-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="f730b-108">October 2019</span></span>| <span data-ttu-id="f730b-109">近日発表</span><span class="sxs-lookup"><span data-stu-id="f730b-109">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="f730b-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f730b-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f730b-111">eコマースに焦点を移す企業は、従来の実店舗での販売チャネルにはなかった新たな詐欺問題に直面しています。</span><span class="sxs-lookup"><span data-stu-id="f730b-111">As businesses shift focus to e-commerce, they are facing new fraud challenges that didn’t exist with the traditional brick-and-mortar sales channel.</span></span> <span data-ttu-id="f730b-112">この環境では、顧客アカウントを保護することがますます難しくなっています。</span><span class="sxs-lookup"><span data-stu-id="f730b-112">In this environment, protecting customer accounts is a growing challenge.</span></span> <span data-ttu-id="f730b-113">アカウントの乗っ取り (ATO) や偽のアカウントは、企業にとって金銭的損失と評判の低下につながる可能性がある詐欺ベクトルの例です。</span><span class="sxs-lookup"><span data-stu-id="f730b-113">Account Takeover (ATO) and fake accounts are examples of fraud vectors that can lead to financial and reputation loss for merchants.</span></span> <span data-ttu-id="f730b-114">Dynamics 365 Fraud Protection は、顧客のアカウントを保護するための機能を企業に提供し、既存の購入保護機能を強化します。</span><span class="sxs-lookup"><span data-stu-id="f730b-114">Dynamics 365 Fraud Protection will provide features to businesses to protect their customers' accounts and will augment existing purchase protection capabilities.</span></span>

### <a name="account-sign-in-assessment"></a><span data-ttu-id="f730b-115">アカウント ログイン評価</span><span class="sxs-lookup"><span data-stu-id="f730b-115">Account sign-in assessment</span></span>
<span data-ttu-id="f730b-116">ATO は、企業にとってますます大きな課題となっており、チャージバック レートの増加、収益の損失、評判の低下につながっています。</span><span class="sxs-lookup"><span data-stu-id="f730b-116">ATO is becoming a growing challenge for merchants, leading to increased chargeback rates, revenue loss, and reputation damage.</span></span> <span data-ttu-id="f730b-117">Dynamics 365 Fraud Protection では、エコシステム内のサインイン イベントを評価する機能、および資格情報のテストとアカウントへの不正アクセスを目的としている可能性がある不正なログイン活動を検出する機能が、企業に提供されます。</span><span class="sxs-lookup"><span data-stu-id="f730b-117">Dynamics 365 Fraud Protection will provide merchants the ability to assess sign-in events within their ecosystem and detect fraudulent sign-in activity that might be intended to test credentials and get unauthorized access to accounts.</span></span> <span data-ttu-id="f730b-118">企業は、そのような不正なログインの試みをブロックしたり、疑わしい試みに対して 2 要素認証やその他のチャレンジをトリガーしたりすることができます。</span><span class="sxs-lookup"><span data-stu-id="f730b-118">Merchants will be empowered to block such fraudulent sign-in attempts or trigger two-factor authentication or other challenges on suspicious attempts.</span></span>

### <a name="fraud-protection-network"></a><span data-ttu-id="f730b-119">不正保護ネットワーク</span><span class="sxs-lookup"><span data-stu-id="f730b-119">Fraud protection network</span></span>
<span data-ttu-id="f730b-120">Dynamics 365 Fraud Protection には、複数の企業にまたがる不正パターンを検出し、重大な損害が発生する前にそれらを防ぐことができる、既存の詐欺防止ネットワークがあります。</span><span class="sxs-lookup"><span data-stu-id="f730b-120">Dynamics 365 Fraud Protection has an existing fraud protection network that can detect fraud patterns across multiple businesses and protect them before there is any significant damage.</span></span> <span data-ttu-id="f730b-121">このネットワークでは、Dynamics 365 Fraud Protection の対象となるすべての既存と新規の詐欺シナリオに対する保護を強化するアカウント保護固有の知識がエンリッチされます。</span><span class="sxs-lookup"><span data-stu-id="f730b-121">We will enrich account protection-specific knowledge in this network that will enhance protection for all existing and new fraud scenarios covered by Dynamics 365 Fraud Protection.</span></span>
<!--feature detail end -->










