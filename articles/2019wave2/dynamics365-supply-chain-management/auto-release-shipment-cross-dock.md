---
title: クロスドッキング用の自動リリース出荷
description: この機能は、クロスドッキング戦略をサポートしており、需要数量を供給する製造オーダーが完了したと報告されたときに需要オーダーを倉庫に自動的にリリースできます。 このようにして、需要オーダーの履行に必要な数量が、生産出荷の場所から出庫の場所に直接移動されます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/07/2020
ms.assetid: 9e62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: fd5dbeb4b522c0dc7faf7d40501a736d956ed06b
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320162"
---
# <a name="auto-release-shipment-for-cross-dock"></a>クロスドッキング用の自動リリース出荷


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 1 月 27 日| 近日発表|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
自動リリース出荷機能は、クロスドッキング フレームワークに基づいており、次の特性があります。

- 供給として製造オーダーのみ、需要として販売注文および移動オーダーのみサポートされます。
- クロスドッキング工程は、供給受領が登録される前に (つまり、生産が終了したと報告される前に) 需要オーダーが倉庫にリリースされなかった場合でも開始できます。

このクロスドッキング機能には 2 つの利点があります。

1. 倉庫工程では、出庫指示を完了するために数量が再びピックアップされるだけの場合、通常の倉庫保管領域に完成品の数量をプット アウェイするステップをスキップできます。 代わりに、数量を出荷の場所から梱包/配送の場所に一度移動できます。 このように、この機能により、在庫の処理回数を最小限に抑えることができ、最終的に、倉庫の作業現場で時間とスペースを最大限に節約できます。
2. 倉庫工程では、関連する製造オーダーの完成品の出荷が終了したと報告されるまで、販売注文のリリースを延期して倉庫に移動することができます。 これは、製造リード タイムが見込み生産環境のリード タイムよりも長くなる傾向がある場合に、受注生産環境で特にメリットとなる可能性があります。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[クロスドッキング用の自動リリース出荷](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/auto-release-shipment-for-cross-docking) (ドキュメント)
<!--docs end-->
