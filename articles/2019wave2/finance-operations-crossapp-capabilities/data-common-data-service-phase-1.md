---
title: Common Data Service のデータ – フェーズ 1
description: Common Data Service のデータ – フェーズ 1
author: RamaKrishnamoorthy
ms.reviewer: sericks
ms.date: 10/16/2019
ms.assetid: fc62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: ramasri
dynamics365pdf: true
ms.openlocfilehash: ddb07852b055f99000269f91304ef5fb66882957
ms.sourcegitcommit: 3e19a91181b001b74894328456d8da10d4f6d973
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/29/2019
ms.locfileid: "2673853"
---
# <a name="data-in-common-data-service--phase-1"></a><span data-ttu-id="f79c0-103">Common Data Service のデータ – フェーズ 1</span><span class="sxs-lookup"><span data-stu-id="f79c0-103">Data in Common Data Service – Phase 1</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="f79c0-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f79c0-104">Enabled for</span></span>    |  <span data-ttu-id="f79c0-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f79c0-105">Public preview</span></span> | <span data-ttu-id="f79c0-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f79c0-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f79c0-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="f79c0-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="f79c0-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="f79c0-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="f79c0-109">2019 年 7 月 24 日</span><span class="sxs-lookup"><span data-stu-id="f79c0-109">Jul 24, 2019</span></span>| <span data-ttu-id="f79c0-110">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="f79c0-110">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="f79c0-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f79c0-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f79c0-112">この機能は、Common Data Service とのシームレスなデータ交換を容易にします。</span><span class="sxs-lookup"><span data-stu-id="f79c0-112">This feature facilitates seamless data exchange with Common Data Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f79c0-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f79c0-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f79c0-114">Common Data Service のデータを取得し、最新の状態に保ちます。</span><span class="sxs-lookup"><span data-stu-id="f79c0-114">Get your data in Common Data Service and keep it up to date.</span></span> 

<span data-ttu-id="f79c0-115">Microsoft では、二重書き込みを追加設定なしで利用できるようにしています。</span><span class="sxs-lookup"><span data-stu-id="f79c0-115">We are making the dual-write setup an out-of-the-box experience.</span></span> <span data-ttu-id="f79c0-116">これにより、企業はアプリの境界を超えてリアルタイムに近いデータを同期双方向方式でシームレスに交換できます。</span><span class="sxs-lookup"><span data-stu-id="f79c0-116">This will allow businesses to exchange near real-time data seamlessly in a synchronous bidirectional fashion, beyond application boundaries.</span></span> <span data-ttu-id="f79c0-117">Microsoft では、ユーザーに "1 つの Dynamics 365" エクスペリエンスを提供したいと考えています。</span><span class="sxs-lookup"><span data-stu-id="f79c0-117">We want to provide users a "One Dynamics 365" experience.</span></span> 

<span data-ttu-id="f79c0-118">すべてのビジネスが本質的に固有のものであることがわかっているので、二重書き込みフレームワークを拡張可能にしました。</span><span class="sxs-lookup"><span data-stu-id="f79c0-118">Knowing every business is unique in itself, we have made the dual-write framework extensible.</span></span> <span data-ttu-id="f79c0-119">これには、カスタム エンティティの有効化に加え、Common Data Service と最重要ビジネス データ用の関連ツールをフル活用するための既存のエンティティへの拡張が含まれます。</span><span class="sxs-lookup"><span data-stu-id="f79c0-119">This includes enabling custom entities, as well as extensions to existing entities, to fully utilize Common Data Service and surrounding tools for your most important business data.</span></span>

## <a name="phase-1-release"></a><span data-ttu-id="f79c0-120">フェーズ 1 リリース</span><span class="sxs-lookup"><span data-stu-id="f79c0-120">Phase 1 release</span></span>
<span data-ttu-id="f79c0-121">フェーズ 1 リリースでは、顧客、仕入先、および製品にマルチマスター機能を提供します。Common Data Service での会社の概念および Dynamics 365 ユーザーのシングルユーザー管理エクスペリエンスも導入されています。</span><span class="sxs-lookup"><span data-stu-id="f79c0-121">The Phase 1 release provides multi-mastering capabilities for customers, vendors, and products, along with an introduction to the company concept in Common Data Service and the single-user management experience for Dynamics 365 users.</span></span> <span data-ttu-id="f79c0-122">また、会計と税の参照データも含まれています。</span><span class="sxs-lookup"><span data-stu-id="f79c0-122">It also includes finance and tax reference data.</span></span> <span data-ttu-id="f79c0-123">これらの機能は 6 月のパブリック プレビューでリリースされ、10 月には一般提供される予定です。</span><span class="sxs-lookup"><span data-stu-id="f79c0-123">These features will be released in public preview in June and made generally available in the October time frame.</span></span> <span data-ttu-id="f79c0-124">対象となっているエンティティは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="f79c0-124">Entities that are being covered are as follows:</span></span> 

