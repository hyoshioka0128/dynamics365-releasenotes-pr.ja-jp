---
title: インドの在庫移動オーダーでの単価と原価価格の取り扱いの改善
description: インドの在庫移動オーダーでの単価と原価価格の取り扱いの改善。
author: relnotes
ms.reviewer: kfend
ms.date: 06/05/2020
ms.assetid: 878e53e0-639e-ea11-a812-000d3a563be2
ms.topic: article
ms.service: business-applications
ms.author: epopov
dynamics365pdf: true
ms.openlocfilehash: 6c4c1161c816d950a4d43cb0ea820d289737374f
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3441383"
---
# <a name="improvements-in-unit-price-and-cost-price-handling-in-stock-transfer-orders-for-india"></a>インドの在庫移動オーダーでの単価と原価価格の取り扱いの改善
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 5 月 29 日| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
在庫移動機能は、インドのお客様が現地の税法に準拠するために使用します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能では、インドの在庫移動オーダー機能に以下の改善が加えられています。

- **移動タイプ**と**価格タイプ**の既定値は、**在庫および倉庫管理パラメーター**で構成できます。
- 在庫移動オーダー明細行の単価は、最初の出荷が明細行に転記されるまで、明細行に指定された在庫分析コードに基づいて正しく再計算されます。
- 単価がゼロの在庫移動オーダー明細行の出荷を防ぐことができます。
- 部分的な出荷または入荷、バッチ管理品目などの場合の在庫移動オーダーには、正しい在庫原価が転記されます。
- 単価が品目の在庫原価価格と異なる場合、在庫移動明細行の出荷または入荷時に未実現の利益または損失は転記されません。

この機能では、在庫移動オーダー明細行の測定単位の変更も制限されます。

**機能管理**で **(インド) 在庫移動オーダーの単価と原価価格の取り扱いの改善**機能を有効にする必要があります。
<!--feature detail end -->









