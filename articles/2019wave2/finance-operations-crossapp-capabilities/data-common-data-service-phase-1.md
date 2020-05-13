---
title: Common Data Service のデータ – フェーズ 1
description: Common Data Service のデータ – フェーズ 1
author: RamaKrishnamoorthy
ms.reviewer: rhaertle
ms.date: 04/06/2020
ms.assetid: fc62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: ramasri
dynamics365pdf: true
ms.openlocfilehash: 0cebd86d33b3a1b849cc24c12e5fcaf70ee34995
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320756"
---
# <a name="data-in-common-data-service--phase-1"></a><span data-ttu-id="8b55e-103">Common Data Service のデータ – フェーズ 1</span><span class="sxs-lookup"><span data-stu-id="8b55e-103">Data in Common Data Service – Phase 1</span></span>


| <span data-ttu-id="8b55e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8b55e-104">Enabled for</span></span>    |  <span data-ttu-id="8b55e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8b55e-105">Public preview</span></span> | <span data-ttu-id="8b55e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8b55e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8b55e-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="8b55e-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="8b55e-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8b55e-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8b55e-109">2019 年 7 月 24 日</span><span class="sxs-lookup"><span data-stu-id="8b55e-109">Jul 24, 2019</span></span>| <span data-ttu-id="8b55e-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8b55e-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8b55e-111">2020 年 3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="8b55e-111">Mar 27, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="8b55e-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8b55e-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8b55e-113">この機能は、Common Data Service とのシームレスなデータ交換を容易にします。</span><span class="sxs-lookup"><span data-stu-id="8b55e-113">This feature facilitates seamless data exchange with Common Data Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8b55e-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8b55e-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8b55e-115">Common Data Service のデータを取得し、最新の状態に保ちます。</span><span class="sxs-lookup"><span data-stu-id="8b55e-115">Get your data in Common Data Service and keep it up to date.</span></span> 

<span data-ttu-id="8b55e-116">Microsoft では、二重書き込みを追加設定なしで利用できるようにしています。</span><span class="sxs-lookup"><span data-stu-id="8b55e-116">We are making the dual-write setup an out-of-the-box experience.</span></span> <span data-ttu-id="8b55e-117">これにより、企業はアプリの境界を超えてリアルタイムに近いデータを同期双方向方式でシームレスに交換できます。</span><span class="sxs-lookup"><span data-stu-id="8b55e-117">This will allow businesses to exchange near real-time data seamlessly in a synchronous bidirectional fashion, beyond application boundaries.</span></span> <span data-ttu-id="8b55e-118">Microsoft では、ユーザーに "1 つの Dynamics 365" エクスペリエンスを提供したいと考えています。</span><span class="sxs-lookup"><span data-stu-id="8b55e-118">We want to provide users a "One Dynamics 365" experience.</span></span> 

<span data-ttu-id="8b55e-119">すべてのビジネスが本質的に固有のものであることがわかっているので、二重書き込みフレームワークを拡張可能にしました。</span><span class="sxs-lookup"><span data-stu-id="8b55e-119">Knowing every business is unique in itself, we have made the dual-write framework extensible.</span></span> <span data-ttu-id="8b55e-120">これには、カスタム エンティティの有効化に加え、Common Data Service と最重要ビジネス データ用の関連ツールをフル活用するための既存のエンティティへの拡張が含まれます。</span><span class="sxs-lookup"><span data-stu-id="8b55e-120">This includes enabling custom entities, as well as extensions to existing entities, to fully utilize Common Data Service and surrounding tools for your most important business data.</span></span>

## <a name="phase-1-release"></a><span data-ttu-id="8b55e-121">フェーズ 1 リリース</span><span class="sxs-lookup"><span data-stu-id="8b55e-121">Phase 1 release</span></span>
<span data-ttu-id="8b55e-122">フェーズ 1 リリースでは、顧客、仕入先、および製品にマルチマスター機能を提供します。Common Data Service での会社の概念および Dynamics 365 ユーザーのシングルユーザー管理エクスペリエンスも導入されています。</span><span class="sxs-lookup"><span data-stu-id="8b55e-122">The Phase 1 release provides multi-mastering capabilities for customers, vendors, and products, along with an introduction to the company concept in Common Data Service and the single-user management experience for Dynamics 365 users.</span></span> <span data-ttu-id="8b55e-123">また、会計と税の参照データも含まれています。</span><span class="sxs-lookup"><span data-stu-id="8b55e-123">It also includes finance and tax reference data.</span></span> <span data-ttu-id="8b55e-124">これらの機能は 6 月のパブリック プレビューでリリースされ、10 月には一般提供される予定です。</span><span class="sxs-lookup"><span data-stu-id="8b55e-124">These features will be released in public preview in June and made generally available in the October time frame.</span></span> <span data-ttu-id="8b55e-125">対象となっているエンティティは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="8b55e-125">Entities that are being covered are as follows:</span></span> 

