---
title: 仕訳帳別転記済みトランザクション レポートのデータ範囲
description: 仕訳帳別転記済みトランザクション レポートで、レポートの生成時に日付範囲の指定が必須となりました。  既定では、この機能は無効になっています。
author: relnotes
ms.reviewer: roschlom
ms.date: 01/08/2020
ms.assetid: b7cd1474-eb21-ea11-a810-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 1fe10a6d1ec88e2020cc5014e763a6f5e68d7cf1
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986610"
---
# <a name="date-range-for-posted-transactions-by-journals-report"></a>仕訳帳別転記済みトランザクション レポートのデータ範囲
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|2020 年 2 月| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
仕訳帳別転記済みトランザクション レポートで、日付範囲の指定が必須となりました。これにより、レポートの生成が迅速化されます。  日付範囲を指定することで、仕訳帳別転記済みトランザクション レポートで処理されるデータの量が制限されます。 制限がないと、処理されるデータの量が膨大になり、システムのパフォーマンスが大幅に低下する可能性があります。  
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
既定では、この機能は無効になっています。 この変更により、ユーザー インターフェイスに 2 つのフィールドが追加されます。**開始日**フィールドと**終了日**フィールドです (仕訳帳別転記済みトランザクション レポートのレポート ダイアログに表示されます)。
<!--feature detail end -->









