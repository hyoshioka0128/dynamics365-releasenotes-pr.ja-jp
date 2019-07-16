---
title: 営業案件/見積/発注/請求書の製品の追加または編集エクスペリエンスの強化
description: この機能強化により、営業案件や見積もりなどの製品明細品目を追加するときに、商品を簡単に検索およびフィルター処理するためのより単純で直感的なエクスペリエンスが提供されます。 さらに、価格表を必須にする必要があるかどうかを設定するための組織レベルのオプションも提供されます。
author: relnotes
ms.reviewer: shujoshi
ms.date: 06/19/2019
ms.assetid: d061278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: naitikds
dynamics365pdf: true
ms.openlocfilehash: 071ee1f5b8992fdc88b959130bba216a4206544a
ms.sourcegitcommit: 0c53eb8711a7594ec968a8d531a78b6ab5b98bf6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/03/2019
ms.locfileid: "1725504"
---
# <a name="enhance-the-adding-or-editing-opportunityquoteorderinvoice-products-experience"></a><span data-ttu-id="8ab4d-104">営業案件/見積/発注/請求書の製品の追加または編集エクスペリエンスの強化</span><span class="sxs-lookup"><span data-stu-id="8ab4d-104">Enhance the adding or editing Opportunity/Quote/Order/Invoice products experience</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="8ab4d-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="8ab4d-105">Enabled for</span></span>    |  <span data-ttu-id="8ab4d-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8ab4d-106">Public preview</span></span> | <span data-ttu-id="8ab4d-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="8ab4d-107">General availability</span></span> | <span data-ttu-id="8ab4d-108">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="8ab4d-108">Early Access</span></span> |
| ---------- | ---------- |---------- |---------- |
|<span data-ttu-id="8ab4d-109">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="8ab4d-109">End users, automatically</span></span>|| <span data-ttu-id="8ab4d-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="8ab4d-110">October 2019</span></span>|<span data-ttu-id="8ab4d-111">はい</span><span class="sxs-lookup"><span data-stu-id="8ab4d-111">Yes</span></span> |


## <a name="business-value"></a><span data-ttu-id="8ab4d-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8ab4d-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8ab4d-113">顧客から最も多い要求です。</span><span class="sxs-lookup"><span data-stu-id="8ab4d-113">A top request by customers.</span></span> 

<span data-ttu-id="8ab4d-114">この機能の機能強化では、営業担当者が任意の明細行品目の製品を選択し、生産性を向上させ、不要なコンテキスト切り替えを回避できるようにすることで、検索やフィルタリングのエクスペリエンスの向上を支援します。</span><span class="sxs-lookup"><span data-stu-id="8ab4d-114">Enhancements to this feature help improve searching and filtering experiences by allowing salespeople to select a product on any line item, empowering them to be more productive and avoid unnecessary context switching.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8ab4d-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8ab4d-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8ab4d-116">反復的な作業となる可能性のある複数の製品明細品目の作成は、新しい "新規作成および追加" 機能によって合理化されます。</span><span class="sxs-lookup"><span data-stu-id="8ab4d-116">Creation of multiple product line items, which can be a repetitive task, is now streamlined with the new “Create and Add” capability.</span></span> <span data-ttu-id="8ab4d-117">営業案件への新しい製品の追加をすばやく繰り返すことで、営業担当者は時間を節約し、より重要なタスクにすばやく焦点を移すことができます。</span><span class="sxs-lookup"><span data-stu-id="8ab4d-117">By quickly iterating on adding new products to an opportunity, salespeople can save time and quickly shift focus to more important tasks.</span></span> <span data-ttu-id="8ab4d-118">さらに:</span><span class="sxs-lookup"><span data-stu-id="8ab4d-118">In addition:</span></span>  

- <span data-ttu-id="8ab4d-119">営業担当者は、価格表の有無にかかわらず、営業案件、見積もり、注文、請求書に既存の製品を追加できます。</span><span class="sxs-lookup"><span data-stu-id="8ab4d-119">Salespeople can add an existing product to an Opportunity, Quote, Order, and Invoice, with or without a price list.</span></span>  
- <span data-ttu-id="8ab4d-120">管理者は、価格表の選択を適用するかどうかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="8ab4d-120">Administrators can choose whether to enforce selection of a price list.</span></span>  
- <span data-ttu-id="8ab4d-121">営業担当者は、営業案件や見積もりの明細品目の編集中でも、製品のプロパティをすばやく表示および編集できます。</span><span class="sxs-lookup"><span data-stu-id="8ab4d-121">Salespeople can quickly view and edit properties for a product, even while editing Opportunity or Quote line items.</span></span>  
- <span data-ttu-id="8ab4d-122">管理者は、価格表品目エンティティに対する追加のカスタマイズ オプションを使用できます。</span><span class="sxs-lookup"><span data-stu-id="8ab4d-122">Administrators can use additional customization options on the price list item entity.</span></span>
<!--feature detail end -->

  <span data-ttu-id="8ab4d-123">![価格表オプション](media/pricelist-optional.png "価格表オプション")</span><span class="sxs-lookup"><span data-stu-id="8ab4d-123">![Price list optional](media/pricelist-optional.png "Price list optional")</span></span>
<!-- Picture 1 -->

> [!NOTE]
> <span data-ttu-id="8ab4d-124">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="8ab4d-124">This feature is available in the Unified Interface only.</span></span>







