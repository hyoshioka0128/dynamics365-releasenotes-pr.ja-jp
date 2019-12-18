---
title: 連続しない番号を許容する
description: 事前定義された番号シリーズからレコードに割り当てられる番号のギャップを許容できるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 11/15/2019
ms.assetid: d07f6b3c-fec7-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: bnielse
dynamics365pdf: true
ms.openlocfilehash: 0a9b189a14dc912436f8709732be56b9ead008a4
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892297"
---
# <a name="allow-non-sequential-numbering"></a>連続しない番号を許容する


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
顧客カードや倉庫内での活動など、多くのタイプのレコードでは、割り当てられた番号が順番どおりであることは法的要件ではありません。 システムのパフォーマンスを改善し、ユーザーがレコードを柔軟に削除できるように、連続しない番号が割り当てられることを許容するように番号シリーズを設定できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
番号シリーズの**番号シリーズ明細行**ページでは、**番号のギャップを許可する**チェック ボックスを選択すると、番号の自動または手動割り当ての際に連続しない番号が割り当てられることを許容します。 これにより、システムが番号シリーズから新しい番号を作成して使用する間、**番号シリーズ明細行**テーブルがロックされているときに発生する、潜在的なパフォーマンスの問題を回避できます。 さらに、使われなくなった銀行口座のカードなどのレコードをユーザーが柔軟に削除できるようになるため、レコードの番号付きリストにギャップが生じます。 

> [!NOTE]
> 特定の番号シリーズでギャップを許容する場合は、まず監査人または会計マネージャーに相談して、その国または地域の法的要件を遵守していることを確認する必要があります。

連続しない番号の割り当てには、SQL サーバーの優先順位ロジックを活用します。 詳細については、「[ロックフリー番号シリーズ](lock-free-number-series.md)」を参照してください。

![番号付けのギャップを許可する](media/allow_gaps_in_no_series_lines.png "番号付けのギャップを許可する")
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[番号付けのギャップを許可する](https://docs.microsoft.com/dynamics365/business-central/ui-create-number-series#gaps-in-number-series) (ドキュメント)
