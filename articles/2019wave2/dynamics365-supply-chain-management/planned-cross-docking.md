---
title: 計画的クロスドッキング
description: クロスドッキングを使用すると、作業者は、既に出庫指示に対してマークされている在庫の入庫プット アウェイと出庫ピッキングをスキップすることができます。
author: relnotes
ms.reviewer: josaw
ms.date: 10/04/2019
ms.assetid: 9862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 826ff28b22c002cecc686b103bdbdbfd790b06b5
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660595"
---
# <a name="planned-cross-docking"></a>計画的クロスドッキング
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 2 日| 2020 年 1 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能により、注文を満たすために必要な在庫数量が、入庫または作成から正しい出荷ドックまたはステージング領域に直接送られる、計画された高度なクロスドッキングが導入されます。 入庫ソースからのすべての残余在庫が、通常のプット アウェイ プロセスを通じて正しい保存場所に送られます。したがって、クロスドッキングを使用すると、作業者は、既に出庫指示にマークされている在庫の入庫プット アウェイと出庫ピッキングをスキップすることができます。 その結果、在庫に触れる回数が可能な限り最小限に抑えられるだけでなく、システムとのやり取りが少なくなるため、倉庫の作業現場での時間とスペースを大幅に節約できます。 

ユーザーは、クロスドッキングに対する供給元とその他の要件を指定した新しいクロスドッキング テンプレートを構成する必要があります。 出庫指示が作成されたら、同じ品目を含む入庫指示に対して明細行がマークされる必要があります。 マーキングは、入庫在庫と出庫指示を突き合わせるプロセスです。 クロスドッキング作業指示書の作成に使用され、倉庫へのリリースによって手動または自動で行うことができます。 入庫指示を受け取った時点で、クロスドッキング設定によってクロスドッキングの必要性が自動的に識別され、場所のディレクティブの設定に基づいて必要な数量の移動作業が作成されます。
<!--feature detail end -->









