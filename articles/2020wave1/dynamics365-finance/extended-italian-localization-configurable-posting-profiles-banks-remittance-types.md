---
title: '拡張されたローカライズ (イタリア): 銀行や送金タイプ別に構成可能な転記プロファイル'
description: Dynamics 365 Finance が、以前はイタリアのパートナー Cluster Reply によって提供された、拡張されたローカライズ (イタリア) (EXIL) アドインでのみ利用可能であった、イタリア語固有の機能セットが利用できるように拡張されました。
author: relnotes
ms.reviewer: kfend
ms.date: 05/05/2020
ms.assetid: 4e761e5a-f1db-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
dynamics365pdf: true
ms.openlocfilehash: 28d561dbe7c95707b0d2ce1b9c5ae99da8512c0e
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3349338"
---
# <a name="extended-italian-localization-configurable-posting-profiles-for-banks-and-remittance-types"></a>拡張されたローカライズ (イタリア): 銀行や送金タイプ別に構成可能な転記プロファイル
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 5 月 1 日| 2020 年 8 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
イタリアに Dynamics 365 Finance を展開するグローバルおよびローカルの顧客は、拡張されたローカライズ (イタリア) (EXIL) アドインやその他イタリアの市場で利用できる類似の機能のアドインを適用することなく、厳選された競争力のあるイタリア語の規制機能をそのまま利用できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
ドラフトが会社の銀行の 1 つに送金されるときは、一般会計の別の相手勘定を更新する必要があります。 これは、受取手形の場合はユーザーによって選択された銀行や送金タイプに基づいており、支払手形の場合はユーザーによって選択された銀行に基づいています。 

この機能を使用すると、会社の銀行口座ごとに異なる専用の転記プロファイルを作成し、選択した銀行にリンクされた勘定科目にそのトランザクションを転記できます。 銀行口座は仕訳作成時に指定され、その銀行口座は特定の転記プロファイルにリンクされているため、送金のトランザクションはその銀行に接続された主勘定を使用します。
<!--feature detail end -->









