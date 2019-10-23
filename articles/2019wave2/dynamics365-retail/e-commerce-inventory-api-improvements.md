---
title: eコマース在庫 API の改善
description: この機能で導入される新しい API を使用して、小売業者は在庫の利用可能性を見積もることができます。 これらの API によって提供される情報を eコマース アプリケーションで使用し、商品を出荷または店頭での集荷に使用できるかどうかを顧客に知らせることができます。 この目的のために以前提供されていた既存の API はパフォーマンスが良くなく、計算ロジックも最適ではありませんでした。
author: hhainesms
ms.reviewer: rhaertle
ms.date: 08/13/2019
ms.assetid: c5ff120b-f182-e911-a98e-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: f85a2740f5ea8079857e27f3a82b0f4c693cec34
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141934"
---
# <a name="e-commerce-inventory-api-improvements"></a>eコマース在庫 API の改善
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|ユーザー、管理者/作成者/アナリストによる有効化|2019 年 10 月| 2020 年 1 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
企業は、推定される手持ち商品の在庫の利用可能性を入手するために、信頼性の高い高性能な API を必要としています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
新しい API では、要求された商品と倉庫に対する手持ち在庫の見積もりが提供されます。 これらの API は、現在提供されている既存の GetProductAvailability および GetAvailableInventoryNearby API に代わるものです。 これらの新しい API では、パフォーマンスを向上させるために計算ロジックとキャッシュが改善されています。

さらに、新しいパラメーターにより、これらの新しい API が取り込まれ、商品の既定の注文設定に基づいてカート注文明細を調達するための "最善" の倉庫の検索が試みられる現在の API の既存の高コスト ロジックがオフになります。 このロジックは新しい API には含まれません。 組織では、将来の分散型注文管理機能を使用して、店頭以外で集配される販売明細行向けに最適なフルフィルメント場所を選択できます。したがって、この高コストのロジックは新しい API には含まれなくなります。
<!--feature detail end -->











