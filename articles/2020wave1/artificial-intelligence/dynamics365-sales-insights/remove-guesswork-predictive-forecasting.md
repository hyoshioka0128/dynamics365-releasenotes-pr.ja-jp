---
title: 見通し予測で当て推量を取り除く
description: ''
author: relnotes
ms.reviewer: udag
ms.date: 02/10/2020
ms.assetid: 0950d5ae-d0ca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: dandalla
dynamics365pdf: true
ms.openlocfilehash: 03bf07dd0072a1fc340def8c5a672534644b8692
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3080074"
---
# <a name="remove-the-guesswork-with-predictive-forecasting"></a><span data-ttu-id="00357-102">見通し予測で当て推量を取り除く</span><span class="sxs-lookup"><span data-stu-id="00357-102">Remove the guesswork with predictive forecasting</span></span>
[!include[artificial-intelligence/dynamics365-sales-insights banner](../includes/artificial-intelligence/dynamics365-sales-insights.md)]

| <span data-ttu-id="00357-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="00357-103">Enabled for</span></span>    |  <span data-ttu-id="00357-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="00357-104">Public preview</span></span> | <span data-ttu-id="00357-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="00357-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="00357-106">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="00357-106">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="00357-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="00357-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="00357-108">2020 年 2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="00357-108">Feb 7, 2020</span></span>| <span data-ttu-id="00357-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="00357-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="00357-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="00357-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="00357-111">販売データが増加することで、ビジネス上の意思決定に情報を提供し、販売のパフォーマンスを向上させるユニークな機会が得られます。</span><span class="sxs-lookup"><span data-stu-id="00357-111">Growing volumes of sales data offer a unique opportunity to inform business decisions and enhance sales performance.</span></span> <span data-ttu-id="00357-112">販売組織は、大規模な販売データを使用して予測性を変革し、より包括的で信頼性の高い販売予測を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="00357-112">Sales organizations can transform forecasting with large-scale sales data to make more comprehensive and reliable sales predictions.</span></span>

<span data-ttu-id="00357-113">見通し予測は、客観的なデータ主導型の予測により、主観的なボトムアップ予測を補完します。</span><span class="sxs-lookup"><span data-stu-id="00357-113">Predictive forecasting complements subjective bottom-up projections with objective data-driven forecasts.</span></span> <span data-ttu-id="00357-114">履歴データとパイプライン データを共に活用することで、より正確に偏りなく売上を予測できます。</span><span class="sxs-lookup"><span data-stu-id="00357-114">By leveraging both historical and pipeline data, sales managers can forecast sales more accurately and without bias.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="00357-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="00357-115">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="00357-116">**過去の証拠を探る**: 主観的なボトムアップ予測を見通し予測で補完し、手作業を介さずに矛盾や不整合を特定します。</span><span class="sxs-lookup"><span data-stu-id="00357-116">**Explore historical evidence**: Complement subjective bottom-up forecasts with predictive projections to identify discrepancies or inconsistencies without manual effort.</span></span>
- <span data-ttu-id="00357-117">**既存のデータを活用する**: 実際のパフォーマンスと予測を直接比較して、取引獲得数が予測に対してどのように推移しているかを視覚的に対比します。</span><span class="sxs-lookup"><span data-stu-id="00357-117">**Leverage your existing data**: Compare actual performance directly against predictions to visually contrast how the number of deals won is pacing against predictions.</span></span> <span data-ttu-id="00357-118">この予測モデルは、過去の取引や進行中の情報ルートからすべての関連データを収集し、最も影響のあるシグナルを特定します。</span><span class="sxs-lookup"><span data-stu-id="00357-118">The predictive model captures all related data from past deals and open pipelines to identify signals that have the most impact.</span></span>
<!--feature detail end -->

<span data-ttu-id="00357-119">![実際の結果と予測値を比較する](media/forecasting_predictive.png "実際の結果と予測値を比較する")</span><span class="sxs-lookup"><span data-stu-id="00357-119">![Compare actual results against predicted values](media/forecasting_predictive.png "Compare actual results against predicted values")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="00357-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="00357-120">See also</span></span>

<span data-ttu-id="00357-121">[見通し予測を使用して収益の結果を分析する](https://docs.microsoft.com/dynamics365/ai/sales/analyze-revenue-outcome-using-predictive-forecasting) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="00357-121">[Analyze revenue outcome by using predictive forecasting](https://docs.microsoft.com/dynamics365/ai/sales/analyze-revenue-outcome-using-predictive-forecasting) (docs)</span></span>
