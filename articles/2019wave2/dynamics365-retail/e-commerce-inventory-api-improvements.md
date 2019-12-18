---
title: eコマース在庫 API の改善
description: この機能で導入される新しい API を使用して、小売業者は在庫の利用可能性を見積もることができます。 これらの API によって提供される情報を eコマース アプリケーションで使用し、商品を出荷または店頭での集荷に使用できるかどうかを顧客に知らせることができます。 この目的のために以前提供されていた既存の API はパフォーマンスが良くなく、計算ロジックも最適ではありませんでした。
author: hhainesms
ms.reviewer: rhaertle
ms.date: 11/15/2019
ms.assetid: c5ff120b-f182-e911-a98e-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: d07b1fa54be8c54cecc1f273880db8e378f9493c
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2890159"
---
# <a name="e-commerce-inventory-api-improvements"></a><span data-ttu-id="812ca-105">eコマース在庫 API の改善</span><span class="sxs-lookup"><span data-stu-id="812ca-105">E-commerce inventory API improvements</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="812ca-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="812ca-106">Enabled for</span></span>    |  <span data-ttu-id="812ca-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="812ca-107">Public preview</span></span> | <span data-ttu-id="812ca-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="812ca-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="812ca-109">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="812ca-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="812ca-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="812ca-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="812ca-111">2019 年 10 月 21 日</span><span class="sxs-lookup"><span data-stu-id="812ca-111">Oct 21, 2019</span></span>| <span data-ttu-id="812ca-112">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="812ca-112">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="812ca-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="812ca-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="812ca-114">企業は、推定される手持ち商品の在庫の利用可能性を入手するために、信頼性の高い高性能な API を必要としています。</span><span class="sxs-lookup"><span data-stu-id="812ca-114">Businesses need reliable, performant APIs to obtain estimated on-hand item inventory availability.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="812ca-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="812ca-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="812ca-116">新しい API では、要求された商品と倉庫に対する手持ち在庫の見積もりが提供されます。</span><span class="sxs-lookup"><span data-stu-id="812ca-116">New APIs will provide an estimation of on-hand inventory for a requested item and warehouses.</span></span> <span data-ttu-id="812ca-117">これらの API は、現在提供されている既存の GetProductAvailability および GetAvailableInventoryNearby API に代わるものです。</span><span class="sxs-lookup"><span data-stu-id="812ca-117">These APIs replace the existing GetProductAvailabilities and GetAvailableInventoryNearby APIs that are currently in-market.</span></span> <span data-ttu-id="812ca-118">これらの新しい API では、パフォーマンスを向上させるために計算ロジックとキャッシュが改善されています。</span><span class="sxs-lookup"><span data-stu-id="812ca-118">These new APIs have improved calculation logic and caching to improve performance.</span></span>

<span data-ttu-id="812ca-119">さらに、新しいパラメーターにより、これらの新しい API が取り込まれ、商品の既定の注文設定に基づいてカート注文明細を調達するための "最善" の倉庫の検索が試みられる現在の API の既存の高コスト ロジックがオフになります。</span><span class="sxs-lookup"><span data-stu-id="812ca-119">Additionally, new parameters will uptake these new APIs as well as turn off the existing expensive logic of the current APIs that attempted to find the "best" warehouse to source the cart order lines based on default order settings for the item.</span></span> <span data-ttu-id="812ca-120">このロジックは新しい API には含まれません。</span><span class="sxs-lookup"><span data-stu-id="812ca-120">This logic will not be in the new APIs.</span></span> <span data-ttu-id="812ca-121">組織では、将来の分散型注文管理機能を使用して、店頭以外で集配される販売明細行向けに最適なフルフィルメント場所を選択できます。したがって、この高コストのロジックは新しい API には含まれなくなります。</span><span class="sxs-lookup"><span data-stu-id="812ca-121">Organizations can choose to use our Distributed Order Management functionality in the future to enable optimized fulfillment location selection for non-in-store pickup saleslines; therefore, this expensive logic will no longer be part of the new APIs.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="812ca-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="812ca-122">See also</span></span>

<span data-ttu-id="812ca-123">[Retail POS API](https://docs.microsoft.com/dynamics365/retail/dev-itpro/pos-apis) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="812ca-123">[Retail POS APIs](https://docs.microsoft.com/dynamics365/retail/dev-itpro/pos-apis) (docs)</span></span>
