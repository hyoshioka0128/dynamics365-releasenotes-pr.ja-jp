---
title: 通貨換算を使用する場合の財務レポートの利益剰余金計算の機能強化
description: ''
author: relnotes
ms.reviewer: roschlom
ms.date: 09/13/2019
ms.assetid: 7b036487-2abe-e911-a963-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: dcca5a85fe136c6ea054b86063132ca56e6e0949
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2142858"
---
# <a name="retained-earnings-calculation-enhancements-for-financial-reporting-when-using-currency-translation"></a>通貨換算を使用する場合の財務レポートの利益剰余金計算の機能強化
[!include[finance-operations banner](../includes/finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 9 月 3 日| 2020 年 1 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能は、通貨換算を使用して所得が複数年にわたって計算される場合に、利益剰余金の計算の精度を向上させます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能を有効にすると、**為替換算タイプ**が**取引日付**に設定された利益剰余金勘定科目では、年とレートだけでなく、履歴全体のレートと残高を使用して、勘定科目の換算残高が計算されます。
<!--feature detail end -->

