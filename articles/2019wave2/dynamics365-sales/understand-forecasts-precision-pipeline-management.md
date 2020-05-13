---
title: 高精度パイプライン管理で予測を理解する
description: 関係するレコードの簡単な管理、明確な視覚化、ほぼリアルタイムの更新が可能であり、これによって精度が向上します。
author: relnotes
ms.reviewer: udag
ms.date: 03/21/2020
ms.assetid: c20ab2a8-a738-ea11-a813-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: dandalla
dynamics365pdf: true
ms.openlocfilehash: 446c5dfcf5cfdc2684f4337775de2b731292b10a
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178474"
---
# <a name="understand-forecasts-with-precision-pipeline-management"></a><span data-ttu-id="af499-103">高精度パイプライン管理で予測を理解する</span><span class="sxs-lookup"><span data-stu-id="af499-103">Understand forecasts with precision pipeline management</span></span>


| <span data-ttu-id="af499-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="af499-104">Enabled for</span></span>    |  <span data-ttu-id="af499-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="af499-105">Public preview</span></span> | <span data-ttu-id="af499-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="af499-106">Early access</span></span> | <span data-ttu-id="af499-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="af499-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="af499-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="af499-108">End users by admins, makers, or analysts</span></span>|-|-| <span data-ttu-id="af499-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="af499-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="af499-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="af499-110">Feb 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="af499-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="af499-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="af499-112">予測には多くの情報、そして場合によっては深い階層が含まれることがあります。</span><span class="sxs-lookup"><span data-stu-id="af499-112">A forecast can contain a lot of information and in some cases a deep hierarchy.</span></span> <span data-ttu-id="af499-113">多くの場合、組織の予測と機会はばらばらです。</span><span class="sxs-lookup"><span data-stu-id="af499-113">Often, the organization’s forecast and opportunities are disjointed.</span></span> <span data-ttu-id="af499-114">営業担当者と営業マネージャーは、こうしたギャップを解決するのに役立つ必要な変更を導入するために、予測値の取得元を理解する必要があります。</span><span class="sxs-lookup"><span data-stu-id="af499-114">Sellers and sales managers need to understand where forecast values are coming from in order to introduce necessary changes that can help to resolve these gaps.</span></span> <span data-ttu-id="af499-115">Dynamics 365 Sales の予測機能では、予測と基礎となる営業案件データの両方が 1 つの滑らかなエクスペリエンスの一部であるため、販売担当者はフロー内の取引情報を直接変更し、反映された予測の変化を即座に確認できます。</span><span class="sxs-lookup"><span data-stu-id="af499-115">In the forecasting capabilities for Dynamics 365 Sales, both the forecast and the underlying opportunity data are part of one fluid experience, allowing sellers to directly modify deal information in the flow and to instantly see changes to the forecast reflected.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="af499-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="af499-116">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="af499-117">**視覚的なキューを備えた応答型予測グリッドのメリット**: グリッドから直接、予測階層全体と各セルの売上予算の達成度を視覚的に表示できます。</span><span class="sxs-lookup"><span data-stu-id="af499-117">**Benefit from a responsive forecast grid with visual cues**: Enable visual representation of the whole forecast hierarchy and quota attainment in each cell, directly from the grid.</span></span>
- <span data-ttu-id="af499-118">**関連するレコードをインラインで編集する**: 計算されたメトリックの基礎となる営業案件を表示および編集して、予測を即座に変更します。</span><span class="sxs-lookup"><span data-stu-id="af499-118">**Edit participating records inline**: View and edit underlying opportunities for any calculated metric to instantly modify the forecast.</span></span>
- <span data-ttu-id="af499-119">**パイプラインと視覚化を管理する**: ドラッグアンドドロップ機能を使用することで営業案件をさまざまな段階に移動することで、予測全体を簡単に管理して更新し、予測データを即座に更新できます。</span><span class="sxs-lookup"><span data-stu-id="af499-119">**Manage pipeline and visualization**: Easily manage and update the full forecast with the drag-and-drop feature to move opportunities across different stages, to instantly update forecast data.</span></span>
- <span data-ttu-id="af499-120">**ほぼリアルタイムの更新のメリット**: 予測値の自動再計算を利用することで、常に可能な限り最新のデータを確認できます。</span><span class="sxs-lookup"><span data-stu-id="af499-120">**Benefit from near real-time updates**: Enjoy automatic recalculation of forecast values to ensure data is always as fresh as possible.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="af499-121">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="af499-121">This feature is available in the Unified Interface only.</span></span>







## <a name="see-also"></a><span data-ttu-id="af499-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="af499-122">See also</span></span>

<span data-ttu-id="af499-123">[基になる営業案件の表示および管理](https://docs.microsoft.com/dynamics365/sales-enterprise/view-and-manage-underlying-opportunities) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="af499-123">[View and manage underlying opportunities](https://docs.microsoft.com/dynamics365/sales-enterprise/view-and-manage-underlying-opportunities) (docs)</span></span>
