---
title: C/AL 定義から AL テーブル定義にテーブルを変換する
description: Sync-NAVApp PowerShell コマンドレットを使用することで、パートナーは、データベースのオーバーヘッドを最小限に抑えながら、アップグレード コードを記述する必要なく、C/AL で定義されたデータベース内のすべてのテーブルを AL で定義されたテーブルに変換できます。
author: relnotes
ms.reviewer: edupont
ms.date: 08/02/2019
ms.assetid: 0d941009-b786-e911-a960-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: d83630fd8a603793f53c366dcf1268c7cacd4185
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140680"
---
# <a name="convert-tables-from-cal-definitions-to-al-table-definitions"></a>C/AL 定義から AL テーブル定義にテーブルを変換する
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|-| 2019 年 10 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Windows PowerShell のコマンドレット Sync-NAVApp が更新され、データベースのオーバーヘッドを最小限に抑えながら、アップグレード コードを記述する必要なく、すべての C/AL テーブルを AL テーブルに変換できます。 コマンド `Sync-NAVApp -Mode BaseAppUpgrade` を使用すると、テナント データベースのテーブルの名前が、AL テーブルの命名規則に準拠するように変更されます。 これは、テナントの技術的なアップグレードに対応し、以前のバージョンの基本アプリケーションのテーブル構造が AL アプリ用のテーブル構造に変換されます。
<!--feature detail end -->











