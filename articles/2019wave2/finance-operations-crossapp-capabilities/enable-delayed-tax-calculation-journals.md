---
title: 仕訳帳の遅延税計算の有効化
description: ユーザーが仕訳帳を作成または変更するときに税計算を遅らせることができます
author: RichardLuan
ms.reviewer: kfend
ms.date: 01/16/2020
ms.assetid: 52767a22-d51f-ea11-a810-000d3a8f004f
ms.topic: article
ms.service: business-applications
ms.author: riluan
dynamics365pdf: true
ms.openlocfilehash: 5857ddd05dadea53027b3257f18763fd26be20c4
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3058598"
---
# <a name="enable-delayed-tax-calculation-on-journals"></a>仕訳帳の遅延税計算の有効化


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、自動的|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 21 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 1 月 3 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能により、仕訳帳明細行が複数ある場合の税計算のパフォーマンスが向上します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
既定では、仕訳帳明細行の消費税額は、税関連フィールドが更新されるたびに計算されます。 これには、消費税グループと品目消費税グループのフィールドが含まれます。 仕訳帳明細行を更新すると、すべての使用税の税額が再計算されます。 この動作により、ユーザーはリアルタイムで計算された税額を確認できますが、仕訳帳明細行の数が非常に多い場合はパフォーマンスにも影響する可能性があります。

遅延税計算機能を使用すると、仕訳帳の税計算を遅らせることができるため、パフォーマンスの問題を修正できます。 この機能をオンにすると、ユーザーが **消費税** または仕訳帳を選択した場合のみ税額が計算されます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[仕訳帳の遅延税計算の有効化](https://docs.microsoft.com/dynamics365/finance/general-ledger/enable-delayed-tax-calculation) (ドキュメント)
