---
title: 店舗における在庫の入庫/出庫の操作の改善
description: この機能は、店舗の在庫入荷プロセスと出庫される移動オーダー出荷プロセスに新しいユーザー インターフェイスと機能強化を提供します。
author: hhainesms
ms.reviewer: josaw
ms.date: 02/05/2020
ms.assetid: 02d60471-0300-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 3cf6f2d22d7f586c77b99dd1b9d04201507524e6
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3032311"
---
# <a name="improved-inbound-and-outbound-inventory-operations-in-store"></a>店舗における在庫の入庫/出庫の操作の改善
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 1 月 27 日| 2020 年 5 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能は、在庫の入荷および移動オーダーの作成または履行を可能にする新しい操作の追加によって、販売時点管理 (POS) アプリケーションを改善します。 これらの新しい操作は、ユーザーの生産性とデータ処理の信頼性を向上させるように設計されています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能では、店舗在庫の入荷および移動オーダー作成と移動オーダー履行のシナリオに共通のワークフローをサポートする、POS の新しいユーザー インターフェイスが作成されます。  新しい「入庫操作」と新しい「出庫操作」は、既存の「ピッキング/入荷」POS 操作を置き換えることを目的として画面レイアウトに追加できます。

これらの新しい操作には、バーコード スキャン用に最適化されたユーザー インターフェイスがあり、関連する入庫/出庫ドキュメント上の品目を表示する簡単な方法を提供します。 領収書または出荷を転記するときの円滑な処理とエラー処理を保証するために入力データを強化および検証するための機能も追加されます。  非同期ドキュメント フレームワークも追加されました。このフレームワークにより、領収書または出庫する移動出荷の HQ への転記を効率的に処理できるようになり、大きなドキュメントを HQ に転記しようとしたときに発生するタイムアウトや処理エラーを伴う「ピッキング/入荷」操作で以前に発生していた問題が解消されます。

この機能は 10.0.9 のサンドボックス/トレーニング環境でプレビューおよび使用できます。   10.0.10 ではさらに安定し、10.0.10 より後の運用環境では、POS レイアウトへのこれらの新しい操作の追加を検討することをお勧めします。

<!--feature detail end -->










## <a name="see-also"></a>関連項目

[在庫の入庫と在庫の出庫](https://docs.microsoft.com/dynamics365/commerce/) (ドキュメント)
