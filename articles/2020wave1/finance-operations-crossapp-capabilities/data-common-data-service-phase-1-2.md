---
title: Common Data Service のデータ - フェーズ 1 と 2
description: Common Data Service のデータ - フェーズ 1 と 2
author: RamaKrishnamoorthy
ms.reviewer: rhaertle
ms.date: 01/08/2020
ms.assetid: 5838d44d-8d1b-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: ramasri
dynamics365pdf: true
ms.openlocfilehash: 54a41489d0c3ffc00f107a9ed1a6d4e45a410cd9
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986725"
---
# <a name="data-in-common-data-service--phase-1--2"></a><span data-ttu-id="9e1b1-103">Common Data Service のデータ - フェーズ 1 と 2</span><span class="sxs-lookup"><span data-stu-id="9e1b1-103">Data in Common Data Service – phase 1 & 2</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="9e1b1-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9e1b1-104">Enabled for</span></span>    |  <span data-ttu-id="9e1b1-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9e1b1-105">Public preview</span></span> | <span data-ttu-id="9e1b1-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="9e1b1-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="9e1b1-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="9e1b1-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="9e1b1-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="9e1b1-108">Feb 2020</span></span>| <span data-ttu-id="9e1b1-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="9e1b1-109">Apr 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="9e1b1-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9e1b1-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9e1b1-111">Finance and Operations アプリのデータを Common Data Service で取得し、最新の状態に保ちます。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-111">Get your Finance and Operations apps data in Common Data Service and keep it up to date.</span></span> 

<span data-ttu-id="9e1b1-112">Finance and Operations アプリとその他の Dynamics 365 アプリの間で収束する概念を調和させることで、二重書き込みフレームワークをシームレスなエクスペリエンスにしています。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-112">We are making the dual-write framework a seamless experience by harmonizing the converging concepts between Finance and Operations apps and other Dynamics 365 apps.</span></span> <span data-ttu-id="9e1b1-113">これにより、企業はアプリの境界を超えて、ニア リアルタイムのデータを同期的に、双方向で交換できるようになるため、"1 つの Dynamics 365" エクスペリエンスが実現します。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-113">This allows businesses to exchange near real-time data in a synchronous, bidirectional fashion beyond application boundaries, giving users a "One Dynamics 365" experience.</span></span> 

<span data-ttu-id="9e1b1-114">すべてのビジネスが固有のものであることがわかっているので、二重書き込みフレームワークを拡張可能にしました。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-114">Knowing every business is unique, we have made the dual-write framework extensible.</span></span> <span data-ttu-id="9e1b1-115">これには、カスタム エンティティの有効化に加え、Common Data Service と最重要ビジネス データ用の関連ツールをフルに使用するための既存のエンティティへの拡張が含まれます。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-115">This includes enabling custom entities, as well as extensions to existing entities, to fully use Common Data Service and surrounding tools for your most important business data.</span></span>

## <a name="phased-release"></a><span data-ttu-id="9e1b1-116">段階的リリース</span><span class="sxs-lookup"><span data-stu-id="9e1b1-116">Phased release</span></span>
<span data-ttu-id="9e1b1-117">フェーズ 1 の機能は、顧客、仕入先、および製品にマルチマスタリング機能を提供すると共に、Common Data Service に企業コンセプトを導入します。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-117">Phase 1 features provide multimastering capabilities for customers, vendors, and products, along with an introduction of the company concept in Common Data Service.</span></span> <span data-ttu-id="9e1b1-118">また、会計と税の参照データも含まれています。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-118">It also includes finance and tax reference data.</span></span> <span data-ttu-id="9e1b1-119">これらの機能は、2019 年 7 月からプレビューされています。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-119">These features have been in preview since July 2019.</span></span> 

<span data-ttu-id="9e1b1-120">次のエンティティがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-120">The following entities are supported:</span></span> 

