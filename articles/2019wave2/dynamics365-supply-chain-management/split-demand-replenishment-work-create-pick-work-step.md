---
title: ピッキング作業作成ステップからの需要補充作業の分割
description: この機能により、ユーザーは補充作業トランザクションを作業作成の残りの部分から分離することができます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 03/19/2020
ms.assetid: 7a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: d5091ab8169a37cf682680bf62c28e32ba213f23
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178804"
---
# <a name="split-demand-replenishment-work-from-create-pick-work-step"></a>ピッキング作業作成ステップからの需要補充作業の分割


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 4 月 1 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 1 月 27 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能により、各トランザクションの将来のパフォーマンス向上が可能になります。 また、トランザクション サイズを小さくすることで、潜在的なロックの影響も本質的に軽減します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
バージョン 7.1 のタイムフレームでは、マルチスレッドを導入することでウェーブの割り当てステップを改善しました。 残りのステップは、現在マルチスレッドではなく、単一の長いデータベース トランザクションで実行されます。 ピッキング作業の作成が表す長いトランザクションの最適化に関する問題の 1 つは、需要の補充がそのトランザクション内で作成されるという事実です。 将来のパフォーマンス最適化の目的で、補充作業作成ステップを独自のトランザクションを持つ独自のスレッドに分離します。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[倉庫管理の概要](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/warehousing/warehouse-management-overview) (ドキュメント)
