---
title: Dynamics 365 チャネル統合フレームワーク バージョン 2
description: Dynamics 365 チャネル統合フレームワーク バージョン 2
author: relnotes
ms.reviewer: susikka
ms.date: 11/15/2019
ms.assetid: 0c62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: askuma
dynamics365pdf: true
ms.openlocfilehash: a1e21ac68de8615367e5ccb1a326f34b314f757c
ms.sourcegitcommit: b18d8ef2595c1298c94fe6a6fd1fceaa16bd9561
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/06/2019
ms.locfileid: "2893679"
---
# <a name="dynamics-365-channel-integration-framework-v2"></a><span data-ttu-id="e2686-103">Dynamics 365 チャネル統合フレームワーク バージョン 2</span><span class="sxs-lookup"><span data-stu-id="e2686-103">Dynamics 365 Channel Integration Framework v2</span></span>
[!include[dynamics365-customer-service banner](../includes/dynamics365-customer-service.md)]

| <span data-ttu-id="e2686-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="e2686-104">Enabled for</span></span>    |  <span data-ttu-id="e2686-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e2686-105">Public preview</span></span> | <span data-ttu-id="e2686-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="e2686-106">Early access</span></span> | <span data-ttu-id="e2686-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="e2686-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="e2686-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="e2686-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="e2686-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e2686-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e2686-110">2019 年 10 月 24 日</span><span class="sxs-lookup"><span data-stu-id="e2686-110">Oct 24, 2019</span></span>|-| <span data-ttu-id="e2686-111">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="e2686-111">Jan 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="e2686-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e2686-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e2686-113">チャネル統合フレームワーク バージョン 2.0 で導入された新機能は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="e2686-113">Here are the new features introduced in Channel Integration Framework version 2.0:</span></span>

- <span data-ttu-id="e2686-114">**顧客サービス用のオムニチャネルのマルチセッション エクスペリエンスとの統合。**</span><span class="sxs-lookup"><span data-stu-id="e2686-114">**Integration with the multi-session experiences in Omnichannel for Customer Service.**</span></span>

  <span data-ttu-id="e2686-115">チャネル統合フレームワーク バージョン 2.0 には、顧客サービス用のオムニチャネル アプリのマルチセッション エクスペリエンスと統合するための API が用意されています。</span><span class="sxs-lookup"><span data-stu-id="e2686-115">The Channel Integration Framework version 2.0 provides APIs to integrate with the multi-session experiences in the Omnichannel for Customer Service app.</span></span> <span data-ttu-id="e2686-116">これらの API を使用すると、プロバイダーは受信した会話に関する通知を関連情報とともに表示し、定義済みのテンプレートから会話の新しいセッションを開始して、必要に応じてアプリケーションのタブを開くことができます。</span><span class="sxs-lookup"><span data-stu-id="e2686-116">These APIs allow providers to show notifications on incoming conversations with relevant information, start new sessions for conversations from predefined templates, and open application tabs when needed.</span></span> <span data-ttu-id="e2686-117">新しいエージェント エクスペリエンスの詳細については、「[顧客サービス用のオムニチャネル アプリを使用するエージェント](https://docs.microsoft.com/dynamics365/customer-engagement/omnichannel/agent/agent-oc/omnichannel-customer-service-app-agent)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="e2686-117">For more information about the new agent experience, see [Agents using Omnichannel for Customer Service app](https://docs.microsoft.com/dynamics365/customer-engagement/omnichannel/agent/agent-oc/omnichannel-customer-service-app-agent).</span></span>

- <span data-ttu-id="e2686-118">**会話コントロールのための新しいモードと場所。**</span><span class="sxs-lookup"><span data-stu-id="e2686-118">**New modes and locations for the conversation control.**</span></span>

  <span data-ttu-id="e2686-119">プロバイダーは構築した会話コントロールの最小化モードのエクスペリエンスを定義できます。</span><span class="sxs-lookup"><span data-stu-id="e2686-119">Providers can define experiences for the minimized mode of the conversation controls they build.</span></span> <span data-ttu-id="e2686-120">エージェントは、コントロールのモードを固定モードから最小化モード、またはその逆に手動で変更できます。</span><span class="sxs-lookup"><span data-stu-id="e2686-120">Agents can manually change the mode of the control from docked to minimized and vice versa.</span></span> <span data-ttu-id="e2686-121">またはプログラムで変更することもできます。</span><span class="sxs-lookup"><span data-stu-id="e2686-121">They can also change them programmatically.</span></span>

- <span data-ttu-id="e2686-122">**複数プロバイダーのサポート。**</span><span class="sxs-lookup"><span data-stu-id="e2686-122">**Support for multiple providers.**</span></span>

  <span data-ttu-id="e2686-123">チャネル統合フレームワーク バージョン 2.0 を使用して、顧客サービス用のオムニチャネル アプリで複数のプロバイダーを構成できます。</span><span class="sxs-lookup"><span data-stu-id="e2686-123">Using Channel Integration Framework version 2.0, organizations can configure multiple providers in the Omnichannel for Customer Service app.</span></span> <span data-ttu-id="e2686-124">これにより、エージェントは、異なるチャネル (ライブ チャットやテレフォニーなど) 上の異なる顧客に対応する複数のセッション (それぞれ異なるプロバイダーに属するセッション) を同時に処理できます。</span><span class="sxs-lookup"><span data-stu-id="e2686-124">This enables agents to simultaneously work on multiple sessions that cater to different customers on different channels (for example, live chat and telephony), where each of these sessions belongs to different providers.</span></span>

> [!NOTE]
> <span data-ttu-id="e2686-125">チャネル統合フレームワーク バージョン 1.0 の API を使用して構築されたすべての会話コントロールは引き続き、バージョン 2.0 の顧客サービス ハブなどの単一セッションの統一インターフェイス アプリで動作します。</span><span class="sxs-lookup"><span data-stu-id="e2686-125">All conversation controls built using the APIs of Channel Integration Framework version 1.0 will continue to work with version 2.0 in the single-session Unified Interface apps, such as Customer Service Hub.</span></span>
>
> <span data-ttu-id="e2686-126">チャネル統合フレームワークの新機能は、マルチセッション パラダイムをサポートする顧客サービス用のオムニチャネルでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="e2686-126">The new capabilities of Channel Integration Framework are available only with the Omnichannel for Customer Service app, which supports the multi-session paradigm.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="e2686-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="e2686-127">See also</span></span>

<span data-ttu-id="e2686-128">[チャネル統合フレームワーク](https://docs.microsoft.com/dynamics365/customer-service/channel-integration-framework/overview-channel-integration-framework) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="e2686-128">[Channel Integration Framework](https://docs.microsoft.com/dynamics365/customer-service/channel-integration-framework/overview-channel-integration-framework) (docs)</span></span>
