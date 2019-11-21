---
title: 店舗および宛先に基づく外税の顧客控除を計算する
description: この機能を使用すると、小売業者は店舗ベースの税を使用しながら、顧客の控除が適用されるかどうかも確認できます。 これは外税価格のシナリオのみを対象としたものです。この機能での税込み価格のサポートは、現在計画中です。
author: relnotes
ms.reviewer: josaw
ms.date: 10/15/2019
ms.assetid: 14fe4af2-19e2-e911-a814-000d3a4f1244
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: b62963f90aaa11f8d521949ceb077cc1331a1255
ms.sourcegitcommit: f10ac8bac0311c919c83ee52b7f5216aed81c3f8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/31/2019
ms.locfileid: "2692198"
---
# <a name="calculate-customer-exemptions-for-store--and-destination-based-exclusive-taxes"></a>店舗および宛先に基づく外税の顧客控除を計算する
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 10 月| 2020 年 1 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
特定の業界では、小売業者が企業間現金売りトランザクションを行うことが一般的です。 そのような場合、特定の顧客が特定の税金を免除されることがありますが、免除されないその他の税については、支払う必要があります。 この機能では、このようなシナリオにそのまま使用できる機能が用意されているので、回避策を講じる必要がなくなります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
店舗で "店舗ベース" や "宛先ベース" の税が使用されている場合、税は常に、販売される商品と、その商品を顧客が入手する店舗や場所での税に基づいて計算されます。 これらの設定では、顧客が特定の税を免除されるシナリオが考慮されません。 

今回この機能が追加されたことで、**顧客控除を計算する** というパラメーターが、小売店レベルで導入されるようになりました。 このパラメーターを有効にすると、トランザクションに適用される税が、顧客の構成した消費税と照合されます。 現在のトランザクションに適用される税が顧客レベルで**控除**対象としてマークされている場合、それらの税はそのトランザクションには適用されません。
<!--feature detail end -->









