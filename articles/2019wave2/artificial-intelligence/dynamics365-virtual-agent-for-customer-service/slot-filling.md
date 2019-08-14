---
title: スロット充足機能
description: スロット充足機能
author: relnotes
ms.reviewer: shellyha
ms.date: 07/31/2019
ms.assetid: 1064278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: omaraf
dynamics365pdf: true
ms.openlocfilehash: 0bf8b34e5227f8e9f365fc1d5ac3cc110edc1d1b
ms.sourcegitcommit: d7e3131b7435c3c6581f61ee059895f9045cc379
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/03/2019
ms.locfileid: "1856121"
---
# <a name="slot-filling-capabilities"></a><span data-ttu-id="91303-103">スロット充足機能</span><span class="sxs-lookup"><span data-stu-id="91303-103">Slot-filling capabilities</span></span>
[!include[artificial-intelligence/dynamics365-virtual-agent-for-customer-service banner](../includes/artificial-intelligence/dynamics365-virtual-agent-for-customer-service.md)]

| <span data-ttu-id="91303-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="91303-104">Enabled for</span></span>    |  <span data-ttu-id="91303-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="91303-105">Public preview</span></span> | <span data-ttu-id="91303-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="91303-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="91303-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="91303-107">Admins, makers, or analysts, automatically</span></span>|| <span data-ttu-id="91303-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="91303-108">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="91303-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="91303-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="91303-110">ユーザーがボットとの対話で何かを言うたびに、応答には会話を導くのに役立つ有用な情報が含まれている可能性があります。</span><span class="sxs-lookup"><span data-stu-id="91303-110">Every time a user says something to interact with a bot, the response might contain useful information that helps guide the conversation.</span></span> <span data-ttu-id="91303-111">システムは、ユーザーの応答で、会話をガイドするために使用する情報を継続的に解析します。</span><span class="sxs-lookup"><span data-stu-id="91303-111">The system continuously parses the user’s responses for information that it uses to guide the conversation.</span></span> 

<span data-ttu-id="91303-112">ほとんどの業界のチャットボットでは、ユーザーの回答で情報が不足しているものや情報が過剰なものは無視され、会話を調整せずに次のスクリプト形式の質問に進みます。</span><span class="sxs-lookup"><span data-stu-id="91303-112">Most industry chatbots ignore any missing or extra information in a user's response, and move on to the next scripted question without adapting the conversation.</span></span> 

<span data-ttu-id="91303-113">これに対し、インテリジェントな会話 AI である Virtual Agent for Customer Service は、ユーザーが既に提供した情報または不足している情報を認識し、必要な場合は明確化のための質問をして、対話を続け、本当に楽しい会話を提供します。</span><span class="sxs-lookup"><span data-stu-id="91303-113">In contrast, with intelligent conversation AI, Virtual Agent for Customer Service recognizes information that the user has already provided or that is missing, asks clarifying questions if needed, and continues with the dialog, providing truly delightful conversation.</span></span> <span data-ttu-id="91303-114">この機能はスロット充足と呼ばれます。</span><span class="sxs-lookup"><span data-stu-id="91303-114">This capability is called slot filling.</span></span>

<span data-ttu-id="91303-115">たとえば、天気について尋ねる場合、ユーザーは自然にトピック (天気予報)、場所 (レドモンド)、時間 (木曜日) を含める可能性があります。</span><span class="sxs-lookup"><span data-stu-id="91303-115">For example, to ask about the weather, the user might naturally include the topic (weather forecast), the location (Redmond), and the time (Thursday).</span></span> <span data-ttu-id="91303-116">たとえば次のようなものです。</span><span class="sxs-lookup"><span data-stu-id="91303-116">For example:</span></span>

 <span data-ttu-id="91303-117">**ユーザー:**      *レドモンドの木曜日の天気はどうですか?*</span><span class="sxs-lookup"><span data-stu-id="91303-117">**User:**      *What's the weather in Redmond on Thursday?*</span></span>
 
 <span data-ttu-id="91303-118">**ボット:**       *ワシントン州レドモンドの木曜日の天気予報は、晴れですが雨が降るかもしれません...*</span><span class="sxs-lookup"><span data-stu-id="91303-118">**Bot:**       *The weather forecast for Thursday in Redmond Washington is sunny with a chance of rain...*</span></span>

<span data-ttu-id="91303-119">ただし、ユーザーの応答があいまいで定型化されていない場合があり、タスクの実行に必要なすべての情報が提供されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="91303-119">However, sometimes a user's response is more ambiguous and less scripted, and the user might not give all the information needed to perform a task.</span></span> <span data-ttu-id="91303-120">スロット充足では、ボットはユーザーと短い会話を行って、タスクを完了するのに必要な不足している情報を見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="91303-120">With slot filling, the bot is able to have a short conversation with the user to find out the missing information required to complete the task.</span></span>

<span data-ttu-id="91303-121">たとえば、天気についての質問の会話でスロット充足が使われると次のようになります。</span><span class="sxs-lookup"><span data-stu-id="91303-121">For example, to ask about the weather, here's what the conversation with slot filling might look like:</span></span>

<span data-ttu-id="91303-122">**ユーザー:**   *天気はどうですか?*</span><span class="sxs-lookup"><span data-stu-id="91303-122">**User:**   *What's the weather like?*</span></span>

<span data-ttu-id="91303-123">**ボット:**    *天気をお調べできます。どこをチェックしますか?*</span><span class="sxs-lookup"><span data-stu-id="91303-123">**Bot:**    *I can look up the weather for you. Where should I check?*</span></span>

<span data-ttu-id="91303-124">**ユーザー:**   *ワシントン州レドモンド*</span><span class="sxs-lookup"><span data-stu-id="91303-124">**User:**   *Redmond Washington*</span></span>

<span data-ttu-id="91303-125">**ボット:**    *わかりました、いつですか?*</span><span class="sxs-lookup"><span data-stu-id="91303-125">**Bot:**    *Okay, for when?*</span></span>

<span data-ttu-id="91303-126">**ユーザー:**   *木曜日*</span><span class="sxs-lookup"><span data-stu-id="91303-126">**User:**   *Thursday*</span></span>

<span data-ttu-id="91303-127">**ボット:**    *ワシントン州レドモンドの木曜日の天気予報は、晴れですが雨が降るかもしれません...*</span><span class="sxs-lookup"><span data-stu-id="91303-127">**Bot:**    *The weather forecast for Thursday in Redmond Washington is sunny with a chance of rain...*</span></span>
<!--feature detail end -->











