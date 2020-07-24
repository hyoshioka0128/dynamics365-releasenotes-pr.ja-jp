---
title: POS 出庫操作で選択した出荷の残余をクローズする
description: この機能は、出庫操作を通じて販売時点管理 (POS) アプリケーションで移動オーダー在庫を出荷するときに、残余をクローズするオプションをユーザーに提供します。
author: hhainesms
ms.reviewer: josaw
ms.date: 05/26/2020
ms.assetid: a7b16c91-9c6f-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: e6fd1018295ba9c76b0fe65d1c935c8cb5fa616d
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3416421"
---
# <a name="close-remainder-of-a-selected-shipment-line-in-pos-outbound-operation"></a>POS 出庫操作で選択した出荷の残余をクローズする
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 5 月 18 日| 2020 年 7 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
販売時点管理 (POS) アプリケーションを通じて出庫移動オーダーの在庫を出荷する際、店舗マネージャーは、出荷できるのは要求された数量の一部のみで、入庫を要求している倉庫に要求数量全体を提供することはできないと判断する場合があります。 

全量が出荷されていなくても、移動オーダー明細が適切にクローズされるようにするために、ユーザーは選択した移動オーダー明細に対して "残余のクローズ" 機能を使用することができます。 このオプションを選択すると、POS からの移動オーダーが処理されるときに部分的な出荷数量がコマース本部に転記され、未処理の出荷残数量はキャンセルされたと見なされます。 これにより、将来の出荷のために明細をクローズすることができ、入庫倉庫または店舗は、要求残数量が別途出荷されることを期待できないと明確に理解できるようになります。 

この機能は、会社が移動オーダーの "過少配送を許可する" パラメーターを構成し、残余/キャンセル済み数量のクローズが移動オーダー明細に構成された過少配送割合の許容範囲内にある場合にのみ機能します。
<!--feature detail end -->









