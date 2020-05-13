---
title: Business Central online でプリンター拡張機能のブロックを解除する新しいイベント
description: 更新プログラム 15.3 では、2 つの新しいイベントが追加され、開発者が Business Central online の直接印刷シナリオ (SetupPrinters と OnDocumentPrintReady) のブロックを解除できるようになります。
author: relnotes
ms.reviewer: jswymer
ms.date: 03/02/2020
ms.assetid: 021aa213-651b-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 47958926fd2e54aedb89edf2885f0b7e7cb8270a
ms.sourcegitcommit: db53421debc891ea407773d0e9b39feb7a01fef3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/09/2020
ms.locfileid: "3110943"
---
# <a name="new-events-to-unblock-printer-extensions-in-business-central-online"></a>Business Central online でプリンター拡張機能のブロックを解除する新しいイベント


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 26 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 3 月 2 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
開発者は、これらのイベントを使って、クラウド印刷プロバイダーのサポートを実装する拡張機能を作成できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
開発者は、SetupPrinters を使って、レポート用のプリンター選択ページ (プリンター仮想テーブル内) で使用される可能性のあるプリンターを挿入できます。 各プリンターには、表示名のほか、両面印刷、部数、カラー、用紙トレイなどのプロパティの仕様を指定できます。 用紙トレイでは、[PaperSourceKind](https://docs.microsoft.com/dotnet/api/system.drawing.printing.papersourcekind?view=netframework-4.8)、[PaperKind](https://docs.microsoft.com/dotnet/api/system.drawing.printing.paperkind?view=netframework-4.8)、横向きなどのプロパティを設定できます。

開発者は、OnDocumentPrintReady を使って、印刷されるレポートに反応し、プリンター仮想テーブルの情報を使ってドキュメントをプリンターに送信できます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[Business Central でのプリンター拡張機能の開発](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-reports-printing) (ドキュメント)
