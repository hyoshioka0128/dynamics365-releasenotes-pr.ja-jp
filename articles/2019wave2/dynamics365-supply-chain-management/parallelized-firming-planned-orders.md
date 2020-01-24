---
title: 計画オーダーの並列確定
description: 計画オーダー ページから複数のスレッドによる並列確定を有効にします。
author: relnotes
ms.reviewer: kamaybac
ms.date: 12/12/2019
ms.assetid: 70517981-13cb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: crytt
dynamics365pdf: true
ms.openlocfilehash: f3fb0bd98677e4f936b7dfc8a685f5739c09c172
ms.sourcegitcommit: 50510b41ebc81897993a45f689651d9eda6c4247
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/20/2019
ms.locfileid: "2909788"
---
# <a name="parallelized-firming-of-planned-orders"></a>計画オーダーの並列確定


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 9 月 6 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 12 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
一度に多数の注文を確定する予定がある場合、実行を並列化すると、実行時間またはパフォーマンスが向上します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
計画オーダー ページからの複数のスレッドによる並列確定により、ユーザーは複数のスレッド間で確定プロセスを並列化することで確定プロセスを高速化できます。 これは、多数の計画オーダーが確定されている場合に意味がある場合があります。 並列確定とスレッド数のオプションは、確定に対して複数の計画オーダーが選択されている場合に利用可能です。
<!--feature detail end -->

![並列確定オプション](media/pf.png "並列確定オプション")
<!-- Picture 1 -->









## <a name="see-also"></a>関連項目
[機能の探索](https://www.microsoft.com/videoplayer/embed/RE4myrJ) (ビデオ)

[並列確定](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/master-planning/maintain-planned-orders#parallelize-firming) (ドキュメント)
