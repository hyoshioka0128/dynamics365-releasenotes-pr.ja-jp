---
title: Lifecycle Services のデータベース移動 RESTful API
description: 診断やデバッグの目的で、データベースが繰り返し更新されるよう設定できます。
author: relnotes
ms.reviewer: sericks
ms.date: 09/04/2019
ms.assetid: a7c806d6-d5c9-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: e18a3c3e64b4c02279fb93420efc7cecba7135ef
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143893"
---
# <a name="database-movement-restful-apis-in-lifecycle-services"></a>Lifecycle Services のデータベース移動 RESTful API
[!include[finance-operations banner](../includes/finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|ユーザー、管理者/作成者/アナリストによる有効化|2019 年 9 月| 2019 年 11 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
平均して、顧客は少なくとも週に 1 回データベース更新のコピー プロセスを使用します。  現在、顧客はセルフサービス アクションを使用して更新をトリガーする必要があります。これは、営業時間中のスタンダード承認テスト環境の可用性に影響を与えます。  RESTful API を使用すると、営業時間外または夜間のビルド プロセスの一部としてアクティビティを実装できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Lifecycle Services (LCS) は RESTful API エンドポイントを公開します。 更新をトリガーするための認証方法と適切な呼び出し方法について説明するドキュメントが提供されます。  この機能は、Azure Logic Apps またはその他の繰り返しエンジンを使用して実行することで、スケジューリングと自動化を行うことができます。
<!--feature detail end -->











