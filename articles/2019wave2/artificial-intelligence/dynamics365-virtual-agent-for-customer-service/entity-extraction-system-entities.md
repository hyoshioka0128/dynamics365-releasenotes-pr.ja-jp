---
title: システム エンティティによるエンティティ抽出
description: システム エンティティによるエンティティ抽出
author: relnotes
ms.reviewer: iawilt
ms.date: 08/30/2019
ms.assetid: 0c64278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: clmori
dynamics365pdf: true
ms.openlocfilehash: cb128bcef8a0e98529ae2fa27487230f86863d22
ms.sourcegitcommit: 856d36597ee54f817177a3682a0048ad1390c936
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2019
ms.locfileid: "2003341"
---
# <a name="entity-extraction-with-system-entities"></a><span data-ttu-id="1aebe-103">システム エンティティによるエンティティ抽出</span><span class="sxs-lookup"><span data-stu-id="1aebe-103">Entity extraction with system entities</span></span>
[!include[artificial-intelligence/dynamics365-virtual-agent-for-customer-service banner](../includes/artificial-intelligence/dynamics365-virtual-agent-for-customer-service.md)]

| <span data-ttu-id="1aebe-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1aebe-104">Enabled for</span></span>    |  <span data-ttu-id="1aebe-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1aebe-105">Public preview</span></span> | <span data-ttu-id="1aebe-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="1aebe-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1aebe-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="1aebe-107">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="1aebe-108">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="1aebe-108">Dec 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="1aebe-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1aebe-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1aebe-110">Dynamics 365 Virtual Agent for Customer Service は、ユーザーの応答に含まれる数多くの共通のエンティティを認識して抽出し、それに基づいて行動することができます。</span><span class="sxs-lookup"><span data-stu-id="1aebe-110">Dynamics 365 Virtual Agent for Customer Service can recognize, extract, and act on dozens of common entities in a user’s responses.</span></span> <span data-ttu-id="1aebe-111">たとえば、色、通貨、年齢、日付と時刻、名前、電話番号、期間、都市、州、住所、郵便番号、メール アドレス、言語、重さ、速度、気温、組織、割合、興味のあるポイント、リンクなどをすべて認識できます。</span><span class="sxs-lookup"><span data-stu-id="1aebe-111">For example, colors, currencies, ages, dates and times, names, telephone numbers, durations, cities, states, addresses, zip codes, email addresses, languages, weights, speeds, temperatures, organizations, percentages, points of interests, and links can all be recognized.</span></span>

<span data-ttu-id="1aebe-112">システムでは、最先端の自然言語機能を使用して、ユーザーの応答を認識されたエンティティと照合します。</span><span class="sxs-lookup"><span data-stu-id="1aebe-112">The system uses natural language capabilities to match a user’s responses to recognized entities.</span></span> <span data-ttu-id="1aebe-113">たとえば、ボットがユーザーに都市のエンティティを提供するよう要求し、「私はエメラルド シティに住んでいます」という応答があった場合、ボットはそれがシアトルのことを指すと理解します。</span><span class="sxs-lookup"><span data-stu-id="1aebe-113">For example, if a bot asks a user to provide a city entity, it understands that the response “I live in the emerald city” maps to the city of Seattle.</span></span> 

<span data-ttu-id="1aebe-114">さらに、システムはこれらのエンティティを検証します。</span><span class="sxs-lookup"><span data-stu-id="1aebe-114">Moreover, the system validates these entities.</span></span> <span data-ttu-id="1aebe-115">たとえば、ボットがユーザーに色を要求し、ユーザーが予期しない回答をした場合、ボットはこの質問を繰り返します。</span><span class="sxs-lookup"><span data-stu-id="1aebe-115">For example, when the bot asks the user for a color, and the user gives an unexpected answer, the bot will repeat this question.</span></span>
<!--feature detail end -->











