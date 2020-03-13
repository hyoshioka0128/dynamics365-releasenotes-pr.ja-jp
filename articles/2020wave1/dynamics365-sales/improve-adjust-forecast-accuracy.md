---
title: 予測精度の改善と調整
description: 予測をシームレスに調整して解釈を深め、精度を向上させます。
author: relnotes
ms.reviewer: udag
ms.date: 02/10/2020
ms.assetid: d95dbaff-4ad5-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: dandalla
dynamics365pdf: true
ms.openlocfilehash: d402ab3a558dae164d39493541a6aab898f373e8
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3079491"
---
# <a name="improve-and-adjust-forecast-accuracy"></a><span data-ttu-id="86299-103">予測精度の改善と調整</span><span class="sxs-lookup"><span data-stu-id="86299-103">Improve and adjust forecast accuracy</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="86299-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="86299-104">Enabled for</span></span>    |  <span data-ttu-id="86299-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="86299-105">Public preview</span></span> | <span data-ttu-id="86299-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="86299-106">Early access</span></span> | <span data-ttu-id="86299-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="86299-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="86299-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="86299-108">End users, automatically</span></span>|-|<span data-ttu-id="86299-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="86299-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="86299-110">2020 年 2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="86299-110">Feb 7, 2020</span></span>| <span data-ttu-id="86299-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="86299-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="86299-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="86299-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="86299-113">ボトムアップ予測は既存の営業案件データに基づいていますが、営業マネージャーは、特定の営業案件では対応に主観的な判断が必要であることを知っています。</span><span class="sxs-lookup"><span data-stu-id="86299-113">Although bottom-up forecasting is based on existing opportunity data, sales managers know that in certain cases their experience requires subjective judgment.</span></span> <span data-ttu-id="86299-114">販売担当者には、取引の確度や価値を正確に予測するために必要な専門知識がない場合があります。</span><span class="sxs-lookup"><span data-stu-id="86299-114">Sellers may not have the expertise required to accurately predict the confidence or the value of a deal.</span></span> <span data-ttu-id="86299-115">これは、販売担当者によっては、売上予算を超過する確率を高めるために、期末になるまで進行中の取引を隠すことにつながる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="86299-115">This may lead some sellers to hide ongoing deals until the period comes to an end, to increase their chance of exceeding quota.</span></span>  

<span data-ttu-id="86299-116">営業マネージャーが信頼性のある有意義な予測数値をリーダーに提供できるようにするために、予測は優れた柔軟性を提供します。</span><span class="sxs-lookup"><span data-stu-id="86299-116">To ensure sales managers can provide leadership with meaningful forecast numbers that they trust, forecasting offers great flexibility.</span></span> <span data-ttu-id="86299-117">営業マネージャーは、有効な予測値を調整することができます。</span><span class="sxs-lookup"><span data-stu-id="86299-117">Sales managers are empowered to adjust any of the enabled forecast values.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="86299-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="86299-118">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="86299-119">**予測をシームレスに調整**: 既存の予測または組織階層に基づいて伝播された予測値を簡単に調整できます。調整を削除したり、以前の調整に戻すことができます。</span><span class="sxs-lookup"><span data-stu-id="86299-119">**Adjust forecasts seamlessly**: Easily make adjustments to any forecasted values that are propagated based on existing forecast or organizational hierarchy, including deleting adjustments or reverting back to an older adjustment.</span></span>
- <span data-ttu-id="86299-120">**予測調整によって解釈を深める**: 変更に寄与する基になるレコードを特定し、調整の履歴を分析するために変更の理由を把握します。</span><span class="sxs-lookup"><span data-stu-id="86299-120">**Gain deeper understanding with forecast adjustments**: Identify the underlying records that contribute to changes and capture the reasons for the changes in order to analyze the history of adjustments.</span></span>
<!--feature detail end -->

<span data-ttu-id="86299-121">![メモで予測を調整し、履歴を表示する](media/forecasting_adjustment.png "メモで予測を調整し、履歴を表示する")</span><span class="sxs-lookup"><span data-stu-id="86299-121">![Adjust the forecast with notes and view the history](media/forecasting_adjustment.png "Adjust the forecast with notes and view the history")</span></span>
<!-- Picture 1 -->

> [!NOTE]
> <span data-ttu-id="86299-122">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="86299-122">This feature is available in the Unified Interface only.</span></span> 
>
> <span data-ttu-id="86299-123">この機能は、Dynamics 365 Sales Enterprise のみを対象としています。</span><span class="sxs-lookup"><span data-stu-id="86299-123">This capability is intended only for Dynamics 365 Sales Enterprise.</span></span>







## <a name="see-also"></a><span data-ttu-id="86299-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="86299-124">See also</span></span>

<span data-ttu-id="86299-125">[予測の値を調整する](https://docs.microsoft.com/dynamics365/sales-enterprise/adjust-values-in-forecast) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="86299-125">[Adjust values in a forecast](https://docs.microsoft.com/dynamics365/sales-enterprise/adjust-values-in-forecast) (docs)</span></span>
