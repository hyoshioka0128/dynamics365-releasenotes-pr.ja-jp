---
title: Business Central オンラインでプリンター拡張機能のブロックを解除する新しいイベント
description: 更新プログラム 15.3 では、2 つの新しいイベントが追加され、開発者が Business Central オンラインの直接印刷シナリオ (SetupPrinters と OnDocumentPrintReady) のブロックを解除できるようになります。
author: relnotes
ms.reviewer: jswymer
ms.date: 01/06/2020
ms.assetid: 021aa213-651b-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: f1def5cf4ffc6061857890c7949f5a0b1da22a35
ms.sourcegitcommit: ba5b15c33dc3669937bf5219b1b38995cffb661b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2947659"
---
# <a name="new-events-to-unblock-printer-extensions-in-business-central-online"></a>Business Central オンラインでプリンター拡張機能のブロックを解除する新しいイベント
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|管理者、作成者、またはアナリスト、自動的|2020 年 1 月| 2020 年 2 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
開発者は、これらのイベントを使って、クラウド印刷プロバイダーのサポートを実装する拡張機能を作成できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
開発者は、SetupPrinters を使って、レポート用のプリンター選択ページ (プリンター仮想テーブル内) で使用される可能性のあるプリンターを挿入できます。 各プリンターには、表示名のほか、両面印刷、部数、カラー、用紙トレイなどのプロパティの仕様を指定できます。 用紙トレイでは、[PaperSourceKind](https://docs.microsoft.com/dotnet/api/system.drawing.printing.papersourcekind?view=netframework-4.8)、[PaperKind](https://docs.microsoft.com/dotnet/api/system.drawing.printing.paperkind?view=netframework-4.8)、横向きなどのプロパティを設定できます。

開発者は、OnDocumentPrintReady を使って、印刷されるレポートに反応し、プリンター仮想テーブルの情報を使ってドキュメントをプリンターに送信できます。
<!--feature detail end -->









