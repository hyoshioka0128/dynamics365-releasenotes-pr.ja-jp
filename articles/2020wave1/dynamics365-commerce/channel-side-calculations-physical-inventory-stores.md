---
title: 店舗で利用可能な現物在庫のチャネル側での計算
description: この機能により、POS (販売時点管理) アプリケーションのユーザーは、リアルタイムのサービス呼び出しを使用しなくても、店舗の手持在庫データにアクセスできるようになります。
author: hhainesms
ms.reviewer: josaw
ms.date: 03/24/2020
ms.assetid: 988847a0-0300-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 72d63d72fe8796c1758ba5b13910bf940e501f05
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232585"
---
# <a name="channel-side-calculations-for-available-physical-inventory-for-stores"></a>店舗で利用可能な現物在庫のチャネル側での計算
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 2 月 24 日| 2020 年 5 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
多くの小売業者は、Commerce Headquarters (HQ) にリアルタイム サービス (RTS) コールバックを実行することなく、推定手持店舗在庫の値を取得することを希望します。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
物理的に利用可能な推定手持在庫の値を提供するチャネル側の計算ロジックは、販売時点管理 (POS) アプリケーションの構成に使用できるようになります。 チャネル側の推定在庫計算では、製品使用可能性バッチおよびデータ同期ジョブを通じて、Commerce Headquarters (HQ) からの在庫データの定期的な "同期" が必要になります。 店舗のチャネル データベースでは、Commerce Headquarters (HQ) からこの情報が取得されていないと、店舗に転記された在庫トランザクション (Commerce Headquarters (HQ) から店舗倉庫に対して処理された領収書、棚卸仕訳帳、販売注文など) を把握できない場合があるため、この同期が必要です。

チャネル側の計算では、Commerce Headquarters (HQ) から提供されたデータを使用し、特定の品目の店舗の物理的な在庫に影響を与える可能性のあるチャネル データベース内の未転記の売上または返品トランザクションについてチャネル側のデータ チェックを実行します。 計算ロジックは、店舗在庫、およびその店舗のフルフィルメント グループにリンクされている他の店舗または倉庫の推定手持在庫の値を導き出します。

計算では、利用可能な在庫の推定数のみを割り出します。 Commerce Headquarters (HQ) データベースは在庫マスターではないため、店舗データベースの手持在庫について常に 100% の信頼性を保証することはできません。 Commerce Headquarters (HQ) で店舗の在庫に影響を与えるイベントが発生する場合がありますが、これはチャネル データベースによって認識されない場合があります。

この機能には、トリクル フィード明細転記の使用も必要になります。
<!--feature detail end -->










## <a name="see-also"></a>関連項目


<!--docs start-->
[小売チャネルの引当可能在庫数量の計算](https://docs.microsoft.com/dynamics365/commerce/calculated-inventory-retail-channels) (ドキュメント)
<!--docs end-->

