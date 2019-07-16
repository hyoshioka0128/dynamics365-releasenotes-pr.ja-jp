---
title: ピッキング作業作成ステップからの需要補充作業の分割
description: この機能により、ユーザーは補充作業トランザクションを作業作成の残りの部分から分離することができます。
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 7a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: d2a456cdce5301f0677d588b76a94627d79c841a
ms.sourcegitcommit: d6ff62c145bfdd7742034a67a29bf75938823eb0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/24/2019
ms.locfileid: "1701458"
---
# <a name="split-demand-replenishment-work-from-create-pick-work-step"></a>ピッキング作業作成ステップからの需要補充作業の分割
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 4 月| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能により、各トランザクションの将来のパフォーマンス向上が可能になります。 また、トランザクション サイズを小さくすることで、潜在的なロックの影響も本質的に軽減します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
バージョン 7.1 のタイムフレームでは、マルチスレッドを導入することでウェーブの割り当てステップを改善しました。 残りのステップは、現在マルチスレッドではなく、単一の長いデータベース トランザクションで実行されます。 ピッキング作業の作成が表す長いトランザクションの最適化に関する問題の 1 つは、需要の補充がそのトランザクション内で作成されるという事実です。 将来のパフォーマンス最適化の目的で、補充作業作成ステップを独自のトランザクションを持つ独自のスレッドに分離します。
<!--feature detail end -->










