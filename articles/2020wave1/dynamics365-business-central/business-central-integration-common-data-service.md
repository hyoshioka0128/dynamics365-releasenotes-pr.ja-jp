---
title: Business Central と Common Data Service の統合
description: Business Central と Common Data Service の統合。
author: relnotes
ms.reviewer: solsen
ms.date: 04/20/2020
ms.assetid: 2591eb8d-52ca-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: henrikwh
dynamics365pdf: true
ms.openlocfilehash: 35dfd5bb2e8351aacd4a4a185f7844088f6f7416
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3293986"
---
# <a name="business-central-integration-with-common-data-service"></a>Business Central と Common Data Service の統合


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 2 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
新しい Common Data Service オンボード エクスペリエンスが提供されます。ユーザーは Common Data Service 環境に接続して、Business Central の会社を Common Data Service の部署に関連付けることができます。 これにより、複数の企業が Common Data Service 環境に接続できるようになります。 セットアップの間に、既定の Common Data Service データベースの Common Data Service 接続エンティティが同期されます。 

Common Data Service 向けの Business Central 統合を開発している開発者に対する拡張性がサポートされます。 拡張性のサポートにより、Business Central Extensions を記述して、フィールドとテーブルを同期プロセスに追加し、既存のテーブルも拡張できます。 さらに、変換を作成し、値を変換およびマッピングできます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Common Data Service は、Dynamics 365 スイートの中心です。 ユーザーはビジネスをすべての方向から見ることができます。 Common Data Service 内のデータにより、ユーザーとソリューションに Dynamics 365 ソリューション全体で共有されるデータの一貫したビューが与えられます。 Dynamics 365 Business Central では Common Data Service の既定のデータベース内のエンティティのセットがサポートされます。 Business Central Common Data Service のベース ソリューションは、他の統合が依存するものです。 ベース ソリューションにより、ユーザーは会社のエンティティを Common Data Service の部署エンティティにマップできます。 

Common Data Service と統合する拡張機能を開発する場合、2020 年リリース ウェーブ 1 では拡張性機能が提供され、そこで Common Data Service テーブルへのプロキシを Business Central に作成でき、これらは拡張可能になります。 これにより、カスタム属性を同期したり、同期プロセスに追加のテーブルを追加したりできます。 同期プロセスでのフィールド値のマッピングと変換のサポートが利用可能になりました。 

CRM Sales 統合の新規インストールは、新しい Business Central Common Data Service ベース ソリューションの上にインストールされ、このソリューションに前述の機能を提供します。
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a>フィードバック
Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。 フォーラム (https://aka.ms/bcideas) をご利用ください。




## <a name="see-also"></a>関連項目

<!--docs start-->
[Common Data Service との統合 ](https://docs.microsoft.com/dynamics365/business-central/admin-common-data-service) (ドキュメント)
<!--docs end-->