* <span data-ttu-id="9e1b1-121">支払スケジュール - ヘッダー</span><span class="sxs-lookup"><span data-stu-id="9e1b1-121">Payment schedules - Header</span></span>  
* <span data-ttu-id="9e1b1-122">支払スケジュール – 明細行</span><span class="sxs-lookup"><span data-stu-id="9e1b1-122">Payment schedules – Line</span></span>
* <span data-ttu-id="9e1b1-123">支払期日 - ヘッダー</span><span class="sxs-lookup"><span data-stu-id="9e1b1-123">Payment day - Header</span></span>
* <span data-ttu-id="9e1b1-124">支払期日 - 明細行</span><span class="sxs-lookup"><span data-stu-id="9e1b1-124">Payment day - Line</span></span>
* <span data-ttu-id="9e1b1-125">顧客グループ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-125">Customer groups</span></span>
* <span data-ttu-id="9e1b1-126">支払条件</span><span class="sxs-lookup"><span data-stu-id="9e1b1-126">Terms of payment</span></span>
* <span data-ttu-id="9e1b1-127">顧客支払方法</span><span class="sxs-lookup"><span data-stu-id="9e1b1-127">Customer payment method</span></span>
* <span data-ttu-id="9e1b1-128">ロイヤルティ カード</span><span class="sxs-lookup"><span data-stu-id="9e1b1-128">Loyalty card</span></span>
* <span data-ttu-id="9e1b1-129">ロイヤルティ報酬ポイント</span><span class="sxs-lookup"><span data-stu-id="9e1b1-129">Loyalty reward points</span></span>
* <span data-ttu-id="9e1b1-130">顧客</span><span class="sxs-lookup"><span data-stu-id="9e1b1-130">Customers</span></span>
* <span data-ttu-id="9e1b1-131">顧客の連絡先</span><span class="sxs-lookup"><span data-stu-id="9e1b1-131">Customer contact</span></span>
* <span data-ttu-id="9e1b1-132">通貨</span><span class="sxs-lookup"><span data-stu-id="9e1b1-132">Currency</span></span>
* <span data-ttu-id="9e1b1-133">会計カレンダー</span><span class="sxs-lookup"><span data-stu-id="9e1b1-133">Fiscal calendar</span></span>
* <span data-ttu-id="9e1b1-134">会計暦年</span><span class="sxs-lookup"><span data-stu-id="9e1b1-134">Fiscal calendar year</span></span>
* <span data-ttu-id="9e1b1-135">為替レート タイプ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-135">Exchange rate types</span></span>
* <span data-ttu-id="9e1b1-136">為替レート ペア</span><span class="sxs-lookup"><span data-stu-id="9e1b1-136">Exchange rate pair</span></span>
* <span data-ttu-id="9e1b1-137">元帳会計期間および財務カレンダー期間</span><span class="sxs-lookup"><span data-stu-id="9e1b1-137">Ledger fiscal periods and financial calendar period</span></span>
* <span data-ttu-id="9e1b1-138">主勘定カテゴリ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-138">Main account category</span></span>
* <span data-ttu-id="9e1b1-139">主勘定</span><span class="sxs-lookup"><span data-stu-id="9e1b1-139">Main account</span></span>
* <span data-ttu-id="9e1b1-140">元帳</span><span class="sxs-lookup"><span data-stu-id="9e1b1-140">Ledger</span></span>
* <span data-ttu-id="9e1b1-141">為替レート</span><span class="sxs-lookup"><span data-stu-id="9e1b1-141">Exchange rates</span></span>
* <span data-ttu-id="9e1b1-142">分析コードの属性</span><span class="sxs-lookup"><span data-stu-id="9e1b1-142">Dimension attribute</span></span>
* <span data-ttu-id="9e1b1-143">分析コード統合形式</span><span class="sxs-lookup"><span data-stu-id="9e1b1-143">Dimension integration format</span></span>
* <span data-ttu-id="9e1b1-144">組織分類および組織階層の目的</span><span class="sxs-lookup"><span data-stu-id="9e1b1-144">Organization classification and organization hierarchy purpose</span></span>
* <span data-ttu-id="9e1b1-145">組織階層</span><span class="sxs-lookup"><span data-stu-id="9e1b1-145">Organization hierarchy</span></span>
* <span data-ttu-id="9e1b1-146">組織階層タイプ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-146">Organization hierarchy type</span></span>
* <span data-ttu-id="9e1b1-147">会社</span><span class="sxs-lookup"><span data-stu-id="9e1b1-147">Company</span></span>
* <span data-ttu-id="9e1b1-148">リリースされた製品</span><span class="sxs-lookup"><span data-stu-id="9e1b1-148">Released products</span></span>
* <span data-ttu-id="9e1b1-149">特徴的リリース済製品</span><span class="sxs-lookup"><span data-stu-id="9e1b1-149">Distinct released products</span></span>
* <span data-ttu-id="9e1b1-150">製品番号で特定されたバーコード エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-150">Product number identified barcode entity</span></span>
* <span data-ttu-id="9e1b1-151">グローバル製品</span><span class="sxs-lookup"><span data-stu-id="9e1b1-151">Global products</span></span>
* <span data-ttu-id="9e1b1-152">製品の既定の注文設定エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-152">Product default order settings entity</span></span>
* <span data-ttu-id="9e1b1-153">製品固有の既定の注文設定</span><span class="sxs-lookup"><span data-stu-id="9e1b1-153">Product specific default order settings</span></span>
* <span data-ttu-id="9e1b1-154">製品分析コード グループ エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-154">Product dimension group entity</span></span>
* <span data-ttu-id="9e1b1-155">追跡用分析コード グループ エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-155">Tracking dimension group entity</span></span>
* <span data-ttu-id="9e1b1-156">測定単位エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-156">Unit of measures entity</span></span>
* <span data-ttu-id="9e1b1-157">測定単位換算</span><span class="sxs-lookup"><span data-stu-id="9e1b1-157">Unit of measure conversion</span></span>
* <span data-ttu-id="9e1b1-158">製品固有の測定単位換算</span><span class="sxs-lookup"><span data-stu-id="9e1b1-158">Product specific unit of measure conversion</span></span>
* <span data-ttu-id="9e1b1-159">サイト エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-159">Site entity</span></span>
* <span data-ttu-id="9e1b1-160">倉庫エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-160">Warehouses entity</span></span>
* <span data-ttu-id="9e1b1-161">色エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-161">Color entity</span></span>
* <span data-ttu-id="9e1b1-162">サイズ エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-162">Size entity</span></span>
* <span data-ttu-id="9e1b1-163">保管分析コード グループ エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-163">Storage dimension group entity</span></span>
* <span data-ttu-id="9e1b1-164">スタイル エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-164">Style entity</span></span>
* <span data-ttu-id="9e1b1-165">構成エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-165">Configuration entity</span></span>
* <span data-ttu-id="9e1b1-166">EcoResProductMasterColor エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-166">EcoResProductMasterColor entity</span></span>
* <span data-ttu-id="9e1b1-167">EcoResProductMasterSize エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-167">EcoResProductMasterSize entity</span></span>
* <span data-ttu-id="9e1b1-168">EcoResProductMasterStyle エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-168">EcoResProductMasterStyle entity</span></span>
* <span data-ttu-id="9e1b1-169">EcoResProductMasterConfig エンティティ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-169">EcoResProductMasterConfig entity</span></span>
* <span data-ttu-id="9e1b1-170">製品カテゴリ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-170">Product categories</span></span>
* <span data-ttu-id="9e1b1-171">製品カテゴリの割り当て</span><span class="sxs-lookup"><span data-stu-id="9e1b1-171">Product category assignments</span></span>
* <span data-ttu-id="9e1b1-172">製品カテゴリ階層</span><span class="sxs-lookup"><span data-stu-id="9e1b1-172">Product category hierarchies</span></span>
* <span data-ttu-id="9e1b1-173">製品カテゴリ階層ロール</span><span class="sxs-lookup"><span data-stu-id="9e1b1-173">Product category hierarchy roles</span></span>
* <span data-ttu-id="9e1b1-174">税グループ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-174">Tax groups</span></span>
* <span data-ttu-id="9e1b1-175">税品目グループ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-175">Tax item groups</span></span>
* <span data-ttu-id="9e1b1-176">免税</span><span class="sxs-lookup"><span data-stu-id="9e1b1-176">Tax exemptions</span></span>
* <span data-ttu-id="9e1b1-177">税務当局</span><span class="sxs-lookup"><span data-stu-id="9e1b1-177">Tax authorities</span></span>
* <span data-ttu-id="9e1b1-178">源泉徴収税コード</span><span class="sxs-lookup"><span data-stu-id="9e1b1-178">Withholding tax codes</span></span>
* <span data-ttu-id="9e1b1-179">源泉徴収税グループ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-179">Withholding tax groups</span></span>
* <span data-ttu-id="9e1b1-180">税勘定科目グループと税転記グループ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-180">Tax ledger account group and tax posting groups</span></span>
* <span data-ttu-id="9e1b1-181">仕入先</span><span class="sxs-lookup"><span data-stu-id="9e1b1-181">Vendors</span></span>
* <span data-ttu-id="9e1b1-182">仕入先グループ</span><span class="sxs-lookup"><span data-stu-id="9e1b1-182">Vendor groups</span></span>
* <span data-ttu-id="9e1b1-183">仕入先支払方法</span><span class="sxs-lookup"><span data-stu-id="9e1b1-183">Vendor payment method</span></span>
* <span data-ttu-id="9e1b1-184">仕入先連絡先</span><span class="sxs-lookup"><span data-stu-id="9e1b1-184">Vendor contacts</span></span>
* <span data-ttu-id="9e1b1-185">勘定科目表</span><span class="sxs-lookup"><span data-stu-id="9e1b1-185">Chart of accounts</span></span>

