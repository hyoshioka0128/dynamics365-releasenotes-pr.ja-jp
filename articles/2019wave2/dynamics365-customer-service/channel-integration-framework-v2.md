---
title: Dynamics 365 チャネル統合フレームワーク バージョン 2
description: Dynamics 365 チャネル統合フレームワーク バージョン 2
author: relnotes
ms.reviewer: susikka
ms.date: 09/16/2019
ms.assetid: 0c62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: askuma
dynamics365pdf: true
ms.openlocfilehash: 06cdf69ec36a2a4fb30a03cae2080a00c8f5afaf
ms.sourcegitcommit: b0fef00d4f04f2507056a10ecce699767c669119
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2662199"
---
# <a name="dynamics-365-channel-integration-framework-v2"></a>Dynamics 365 チャネル統合フレームワーク バージョン 2
[!include[dynamics365-customer-service banner](../includes/dynamics365-customer-service.md)]

| 有効対象    |  パブリック プレビュー | 早期アクセス | 一般提供 | 
| ---------- | :----------: |:----------: |:----------: |
|エンド ユーザー、管理者/作成者による有効化、またはアナリスト|2019 年 10 月|-| 2020 年 1 月|






## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
チャネル統合フレームワーク バージョン 2.0 で導入された新機能は次のとおりです。

- **顧客サービス用のオムニチャネルのマルチセッション エクスペリエンスとの統合**。
チャネル統合フレームワーク バージョン 2.0 には、顧客サービス用のオムニチャネル アプリのマルチセッション エクスペリエンスと統合するための API が用意されています。 これらの API を使用すると、プロバイダーは受信した会話に関する通知を関連情報とともに表示し、定義済みのテンプレートから会話の新しいセッションを開始して、必要に応じてアプリケーションのタブを開くことができます。 新しいエージェント エクスペリエンスの詳細については、「[顧客サービス用のオムニチャネル アプリを使用するエージェント](https://docs.microsoft.com/dynamics365/customer-engagement/omnichannel/agent/agent-oc/omnichannel-customer-service-app-agent)」を参照してください。

- **会話コントロールのための新しいモードと場所**。
プロバイダーは構築した会話コントロールの最小化モードのエクスペリエンスを定義できます。 エージェントは、コントロールのモードを固定モードから最小化モード、またはその逆に手動で変更できます。 またはプログラムで変更することもできます。

- **複数プロバイダーのサポート**。
チャネル統合フレームワーク バージョン 2.0 を使用して、顧客サービス用のオムニチャネル アプリで複数のプロバイダーを構成できます。 これにより、エージェントは、異なるチャネル (ライブ チャットやテレフォニーなど) 上の異なる顧客に対応する複数のセッション (それぞれ異なるプロバイダーに属するセッション) を同時に処理できます。

> [!NOTE]
> チャネル統合フレームワーク バージョン 1.0 の API を使用して構築されたすべての会話コントロールは引き続き、バージョン 2.0 の顧客サービス ハブなどの単一セッションの統一インターフェイス アプリで動作します。
>
> チャネル統合フレームワークの新機能は、マルチセッション パラダイムをサポートする顧客サービス用のオムニチャネルでのみ使用できます。
<!--feature detail end -->









