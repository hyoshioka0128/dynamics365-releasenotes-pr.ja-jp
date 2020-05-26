---
title: 読み取りスケールアウト
description: Business Central Server では、Azure SQL Database や SQL Server (使用可能な場合) で読み取り専用のレプリカを使用できます。
author: relnotes
ms.reviewer: jswymer
ms.date: 04/15/2020
ms.assetid: eda564e4-e71b-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 9d53467c70e28a642a6c381f29e7a426357837b8
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273711"
---
# <a name="read-scale-out"></a>読み取りスケールアウト


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
顧客は、データベースの読み取り専用レプリカで選択したレポート、クエリ、Web サービスの呼び出しを実行することを選択できます。 これにより、分析ワークロードがプライマリ データベースに影響を与えることはありません。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central のアーティファクト (レポート、API ページ、クエリ) で、データベースの読み取り専用レプリカにアクセスできるようになりました。 

ページ、レポート、クエリの各オブジェクトには、ReadOnly または ReadWrite の値を取ることができる "DataAccessIntent" という新しいプロパティがあります。 このプロパティは、可能であればセカンダリ レプリカに接続するサーバーのヒントとして機能します。 レプリカに対してワークロードが実行されると、挿入/削除/変更操作を実行できないため、ReadOnly オブジェクトに新しい検証が導入されます。 これらの操作はいずれも実行時に例外をスローします (将来、新しいコンパイル時検証が追加される予定です)。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[パフォーマンス向上のための読み取りスケールアウトの使用](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/database-read-scale-out-overview) (ドキュメント)
<!--docs end-->
