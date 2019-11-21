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
ms.openlocfilehash: fbb241b085b45e264d848cdf5aa7d169296e9e00
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660598"
---
# <a name="parallelized-firming-of-planned-orders"></a>計画オーダーの並列確定
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 9 月 6 日| 2019 年 12 月|


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
