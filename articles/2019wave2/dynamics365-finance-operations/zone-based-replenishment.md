---
title: ゾーン ベースの補充
description: この機能により、動的な場所を使用する会社は、最小/最大補充プロセスを使用できます。たとえば、短期間で多数の在庫のある商品を扱う小売業者などです。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: 8462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: d0ae252886c52d7709bf9e6f131139afc85b9588
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854616"
---
# <a name="zone-based-replenishment"></a>ゾーン ベースの補充
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | ---------- |---------- |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 8 月| 2019 年 10 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
ゾーンベースの補充機能では、最小/最大補充戦略が使用されますが、個々の場所ではなく倉庫ゾーンが評価されます。 固定の場所の設定に依存しないことで、この機能では動的な場所の補充が可能になります。 これにより、動的な場所を使用する会社は、最小/最大補充プロセスを使用できます。たとえば、短期間で多数の在庫のある商品を扱う小売業者などです。 最小/最大補充用の補充テンプレートでは、ユーザーはしきい値を場所ごとまたはゾーンごとのどちらで評価する必要があるかを指定します。 ゾーンの場合は、特定のゾーンがゾーン選択クエリに追加されます。 場所ベースの最小/最大補充では、ゾーン ベースの最小/最大補充は、選択した品目および品目バリアントの補充作業指示書の作成をトリガーする在庫の最小しきい値の設定に基づいています。 結果として、在庫を目的のゾーン最大しきい値まで増加させる数量の補充が作成されます。
<!--feature detail end -->











