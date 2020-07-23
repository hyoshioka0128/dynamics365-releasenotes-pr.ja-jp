---
title: パートナー向け Application Insights のエラー テレメトリの更新
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは更新 codeunit で例外によって発生した更新エラーに関するテレメトリを Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 05/11/2020
ms.assetid: ffafb82d-8f84-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: e2bd226590b2ebc9ac51a819b40aaeecb7cf3e62
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3381367"
---
# <a name="update-error-telemetry-in-application-insights-for-partners"></a>パートナー向け Application Insights のエラー テレメトリの更新
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 7 月| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは更新 codeunit で例外によって発生した更新エラーに関するテレメトリを Application Insights に送信します。



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
更新 codeunit の例外によって発生した更新エラーは、以下に関する情報と共に送信されます。

- 例外がスローされた codeunit。
- AL スタック トレース。
- 例外メッセージ。

これによりパートナーは、テナントごとの拡張機能の更新エラーをすばやく修正できます。
<!--feature detail end -->









