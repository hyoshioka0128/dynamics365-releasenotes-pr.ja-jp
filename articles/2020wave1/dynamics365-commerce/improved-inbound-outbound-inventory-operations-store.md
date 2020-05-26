---
title: 店舗における在庫の入庫/出庫の操作の改善
description: この機能は、店舗の在庫入荷プロセスと出庫される移動オーダー出荷プロセスに新しいユーザー インターフェイスと機能強化を提供します。
author: hhainesms
ms.reviewer: josaw
ms.date: 05/04/2020
ms.assetid: 02d60471-0300-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: bf6e2efbd6ed6ca0ce609cee985ebd06a074bcd2
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3349558"
---
# <a name="improved-inbound-and-outbound-inventory-operations-in-store"></a>店舗における在庫の入庫/出庫の操作の改善


| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 3 日| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 5 月 1 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能は、ユーザーによる在庫の入荷や移動オーダーの作成または履行を可能にするために、新しい操作を追加することによって販売時点管理 (POS) アプリケーションを改善します。 これらの新しい操作は、ユーザーの生産性とデータ処理の信頼性を向上させるように設計されています。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能では、店舗在庫の入荷および移動オーダー作成と移動オーダー履行のシナリオに共通のワークフローをサポートする、販売時点管理 (POS) の新しいユーザー インターフェイスが作成されます。  新しい**入庫操作**および新しい**出庫操作**を画面レイアウトに追加できるようになります。 これらにより既存の**ピッキング/入荷** POS 操作を置き換える必要があります。

新しい操作には、関連する入庫/出庫ドキュメント上の品目を表示する簡単な方法を提供する、バーコード スキャン用に最適化されたユーザー インターフェイスがあります。 POS から Commerce Headquarters (HQ) に領収書または出荷を転記するときの円滑な処理とエラー処理を保証するために入力データを強化および検証するための機能も追加されます。  

非同期ドキュメント フレームワークも追加されました。 このフレームワークにより、ユーザーは領収書または出庫する移動出荷を HQ に転記して効率的に処理できるようになります。 この機能により、ユーザーが大きなドキュメントを HQ に転記しようとしたときにピッキング/入荷操作で以前に発生していたタイムアウトの問題や処理エラーが解消されます。

この機能は Commerce バージョン 10.0.9 のサンドボックス/トレーニング環境でプレビューおよび使用できます。 Commerce バージョン 10.0.10 ではさらに安定化されます。 バージョン 10.0.10 より後の運用環境では、これらの新しい操作を POS レイアウトに追加することを検討することをお勧めします。  従来の**ピッキング/入荷**操作は製品の投資分野ではなくなるため、**ピッキング/入荷**操作から**入庫**および**出庫**操作に移行することをお勧めします。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

<!--docs start-->
[Commerce のドキュメント](https://docs.microsoft.com/dynamics365/commerce/) (ドキュメント)
<!--docs end-->
