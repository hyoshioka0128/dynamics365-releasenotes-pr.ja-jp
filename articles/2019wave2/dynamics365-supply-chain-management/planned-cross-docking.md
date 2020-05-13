---
title: クロスドッキング
description: クロスドッキングを使用すると、作業者は、既に出庫指示に対してマークされている在庫の入庫プット アウェイと出庫ピッキングをスキップすることができます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/07/2020
ms.assetid: 9862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: a8c600f0658cd325ee919daf0c8784f3bd2b59b3
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3319997"
---
# <a name="cross-docking"></a>クロスドッキング


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 8 月 2 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 3 月 31 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能により、既存の注文を満たすために必要なすべての入庫在庫を、プット アウェイしなくても正しい出荷ドックまたはステージング領域に直接移動できる、計画された高度なクロスドッキングが導入されます。 入庫ソースからのすべての残余在庫が、通常のプット アウェイ プロセスを通じて正しい保存場所に送られます。 クロスドッキングを使用すると、作業者は、既に出庫指示で対象としてマークされている在庫の入庫プット アウェイと出庫ピッキングをスキップすることができます。 その結果、在庫に触れる回数が可能な限り最小限に抑えられると同時に、システムを操作する回数が減るため、倉庫の作業現場での時間とスペースを節約できます。 

ユーザーは、新しいクロスドッキング テンプレートをを使って、クロスドッキングに対する供給元とその他の要件を指定できます。 入庫在庫と出庫指示を突き合わせるプロセスは、_マーキング_と呼ばれます。 出庫指示を作成する際、ユーザーは必要な品目を含む入庫指示と一致するように各関連行をマークする必要があります。 このプロセスでは、クロスドッキング作業指示書が作成され、倉庫へのリリースによって手動または自動で行うことができます。 入庫指示を受け取ったら、クロスドッキング設定によってクロスドッキングの必要性が自動的に識別され、場所のディレクティブの設定に基づいて必要な数量の移動作業が作成されます。

自動リリース出荷機能は、クロスドッキング フレームワークに基づいています。また、クロスドッキング戦略をサポートしており、需要数量を供給する製造オーダーが完了したと報告されたときに販売注文または移動オーダーを倉庫に自動的にリリースできます。 このようにして、需要オーダーを履行するのに必要な数量が、生産出荷の場所から出庫の場所に直接移動されます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目
[機能の探索](https://www.microsoft.com/videoplayer/embed/RE4f7LF) (ビデオ)

<!--docs start-->
[倉庫管理の概要](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (ドキュメント)
<!--docs end-->
