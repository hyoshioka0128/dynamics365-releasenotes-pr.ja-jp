---
title: Business Central と Common Data Service の統合
description: Business Central と Common Data Service の統合。
author: relnotes
ms.reviewer: solsen
ms.date: 12/10/2019
ms.assetid: 2591eb8d-52ca-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: henrikwh
dynamics365pdf: true
ms.openlocfilehash: 4db931dc3695882b64ff9243ca75ea19c39d1b87
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986672"
---
# <a name="business-central-integration-with-common-data-service"></a>Business Central と Common Data Service の統合
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|2020 年 2 月| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
新しい Common Data Service オンボーディング エクスペリエンスが提供されます。ユーザーは Common Data Service 環境に接続して、Business Central の会社を Common Data Service の部署に関連付けることができます。 これにより、複数の企業が Common Data Service インスタンスに接続できるようになります。 セットアップの間に、既定の Common Data Service データベースの Common Data Service 接続エンティティが同期されます。 

これにより、Common Data Service 向けの統合を開発している開発者に対する拡張性がサポートされます。  

<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Common Data Service は、Dynamics 365 スイートの中心です。 Common Data Service を使用すると、Common Data Service でデータを利用できるため、ユーザーはビジネスをすべての方向から見ることができます。 データが Common Data Service に取り込まれると、ユーザーは Dynamics 365 ソリューション全体で共有されるデータの一貫したビューを取得できます。 Dynamics 365 Business Central では、他の統合が依存する "Business Central の CDS ベース ソリューション" で提供される既定の Common Data Service データベースのエンティティ セットがサポートされます。 ベース ソリューションには、会社のエンティティを Common Data Service の部署エンティティにマップする機能があります。 

Common Data Service と統合する拡張機能を開発する場合、Business Central 2020 年リリース ウェーブ 1 では拡張性機能が提供され、Common Data Service テーブルと Common Data Service テーブル拡張機能を作成できます。 これにより、任意のカスタム属性を同期できます。 
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。



