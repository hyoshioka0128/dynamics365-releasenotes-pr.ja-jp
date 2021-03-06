---
title: 仕訳帳別転記済みトランザクション レポートのデータ範囲
description: 仕訳帳別転記済みトランザクション レポートで、レポートの生成時に日付範囲の指定が必須となりました。 既定では、この機能は無効になっています。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/06/2020
ms.assetid: b7cd1474-eb21-ea11-a810-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 0f2f8ad824cb8af83774e5baf80d88cb705ac0e8
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255488"
---
# <a name="date-range-for-posted-transactions-by-journals-report"></a>仕訳帳別転記済みトランザクション レポートのデータ範囲


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 3 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
仕訳帳別転記済みトランザクション レポートで、日付範囲の指定が必須となりました。これにより、レポートの生成が迅速化されます。 日付範囲を指定することで、仕訳帳別転記済みトランザクション レポートで処理されるデータの量が制限されます。 制限がないと、処理されるデータの量が膨大になり、システムのパフォーマンスが大幅に低下する可能性があります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
既定では、この機能は無効になっています。 この変更により、ユーザー インターフェイスに 2 つのフィールドが追加されます。**開始日**フィールドと**終了日**フィールドです (仕訳帳別転記済みトランザクション レポートのレポート ダイアログに表示されます)。 一般会計での仕訳帳の処理の詳細については、「[一般仕訳帳の処理](https://docs.microsoft.com/dynamics365/finance/general-ledger/general-journal-processing)」を参照してください。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[一般仕訳帳の処理](https://docs.microsoft.com/dynamics365/finance/general-ledger/general-journal-processing) (ドキュメント)
<!--docs end-->
