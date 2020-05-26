---
title: パートナー向け Application Insights の拡張機能ライフサイクル テレメトリ
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは拡張ライフサイクル イベントに関するテレメトリ (成功または失敗) を Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 04/24/2020
ms.assetid: 2fb3756a-9184-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: c3facbd3b398d1cc9d1aec29abaf3d7ad29ab0a8
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350925"
---
# <a name="extension-lifecycle-telemetry-in-application-insights-for-partners"></a>パートナー向け Application Insights の拡張機能ライフサイクル テレメトリ
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 7 月| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは拡張ライフサイクル イベントに関するテレメトリ (成功または失敗) を Application Insights に送信します。


## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central Server は、拡張ライフサイクル イベントに関するテレメトリ (成功または失敗) を送信します。 操作が失敗した場合、その理由もメッセージに記録されます。 

以下のイベントが発行されます。

- 拡張機能が同期されました (成功)
- 拡張機能が同期されました (失敗)
- 拡張機能がインストールされました (成功)
- 拡張機能がインストールされました (失敗)
- 拡張機能が更新されました (成功)
- 拡張機能が更新されました (失敗)
- 拡張機能がアンインストールされました (成功)
- 拡張機能がアンインストールされました (失敗)
<!--feature detail end -->









