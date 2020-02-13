---
title: 品目価格の比較の格納
description: 品目価格の比較の格納機能を使用すると、品目価格の比較レポートを実行して、Dynamics 365 Supply Chain Management 内で出力にアクセスできるようにしたり、外部アプリケーションで使用するためにデータ エンティティを通じて出力のエクスポートに使用できるようにしたりできます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 01/07/2020
ms.assetid: 77df9cfb-2831-ea11-a810-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: aevengir
dynamics365pdf: true
ms.openlocfilehash: 2ac9e04a81fee1695400ba47e8a110bb9fe8f59d
ms.sourcegitcommit: 9ede92eba84a02579fc8fc63e6a9673b034ce30c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2020
ms.locfileid: "2976553"
---
# <a name="compare-item-price-storage"></a>品目価格の比較の格納
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 2 月| 2020 年 4 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この新しい品目価格の比較レポートの実行方法は、出力に多数の行が含まれる場合に役立ちます。 たとえば、60,000 品目に対する現在のアクティブな標準原価と来年の保留中の標準原価の比較を要求すると、データを確認するのが難しい非常に長いレポートが生成されます。 結果を並べ替えてフィルター処理したり、結果を外部システムにエクスポートしたりできると、レポートをすばやく簡単に確認できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
品目価格の比較の格納用の新しい機能を導入しています。 「品目価格の比較」レポートを実行するときは、特定の実行に対して一意の名前を指定する必要があり、レポートの結果はその名前で保存されます。

出力には、**品目価格の比較の格納**ページでアクセスできます。 このページでは、ユーザーが行った構成に応じて列が動的に調整され、残高が集計されます。 フィルターを追加して、価格の純変動額が最大の品目がグリッドの上部に表示されるようにすることができます。 ドリルスルー機能を使用すると、原価グループ タイプまたは原価グループごとに純変動額を確認できます。  特定の価格をさらに分析する必要がある場合は、実際原価計算へのリンクを利用できます。

また、新しい「品目価格の比較」データ エンティティも導入しています。 このデータ エンティティを使用すると、特定の「品目価格の比較」レポートの出力をデータ管理でサポートされる任意の形式にエクスポートして、データを外部アプリケーションで使用できるようにすることができます。
<!--feature detail end -->






![比較チャートを表示します。品目が原価グループ タイプおよび原価グループ別の内訳でフィルターされています](media/compare-chart.png "比較チャートを表示します。品目が原価グループ タイプおよび原価グループ別の内訳でフィルターされています。")
<!-- Picture 1 -->
![品目価格の比較の格納の詳細。品目が原価グループ別の内訳でフィルターされています](media/compare-details.png "品目価格の比較の格納の詳細。品目が原価グループ別の内訳でフィルターされています。")
<!-- Picture 2 -->









## <a name="see-also"></a>関連項目

[品目価格の比較の格納](https://docs.microsoft.com/dynamics365/supply-chain/cost-management/compare-item-price) (ドキュメント)