* <span data-ttu-id="f79c0-125">支払スケジュール - ヘッダー</span><span class="sxs-lookup"><span data-stu-id="f79c0-125">Payment schedules - Header</span></span>  
* <span data-ttu-id="f79c0-126">支払スケジュール – 明細行</span><span class="sxs-lookup"><span data-stu-id="f79c0-126">Payment schedules – Line</span></span>
* <span data-ttu-id="f79c0-127">支払期日 - ヘッダー</span><span class="sxs-lookup"><span data-stu-id="f79c0-127">Payment day - Header</span></span>
* <span data-ttu-id="f79c0-128">支払期日 - 明細行</span><span class="sxs-lookup"><span data-stu-id="f79c0-128">Payment day - Line</span></span>
* <span data-ttu-id="f79c0-129">顧客グループ</span><span class="sxs-lookup"><span data-stu-id="f79c0-129">Customer groups</span></span>
* <span data-ttu-id="f79c0-130">支払条件</span><span class="sxs-lookup"><span data-stu-id="f79c0-130">Terms of payment</span></span>
* <span data-ttu-id="f79c0-131">顧客支払方法</span><span class="sxs-lookup"><span data-stu-id="f79c0-131">Customer payment method</span></span>
* <span data-ttu-id="f79c0-132">ロイヤルティ カード</span><span class="sxs-lookup"><span data-stu-id="f79c0-132">Loyalty card</span></span>
* <span data-ttu-id="f79c0-133">ロイヤルティ報酬ポイント</span><span class="sxs-lookup"><span data-stu-id="f79c0-133">Loyalty reward points</span></span>
* <span data-ttu-id="f79c0-134">顧客</span><span class="sxs-lookup"><span data-stu-id="f79c0-134">Customers</span></span>
* <span data-ttu-id="f79c0-135">顧客の連絡先</span><span class="sxs-lookup"><span data-stu-id="f79c0-135">Customer contact</span></span>
* <span data-ttu-id="f79c0-136">通貨</span><span class="sxs-lookup"><span data-stu-id="f79c0-136">Currency</span></span>
* <span data-ttu-id="f79c0-137">会計カレンダー</span><span class="sxs-lookup"><span data-stu-id="f79c0-137">Fiscal calendar</span></span>
* <span data-ttu-id="f79c0-138">会計暦年</span><span class="sxs-lookup"><span data-stu-id="f79c0-138">Fiscal calendar year</span></span>
* <span data-ttu-id="f79c0-139">為替レート タイプ</span><span class="sxs-lookup"><span data-stu-id="f79c0-139">Exchange rate types</span></span>
* <span data-ttu-id="f79c0-140">為替レート ペア</span><span class="sxs-lookup"><span data-stu-id="f79c0-140">Exchange rate pair</span></span>
* <span data-ttu-id="f79c0-141">元帳会計期間/財務カレンダー期間</span><span class="sxs-lookup"><span data-stu-id="f79c0-141">Ledger fiscal periods/ Financial calendar period</span></span>
* <span data-ttu-id="f79c0-142">主勘定カテゴリ</span><span class="sxs-lookup"><span data-stu-id="f79c0-142">Main account category</span></span>
* <span data-ttu-id="f79c0-143">主勘定</span><span class="sxs-lookup"><span data-stu-id="f79c0-143">Main account</span></span>
* <span data-ttu-id="f79c0-144">元帳</span><span class="sxs-lookup"><span data-stu-id="f79c0-144">Ledger</span></span>
* <span data-ttu-id="f79c0-145">為替レート</span><span class="sxs-lookup"><span data-stu-id="f79c0-145">Exchange rates</span></span>
* <span data-ttu-id="f79c0-146">分析コードの属性</span><span class="sxs-lookup"><span data-stu-id="f79c0-146">Dimension attribute</span></span>
* <span data-ttu-id="f79c0-147">分析コード統合形式</span><span class="sxs-lookup"><span data-stu-id="f79c0-147">Dimension integration format</span></span>
* <span data-ttu-id="f79c0-148">組織分類/組織階層の目的</span><span class="sxs-lookup"><span data-stu-id="f79c0-148">Organization classification/Organization hierarchy purpose</span></span>
* <span data-ttu-id="f79c0-149">組織階層</span><span class="sxs-lookup"><span data-stu-id="f79c0-149">Organization hierarchy</span></span>
* <span data-ttu-id="f79c0-150">組織階層タイプ</span><span class="sxs-lookup"><span data-stu-id="f79c0-150">Organization hierarchy type</span></span>
* <span data-ttu-id="f79c0-151">会社</span><span class="sxs-lookup"><span data-stu-id="f79c0-151">Company</span></span>
* <span data-ttu-id="f79c0-152">リリースされた製品</span><span class="sxs-lookup"><span data-stu-id="f79c0-152">Released products</span></span>
* <span data-ttu-id="f79c0-153">特徴的リリース済製品</span><span class="sxs-lookup"><span data-stu-id="f79c0-153">Distinct released products</span></span>
* <span data-ttu-id="f79c0-154">製品番号で特定されたバーコード エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-154">Product number Identified barcode entity</span></span>
* <span data-ttu-id="f79c0-155">グローバル製品</span><span class="sxs-lookup"><span data-stu-id="f79c0-155">Global Products</span></span>
* <span data-ttu-id="f79c0-156">製品の既定の注文設定エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-156">Product Default order settings entity</span></span>
* <span data-ttu-id="f79c0-157">製品固有の既定の注文設定</span><span class="sxs-lookup"><span data-stu-id="f79c0-157">Product specific default order settings</span></span>
* <span data-ttu-id="f79c0-158">製品分析コード グループ エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-158">Product dimension group entity</span></span>
* <span data-ttu-id="f79c0-159">追跡用分析コード グループ エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-159">Tracking dimension group entity</span></span>
* <span data-ttu-id="f79c0-160">測定単位エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-160">Unit of measures entity</span></span>
* <span data-ttu-id="f79c0-161">測定単位換算</span><span class="sxs-lookup"><span data-stu-id="f79c0-161">Unit of measure conversion</span></span>
* <span data-ttu-id="f79c0-162">製品固有の測定単位換算</span><span class="sxs-lookup"><span data-stu-id="f79c0-162">Product specific unit of measure conversion</span></span>
* <span data-ttu-id="f79c0-163">サイト エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-163">Site entity</span></span>
* <span data-ttu-id="f79c0-164">倉庫エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-164">Warehouses entity</span></span>
* <span data-ttu-id="f79c0-165">色エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-165">Color entity</span></span>
* <span data-ttu-id="f79c0-166">サイズ エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-166">Size entity</span></span>
* <span data-ttu-id="f79c0-167">保管分析コード グループ エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-167">Storage dimension group entity</span></span>
* <span data-ttu-id="f79c0-168">スタイル エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-168">Style entity</span></span>
* <span data-ttu-id="f79c0-169">構成エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-169">Configuration entity</span></span>
* <span data-ttu-id="f79c0-170">EcoResProductMasterColor エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-170">EcoResProductMasterColor entity</span></span>
* <span data-ttu-id="f79c0-171">EcoResProductMasterSize エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-171">EcoResProductMasterSize entity</span></span>
* <span data-ttu-id="f79c0-172">EcoResProductMasterStyle エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-172">EcoResProductMasterStyle entity</span></span>
* <span data-ttu-id="f79c0-173">EcoResProductMasterConfig エンティティ</span><span class="sxs-lookup"><span data-stu-id="f79c0-173">EcoResProductMasterConfig entity</span></span>
* <span data-ttu-id="f79c0-174">製品カテゴリ</span><span class="sxs-lookup"><span data-stu-id="f79c0-174">Product categories</span></span>
* <span data-ttu-id="f79c0-175">製品カテゴリの割り当て</span><span class="sxs-lookup"><span data-stu-id="f79c0-175">Product category assignments</span></span>
* <span data-ttu-id="f79c0-176">製品カテゴリ階層</span><span class="sxs-lookup"><span data-stu-id="f79c0-176">Product category hierarchies</span></span>
* <span data-ttu-id="f79c0-177">製品カテゴリ階層ロール</span><span class="sxs-lookup"><span data-stu-id="f79c0-177">Product category hierarchy roles</span></span>
* <span data-ttu-id="f79c0-178">税グループ</span><span class="sxs-lookup"><span data-stu-id="f79c0-178">Tax groups</span></span>
* <span data-ttu-id="f79c0-179">税品目グループ</span><span class="sxs-lookup"><span data-stu-id="f79c0-179">Tax item groups</span></span>
* <span data-ttu-id="f79c0-180">免税</span><span class="sxs-lookup"><span data-stu-id="f79c0-180">Tax exemptions</span></span>
* <span data-ttu-id="f79c0-181">税務当局</span><span class="sxs-lookup"><span data-stu-id="f79c0-181">Tax authorities</span></span>
* <span data-ttu-id="f79c0-182">源泉徴収税コード</span><span class="sxs-lookup"><span data-stu-id="f79c0-182">Withholding tax codes</span></span>
* <span data-ttu-id="f79c0-183">源泉徴収税グループ</span><span class="sxs-lookup"><span data-stu-id="f79c0-183">Withholding tax groups</span></span>
* <span data-ttu-id="f79c0-184">税勘定科目グループ/税転記グループ</span><span class="sxs-lookup"><span data-stu-id="f79c0-184">Tax ledger account group/Tax posting groups</span></span>
* <span data-ttu-id="f79c0-185">仕入先</span><span class="sxs-lookup"><span data-stu-id="f79c0-185">Vendors</span></span>
* <span data-ttu-id="f79c0-186">仕入先グループ</span><span class="sxs-lookup"><span data-stu-id="f79c0-186">Vendor groups</span></span>
* <span data-ttu-id="f79c0-187">仕入先支払方法</span><span class="sxs-lookup"><span data-stu-id="f79c0-187">Vendor payment method</span></span>
* <span data-ttu-id="f79c0-188">仕入先連絡先</span><span class="sxs-lookup"><span data-stu-id="f79c0-188">Vendor contacts</span></span>
* <span data-ttu-id="f79c0-189">勘定科目表</span><span class="sxs-lookup"><span data-stu-id="f79c0-189">Chart of accounts</span></span>

