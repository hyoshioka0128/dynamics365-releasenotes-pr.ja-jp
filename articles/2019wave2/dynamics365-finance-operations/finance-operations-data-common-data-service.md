---
title: Common Data Service での Finance and Operations のデータ - フェーズ 1
description: Common Data Service での Finance and Operations のデータ
author: RamaKrishnamoorthy
ms.reviewer: sericks
ms.date: 07/31/2019
ms.assetid: fc62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: ramasri
dynamics365pdf: true
ms.openlocfilehash: 0547e383fd114cd39d87881d1c0b193af6ad5e85
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854220"
---
# <a name="finance-and-operations-data-in-common-data-service---phase-1"></a><span data-ttu-id="f3ac3-103">Common Data Service での Finance and Operations のデータ - フェーズ 1</span><span class="sxs-lookup"><span data-stu-id="f3ac3-103">Finance and Operations data in Common Data Service - Phase 1</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="f3ac3-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f3ac3-104">Enabled for</span></span>    |  <span data-ttu-id="f3ac3-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f3ac3-105">Public preview</span></span> | <span data-ttu-id="f3ac3-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f3ac3-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="f3ac3-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="f3ac3-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="f3ac3-108">2019 年 7 月 24 日</span><span class="sxs-lookup"><span data-stu-id="f3ac3-108">July 24, 2019</span></span>| <span data-ttu-id="f3ac3-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="f3ac3-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="f3ac3-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f3ac3-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f3ac3-111">この機能は、Dynamics 365 for Finance and Operations と Common Data Service の間のシームレスなデータ交換を容易にします。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-111">This feature facilitates seamless data exchange between Dynamics 365 for Finance and Operations and Common Data Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f3ac3-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f3ac3-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f3ac3-113">Dynamics 365 for Finance and Operations のデータを Common Data Service で取得し、最新の状態に保ちます。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-113">Get your Dynamics 365 for Finance and Operations data in Common Data Service and keep it up to date.</span></span> 

<span data-ttu-id="f3ac3-114">Microsoft では、二重書き込みのセットアップを特別な設定が不要なエクスペリエンスにしています。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-114">We are making the dual-write setup an out-of-the-box experience.</span></span> <span data-ttu-id="f3ac3-115">これにより、企業はアプリの境界を超えてリアルタイムに近いデータを同期双方向方式でシームレスに交換できます。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-115">This will allow businesses to exchange near real-time data seamlessly in a synchronous bidirectional fashion, beyond application boundaries.</span></span> <span data-ttu-id="f3ac3-116">Microsoft では、ユーザーに "1 つの Dynamics 365" エクスペリエンスを提供したいと考えています。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-116">We want to provide users a "One Dynamics 365" experience.</span></span> 

<span data-ttu-id="f3ac3-117">すべてのビジネスが本質的に固有のものであることがわかっているので、二重書き込みフレームワークを拡張可能にしました。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-117">Knowing every business is unique in itself, we have made the dual-write framework extensible.</span></span> <span data-ttu-id="f3ac3-118">これには、カスタム エンティティの有効化に加え、Common Data Service と最重要ビジネス データ用の関連ツールをフル活用するための既存のエンティティへの拡張が含まれます。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-118">This includes enabling custom entities, as well as extensions to existing entities, to fully utilize Common Data Service and surrounding tools for your most important business data.</span></span>



## <a name="phase-1-release"></a><span data-ttu-id="f3ac3-119">フェーズ 1 リリース</span><span class="sxs-lookup"><span data-stu-id="f3ac3-119">Phase 1 release</span></span>
<span data-ttu-id="f3ac3-120">フェーズ 1 リリースでは、顧客、仕入先、および製品にマルチマスター機能を提供します。Common Data Service での会社の概念および Dynamics 365 ユーザーのシングルユーザー管理エクスペリエンスも導入されています。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-120">The Phase 1 release provides multi-mastering capabilities for customers, vendors, and products, along with an introduction to the company concept in Common Data Service and to the single-user management experience for Dynamics 365 users.</span></span> <span data-ttu-id="f3ac3-121">これらの機能は 6 月のパブリック プレビューでリリースされ、10 月には一般提供される予定です。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-121">These features will be released in public preview in June and made generally available in the October time frame.</span></span> <span data-ttu-id="f3ac3-122">対象となっているエンティティは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-122">Entities that are being covered are as follows:</span></span> 

