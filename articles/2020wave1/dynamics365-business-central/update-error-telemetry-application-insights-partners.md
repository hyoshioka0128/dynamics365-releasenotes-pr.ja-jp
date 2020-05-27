---
title: パートナー向け Application Insights のエラー テレメトリの更新
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは更新 codeunit で例外によって発生した更新エラーに関するテレメトリを Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 04/24/2020
ms.assetid: ffafb82d-8f84-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: fe0ac03ead20f0e306e86b893fc497697b1fb6cb
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350931"
---
# <a name="update-error-telemetry-in-application-insights-for-partners"></a>パートナー向け Application Insights のエラー テレメトリの更新
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 6 月| 2020 年 6 月|


## <a name="business-value"></a>ビジネス バリュー
環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは更新 codeunit で例外によって発生した更新エラーに関するテレメトリを Application Insights に送信します。

## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central Server は、企業ライフサイクル イベントに関するテレメトリ (成功または失敗) を送信します。 

更新 codeunit の例外によって発生した更新エラーは、以下に関する情報と共に送信されます。

- 例外がスローされた codeunit。
- AL スタック トレース。
- 例外メッセージ。

これによりパートナーは、テナントごとの拡張機能の更新エラーをすばやく修正できます。
<!--feature detail end -->









