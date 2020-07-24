---
title: 在庫決算キャンセルの用語を在庫決算破棄に変更
description: 在庫決算キャンセルの用語を在庫決算破棄に変更します。
author: RichardLuan
ms.reviewer: kamaybac
ms.date: 06/24/2020
ms.assetid: 3a55c727-02a7-ea11-a812-000d3a563be2
ms.topic: article
ms.service: business-applications
ms.author: riluan
dynamics365pdf: true
ms.openlocfilehash: 739b450b0b15e9a4d5eb062d9e19a2c7d5d8b95b
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3524113"
---
# <a name="change-the-terminology-of-inventory-closing-cancellation-to-inventory-closing-reverse"></a>"在庫決算キャンセル" の用語を "在庫決算破棄" に変更
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|2020 年 8 月| 2020 年 9 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
ラベルを変更して、在庫決算操作を元に戻すコマンドをユーザーが理解しやすくします。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
**決算と調整**ページには、ユーザーが選択した在庫決算操作を "キャンセル" できるボタンがあります。ただし、まだ実行中の在庫決算操作をユーザーがキャンセルしようとすると、データの破損を防ぐために要求がブロックされます。 代わりに、システムは選択された決算操作を完了後に*元に戻し*ます。 混乱を避けるため、この機能に関連するボタンのラベルとその他のラベルを**キャンセル**から**破棄**に変更しました。 

この変更はリリース 10.0.13 以降は既定で適用されますが、機能が "[決算と調整] のキャンセルのラベルを取消に変更" という名前になっている Supply Chain Management の**機能管理**ページにも表示されます。 以前のラベルの方が好ましい場合は、機能管理を使用してこの機能をオフにすることができます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[在庫決算](https://docs.microsoft.com/dynamics365/supply-chain/cost-management/inventory-close) (ドキュメント)
<!--docs end-->
