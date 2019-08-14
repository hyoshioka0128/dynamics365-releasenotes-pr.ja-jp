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
# <a name="finance-and-operations-data-in-common-data-service---phase-1"></a>Common Data Service での Finance and Operations のデータ - フェーズ 1
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 7 月 24 日| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能は、Dynamics 365 for Finance and Operations と Common Data Service の間のシームレスなデータ交換を容易にします。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Dynamics 365 for Finance and Operations のデータを Common Data Service で取得し、最新の状態に保ちます。 

Microsoft では、二重書き込みのセットアップを特別な設定が不要なエクスペリエンスにしています。 これにより、企業はアプリの境界を超えてリアルタイムに近いデータを同期双方向方式でシームレスに交換できます。 Microsoft では、ユーザーに "1 つの Dynamics 365" エクスペリエンスを提供したいと考えています。 

すべてのビジネスが本質的に固有のものであることがわかっているので、二重書き込みフレームワークを拡張可能にしました。 これには、カスタム エンティティの有効化に加え、Common Data Service と最重要ビジネス データ用の関連ツールをフル活用するための既存のエンティティへの拡張が含まれます。



## <a name="phase-1-release"></a>フェーズ 1 リリース
フェーズ 1 リリースでは、顧客、仕入先、および製品にマルチマスター機能を提供します。Common Data Service での会社の概念および Dynamics 365 ユーザーのシングルユーザー管理エクスペリエンスも導入されています。 これらの機能は 6 月のパブリック プレビューでリリースされ、10 月には一般提供される予定です。 対象となっているエンティティは次のとおりです。 

OMOrganizationHierarchyPurposeEntity</br>
OMOrganizationHierarchyPublishedEntity</br>
OMOrganizationHierarchyTypeEntity</br>
OMOperatingUnitEntity</br>
OMLegalEntity</br>
CustCustomerGroupEntity</br>
PaymentTermEntity</br>
CustomerPaymentMethodEntity</br>
CustCustomerV3Entity</br>
VendVendorV2Entity</br>
VendVendorGroupEntity</br>
VendorPaymentMethodEntity</br>
SmmContactPersonEntity</br>
RetailLoyaltyCardEntity</br>
PaymentScheduleEntity</br>
PaymentScheduleLineEntity</br>
CDSPaymentDayEntity</br>
CDSPaymentDayLineEntity</br>
EcoResProductCDS</br>
CDSEcoResProductMaster</br>
EcoResProductProperties</br>
EcoResProductBarcode</br>
EcoResProductDefaultOrderSettings</br>
EcoResProductDimensionGroup</br>
UnitOfMeasures</br>
NameAffix

## <a name="phase-2-release"></a>フェーズ 2 リリース
フェーズ 2 リリースでは、プロジェクト、在庫、販売、調達から財務までをカバーするエンドツーエンドのシナリオがサポートされます。 これらの分野で最も重要なエンティティをサポートする、すぐに使えるなシナリオが既定で提供されます。 これらのシナリオは、Finance and Operations と Common Data Service 全体に拡張されるように、顧客とパートナーがさらに充実させることができます。 

これらの機能は 10 月のパブリック プレビューでリリースされ、4 月には一般提供される予定です。 対象となるエンティティは後日発表されます。
<!--feature detail end -->












## <a name="see-also"></a>関連項目

[プレビュー: Finance and Operations と Common Data Service の統合 - フェーズ 1](https://cloudblogs.microsoft.com/dynamics365/?p=78375&secret=DT7uTp)
