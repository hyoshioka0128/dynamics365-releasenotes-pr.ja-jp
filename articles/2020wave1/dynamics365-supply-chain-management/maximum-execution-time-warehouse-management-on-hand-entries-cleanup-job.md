---
title: 倉庫管理の手持在庫エントリのクリーンアップ ジョブの最大実行時間
description: 倉庫管理の手持在庫エントリのクリーンアップ ジョブの機能強化
author: relnotes
ms.reviewer: kamaybac
ms.date: 06/04/2020
ms.assetid: 22aeafda-e18a-ea11-a812-000d3a4e3654
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: 0a257fb70dd8a695c0d1632b9e31d8af81e229e9
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3440888"
---
# <a name="maximum-execution-time-for-the-warehouse-management-on-hand-entries-cleanup-job"></a>倉庫管理の手持在庫エントリのクリーンアップ ジョブの最大実行時間
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 5 月 29 日| 2020 年 7 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能を使用すると、手持在庫エントリのクリーンアップ ジョブの処理に対して許可される最大時間を設定できます。 指定した時間数以内にジョブが完了しない場合は、それまでに完了した作業を保存して終了します。 この機能は、在庫の使用率が高い実装に特に関連しています。 この場合、システムの負荷ができるだけ低いときにジョブが実行されるようにスケジュールする必要があります。 バッチ ジョブが完了するまで実行を継続できるようにするには、値「0」を入力するか、空白のままにします。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[倉庫管理の手持在庫エントリのクリーンアップ ジョブ](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/onhand-cleanup) (ドキュメント)
<!--docs end-->
