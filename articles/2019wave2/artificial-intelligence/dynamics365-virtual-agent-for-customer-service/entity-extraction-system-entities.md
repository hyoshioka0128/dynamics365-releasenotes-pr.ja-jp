---
title: システム エンティティによるエンティティ抽出
description: システム エンティティによるエンティティ抽出
author: relnotes
ms.reviewer: shellyha
ms.date: 07/31/2019
ms.assetid: 0c64278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: omaraf
dynamics365pdf: true
ms.openlocfilehash: 831bde189e949983134308da4d73fbb6cef1793b
ms.sourcegitcommit: d7e3131b7435c3c6581f61ee059895f9045cc379
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/03/2019
ms.locfileid: "1856095"
---
# <a name="entity-extraction-with-system-entities"></a><span data-ttu-id="e1988-103">システム エンティティによるエンティティ抽出</span><span class="sxs-lookup"><span data-stu-id="e1988-103">Entity extraction with system entities</span></span>
[!include[artificial-intelligence/dynamics365-virtual-agent-for-customer-service banner](../includes/artificial-intelligence/dynamics365-virtual-agent-for-customer-service.md)]

| <span data-ttu-id="e1988-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="e1988-104">Enabled for</span></span>    |  <span data-ttu-id="e1988-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e1988-105">Public preview</span></span> | <span data-ttu-id="e1988-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="e1988-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="e1988-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="e1988-107">Admins, makers, or analysts, automatically</span></span>|| <span data-ttu-id="e1988-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="e1988-108">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="e1988-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e1988-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e1988-110">Virtual Agent for Customer Service は、ユーザーの回答に含まれる多数の一般的なエンティティを認識、抽出、および操作できます。</span><span class="sxs-lookup"><span data-stu-id="e1988-110">Virtual Agent for Customer Service can recognize, extract, and act on dozens of common entities in a user’s responses.</span></span> <span data-ttu-id="e1988-111">たとえば、色、タイム ゾーン、通貨、年齢、日付と時刻、名前、電話番号、期間、都市、州、住所、郵便番号、メール アドレス、言語、重さ、速度、気温、組織、割合、興味のあるポイント、リンクなどです。</span><span class="sxs-lookup"><span data-stu-id="e1988-111">For example: colors, time zones, currencies, ages, dates and times, names, telephone numbers, durations, cities, states, addresses, zip codes, email addresses, languages, weights, speeds, temperatures, organizations, percentages, points of interests, links, and more.</span></span> 
 
<span data-ttu-id="e1988-112">システムでは、最先端の自然言語機能を使用して、ユーザーの応答でこれらのエンティティを照合します。</span><span class="sxs-lookup"><span data-stu-id="e1988-112">The system uses state-of-the-art natural language capabilities to match a user’s responses to these entities.</span></span> <span data-ttu-id="e1988-113">たとえば、ボットがユーザーにハンバーガーとスープのどちらかを選択するように要求した場合、システムは "私はサンドイッチにします" という応答がハンバーガーの好みに対応していると認識します。</span><span class="sxs-lookup"><span data-stu-id="e1988-113">For example, if a bot asks a user to choose between burgers and soup, the system understands that the response “I think I’ll go with the sandwich” maps to a preference for burgers.</span></span> 

<span data-ttu-id="e1988-114">さらに、システムはこれらのエンティティを検証します。</span><span class="sxs-lookup"><span data-stu-id="e1988-114">Moreover, the system validates these entities.</span></span> <span data-ttu-id="e1988-115">たとえば、ユーザーに色を尋ねたときは、"犬" のような応答は拒否し、ユーザーに本当の色を選択するように要求します。</span><span class="sxs-lookup"><span data-stu-id="e1988-115">For example, when asking the user for a color, it will reject a response like “dog” and ask the user to pick an actual color.</span></span>
<!--feature detail end -->











