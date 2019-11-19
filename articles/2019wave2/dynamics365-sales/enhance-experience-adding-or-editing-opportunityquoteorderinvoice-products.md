---
title: 営業案件/見積/発注/請求書の製品の追加または編集エクスペリエンスの強化
description: この機能強化により、営業案件や見積もりなどの製品明細品目を追加するときに、商品を簡単に検索およびフィルター処理するためのより単純で直感的なエクスペリエンスが提供されます。 さらに、価格表を必須にする必要があるかどうかを設定するための組織レベルのオプションも提供されます。
author: relnotes
ms.reviewer: shujoshi
ms.date: 10/17/2019
ms.assetid: d061278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: naitikds
dynamics365pdf: true
ms.openlocfilehash: 45d6398c51838128ce3c3de2122aa215eec409b6
ms.sourcegitcommit: b0fef00d4f04f2507056a10ecce699767c669119
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2661781"
---
# <a name="enhance-the-adding-or-editing-opportunityquoteorderinvoice-products-experience"></a><span data-ttu-id="67727-104">営業案件/見積/発注/請求書の製品の追加または編集エクスペリエンスの強化</span><span class="sxs-lookup"><span data-stu-id="67727-104">Enhance the adding or editing Opportunity/Quote/Order/Invoice products experience</span></span>


| <span data-ttu-id="67727-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="67727-105">Enabled for</span></span>    |  <span data-ttu-id="67727-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="67727-106">Public preview</span></span> | <span data-ttu-id="67727-107">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="67727-107">Early access</span></span> | <span data-ttu-id="67727-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="67727-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="67727-109">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="67727-109">End users, automatically</span></span>|-|<span data-ttu-id="67727-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="67727-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="67727-111">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="67727-111">Aug 1, 2019</span></span>| <span data-ttu-id="67727-112">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="67727-112">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="67727-113">2019 年 10 月 6 日</span><span class="sxs-lookup"><span data-stu-id="67727-113">Oct 6, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="67727-114">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="67727-114">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="67727-115">顧客から最も多い要望です。</span><span class="sxs-lookup"><span data-stu-id="67727-115">A top request by customers.</span></span> 

<span data-ttu-id="67727-116">この機能強化では、営業担当者が任意の明細行品目の製品を選択できるようにすることで、検索やフィルター処理操作を改善します。これにより、生産性を高め、不要なコンテキストの切り替えを行わずに済むようになります。</span><span class="sxs-lookup"><span data-stu-id="67727-116">Enhancements to this feature help improve searching and filtering experiences by allowing salespeople to select a product on any line item, empowering them to be more productive and avoid unnecessary context switching.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="67727-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="67727-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="67727-118">反復的な作業となる可能性のある複数の製品明細品目の作成は、新しい新規作成および追加機能によって合理化されます。</span><span class="sxs-lookup"><span data-stu-id="67727-118">Creation of multiple product line items, which can be a repetitive task, is now streamlined with the new Create and Add capability.</span></span> <span data-ttu-id="67727-119">営業案件への新しい製品の追加をすばやく繰り返すことで、営業担当者は時間を節約し、より重要なタスクにすばやく焦点を移すことができます。</span><span class="sxs-lookup"><span data-stu-id="67727-119">By quickly iterating on adding new products to an opportunity, salespeople can save time and quickly shift focus to more important tasks.</span></span> <span data-ttu-id="67727-120">さらに:</span><span class="sxs-lookup"><span data-stu-id="67727-120">In addition:</span></span>  

- <span data-ttu-id="67727-121">営業担当者は、価格表の有無にかかわらず、営業案件、見積もり、注文、請求書に既存の製品を追加できます。</span><span class="sxs-lookup"><span data-stu-id="67727-121">Salespeople can add an existing product to an Opportunity, Quote, Order, and Invoice, with or without a price list.</span></span>  
- <span data-ttu-id="67727-122">管理者は、価格表の選択を適用するかどうかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="67727-122">Administrators can choose whether to enforce selection of a price list.</span></span>  
- <span data-ttu-id="67727-123">営業担当者は、営業案件や見積もりの明細品目の編集中でも、製品のプロパティをすばやく表示および編集できます。</span><span class="sxs-lookup"><span data-stu-id="67727-123">Salespeople can quickly view and edit properties for a product, even while editing Opportunity or Quote line items.</span></span>  
- <span data-ttu-id="67727-124">管理者は、価格表品目エンティティに対する追加のカスタマイズ オプションを使用できます。</span><span class="sxs-lookup"><span data-stu-id="67727-124">Administrators can use additional customization options on the price list item entity.</span></span>

<span data-ttu-id="67727-125">![価格表オプション](media/pricelist-optional.png "価格表オプション")</span><span class="sxs-lookup"><span data-stu-id="67727-125">![Price list optional](media/pricelist-optional.png "Price list optional")</span></span>

<span data-ttu-id="67727-126">![保存して新規作成するオプション](media/save-create-new.png "保存して新規作成するオプション")</span><span class="sxs-lookup"><span data-stu-id="67727-126">![Option to Save and create new](media/save-create-new.png "Option to Save and create new")</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="67727-127">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="67727-127">This feature is available in the Unified Interface only.</span></span> <span data-ttu-id="67727-128">この機能は、Dynamics 365 Sales Enterprise と Dynamics 365 Sales Professional で使用できます。</span><span class="sxs-lookup"><span data-stu-id="67727-128">This capability is available in Dynamics 365 Sales Enterprise and Dynamics 365 Sales Professional.</span></span>







## <a name="see-also"></a><span data-ttu-id="67727-129">関連項目</span><span class="sxs-lookup"><span data-stu-id="67727-129">See also</span></span>

<span data-ttu-id="67727-130">[追加または編集操作の強化](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-sales/enhance-experience-adding-or-editing-opportunityquoteorderinvoice-products) (ブログ)</span><span class="sxs-lookup"><span data-stu-id="67727-130">[Enhance the adding or editing](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-sales/enhance-experience-adding-or-editing-opportunityquoteorderinvoice-products) (blog)</span></span>

<span data-ttu-id="67727-131">[価格表の選択を任意にする](https://docs.microsoft.com/dynamics365/customer-engagement/sales-enterprise/make-price-list-optional) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="67727-131">[Make selection of price list optional](https://docs.microsoft.com/dynamics365/customer-engagement/sales-enterprise/make-price-list-optional) (docs)</span></span>