## <a name="phase-2-release"></a><span data-ttu-id="f79c0-190">フェーズ 2 リリース</span><span class="sxs-lookup"><span data-stu-id="f79c0-190">Phase 2 release</span></span>
<span data-ttu-id="f79c0-191">フェーズ 2 リリースでは、プロジェクト、在庫、販売、調達から財務までをカバーするエンドツーエンドのシナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="f79c0-191">The Phase 2 release will target supporting end-to-end scenarios covering project, inventory, sales, and procurement through to financials.</span></span> <span data-ttu-id="f79c0-192">これらの分野で最も重要なエンティティをサポートする、すぐに使えるなシナリオが既定で提供されます。</span><span class="sxs-lookup"><span data-stu-id="f79c0-192">Out-of-the-box scenarios supporting the most important entities in these areas will be provided by default.</span></span> <span data-ttu-id="f79c0-193">これらのシナリオは、ユーザーとパートナーによってさらに充実させることができます。</span><span class="sxs-lookup"><span data-stu-id="f79c0-193">These scenarios can be further enriched by customers and partners.</span></span> 

<span data-ttu-id="f79c0-194">これらの機能は 10 月のパブリック プレビューでリリースされ、4 月には一般提供される予定です。</span><span class="sxs-lookup"><span data-stu-id="f79c0-194">These features will be released in public preview in October and made generally available in the April time frame.</span></span> <span data-ttu-id="f79c0-195">対象となるエンティティは後日発表されます。</span><span class="sxs-lookup"><span data-stu-id="f79c0-195">Entity coverage will be revealed at a future date.</span></span>
<!--feature detail end -->




