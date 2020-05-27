---
title: 顧客の注文に対して出荷/集荷元倉庫を選択するための柔軟なオプションを提供する
description: この機能により、DOM ルールに対して出荷倉庫を選択するオプションが管理者に提供されます。
author: relnotes
ms.reviewer: josaw
ms.date: 04/30/2020
ms.assetid: b5b8b554-948a-ea11-a812-000d3a563be2
ms.topic: article
ms.service: business-applications
ms.author: rapraj
dynamics365pdf: true
ms.openlocfilehash: b605c21f337df03a0d2352419d6a859e4b675588
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350920"
---
# <a name="provide-flexible-options-for-choosing-shipping-or-pickup-warehouse-for-customer-orders"></a>顧客の注文に対して出荷/集荷元倉庫を選択するための柔軟なオプションを提供する
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 5 月| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能により、分散型注文管理 (DOM) フルフィルメント プロファイルに対してルールを実行する際の効率が向上します。 この機能を使用すると、DOM ルールが出荷倉庫の場所に対してのみ実行され、より大きな場所のサブセットに対しては実行されなくなります。 

DOM フルフィルメント プロファイルに関連付けられた、フルフィルメント グループに含まれている出荷倉庫のフィルター処理されたリストのみを使用することにより、DOM ルールがより効果的かつ効率的に実行されるようにします。  
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
- 出荷される品目の一部またはすべてに対して注文が作成されると、DOM は出荷場所のリストからの製品の在庫状況に基づいて、注文を処理するための最適化された計画を実行します。  

- 注文管理サービスが処理されて注文が実行されると、DOM プロファイルは関連付けられているフルフィルメント グループから利用可能なすべての出荷場所を調べ、そのグループ内の出荷場所に対してルールを実行します。 

- 関連付けられている出荷場所またはフルフィルメント グループがない場合、DOM フルフィルメント プロファイル内のルールを実行する現在のプロセスに変わりはありません。 
<!--feature detail end -->









