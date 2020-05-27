---
title: エージェント マクロの強化
description: エージェント マクロの強化
author: relnotes
ms.reviewer: nenellim
ms.date: 04/09/2020
ms.assetid: cf8ed4f6-7c58-ea11-a811-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: srikot
dynamics365pdf: true
ms.openlocfilehash: 7ffff1df766c1fd14c5633d490c2beca37b29c49
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3272600"
---
# <a name="agent-macro-enhancements"></a>エージェント マクロの強化


| 有効対象    |  パブリック プレビュー | 早期アクセス | 一般提供 | 
| ---------- | :----------: |:----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|-|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
マクロは、一連の一般的で反復的なタスクを自動化することでエージェントの生産性を高め、大規模なチーム全体でこれらのタスクの一貫性と品質を確保するのに役立ちます。 このマクロの強化により、自動化プロセスにさらに複雑なロジックを適用して、エージェントの負担を軽減し、最適なサービス エクスペリエンスの一貫性を高め、顧客のサポートにかかる時間を短縮できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能を使用すると、管理者はマクロに決定分岐を作成して、コンテキスト変数をマクロ ステップとして評価するための論理条件を追加できます。 その後、ユーザーがマクロを実行すると、論理条件が評価され、マクロで定義されている適切なステップが実行されます。 条件の例を次にいくつか示します。

-   会話にケースが添付されている場合は、既存のケース フォームを開きます。それ以外の場合は、新しいケース フォームを開きます。
-   顧客の優先度が高い場合は、"高優先度のメール テンプレート" を使用します。それ以外の場合は、"通常の確認応答テンプレート" を使用します。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[マクロでタスクを自動化](https://docs.microsoft.com/dynamics365/omnichannel/administrator/macros) (ドキュメント)
<!--docs end-->
