---
title: システム エンティティによるエンティティ抽出
description: システム エンティティによるエンティティ抽出
author: ''
ms.reviewer: shellyha
ms.date: 06/11/2019
ms.assetid: 0c64278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: omaraf
dynamics365pdf: true
ms.openlocfilehash: 3b525c3c0eb59a8b2a3ca8a9ab1a59e8c83a6e0a
ms.sourcegitcommit: 4620697dc1f4fc6903504a55406f3d22af75e361
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1693959"
---
# <a name="entity-extraction-with-system-entities"></a><span data-ttu-id="248a1-103">システム エンティティによるエンティティ抽出</span><span class="sxs-lookup"><span data-stu-id="248a1-103">Entity extraction with system entities</span></span>
[!include[artificial-intelligence/dynamics365-virtual-agent-for-customer-service banner](../includes/artificial-intelligence/dynamics365-virtual-agent-for-customer-service.md)]

| <span data-ttu-id="248a1-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="248a1-104">Enabled for</span></span>    |  <span data-ttu-id="248a1-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="248a1-105">Public preview</span></span> | <span data-ttu-id="248a1-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="248a1-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="248a1-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="248a1-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="248a1-108">2019 年 7 月</span><span class="sxs-lookup"><span data-stu-id="248a1-108">July 2019</span></span>| <span data-ttu-id="248a1-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="248a1-109">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="248a1-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="248a1-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="248a1-111">Virtual Agent for Customer Service は、ユーザーの回答に含まれる多数の一般的なエンティティを認識、抽出、および操作できます。</span><span class="sxs-lookup"><span data-stu-id="248a1-111">Virtual Agent for Customer Service can recognize, extract, and act on dozens of common entities in a user’s responses.</span></span> <span data-ttu-id="248a1-112">たとえば、色、タイム ゾーン、通貨、年齢、日付と時刻、名前、電話番号、期間、都市、州、住所、郵便番号、メール アドレス、言語、重さ、速度、気温、組織、割合、興味のあるポイント、リンクなどです。</span><span class="sxs-lookup"><span data-stu-id="248a1-112">For example: colors, time zones, currencies, ages, dates and times, names, telephone numbers, durations, cities, states, addresses, zip codes, email addresses, languages, weights, speeds, temperatures, organizations, percentages, points of interests, links, and more.</span></span> 
 
<span data-ttu-id="248a1-113">システムでは、最先端の自然言語機能を使用して、ユーザーの応答でこれらのエンティティを照合します。</span><span class="sxs-lookup"><span data-stu-id="248a1-113">The system uses state-of-the-art natural language capabilities to match a user’s responses to these entities.</span></span> <span data-ttu-id="248a1-114">たとえば、ボットがユーザーにハンバーガーとスープのどちらかを選択するように要求した場合、システムは "私はサンドイッチにします" という応答がハンバーガーの好みに対応していると認識します。</span><span class="sxs-lookup"><span data-stu-id="248a1-114">For example, if a bot asks a user to choose between burgers and soup, the system understands that the response “I think I’ll go with the sandwich” maps to a preference for burgers.</span></span> 

<span data-ttu-id="248a1-115">さらに、システムはこれらのエンティティを検証します。</span><span class="sxs-lookup"><span data-stu-id="248a1-115">Moreover, the system validates these entities.</span></span> <span data-ttu-id="248a1-116">たとえば、ユーザーに色を尋ねたときは、"犬" のような応答は拒否し、ユーザーに本当の色を選択するように要求します。</span><span class="sxs-lookup"><span data-stu-id="248a1-116">For example, when asking the user for a color, it will reject a response like “dog” and ask the user to pick an actual color.</span></span>
<!--feature detail end -->










