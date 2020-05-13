---
title: 予測から隠れた分析情報を見つける
description: ''
author: relnotes
ms.reviewer: udag
ms.date: 03/22/2020
ms.assetid: e027ecaa-a438-ea11-a813-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: dandalla
dynamics365pdf: true
ms.openlocfilehash: 30a09479841a3ec6d98896a52369c75f2dba0182
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3179068"
---
# <a name="uncover-hidden-insights-in-your-forecasts"></a><span data-ttu-id="0b373-102">予測から隠れた分析情報を見つける</span><span class="sxs-lookup"><span data-stu-id="0b373-102">Uncover hidden insights in your forecasts</span></span>


| <span data-ttu-id="0b373-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="0b373-103">Enabled for</span></span>    |  <span data-ttu-id="0b373-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0b373-104">Public preview</span></span> | <span data-ttu-id="0b373-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="0b373-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0b373-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="0b373-106">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="0b373-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0b373-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0b373-108">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="0b373-108">Feb 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="0b373-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0b373-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0b373-110">Dynamics 365 Sales の予測機能は、営業マネージャーが信頼できる有意義な予測数値をリーダーシップ チームに活用できる優れた柔軟性を提供します。</span><span class="sxs-lookup"><span data-stu-id="0b373-110">To ensure sales managers can provide the leadership team with meaningful forecast numbers that they trust, the forecasting capabilities of Dynamics 365 Sales offer great flexibility.</span></span> <span data-ttu-id="0b373-111">営業マネージャーは、スナップショットを取得し、その時点で予測を凍結して予測を分析し、スナップショット間の変化を通じてより深い理解を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="0b373-111">Sales managers are empowered to take snapshots, to freeze a forecast in the moment, and to analyze forecasts, gaining a deeper understanding through changes that occur between snapshots.</span></span>  

<span data-ttu-id="0b373-112">取引フロー分析では、2 つのスナップショットを視覚的に比較することで、営業マネージャーは予測値の変化だけでなく、変化に寄与している背後のレコードを簡単に確認できます。</span><span class="sxs-lookup"><span data-stu-id="0b373-112">With deal flow analyses, comparing two snapshots visually, sales managers can easily view changes in forecasted values as well as the underlying records that contribute to the change.</span></span> <span data-ttu-id="0b373-113">たとえば、営業マネージャーとして、自身のチームが 10 万件の取引を成約すると予測していたものの、8 万件しか成約しなかった場合、どの取引が成約しなかったのかを調査してその理由を把握し、将来のプランニングに生かすことができます。</span><span class="sxs-lookup"><span data-stu-id="0b373-113">For example, if as a sales manager, your team forecasted to close 100,000 deals, but only closed 80,000, you can investigate which deals slipped and why—to get a deeper understanding and inform future planning.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0b373-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0b373-114">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="0b373-115">**スナップショットを活用する**: 調整期間が終了する前または後にスナップショットの作成をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="0b373-115">**Take advantage of snapshots**: Trigger snapshot creations before or after adjustment periods end.</span></span> <span data-ttu-id="0b373-116">これにより、セールス イネーブルメント マネージャーが自動スナップショットを提供できるようになります。</span><span class="sxs-lookup"><span data-stu-id="0b373-116">This empowers sales enablement managers to offer automated snapshots.</span></span>
- <span data-ttu-id="0b373-117">**スナップショットの履歴を表示する**: 予測ごとに、取得されたすべてのスナップショットのログを調べ、必要に応じて管理します。</span><span class="sxs-lookup"><span data-stu-id="0b373-117">**View snapshot history**: Explore a log of all snapshots taken per forecast and manage these as needed.</span></span> <span data-ttu-id="0b373-118">これにより、セールス イネーブルメント マネージャーが組織にとって有益な学習を構築できるようになります。</span><span class="sxs-lookup"><span data-stu-id="0b373-118">This empowers sales enablement managers to develop valuable learnings for the organization.</span></span>
- <span data-ttu-id="0b373-119">**取引フローとスナップショットの視覚化のメリット**: 2 つの予測スナップショットを視覚的に比較して、予測が時間とともに変化した経緯と理由について理解を深めます。</span><span class="sxs-lookup"><span data-stu-id="0b373-119">**Benefit from deal-flow and snapshot visualization**: Visually compare two forecast snapshots to better understand how and why forecasting has changed over time.</span></span>
- <span data-ttu-id="0b373-120">**累積トレンド グラフを活用する**: タイムライン グラフ全体で予測を視覚的に調査します。</span><span class="sxs-lookup"><span data-stu-id="0b373-120">**Take advantage of cumulative trend chart**: Inspect forecast projections visually across a timeline chart.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="0b373-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="0b373-121">See also</span></span>

<span data-ttu-id="0b373-122">[スナップショット間の取引フローを分析する](https:/docs.microsoft.com/dynamics365/ai/sales/analyze-deals-flow-between-snapshots) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="0b373-122">[Analyze deals flows between snapshots](https:/docs.microsoft.com/dynamics365/ai/sales/analyze-deals-flow-between-snapshots) (docs)</span></span>
