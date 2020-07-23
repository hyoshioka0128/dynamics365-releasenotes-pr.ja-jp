---
title: 実行時間の長い操作をレガシ Web クライアントからキャンセルできる
description: 操作とレポートは、完了までに時間がかかりすぎる場合、ブラウザーからキャンセルできます。
author: kotelko
ms.reviewer: sgroespe
ms.date: 04/07/2020
ms.assetid: da142188-f753-ea11-a812-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: a2aadf7f2ed870ff09a95216844c3397009bab2c
ms.sourcegitcommit: 299e7ae952585bc5f8dbe620de3a9d5ef778990a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2020
ms.locfileid: "3548210"
---
# <a name="long-running-operations-can-be-canceled-from-the-legacy-web-client"></a>実行時間の長い操作をレガシ Web クライアントからキャンセルできる


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 2 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
最新のビジネス システムでは、大量のデータを扱う場合でも、実行時間の長い操作 (レポートなど) に関連する柔軟性が不可欠です。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
実行時間の長い操作またはアプリケーション ジョブをキャンセルできるようになりました。 操作全体をキャンセルするオプションを備えた処理済みの行数を示す進行状況ウィンドウが表示されます。 キャンセルされると、システムによって確認を求められ、ジョブのキャンセルが要求されます。

典型的なシナリオは、レポートまたは長時間実行されているバッチ ジョブをキャンセルする機能ですが、この機能は、請求書の一括転記など、他の実行時間の長い操作のキャンセルにまで拡張されます。
<!--feature detail end -->

![レポートのキャンセル](media/cancel-report.png "レポートのキャンセル")
<!-- Picture 1 -->









## <a name="see-also"></a>関連項目

<!--docs start-->
[レポート、バッチ ジョブ、XMLport の操作](https://docs.microsoft.com/dynamics365/business-central/ui-work-report) (ドキュメント)
<!--docs end-->
