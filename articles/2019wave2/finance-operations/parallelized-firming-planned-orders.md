---
title: 計画オーダーの並列確定
description: 計画オーダー ページから複数のスレッドによる並列確定を有効にします。
author: relnotes
ms.reviewer: josaw
ms.date: 09/12/2019
ms.assetid: 70517981-13cb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: crytt
dynamics365pdf: true
ms.openlocfilehash: 06917cb5704084f969bdb89ef632d2777e2d1ff2
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143001"
---
# <a name="parallelized-firming-of-planned-orders"></a>計画オーダーの並列確定
[!include[finance-operations banner](../includes/finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 9 月 6 日| 2019 年 12 月|


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

[並列確定](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/master-planning/maintain-planned-orders#parallelize-firming) (ドキュメント)