* <span data-ttu-id="8b55e-126">支払スケジュール - ヘッダー</span><span class="sxs-lookup"><span data-stu-id="8b55e-126">Payment schedules - Header</span></span>  
* <span data-ttu-id="8b55e-127">支払スケジュール – 明細行</span><span class="sxs-lookup"><span data-stu-id="8b55e-127">Payment schedules – Line</span></span>
* <span data-ttu-id="8b55e-128">支払期日 - ヘッダー</span><span class="sxs-lookup"><span data-stu-id="8b55e-128">Payment day - Header</span></span>
* <span data-ttu-id="8b55e-129">支払期日 - 明細行</span><span class="sxs-lookup"><span data-stu-id="8b55e-129">Payment day - Line</span></span>
* <span data-ttu-id="8b55e-130">顧客グループ</span><span class="sxs-lookup"><span data-stu-id="8b55e-130">Customer groups</span></span>
* <span data-ttu-id="8b55e-131">支払条件</span><span class="sxs-lookup"><span data-stu-id="8b55e-131">Terms of payment</span></span>
* <span data-ttu-id="8b55e-132">顧客支払方法</span><span class="sxs-lookup"><span data-stu-id="8b55e-132">Customer payment method</span></span>
* <span data-ttu-id="8b55e-133">ロイヤルティ カード</span><span class="sxs-lookup"><span data-stu-id="8b55e-133">Loyalty card</span></span>
* <span data-ttu-id="8b55e-134">ロイヤルティ報酬ポイント</span><span class="sxs-lookup"><span data-stu-id="8b55e-134">Loyalty reward points</span></span>
* <span data-ttu-id="8b55e-135">顧客</span><span class="sxs-lookup"><span data-stu-id="8b55e-135">Customers</span></span>
* <span data-ttu-id="8b55e-136">顧客の連絡先</span><span class="sxs-lookup"><span data-stu-id="8b55e-136">Customer contact</span></span>
* <span data-ttu-id="8b55e-137">通貨</span><span class="sxs-lookup"><span data-stu-id="8b55e-137">Currency</span></span>
* <span data-ttu-id="8b55e-138">会計カレンダー</span><span class="sxs-lookup"><span data-stu-id="8b55e-138">Fiscal calendar</span></span>
* <span data-ttu-id="8b55e-139">会計暦年</span><span class="sxs-lookup"><span data-stu-id="8b55e-139">Fiscal calendar year</span></span>
* <span data-ttu-id="8b55e-140">為替レート タイプ</span><span class="sxs-lookup"><span data-stu-id="8b55e-140">Exchange rate types</span></span>
* <span data-ttu-id="8b55e-141">為替レート ペア</span><span class="sxs-lookup"><span data-stu-id="8b55e-141">Exchange rate pair</span></span>
* <span data-ttu-id="8b55e-142">元帳会計期間/財務カレンダー期間</span><span class="sxs-lookup"><span data-stu-id="8b55e-142">Ledger fiscal periods/ Financial calendar period</span></span>
* <span data-ttu-id="8b55e-143">主勘定カテゴリ</span><span class="sxs-lookup"><span data-stu-id="8b55e-143">Main account category</span></span>
* <span data-ttu-id="8b55e-144">主勘定</span><span class="sxs-lookup"><span data-stu-id="8b55e-144">Main account</span></span>
* <span data-ttu-id="8b55e-145">元帳</span><span class="sxs-lookup"><span data-stu-id="8b55e-145">Ledger</span></span>
* <span data-ttu-id="8b55e-146">為替レート</span><span class="sxs-lookup"><span data-stu-id="8b55e-146">Exchange rates</span></span>
* <span data-ttu-id="8b55e-147">分析コードの属性</span><span class="sxs-lookup"><span data-stu-id="8b55e-147">Dimension attribute</span></span>
* <span data-ttu-id="8b55e-148">分析コード統合形式</span><span class="sxs-lookup"><span data-stu-id="8b55e-148">Dimension integration format</span></span>
* <span data-ttu-id="8b55e-149">組織分類/組織階層の目的</span><span class="sxs-lookup"><span data-stu-id="8b55e-149">Organization classification/Organization hierarchy purpose</span></span>
* <span data-ttu-id="8b55e-150">組織階層</span><span class="sxs-lookup"><span data-stu-id="8b55e-150">Organization hierarchy</span></span>
* <span data-ttu-id="8b55e-151">組織階層タイプ</span><span class="sxs-lookup"><span data-stu-id="8b55e-151">Organization hierarchy type</span></span>
* <span data-ttu-id="8b55e-152">会社</span><span class="sxs-lookup"><span data-stu-id="8b55e-152">Company</span></span>
* <span data-ttu-id="8b55e-153">リリースされた製品</span><span class="sxs-lookup"><span data-stu-id="8b55e-153">Released products</span></span>
* <span data-ttu-id="8b55e-154">特徴的リリース済製品</span><span class="sxs-lookup"><span data-stu-id="8b55e-154">Distinct released products</span></span>
* <span data-ttu-id="8b55e-155">製品番号で特定されたバーコード エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-155">Product number Identified barcode entity</span></span>
* <span data-ttu-id="8b55e-156">グローバル製品</span><span class="sxs-lookup"><span data-stu-id="8b55e-156">Global Products</span></span>
* <span data-ttu-id="8b55e-157">製品の既定の注文設定エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-157">Product Default order settings entity</span></span>
* <span data-ttu-id="8b55e-158">製品固有の既定の注文設定</span><span class="sxs-lookup"><span data-stu-id="8b55e-158">Product specific default order settings</span></span>
* <span data-ttu-id="8b55e-159">製品分析コード グループ エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-159">Product dimension group entity</span></span>
* <span data-ttu-id="8b55e-160">追跡用分析コード グループ エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-160">Tracking dimension group entity</span></span>
* <span data-ttu-id="8b55e-161">測定単位エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-161">Unit of measures entity</span></span>
* <span data-ttu-id="8b55e-162">測定単位換算</span><span class="sxs-lookup"><span data-stu-id="8b55e-162">Unit of measure conversion</span></span>
* <span data-ttu-id="8b55e-163">製品固有の測定単位換算</span><span class="sxs-lookup"><span data-stu-id="8b55e-163">Product specific unit of measure conversion</span></span>
* <span data-ttu-id="8b55e-164">サイト エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-164">Site entity</span></span>
* <span data-ttu-id="8b55e-165">倉庫エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-165">Warehouses entity</span></span>
* <span data-ttu-id="8b55e-166">色エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-166">Color entity</span></span>
* <span data-ttu-id="8b55e-167">サイズ エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-167">Size entity</span></span>
* <span data-ttu-id="8b55e-168">保管分析コード グループ エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-168">Storage dimension group entity</span></span>
* <span data-ttu-id="8b55e-169">スタイル エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-169">Style entity</span></span>
* <span data-ttu-id="8b55e-170">構成エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-170">Configuration entity</span></span>
* <span data-ttu-id="8b55e-171">EcoResProductMasterColor エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-171">EcoResProductMasterColor entity</span></span>
* <span data-ttu-id="8b55e-172">EcoResProductMasterSize エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-172">EcoResProductMasterSize entity</span></span>
* <span data-ttu-id="8b55e-173">EcoResProductMasterStyle エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-173">EcoResProductMasterStyle entity</span></span>
* <span data-ttu-id="8b55e-174">EcoResProductMasterConfig エンティティ</span><span class="sxs-lookup"><span data-stu-id="8b55e-174">EcoResProductMasterConfig entity</span></span>
* <span data-ttu-id="8b55e-175">製品カテゴリ</span><span class="sxs-lookup"><span data-stu-id="8b55e-175">Product categories</span></span>
* <span data-ttu-id="8b55e-176">製品カテゴリの割り当て</span><span class="sxs-lookup"><span data-stu-id="8b55e-176">Product category assignments</span></span>
* <span data-ttu-id="8b55e-177">製品カテゴリ階層</span><span class="sxs-lookup"><span data-stu-id="8b55e-177">Product category hierarchies</span></span>
* <span data-ttu-id="8b55e-178">製品カテゴリ階層ロール</span><span class="sxs-lookup"><span data-stu-id="8b55e-178">Product category hierarchy roles</span></span>
* <span data-ttu-id="8b55e-179">税グループ</span><span class="sxs-lookup"><span data-stu-id="8b55e-179">Tax groups</span></span>
* <span data-ttu-id="8b55e-180">税品目グループ</span><span class="sxs-lookup"><span data-stu-id="8b55e-180">Tax item groups</span></span>
* <span data-ttu-id="8b55e-181">免税</span><span class="sxs-lookup"><span data-stu-id="8b55e-181">Tax exemptions</span></span>
* <span data-ttu-id="8b55e-182">税務当局</span><span class="sxs-lookup"><span data-stu-id="8b55e-182">Tax authorities</span></span>
* <span data-ttu-id="8b55e-183">源泉徴収税コード</span><span class="sxs-lookup"><span data-stu-id="8b55e-183">Withholding tax codes</span></span>
* <span data-ttu-id="8b55e-184">源泉徴収税グループ</span><span class="sxs-lookup"><span data-stu-id="8b55e-184">Withholding tax groups</span></span>
* <span data-ttu-id="8b55e-185">税勘定科目グループ/税転記グループ</span><span class="sxs-lookup"><span data-stu-id="8b55e-185">Tax ledger account group/Tax posting groups</span></span>
* <span data-ttu-id="8b55e-186">仕入先</span><span class="sxs-lookup"><span data-stu-id="8b55e-186">Vendors</span></span>
* <span data-ttu-id="8b55e-187">仕入先グループ</span><span class="sxs-lookup"><span data-stu-id="8b55e-187">Vendor groups</span></span>
* <span data-ttu-id="8b55e-188">仕入先支払方法</span><span class="sxs-lookup"><span data-stu-id="8b55e-188">Vendor payment method</span></span>
* <span data-ttu-id="8b55e-189">仕入先連絡先</span><span class="sxs-lookup"><span data-stu-id="8b55e-189">Vendor contacts</span></span>
* <span data-ttu-id="8b55e-190">勘定科目表</span><span class="sxs-lookup"><span data-stu-id="8b55e-190">Chart of accounts</span></span>

