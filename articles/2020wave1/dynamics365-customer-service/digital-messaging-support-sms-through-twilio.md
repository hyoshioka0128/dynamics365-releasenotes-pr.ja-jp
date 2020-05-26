---
title: Twilio 経由の SMS 向けデジタル メッセージング サポート
description: SMS を通じて顧客に働きかけ、時間のあるときに会話に参加できる利便性を提供します。
author: relnotes
ms.reviewer: nenellim
ms.date: 04/09/2020
ms.assetid: c5481a05-d0c5-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: srikot
dynamics365pdf: true
ms.openlocfilehash: 33b5737bc2eb6022109524a94ac7cc66152d1b82
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273348"
---
# <a name="digital-messaging-support-for-sms-through-twilio"></a><span data-ttu-id="1bdf9-103">Twilio 経由の SMS 向けデジタル メッセージング サポート</span><span class="sxs-lookup"><span data-stu-id="1bdf9-103">Digital messaging support for SMS through Twilio</span></span>


| <span data-ttu-id="1bdf9-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1bdf9-104">Enabled for</span></span>    |  <span data-ttu-id="1bdf9-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1bdf9-105">Public preview</span></span> | <span data-ttu-id="1bdf9-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="1bdf9-106">Early access</span></span> | <span data-ttu-id="1bdf9-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="1bdf9-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="1bdf9-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="1bdf9-108">End users by admins, makers, or analysts</span></span>|-|-| <span data-ttu-id="1bdf9-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1bdf9-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1bdf9-110">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="1bdf9-110">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1bdf9-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1bdf9-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1bdf9-112">企業は、SMS を通じたコミュニケーションを好む顧客へのサービス提供のためにテキスト メッセージングをサポート チャネルとして提供することで、顧客に幅広いチャネル選択を提供できます。</span><span class="sxs-lookup"><span data-stu-id="1bdf9-112">Businesses can offer expanded channel choice to customers with text messaging as a support channel to service customers who prefer to communicate through SMS.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1bdf9-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1bdf9-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1bdf9-114">SMS チャネルは、組織が顧客とタイムリーに対話し、顧客満足度を高め、エージェントの生産性を向上させ、サポート コストを削減するための便利なツールです。</span><span class="sxs-lookup"><span data-stu-id="1bdf9-114">The SMS channel is a useful tool for organizations to interact with their customers in a timely manner and increase customer satisfaction, improve agent productivity, and reduce support costs.</span></span> <span data-ttu-id="1bdf9-115">以下の機能を利用するには、Twilio との SMS 契約が必要です。</span><span class="sxs-lookup"><span data-stu-id="1bdf9-115">Customers will need an SMS subscription with Twilio to leverage the following capabilities:</span></span>

-   <span data-ttu-id="1bdf9-116">管理者は、**オムニチャネル管理**アプリで Twilio をプロバイダーとして使用して SMS チャネルを設定できます。</span><span class="sxs-lookup"><span data-stu-id="1bdf9-116">Administrators can configure the SMS channel in the **Omnichannel Administration** app using Twilio as a provider.</span></span>
-   <span data-ttu-id="1bdf9-117">顧客は、SMS を通じて企業に連絡し、非同期的なサポートを得ることができます。</span><span class="sxs-lookup"><span data-stu-id="1bdf9-117">Customers can reach out to the business through SMS and seek support in an asynchronous nature.</span></span>
-   <span data-ttu-id="1bdf9-118">エージェントは、同じ統一された状況依存の生産的な **Customer Service 用オムニチャネル** アプリ インターフェイスを使用して顧客とやり取りし、顧客の問題を解決することができます。</span><span class="sxs-lookup"><span data-stu-id="1bdf9-118">Agents can use the same unified, contextual, and productive **Omnichannel for Customer Service** app interface to engage with customers and resolve their issues.</span></span>
-   <span data-ttu-id="1bdf9-119">スーパーバイザーとマネージャーは、サポート センターを効率的かつ効果的に運営するのに役立つ充実したレポートにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="1bdf9-119">Supervisors and managers can access rich reports to run the support center efficiently and effectively.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="1bdf9-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="1bdf9-120">See also</span></span>

<!--docs start-->
<span data-ttu-id="1bdf9-121">[Twilio の SMS チャネルを構成する](https://docs.microsoft.com/dynamics365/omnichannel/administrator/configure-sms-channel-twilio) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="1bdf9-121">[Configure an SMS channel for Twilio](https://docs.microsoft.com/dynamics365/omnichannel/administrator/configure-sms-channel-twilio) (docs)</span></span>
<!--docs end-->
