---
title: 手持在庫レポート ストレージ
description: Dynamics 365 Supply Chain Management で直接探索したり、エクスポートして外部アプリケーションで使用したりできる手持在庫レポートを生成します。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/02/2020
ms.assetid: 2a3532b4-5c73-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: sorenand
dynamics365pdf: true
ms.openlocfilehash: 0a14b00f4a8423aff66ca615d8cb91cd296659db
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219706"
---
# <a name="inventory-on-hand-report-storage"></a>手持在庫レポート ストレージ
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 4 月| 2020 年 5 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この新しい手持在庫レポートの生成方法は、出力に多数の行が含まれる場合に役立ちます。 たとえば、50,000 の品目と 300 の店舗があるシナリオで品目、サイト、倉庫別の手持在庫を要求すると、データの確認を困難にする非常に長いレポートが生成されます。 アプリケーション内で結果を並べ替えてフィルター処理したり、結果を外部システムにエクスポートしたりする機能により、手持在庫レポートの結果をすばやく簡単に確認できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
新しい*手持在庫レポート ストレージ*機能では、手持在庫レポートが生成され、その結果が Supply Chain Management に保存されます。Supply Chain Management では、結果をオンラインで探索したり、外部システムで使用するためにエクスポートしたりできます。 

この機能を使用してレポートを生成すると、レポートに一意の名前を指定するよう求められ、生成されたレポートはこの名前で保存されます。 これにより、同じ期間に対して複数の手持在庫レポートを実行する必要がなくなります。 ユーザーは、**手持在庫レポート ストレージ詳細**ページに移動することで保存されたレポートを参照できます。

*手持在庫レポート ストレージ* レポートは新しいデータ エンティティに保存されます。これにより、特定の名前付き手持在庫レポートの出力を、データ管理でサポートされている任意の形式にエクスポートできます。

<!--feature detail end -->









