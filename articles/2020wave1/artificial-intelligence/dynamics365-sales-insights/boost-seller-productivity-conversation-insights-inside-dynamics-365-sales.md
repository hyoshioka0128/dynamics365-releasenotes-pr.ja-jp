---
title: Dynamics 365 Sales から会話の分析情報を取得して販売担当者の生産性を高める
description: ''
author: relnotes
ms.reviewer: udag
ms.date: 09/27/2019
ms.assetid: 3a7ba790-35cb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: ereza
dynamics365pdf: true
ms.openlocfilehash: 4ca388520b65faf54b83ea43030cc1f31784ac15
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986680"
---
# <a name="boost-seller-productivity-with-conversation-insights-inside-dynamics-365-sales"></a><span data-ttu-id="ec2e9-102">Dynamics 365 Sales から会話の分析情報を取得して販売担当者の生産性を高める</span><span class="sxs-lookup"><span data-stu-id="ec2e9-102">Boost seller productivity with conversation insights inside Dynamics 365 Sales</span></span>
[!include[artificial-intelligence/dynamics365-sales-insights banner](../includes/artificial-intelligence/dynamics365-sales-insights.md)]

| <span data-ttu-id="ec2e9-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="ec2e9-103">Enabled for</span></span>    |  <span data-ttu-id="ec2e9-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ec2e9-104">Public preview</span></span> | <span data-ttu-id="ec2e9-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="ec2e9-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ec2e9-106">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="ec2e9-106">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="ec2e9-107">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="ec2e9-107">Apr 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="ec2e9-108">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ec2e9-108">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ec2e9-109">販売担当者は、顧客と電話で話した後で、わかったことと次のステップをまとめるために、平均 8 分を費やします。</span><span class="sxs-lookup"><span data-stu-id="ec2e9-109">Sellers spend an average of 8 minutes after every customer call summarizing what they learned and the next steps.</span></span> <span data-ttu-id="ec2e9-110">多くの場合、これらの学んだことは Dynamics 365 Sales 内には取り込まれません。</span><span class="sxs-lookup"><span data-stu-id="ec2e9-110">Often these learnings are not captured within Dynamics 365 Sales.</span></span> <span data-ttu-id="ec2e9-111">複数の販売担当者が 1 つの営業案件の作業を共同で行っている場合、顧客とのすべての会話が全員に公開されることが重要です。</span><span class="sxs-lookup"><span data-stu-id="ec2e9-111">When multiple sellers are jointly working on a shared opportunity, it is critical that everyone has exposure to all customer conversations.</span></span> 

<span data-ttu-id="ec2e9-112">2020 年リリース ウェーブ 1 では、アクション項目、話し合ったトピック、通話の再生を含む完全な通話の概要を、Dynamics 365 Sales の通話アクティビティ ログで直接確認できます。</span><span class="sxs-lookup"><span data-stu-id="ec2e9-112">In the 2020 release wave 1, a complete call summary including action items, topics discussed, and call playback, are available directly within Dynamics 365 Sales phone call activity logs.</span></span> <span data-ttu-id="ec2e9-113">会話インテリジェンスを使用してこれらの学んだことを自動的に取り込むことにより、販売担当者は顧客のニーズに集中することができます。</span><span class="sxs-lookup"><span data-stu-id="ec2e9-113">Capturing these learnings automatically with Conversational Intelligence enables a seller to focus their time on customer needs.</span></span> <span data-ttu-id="ec2e9-114">さらに、セールス イネーブルメント マネージャーは、販売スタジオを使用して販売担当者向けの販売ガイダンスと分析情報を作成できます。</span><span class="sxs-lookup"><span data-stu-id="ec2e9-114">Additionally, sales enablement managers can create sales guidance and insights for sellers using Sales Studio.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ec2e9-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ec2e9-115">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="ec2e9-116">**会話に簡単にアクセスする**: 再生、トランスクリプト、アクション項目、トピック、キーワード、ブランドへの言及、会話 KPI、センチメント分析など、Dynamics 365 Sales の電話活動で通話の概要を見ることができます。</span><span class="sxs-lookup"><span data-stu-id="ec2e9-116">**Easy access to conversations**: View call summary within Dynamics 365 Sales phone call activity including playback, transcript, action items, topics, keywords, brand mentions, conversation KPIs, and sentiment analyses.</span></span>
- <span data-ttu-id="ec2e9-117">**会話の分析情報とハイライトにアクセスする**: 再生、キーワード、センチメント、競合する言及、会話 KPI、アクション項目を簡単に見ることができます。</span><span class="sxs-lookup"><span data-stu-id="ec2e9-117">**Access to conversational insights and highlights**: Easily view playback, keywords, sentiment, compete mentions, conversational KPIs, and action items.</span></span> 
- <span data-ttu-id="ec2e9-118">**次善のアクションと強調された情報を作成する**: Dynamics 365 Sales 内で利用可能な会話データに、Dynamics 365 Assistant Studio から簡単にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="ec2e9-118">**Create the next best actions and highlighted information**: Conversational data available within Dynamics 365 Sales is easily accessible via Dynamics 365 Assistant Studio.</span></span>
<!--feature detail end -->









