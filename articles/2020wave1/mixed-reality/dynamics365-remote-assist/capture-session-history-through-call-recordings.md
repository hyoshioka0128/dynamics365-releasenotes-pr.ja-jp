---
title: 通話記録を介してセッション履歴をキャプチャする
description: 通話記録を介してセッション履歴をキャプチャする
author: relnotes
ms.reviewer: krbjoran
ms.date: 04/02/2020
ms.assetid: 07e22fe0-071b-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: xolee
dynamics365pdf: true
ms.openlocfilehash: ad8ce7f95cb4d8493fe0db02577afb0fc410f47a
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3218646"
---
# <a name="capture-session-history-through-call-recordings"></a><span data-ttu-id="eb55f-103">通話記録を介してセッション履歴をキャプチャする</span><span class="sxs-lookup"><span data-stu-id="eb55f-103">Capture session history through call recordings</span></span>


| <span data-ttu-id="eb55f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="eb55f-104">Enabled for</span></span>    |  <span data-ttu-id="eb55f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="eb55f-105">Public preview</span></span> | <span data-ttu-id="eb55f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="eb55f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="eb55f-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="eb55f-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="eb55f-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="eb55f-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="eb55f-109">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="eb55f-109">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="eb55f-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="eb55f-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="eb55f-111">企業にとって、毎日発生するさまざまなインシデントの記録を保持することが重要です。</span><span class="sxs-lookup"><span data-stu-id="eb55f-111">For businesses, it's important to keep a record of different incidents that happen on a daily basis.</span></span> <span data-ttu-id="eb55f-112">多くの場合、これらの記録は紙の証跡またはテキストベースの関連資料によって保持されます。</span><span class="sxs-lookup"><span data-stu-id="eb55f-112">Oftentimes, these records are kept through paper trails or text-based collateral.</span></span> <span data-ttu-id="eb55f-113">Dynamics 365 Remote Assist セッションでビデオを通じてキャプチャされた情報を活用すると、運用管理者、技術者、およびビジネス上の意思決定者は、後でセッションを参照して、他の技術者のために通話の知識ベースを作成できます。</span><span class="sxs-lookup"><span data-stu-id="eb55f-113">Taking advantage of the information captured through video in a Dynamics 365 Remote Assist session will allow operations managers, technicians, and business decision makers to refer back to sessions later and create a knowledge base of calls for other technicians.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="eb55f-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="eb55f-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="eb55f-115">このリリースでは、次のシナリオが有効になります。</span><span class="sxs-lookup"><span data-stu-id="eb55f-115">In this release, we're enabling the following scenario:</span></span>
 
- <span data-ttu-id="eb55f-116">モバイル向け Dynamics 365 Remote Assist を使用している技術者が、ユーザー間のビデオ録画を通じて、プロセスとサービス コールを包括的に文書化する機能。</span><span class="sxs-lookup"><span data-stu-id="eb55f-116">The ability for technicians using Dynamics 365 Remote Assist for mobile to comprehensively document their processes and service calls through video recordings between users.</span></span> <span data-ttu-id="eb55f-117">この機能は、現在、HoloLens では、グループ通話に使用できます。</span><span class="sxs-lookup"><span data-stu-id="eb55f-117">This feature is available on HoloLens today for group calls.</span></span> 
 

<!--feature detail end -->









