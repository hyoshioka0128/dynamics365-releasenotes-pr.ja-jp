---
title: Dynamics 365 チャネル統合フレームワーク バージョン 2
description: Dynamics 365 チャネル統合フレームワーク バージョン 2
author: relnotes
ms.reviewer: susikka
ms.date: 02/04/2020
ms.assetid: 0c62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: askuma
dynamics365pdf: true
ms.openlocfilehash: bf963d117a7ef3bef1b2081ec64cc274d49ae87e
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3058620"
---
# <a name="dynamics-365-channel-integration-framework-v2"></a>Dynamics 365 チャネル統合フレームワーク バージョン 2


| 有効対象    |  パブリック プレビュー | 早期アクセス | 一般提供 | 
| ---------- | :----------: |:----------: |:----------: |
|エンド ユーザー、管理者/作成者/アナリストによる有効化|![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2019 年 10 月 24 日|-| ![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。") 2020 年 1 月 24 日|


## <a name="business-value"></a>ビジネス バリュー
<!-- bv start -->
Dynamics 365 チャネル統合フレームワーク V2 を使うと、既に電話サービス プロバイダーを持っているお客様が、Customer Service 用オムニチャネルにおけるシームレスなエージェント エクスペリエンスにそのプロバイダーを簡単に統合できます。 エージェントは、ツールを切り替えなくても、電話サービス プロバイダーを介して着信した顧客からの電話を処理し、Customer Service 用オムニチャネルのエージェント エクスペリエンスですべての会話要求を取得できます。 
<!-- bv end -->



## <a name="feature-details"></a>機能の詳細
<!--feature detail start -->
Dynamics 365 チャネル統合フレームワーク バージョン 2.0 で導入された新機能は次のとおりです。

- **Customer Service 用オムニチャネルのマルチセッション エクスペリエンスとの統合。**

  Dynamics 365 チャネル統合フレームワーク バージョン 2.0 には、Customer Service 用オムニチャネル アプリのマルチセッション エクスペリエンスと統合するための API が用意されています。 これらの API を使用すると、プロバイダーは受信した会話に関する通知を関連情報とともに表示し、定義済みのテンプレートから会話の新しいセッションを開始して、必要に応じてアプリケーションのタブを開くことができます。 新しいエージェント エクスペリエンスの詳細については、「[Customer Service 用オムニチャネル アプリを使用するエージェント](https://docs.microsoft.com/dynamics365/customer-engagement/omnichannel/agent/agent-oc/omnichannel-customer-service-app-agent)」を参照してください。

- **会話コントロールのための新しいモードと場所。**

  プロバイダーは構築した会話コントロールの最小化モードのエクスペリエンスを定義できます。 エージェントは、コントロールのモードを固定モードから最小化モード、またはその逆に手動で変更できます。 またはプログラムで変更することもできます。

- **複数プロバイダーのサポート。**

  Dynamics 365 チャネル統合フレームワーク バージョン 2.0 を使用して、Customer Service 用オムニチャネル アプリで複数のプロバイダーを構成できます。 これにより、エージェントは、異なるチャネル (ライブ チャットやテレフォニーなど) 上の異なる顧客に対応する複数のセッション (それぞれ異なるプロバイダーに属するセッション) を同時に処理できます。

> [!NOTE]
> Dynamics 365 チャネル統合フレームワーク バージョン 1.0 の API を使用して構築されたすべての会話コントロールは引き続き、バージョン 2.0 の顧客サービス ハブなどの単一セッションの統一インターフェイス アプリで動作します。
>
> Dynamics 365 チャネル統合フレームワークの新機能は、マルチセッション パラダイムをサポートする Customer Service 用オムニチャネルでのみ使用できます。
<!--feature detail end -->










## <a name="see-also"></a>関連項目

[チャネル統合フレームワーク](https://docs.microsoft.com/dynamics365/customer-service/channel-integration-framework/v2/overview-channel-integration-framework) (ドキュメント)
