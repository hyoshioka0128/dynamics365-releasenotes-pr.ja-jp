---
title: 出荷の自動更新
description: この機能は、AWAX 機能を標準の WHS 機能に統合するという Blue Horseshoe との契約から始まります。 この機能では、関連する注文からの出荷数量のリアルタイム表現が提供され、それがウェーブで処理されていない限り、倉庫にリリースされた後でシステムは出荷の数量を自動的に更新することができます。
author: relnotes
ms.reviewer: josaw
ms.date: 08/01/2019
ms.assetid: 9062278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: henrikan
dynamics365pdf: true
ms.openlocfilehash: 8c923aad99ea195738ba6c752472ce8a68dc155d
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854814"
---
# <a name="shipment-auto-update"></a>出荷の自動更新
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 8 月 1 日| 2019 年 10 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能を使用すると、企業は、注文明細の更新が関連する出荷や積荷に反映されないことを心配することなく、倉庫に更新をシームレスに提供できます。 この機能がないと、注文数量が増えた場合や新しい注文明細行が追加された場合、ユーザーは手動で更新または削除した後でその明細を再度リリースする必要があります。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能は、倉庫にリリースされた後で出荷に関連付けられた積荷明細行の数量を自動的に更新 (増減) します。 これは、出荷の積荷明細行または積荷がウェーブで処理されていない場合に限り行われます。 これは、倉庫作業が作成されていない限り、機能によって、手動での介入なしに、注文の更新が自動的に倉庫に流れることを意味します。 この機能がないと、倉庫作業が作成されていない場合に自動的に流れるのは数量の減少のみです。 この機能は、販売注文明細行と移動オーダー明細行に適用されます。 
 
この機能は特定の倉庫に対して有効にされます。 これにより、会社は必要に応じて、倉庫ごとに異なる出荷自動更新ポリシーを適用できます。 既定では、倉庫管理プロセスを使用するすべての倉庫に適用される出荷自動更新ポリシーは、数量の減少についてです。 このポリシーを設定すると、倉庫作業が作成されていない場合に自動的に流れるのは、出荷と積荷に対する数量の減少のみです。
<!--feature detail end -->












## <a name="see-also"></a>関連項目

[出荷の自動更新](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-finance-operations/shipment-auto-update)
