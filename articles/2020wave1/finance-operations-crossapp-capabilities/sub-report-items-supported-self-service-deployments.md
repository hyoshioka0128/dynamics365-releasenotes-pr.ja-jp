---
title: セルフサービス展開でサポートされているサブレポート項目
description: セルフサービス展開でホストされているアプリケーション ソリューションで、サブレポート項目がサポートされるようになりました。
author: relnotes
ms.reviewer: kfend
ms.date: 05/21/2020
ms.assetid: 877a8a73-f69a-ea11-a811-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: tjvass
dynamics365pdf: true
ms.openlocfilehash: 18f4f5935913a693773cb797d9960357a4ddbcba
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3416426"
---
# <a name="subreport-items-supported-in-self-service-deployments"></a>セルフサービス展開でサポートされているサブレポート項目
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
サブレポート項目は、ドキュメントにヘッダーと本文の両方を含む、顧客支払提案レポートなどのソリューションにとって効果的なツールです。サブレポートを使用すると、アプリケーション ソリューションでは、レポート パラメーターの評価に応じて、実行時にドキュメント ヘッダーを効率的に除外または追加できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
パートナーのフィードバックに応えて、セルフサービス展開にサブレポート項目を含むアプリケーション ソリューションのサポートを追加しました。  [サブレポート](https://docs.microsoft.com/sql/reporting-services/report-design/subreports-report-builder-and-ssrs?view=sql-server-ver15)項目を使用すると、設計者はレポート全体を別のレポートの本体に埋め込むことができます。通常、これらは関連するデータ セットに基づくセクションを含むアプリケーション ソリューションで見られます。

> [!IMPORTANT]
> アプリケーション ソリューションの場合、Tablix コントロール内でサブレポート項目を使用することは推奨**されません**。Tablix コントロール内にサブレポート項目を含むレポート デザイン定義は推奨されておらず、サービスでランタイム エラーが発生する可能性があります。
<!--feature detail end -->









