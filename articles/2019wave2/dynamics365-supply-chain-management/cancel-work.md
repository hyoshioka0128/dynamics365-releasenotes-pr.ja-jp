---
title: 作業のキャンセル
description: 作業のキャンセル機能を使用すると、管理ユーザーは現在進行中であるがブロックされている特定の倉庫作業をキャンセルできます。 運用上の理由でキャンセルが必要な作業については、ユーザーは作業フォームで利用可能な通常の作業キャンセル操作を引き続き使用する必要があります。
author: relnotes
ms.reviewer: josaw
ms.date: 10/16/2019
ms.assetid: 6062278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: omulvad
dynamics365pdf: true
ms.openlocfilehash: 8b322d48677de8f0756f11cd1f30139ee941f554
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660552"
---
# <a name="cancel-work"></a>作業のキャンセル
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 6 月 7 日| 2020 年 1 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
作業のキャンセル機能は、現在は管理権限を持つ会社のユーザーが使用できる、矛盾するデータを修正するために通常は IcM チケットを通じて要求される SQL 修正スクリプトに代わる、魅力的で安全な方法です。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
倉庫作業の強制キャンセルは、現在進行中ではあるがブロックされている (多くの場合はデータ破損のためですが、そうでない場合もあります) 特定の倉庫作業をユーザーがキャンセルできるようにする管理機能です。 

標準の**キャンセル** ボタン ([作業] ページから直接使用できるボタン) とは異なり、新しい作業のキャンセル機能には、最後に完了した作業明細のタイプが**プット**でなければならないという前提条件はありません。 つまり、作業明細の品目数量がユーザー以外の場所にある必要はありません。 

このジョブで取り消すことができるのは、タイプが**販売**、**移動の出庫**、**原材料ピッキング**、または**補充**の作業だけです。 凍結された原材料のピッキング作業の場合、または通常の取消機能 (前述のとおり) で取り消すことができる作業の場合、キャンセルは実行されません。 

作業のブロックを解除するため、残りの作業明細が取り消され、作業 ID に関連付けられている倉庫データが修正されます。 これにより、影響を受ける品目の数量を含む通常の倉庫処理作業を再開できます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[例外処理のために倉庫作業をキャンセル](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/cancel-warehouse-work) (ドキュメント)
