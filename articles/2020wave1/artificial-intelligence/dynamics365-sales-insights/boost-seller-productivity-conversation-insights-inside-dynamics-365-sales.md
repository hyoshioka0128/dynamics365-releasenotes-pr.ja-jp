---
title: Dynamics 365 Sales から会話の分析情報を取得して販売担当者の生産性を高める
description: 再生、トランスクリプト、アクション項目、トピック、キーワード、ブランドへの言及、会話 KPI、センチメント分析など、Dynamics 365 Sales の電話活動で通話の概要を見ることができます。
author: relnotes
ms.reviewer: udag
ms.date: 04/24/2020
ms.assetid: 3a7ba790-35cb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: ereza
dynamics365pdf: true
ms.openlocfilehash: f1ab85a77f2bf8b3b255d7ce7e42f55288df0ee9
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294536"
---
# <a name="boost-seller-productivity-with-conversation-insights-inside-dynamics-365-sales"></a><span data-ttu-id="bbbd7-103">Dynamics 365 Sales から会話の分析情報を取得して販売担当者の生産性を高める</span><span class="sxs-lookup"><span data-stu-id="bbbd7-103">Boost seller productivity with conversation insights inside Dynamics 365 Sales</span></span>


| <span data-ttu-id="bbbd7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="bbbd7-104">Enabled for</span></span>    |  <span data-ttu-id="bbbd7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="bbbd7-105">Public preview</span></span> | <span data-ttu-id="bbbd7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="bbbd7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="bbbd7-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="bbbd7-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="bbbd7-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="bbbd7-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="bbbd7-109">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="bbbd7-109">Apr 1, 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="bbbd7-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="bbbd7-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="bbbd7-111">販売担当者は、顧客と電話で話した後で、わかったことと次のステップをまとめるために、平均 8 分を費やします。</span><span class="sxs-lookup"><span data-stu-id="bbbd7-111">Sellers spend an average of 8 minutes after every customer call summarizing what they learned and the next steps.</span></span> <span data-ttu-id="bbbd7-112">多くの場合、これらの学んだことは Dynamics 365 Sales 内には取り込まれません。</span><span class="sxs-lookup"><span data-stu-id="bbbd7-112">Often these learnings are not captured within Dynamics 365 Sales.</span></span> <span data-ttu-id="bbbd7-113">複数の販売担当者が 1 つの営業案件の作業を共同で行っている場合、顧客とのすべての会話が全員に公開されることが重要です。</span><span class="sxs-lookup"><span data-stu-id="bbbd7-113">When multiple sellers are jointly working on a shared opportunity, it is critical that everyone has exposure to all customer conversations.</span></span> 

<span data-ttu-id="bbbd7-114">2020 年リリース ウェーブ 1 では、アクション項目、話し合ったトピック、通話の再生を含む完全な通話の概要を、Dynamics 365 Sales の通話アクティビティ ログで直接確認できます。</span><span class="sxs-lookup"><span data-stu-id="bbbd7-114">In 2020 release wave 1, a complete call summary including action items, topics discussed, and call playback, are available directly within Dynamics 365 Sales phone call activity logs.</span></span> <span data-ttu-id="bbbd7-115">会話インテリジェンスを使用してこれらの学んだことを自動的に取り込むことにより、販売担当者は顧客のニーズに集中することができます。</span><span class="sxs-lookup"><span data-stu-id="bbbd7-115">Capturing these learnings automatically with Conversational Intelligence enables a seller to focus their time on customer needs.</span></span> <span data-ttu-id="bbbd7-116">さらに、セールス イネーブルメント マネージャーは、販売スタジオを使用して販売担当者向けの販売ガイダンスと分析情報を作成できます。</span><span class="sxs-lookup"><span data-stu-id="bbbd7-116">Additionally, sales enablement managers can create sales guidance and insights for sellers using Sales Studio.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="bbbd7-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="bbbd7-117">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="bbbd7-118">**会話に簡単にアクセスする**: 再生、トランスクリプト、アクション項目、トピック、キーワード、ブランドへの言及、会話 KPI、センチメント分析など、Dynamics 365 Sales の電話活動で通話の概要を見ることができます。</span><span class="sxs-lookup"><span data-stu-id="bbbd7-118">**Easy access to conversations**: View call summary within Dynamics 365 Sales phone call activity including playback, transcript, action items, topics, keywords, brand mentions, conversation KPIs, and sentiment analyses.</span></span>
- <span data-ttu-id="bbbd7-119">**会話の分析情報とハイライトにアクセスする**: 再生、キーワード、センチメント、競合する言及、会話 KPI、アクション項目を簡単に見ることができます。</span><span class="sxs-lookup"><span data-stu-id="bbbd7-119">**Access to conversational insights and highlights**: Easily view playback, keywords, sentiment, compete mentions, conversational KPIs, and action items.</span></span> 
- <span data-ttu-id="bbbd7-120">**次善のアクションと強調された情報を作成する**: Dynamics 365 Sales 内で利用可能な会話データに、Dynamics 365 アシスタント スタジオから簡単にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="bbbd7-120">**Create the next best actions and highlighted information**: Conversational data available within Dynamics 365 Sales is easily accessible via Dynamics 365 Assistant Studio.</span></span>
<!--feature detail end -->









