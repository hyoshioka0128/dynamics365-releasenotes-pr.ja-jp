---
title: 顧客移行ツールの機能強化
description: 顧客移行ツールの新機能により、Dynamics 365 Business Central に移行する顧客に対する移行エクスペリエンスが向上します。
author: relnotes
ms.reviewer: edupont
ms.date: 08/20/2019
ms.assetid: e6e5c71c-9475-e911-a965-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: jenolson
dynamics365pdf: true
ms.openlocfilehash: 59ea07ae67e96b761557d23c164e84c1d20e89ec
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140647"
---
# <a name="enhancements-for-customer-migration-tools"></a>顧客移行ツールの機能強化
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
ISV が自社ソリューションを Business Central オンラインに取り込めるようにした後の次のステップは、Dynamics 365 Business Central オンプレミス、Dynamics GP 2018 R2、Dynamics SL 2018 CU1 を使用している既存の Dynamics SMB の顧客の作業を簡素化することです。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
2019 年リリース ウェーブ 2 の更新プログラムでは、Business Central オンプレミスの移行ツールが最初に提供され、その後で Dynamics GP と Dynamics SL の機能強化が行われます。 既存のデータ複製ツールは、Azure Data Factory をベースとしています。 この更新プログラムにより、移行を完了するために必要なテーブルが追加されます。 セットアップ プロセスは同じままですが、商標が変更されるコンポーネントがあり、より合理化された移行をサポートするためにテーブルが追加されます。 移行ツールでは、既定でインストール済み拡張機能からのデータの移行に対応するため、Business Central オンプレミス アプリケーションを拡張機能でカスタマイズしている顧客は、追加の作業を行わなくても、それらのデータを Business Central オンラインに持ち込むことができます。

この更新プログラムにより、管理者は Azure Data Factory を使用して SQL Server データベースを Business Central オンラインのテナントに接続し、データを共有することができます。 さらに、2019 年リリース ウェーブ 2 では、移行を完了するために必要な情報のチェックリストが追加されます。
<!--feature detail end -->











