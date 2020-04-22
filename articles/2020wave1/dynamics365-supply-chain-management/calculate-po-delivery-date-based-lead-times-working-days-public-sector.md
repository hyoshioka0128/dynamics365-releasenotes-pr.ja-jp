---
title: リード タイムと稼働日に基づいて発注書の配送日を計算する (公的機関)
description: 仕入先のリード タイムと組織の稼働日カレンダーに基づいて、発注書明細行の配送日を計算します。 この機能は公的機関の構成にのみ適用されます。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/01/2020
ms.assetid: 002d1922-021e-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: mkirknel
dynamics365pdf: true
ms.openlocfilehash: 21c47f74f366d46debf9723c630ba5f88641816f
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219229"
---
# <a name="calculate-po-delivery-date-based-on-lead-times-and-working-days-public-sector"></a>リード タイムと稼働日に基づいて発注書の配送日を計算する (公的機関)
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日| 2020 年 4 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
仕入先のリード タイムと組織の稼働日カレンダーに基づいて、明細行の配送日を計算します。仕入先は各明細行のリード タイムを入力できます。発注書が確認されると、リード タイムと稼働日カレンダーに基づいて、確認日付から明細行の配送日が計算されます。リード タイムが指定されていない場合、配送日は確認日になります。管理者は、機能を有効にした後、調達パラメーターを使用して機能を有効にする必要があります。
<!--feature detail end -->









