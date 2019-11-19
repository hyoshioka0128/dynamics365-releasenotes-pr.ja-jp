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
# <a name="dynamics-365-channel-integration-framework-v2"></a><span data-ttu-id="8cfd2-103">Dynamics 365 チャネル統合フレームワーク バージョン 2</span><span class="sxs-lookup"><span data-stu-id="8cfd2-103">Dynamics 365 Channel Integration Framework v2</span></span>
[!include[dynamics365-customer-service banner](../includes/dynamics365-customer-service.md)]

| <span data-ttu-id="8cfd2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8cfd2-104">Enabled for</span></span>    |  <span data-ttu-id="8cfd2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8cfd2-105">Public preview</span></span> | <span data-ttu-id="8cfd2-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="8cfd2-106">Early access</span></span> | <span data-ttu-id="8cfd2-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="8cfd2-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="8cfd2-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="8cfd2-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="8cfd2-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="8cfd2-109">Oct 2019</span></span>|-| <span data-ttu-id="8cfd2-110">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="8cfd2-110">Jan 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="8cfd2-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8cfd2-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8cfd2-112">チャネル統合フレームワーク バージョン 2.0 で導入された新機能は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-112">Here are the new features introduced in Channel Integration Framework version 2.0:</span></span>

- <span data-ttu-id="8cfd2-113">**顧客サービス用のオムニチャネルのマルチセッション エクスペリエンスとの統合**。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-113">**Integration with the multi-session experiences in Omnichannel for Customer Service**.</span></span>
<span data-ttu-id="8cfd2-114">チャネル統合フレームワーク バージョン 2.0 には、顧客サービス用のオムニチャネル アプリのマルチセッション エクスペリエンスと統合するための API が用意されています。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-114">The Channel Integration Framework version 2.0 provides APIs to integrate with the multi-session experiences in the Omnichannel for Customer Service app.</span></span> <span data-ttu-id="8cfd2-115">これらの API を使用すると、プロバイダーは受信した会話に関する通知を関連情報とともに表示し、定義済みのテンプレートから会話の新しいセッションを開始して、必要に応じてアプリケーションのタブを開くことができます。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-115">These APIs allow providers to show notifications on incoming conversations with relevant information, start new sessions for conversations from predefined templates, and open application tabs when needed.</span></span> <span data-ttu-id="8cfd2-116">新しいエージェント エクスペリエンスの詳細については、「[顧客サービス用のオムニチャネル アプリを使用するエージェント](https://docs.microsoft.com/dynamics365/customer-engagement/omnichannel/agent/agent-oc/omnichannel-customer-service-app-agent)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-116">For more information about the new agent experience, see [Agents using Omnichannel for Customer Service app](https://docs.microsoft.com/dynamics365/customer-engagement/omnichannel/agent/agent-oc/omnichannel-customer-service-app-agent).</span></span>

- <span data-ttu-id="8cfd2-117">**会話コントロールのための新しいモードと場所**。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-117">**New modes and locations for the conversation control**.</span></span>
<span data-ttu-id="8cfd2-118">プロバイダーは構築した会話コントロールの最小化モードのエクスペリエンスを定義できます。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-118">Providers can define experiences for the minimized mode of the conversation controls they build.</span></span> <span data-ttu-id="8cfd2-119">エージェントは、コントロールのモードを固定モードから最小化モード、またはその逆に手動で変更できます。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-119">Agents can manually change the mode of the control from docked to minimized and vice versa.</span></span> <span data-ttu-id="8cfd2-120">またはプログラムで変更することもできます。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-120">They can also change them programmatically.</span></span>

- <span data-ttu-id="8cfd2-121">**複数プロバイダーのサポート**。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-121">**Support for multiple providers**.</span></span>
<span data-ttu-id="8cfd2-122">チャネル統合フレームワーク バージョン 2.0 を使用して、顧客サービス用のオムニチャネル アプリで複数のプロバイダーを構成できます。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-122">Using Channel Integration Framework version 2.0, organizations can configure multiple providers in the Omnichannel for Customer Service app.</span></span> <span data-ttu-id="8cfd2-123">これにより、エージェントは、異なるチャネル (ライブ チャットやテレフォニーなど) 上の異なる顧客に対応する複数のセッション (それぞれ異なるプロバイダーに属するセッション) を同時に処理できます。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-123">This enables agents to simultaneously work on multiple sessions that cater to different customers on different channels (for example, live chat and telephony), where each of these sessions belongs to different providers.</span></span>

> [!NOTE]
> <span data-ttu-id="8cfd2-124">チャネル統合フレームワーク バージョン 1.0 の API を使用して構築されたすべての会話コントロールは引き続き、バージョン 2.0 の顧客サービス ハブなどの単一セッションの統一インターフェイス アプリで動作します。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-124">All conversation controls built using the APIs of Channel Integration Framework version 1.0 will continue to work with version 2.0 in the single-session Unified Interface apps, such as Customer Service Hub.</span></span>
>
> <span data-ttu-id="8cfd2-125">チャネル統合フレームワークの新機能は、マルチセッション パラダイムをサポートする顧客サービス用のオムニチャネルでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="8cfd2-125">The new capabilities of Channel Integration Framework are available only with the Omnichannel for Customer Service app, which supports the multi-session paradigm.</span></span>
<!--feature detail end -->









