---
title: 元帳の会計カレンダーを変更するときに「期間残高の再計算」が必要
description: この機能では、**元帳**ページで会計カレンダーを変更した後、会計期間を再計算する必要があります。
author: relnotes
ms.reviewer: roschlom
ms.date: 01/30/2020
ms.assetid: ba202472-ce42-ea11-a812-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 831a8287bc47f3347074f8a25f7e1e2c32e4a88f
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3032589"
---
# <a name="require-recalculate-ledger-periods-when-changing-fiscal-calendar-on-ledger"></a>元帳の会計カレンダーを変更するときに「期間残高の再計算」が必要
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|-| 2020 年 5 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能では、**元帳**ページで会計カレンダーを変更した後、会計期間を再計算する必要があります。 この要件により、トランザクションが新しいカレンダーの正しい期間に割り当てられるようになります。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
元帳に割り当てられた会計カレンダーはいつでも変更できます。 カレンダーを変更するときは、元帳期間の再計算プロセスも実行する必要がありますが、プロセスをすぐに実行する必要はありません。 ただし、期間を後で再計算した場合、またはプロセスをまったく実行しない場合は、レポートまたは年度の決算時に問題が発生する可能性があります。 この機能を有効にした場合は、**元帳**ページで会計カレンダーを変更した後、すぐに会計期間を再計算する必要があります。
<!--feature detail end -->









