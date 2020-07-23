---
title: 顧客の Data Lake Storage Gen2 データ レイク内のテーブル
description: Dynamics 365 Finance and Operations アプリのテーブルが、独自の Azure Data Lake で使用できるようになりました。 顧客は、システムがほぼリアルタイムでデータを更新している間に、必要なテーブルを選択できます。
author: relnotes
ms.reviewer: kfend
ms.date: 06/17/2020
ms.assetid: 0c193363-efc9-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: milindav
dynamics365pdf: true
ms.openlocfilehash: 37d33fbdd0892922d8040c31dd8971fb0bc80546
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3488529"
---
# <a name="tables-in-a-customers-data-lake-storage-gen2-data-lake"></a>顧客の Data Lake Storage Gen2 データ レイク内のテーブル
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 9 月| -|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
独自のデータ レイクでデータがすぐに利用できるときは、独自の Azure SQL Database にデータをエクスポートする必要はありません。 この機能により、お客様は**自分のデータベースの持ち込み (BYOD)** 機能への依存を減らし、最終的に BYOD の使用を廃止できます。 

既存のデータ ウェアハウスを運用データベースに統合している、Dynamics AX 2009 および Dynamics AX 2012 からアップグレードするお客様は、既存の統合への影響を最小限に抑えながら、Finance and Operations アプリにアップグレードできるようになりました。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Finance and Operations アプリのテーブルが、独自の Azure Data Lake で使用できるようになりました。 システムがほぼリアルタイムでデータを更新している間に、必要なテーブルを選択できます。 エクスポート ジョブやスケジュールを監視したり、管理したりする必要はなくなりました。 パワー ユーザーと開発者は、さまざまなツールと言語を使用して、データフロー、Spark、SQL など、独自のデータ レイク内のデータにアクセスできます。

> [!NOTE]
> この機能は、一部の Azure リージョンおよび環境では上記の日付までに利用可能にならない場合があります。 詳細については、ドキュメントを参照してください。
<!--feature detail end -->









