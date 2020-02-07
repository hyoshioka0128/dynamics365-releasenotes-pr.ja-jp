---
title: 予測から隠れた分析情報を見つける
description: ''
author: relnotes
ms.reviewer: udag
ms.date: 01/16/2020
ms.assetid: 2c748d11-a2d7-e911-a812-000d3a4f15f1
ms.topic: article
ms.service: business-applications
ms.author: dandalla
dynamics365pdf: true
ms.openlocfilehash: bc5ed2c0f8f49c1b1fb061fffb63ea817e0dc657
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986836"
---
# <a name="uncover-hidden-insights-in-your-forecasts"></a><span data-ttu-id="e4a29-102">予測から隠れた分析情報を見つける</span><span class="sxs-lookup"><span data-stu-id="e4a29-102">Uncover hidden insights in your forecasts</span></span>
[!include[artificial-intelligence/dynamics365-sales-insights banner](../includes/artificial-intelligence/dynamics365-sales-insights.md)]

| <span data-ttu-id="e4a29-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="e4a29-103">Enabled for</span></span>    |  <span data-ttu-id="e4a29-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e4a29-104">Public preview</span></span> | <span data-ttu-id="e4a29-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="e4a29-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="e4a29-106">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="e4a29-106">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="e4a29-107">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="e4a29-107">Feb 2020</span></span>| <span data-ttu-id="e4a29-108">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="e4a29-108">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="e4a29-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e4a29-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e4a29-110">Dynamics 365 Sales の予測機能は、営業マネージャーが信頼できる有意義な予測数値をリーダーシップに活用できる優れた柔軟性を提供します。</span><span class="sxs-lookup"><span data-stu-id="e4a29-110">To ensure sales managers can provide leadership with meaningful forecast numbers that they trust, the forecasting capabilities of Dynamics 365 Sales offer great flexibility.</span></span> <span data-ttu-id="e4a29-111">営業マネージャーは、スナップショットを取得し、その時点で予測を凍結して予測を分析し、スナップショット間の変化を通じてより深い理解を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="e4a29-111">Sales managers are empowered to take snapshots to freeze a forecast in the moment and to analyze forecasts, gaining a deeper understanding through changes that occur between snapshots.</span></span> 

<span data-ttu-id="e4a29-112">取引フロー分析では、2 つのスナップショットを視覚的に比較することで、営業マネージャーは予測値の変化だけでなく、変化に寄与している背後のレコードを簡単に確認できます。</span><span class="sxs-lookup"><span data-stu-id="e4a29-112">With deal flow analyses, comparing two snapshots visually, sales managers can easily view changes in forecasted values as well as the underlying records that contribute to the change.</span></span> <span data-ttu-id="e4a29-113">たとえば、営業マネージャーとして、自身のチームが 10 万件の取引を成約すると予測していたものの、8 万件しか成約しなかった場合、どの取引が成約しなかったのかを調査してその理由を把握し、将来のプランニングに生かすことができます。</span><span class="sxs-lookup"><span data-stu-id="e4a29-113">For example, if a sales manager's team forecasted to close 100,000 deals, but only closed 80,000, the sales manager can investigate which deals slipped and why to get a deeper understanding and inform future planning.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e4a29-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e4a29-114">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="e4a29-115">**スナップショットを活用する**: 調整期間が終了する前または後にスナップショットの作成をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="e4a29-115">**Take advantage of snapshots**: Trigger snapshot creations before or after adjustment periods end.</span></span> <span data-ttu-id="e4a29-116">セールス イネーブルメント マネージャーが自動スナップショットを提供できるようにします。</span><span class="sxs-lookup"><span data-stu-id="e4a29-116">Empowers sales enablement managers to offer automated snapshots.</span></span>
- <span data-ttu-id="e4a29-117">**スナップショットの履歴を表示する**: 予測ごとに、取得されたすべてのスナップショットのログを調べ、必要に応じて管理します。</span><span class="sxs-lookup"><span data-stu-id="e4a29-117">**View snapshot history**: Explore a log of all snapshots taken per forecast and manage these as needed.</span></span> <span data-ttu-id="e4a29-118">Sales Enablement マネージャーが組織にとって有益な学習を構築できるようにします。</span><span class="sxs-lookup"><span data-stu-id="e4a29-118">Empowers sales enablement managers to develop valuable learnings for the organization.</span></span>
- <span data-ttu-id="e4a29-119">**取引フローとスナップショットの視覚化のメリット**: 2 つの予測スナップショットを視覚的に比較して、予測が時間とともに変化した経緯と理由について理解を深めます。</span><span class="sxs-lookup"><span data-stu-id="e4a29-119">**Benefit from deal-flow and snapshot visualization**: Visually compare two forecast snapshots to better understand how and why forecasting has changed over time.</span></span>
- <span data-ttu-id="e4a29-120">**累積トレンド グラフを活用する**: タイムライン グラフ全体で予測を視覚的に調査します。</span><span class="sxs-lookup"><span data-stu-id="e4a29-120">**Take advantage of cumulative trend chart**: Inspect forecast projections visually across a timeline chart.</span></span>

<!--feature detail end -->

<span data-ttu-id="e4a29-121">![予測が時間とともにどのように変化しているかを理解する](media/forecasting_dealflow.png "予測が時間とともにどのように変化しているかを理解する")</span><span class="sxs-lookup"><span data-stu-id="e4a29-121">![Know how the forecast is changing over time](media/forecasting_dealflow.png "Know how the forecast is changing over time")</span></span>
<!-- Picture 1 -->








