---
title: 顧客データ レイクでの Finance and Operations エンティティ
description: Finance and Operations アプリのエンティティを、独自のデータ レイクで使用できるようになりました。 お客様は、システムがほぼリアルタイムでデータを更新している間に、必要なテーブル エンティティを選択できます。
author: relnotes
ms.reviewer: kfend
ms.date: 01/14/2020
ms.assetid: 5861c499-2fcc-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: milindav
dynamics365pdf: true
ms.openlocfilehash: ea261e4503baa04a17f99910d709c3df382661e4
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986721"
---
# <a name="finance-and-operations-entities-in-a-customers-data-lake"></a>顧客データ レイクでの Finance and Operations エンティティ
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 5 月| 2020 年 6 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
独自のデータ レイクでデータがすぐに利用できるのに、なぜ独自の Azure SQL Database にデータをエクスポートするのでしょうか。 この機能により、顧客は自分のデータベースの持ち込み (BYOD) への依存を減らし、最終的に BYOD の使用を廃止できます。 Azure Data Lake 内のデータ エンティティ定義にアクセスできることにより、お客様はダウンストリーム統合を変更せずに BYOD サービスを廃止できます。

既存のデータ ウェアハウスを運用データベースに統合していて、Microsoft Dynamics AX 2009 および Dynamics AX 2012 からアップグレードするお客様は、テーブル レベル データへのアクセスとの既存の統合への影響を最小限に抑えながら、Finance and Operations アプリにアップグレードできるようになりました。 エンティティ形式の追加により、ビジネス ユーザーは、基になっているテーブルの定義とリレーションシップを理解しなくても、データを簡単に使用できます。

<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Finance and Operations アプリのエンティティを、独自の Azure データ レイクで使用できるようになりました。 お客様は必要なエンティティを選択できます。 システムにより、基になっているテーブルが識別されて、対応するデータがほぼリアルタイムで更新され続けます。 エクスポート ジョブやスケジュールを監視したり、管理したりする必要はなくなりました。 パワー ユーザーと開発者は、さまざまなツールと言語を使用して、データフロー、Spark、SQL など、独自のデータ レイク内のデータにアクセスできます。 Azure Synapse を使用することで、SQL ビュー定義としてエンティティ データにアクセスできます。

<!--feature detail end -->









