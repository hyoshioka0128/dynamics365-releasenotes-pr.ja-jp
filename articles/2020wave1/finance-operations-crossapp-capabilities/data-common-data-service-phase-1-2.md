---
title: Common Data Service のデータ - フェーズ 1 と 2
description: Common Data Service のデータ - フェーズ 1 と 2
author: RamaKrishnamoorthy
ms.reviewer: rhaertle
ms.date: 04/01/2020
ms.assetid: 5838d44d-8d1b-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: ramasri
dynamics365pdf: true
ms.openlocfilehash: 88b558589dae39d149a3a56f72aba9451aa8c5de
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3231881"
---
# <a name="data-in-common-data-service--phase-1--2"></a><span data-ttu-id="4863c-103">Common Data Service のデータ - フェーズ 1 と 2</span><span class="sxs-lookup"><span data-stu-id="4863c-103">Data in Common Data Service – phase 1 & 2</span></span>


| <span data-ttu-id="4863c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="4863c-104">Enabled for</span></span>    |  <span data-ttu-id="4863c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="4863c-105">Public preview</span></span> | <span data-ttu-id="4863c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="4863c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="4863c-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="4863c-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="4863c-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="4863c-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="4863c-109">2020 年 2 月 19 日</span><span class="sxs-lookup"><span data-stu-id="4863c-109">Feb 19, 2020</span></span>| <span data-ttu-id="4863c-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="4863c-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="4863c-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="4863c-111">Apr 1, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="4863c-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="4863c-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="4863c-113">Finance and Operations アプリのデータを Common Data Service で取得し、最新の状態に保ちます。</span><span class="sxs-lookup"><span data-stu-id="4863c-113">Get your Finance and Operations apps data in Common Data Service and keep it up to date.</span></span> 

<span data-ttu-id="4863c-114">Finance and Operations アプリと Dynamics 365 のモデル駆動型アプリの間で収束する概念を調和させることで、二重書き込みフレームワークをシームレスなエクスペリエンスにしています。</span><span class="sxs-lookup"><span data-stu-id="4863c-114">We are making the dual-write framework a seamless experience by harmonizing the converging concepts between Finance and Operations apps and model-driven apps in Dynamics 365.</span></span> <span data-ttu-id="4863c-115">これにより、企業はアプリの境界を超えて、ニア リアルタイムのデータを同期的に、双方向で交換できるようになるため、統合されたエクスペリエンスがユーザーに提供されます。</span><span class="sxs-lookup"><span data-stu-id="4863c-115">This allows businesses to exchange near real-time data in a synchronous, bidirectional fashion beyond application boundaries, giving users a unified experience.</span></span> 

<span data-ttu-id="4863c-116">すべてのビジネスが固有のものであることがわかっているので、二重書き込みフレームワークを拡張可能にしました。</span><span class="sxs-lookup"><span data-stu-id="4863c-116">Knowing every business is unique, we have made the dual-write framework extensible.</span></span> <span data-ttu-id="4863c-117">これには、カスタム エンティティの有効化に加え、Common Data Service と最重要ビジネス データ用の関連ツールをフルに使用するための既存のエンティティへの拡張が含まれます。</span><span class="sxs-lookup"><span data-stu-id="4863c-117">This includes enabling custom entities, as well as extensions to existing entities, to fully use Common Data Service and surrounding tools for your most important business data.</span></span>

## <a name="phased-release"></a><span data-ttu-id="4863c-118">段階的リリース</span><span class="sxs-lookup"><span data-stu-id="4863c-118">Phased release</span></span>
<span data-ttu-id="4863c-119">フェーズ 1 の機能は、顧客、仕入先、および製品にマルチマスタリング機能を提供すると共に、Common Data Service に企業コンセプトを導入します。</span><span class="sxs-lookup"><span data-stu-id="4863c-119">Phase 1 features provide multimastering capabilities for customers, vendors, and products, along with an introduction of the company concept in Common Data Service.</span></span> <span data-ttu-id="4863c-120">また、会計と税の参照データも含まれています。</span><span class="sxs-lookup"><span data-stu-id="4863c-120">It also includes finance and tax reference data.</span></span> <span data-ttu-id="4863c-121">これらの機能は、2019 年 7 月からプレビューされています。</span><span class="sxs-lookup"><span data-stu-id="4863c-121">These features have been in preview since July 2019.</span></span> 

