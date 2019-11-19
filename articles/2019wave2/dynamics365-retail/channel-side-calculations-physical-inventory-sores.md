---
title: 店舗で利用可能な現物在庫のチャネル側での計算
description: この機能により、POS (販売時点管理) アプリケーションのユーザーは、リアルタイムのサービス呼び出しを使用しなくても、店舗の手持在庫データにアクセスできるようになります。
author: hhainesms
ms.reviewer: josaw
ms.date: 10/02/2019
ms.assetid: 6663278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 538c556bf8420e931febe088bd94d37b567cb4ad
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2659916"
---
# <a name="channel-side-calculations-for-available-physical-inventory-for-stores"></a>店舗で利用可能な現物在庫のチャネル側での計算
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 11 月| 2020 年 1 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
この機能は、HQ への安定した接続がなく、店舗で利用可能な現物在庫データを表示したい一部のお客様をサポートするものです。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
"利用可能な現物" のチャネル側計算ロジックは、店舗在庫検索関連タスクでの使用のために、小売サーバーに追加されます。 この計算を実行するには、製品使用可能性ジョブを通じて、HQ からの在庫データを定期的に "同期" する必要があります。 店舗のチャネル データベースでは、HQ からこの情報が取得されていないと、店舗に転記された在庫トランザクション (HQ から店舗倉庫に対して処理された領収/棚卸仕訳帳や販売注文など) を把握できない場合があります。

このチャネル側計算は、HQ によって提供されたデータを取得し、店舗のチャネル DB で "利用可能な現物" に影響する可能性がある未転記のトランザクションをチェックした後、必要に応じて在庫を追加/削除して、HQ がまだ把握していないトランザクションを把握するというものです。

この計算は、あくまで利用可能な在庫の推定数を割り出すことを目的としたものです。 ERP/HQ は在庫マスターではないため、常に 100% の信頼性を保証することはできません。店舗在庫に影響を与える事象が HQ で発生した場合に、そのことがチャネル データベースで認識されない可能性もあります。

この機能を正常に動作させるには、トリクル フィード明細転記の使用も必要になります。
<!--feature detail end -->