## <a name="phase-2-release"></a><span data-ttu-id="8b55e-191">フェーズ 2 リリース</span><span class="sxs-lookup"><span data-stu-id="8b55e-191">Phase 2 release</span></span>
<span data-ttu-id="8b55e-192">フェーズ 2 リリースでは、プロジェクト、在庫、販売、調達から財務までをカバーするエンドツーエンドのシナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="8b55e-192">The Phase 2 release will target supporting end-to-end scenarios covering project, inventory, sales, and procurement through to financials.</span></span> <span data-ttu-id="8b55e-193">これらの分野で最も重要なエンティティをサポートする、すぐに使えるなシナリオが既定で提供されます。</span><span class="sxs-lookup"><span data-stu-id="8b55e-193">Out-of-the-box scenarios supporting the most important entities in these areas will be provided by default.</span></span> <span data-ttu-id="8b55e-194">これらのシナリオは、ユーザーとパートナーによってさらに充実させることができます。</span><span class="sxs-lookup"><span data-stu-id="8b55e-194">These scenarios can be further enriched by customers and partners.</span></span> 

<span data-ttu-id="8b55e-195">これらの機能は 10 月のパブリック プレビューでリリースされ、4 月には一般提供される予定です。</span><span class="sxs-lookup"><span data-stu-id="8b55e-195">These features will be released in public preview in October and made generally available in the April time frame.</span></span> <span data-ttu-id="8b55e-196">対象となるエンティティは後日発表されます。</span><span class="sxs-lookup"><span data-stu-id="8b55e-196">Entity coverage will be revealed at a future date.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="8b55e-197">関連項目</span><span class="sxs-lookup"><span data-stu-id="8b55e-197">See also</span></span>
<!--docs start-->
<span data-ttu-id="8b55e-198">[二重書き込みのホームページ](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/dual-write/dual-write-home-page) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="8b55e-198">[Dual-write home page](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/dual-write/dual-write-home-page) (docs)</span></span>
<!--docs end-->
