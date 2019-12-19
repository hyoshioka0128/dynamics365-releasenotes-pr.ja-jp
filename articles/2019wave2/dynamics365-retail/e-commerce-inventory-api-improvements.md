---
title: eコマース在庫 API の改善
description: この機能で導入される新しい API を使用して、小売業者は在庫の利用可能性を見積もることができます。 これらの API によって提供される情報を eコマース アプリケーションで使用し、商品を出荷または店頭での集荷に使用できるかどうかを顧客に知らせることができます。 この目的のために以前提供されていた既存の API はパフォーマンスが良くなく、計算ロジックも最適ではありませんでした。
author: hhainesms
ms.reviewer: rhaertle
ms.date: 11/15/2019
ms.assetid: c5ff120b-f182-e911-a98e-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: d07b1fa54be8c54cecc1f273880db8e378f9493c
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2890159"
---
# <a name="e-commerce-inventory-api-improvements"></a>eコマース在庫 API の改善
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 21 日| 2020 年 1 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
企業は、推定される手持ち商品の在庫の利用可能性を入手するために、信頼性の高い高性能な API を必要としています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
新しい API では、要求された商品と倉庫に対する手持ち在庫の見積もりが提供されます。 これらの API は、現在提供されている既存の GetProductAvailability および GetAvailableInventoryNearby API に代わるものです。 これらの新しい API では、パフォーマンスを向上させるために計算ロジックとキャッシュが改善されています。

さらに、新しいパラメーターにより、これらの新しい API が取り込まれ、商品の既定の注文設定に基づいてカート注文明細を調達するための "最善" の倉庫の検索が試みられる現在の API の既存の高コスト ロジックがオフになります。 このロジックは新しい API には含まれません。 組織では、将来の分散型注文管理機能を使用して、店頭以外で集配される販売明細行向けに最適なフルフィルメント場所を選択できます。したがって、この高コストのロジックは新しい API には含まれなくなります。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[Retail POS API](https://docs.microsoft.com/dynamics365/retail/dev-itpro/pos-apis) (ドキュメント)
