---
title: ゾーンしきい値の補充
description: この機能により、動的な場所を使用する会社は、最小/最大補充プロセスを使用できます。たとえば、短期間で多数の在庫のある商品を扱う小売業者などです。
author: relnotes
ms.reviewer: kamaybac
ms.date: 01/06/2020
ms.assetid: 8462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: e64986f905bc803f34caf47324642fee99d0e2db
ms.sourcegitcommit: 7d5d14ac84333ba166265755f410f7e16035a64e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2948257"
---
# <a name="zone-threshold-replenishment"></a>ゾーンしきい値の補充


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 4 月 8 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 12 月 19 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
ゾーンベースの補充機能では、最小/最大補充戦略が使用されますが、個々の場所ではなく倉庫ゾーンが評価されます。 固定の場所の設定に依存しないことで、この機能では動的な場所の補充が可能になります。 これにより、動的な場所を使用する会社は、最小/最大補充プロセスを使用できます。たとえば、短期間で多数の在庫のある商品を扱う小売業者などです。 

最小/最大補充用の補充テンプレートでは、ユーザーはしきい値を場所ごとまたはゾーンごとのどちらで評価する必要があるかを指定します。 ゾーンの場合は、特定のゾーンがゾーン選択クエリに追加されます。 場所ベースの最小/最大補充では、ゾーン ベースの最小/最大補充は、選択した品目および品目バリアントの補充作業指示書の作成をトリガーする在庫の最小しきい値の設定に基づいています。 結果として、在庫を目的のゾーン最大しきい値まで増加させる数量の補充が作成されます。
<!--feature detail end -->




