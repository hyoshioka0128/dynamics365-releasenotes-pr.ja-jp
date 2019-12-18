---
title: C/AL 定義から AL テーブル定義にテーブルを変換する
description: Sync-NAVApp PowerShell コマンドレットを使用することで、パートナーは、データベースのオーバーヘッドを最小限に抑えながら、アップグレード コードを記述する必要なく、C/AL で定義されたデータベース内のすべてのテーブルを AL で定義されたテーブルに変換できます。
author: relnotes
ms.reviewer: edupont
ms.date: 11/15/2019
ms.assetid: 0d941009-b786-e911-a960-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: ee6f230a84a63ddce8d1e7a3521398704ded3753
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892231"
---
# <a name="convert-tables-from-cal-definitions-to-al-table-definitions"></a>C/AL 定義から AL テーブル定義にテーブルを変換する


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Windows PowerShell のコマンドレット Sync-NAVApp が更新され、データベースのオーバーヘッドを最小限に抑えながら、アップグレード コードを記述する必要なく、すべての C/AL テーブルを AL テーブルに変換できます。 コマンド `Sync-NAVApp -Mode Sync` を使用すると、テナント データベースのテーブルの名前が、AL テーブルの命名規則に準拠するように変更されます。 これは、テナントの技術的なアップグレードに対応し、以前のバージョンの基本アプリケーションのテーブル構造が AL アプリ用のテーブル構造に変換されます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[Sync-NAVApp](https://docs.microsoft.com/powershell/module/microsoft.dynamics.nav.apps.management/sync-navapp?view=businesscentral-ps-15) (ドキュメント)
