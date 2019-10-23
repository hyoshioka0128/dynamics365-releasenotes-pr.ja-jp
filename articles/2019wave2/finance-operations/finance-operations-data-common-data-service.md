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
# <a name="data-in-common-data-service---phase-1"></a>Common Data Service のデータ - フェーズ 1
[!include[finance-operations banner](../includes/finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 7 月 24 日| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能は、Common Data Service とのシームレスなデータ交換を容易にします。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Common Data Service のデータを取得し、最新の状態に保ちます。 

Microsoft では、二重書き込みを追加設定なしで利用できるようにしています。 これにより、企業はアプリの境界を超えてリアルタイムに近いデータを同期双方向方式でシームレスに交換できます。 Microsoft では、ユーザーに "1 つの Dynamics 365" エクスペリエンスを提供したいと考えています。 

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
フェーズ 2 リリースでは、プロジェクト、在庫、販売、調達から財務までをカバーするエンドツーエンドのシナリオがサポートされます。 これらの分野で最も重要なエンティティをサポートする、すぐに使えるなシナリオが既定で提供されます。 これらのシナリオは、ユーザーとパートナーによってさらに充実させることができます。 

これらの機能は 10 月のパブリック プレビューでリリースされ、4 月には一般提供される予定です。 対象となるエンティティは後日発表されます。
<!--feature detail end -->

