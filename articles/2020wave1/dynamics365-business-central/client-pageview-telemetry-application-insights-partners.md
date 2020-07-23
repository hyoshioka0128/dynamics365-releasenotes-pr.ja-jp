---
title: パートナー向け Application Insights のクライアント ページ ビュー テレメトリ
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、クライアントはページ ビューに関するテレメトリを Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 06/25/2020
ms.assetid: f2e1ac5e-6790-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 4bd2ae1d993956d746ba550f4286d2084868c917
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3524114"
---
# <a name="client-page-view-telemetry-in-application-insights-for-partners"></a>パートナー向け Application Insights のクライアント ページ ビュー テレメトリ
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 7 月| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
これにより、パートナーと顧客管理者はシステムの使用状況を追跡できます。 

また、パートナーはページ ビュー シグナルを使用して、ブラウザーやクライアント設定に起因するパフォーマンスの問題のトラブルシューティングを実行できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
2019 年リリース ウェーブ 2 では、テナント管理者は Azure Application Insights キーを指定して、事前定義されたトレース イベントのロギングを有効にできました。 これまでは、[aka.ms/bctelemetry](https://aka.ms/bctelemetry) に示されている例のように、サーバーからのトレースのみが送信されていました。

この変更により、同じチャネルを通じてクライアント テレメトリを利用できるようにする最初のステップが実現しました。 利用可能になる最初のシグナルはページ ビューです。
<!--feature detail end -->









