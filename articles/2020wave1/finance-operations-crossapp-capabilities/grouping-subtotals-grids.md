---
title: グリッドの小計でグループ化
description: 1 つ以上の列に基づいてデータをグループ化し、組織化された方法でデータを表示して、Finance and Operations Web クライアントで簡単なアドホック データ分析を実行します。
author: relnotes
ms.reviewer: sericks
ms.date: 04/07/2020
ms.assetid: bc751b0a-83ca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: bf607e2b4970f6e23886167433642ff1329c179d
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3256192"
---
# <a name="grouping-with-subtotals-in-grids"></a>グリッドの小計でグループ化


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 3 日| -|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
ユーザーは、しばしばデータのアドホック分析を実行する必要があります。 これは現在、データを Microsoft Excel にエクスポートしてからピボットテーブルを使用して行うことができます。 Web クライアント内でのデータのグループ化を有効にし、以前に追加されている**合計**機能を拡張してグループ レベルで小計ができるようにすることで、ユーザーはこれらの分析情報を Finance and Operations アプリから直接取得できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能は、新しいグリッド コントロールでのみ使用できます。 リリース ウェーブを通して拡張され、最終的に、ユーザーは最大 5 つの列の値に基づいてグリッド内のデータをグループ化できるようになります。 ユーザーは、必要に応じてグループを展開または折りたたむことができます。これはデータの要約ビューを作成するのに役立ちます。 小計もグループ ヘッダー レベルに表示されます。 

**10.0.9 / Platform update 33** 単一の列に基づいてデータをグループ化します。 これは、保存されたビュー機能が有効になっているときは、個人用設定を使用して保存できます。 グループを展開または縮小する機能は、将来の更新で計画されています。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[グリッド機能](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/grid-capabilities) (ドキュメント)
<!--docs end-->
