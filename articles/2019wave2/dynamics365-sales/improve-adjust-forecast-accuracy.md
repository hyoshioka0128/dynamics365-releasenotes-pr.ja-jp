---
title: 予測精度の改善と調整
description: 予測をシームレスに調整して解釈を深め、精度を向上させます。
author: relnotes
ms.reviewer: udag
ms.date: 03/21/2020
ms.assetid: 842a7b5f-a738-ea11-a813-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: dandalla
dynamics365pdf: true
ms.openlocfilehash: 2f531fbada00710f1691b6ef5397af8c3b2068a8
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178881"
---
# <a name="improve-and-adjust-forecast-accuracy"></a><span data-ttu-id="a2d4a-103">予測精度の改善と調整</span><span class="sxs-lookup"><span data-stu-id="a2d4a-103">Improve and adjust forecast accuracy</span></span>


| <span data-ttu-id="a2d4a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a2d4a-104">Enabled for</span></span>    |  <span data-ttu-id="a2d4a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a2d4a-105">Public preview</span></span> | <span data-ttu-id="a2d4a-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="a2d4a-106">Early access</span></span> | <span data-ttu-id="a2d4a-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="a2d4a-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="a2d4a-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a2d4a-108">End users by admins, makers, or analysts</span></span>|-|-| <span data-ttu-id="a2d4a-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a2d4a-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a2d4a-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="a2d4a-110">Feb 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a2d4a-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a2d4a-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a2d4a-112">ボトムアップ予測は既存の営業案件データに基づいていますが、営業マネージャーは、特定の営業案件では対応に主観的な判断が必要であることを知っています。</span><span class="sxs-lookup"><span data-stu-id="a2d4a-112">Although bottom-up forecasting is based on existing opportunity data, sales managers know that in certain cases their experience requires subjective judgment.</span></span> <span data-ttu-id="a2d4a-113">販売担当者は、取引の確度や価値を正確に予測するために必要な専門知識を持っていない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a2d4a-113">Sellers might not have the expertise required to accurately predict the confidence or the value of a deal.</span></span> <span data-ttu-id="a2d4a-114">これは、販売担当者によっては、売上予算を超過する確率を高めるために、期末になるまで進行中の取引を隠すことにつながる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="a2d4a-114">This might lead some sellers to hide ongoing deals until the period comes to an end, to increase their chance of exceeding quota.</span></span>  

<span data-ttu-id="a2d4a-115">営業マネージャーが信頼性のある有意義な予測数値をリーダーに提供できるようにするために、予測は優れた柔軟性を提供します。</span><span class="sxs-lookup"><span data-stu-id="a2d4a-115">To ensure sales managers can provide leadership with meaningful forecast numbers that they trust, forecasting offers great flexibility.</span></span> <span data-ttu-id="a2d4a-116">営業マネージャーは、有効な予測値を調整することができます。</span><span class="sxs-lookup"><span data-stu-id="a2d4a-116">Sales managers are empowered to adjust any of the enabled forecast values.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a2d4a-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a2d4a-117">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="a2d4a-118">**予測をシームレスに調整**: 既存の予測または組織階層に基づいて伝播された予測値を簡単に調整できます。調整を削除したり、以前の調整に戻すことができます。</span><span class="sxs-lookup"><span data-stu-id="a2d4a-118">**Adjust forecasts seamlessly**: Easily make adjustments to any forecasted values that are propagated based on existing forecast or organizational hierarchy, including deleting adjustments or reverting back to an older adjustment.</span></span>
- <span data-ttu-id="a2d4a-119">**予測調整によって解釈を深める**: 変更に寄与する基になるレコードを特定し、調整の履歴を分析するために理由を把握します。</span><span class="sxs-lookup"><span data-stu-id="a2d4a-119">**Gain deeper understanding with forecast adjustments**: Identify the underlying records that contribute to changes and capture reasons to analyze the history of adjustments.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="a2d4a-120">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="a2d4a-120">This feature is available in the Unified Interface only.</span></span> <span data-ttu-id="a2d4a-121">この機能は、Dynamics 365 Sales Enterprise のみを対象としています。</span><span class="sxs-lookup"><span data-stu-id="a2d4a-121">This capability is intended only for Dynamics 365 Sales Enterprise.</span></span>







## <a name="see-also"></a><span data-ttu-id="a2d4a-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="a2d4a-122">See also</span></span>

<span data-ttu-id="a2d4a-123">[予測の値を調整する](https://docs.microsoft.com/dynamics365/sales-enterprise/adjust-values-in-forecast) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="a2d4a-123">[Adjust values in a forecast](https://docs.microsoft.com/dynamics365/sales-enterprise/adjust-values-in-forecast) (docs)</span></span>
