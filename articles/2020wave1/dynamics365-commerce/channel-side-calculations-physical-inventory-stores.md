---
title: 店舗で利用可能な現物在庫のチャネル側での計算
description: この機能により、POS (販売時点管理) アプリケーションのユーザーは、リアルタイムのサービス呼び出しを使用しなくても、店舗の手持在庫データにアクセスできるようになります。
author: hhainesms
ms.reviewer: josaw
ms.date: 01/28/2020
ms.assetid: 988847a0-0300-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 37c06c554a73ab03b984c0c0ab271dfc9c42c5df
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3031695"
---
# <a name="channel-side-calculations-for-available-physical-inventory-for-stores"></a>店舗で利用可能な現物在庫のチャネル側での計算
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 2 月| 2020 年 5 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
本社 (HQ) にリアルタイム サービス (RTS) コールバックを実行することなく、推定手持店舗在庫の値を取得することを希望する多くの小売業者がいます。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
"利用可能な現物" のチャネル側計算ロジックは、店舗在庫検索関連タスクでの使用のために追加されます。 この計算を実行するには、製品使用可能性ジョブを通じて、HQ からの在庫データを定期的に "同期" する必要があります。 店舗のチャネル データベースでは、HQ からこの情報が取得されていないと、店舗に転記された在庫トランザクション (HQ から店舗倉庫に対して処理された領収書、棚卸仕訳帳、販売注文など) を把握できない場合があります。

このチャネル側計算は、HQ によって提供されたデータを取得し、店舗のチャネル データベースで "利用可能な現物" に影響する可能性がある未転記のトランザクションをチェックした後、必要に応じて在庫を追加または削除して、HQ がまだ把握していないトランザクションを把握するというものです。

この計算は、あくまで利用可能な在庫の推定数を割り出すことを目的としたものです。 HQ データベースは在庫マスターではないため、店舗データベースの手持在庫について常に 100% の信頼性を保証することはできません。 HQ で店舗の在庫に影響を与えるイベントが発生する場合がありますが、これはチャネル データベースによって認識されない場合があります。

この機能を正常に動作させるには、トリクル フィード明細転記の使用も必要になります。
<!--feature detail end -->









