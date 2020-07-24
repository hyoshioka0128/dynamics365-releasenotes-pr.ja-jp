---
title: オプトインによる二重書き込みでの通貨の小数の拡張のサポート
description: Finance and Operations アプリと Common Data Service 間の二重書き込みを使用している組織では、Common Data Service の通貨と為替レートの小数点以下の桁数を増やすようにオプトインできます。
author: relnotes
ms.reviewer: sericks
ms.date: 06/26/2020
ms.assetid: b4fa7ba5-02b7-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: nhelgren
dynamics365pdf: true
ms.openlocfilehash: f2ba084d39efe1275c1e7eb07725e1fa60b066ce
ms.sourcegitcommit: 5c4dedb0e6948b1f237125c035518882f4cce114
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3530869"
---
# <a name="opt-in-extended-decimal-support-for-currencies-with-dual-write"></a>オプトインによる二重書き込みでの通貨の小数の拡張のサポート
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|-| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Finance and Operations アプリと Common Data Service での二重書き込みの使用時に、小数点以下の桁数が多いことが原因でデータが失われるのを防ぎます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->

Common Data Service の標準的なデプロイでは、通貨値の小数点以下の桁数は 4 桁、為替レート値の小数点以下の桁数は 10 桁です。 Finance and Operations アプリで通貨値と為替レート値を二重書き込みする際にデータが失われないようにするために、ユーザーは Common Data Service で小数のサポートを拡張 (通貨の小数点以下の桁数を 10 桁、為替レートの小数点以下の桁数を 12 桁に) するようにオプトインできます。 オプトインすると、通貨と為替レートのデータ型が新しい小数値に拡張され、既存のすべてのデータが新しい小数点以下の桁数に移行されます。

移行は任意です。 小数点以下の桁数を増やすことでメリットが得られる可能性のある場合は、移行を検討することをお勧めします。 小数点以下の桁数が 4 桁を超える値が不要な組織では、移行の必要はありません。

> [!NOTE]
> この機能は現在、二重書き込みを使用する環境でのみサポートされています。
<!--feature detail end -->



## <a name="see-also"></a>関連項目

[二重書き込みの通貨データ型の移行](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/dual-write/currrency-decimal-places)