<span data-ttu-id="f3ac3-123">OMOrganizationHierarchyPurposeEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-123">OMOrganizationHierarchyPurposeEntity</span></span></br>
<span data-ttu-id="f3ac3-124">OMOrganizationHierarchyPublishedEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-124">OMOrganizationHierarchyPublishedEntity</span></span></br>
<span data-ttu-id="f3ac3-125">OMOrganizationHierarchyTypeEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-125">OMOrganizationHierarchyTypeEntity</span></span></br>
<span data-ttu-id="f3ac3-126">OMOperatingUnitEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-126">OMOperatingUnitEntity</span></span></br>
<span data-ttu-id="f3ac3-127">OMLegalEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-127">OMLegalEntity</span></span></br>
<span data-ttu-id="f3ac3-128">CustCustomerGroupEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-128">CustCustomerGroupEntity</span></span></br>
<span data-ttu-id="f3ac3-129">PaymentTermEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-129">PaymentTermEntity</span></span></br>
<span data-ttu-id="f3ac3-130">CustomerPaymentMethodEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-130">CustomerPaymentMethodEntity</span></span></br>
<span data-ttu-id="f3ac3-131">CustCustomerV3Entity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-131">CustCustomerV3Entity</span></span></br>
<span data-ttu-id="f3ac3-132">VendVendorV2Entity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-132">VendVendorV2Entity</span></span></br>
<span data-ttu-id="f3ac3-133">VendVendorGroupEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-133">VendVendorGroupEntity</span></span></br>
<span data-ttu-id="f3ac3-134">VendorPaymentMethodEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-134">VendorPaymentMethodEntity</span></span></br>
<span data-ttu-id="f3ac3-135">SmmContactPersonEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-135">SmmContactPersonEntity</span></span></br>
<span data-ttu-id="f3ac3-136">RetailLoyaltyCardEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-136">RetailLoyaltyCardEntity</span></span></br>
<span data-ttu-id="f3ac3-137">PaymentScheduleEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-137">PaymentScheduleEntity</span></span></br>
<span data-ttu-id="f3ac3-138">PaymentScheduleLineEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-138">PaymentScheduleLineEntity</span></span></br>
<span data-ttu-id="f3ac3-139">CDSPaymentDayEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-139">CDSPaymentDayEntity</span></span></br>
<span data-ttu-id="f3ac3-140">CDSPaymentDayLineEntity</span><span class="sxs-lookup"><span data-stu-id="f3ac3-140">CDSPaymentDayLineEntity</span></span></br>
<span data-ttu-id="f3ac3-141">EcoResProductCDS</span><span class="sxs-lookup"><span data-stu-id="f3ac3-141">EcoResProductCDS</span></span></br>
<span data-ttu-id="f3ac3-142">CDSEcoResProductMaster</span><span class="sxs-lookup"><span data-stu-id="f3ac3-142">CDSEcoResProductMaster</span></span></br>
<span data-ttu-id="f3ac3-143">EcoResProductProperties</span><span class="sxs-lookup"><span data-stu-id="f3ac3-143">EcoResProductProperties</span></span></br>
<span data-ttu-id="f3ac3-144">EcoResProductBarcode</span><span class="sxs-lookup"><span data-stu-id="f3ac3-144">EcoResProductBarcode</span></span></br>
<span data-ttu-id="f3ac3-145">EcoResProductDefaultOrderSettings</span><span class="sxs-lookup"><span data-stu-id="f3ac3-145">EcoResProductDefaultOrderSettings</span></span></br>
<span data-ttu-id="f3ac3-146">EcoResProductDimensionGroup</span><span class="sxs-lookup"><span data-stu-id="f3ac3-146">EcoResProductDimensionGroup</span></span></br>
<span data-ttu-id="f3ac3-147">UnitOfMeasures</span><span class="sxs-lookup"><span data-stu-id="f3ac3-147">UnitOfMeasures</span></span></br>
<span data-ttu-id="f3ac3-148">NameAffix</span><span class="sxs-lookup"><span data-stu-id="f3ac3-148">NameAffix</span></span>

## <a name="phase-2-release"></a><span data-ttu-id="f3ac3-149">フェーズ 2 リリース</span><span class="sxs-lookup"><span data-stu-id="f3ac3-149">Phase 2 release</span></span>
<span data-ttu-id="f3ac3-150">フェーズ 2 リリースでは、プロジェクト、在庫、販売、調達から財務までをカバーするエンドツーエンドのシナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-150">The Phase 2 release will target supporting end-to-end scenarios covering project, inventory, sales, and procurement through to financials.</span></span> <span data-ttu-id="f3ac3-151">これらの分野で最も重要なエンティティをサポートする、すぐに使えるなシナリオが既定で提供されます。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-151">Out-of-the-box scenarios supporting the most important entities in these areas will be provided by default.</span></span> <span data-ttu-id="f3ac3-152">これらのシナリオは、Finance and Operations と Common Data Service 全体に拡張されるように、顧客とパートナーがさらに充実させることができます。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-152">These scenarios can be further enriched by customers and partners so that they extend across Finance and Operations and Common Data Service.</span></span> 

<span data-ttu-id="f3ac3-153">これらの機能は 10 月のパブリック プレビューでリリースされ、4 月には一般提供される予定です。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-153">These features will be released in public preview in October and made generally available in the April timeframe.</span></span> <span data-ttu-id="f3ac3-154">対象となるエンティティは後日発表されます。</span><span class="sxs-lookup"><span data-stu-id="f3ac3-154">Entity coverage will be revealed at a future date.</span></span>
<!--feature detail end -->












## <a name="see-also"></a><span data-ttu-id="f3ac3-155">関連項目</span><span class="sxs-lookup"><span data-stu-id="f3ac3-155">See also</span></span>

[<span data-ttu-id="f3ac3-156">プレビュー: Finance and Operations と Common Data Service の統合 - フェーズ 1</span><span class="sxs-lookup"><span data-stu-id="f3ac3-156">Preview: Integration between Finance and Operations and Common Data Service - Phase 1</span></span>](https://cloudblogs.microsoft.com/dynamics365/?p=78375&secret=DT7uTp)
