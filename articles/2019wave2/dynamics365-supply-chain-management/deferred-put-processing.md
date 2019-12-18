---
title: 遅延プット処理
description: プット プロセスを非同期に設定することができます。 作業明細行の特定のしきい値を超えるとプット処理が遅延されるように、システムをセットアップすることができます。
author: relnotes
ms.reviewer: josaw
ms.date: 11/15/2019
ms.assetid: 7862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: 0159ab92224d5830aa0c5ddeda4b4abc10fb7282
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889686"
---
# <a name="deferred-put-processing"></a>遅延プット処理
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 6 月 5 日| 2020 年 1 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
遅延プット処理により、モバイル デバイスは直ちに解放されて、ユーザーは新しいタスクを処理できます。 また、システムは、プット処理のランダムなピーク時間にも耐性を持つようになります。すべての処理時間はバッチ サーバーによって処理されるため、倉庫の作業者は、プット登録のためのサーバー パフォーマンスの予期しない低下が発生した場合に中断されることなく操作できます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
これは、倉庫作業者の生産性向上に重点を置いたパフォーマンス関連の機能です。 モバイル デバイスが "フリーズ" する原因になる、プット完了のたびのさまざまなインベントリ更新のオンライン処理を行う必要がなく、そのプロセスを非同期的に実行できます。 

倉庫作業者は、一定数の更新を必要とするすべての作業のパフォーマンスが向上します。たとえば、10 明細行を選択するプット登録には、関連する場所の 20 の在庫更新と 10 の元伝票明細行の更新が含まれます。 これらの操作はバッチによって自動化され、システムの負荷はよりバランスがとれたものになります。 倉庫作業者はシステムの散発的またはランダムなピーク使用に依存しなくなります。 

この機能は、一部の顧客でテストできるように提供されます。出荷ドキュメントのマニフェストと印刷などのさまざまなフォローアップ プロセスへの影響を理解する必要があります。
<!--feature detail end -->

![作業処理 ポリシー](media/work-processing-policies.png "作業処理 ポリシー")
<!-- Picture 1 -->









## <a name="see-also"></a>関連項目

[倉庫作業の繰延処理](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/warehousing/deferred-put) (ドキュメント)
