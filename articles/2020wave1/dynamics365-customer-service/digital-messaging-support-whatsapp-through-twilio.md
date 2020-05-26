---
title: Twilio 経由の WhatsApp 向けデジタル メッセージング サポート
description: WhatsApp を通じて顧客に働きかけ、時間のあるときに会話に参加できる利便性を提供します。
author: relnotes
ms.reviewer: nenellim
ms.date: 04/09/2020
ms.assetid: dd7c8885-cfc5-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: srikot
dynamics365pdf: true
ms.openlocfilehash: f035666265f210656cd3697643a538058af57bc3
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273315"
---
# <a name="digital-messaging-support-for-whatsapp-through-twilio"></a><span data-ttu-id="6cc19-103">Twilio 経由の WhatsApp 向けデジタル メッセージング サポート</span><span class="sxs-lookup"><span data-stu-id="6cc19-103">Digital messaging support for WhatsApp through Twilio</span></span>


| <span data-ttu-id="6cc19-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="6cc19-104">Enabled for</span></span>    |  <span data-ttu-id="6cc19-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6cc19-105">Public preview</span></span> | <span data-ttu-id="6cc19-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="6cc19-106">Early access</span></span> | <span data-ttu-id="6cc19-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="6cc19-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="6cc19-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="6cc19-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="6cc19-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6cc19-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6cc19-110">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="6cc19-110">Apr 1, 2020</span></span>|-| -|


## <a name="business-value"></a><span data-ttu-id="6cc19-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="6cc19-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="6cc19-112">企業は、WhatsApp を通じたコミュニケーションを好む顧客へのサービス提供のために WhatsApp メッセージングをサポート チャネルとして提供することで、顧客に幅広いチャネル選択を提供できます。</span><span class="sxs-lookup"><span data-stu-id="6cc19-112">Businesses can offer expanded channel choice to customers by offering WhatsApp messaging as a support channel to service customers who prefer to communicate through WhatsApp.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="6cc19-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6cc19-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6cc19-114">WhatsApp などのソーシャル メッセージング プラットフォームは、企業が顧客と独自のコンテキストでかかわる機会を提供し、シームレスでパーソナライズされた顧客サービス エクスペリエンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="6cc19-114">Social messaging platforms such as WhatsApp give businesses an opportunity to engage with customers in their own context to provide them with a seamless and personalized customer service experience.</span></span> <span data-ttu-id="6cc19-115">WhatsApp は、このリリースの Customer Service 用オムニチャネルで導入されたチャネルです。</span><span class="sxs-lookup"><span data-stu-id="6cc19-115">WhatsApp is a channel introduced in this release of Omnichannel for Customer Service.</span></span> <span data-ttu-id="6cc19-116">これには次の機能があります。</span><span class="sxs-lookup"><span data-stu-id="6cc19-116">It has the following capabilities:</span></span>

-   <span data-ttu-id="6cc19-117">管理者は、**オムニチャネル管理**アプリで WhatsApp チャネルを設定できます。</span><span class="sxs-lookup"><span data-stu-id="6cc19-117">Administrators can configure the WhatsApp channel in the **Omnichannel Administration** app.</span></span>
-   <span data-ttu-id="6cc19-118">顧客は、WhatsApp を通じて企業に連絡し、非同期的なサポートを得ることができます。</span><span class="sxs-lookup"><span data-stu-id="6cc19-118">Customers can reach out to the business through WhatsApp and seek support in an asynchronous nature.</span></span>
-   <span data-ttu-id="6cc19-119">エージェントは、同じ統一された状況依存の生産的な **Customer Service 用オムニチャネル** アプリ インターフェイスを使用して顧客とやり取りし、顧客の問題を解決することができます。</span><span class="sxs-lookup"><span data-stu-id="6cc19-119">Agents can use the same unified, contextual, and productive **Omnichannel for Customer Service** app interface to engage with customers and resolve their issues.</span></span>
-   <span data-ttu-id="6cc19-120">スーパーバイザーとマネージャーは、サポート センターを効率的かつ効果的に運営するのに役立つ充実したレポートにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="6cc19-120">Supervisors and managers can access rich reports to run the support center efficiently and effectively.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="6cc19-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="6cc19-121">See also</span></span>

<!--docs start-->
<span data-ttu-id="6cc19-122">[Twilio を通じて WhatsApp チャネルを構成する](https://docs.microsoft.com/dynamics365/omnichannel/administrator/configure-whatsapp-channel) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="6cc19-122">[Configure a WhatsApp channel through Twilio](https://docs.microsoft.com/dynamics365/omnichannel/administrator/configure-whatsapp-channel) (docs)</span></span>
<!--docs end-->
