---
title: 見通し予測で当て推量を取り除く
description: 見通し予測で当て推量を取り除く
author: relnotes
ms.reviewer: udag
ms.date: 04/24/2020
ms.assetid: 0950d5ae-d0ca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: dandalla
dynamics365pdf: true
ms.openlocfilehash: 2504ab01d30297dbda4a2666e8d7fd5378377046
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294360"
---
# <a name="remove-the-guesswork-with-predictive-forecasting"></a><span data-ttu-id="79a6b-103">見通し予測で当て推量を取り除く</span><span class="sxs-lookup"><span data-stu-id="79a6b-103">Remove the guesswork with predictive forecasting</span></span>


| <span data-ttu-id="79a6b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="79a6b-104">Enabled for</span></span>    |  <span data-ttu-id="79a6b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="79a6b-105">Public preview</span></span> | <span data-ttu-id="79a6b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="79a6b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="79a6b-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="79a6b-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="79a6b-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="79a6b-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="79a6b-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="79a6b-109">Feb 3, 2020</span></span>| <span data-ttu-id="79a6b-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="79a6b-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="79a6b-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="79a6b-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="79a6b-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="79a6b-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="79a6b-113">販売データが増加することで、ビジネス上の意思決定に情報を提供し、販売のパフォーマンスを向上させるユニークな機会が得られます。</span><span class="sxs-lookup"><span data-stu-id="79a6b-113">Growing volumes of sales data offer a unique opportunity to inform business decisions and enhance sales performance.</span></span> <span data-ttu-id="79a6b-114">販売組織は、大規模な販売データを使用して予測性を変革し、より包括的で信頼性の高い販売予測を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="79a6b-114">Sales organizations can transform forecasting with large-scale sales data to make more comprehensive and reliable sales predictions.</span></span>

<span data-ttu-id="79a6b-115">見通し予測は、客観的なデータ主導型の予測により、主観的なボトムアップ予測を補完します。</span><span class="sxs-lookup"><span data-stu-id="79a6b-115">Predictive forecasting complements subjective bottom-up projections with objective data-driven forecasts.</span></span> <span data-ttu-id="79a6b-116">履歴データとパイプライン データを共に活用することで、より正確に偏りなく売上を予測できます。</span><span class="sxs-lookup"><span data-stu-id="79a6b-116">By leveraging both historical and pipeline data, sales managers can forecast sales more accurately and without bias.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="79a6b-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="79a6b-117">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="79a6b-118">**過去の証拠を探る**: 主観的なボトムアップ予測を見通し予測で補完し、手作業を介さずに矛盾や不整合を特定します。</span><span class="sxs-lookup"><span data-stu-id="79a6b-118">**Explore historical evidence**: Complement subjective bottom-up forecasts with predictive projections to identify discrepancies or inconsistencies without manual effort.</span></span>
- <span data-ttu-id="79a6b-119">**既存のデータを活用する**: 実際のパフォーマンスと予測を直接比較して、取引獲得数が予測に対してどのように推移しているかを視覚的に対比します。</span><span class="sxs-lookup"><span data-stu-id="79a6b-119">**Leverage your existing data**: Compare actual performance directly against predictions to visually contrast how the number of deals won is pacing against predictions.</span></span> <span data-ttu-id="79a6b-120">この予測モデルは、過去の取引や進行中の情報ルートからすべての関連データを収集し、最も影響のあるシグナルを特定します。</span><span class="sxs-lookup"><span data-stu-id="79a6b-120">The predictive model captures all related data from past deals and open pipelines to identify signals that have the most impact.</span></span>
<!--feature detail end -->

<span data-ttu-id="79a6b-121">![実際の結果と予測値を比較する](media/forecasting_predictive.png "実際の結果と予測値を比較する")</span><span class="sxs-lookup"><span data-stu-id="79a6b-121">![Compare actual results against predicted values](media/forecasting_predictive.png "Compare actual results against predicted values")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="79a6b-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="79a6b-122">See also</span></span>

<!--blog start-->
<span data-ttu-id="79a6b-123">[Dynamics 365 Sales の高度な予測による説明責任の推進](https://aka.ms/forecasting.blog) (ブログ)</span><span class="sxs-lookup"><span data-stu-id="79a6b-123">[Driving accountability with advanced forecasting in Dynamics 365 Sales](https://aka.ms/forecasting.blog) (blog)</span></span>
<!--blog end-->

<!--docs start-->
<span data-ttu-id="79a6b-124">[見通し予測を使用して収益の結果を分析する](https://docs.microsoft.com/dynamics365/ai/sales/analyze-revenue-outcome-using-predictive-forecasting) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="79a6b-124">[Analyze revenue outcome by using predictive forecasting](https://docs.microsoft.com/dynamics365/ai/sales/analyze-revenue-outcome-using-predictive-forecasting) (docs)</span></span>
<!--docs end-->
