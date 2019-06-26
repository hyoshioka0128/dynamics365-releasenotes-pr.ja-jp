---
title: Common Data Service での Finance and Operations のデータ
description: Common Data Service での Finance and Operations のデータ
author: RamaKrishnamoorthy
ms.reviewer: sericks
ms.date: 05/29/2019
ms.assetid: fc62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: ramasri
dynamics365pdf: true
---
# <a name="finance-and-operations-data-in-common-data-service"></a>Common Data Service での Finance and Operations のデータ
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 6 月| 近日発表|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能は、Dynamics 365 for Finance and Operations と Common Data Service の間のシームレスなデータ交換を容易にします。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Dynamics 365 for Finance and Operations のデータを Common Data Service で取得し、最新の状態に保ちます。 

Microsoft では、二重書き込みのセットアップを特別な設定が不要なエクスペリエンスにしています。 これにより、企業はアプリの境界を超えてリアルタイムに近いデータを同期双方向方式でシームレスに交換できます。 Microsoft では、ユーザーに "1 つの Dynamics 365" エクスペリエンスを提供したいと考えています。 

すべてのビジネスが本質的に固有のものであることがわかっているので、二重書き込みフレームワークを拡張可能にしました。 これには、カスタム エンティティの有効化に加え、Common Data Service と最重要ビジネス データ用の関連ツールをフル活用するための既存のエンティティへの拡張が含まれます。

<!--note from editor: Confirming that the terms "Phase 1 and Phase 2 still work, given the new naming of release "2019 release wave 2".   -->

## <a name="phase-1-release"></a>フェーズ 1 リリース
フェーズ 1 リリースでは、顧客、仕入先、および製品にマルチマスター機能を提供します。Common Data Service での会社の概念および Dynamics 365 ユーザーのシングルユーザー管理エクスペリエンスも導入されています。 これらの機能は 6 月のパブリック プレビューでリリースされ、10 月には一般提供される予定です。 対象となっているエンティティは次のとおりです。 

OMOrganizationHierarchyPurposeEntity, OMOrganizationHierarchyPublishedEntity, OMOrganizationHierarchyTypeEntity, OMOperatingUnitEntity, OMLegalEntity, CustCustomerGroupEntity, PaymentTermEntity, CustomerPaymentMethodEntity, CustCustomerV3Entity, VendVendorV2Entity, VendVendorGroupEntity, VendorPaymentMethodEntity, SmmContactPersonEntity, RetailLoyaltyCardEntity, PaymentScheduleEntity, PaymentScheduleLineEntity, CDSPaymentDayEntity, CDSPaymentDayLineEntity, EcoResProductCDS, CDSEcoResProductMaster, EcoResProductProperties, EcoResProductBarcode, EcoResProductDefaultOrderSettings, EcoResProductDimensionGroup, UnitOfMeasures, NameAffix.

## <a name="phase-2-release"></a>フェーズ 2 リリース
フェーズ 2 リリースでは、プロジェクト、在庫、販売、調達から財務までをカバーするエンドツーエンドのシナリオがサポートされます。 これらの分野で最も重要なエンティティをサポートする、すぐに使えるなシナリオが既定で提供されます。 これらのシナリオは、Finance and Operations と Common Data Service 全体に拡張されるように、顧客とパートナーがさらに充実させることができます。 

これらの機能は 10 月のパブリック プレビューでリリースされ、4 月には一般提供される予定です。 対象となるエンティティは後日発表されます。
<!--feature detail end -->










