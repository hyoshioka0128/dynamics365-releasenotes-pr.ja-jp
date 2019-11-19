---
title: eコマース在庫 API の改善
description: この機能で導入される新しい API を使用して、小売業者は在庫の利用可能性を見積もることができます。 これらの API によって提供される情報を eコマース アプリケーションで使用し、商品を出荷または店頭での集荷に使用できるかどうかを顧客に知らせることができます。 この目的のために以前提供されていた既存の API はパフォーマンスが良くなく、計算ロジックも最適ではありませんでした。
author: hhainesms
ms.reviewer: rhaertle
ms.date: 08/13/2019
ms.assetid: c5ff120b-f182-e911-a98e-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: b01d68ba8e10578cfafa024222d836257d8ae221
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2659883"
---
# <a name="e-commerce-inventory-api-improvements"></a><span data-ttu-id="774dd-105">eコマース在庫 API の改善</span><span class="sxs-lookup"><span data-stu-id="774dd-105">E-commerce inventory API improvements</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="774dd-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="774dd-106">Enabled for</span></span>    |  <span data-ttu-id="774dd-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="774dd-107">Public preview</span></span> | <span data-ttu-id="774dd-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="774dd-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="774dd-109">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="774dd-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="774dd-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="774dd-110">Oct 2019</span></span>| <span data-ttu-id="774dd-111">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="774dd-111">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="774dd-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="774dd-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="774dd-113">企業は、推定される手持ち商品の在庫の利用可能性を入手するために、信頼性の高い高性能な API を必要としています。</span><span class="sxs-lookup"><span data-stu-id="774dd-113">Businesses need reliable, performant APIs to obtain estimated on-hand item inventory availability.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="774dd-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="774dd-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="774dd-115">新しい API では、要求された商品と倉庫に対する手持ち在庫の見積もりが提供されます。</span><span class="sxs-lookup"><span data-stu-id="774dd-115">New APIs will provide an estimation of on-hand inventory for a requested item and warehouses.</span></span> <span data-ttu-id="774dd-116">これらの API は、現在提供されている既存の GetProductAvailability および GetAvailableInventoryNearby API に代わるものです。</span><span class="sxs-lookup"><span data-stu-id="774dd-116">These APIs replace the existing GetProductAvailabilities and GetAvailableInventoryNearby APIs that are currently in-market.</span></span> <span data-ttu-id="774dd-117">これらの新しい API では、パフォーマンスを向上させるために計算ロジックとキャッシュが改善されています。</span><span class="sxs-lookup"><span data-stu-id="774dd-117">These new APIs have improved calculation logic and caching to improve performance.</span></span>

<span data-ttu-id="774dd-118">さらに、新しいパラメーターにより、これらの新しい API が取り込まれ、商品の既定の注文設定に基づいてカート注文明細を調達するための "最善" の倉庫の検索が試みられる現在の API の既存の高コスト ロジックがオフになります。</span><span class="sxs-lookup"><span data-stu-id="774dd-118">Additionally, new parameters will uptake these new APIs as well as turn off the existing expensive logic of the current APIs that attempted to find the "best" warehouse to source the cart order lines based on default order settings for the item.</span></span> <span data-ttu-id="774dd-119">このロジックは新しい API には含まれません。</span><span class="sxs-lookup"><span data-stu-id="774dd-119">This logic will not be in the new APIs.</span></span> <span data-ttu-id="774dd-120">組織では、将来の分散型注文管理機能を使用して、店頭以外で集配される販売明細行向けに最適なフルフィルメント場所を選択できます。したがって、この高コストのロジックは新しい API には含まれなくなります。</span><span class="sxs-lookup"><span data-stu-id="774dd-120">Organizations can choose to use our Distributed Order Management functionality in the future to enable optimized fulfillment location selection for non-in-store pickup saleslines; therefore, this expensive logic will no longer be part of the new APIs.</span></span>
<!--feature detail end -->









