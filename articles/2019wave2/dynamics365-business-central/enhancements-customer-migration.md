---
title: 顧客移行ツールの機能強化
description: 顧客移行ツールの新機能により、Dynamics 365 Business Central に移行する顧客に対する移行エクスペリエンスが向上します。
author: relnotes
ms.reviewer: edupont
ms.date: 07/01/2019
ms.assetid: e6e5c71c-9475-e911-a965-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: jenolson
dynamics365pdf: true
ms.openlocfilehash: f4a904d549ee368cfad2e4867c24b3b9dc339b67
ms.sourcegitcommit: e5523d6228bfee2d93355b170028731509aed19a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/02/2019
ms.locfileid: "1722710"
---
# <a name="enhancements-for-customer-migration-tools"></a>顧客移行ツールの機能強化
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|管理者、作成者、またはアナリスト、自動的|| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
ISV が Business Central でソリューションをオンラインにした後の次のステップは、Dynamics 365 Business Central オンプレミス、Dynamics NAV 2018、Dynamics GP 2018 R2、Dynamics SL 2018 CU1 を使用している既存の Dynamics SMB の顧客の作業を簡素化することです。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
既存のデータ レプリケーション ツールは Azure Data Factory に基づいており、移行を完了するために必要なテーブルを追加するように更新されます。 2019 年リリース ウェーブ 2 の更新プログラムでは、Business Central オンプレミスと Dynamics NAV 2018 の移行ツールが最初に提供され、その後で Dynamics GP と Dynamics SL の機能強化が行われます。 セットアップ プロセスは同じままですが、ブランド変更コンポーネントがあり、より合理化された移行をサポートするためにテーブルが追加されます。 移行ツールでは、既定でインストール済み拡張機能からのデータの移行がサポートされるので、Dynamics NAV 2018 または Business Central オンプレミス アプリケーションを拡張機能で拡張している顧客は、追加の作業を行わなくても、それらのデータを Business Central オンラインに持ち込むことができます。

このツールでは現在、ユーザーは Azure Data Factory を使用して SQL Server データベースを Business Central オンラインのテナントに接続し、データを共有することができます。 さらに、2019 年リリース ウェーブ 2 では、移行を完了するために必要な情報のチェックリストが追加されます。
<!--feature detail end -->