<span data-ttu-id="9e1b1-186">[フェーズ 1](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/finance-operations-crossapp-capabilities/data-common-data-service-phase-1) のプレビュー時には、マスター データと参照データのシナリオに関する一連の機能が引き続き提供されます。**フェーズ 2** の機能では、価格設定、見積、注文、請求書、資産など、エンドツーエンドのシナリオがサポートされる予定です。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-186">While the preview for the [Phase 1](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/finance-operations-crossapp-capabilities/data-common-data-service-phase-1) set of features around master and reference data scenarios are continuing, **Phase 2** features are about supporting end-to-end scenarios on pricing, quotes, orders, invoices, and assets.</span></span> <span data-ttu-id="9e1b1-187">これらのシナリオは、ユーザーとパートナーによってさらに充実させることができます。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-187">These scenarios can be further enriched by customers and partners.</span></span> <span data-ttu-id="9e1b1-188">これらの領域に対するエンティティの対応範囲は、プレビュー時に発表されます。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-188">Entity coverage for these areas will be revealed during preview.</span></span> 

<span data-ttu-id="9e1b1-189">フェーズ 2 の機能は、1 月から 2 月にかけてのプレビューを予定しています。</span><span class="sxs-lookup"><span data-stu-id="9e1b1-189">Phase 2 features are planned for preview in the January-February timeframe.</span></span>

<!--feature detail end -->









