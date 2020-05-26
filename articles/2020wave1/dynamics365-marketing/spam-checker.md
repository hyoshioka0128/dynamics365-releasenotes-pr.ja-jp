---
title: スパム チェッカー
description: 送信する前に電子メールのスパム リスクを評価します
author: relnotes
ms.reviewer: alfergus
ms.date: 04/13/2020
ms.assetid: 5139080d-6548-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: gagatera
dynamics365pdf: true
ms.openlocfilehash: bb520b4f46fb61d071be2132f128090d6e04329a
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3272864"
---
# <a name="spam-checker"></a><span data-ttu-id="79460-103">スパム チェッカー</span><span class="sxs-lookup"><span data-stu-id="79460-103">Spam checker</span></span>


| <span data-ttu-id="79460-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="79460-104">Enabled for</span></span>    |  <span data-ttu-id="79460-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="79460-105">Public preview</span></span> | <span data-ttu-id="79460-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="79460-106">Early access</span></span> | <span data-ttu-id="79460-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="79460-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="79460-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="79460-108">End users by admins, makers, or analysts</span></span>|-|-| <span data-ttu-id="79460-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="79460-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="79460-110">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="79460-110">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="79460-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="79460-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="79460-112">スパム チェッカーにより、マーケティング担当者は、電子メール コンテンツの AI ベースの評価 (スパム スコア) を提供し、スパム スコアを最小化する方法を提案することにより、電子メールによる顧客エンゲージメントを最大化できます。</span><span class="sxs-lookup"><span data-stu-id="79460-112">Spam checker allows marketers to maximize customer engagement with their emails by providing an AI-based assessment of the email content (a spam score) and suggesting ways to minimize the spam score.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="79460-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="79460-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="79460-114">現在、マーケティング担当者には、電子メール キャンペーンが顧客の受信トレイに届くのか、スパムと見なされるのかがわかりません。</span><span class="sxs-lookup"><span data-stu-id="79460-114">Today, marketers don't know if their email campaigns will land in a customer’s inbox or be flagged as spam.</span></span> <span data-ttu-id="79460-115">Dynamics 365 Marketing の新しいスパム チェッカー機能を使用すると、マーケティング担当者は、スパムと見なされる原因となる可能性のある電子メール コンテンツの問題を診断および軽減できます。</span><span class="sxs-lookup"><span data-stu-id="79460-115">The new spam checker feature in Dynamics 365 Marketing enables marketers to diagnose and mitigate any issues with email content that could potentially cause it to be flagged as spam.</span></span> <span data-ttu-id="79460-116">スパム チェッカー機能は、修正可能な内容について規範となるガイダンスも提供します。</span><span class="sxs-lookup"><span data-stu-id="79460-116">The spam checker feature also provides prescriptive guidance on what can be fixed.</span></span> <span data-ttu-id="79460-117">この機能を使用すると、マーケティング担当者は自信を持って電子メールを作成し、キャンペーンに使用できると同時に、電子メールが顧客の受信トレイに届く可能性を最大限に高めることができます。</span><span class="sxs-lookup"><span data-stu-id="79460-117">With this feature, marketers can confidently create emails and use them for campaigns, while maximizing the chance that emails will land in their customers’ inboxes.</span></span>

<span data-ttu-id="79460-118">スパム チェッカーでは、以下のことができます。</span><span class="sxs-lookup"><span data-stu-id="79460-118">Spam checker enables you to:</span></span>

- <span data-ttu-id="79460-119">**スパム リスクを評価する**: 高、中、低のリスク評価スコアを使用して、電子メールがスパム フィルターに捕捉される可能性を判断します。</span><span class="sxs-lookup"><span data-stu-id="79460-119">**Assess spam risk**: Determine how likely it is for an email to be caught by spam filters through a risk assessment score of high, medium, or low.</span></span>
- <span data-ttu-id="79460-120">**レコメンデーションを取得する**: スパム スコアを改善し、電子メールが受信者の受信トレイに届く可能性を高めるために必要な変更を確認します。</span><span class="sxs-lookup"><span data-stu-id="79460-120">**Get recommendations**: View what changes need to be made to improve the spam score and increase the chance for your email to land in your recipient’s inbox.</span></span>
<!--feature detail end -->

<span data-ttu-id="79460-121">![危険度 - 中と表示されたスパム スコア](media/spamscore.png "危険度 - 中と表示されたスパム スコア")</span><span class="sxs-lookup"><span data-stu-id="79460-121">![Spam score showing medium risk](media/spamscore.png "Spam score showing medium risk")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="79460-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="79460-122">See also</span></span>

<!--docs start-->
<span data-ttu-id="79460-123">[電子メール コンテンツのスパム リスクを確認する](https://docs.microsoft.com/dynamics365/marketing/spam-checker) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="79460-123">[Check the spam risk of your email content](https://docs.microsoft.com/dynamics365/marketing/spam-checker) (docs)</span></span>
<!--docs end-->
