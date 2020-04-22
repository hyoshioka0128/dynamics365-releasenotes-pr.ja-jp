---
title: 読み取りスケールアウト
description: Business Central Server では、Azure SQL Database や SQL Server (使用可能な場合) で読み取り専用のレプリカを使用できます。
author: relnotes
ms.reviewer: jswymer
ms.date: 03/25/2020
ms.assetid: eda564e4-e71b-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 94ec29cf1ada33e70906b7d1604802f1f761c29d
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232717"
---
# <a name="read-scale-out"></a>読み取りスケールアウト
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 4 月| 2020 年 4 月|


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

