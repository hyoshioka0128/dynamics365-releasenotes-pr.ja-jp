---
title: ピッキング明細行のグループ化
description: ピッキング明細行グループ化設定により、ユーザーはモバイル デバイス上で複数のピッキング明細行を動的にグループ化して単一のピッキング実行ステップに集約できます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 01/06/2020
ms.assetid: 6a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: d2f1bfbeb3825c217e9ff778abf6b4c8cb18933e
ms.sourcegitcommit: 7d5d14ac84333ba166265755f410f7e16035a64e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2947991"
---
# <a name="pick-line-grouping"></a>ピッキング明細行のグループ化


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 3 月 5 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 12 月 19 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
ピッキング明細行グループ化設定により、ユーザーはモバイル デバイス上で複数のピッキング明細行を動的にグループ化して単一のピッキング実行ステップに集約できます。 システムは、すべてのピッキング明細行を一致する分析コード セット (つまり、品目 ID と場所 ID) でグループ化します。ユーザーは、複数の一致するピッキング明細行を持つ 1 つの作業指示書に対し、ピッキング場所に 1 回だけアクセスする必要があります。 この機能により、ピッキング作業をすばやく実行でき、特定のシナリオでの作業者のピッキング パスが大幅に短縮されます。 この機能は、モバイル デバイスの設定を介して自動的に適用されます。 処理中の作業指示書のすべての一致するピッキング明細行および関連するトランザクションが、システムによって相互に更新されます。 作業指示書の構造は最初に作成されたままになり、明細行はクライアント内で集約されません。ただし、この機能を使用するには、ピッキング明細行を品目 ID で並べ替える必要があります。
<!--feature detail end -->





