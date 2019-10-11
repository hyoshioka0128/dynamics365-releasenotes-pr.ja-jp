---
title: Common Data Service のデータ - フェーズ 1
description: Common Data Service のデータ
author: RamaKrishnamoorthy
ms.reviewer: sericks
ms.date: 09/12/2019
ms.assetid: fc62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: ramasri
dynamics365pdf: true
ms.openlocfilehash: c897aebc267080f43e6335a771babffb6a23d236
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143159"
---
# <a name="data-in-common-data-service---phase-1"></a><span data-ttu-id="b8264-103">Common Data Service のデータ - フェーズ 1</span><span class="sxs-lookup"><span data-stu-id="b8264-103">Data in Common Data Service - Phase 1</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="b8264-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b8264-104">Enabled for</span></span>    |  <span data-ttu-id="b8264-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b8264-105">Public preview</span></span> | <span data-ttu-id="b8264-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b8264-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b8264-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="b8264-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="b8264-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b8264-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b8264-109">2019 年 7 月 24 日</span><span class="sxs-lookup"><span data-stu-id="b8264-109">Jul 24, 2019</span></span>| <span data-ttu-id="b8264-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="b8264-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="b8264-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b8264-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b8264-112">この機能は、Common Data Service とのシームレスなデータ交換を容易にします。</span><span class="sxs-lookup"><span data-stu-id="b8264-112">This feature facilitates seamless data exchange with Common Data Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b8264-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b8264-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b8264-114">Common Data Service のデータを取得し、最新の状態に保ちます。</span><span class="sxs-lookup"><span data-stu-id="b8264-114">Get your data in Common Data Service and keep it up to date.</span></span> 

<span data-ttu-id="b8264-115">Microsoft では、二重書き込みを追加設定なしで利用できるようにしています。</span><span class="sxs-lookup"><span data-stu-id="b8264-115">We are making the dual-write setup an out-of-the-box experience.</span></span> <span data-ttu-id="b8264-116">これにより、企業はアプリの境界を超えてリアルタイムに近いデータを同期双方向方式でシームレスに交換できます。</span><span class="sxs-lookup"><span data-stu-id="b8264-116">This will allow businesses to exchange near real-time data seamlessly in a synchronous bidirectional fashion, beyond application boundaries.</span></span> <span data-ttu-id="b8264-117">Microsoft では、ユーザーに "1 つの Dynamics 365" エクスペリエンスを提供したいと考えています。</span><span class="sxs-lookup"><span data-stu-id="b8264-117">We want to provide users a "One Dynamics 365" experience.</span></span> 

<span data-ttu-id="b8264-118">すべてのビジネスが本質的に固有のものであることがわかっているので、二重書き込みフレームワークを拡張可能にしました。</span><span class="sxs-lookup"><span data-stu-id="b8264-118">Knowing every business is unique in itself, we have made the dual-write framework extensible.</span></span> <span data-ttu-id="b8264-119">これには、カスタム エンティティの有効化に加え、Common Data Service と最重要ビジネス データ用の関連ツールをフル活用するための既存のエンティティへの拡張が含まれます。</span><span class="sxs-lookup"><span data-stu-id="b8264-119">This includes enabling custom entities, as well as extensions to existing entities, to fully utilize Common Data Service and surrounding tools for your most important business data.</span></span>



## <a name="phase-1-release"></a><span data-ttu-id="b8264-120">フェーズ 1 リリース</span><span class="sxs-lookup"><span data-stu-id="b8264-120">Phase 1 release</span></span>
<span data-ttu-id="b8264-121">フェーズ 1 リリースでは、顧客、仕入先、および製品にマルチマスター機能を提供します。Common Data Service での会社の概念および Dynamics 365 ユーザーのシングルユーザー管理エクスペリエンスも導入されています。</span><span class="sxs-lookup"><span data-stu-id="b8264-121">The Phase 1 release provides multi-mastering capabilities for customers, vendors, and products, along with an introduction to the company concept in Common Data Service and to the single-user management experience for Dynamics 365 users.</span></span> <span data-ttu-id="b8264-122">これらの機能は 6 月のパブリック プレビューでリリースされ、10 月には一般提供される予定です。</span><span class="sxs-lookup"><span data-stu-id="b8264-122">These features will be released in public preview in June and made generally available in the October time frame.</span></span> <span data-ttu-id="b8264-123">対象となっているエンティティは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="b8264-123">Entities that are being covered are as follows:</span></span> 

