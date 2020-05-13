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
# <a name="dynamics-365-channel-integration-framework-v2"></a><span data-ttu-id="a6cdc-103">Dynamics 365 チャネル統合フレームワーク バージョン 2</span><span class="sxs-lookup"><span data-stu-id="a6cdc-103">Dynamics 365 Channel Integration Framework v2</span></span>


| <span data-ttu-id="a6cdc-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a6cdc-104">Enabled for</span></span>    |  <span data-ttu-id="a6cdc-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a6cdc-105">Public preview</span></span> | <span data-ttu-id="a6cdc-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="a6cdc-106">Early access</span></span> | <span data-ttu-id="a6cdc-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="a6cdc-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="a6cdc-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a6cdc-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="a6cdc-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a6cdc-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a6cdc-110">2019 年 10 月 24 日</span><span class="sxs-lookup"><span data-stu-id="a6cdc-110">Oct 24, 2019</span></span>|-| <span data-ttu-id="a6cdc-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a6cdc-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a6cdc-112">2020 年 1 月 24 日</span><span class="sxs-lookup"><span data-stu-id="a6cdc-112">Jan 24, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a6cdc-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a6cdc-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a6cdc-114">Dynamics 365 チャネル統合フレームワーク V2 を使うと、既に電話サービス プロバイダーを持っているお客様が、Customer Service 用オムニチャネルにおけるシームレスなエージェント エクスペリエンスにそのプロバイダーを簡単に統合できます。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-114">Dynamics 365 Channel Integration Framework v2 helps customers who already have a telephony provider easily integrate that provider into a seamless agent experience in Omnichannel for Customer Service.</span></span> <span data-ttu-id="a6cdc-115">エージェントは、ツールを切り替えなくても、電話サービス プロバイダーを介して着信した顧客からの電話を処理し、Customer Service 用オムニチャネルのエージェント エクスペリエンスですべての会話要求を取得できます。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-115">Agents can avoid toggling between tools and instead handle customer calls coming in through their telephony provider and take conversation requests all in the agent experience in Omnichannel for Customer Service.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a6cdc-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a6cdc-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a6cdc-117">Dynamics 365 チャネル統合フレームワーク バージョン 2.0 で導入された新機能は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-117">Here are the new features introduced in Dynamics 365 Channel Integration Framework version 2.0:</span></span>

- <span data-ttu-id="a6cdc-118">**Customer Service 用オムニチャネルのマルチセッション エクスペリエンスとの統合。**</span><span class="sxs-lookup"><span data-stu-id="a6cdc-118">**Integration with the multi-session experiences in Omnichannel for Customer Service.**</span></span>

  <span data-ttu-id="a6cdc-119">Dynamics 365 チャネル統合フレームワーク バージョン 2.0 には、Customer Service 用オムニチャネル アプリのマルチセッション エクスペリエンスと統合するための API が用意されています。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-119">Dynamics 365 Channel Integration Framework version 2.0 provides APIs to integrate with the multi-session experiences in the Omnichannel for Customer Service app.</span></span> <span data-ttu-id="a6cdc-120">これらの API を使用すると、プロバイダーは受信した会話に関する通知を関連情報とともに表示し、定義済みのテンプレートから会話の新しいセッションを開始して、必要に応じてアプリケーションのタブを開くことができます。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-120">These APIs allow providers to show notifications on incoming conversations with relevant information, start new sessions for conversations from predefined templates, and open application tabs when needed.</span></span> <span data-ttu-id="a6cdc-121">新しいエージェント エクスペリエンスの詳細については、「[Customer Service 用オムニチャネル アプリを使用するエージェント](https://docs.microsoft.com/dynamics365/customer-engagement/omnichannel/agent/agent-oc/omnichannel-customer-service-app-agent)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-121">For more information about the new agent experience, see [Agents using Omnichannel for Customer Service app](https://docs.microsoft.com/dynamics365/customer-engagement/omnichannel/agent/agent-oc/omnichannel-customer-service-app-agent).</span></span>

- <span data-ttu-id="a6cdc-122">**会話コントロールのための新しいモードと場所。**</span><span class="sxs-lookup"><span data-stu-id="a6cdc-122">**New modes and locations for the conversation control.**</span></span>

  <span data-ttu-id="a6cdc-123">プロバイダーは構築した会話コントロールの最小化モードのエクスペリエンスを定義できます。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-123">Providers can define experiences for the minimized mode of the conversation controls they build.</span></span> <span data-ttu-id="a6cdc-124">エージェントは、コントロールのモードを固定モードから最小化モード、またはその逆に手動で変更できます。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-124">Agents can manually change the mode of the control from docked to minimized and vice versa.</span></span> <span data-ttu-id="a6cdc-125">またはプログラムで変更することもできます。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-125">They can also change them programmatically.</span></span>

- <span data-ttu-id="a6cdc-126">**複数プロバイダーのサポート。**</span><span class="sxs-lookup"><span data-stu-id="a6cdc-126">**Support for multiple providers.**</span></span>

  <span data-ttu-id="a6cdc-127">Dynamics 365 チャネル統合フレームワーク バージョン 2.0 を使用して、Customer Service 用オムニチャネル アプリで複数のプロバイダーを構成できます。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-127">Using Dynamics 365 Channel Integration Framework version 2.0, organizations can configure multiple providers in the Omnichannel for Customer Service app.</span></span> <span data-ttu-id="a6cdc-128">これにより、エージェントは、異なるチャネル (ライブ チャットやテレフォニーなど) 上の異なる顧客に対応する複数のセッション (それぞれ異なるプロバイダーに属するセッション) を同時に処理できます。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-128">This enables agents to simultaneously work on multiple sessions that cater to different customers on different channels (for example, live chat and telephony), where each of these sessions belongs to different providers.</span></span>

> [!NOTE]
> <span data-ttu-id="a6cdc-129">Dynamics 365 チャネル統合フレームワーク バージョン 1.0 の API を使用して構築されたすべての会話コントロールは引き続き、バージョン 2.0 の顧客サービス ハブなどの単一セッションの統一インターフェイス アプリで動作します。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-129">All conversation controls built using the APIs of Dynamics 365 Channel Integration Framework version 1.0 will continue to work with version 2.0 in the single-session Unified Interface apps, such as Customer Service Hub.</span></span>
>
> <span data-ttu-id="a6cdc-130">Dynamics 365 チャネル統合フレームワークの新機能は、マルチセッション パラダイムをサポートする Customer Service 用オムニチャネルでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="a6cdc-130">The new capabilities of Dynamics 365 Channel Integration Framework are available only with the Omnichannel for Customer Service app, which supports the multi-session paradigm.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="a6cdc-131">関連項目</span><span class="sxs-lookup"><span data-stu-id="a6cdc-131">See also</span></span>

<span data-ttu-id="a6cdc-132">[チャネル統合フレームワーク](https://docs.microsoft.com/dynamics365/customer-service/channel-integration-framework/v2/overview-channel-integration-framework) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="a6cdc-132">[Channel Integration Framework](https://docs.microsoft.com/dynamics365/customer-service/channel-integration-framework/v2/overview-channel-integration-framework) (docs)</span></span>
