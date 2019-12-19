---
title: 二重通貨連結のためのオンライン連結の 連結勘定の選択元 コントロール
description: ''
author: relnotes
ms.reviewer: roschlom
ms.date: 11/15/2019
ms.assetid: 45ee7f88-b0a9-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: a071b23cbb11478e1ba26b446e559ff96b14d490
ms.sourcegitcommit: cf8b2ba74d2b553c2a721942221c285ffcf184c5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892771"
---
# <a name="select-consolidation-amount-from-control-on-the-consolidate-online-for-dual-currency-consolidation"></a>二重通貨連結のためのオンライン連結の [連結勘定の選択元] コントロール


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 5 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能を使用すると、連結会社の取引通貨として使用される通貨 (会計通貨またはレポート通貨) を制御でき、通貨が同じ場合は、ソースの会社から連結会社に金額を自動的にコピーできます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
- **オンライン連結フォームへの [連結勘定の選択元] コントロールの追加。**

  この機能が有効になっている場合、ユーザーはソース会社の会計通貨とレポート通貨のどちらを連結会社の取引通貨として使用するかを選択できます。

- **通貨が同じ場合は、ソースの会社から連結会社に金額を直接コピー。**

  この機能が有効になっている場合、ソース会社の会計通貨またはレポート通貨の金額は、どちらかの通貨が同じ場合には、連結会社の会計通貨またはレポート通貨の金額に直接コピーされます。 どちらの通貨も同じでない場合、連結会社の会計通貨およびレポート通貨の金額は為替レートを使用して計算されます。
<!--feature detail end -->










