---
title: 顧客体験エクスペリエンスの改善
description: ''
author: relnotes
ms.reviewer: alfergus
ms.date: 03/18/2020
ms.assetid: 81212add-e81b-ea11-a811-000d3a8f004f
ms.topic: article
ms.service: business-applications
ms.author: agmiskow
dynamics365pdf: true
ms.openlocfilehash: 8121c73d4588716ccf6d8606181c09f252eaecef
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3231892"
---
# <a name="improved-customer-journey-experience"></a><span data-ttu-id="003f7-102">顧客体験エクスペリエンスの改善</span><span class="sxs-lookup"><span data-stu-id="003f7-102">Improved customer journey experience</span></span>
[!include[dynamics365-marketing banner](../includes/dynamics365-marketing.md)]

| <span data-ttu-id="003f7-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="003f7-103">Enabled for</span></span>    |  <span data-ttu-id="003f7-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="003f7-104">Public preview</span></span> | <span data-ttu-id="003f7-105">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="003f7-105">Early access</span></span> | <span data-ttu-id="003f7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="003f7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="003f7-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="003f7-107">End users, automatically</span></span>|-|<span data-ttu-id="003f7-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="003f7-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="003f7-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="003f7-109">Feb 3, 2020</span></span>| <span data-ttu-id="003f7-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="003f7-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="003f7-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="003f7-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="003f7-112">一部の顧客体験には、時間に依存するコンテンツを含む電子メール メッセージが含まれる場合があります。</span><span class="sxs-lookup"><span data-stu-id="003f7-112">Some of your customer journeys might include email messages with time-sensitive content.</span></span> <span data-ttu-id="003f7-113">時間に依存する電子メールには、期間限定のオファー、休日のプロモーション、または今後のイベントの 2 週間前のリマインダーなどがあります。</span><span class="sxs-lookup"><span data-stu-id="003f7-113">Time-sensitive emails could include time-limited offers, holiday promotions, or a two-week reminder for an upcoming event.</span></span> <span data-ttu-id="003f7-114">取引先担当者はいつでも体験に参加できるため、1 つ以上の選択した電子メール メッセージに有効期限を設定することにより、古い情報の配信を防止できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="003f7-114">Because contacts might join the journey at any time, you can now prevent delivering outdated information by setting an expiration date for one or more selected email messages.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="003f7-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="003f7-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="003f7-116">**時間依存コンテンツの有効期限**: 静的な有効期限を設定します (たとえば、2020 年 3 月 31 日、顧客のタイムゾーンの午後 10:00 など)。</span><span class="sxs-lookup"><span data-stu-id="003f7-116">**Expiration dates and times for time-sensitive content**: Set a static expiration date and time—for example, March 31, 2020, at 10:00 PM in the customer’s time zone.</span></span>
<span data-ttu-id="003f7-117">**古いメッセージなし**: 有効期限後に電子メール タイルを入力した取引先担当者は、電子メール メッセージを受信しません。</span><span class="sxs-lookup"><span data-stu-id="003f7-117">**No outdated messages**: Any contact who enters an email tile after its expiration date doesn't receive the email message.</span></span> 
<span data-ttu-id="003f7-118">**メッセージを受信しなかった人を特定する**: 有効期限が切れたためにメッセージを受信しなかった人に関する情報が捕捉され、電子メールと体験の分析情報から入手できます。</span><span class="sxs-lookup"><span data-stu-id="003f7-118">**Determine who didn't receive your message**: Information on who didn't receive a message due to an expiration date is captured and available from email and journey insights.</span></span>
<span data-ttu-id="003f7-119">**ライブ レコードの停止時の警告**: ライブの顧客体験で使用される電子メール メッセージ、フォーム、またはセグメントを停止する前に、ライブ体験で使用されるエンティティをユーザーが不注意に破損することを防ぐための警告メッセージがユーザーに表示されます。</span><span class="sxs-lookup"><span data-stu-id="003f7-119">**Warning when stopping live records**: Before stopping email messages, forms, or segments used by live customer journeys, the user sees a warning message to help prevent the user from inadvertently corrupting an entity used in a live journey.</span></span>
<!--feature detail end -->

<span data-ttu-id="003f7-120">![顧客体験に有効期限を追加する](media/improve-customer-journey.png "顧客体験に有効期限を追加する")</span><span class="sxs-lookup"><span data-stu-id="003f7-120">![Add an expiration date and time to customer journeys](media/improve-customer-journey.png "Add an expiration date and time to customer journeys")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="003f7-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="003f7-121">See also</span></span>


<!--docs start-->
<span data-ttu-id="003f7-122">[Dynamics 365 Marketing の新機能](https://docs.microsoft.com/dynamics365/marketing/whats-new-marketing)</span><span class="sxs-lookup"><span data-stu-id="003f7-122">[What's new in Dynamics 365 Marketing](https://docs.microsoft.com/dynamics365/marketing/whats-new-marketing) (docs)</span></span>
<!--docs end-->