<span data-ttu-id="b8264-124">OMOrganizationHierarchyPurposeEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-124">OMOrganizationHierarchyPurposeEntity</span></span></br>
<span data-ttu-id="b8264-125">OMOrganizationHierarchyPublishedEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-125">OMOrganizationHierarchyPublishedEntity</span></span></br>
<span data-ttu-id="b8264-126">OMOrganizationHierarchyTypeEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-126">OMOrganizationHierarchyTypeEntity</span></span></br>
<span data-ttu-id="b8264-127">OMOperatingUnitEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-127">OMOperatingUnitEntity</span></span></br>
<span data-ttu-id="b8264-128">OMLegalEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-128">OMLegalEntity</span></span></br>
<span data-ttu-id="b8264-129">CustCustomerGroupEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-129">CustCustomerGroupEntity</span></span></br>
<span data-ttu-id="b8264-130">PaymentTermEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-130">PaymentTermEntity</span></span></br>
<span data-ttu-id="b8264-131">CustomerPaymentMethodEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-131">CustomerPaymentMethodEntity</span></span></br>
<span data-ttu-id="b8264-132">CustCustomerV3Entity</span><span class="sxs-lookup"><span data-stu-id="b8264-132">CustCustomerV3Entity</span></span></br>
<span data-ttu-id="b8264-133">VendVendorV2Entity</span><span class="sxs-lookup"><span data-stu-id="b8264-133">VendVendorV2Entity</span></span></br>
<span data-ttu-id="b8264-134">VendVendorGroupEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-134">VendVendorGroupEntity</span></span></br>
<span data-ttu-id="b8264-135">VendorPaymentMethodEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-135">VendorPaymentMethodEntity</span></span></br>
<span data-ttu-id="b8264-136">SmmContactPersonEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-136">SmmContactPersonEntity</span></span></br>
<span data-ttu-id="b8264-137">RetailLoyaltyCardEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-137">RetailLoyaltyCardEntity</span></span></br>
<span data-ttu-id="b8264-138">PaymentScheduleEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-138">PaymentScheduleEntity</span></span></br>
<span data-ttu-id="b8264-139">PaymentScheduleLineEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-139">PaymentScheduleLineEntity</span></span></br>
<span data-ttu-id="b8264-140">CDSPaymentDayEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-140">CDSPaymentDayEntity</span></span></br>
<span data-ttu-id="b8264-141">CDSPaymentDayLineEntity</span><span class="sxs-lookup"><span data-stu-id="b8264-141">CDSPaymentDayLineEntity</span></span></br>
<span data-ttu-id="b8264-142">EcoResProductCDS</span><span class="sxs-lookup"><span data-stu-id="b8264-142">EcoResProductCDS</span></span></br>
<span data-ttu-id="b8264-143">CDSEcoResProductMaster</span><span class="sxs-lookup"><span data-stu-id="b8264-143">CDSEcoResProductMaster</span></span></br>
<span data-ttu-id="b8264-144">EcoResProductProperties</span><span class="sxs-lookup"><span data-stu-id="b8264-144">EcoResProductProperties</span></span></br>
<span data-ttu-id="b8264-145">EcoResProductBarcode</span><span class="sxs-lookup"><span data-stu-id="b8264-145">EcoResProductBarcode</span></span></br>
<span data-ttu-id="b8264-146">EcoResProductDefaultOrderSettings</span><span class="sxs-lookup"><span data-stu-id="b8264-146">EcoResProductDefaultOrderSettings</span></span></br>
<span data-ttu-id="b8264-147">EcoResProductDimensionGroup</span><span class="sxs-lookup"><span data-stu-id="b8264-147">EcoResProductDimensionGroup</span></span></br>
<span data-ttu-id="b8264-148">UnitOfMeasures</span><span class="sxs-lookup"><span data-stu-id="b8264-148">UnitOfMeasures</span></span></br>
<span data-ttu-id="b8264-149">NameAffix</span><span class="sxs-lookup"><span data-stu-id="b8264-149">NameAffix</span></span>

## <a name="phase-2-release"></a><span data-ttu-id="b8264-150">フェーズ 2 リリース</span><span class="sxs-lookup"><span data-stu-id="b8264-150">Phase 2 release</span></span>
<span data-ttu-id="b8264-151">フェーズ 2 リリースでは、プロジェクト、在庫、販売、調達から財務までをカバーするエンドツーエンドのシナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="b8264-151">The Phase 2 release will target supporting end-to-end scenarios covering project, inventory, sales, and procurement through to financials.</span></span> <span data-ttu-id="b8264-152">これらの分野で最も重要なエンティティをサポートする、すぐに使えるなシナリオが既定で提供されます。</span><span class="sxs-lookup"><span data-stu-id="b8264-152">Out-of-the-box scenarios supporting the most important entities in these areas will be provided by default.</span></span> <span data-ttu-id="b8264-153">これらのシナリオは、ユーザーとパートナーによってさらに充実させることができます。</span><span class="sxs-lookup"><span data-stu-id="b8264-153">These scenarios can be further enriched by customers and partners.</span></span> 

<span data-ttu-id="b8264-154">これらの機能は 10 月のパブリック プレビューでリリースされ、4 月には一般提供される予定です。</span><span class="sxs-lookup"><span data-stu-id="b8264-154">These features will be released in public preview in October and made generally available in the April timeframe.</span></span> <span data-ttu-id="b8264-155">対象となるエンティティは後日発表されます。</span><span class="sxs-lookup"><span data-stu-id="b8264-155">Entity coverage will be revealed at a future date.</span></span>
<!--feature detail end -->

