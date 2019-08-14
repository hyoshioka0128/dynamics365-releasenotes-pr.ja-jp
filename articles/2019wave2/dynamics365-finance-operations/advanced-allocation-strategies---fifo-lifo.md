---
title: 高度な割り当て戦略 - FIFO と LIFO
description: 2 つの新しいピッキング場所ディレクティブ戦略として、FIFO (先入れ先出し) と LIFO (後入れ先出し) が導入されました。 これらは場所とライセンス プレートのエイジング日付フィールドと連携して機能し、在庫が最初に倉庫に入ったときを追跡します。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: 8262278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 8b5b7d29889ca15f10483cf5558a816f525b2c29
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854154"
---
# <a name="advanced-allocation-strategies---fifo-and-lifo"></a>高度な割り当て戦略 - FIFO と LIFO
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 8 月| 2019 年 10 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
2 つの新しいピッキング場所ディレクティブ戦略として、FIFO (先入れ先出し) と LIFO (後入れ先出し) が導入されました。 これらは場所とライセンス プレートのエイジング日付フィールドと連携して機能し、在庫が最初に倉庫に入ったときを追跡します。 これらの戦略をバッチと非バッチの両方の追跡対象品目に使用し、在庫が倉庫に入った時期に基づいて顧客に品目を出荷できます。 これは、有効期限がソートに使用できない非バッチの追跡対象在庫に対して特に便利です。 在庫が倉庫内に最初に入庫または作成されたときに、現在の日付がエイジング日付として入力されてライセンス プレートが更新されます。 その後、この日付は、戦略で倉庫内の最も古い在庫または最も新しい在庫を特定するために使用されます。 在庫がライセンス プレートによる追跡対象でない場所に移動された場合、その場所自体がエイジング日付を反映して更新され、戦略でも使用されます。
<!--feature detail end -->











