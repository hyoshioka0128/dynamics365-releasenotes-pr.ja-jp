---
title: 営業案件に製品を追加するエクスペリエンスの強化
description: カタログから製品を直接検索できます。 製品の詳細をインラインで調べ、製品を比較して、情報に基づいた選択を行うことができます。 一度に複数の製品を追加できます。
author: relnotes
ms.reviewer: shujoshi
ms.date: 02/04/2020
ms.assetid: 0989253e-61cb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: naitikds
dynamics365pdf: true
ms.openlocfilehash: a5f8356580877827ea17e2849cb2e596f9f82734
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3032135"
---
# <a name="enhanced-experience-for-adding-products-to-opportunities"></a><span data-ttu-id="e323f-105">営業案件に製品を追加するエクスペリエンスの強化</span><span class="sxs-lookup"><span data-stu-id="e323f-105">Enhanced experience for adding products to opportunities</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="e323f-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="e323f-106">Enabled for</span></span>    |  <span data-ttu-id="e323f-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e323f-107">Public preview</span></span> | <span data-ttu-id="e323f-108">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="e323f-108">Early access</span></span> | <span data-ttu-id="e323f-109">一般提供</span><span class="sxs-lookup"><span data-stu-id="e323f-109">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="e323f-110">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="e323f-110">End users by admins, makers, or analysts</span></span>|-|<span data-ttu-id="e323f-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e323f-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e323f-112">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="e323f-112">Feb 3, 2020</span></span>| <span data-ttu-id="e323f-113">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="e323f-113">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="e323f-114">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e323f-114">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e323f-115">Dynamics 365 Sales では、パイプライン管理、製品調達、営業全体の追跡に利用される、膨大な量の顧客情報が保持されます。</span><span class="sxs-lookup"><span data-stu-id="e323f-115">Dynamics 365 Sales holds a vast amount of customer information that feeds into pipeline management, product procurement, and overall sales tracking.</span></span> <span data-ttu-id="e323f-116">これらが適切に管理されるようにするためには、営業案件に顧客の関心が正確に反映されている必要があります。</span><span class="sxs-lookup"><span data-stu-id="e323f-116">To ensure these are managed properly, opportunities must accurately reflect customer interest.</span></span> <span data-ttu-id="e323f-117">これを実現するために、販売担当者はたとえ幅広い製品を管理していても、各製品の購入意志が即時に反映されるように営業案件を定期的に更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e323f-117">To achieve this, sellers are required to update opportunities regularly to reflect the purchase intent for every product, as it arises, even if sellers manage a wide range of products.</span></span> 

<span data-ttu-id="e323f-118">営業案件を最新の状態に保つことは、販売活動やその他の多くの反復的な作業と競合します。つまり、多くの場合、製品情報は除外されるか、顧客の最新の関心が反映されるように更新されません。</span><span class="sxs-lookup"><span data-stu-id="e323f-118">Keeping opportunities current competes with selling activities as well as many other repetitive tasks, which means oftentimes, product information is either excluded or not updated to reflect the latest customer interest.</span></span> <span data-ttu-id="e323f-119">2020 年リリース ウェーブ 1 では、製品と営業案件の照合が簡単かつ迅速になり、ストレスが減って販売担当者のモチベーションが上がります。</span><span class="sxs-lookup"><span data-stu-id="e323f-119">In the 2020 release wave 1, we simplify and expedite matching products to opportunities, reducing friction and motivating sellers.</span></span> <span data-ttu-id="e323f-120">この機能により、販売担当者は最小限の労力で、迅速かつ直感的に製品を追加できます。</span><span class="sxs-lookup"><span data-stu-id="e323f-120">With this feature, sellers can add products quickly and intuitively, with minimal effort.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e323f-121">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e323f-121">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="e323f-122">**カタログから製品を直接検索する**: 製品エンティティ内の名前列と説明列でフリー テキストに基づいて製品を検索し、見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="e323f-122">**Look up products directly from the catalog**: Search and find products based on free text across name and description columns within the Product entity.</span></span> <span data-ttu-id="e323f-123">製品ファミリまたは定義済みのビューに基づいて製品をフィルター処理できます。これにより、正しい製品を簡単かつ迅速に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="e323f-123">Filter products based on product family or predefined views to simplify and expedite finding the right product.</span></span>
- <span data-ttu-id="e323f-124">**製品の詳細をインラインで調べ、製品を比較して、情報に基づいた選択を行う**: 製品を選択する前に各製品の追加情報を確認できます。</span><span class="sxs-lookup"><span data-stu-id="e323f-124">**Explore product details inline and compare products to make an informed selection**: View additional information for each product before selecting it.</span></span>
- <span data-ttu-id="e323f-125">**一度に複数の製品を追加する**: 複数の製品を同時に選択して、時間を節約し、生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="e323f-125">**Add multiple products at once**: Select multiple products at the same time to save time and increase productivity.</span></span>
<!--feature detail end -->

<span data-ttu-id="e323f-126">![営業案件に製品を追加する](media/add-products-opportunity.png "営業案件に製品を追加する")</span><span class="sxs-lookup"><span data-stu-id="e323f-126">![Add products to an opportunity](media/add-products-opportunity.png "Add products to an opportunity")</span></span>
<!-- Picture 1 -->
<span data-ttu-id="e323f-127">![製品の詳細](media/product-details.png "製品の詳細")</span><span class="sxs-lookup"><span data-stu-id="e323f-127">![Product details](media/product-details.png "Product details")</span></span>
<!-- Picture 2 -->
<span data-ttu-id="e323f-128">![製品の検索と選択](media/search-select-products.png "製品の検索と選択")</span><span class="sxs-lookup"><span data-stu-id="e323f-128">![Search and select products](media/search-select-products.png "Search and select products")</span></span>
<!-- Picture 3 -->

> [!NOTE]
> <span data-ttu-id="e323f-129">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="e323f-129">This feature is available in the Unified Interface only.</span></span> 
>
> <span data-ttu-id="e323f-130">この機能は、Dynamics 365 Sales Enterprise で使用できます。</span><span class="sxs-lookup"><span data-stu-id="e323f-130">This capability is available in Dynamics 365 Sales Enterprise.</span></span>







## <a name="see-also"></a><span data-ttu-id="e323f-131">関連項目</span><span class="sxs-lookup"><span data-stu-id="e323f-131">See also</span></span>

<span data-ttu-id="e323f-132">[強化されたエクスペリエンスを使用して営業案件に製品を追加する](https://docs.microsoft.com/dynamics365/sales-enterprise/add-products-enhanced-experience) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="e323f-132">[Add products to an opportunity by using the enhanced experience](https://docs.microsoft.com/dynamics365/sales-enterprise/add-products-enhanced-experience) (docs)</span></span>