<span data-ttu-id="4863c-122">次のエンティティがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="4863c-122">The following entities are supported:</span></span> 

* <span data-ttu-id="4863c-123">支払スケジュール - ヘッダー</span><span class="sxs-lookup"><span data-stu-id="4863c-123">Payment schedules - Header</span></span>  
* <span data-ttu-id="4863c-124">支払スケジュール – 明細行</span><span class="sxs-lookup"><span data-stu-id="4863c-124">Payment schedules – Line</span></span>
* <span data-ttu-id="4863c-125">支払期日 - ヘッダー</span><span class="sxs-lookup"><span data-stu-id="4863c-125">Payment day - Header</span></span>
* <span data-ttu-id="4863c-126">支払期日 - 明細行</span><span class="sxs-lookup"><span data-stu-id="4863c-126">Payment day - Line</span></span>
* <span data-ttu-id="4863c-127">顧客グループ</span><span class="sxs-lookup"><span data-stu-id="4863c-127">Customer groups</span></span>
* <span data-ttu-id="4863c-128">支払条件</span><span class="sxs-lookup"><span data-stu-id="4863c-128">Terms of payment</span></span>
* <span data-ttu-id="4863c-129">顧客支払方法</span><span class="sxs-lookup"><span data-stu-id="4863c-129">Customer payment method</span></span>
* <span data-ttu-id="4863c-130">ロイヤルティ カード</span><span class="sxs-lookup"><span data-stu-id="4863c-130">Loyalty card</span></span>
* <span data-ttu-id="4863c-131">ロイヤルティ報酬ポイント</span><span class="sxs-lookup"><span data-stu-id="4863c-131">Loyalty reward points</span></span>
* <span data-ttu-id="4863c-132">顧客</span><span class="sxs-lookup"><span data-stu-id="4863c-132">Customers</span></span>
* <span data-ttu-id="4863c-133">顧客の連絡先</span><span class="sxs-lookup"><span data-stu-id="4863c-133">Customer contact</span></span>
* <span data-ttu-id="4863c-134">通貨</span><span class="sxs-lookup"><span data-stu-id="4863c-134">Currency</span></span>
* <span data-ttu-id="4863c-135">会計カレンダー</span><span class="sxs-lookup"><span data-stu-id="4863c-135">Fiscal calendar</span></span>
* <span data-ttu-id="4863c-136">会計暦年</span><span class="sxs-lookup"><span data-stu-id="4863c-136">Fiscal calendar year</span></span>
* <span data-ttu-id="4863c-137">為替レート タイプ</span><span class="sxs-lookup"><span data-stu-id="4863c-137">Exchange rate types</span></span>
* <span data-ttu-id="4863c-138">為替レート ペア</span><span class="sxs-lookup"><span data-stu-id="4863c-138">Exchange rate pair</span></span>
* <span data-ttu-id="4863c-139">元帳会計期間および財務カレンダー期間</span><span class="sxs-lookup"><span data-stu-id="4863c-139">Ledger fiscal periods and financial calendar period</span></span>
* <span data-ttu-id="4863c-140">主勘定カテゴリ</span><span class="sxs-lookup"><span data-stu-id="4863c-140">Main account category</span></span>
* <span data-ttu-id="4863c-141">主勘定</span><span class="sxs-lookup"><span data-stu-id="4863c-141">Main account</span></span>
* <span data-ttu-id="4863c-142">元帳</span><span class="sxs-lookup"><span data-stu-id="4863c-142">Ledger</span></span>
* <span data-ttu-id="4863c-143">為替レート</span><span class="sxs-lookup"><span data-stu-id="4863c-143">Exchange rates</span></span>
* <span data-ttu-id="4863c-144">分析コードの属性</span><span class="sxs-lookup"><span data-stu-id="4863c-144">Dimension attribute</span></span>
* <span data-ttu-id="4863c-145">分析コード統合形式</span><span class="sxs-lookup"><span data-stu-id="4863c-145">Dimension integration format</span></span>
* <span data-ttu-id="4863c-146">組織分類および組織階層の目的</span><span class="sxs-lookup"><span data-stu-id="4863c-146">Organization classification and organization hierarchy purpose</span></span>
* <span data-ttu-id="4863c-147">組織階層</span><span class="sxs-lookup"><span data-stu-id="4863c-147">Organization hierarchy</span></span>
* <span data-ttu-id="4863c-148">組織階層タイプ</span><span class="sxs-lookup"><span data-stu-id="4863c-148">Organization hierarchy type</span></span>
* <span data-ttu-id="4863c-149">会社</span><span class="sxs-lookup"><span data-stu-id="4863c-149">Company</span></span>
* <span data-ttu-id="4863c-150">リリースされた製品</span><span class="sxs-lookup"><span data-stu-id="4863c-150">Released products</span></span>
* <span data-ttu-id="4863c-151">特徴的リリース済製品</span><span class="sxs-lookup"><span data-stu-id="4863c-151">Distinct released products</span></span>
* <span data-ttu-id="4863c-152">製品番号で特定されたバーコード エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-152">Product number identified barcode entity</span></span>
* <span data-ttu-id="4863c-153">グローバル製品</span><span class="sxs-lookup"><span data-stu-id="4863c-153">Global products</span></span>
* <span data-ttu-id="4863c-154">製品の既定の注文設定エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-154">Product default order settings entity</span></span>
* <span data-ttu-id="4863c-155">製品固有の既定の注文設定</span><span class="sxs-lookup"><span data-stu-id="4863c-155">Product specific default order settings</span></span>
* <span data-ttu-id="4863c-156">製品分析コード グループ エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-156">Product dimension group entity</span></span>
* <span data-ttu-id="4863c-157">追跡用分析コード グループ エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-157">Tracking dimension group entity</span></span>
* <span data-ttu-id="4863c-158">測定単位エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-158">Unit of measures entity</span></span>
* <span data-ttu-id="4863c-159">測定単位換算</span><span class="sxs-lookup"><span data-stu-id="4863c-159">Unit of measure conversion</span></span>
* <span data-ttu-id="4863c-160">製品固有の測定単位換算</span><span class="sxs-lookup"><span data-stu-id="4863c-160">Product specific unit of measure conversion</span></span>
* <span data-ttu-id="4863c-161">サイト エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-161">Site entity</span></span>
* <span data-ttu-id="4863c-162">倉庫エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-162">Warehouses entity</span></span>
* <span data-ttu-id="4863c-163">色エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-163">Color entity</span></span>
* <span data-ttu-id="4863c-164">サイズ エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-164">Size entity</span></span>
* <span data-ttu-id="4863c-165">保管分析コード グループ エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-165">Storage dimension group entity</span></span>
* <span data-ttu-id="4863c-166">スタイル エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-166">Style entity</span></span>
* <span data-ttu-id="4863c-167">構成エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-167">Configuration entity</span></span>
* <span data-ttu-id="4863c-168">EcoResProductMasterColor エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-168">EcoResProductMasterColor entity</span></span>
* <span data-ttu-id="4863c-169">EcoResProductMasterSize エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-169">EcoResProductMasterSize entity</span></span>
* <span data-ttu-id="4863c-170">EcoResProductMasterStyle エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-170">EcoResProductMasterStyle entity</span></span>
* <span data-ttu-id="4863c-171">EcoResProductMasterConfig エンティティ</span><span class="sxs-lookup"><span data-stu-id="4863c-171">EcoResProductMasterConfig entity</span></span>
* <span data-ttu-id="4863c-172">製品カテゴリ</span><span class="sxs-lookup"><span data-stu-id="4863c-172">Product categories</span></span>
* <span data-ttu-id="4863c-173">製品カテゴリの割り当て</span><span class="sxs-lookup"><span data-stu-id="4863c-173">Product category assignments</span></span>
* <span data-ttu-id="4863c-174">製品カテゴリ階層</span><span class="sxs-lookup"><span data-stu-id="4863c-174">Product category hierarchies</span></span>
* <span data-ttu-id="4863c-175">製品カテゴリ階層ロール</span><span class="sxs-lookup"><span data-stu-id="4863c-175">Product category hierarchy roles</span></span>
* <span data-ttu-id="4863c-176">税グループ</span><span class="sxs-lookup"><span data-stu-id="4863c-176">Tax groups</span></span>
* <span data-ttu-id="4863c-177">税品目グループ</span><span class="sxs-lookup"><span data-stu-id="4863c-177">Tax item groups</span></span>
* <span data-ttu-id="4863c-178">免税</span><span class="sxs-lookup"><span data-stu-id="4863c-178">Tax exemptions</span></span>
* <span data-ttu-id="4863c-179">税務当局</span><span class="sxs-lookup"><span data-stu-id="4863c-179">Tax authorities</span></span>
* <span data-ttu-id="4863c-180">源泉徴収税コード</span><span class="sxs-lookup"><span data-stu-id="4863c-180">Withholding tax codes</span></span>
* <span data-ttu-id="4863c-181">源泉徴収税グループ</span><span class="sxs-lookup"><span data-stu-id="4863c-181">Withholding tax groups</span></span>
* <span data-ttu-id="4863c-182">税勘定科目グループと税転記グループ</span><span class="sxs-lookup"><span data-stu-id="4863c-182">Tax ledger account group and tax posting groups</span></span>
* <span data-ttu-id="4863c-183">仕入先</span><span class="sxs-lookup"><span data-stu-id="4863c-183">Vendors</span></span>
* <span data-ttu-id="4863c-184">仕入先グループ</span><span class="sxs-lookup"><span data-stu-id="4863c-184">Vendor groups</span></span>
* <span data-ttu-id="4863c-185">仕入先支払方法</span><span class="sxs-lookup"><span data-stu-id="4863c-185">Vendor payment method</span></span>
* <span data-ttu-id="4863c-186">仕入先連絡先</span><span class="sxs-lookup"><span data-stu-id="4863c-186">Vendor contacts</span></span>
* <span data-ttu-id="4863c-187">勘定科目表</span><span class="sxs-lookup"><span data-stu-id="4863c-187">Chart of accounts</span></span>

