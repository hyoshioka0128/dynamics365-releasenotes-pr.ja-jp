---
title: スロット充足機能
description: スロット充足機能
author: relnotes
ms.reviewer: iawilt
ms.date: 08/27/2019
ms.assetid: 1064278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: clmori
dynamics365pdf: true
ms.openlocfilehash: a0aea05871f63f6e24bc16a9e79210ff14f8dd4e
ms.sourcegitcommit: 856d36597ee54f817177a3682a0048ad1390c936
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2019
ms.locfileid: "2003616"
---
# <a name="slot-filling-capabilities"></a><span data-ttu-id="370d7-103">スロット充足機能</span><span class="sxs-lookup"><span data-stu-id="370d7-103">Slot-filling capabilities</span></span>
[!include[artificial-intelligence/dynamics365-virtual-agent-for-customer-service banner](../includes/artificial-intelligence/dynamics365-virtual-agent-for-customer-service.md)]

| <span data-ttu-id="370d7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="370d7-104">Enabled for</span></span>    |  <span data-ttu-id="370d7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="370d7-105">Public preview</span></span> | <span data-ttu-id="370d7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="370d7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="370d7-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="370d7-107">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="370d7-108">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="370d7-108">Dec 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="370d7-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="370d7-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="370d7-110">ユーザーがボットとの対話で何かを言うたびに、応答には会話を導くのに役立つ有用な情報が含まれている可能性があります。</span><span class="sxs-lookup"><span data-stu-id="370d7-110">Every time a user says something to interact with a bot, the response might contain useful information that helps guide the conversation.</span></span> <span data-ttu-id="370d7-111">システムは、ユーザーの応答で、会話をガイドするために使用する情報を継続的に解析します。</span><span class="sxs-lookup"><span data-stu-id="370d7-111">The system continuously parses the user’s responses for information that it uses to guide the conversation.</span></span> 

<span data-ttu-id="370d7-112">これは、ユーザーが既に提供した情報または不足している情報をボットが認識し、必要に応じて明確化のための質問をして、対話を続けられることを意味します。</span><span class="sxs-lookup"><span data-stu-id="370d7-112">This means the bot can recognize information that the user has already provided or that is missing, ask clarifying questions if needed, and continue with the dialog.</span></span> <span data-ttu-id="370d7-113">この機能はスロット充足と呼ばれます。</span><span class="sxs-lookup"><span data-stu-id="370d7-113">This capability is called slot filling.</span></span>

<span data-ttu-id="370d7-114">たとえば、天気についてたずねる場合、ユーザーは自然にトピック (天気予報)、場所 (レドモンド)、時間 (木曜日) を含める可能性があります。</span><span class="sxs-lookup"><span data-stu-id="370d7-114">For example, to ask about the weather, the user might naturally include the topic (weather forecast), the location (Redmond), and the time (Thursday).</span></span> <span data-ttu-id="370d7-115">次に例を示します。</span><span class="sxs-lookup"><span data-stu-id="370d7-115">For example:</span></span>

 <span data-ttu-id="370d7-116">**ユーザー:**      *レドモンドの木曜日の天気はどうですか?*</span><span class="sxs-lookup"><span data-stu-id="370d7-116">**User:**      *What's the weather in Redmond on Thursday?*</span></span>
 
 <span data-ttu-id="370d7-117">**ボット:**       *ワシントン州レドモンドの木曜日の天気予報は、晴れですが雨が降るかもしれません...*</span><span class="sxs-lookup"><span data-stu-id="370d7-117">**Bot:**       *The weather forecast for Thursday in Redmond Washington is sunny with a chance of rain...*</span></span>

<span data-ttu-id="370d7-118">ただし、ユーザーの応答があいまいで定型化されていない場合があり、タスクの実行に必要なすべての情報が提供されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="370d7-118">However, sometimes a user's response is more ambiguous and less scripted, and the user might not give all the information needed to perform a task.</span></span> <span data-ttu-id="370d7-119">スロット充足では、ボットはユーザーと短い会話を行って、タスクを完了するのに必要な不足している情報を見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="370d7-119">With slot filling, the bot can have a short conversation with the user to find out the missing information required to complete the task.</span></span>

<span data-ttu-id="370d7-120">たとえば、天気についての質問の会話でスロット充足が使われると次のようになります。</span><span class="sxs-lookup"><span data-stu-id="370d7-120">For example, to ask about the weather, here's what the conversation with slot filling might look like:</span></span>

<span data-ttu-id="370d7-121">**ユーザー:**   *木曜日の天気はどうですか?*</span><span class="sxs-lookup"><span data-stu-id="370d7-121">**User:**   *What's the weather like Thursday?*</span></span>

<span data-ttu-id="370d7-122">**ボット:**    *天気をお調べできます。どこをチェックしますか?*</span><span class="sxs-lookup"><span data-stu-id="370d7-122">**Bot:**    *I can look up the weather for you. Where should I check?*</span></span>

<span data-ttu-id="370d7-123">**ユーザー:**   *ワシントン州レドモンド*</span><span class="sxs-lookup"><span data-stu-id="370d7-123">**User:**   *Redmond Washington*</span></span>

<span data-ttu-id="370d7-124">**ボット:**    *ワシントン州レドモンドの木曜日の天気予報は、晴れですが雨が降るかもしれません...*</span><span class="sxs-lookup"><span data-stu-id="370d7-124">**Bot:**    *The weather forecast for Thursday in Redmond Washington is sunny with a chance of rain...*</span></span>
<!--feature detail end -->











