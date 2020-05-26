---
title: 顧客体験エクスペリエンスの改善
description: Dynamics 365 Marketing の改善された顧客体験エクスペリエンスにより、1 つ以上の選択した電子メール メッセージに有効期限を設定して、古い情報の配信を防止できるようになりました。
author: relnotes
ms.reviewer: alfergus
ms.date: 04/21/2020
ms.assetid: 81212add-e81b-ea11-a811-000d3a8f004f
ms.topic: article
ms.service: business-applications
ms.author: agmiskow
dynamics365pdf: true
ms.openlocfilehash: 5d8d1d8804b4b50878a7059e5c55e2332bad6e87
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3349932"
---
# <a name="improved-customer-journey-experience"></a><span data-ttu-id="0ab9b-103">顧客体験エクスペリエンスの改善</span><span class="sxs-lookup"><span data-stu-id="0ab9b-103">Improved customer journey experience</span></span>


| <span data-ttu-id="0ab9b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0ab9b-104">Enabled for</span></span>    |  <span data-ttu-id="0ab9b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0ab9b-105">Public preview</span></span> | <span data-ttu-id="0ab9b-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="0ab9b-106">Early access</span></span> | <span data-ttu-id="0ab9b-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="0ab9b-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="0ab9b-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="0ab9b-108">End users, automatically</span></span>|-|<span data-ttu-id="0ab9b-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0ab9b-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0ab9b-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="0ab9b-110">Feb 3, 2020</span></span>| <span data-ttu-id="0ab9b-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0ab9b-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0ab9b-112">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="0ab9b-112">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="0ab9b-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0ab9b-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0ab9b-114">一部の顧客体験には、時間に依存するコンテンツを含む電子メール メッセージが含まれる場合があります。</span><span class="sxs-lookup"><span data-stu-id="0ab9b-114">Some of your customer journeys might include email messages with time-sensitive content.</span></span> <span data-ttu-id="0ab9b-115">時間に依存する電子メールには、期間限定のオファー、休日のプロモーション、または今後のイベントの 2 週間前のリマインダーなどがあります。</span><span class="sxs-lookup"><span data-stu-id="0ab9b-115">Time-sensitive emails could include time-limited offers, holiday promotions, or a two-week reminder for an upcoming event.</span></span> <span data-ttu-id="0ab9b-116">取引先担当者はいつでも体験に参加できるため、1 つ以上の選択した電子メール メッセージに有効期限を設定することにより、古い情報の配信を防止できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0ab9b-116">Because contacts might join the journey at any time, you can now prevent delivering outdated information by setting an expiration date for one or more selected email messages.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0ab9b-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0ab9b-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0ab9b-118">**時間依存コンテンツの有効期限**: 静的な有効期限を設定します。</span><span class="sxs-lookup"><span data-stu-id="0ab9b-118">**Expiration dates and times for time-sensitive content**: Set a static expiration date and time.</span></span> <span data-ttu-id="0ab9b-119">たとえば、2020 年 3 月 31 日、顧客のタイムゾーンの午後 10:00 などです。</span><span class="sxs-lookup"><span data-stu-id="0ab9b-119">For example, March 31, 2020, at 10:00 PM in the customer’s time zone.</span></span>
<span data-ttu-id="0ab9b-120">**古いメッセージなし**: 有効期限後に電子メール タイルを入力した取引先担当者は、電子メール メッセージを受信しません。</span><span class="sxs-lookup"><span data-stu-id="0ab9b-120">**No outdated messages**: Any contact who enters an email tile after its expiration date doesn't receive the email message.</span></span> 
<span data-ttu-id="0ab9b-121">**メッセージを受信しなかった人を特定する**: 有効期限が切れたためにメッセージを受信しなかった人に関する情報が捕捉され、電子メールと体験の分析情報から入手できます。</span><span class="sxs-lookup"><span data-stu-id="0ab9b-121">**Determine who didn't receive your message**: Information regarding who didn't receive a message because it expired is captured and available from email and journey insights.</span></span>
<span data-ttu-id="0ab9b-122">**ライブ レコードの停止時の警告**: ライブの顧客体験で使用される電子メール メッセージ、フォーム、またはセグメントを停止する前に、ライブ体験で使用されるエンティティを不注意に破損することを防ぐための警告メッセージが表示されます。</span><span class="sxs-lookup"><span data-stu-id="0ab9b-122">**Warning when stopping live records**: Before stopping email messages, forms, or segments used by live customer journeys, you will receive a warning message to prevent you from inadvertently corrupting an entity used in a live journey.</span></span>
<!--feature detail end -->

<span data-ttu-id="0ab9b-123">![顧客体験に有効期限を追加する](media/improve-customer-journey.png "顧客体験に有効期限を追加する")</span><span class="sxs-lookup"><span data-stu-id="0ab9b-123">![Add an expiration date and time to customer journeys](media/improve-customer-journey.png "Add an expiration date and time to customer journeys")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="0ab9b-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="0ab9b-124">See also</span></span>

<!--docs start-->
<span data-ttu-id="0ab9b-125">[新機能](https://docs.microsoft.com/dynamics365/marketing/whats-new-marketing) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="0ab9b-125">[What's new](https://docs.microsoft.com/dynamics365/marketing/whats-new-marketing) (docs)</span></span>
<!--docs end-->
