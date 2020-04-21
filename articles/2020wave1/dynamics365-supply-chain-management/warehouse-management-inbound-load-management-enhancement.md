---
title: 倉庫管理 – 入庫積荷管理の機能強化
description: ''
author: relnotes
ms.reviewer: kamaybac
ms.date: 02/28/2020
ms.assetid: 3ba85dcc-b159-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: 4ffa2243f5f020989b547310a55ed2330f978b12
ms.sourcegitcommit: 2928661abcc468748ffc7c33516ebc8e3cd5d653
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/04/2020
ms.locfileid: "3099211"
---
# <a name="warehouse-management--inbound-load-management-enhancement"></a>倉庫管理 – 入庫積荷管理の機能強化
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 4 月| 2020 年 5 月|


## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能は以下で構成されます。

-  倉庫モバイル デバイスから入庫を行う際の、発注書在庫トランザクション (Inventtrans) と貨物 ID の新しい関連付け。 
- 発注書の未積み込み数量の計算に関する機能強化。登録された数量が使用されるようになりました。
- 入庫積荷の倉庫処理操作の更新。 この機能は、"積荷あたり複数の製品受領転記" と呼ばれます。 同じ積荷に対して複数の製品受領転記が可能になり、積荷受領プロセスの柔軟性が向上します。 これにより倉庫管理者は、積荷に対して_製品受領書の更新_ジョブを実行した後もその積荷をオープン状態のままにでき、同じ積荷に対して追加の数量登録を実行できるようになります。 その後、製品受領が元帳に対して継続的に更新されます。

これらの機能強化により、ISV は積荷エンティティと統合するときに、より堅牢なソリューションを構築できます。
<!--feature detail end -->









