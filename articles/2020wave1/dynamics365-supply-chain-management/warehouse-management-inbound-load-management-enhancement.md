---
title: 入庫積荷管理の機能強化
description: 入庫積荷管理の機能強化
author: relnotes
ms.reviewer: kamaybac
ms.date: 06/02/2020
ms.assetid: 3ba85dcc-b159-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: 21e2cd09f9c34651a0c4763866d62f9e840950e6
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3440789"
---
# <a name="inbound-load-management-enhancement"></a>入庫積荷管理の機能強化


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 4 月 17 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 5 月 26 日|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能により、発注書に対する入庫積荷の倉庫処理プロセスにいくつかの機能強化が追加されます。 これらの機能強化によって、独立系ソフトウェア ベンダー (ISV) は積荷エンティティと統合するときに、より堅牢なソリューションを構築できます。

### <a name="enhancements-added-in-release-10011"></a>リリース 10.0.11 で追加された機能強化

- _積荷数量の超過入庫_。これにより、入庫積荷数量の超過入庫を許可するか禁止するかを選択できます。 超過入庫は、作業者が選択した積荷の残りの未登録数量 (超過配送率の調整後) を超える数量を入力したときに発生します。 超過入庫の許可を選択する場合でも、終了した (状態が "受入済" である) 積荷に対しては禁止を選択できます。

### <a name="enhancements-added-in-release-10010"></a>リリース 10.0.10 で追加された機能強化

- 倉庫モバイル デバイスから入庫を行う際の、発注書在庫トランザクション (Inventtrans) と積荷 ID の新しい関連付け。 
- 発注書の積荷残数量の計算に対する機能強化。登録済数量が使用されるようになり、_発注書明細行の積荷残数量_の計算が、積荷の登録済数量がマークして表示されるビューに置き換えられました。 
- _積荷あたり複数の製品受領転記_と呼ばれる機能による、入庫積荷の倉庫処理操作の更新。 同じ積荷に対して複数の製品受領転記が可能になり、積荷受領プロセスの柔軟性が向上します。 これにより倉庫管理者は、積荷に対して_製品受領書の更新_ジョブを実行した後もその積荷をオープン状態のままにでき、同じ積荷に対して追加の数量登録を実行できるようになります。 その後、製品受領が元帳に対して継続的に更新されます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[発注書に対する入庫積荷の倉庫処理](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/inbound-load-handling) (ドキュメント)
<!--docs end-->
