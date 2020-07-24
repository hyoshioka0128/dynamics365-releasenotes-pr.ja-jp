---
title: 類似する顧客を見つける
description: 人工知能で類似する顧客セグメントを見つけます。
author: relnotes
ms.reviewer: mhart
ms.date: 06/03/2020
ms.assetid: 2e415913-c988-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: midevane
dynamics365pdf: true
ms.openlocfilehash: 03dbc9e401ee035afb903de88caad9e10d762814
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3440602"
---
# <a name="find-similar-customers"></a>類似する顧客を見つける
[!include[artificial-intelligence/dynamics365-customer-insights banner](../includes/artificial-intelligence/dynamics365-customer-insights.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 6 月| 近日発表|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
セグメントの拡張により、人工知能を使用して顧客ベース内の類似する顧客を見つけることができます。 二項分類機械学習モデルでは、拡張されたセグメント内の顧客に類似性スコアが割り当てられます。 スコアは、ソース セグメントの顧客との類似性に基づきます。 類似性スコアに応じて、新しく作成されたセグメントに顧客プロファイルが追加されます。

これはデジタル マーケティングで類似モデリングと呼ばれることもあり、AI モデルを使用して、追加の属性を考慮することで顧客の別のセグメントに類似する顧客を見つけるのに役立ちます。 これにより、属性を選択できるだけでなく、この新しいセグメントに含まれる顧客の最大数を指定することもできます。 AI モデルは、選択した属性に基づいて各顧客の類似スコアを計算し、平均類似スコアが高い顧客を探します。 結果のセグメントには、元のセグメント内の顧客に似ている顧客が含まれます。
<!--feature detail end -->









