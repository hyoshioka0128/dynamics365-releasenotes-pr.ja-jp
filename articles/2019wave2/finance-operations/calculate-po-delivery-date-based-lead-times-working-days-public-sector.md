---
title: リード タイムと稼働日に基づいて発注書の配送日を計算する (公的機関)
description: 仕入先のリード タイムと組織の稼働日カレンダーに基づいて、発注書明細行の配送日を計算します。 この機能は公的機関の構成にのみ適用されます。
author: relnotes
ms.reviewer: josaw
ms.date: 08/02/2019
ms.assetid: 543675a1-3772-e911-a960-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: mkirknel
dynamics365pdf: true
ms.openlocfilehash: afaf2f5dcc4f17ae9161205ef3f6fbf71f07363e
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141637"
---
# <a name="calculate-po-delivery-date-based-on-lead-times-and-working-days-public-sector"></a>リード タイムと稼働日に基づいて発注書の配送日を計算する (公的機関)
[!include[finance-operations banner](../includes/finance-operations.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|ユーザー、管理者/作成者/アナリストによる有効化|-| 2019 年 11 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能は、仕入先のコンプライアンスを追跡したい組織に役立ちます。 仕入先が RFQ でリード タイムを送信すると、結果の発注書では配送日が自動的に計算されます。 購入者はレポートを実行し、元の提案とコミットメントに基づいて仕入先のパフォーマンスを確認できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
仕入先のリード タイムと組織の稼働日カレンダーに基づいて、明細行の配送日を計算します。仕入先は各明細行のリード タイムを入力できます。発注書が確認されると、リード タイムと稼働日カレンダーに基づいて、確認日付から明細行の配送日が計算されます。リード タイムが指定されていない場合、配送日は確認日になります。管理者が機能を有効にした後、調達パラメーターを使用して機能を有効にする必要があります。
<!--feature detail end -->











