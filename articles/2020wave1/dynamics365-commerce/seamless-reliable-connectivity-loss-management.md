---
title: シームレスで信頼性の高い接続損失管理
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 01/11/2020
ms.assetid: 833937ea-c8fa-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: 63a25409c992905f134f6ec7178450cfb7202c45
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986637"
---
# <a name="seamless-and-reliable-connectivity-loss-management"></a>シームレスで信頼性の高い接続損失管理
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| 有効対象    |  パブリック プレビュー | 一般提供 | 
| ---------- | :----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|2020 年 5 月| 2020 年 7 月|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Microsoft のリアルタイム トランザクション サービス (RTS) コンポーネントは、さまざまなチャネル (POS (Point of Sale) や 電子商取引など) にサービスを提供する Commerce Server (旧 Retail サーバー) と Commerce Headquarters 間の主要な接続ポイントです。

いくつかのパフォーマンスと信頼性のシナリオでは、信頼性を最大化するための追加ロジックにより改善が可能です。 焦点となるのは、必要なときに有意義なメッセージを提供し、可能な限りシームレスに機能することです。
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
この機能には、次の領域でのいくつかの独立した改善が含まれます。

- Commerce Server (旧 Retail サーバー) にシステム上の問題がある場合は、シームレスな Modern POS (MPOS) オフラインをトリガーします。 たとえば、チャネル DB がダウンした場合にオフライン機能をトリガーします。

- シームレスなオフラインの可用性の設計を改善し、信頼性を高めます。

- デバイスの現在のステータスの詳細を示すダッシュボードの詳細を Headquarters に追加します。
<!--feature detail end -->









