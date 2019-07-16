---
title: スロット充足機能
description: スロット充足機能
author: ''
ms.reviewer: shellyha
ms.date: 06/11/2019
ms.assetid: 1064278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: omaraf
dynamics365pdf: true
ms.openlocfilehash: 2e4748b8e63b1191d976171ba44dd9c330bd62ca
ms.sourcegitcommit: 4620697dc1f4fc6903504a55406f3d22af75e361
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1694103"
---
# <a name="slot-filling-capabilities"></a><span data-ttu-id="91cc8-103">スロット充足機能</span><span class="sxs-lookup"><span data-stu-id="91cc8-103">Slot-filling capabilities</span></span>
[!include[artificial-intelligence/dynamics365-virtual-agent-for-customer-service banner](../includes/artificial-intelligence/dynamics365-virtual-agent-for-customer-service.md)]

| <span data-ttu-id="91cc8-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="91cc8-104">Enabled for</span></span>    |  <span data-ttu-id="91cc8-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="91cc8-105">Public preview</span></span> | <span data-ttu-id="91cc8-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="91cc8-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="91cc8-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="91cc8-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="91cc8-108">2019 年 7 月</span><span class="sxs-lookup"><span data-stu-id="91cc8-108">July 2019</span></span>| <span data-ttu-id="91cc8-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="91cc8-109">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="91cc8-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="91cc8-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="91cc8-111">ユーザーがボットとの対話で何かを言うたびに、応答には会話を導くのに役立つ有用な情報が含まれている可能性があります。</span><span class="sxs-lookup"><span data-stu-id="91cc8-111">Every time a user says something to interact with a bot, the response might contain useful information that helps guide the conversation.</span></span> <span data-ttu-id="91cc8-112">システムは、ユーザーの応答で、会話をガイドするために使用する情報を継続的に解析します。</span><span class="sxs-lookup"><span data-stu-id="91cc8-112">The system continuously parses the user’s responses for information that it uses to guide the conversation.</span></span> 

<span data-ttu-id="91cc8-113">ほとんどの業界のチャットボットでは、ユーザーの回答で情報が不足しているものや情報が過剰なものは無視され、会話を調整せずに次のスクリプト形式の質問に進みます。</span><span class="sxs-lookup"><span data-stu-id="91cc8-113">Most industry chatbots ignore any missing or extra information in a user's response, and move on to the next scripted question without adapting the conversation.</span></span> 

<span data-ttu-id="91cc8-114">これに対し、インテリジェントな会話 AI である Virtual Agent for Customer Service は、ユーザーが既に提供した情報または不足している情報を認識し、必要な場合は明確化のための質問をして、対話を続け、本当に楽しい会話を提供します。</span><span class="sxs-lookup"><span data-stu-id="91cc8-114">In contrast, with intelligent conversation AI, Virtual Agent for Customer Service recognizes information that the user has already provided or that is missing, asks clarifying questions if needed, and continues with the dialog, providing truly delightful conversation.</span></span> <span data-ttu-id="91cc8-115">この機能はスロット充足と呼ばれます。</span><span class="sxs-lookup"><span data-stu-id="91cc8-115">This capability is called slot filling.</span></span>

<span data-ttu-id="91cc8-116">たとえば、天気について尋ねる場合、ユーザーは自然にトピック (天気予報)、場所 (レドモンド)、時間 (木曜日) を含める可能性があります。</span><span class="sxs-lookup"><span data-stu-id="91cc8-116">For example, to ask about the weather, the user might naturally include the topic (weather forecast), the location (Redmond), and the time (Thursday).</span></span> <span data-ttu-id="91cc8-117">たとえば次のようなものです。</span><span class="sxs-lookup"><span data-stu-id="91cc8-117">For example:</span></span>

 <span data-ttu-id="91cc8-118">**ユーザー:**      *レドモンドの木曜日の天気はどうですか?*</span><span class="sxs-lookup"><span data-stu-id="91cc8-118">**User:**      *What's the weather in Redmond on Thursday?*</span></span>
 
 <span data-ttu-id="91cc8-119">**ボット:**       *ワシントン州レドモンドの木曜日の天気予報は、晴れですが雨が降るかもしれません...*</span><span class="sxs-lookup"><span data-stu-id="91cc8-119">**Bot:**       *The weather forecast for Thursday in Redmond Washington is sunny with a chance of rain...*</span></span>

<span data-ttu-id="91cc8-120">ただし、ユーザーの応答があいまいで定型化されていない場合があり、タスクの実行に必要なすべての情報が提供されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="91cc8-120">However, sometimes a user's response is more ambiguous and less scripted, and the user might not give all the information needed to perform a task.</span></span> <span data-ttu-id="91cc8-121">スロット充足では、ボットはユーザーと短い会話を行って、タスクを完了するのに必要な不足している情報を見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="91cc8-121">With slot filling, the bot is able to have a short conversation with the user to find out the missing information required to complete the task.</span></span>

<span data-ttu-id="91cc8-122">たとえば、天気についての質問の会話でスロット充足が使われると次のようになります。</span><span class="sxs-lookup"><span data-stu-id="91cc8-122">For example, to ask about the weather, here's what the conversation with slot filling might look like:</span></span>

<span data-ttu-id="91cc8-123">**ユーザー:**   *天気はどうですか?*</span><span class="sxs-lookup"><span data-stu-id="91cc8-123">**User:**   *What's the weather like?*</span></span>

<span data-ttu-id="91cc8-124">**ボット:**    *天気をお調べできます。どこをチェックしますか?*</span><span class="sxs-lookup"><span data-stu-id="91cc8-124">**Bot:**    *I can look up the weather for you. Where should I check?*</span></span>

<span data-ttu-id="91cc8-125">**ユーザー:**   *ワシントン州レドモンド*</span><span class="sxs-lookup"><span data-stu-id="91cc8-125">**User:**   *Redmond Washington*</span></span>

<span data-ttu-id="91cc8-126">**ボット:**    *わかりました、いつですか?*</span><span class="sxs-lookup"><span data-stu-id="91cc8-126">**Bot:**    *Okay, for when?*</span></span>

<span data-ttu-id="91cc8-127">**ユーザー:**   *木曜日*</span><span class="sxs-lookup"><span data-stu-id="91cc8-127">**User:**   *Thursday*</span></span>

<span data-ttu-id="91cc8-128">**ボット:**    *ワシントン州レドモンドの木曜日の天気予報は、晴れですが雨が降るかもしれません...*</span><span class="sxs-lookup"><span data-stu-id="91cc8-128">**Bot:**    *The weather forecast for Thursday in Redmond Washington is sunny with a chance of rain...*</span></span>
<!--feature detail end -->










