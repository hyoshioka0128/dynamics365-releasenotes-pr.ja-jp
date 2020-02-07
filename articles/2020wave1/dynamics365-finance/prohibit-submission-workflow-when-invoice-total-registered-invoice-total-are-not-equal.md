---
title: 請求書の合計と登録済みの請求書の合計が等しくない場合、ワークフローへの送信を禁止します
description: この機能は、仕入先請求書をワークフロー プロセスに送信する前にエラーを特定して修正するのに役立ちます。
author: relnotes
ms.reviewer: roschlom
ms.date: 01/08/2020
ms.assetid: c2003594-f11e-ea11-a810-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: f4361ea545f1ef7b828b4352bbe9897053112d7e
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986601"
---
# <a name="prohibit-submission-to-workflow-when-the-invoice-total-and-registered-invoice-total-are-not-equal"></a>請求書の合計と登録済みの請求書の合計が等しくない場合、ワークフローへの送信を禁止します
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 2 月| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
請求書がワークフローに送信される前に問題を見つけることは、転記が中止されたり、仕入先請求書をワークフローに再送信する必要が生じたりするエラーを防ぐのに役立ち、結果的に送信者と承認者の時間を節約します。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能を使用すると、請求書の合計と登録済みの請求書の合計が等しくない場合に、仕入先請求書がワークフロー プロセスに送信されないようにすることができます。 代わりに、請求書の送信者は、合計が一致しないという通知を受け取り、ワークフローに送信する前に修正するよう求められます。  
<!--feature detail end -->









