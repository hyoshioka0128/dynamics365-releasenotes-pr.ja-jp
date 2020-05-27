---
title: 顧客データ レイクでの Finance and Operations エンティティ
description: Finance and Operations アプリのエンティティを、独自のデータ レイクで使用できるようになりました。 お客様は、システムがほぼリアルタイムでデータを更新している間に、必要なテーブル エンティティを選択できます。
author: relnotes
ms.reviewer: kfend
ms.date: 04/14/2020
ms.assetid: 5861c499-2fcc-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: milindav
dynamics365pdf: true
ms.openlocfilehash: 38101355b4c2ac757f63d12eed27188d7cf23e8b
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3293392"
---
# <a name="finance-and-operations-entities-in-a-customers-data-lake"></a>顧客データ レイクでの Finance and Operations エンティティ
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 8 月| 2020 年 9 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能により、お客様は自分のデータベースの持ち込み (BYOD) への依存を減らし、最終的に BYOD の使用を廃止できます。 Azure Data Lake 内のデータ エンティティ定義へのアクセスにより、お客様はダウンストリーム統合を変更せずに BYOD サービスを廃止できます。

既存のデータ ウェアハウスを運用データベースに統合していて、Microsoft Dynamics AX 2009 および Dynamics AX 2012 からアップグレードするお客様は、テーブル レベル データへのアクセスとの既存の統合への影響を最小限に抑えながら、Finance and Operations アプリにアップグレードできるようになりました。 エンティティ形式の追加により、ビジネス ユーザーは、基になっているテーブルの定義とリレーションシップを理解しなくても、データを簡単に使用できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Dynamics 365 Finance and Operations アプリ内のエンティティは、独自の Azure データ レイク内で利用できるようになり、必要なエンティティを選択できるようになりました。 システムにより、基になっているテーブルが識別されて、対応するデータがほぼリアルタイムで更新され続けます。 データ レイクで利用可能なエンティティ定義メタデータを使用することにより、お客様は Azure Synapse を使用してエンティティ シェイプのクエリを実行できます。 オプションで、お客様はデータ レイク内でエンティティをステージングすることもできます。

エクスポート ジョブやスケジュールを監視したり、管理したりする必要はなくなりました。 パワー ユーザーと開発者は、さまざまなツールと言語を使用して、データフロー、Spark、SQL など、独自のデータ レイク内のデータにアクセスできます。 Azure Synapse を使用することで、SQL ビュー定義としてエンティティ データにアクセスできます。

> [!NOTE]
> この機能は、一部の Azure リージョンおよび環境では上記の日付までに利用可能にならない場合があります。
<!--feature detail end -->









