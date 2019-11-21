---
title: Lifecycle Services のデータベース移動 RESTful API
description: 診断やデバッグの目的で、データベースが繰り返し更新されるよう設定できます。
author: relnotes
ms.reviewer: sericks
ms.date: 10/03/2019
ms.assetid: a7c806d6-d5c9-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: 9320db9352f62987253eace3380f8fa9a684305a
ms.sourcegitcommit: b5be4afdeec589f0490a82495e8206a2b3aee287
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2668326"
---
# <a name="database-movement-restful-apis-in-lifecycle-services"></a>Lifecycle Services のデータベース移動 RESTful API
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 9 月 30 日| 2019 年 11 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
平均して、顧客は少なくとも週に 1 回データベース更新のコピー プロセスを使用します。  現在、顧客はセルフサービス アクションを使用して更新をトリガーする必要があります。これは、営業時間中のスタンダード承認テスト環境の可用性に影響を与えます。  RESTful API を使用すると、営業時間外または夜間のビルド プロセスの一部としてアクティビティを実装できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Lifecycle Services (LCS) は RESTful API エンドポイントを公開します。 更新をトリガーするための認証方法と適切な呼び出し方法について説明するドキュメントが提供されます。  この機能は、Azure Logic Apps またはその他の繰り返しエンジンを使用して実行することで、スケジューリングと自動化を行うことができます。
<!--feature detail end -->









