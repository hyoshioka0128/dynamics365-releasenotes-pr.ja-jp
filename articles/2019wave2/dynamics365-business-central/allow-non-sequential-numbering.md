---
title: 連続しない番号を許容する
description: 事前定義された番号シリーズからレコードに割り当てられる番号のギャップを許容できるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 08/29/2019
ms.assetid: d07f6b3c-fec7-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: bnielse
dynamics365pdf: true
ms.openlocfilehash: 3d4e77d8d82c9b37504f723c910fff23842a8af0
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140746"
---
# <a name="allow-non-sequential-numbering"></a>連続しない番号を許容する
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|ユーザー、自動的|-| 2019 年 10 月|


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

![番号付けのギャップを許容する](media/allow_gaps_in_no_series_lines.png "番号付けのギャップを許容する")

<!--feature detail end -->





