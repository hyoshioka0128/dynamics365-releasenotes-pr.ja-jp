---
title: eコマース在庫 API の改善
description: この機能で導入される新しい API を利用して、小売業者は在庫の利用可能性を見積もることができます。 これらの API によって提供される情報を eコマース アプリケーションで使用し、商品を出荷または店頭での集荷に使用できるかどうかを顧客に知らせることができます。 この目的のために以前提供されていた既存の API はパフォーマンスが良くなく、計算ロジックも最適ではありませんでした。
author: hhainesms
ms.reviewer: rhaertl
ms.date: 06/18/2019
ms.assetid: c5ff120b-f182-e911-a98e-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 68da7e13b521516efc606df9d4169b1ff8ed9bd0
ms.sourcegitcommit: 4620697dc1f4fc6903504a55406f3d22af75e361
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1693772"
---
# <a name="e-commerce-inventory-api-improvements"></a><span data-ttu-id="119ce-105">eコマース在庫 API の改善</span><span class="sxs-lookup"><span data-stu-id="119ce-105">E-commerce Inventory API improvements</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="119ce-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="119ce-106">Enabled for</span></span>    |  <span data-ttu-id="119ce-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="119ce-107">Public preview</span></span> | <span data-ttu-id="119ce-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="119ce-108">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="119ce-109">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="119ce-109">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="119ce-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="119ce-110">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="119ce-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="119ce-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="119ce-112">企業は、推定される手持ち商品の在庫の利用可能性を入手するために、信頼性の高い高性能な API を必要としています。</span><span class="sxs-lookup"><span data-stu-id="119ce-112">Businesses need reliable performant APIs to obtain estimated on-hand item inventory availability.</span></span>  
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="119ce-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="119ce-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="119ce-114">新しい API では、要求された商品と倉庫に対する手持ち在庫の見積もりが提供されます。</span><span class="sxs-lookup"><span data-stu-id="119ce-114">New APIs will provide an estimation of on-hand inventory for a requested item and warehouses.</span></span> <span data-ttu-id="119ce-115">これらの API は、現在提供されている既存の GetProductAvailability および GetAvailableInventoryNearby API に代わるものです。</span><span class="sxs-lookup"><span data-stu-id="119ce-115">These APIs replace the existing GetProductAvailabilities and GetAvailableInventoryNearby APIs that are currently in-market.</span></span> <span data-ttu-id="119ce-116">これらの新しい API では、パフォーマンスを向上させるために計算ロジックとキャッシュが改善されています。</span><span class="sxs-lookup"><span data-stu-id="119ce-116">These new APIs have improved calculation logic and caching to improve performance.</span></span>

<span data-ttu-id="119ce-117">さらに、新しいパラメーターにより、これらの新しい API が取り込まれ、商品の既定の注文設定に基づいてカート注文明細を調達するための "最善" の倉庫の検索が試みられる現在の API の既存の高コスト ロジックがオフになります。</span><span class="sxs-lookup"><span data-stu-id="119ce-117">Additionally, new parameters will uptake these new APIs as well as turn off the existing expensive logic of the current APIs that attempted to find the "best" warehouse to source the cart order lines based on default order settings for the item.</span></span> <span data-ttu-id="119ce-118">このロジックは新しい API には含まれません。</span><span class="sxs-lookup"><span data-stu-id="119ce-118">This logic will not be in the new APIs.</span></span> <span data-ttu-id="119ce-119">組織では、将来の分散型注文管理機能を利用して、店頭以外で集配される販売明細行向けに最適なフルフィルメント場所を選択できます。したがって、この高コストのロジックは新しい API には含まれなくなります。</span><span class="sxs-lookup"><span data-stu-id="119ce-119">Organizations can choose to utilize our Distributed Order Management functionality in the future to enable optimized fulfillment location selection for non in-store pickup saleslines; therefore, this expensive logic will no longer be part of the new APIs.</span></span>
<!--feature detail end -->










