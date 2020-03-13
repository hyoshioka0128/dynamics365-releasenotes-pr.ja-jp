---
title: 営業リズムによるベスト プラクティスの適用
description: 営業担当者は Dynamics 365 アシスタントを通じて、営業リズムに基づくその時点のガイダンスを受け取ります。ガイダンスでは、適切なタイミングでの、適切な通信チャネルと適切なコンテンツを使用した適切な活動が指示されます。
author: relnotes
ms.reviewer: shujoshi
ms.date: 02/14/2020
ms.assetid: 2d6e4b89-5fcb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: efgilboa
dynamics365pdf: true
ms.openlocfilehash: 7216c5e74ee7b0b368fb4ca9044b4ff8220b0b69
ms.sourcegitcommit: 5164b04916273ffd769ce37c79b1fd63ce1bf937
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/24/2020
ms.locfileid: "3081940"
---
# <a name="enforce-best-practices-with-sales-cadence"></a><span data-ttu-id="71404-103">営業リズムによるベスト プラクティスの適用</span><span class="sxs-lookup"><span data-stu-id="71404-103">Enforce best practices with sales cadence</span></span>
[!include[artificial-intelligence/dynamics365-sales-insights banner](../includes/artificial-intelligence/dynamics365-sales-insights.md)]

| <span data-ttu-id="71404-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="71404-104">Enabled for</span></span>    |  <span data-ttu-id="71404-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="71404-105">Public preview</span></span> | <span data-ttu-id="71404-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="71404-106">Early access</span></span> | <span data-ttu-id="71404-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="71404-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="71404-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="71404-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="71404-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="71404-109">Apr 2020</span></span>|-| -|


## <a name="business-value"></a><span data-ttu-id="71404-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="71404-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="71404-111">一貫性のあるエクスペリエンスと明確なコミュニケーションは、成果を上げるための重要な側面です。</span><span class="sxs-lookup"><span data-stu-id="71404-111">Consistent experiences and clear communications are a critical aspect of achieving successful outcomes.</span></span> <span data-ttu-id="71404-112">セールス イネーブルメント マネージャーからのベスト プラクティスは、成功する販売戦略を広め、強化するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="71404-112">Best practices from sales enablement managers help to propagate and reinforce winning selling strategies.</span></span> <span data-ttu-id="71404-113">営業活動全体に提案と分析情報を組み込むことで、インサイド販売担当者はスムーズに段取りを進めることができ、また各顧客との対話を最大限に活用できるようになるため、成功の可能性が高まります。</span><span class="sxs-lookup"><span data-stu-id="71404-113">Infusing suggestions and insights throughout the sales motion helps to keep inside sellers on track and makes the most out of every customer interaction, and increases the likelihood of successful outcomes.</span></span> 

<span data-ttu-id="71404-114">営業リズムは、販売組織が成功戦略を作成および実施するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="71404-114">Sales cadence helps sales organizations develop and enforce winning strategies.</span></span> <span data-ttu-id="71404-115">セールス イネーブルメント マネージャーは、販売スタジオを使用して標準の対話戦略を作成、監視、改善できます。この戦略では、リードの変換と取引の成立を最適化し、営業チーム全体の一貫性を促す一連の営業の流れが定義されます。</span><span class="sxs-lookup"><span data-stu-id="71404-115">Sales enablement managers can create, monitor, and improve standard interaction strategies via Sales Studio, defining sequences of a sale that optimize lead conversion and closing of deals and inspire consistency across the sales team.</span></span>

<span data-ttu-id="71404-116">営業担当者は Dynamics 365 アシスタントを通じて、営業リズムに基づくその時点のガイダンスを受け取ります。ガイダンスでは、適切なタイミングでの、適切な通信チャネルと適切なコンテンツを使用した適切な活動が指示されます。</span><span class="sxs-lookup"><span data-stu-id="71404-116">Through Dynamics 365 Assistant, sellers receive in-the-moment guidance based on sales cadences, directed toward the right activity, at the right time, and using the right communication channel and right content.</span></span> <span data-ttu-id="71404-117">チームの全員が組織のベスト プラクティスを順守すると同時に、マネージャーは高度な分析を活用し、営業リズムの実施を簡単に監視することができます。</span><span class="sxs-lookup"><span data-stu-id="71404-117">Everyone on the team adheres to organizational best practices, while managers benefit from advanced analytics and can easily monitor sales cadence adoption.</span></span> <span data-ttu-id="71404-118">セールス イネーブルメント マネージャーは、摩擦のないサイクルを通じてより良い結果が得られるように営業活動を最適化できます。</span><span class="sxs-lookup"><span data-stu-id="71404-118">Sales enablement managers are empowered to optimize sales practices for better outcomes through a frictionless cycle.</span></span> <span data-ttu-id="71404-119">営業戦略を簡単に配布し、変換と取引成立への実際の影響を監視することができます。</span><span class="sxs-lookup"><span data-stu-id="71404-119">They can easily distribute sales strategies and then monitor actual impact on conversions and deal wins.</span></span>

<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="71404-120">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="71404-120">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="71404-121">**販売スタジオを使用した営業リズムの構築**: 販売スタジオの機能を利用して組織のベスト プラクティスと販売戦略を反映した営業リズムを構築し、販売担当者をその時点で支援できるようにします。</span><span class="sxs-lookup"><span data-stu-id="71404-121">**Build sales cadences via Sales Studio**: Benefit from the power of Sales Studio to build sales cadences that reflect organizational best practices and sales strategies to help sellers in the moment.</span></span>
- <span data-ttu-id="71404-122">**営業リズムの影響の最大化**: これらの戦略がリード変換や営業案件受注に及ぼす影響に基づいて、営業リズムを監視および改善します。</span><span class="sxs-lookup"><span data-stu-id="71404-122">**Maximize the impact of sales cadences**: Monitor and improve sales cadences based on impact of these strategies on lead conversions or opportunity wins.</span></span>
- <span data-ttu-id="71404-123">**インサイド販売担当者をその時点で支援**: Dynamics 365 アシスタントでガイダンスを提供して、販売担当者にリズムの次のステップを示します。</span><span class="sxs-lookup"><span data-stu-id="71404-123">**Guide inside sellers in the moment**: Offer guidance with the Dynamics 365 Assistant to direct sellers toward the next cadence step.</span></span> <span data-ttu-id="71404-124">ガイダンスには、販売スタジオで設計された営業リズムに基づく、顧客への連絡に最適なチャネルと最適なタイミングの推奨が含まれます。</span><span class="sxs-lookup"><span data-stu-id="71404-124">Guidance includes recommending the most suitable channel to reach out to the customer and the best time, based on sales cadence that is designed in Sales Studio.</span></span>
<!--feature detail end -->

<span data-ttu-id="71404-125">![リズム デザイナーのマネージャー ビュー](media/cadence-designer1.jpg "リズム デザイナーのマネージャー ビュー")</span><span class="sxs-lookup"><span data-stu-id="71404-125">![Cadence designer manager view](media/cadence-designer1.jpg "Cadence designer manager view")</span></span>
<!-- Picture 1 -->

<span data-ttu-id="71404-126">![リズム デザイナーの編集機能](media/cadence-designer2.jpg "リズム デザイナーの編集機能")</span><span class="sxs-lookup"><span data-stu-id="71404-126">![Cadence designer edit capabilities](media/cadence-designer2.jpg "Cadence designer edit capabilities")</span></span>
<!-- Picture 2 -->

> [!NOTE]
> <span data-ttu-id="71404-127">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="71404-127">This feature is available in the Unified Interface only.</span></span>






