---
title: 在庫バッファを定義および利用して、eコマースで在庫レベルの表示を促進する
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 02/11/2020
ms.assetid: 4a2e53c8-a3ca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: boycez
dynamics365pdf: true
ms.openlocfilehash: c82c94fc95ce10549767c72d30a3bf672c402817
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3079876"
---
# <a name="define-and-utilize-inventory-buffers-to-drive-inventory-level-displays-in-e-commerce"></a>在庫バッファを定義および利用して、eコマースで在庫レベルの表示を促進する
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 4 月| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
オムニチャネル環境では在庫がすばやく移動するため、正確な手持在庫の評価を取得することが困難な場合があります。 小売業者によっては、実際の推定手持在庫数量を表示する代わりに、現在の在庫ステータスを示すだけで問題ない場合もあります。つまり、Commerce Headquarters (HQ) によって示された利用可能手持在庫値が、指定されたバッファ値よりも低い場合に、商品が品薄または在庫切れになる可能性があるという警告メッセージを顧客に表示するという方法もあります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能を使用すると、販売計画時に在庫バッファを定義しておいて、在庫バッファから抽出された在庫レベル インジケーターに API でアクセスできるようになります。
<!--feature detail end -->









