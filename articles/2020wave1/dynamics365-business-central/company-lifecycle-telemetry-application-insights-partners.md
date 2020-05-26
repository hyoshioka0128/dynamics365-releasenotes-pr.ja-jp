---
title: パートナー向け Application Insights の企業ライフサイクル テレメトリ
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは企業ライフサイクル イベントに関するテレメトリ (成功または失敗) を Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 04/24/2020
ms.assetid: 271a38ba-7f84-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 15da6e34461c35790ebe7ec24b414298768cceea
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294941"
---
# <a name="company-lifecycle-telemetry-in-application-insights-for-partners"></a>パートナー向け Application Insights の企業ライフサイクル テレメトリ
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 6 月| 2020 年 6 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Business Central Server は、企業ライフサイクル イベントに関するテレメトリ (成功または失敗) を送信します。 

試行が失敗した場合、その理由もメッセージに記録されます。 

以下のイベントが発行されます。

- 会社の作成 (成功)  
- 会社の作成 (失敗)  
- 会社のコピー (成功)  
- 会社のコピー (失敗)  
- 会社のコピー (キャンセル)  
- 会社の削除 (成功)  
- 会社の削除 (失敗)  
<!--feature detail end -->









