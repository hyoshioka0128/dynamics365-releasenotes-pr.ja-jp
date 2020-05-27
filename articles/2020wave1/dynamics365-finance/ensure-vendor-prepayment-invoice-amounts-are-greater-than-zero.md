---
title: 仕入先の前払請求額がゼロより大きいことを確認する
description: この機能は、仕入先前払請求額が確実にゼロより大きくなるようにします。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/16/2020
ms.assetid: 66b50591-707f-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 3c1c7b56e12f53039a1fcc5b9134b8f704609393
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294943"
---
# <a name="ensure-vendor-prepayment-invoice-amounts-are-greater-than-zero"></a>仕入先の前払請求額がゼロより大きいことを確認する
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|-| 2020 年 8 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
仕入先前払請求額が確実にゼロよりも大きくなるようにすると、その後の前払処理を正常に完了できるように予防手段が提供されます。  
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能により、通貨金額がゼロの前払請求書を転記できなくなります。 前払請求書に正の金額を要求すると、後続の処理が正常に完了することを保証できます。 この変更は必須であり、既定でオンになっています。
<!--feature detail end -->









