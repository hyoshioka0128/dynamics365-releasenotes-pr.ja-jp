---
title: eコマース在庫 API の改善
description: この機能で導入される新しい API を使用して、小売業者は在庫の利用可能性を見積もることができます。 これらの API によって提供される情報を eコマース アプリケーションで使用し、商品を出荷または店頭での集荷に使用できるかどうかを顧客に知らせることができます。 この目的のために以前提供されていた既存の API はパフォーマンスが良くなく、計算ロジックも最適ではありませんでした。
author: hhainesms
ms.reviewer: rhaertle
ms.date: 03/09/2020
ms.assetid: c5ff120b-f182-e911-a98e-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: afb55f45b5419f3bed25664bc2810d8a79da5848
ms.sourcegitcommit: 8756c08fc492e62cc366fa85ee3e510af3d16f70
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/18/2020
ms.locfileid: "3139591"
---
# <a name="e-commerce-inventory-api-improvements"></a><span data-ttu-id="702bd-105">eコマース在庫 API の改善</span><span class="sxs-lookup"><span data-stu-id="702bd-105">E-commerce inventory API improvements</span></span>


| <span data-ttu-id="702bd-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="702bd-106">Enabled for</span></span>    |  <span data-ttu-id="702bd-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="702bd-107">Public preview</span></span> | <span data-ttu-id="702bd-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="702bd-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="702bd-109">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="702bd-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="702bd-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="702bd-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="702bd-111">2019 年 10 月 21 日</span><span class="sxs-lookup"><span data-stu-id="702bd-111">Oct 21, 2019</span></span>| <span data-ttu-id="702bd-112">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="702bd-112">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="702bd-113">2020 年 1 月 1 日</span><span class="sxs-lookup"><span data-stu-id="702bd-113">Jan 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="702bd-114">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="702bd-114">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="702bd-115">企業は、推定される手持ち商品の在庫の利用可能性を入手するために、信頼性の高い高性能な API を必要としています。</span><span class="sxs-lookup"><span data-stu-id="702bd-115">Businesses need reliable, performant APIs to obtain estimated on-hand item inventory availability.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="702bd-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="702bd-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="702bd-117">新しい API では、要求された商品と倉庫に対する手持ち在庫の見積もりが提供されます。</span><span class="sxs-lookup"><span data-stu-id="702bd-117">New APIs will provide an estimation of on-hand inventory for a requested item and warehouses.</span></span> <span data-ttu-id="702bd-118">これらの API は、現在提供されている既存の GetProductAvailability および GetAvailableInventoryNearby API に代わるものです。</span><span class="sxs-lookup"><span data-stu-id="702bd-118">These APIs replace the existing GetProductAvailabilities and GetAvailableInventoryNearby APIs that are currently in-market.</span></span> <span data-ttu-id="702bd-119">これらの新しい API では、パフォーマンスを向上させるために計算ロジックとキャッシュが改善されています。</span><span class="sxs-lookup"><span data-stu-id="702bd-119">These new APIs have improved calculation logic and caching to improve performance.</span></span>

<span data-ttu-id="702bd-120">さらに、新しいパラメーターにより、これらの新しい API が取り込まれ、商品の既定の注文設定に基づいてカート注文明細を調達するための "最善" の倉庫の検索が試みられる現在の API の既存の高コスト ロジックがオフになります。</span><span class="sxs-lookup"><span data-stu-id="702bd-120">Additionally, new parameters will uptake these new APIs as well as turn off the existing expensive logic of the current APIs that attempted to find the "best" warehouse to source the cart order lines based on default order settings for the item.</span></span> <span data-ttu-id="702bd-121">このロジックは新しい API には含まれません。</span><span class="sxs-lookup"><span data-stu-id="702bd-121">This logic will not be in the new APIs.</span></span> <span data-ttu-id="702bd-122">組織では、将来の分散型注文管理機能を使用して、店頭以外で集配される販売明細行向けに最適なフルフィルメント場所を選択できます。したがって、この高コストのロジックは新しい API には含まれなくなります。</span><span class="sxs-lookup"><span data-stu-id="702bd-122">Organizations can choose to use our Distributed Order Management functionality in the future to enable optimized fulfillment location selection for non-in-store pickup saleslines; therefore, this expensive logic will no longer be part of the new APIs.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="702bd-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="702bd-123">See also</span></span>

<span data-ttu-id="702bd-124">[小売チャネルの引当可能在庫数量の計算](https://docs.microsoft.com/dynamics365/commerce/calculated-inventory-retail-channels) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="702bd-124">[Calculate inventory availability for retail channels](https://docs.microsoft.com/dynamics365/commerce/calculated-inventory-retail-channels) (docs)</span></span>