<span data-ttu-id="4863c-188">[フェーズ 1](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/finance-operations-crossapp-capabilities/data-common-data-service-phase-1) のプレビュー時には、マスター データと参照データのシナリオに関する一連の機能が引き続き提供されます。**フェーズ 2** の機能では、価格設定、見積、注文、請求書、資産など、エンドツーエンドのシナリオがサポートされる予定です。</span><span class="sxs-lookup"><span data-stu-id="4863c-188">While the preview for the [Phase 1](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/finance-operations-crossapp-capabilities/data-common-data-service-phase-1) set of features around master and reference data scenarios are continuing, **Phase 2** features are about supporting end-to-end scenarios on pricing, quotes, orders, invoices, and assets.</span></span> <span data-ttu-id="4863c-189">これらのシナリオは、ユーザーとパートナーによってさらに充実させることができます。</span><span class="sxs-lookup"><span data-stu-id="4863c-189">These scenarios can be further enriched by customers and partners.</span></span> <span data-ttu-id="4863c-190">これらの領域に対するエンティティの対応範囲は、プレビュー時に発表されます。</span><span class="sxs-lookup"><span data-stu-id="4863c-190">Entity coverage for these areas will be revealed during preview.</span></span> 

<span data-ttu-id="4863c-191">フェーズ 2 の機能は、1 月から 2 月にかけてのプレビューを予定しています。</span><span class="sxs-lookup"><span data-stu-id="4863c-191">Phase 2 features are planned for preview in the January-February timeframe.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="4863c-192">関連項目</span><span class="sxs-lookup"><span data-stu-id="4863c-192">See also</span></span>


<!--docs start-->
<span data-ttu-id="4863c-193">[二重書き込みのホームページ](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/dual-write/dual-write-home-page) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="4863c-193">[Dual-write home page](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/dual-write/dual-write-home-page) (docs)</span></span>
<!--docs end-->

