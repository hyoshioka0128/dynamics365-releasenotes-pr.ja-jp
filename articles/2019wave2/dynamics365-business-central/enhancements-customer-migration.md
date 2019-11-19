---
title: 顧客移行ツールの機能強化
description: 顧客移行ツールの新機能により、Dynamics 365 Business Central に移行する顧客に対する移行エクスペリエンスが向上します。
author: relnotes
ms.reviewer: edupont
ms.date: 10/17/2019
ms.assetid: e6e5c71c-9475-e911-a965-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: jenolson
dynamics365pdf: true
ms.openlocfilehash: 0d5639ee37411aa948c627d223e1b730cd901a65
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2667072"
---
# <a name="enhancements-for-customer-migration-tools"></a>顧客移行ツールの機能強化


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
ISV が自社ソリューションを Business Central オンラインに取り込めるようにした後の次のステップは、Dynamics 365 Business Central オンプレミス、Dynamics GP 2018 R2、Dynamics SL 2018 CU1 を使用している既存の Dynamics SMB の顧客の作業を簡素化することです。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
2019 年リリース ウェーブ 2 の更新プログラムでは、Business Central オンプレミスの移行ツールが最初に提供され、その後で Dynamics GP と Dynamics SL の機能強化が行われます。 既存のデータ複製ツールは、Azure Data Factory をベースとしています。 この更新プログラムにより、移行を完了するために必要なテーブルが追加されます。 セットアップ プロセスは同じままですが、商標が変更されるコンポーネントがあり、より合理化された移行をサポートするためにテーブルが追加されます。 移行ツールでは、既定でインストール済み拡張機能からのデータの移行に対応するため、Business Central オンプレミス アプリケーションを拡張機能でカスタマイズしている顧客は、追加の作業を行わなくても、それらのデータを Business Central オンラインに持ち込むことができます。

この更新プログラムにより、管理者は Azure Data Factory を使用して SQL Server データベースを Business Central オンラインのテナントに接続し、データを共有することができます。 さらに、2019 年リリース ウェーブ 2 では、移行を完了するために必要な情報のチェックリストが追加されます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[Dynamics 365 Business Central を使用してオンプレミスからインテリジェント クラウドに接続する](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/about-intelligent-edge) (ドキュメント)
