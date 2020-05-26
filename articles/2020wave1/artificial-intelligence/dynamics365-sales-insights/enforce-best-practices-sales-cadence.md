---
title: 営業シーケンスによるベスト プラクティスの適用
description: 販売担当者は、営業シーケンスに基づくその時点のガイダンスを受け取ります。ガイダンスでは、適切な通信チャネルと必要なコンテンツを適切なタイミングで使用して、適切な活動が案内されます。
author: relnotes
ms.reviewer: udag
ms.date: 04/06/2020
ms.assetid: 2d6e4b89-5fcb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: nataln
dynamics365pdf: true
ms.openlocfilehash: 8f3c43ffc8ce3350140ec6c818d56079d927ea36
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255268"
---
# <a name="enforce-best-practices-with-sales-sequences"></a><span data-ttu-id="4bdfc-103">営業シーケンスによるベスト プラクティスの適用</span><span class="sxs-lookup"><span data-stu-id="4bdfc-103">Enforce best practices with sales sequences</span></span>


| <span data-ttu-id="4bdfc-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="4bdfc-104">Enabled for</span></span>    |  <span data-ttu-id="4bdfc-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="4bdfc-105">Public preview</span></span> | <span data-ttu-id="4bdfc-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="4bdfc-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="4bdfc-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="4bdfc-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="4bdfc-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="4bdfc-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="4bdfc-109">2020 年 4 月 6 日</span><span class="sxs-lookup"><span data-stu-id="4bdfc-109">Apr 6, 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="4bdfc-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="4bdfc-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="4bdfc-111">一貫性のあるエクスペリエンスと明確なコミュニケーションは、成果を上げるための重要な側面です。</span><span class="sxs-lookup"><span data-stu-id="4bdfc-111">Consistent experiences and clear communications are a critical aspect of achieving successful outcomes.</span></span> <span data-ttu-id="4bdfc-112">セールス イネーブルメント マネージャーからのベスト プラクティスは、成功する販売戦略を広め、強化するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="4bdfc-112">Best practices from sales enablement managers help to propagate and reinforce winning selling strategies.</span></span> <span data-ttu-id="4bdfc-113">営業活動全体に提案と分析情報を組み込むことで、インサイド販売担当者はスムーズに段取りを進めることができ、各顧客との対話を最大限に活用できるようになるため、成功の可能性が高まります。</span><span class="sxs-lookup"><span data-stu-id="4bdfc-113">Infusing suggestions and insights throughout the sales motion helps to keep inside sellers on track, makes the most out of every customer interaction, and increases the likelihood of successful outcomes.</span></span> 

<span data-ttu-id="4bdfc-114">営業シーケンスは、販売組織が成功戦略を作成および実施するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="4bdfc-114">Sales sequences help sales organizations develop and enforce winning strategies.</span></span> <span data-ttu-id="4bdfc-115">セールス イネーブルメント マネージャーは、標準の対話戦略を作成、監視、改善できます。この戦略では、リードの変換と取引の成立を最適化し、営業チーム全体の一貫性を促す一連の営業の流れが定義されます。</span><span class="sxs-lookup"><span data-stu-id="4bdfc-115">Sales enablement managers can create, monitor, and improve standard interaction strategies, defining sequences of a sale that optimize lead conversion and closing of deals and inspire consistency across the sales team.</span></span>

<span data-ttu-id="4bdfc-116">シーケンスにより、販売担当者は、その時点のガイダンスを受け取ります。ガイダンスでは、適切な通信チャネルと必要なコンテンツを適切なタイミングで使用して、適切な活動が案内されます。</span><span class="sxs-lookup"><span data-stu-id="4bdfc-116">With sequences, sellers receive in-the-moment guidance, guided toward the correct activity, on time using an appropriate communication channel with the necessary content.</span></span> <span data-ttu-id="4bdfc-117">チームの全員が組織のベスト プラクティスを遵守している一方で、セールス イネーブルメント マネージャーは、ストレスのないサイクルを通じてより優れた結果を得るために営業活動を最適化し、営業戦略を簡単に配布することができます。</span><span class="sxs-lookup"><span data-stu-id="4bdfc-117">Everyone on the team adheres to organizational best practices, while sales enablement managers are empowered to optimize sales practices for better outcomes through a frictionless cycle and can easily distribute sales strategies.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="4bdfc-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="4bdfc-118">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="4bdfc-119">**営業シーケンスの構築**: 組織のベスト プラクティスと販売戦略を反映した営業シーケンスを構築し、インサイド販売担当者をその時点で支援できるようにします。</span><span class="sxs-lookup"><span data-stu-id="4bdfc-119">**Build sales sequences**: Build sales sequences that reflect organizational best practices and sales strategies to help inside sellers in the moment.</span></span>
- <span data-ttu-id="4bdfc-120">**インサイド販売担当者をその時点で支援**: ガイダンスを提供して、販売担当者に次にとる必要のあるステップを示します。</span><span class="sxs-lookup"><span data-stu-id="4bdfc-120">**Guide inside sellers in the moment**: Offer guidance to direct sellers toward the next step they need to take.</span></span> <span data-ttu-id="4bdfc-121">ガイダンスには、顧客への連絡に最適なチャネルと最適なタイミングの推奨が含まれます。</span><span class="sxs-lookup"><span data-stu-id="4bdfc-121">Guidance includes recommending the most suitable channel to reach out to the customer and the best time.</span></span>
<!--feature detail end -->

<span data-ttu-id="4bdfc-122">![リズム デザイナーのマネージャー ビュー](media/cadence-designer1.jpg "リズム デザイナーのマネージャー ビュー")</span><span class="sxs-lookup"><span data-stu-id="4bdfc-122">![Cadence designer manager view](media/cadence-designer1.jpg "Cadence designer manager view")</span></span>
<!-- Picture 1 -->
<span data-ttu-id="4bdfc-123">![リズム デザイナーの編集機能](media/cadence-designer2.jpg "リズム デザイナーの編集機能")</span><span class="sxs-lookup"><span data-stu-id="4bdfc-123">![Cadence designer edit capabilities](media/cadence-designer2.jpg "Cadence designer edit capabilities")</span></span>
<!-- Picture 2 -->








