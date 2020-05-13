---
title: Lifecycle Services のデータベース移動 RESTful API
description: 診断やデバッグの目的で、データベースが繰り返し更新されるよう設定できます。
author: relnotes
ms.reviewer: sericks
ms.date: 02/06/2020
ms.assetid: a7c806d6-d5c9-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: d394fcc5b7b7c1517304e266909cb0db9c4d4965
ms.sourcegitcommit: 2928661abcc468748ffc7c33516ebc8e3cd5d653
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/04/2020
ms.locfileid: "3098451"
---
# <a name="database-movement-restful-apis-in-lifecycle-services"></a>Lifecycle Services のデータベース移動 RESTful API


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 9 月 30 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
平均して、顧客は少なくとも週に 1 回データベース更新のコピー プロセスを使用します。  現在、顧客はセルフサービス アクションを使用して更新をトリガーする必要があります。これは、営業時間中のスタンダード承認テスト環境の可用性に影響を与えます。  RESTful API を使用すると、営業時間外または夜間のビルド プロセスの一部としてアクティビティを実装できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Lifecycle Services (LCS) は RESTful API エンドポイントを公開します。 更新をトリガーするための認証方法と適切な呼び出し方法について説明するドキュメントが提供されます。  Azure Logic Apps またはその他の繰り返しエンジンを使用してこの機能を実行すると、スケジューリングと自動化を行うことができます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[データベース移動 API ](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/database/dbmovement-operations#database-movement-api) (ドキュメント)
