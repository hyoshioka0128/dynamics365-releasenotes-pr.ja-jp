---
title: 予測から隠れた分析情報を見つける
description: 予測から隠れた分析情報を見つける
author: relnotes
ms.reviewer: udag
ms.date: 04/24/2020
ms.assetid: 2c748d11-a2d7-e911-a812-000d3a4f15f1
ms.topic: article
ms.service: business-applications
ms.author: dandalla
dynamics365pdf: true
ms.openlocfilehash: 865355ddea4daa291b5a10c892122c3f7fefa8ef
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294316"
---
# <a name="uncover-hidden-insights-in-your-forecasts"></a><span data-ttu-id="d734f-103">予測から隠れた分析情報を見つける</span><span class="sxs-lookup"><span data-stu-id="d734f-103">Uncover hidden insights in your forecasts</span></span>


| <span data-ttu-id="d734f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="d734f-104">Enabled for</span></span>    |  <span data-ttu-id="d734f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d734f-105">Public preview</span></span> | <span data-ttu-id="d734f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="d734f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d734f-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="d734f-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="d734f-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="d734f-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="d734f-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="d734f-109">Feb 3, 2020</span></span>| <span data-ttu-id="d734f-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="d734f-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="d734f-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="d734f-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="d734f-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d734f-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d734f-113">Dynamics 365 Sales の予測機能は、営業マネージャーが信頼できる有意義な予測数値をリーダーシップに活用できる優れた柔軟性を提供します。</span><span class="sxs-lookup"><span data-stu-id="d734f-113">To ensure sales managers can provide leadership with meaningful forecast numbers that they trust, the forecasting capabilities of Dynamics 365 Sales offer great flexibility.</span></span> <span data-ttu-id="d734f-114">営業マネージャーは、スナップショットを取得し、その時点で予測を凍結して予測を分析し、スナップショット間の変化を通じてより深い理解を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="d734f-114">Sales managers are empowered to take snapshots to freeze a forecast in the moment and to analyze forecasts, gaining a deeper understanding through changes that occur between snapshots.</span></span> 

<span data-ttu-id="d734f-115">取引フロー分析では、2 つのスナップショットを視覚的に比較することで、営業マネージャーは予測値の変化だけでなく、変化に寄与している背後のレコードを簡単に確認できます。</span><span class="sxs-lookup"><span data-stu-id="d734f-115">With deal flow analyses, comparing two snapshots visually, sales managers can easily view changes in forecasted values as well as the underlying records that contribute to the change.</span></span> <span data-ttu-id="d734f-116">たとえば、営業マネージャーとして、自身のチームが 10 万件の取引を成約すると予測していたものの、8 万件しか成約しなかった場合、どの取引が成約しなかったのかを調査してその理由を把握し、将来のプランニングに生かすことができます。</span><span class="sxs-lookup"><span data-stu-id="d734f-116">For example, if a sales manager's team forecasted to close 100,000 deals, but only closed 80,000, the sales manager can investigate which deals slipped and why to get a deeper understanding and inform future planning.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d734f-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d734f-117">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="d734f-118">**スナップショットを活用する**: 調整期間が終了する前または後にスナップショットの作成をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="d734f-118">**Take advantage of snapshots**: Trigger snapshot creations before or after adjustment periods end.</span></span> <span data-ttu-id="d734f-119">セールス イネーブルメント マネージャーが自動スナップショットを提供できるようにします。</span><span class="sxs-lookup"><span data-stu-id="d734f-119">Empowers sales enablement managers to offer automated snapshots.</span></span>
- <span data-ttu-id="d734f-120">**スナップショットの履歴を表示する**: 予測ごとに、取得されたすべてのスナップショットのログを調べ、必要に応じて管理します。</span><span class="sxs-lookup"><span data-stu-id="d734f-120">**View snapshot history**: Explore a log of all snapshots taken per forecast and manage these as needed.</span></span> <span data-ttu-id="d734f-121">Sales Enablement マネージャーが組織にとって有益な学習を構築できるようにします。</span><span class="sxs-lookup"><span data-stu-id="d734f-121">Empowers sales enablement managers to develop valuable learnings for the organization.</span></span>
- <span data-ttu-id="d734f-122">**取引フローとスナップショットの視覚化のメリット**: 2 つの予測スナップショットを視覚的に比較して、予測が時間とともに変化した経緯と理由について理解を深めます。</span><span class="sxs-lookup"><span data-stu-id="d734f-122">**Benefit from deal-flow and snapshot visualization**: Visually compare two forecast snapshots to better understand how and why forecasting has changed over time.</span></span>
- <span data-ttu-id="d734f-123">**累積トレンド グラフを活用する**: タイムライン グラフ全体で予測を視覚的に調査します。</span><span class="sxs-lookup"><span data-stu-id="d734f-123">**Take advantage of cumulative trend chart**: Inspect forecast projections visually across a timeline chart.</span></span>
<!--feature detail end -->

<span data-ttu-id="d734f-124">![予測が時間と共にどのように変化しているかを理解する](media/forecasting_dealflow.png "予測が時間と共にどのように変化しているかを理解する")</span><span class="sxs-lookup"><span data-stu-id="d734f-124">![Know how the forecast is changing over time](media/forecasting_dealflow.png "Know how the forecast is changing over time")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="d734f-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="d734f-125">See also</span></span>

<!--blog start-->
<span data-ttu-id="d734f-126">[Dynamics 365 Sales の高度な予測による説明責任の推進](https://aka.ms/forecasting.blog) (ブログ)</span><span class="sxs-lookup"><span data-stu-id="d734f-126">[Driving accountability with advanced forecasting in Dynamics 365 Sales](https://aka.ms/forecasting.blog) (blog)</span></span>
<!--blog end-->

<!--docs start-->
<span data-ttu-id="d734f-127">[スナップショット間の取引フローを分析する](https://docs.microsoft.com/dynamics365/ai/sales/analyze-deals-flow-between-snapshots) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="d734f-127">[Analyze deals flows between snapshots](https://docs.microsoft.com/dynamics365/ai/sales/analyze-deals-flow-between-snapshots) (docs)</span></span>
<!--docs end-->
