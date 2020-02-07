---
title: 通話記録を介してセッション履歴をキャプチャする
description: 通話記録を介してセッション履歴をキャプチャする
author: relnotes
ms.reviewer: krbjoran
ms.date: 01/14/2020
ms.assetid: 07e22fe0-071b-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: hegate
dynamics365pdf: true
ms.openlocfilehash: 664482c69614749a50d83a3c43929ae9a408bd2a
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986580"
---
# <a name="capture-session-history-through-call-recordings"></a><span data-ttu-id="35a03-103">通話記録を介してセッション履歴をキャプチャする</span><span class="sxs-lookup"><span data-stu-id="35a03-103">Capture session history through call recordings</span></span>
[!include[mixed-reality/dynamics365-remote-assist banner](../includes/mixed-reality/dynamics365-remote-assist.md)]

| <span data-ttu-id="35a03-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="35a03-104">Enabled for</span></span>    |  <span data-ttu-id="35a03-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="35a03-105">Public preview</span></span> | <span data-ttu-id="35a03-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="35a03-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="35a03-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="35a03-107">Users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="35a03-108">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="35a03-108">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="35a03-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="35a03-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="35a03-110">企業にとって、毎日発生するさまざまなインシデントの記録を保持することが重要です。</span><span class="sxs-lookup"><span data-stu-id="35a03-110">For businesses, it's important to keep a record of different incidents that happen on a daily basis.</span></span> <span data-ttu-id="35a03-111">多くの場合、これらの記録は紙の証跡またはテキストベースの関連資料によって保持されます。</span><span class="sxs-lookup"><span data-stu-id="35a03-111">Oftentimes, these records are kept through paper trails or text-based collateral.</span></span> <span data-ttu-id="35a03-112">Dynamics 365 Remote Assist セッションでビデオを通じてキャプチャされた情報を活用すると、運用管理者、技術者、およびビジネス上の意思決定者は、後でセッションを参照して、他の技術者のために通話の知識ベースを作成できます。</span><span class="sxs-lookup"><span data-stu-id="35a03-112">Taking advantage of the information captured through video in a Dynamics 365 Remote Assist session will allow operations managers, technicians, and business decision makers to refer back to sessions later and create a knowledge base of calls for other technicians.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="35a03-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="35a03-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="35a03-114">このリリースでは、次のシナリオが有効になります。</span><span class="sxs-lookup"><span data-stu-id="35a03-114">In this release, we're enabling the following scenarios:</span></span>
 
- <span data-ttu-id="35a03-115">モバイル向け Dynamics 365 Remote Assist を使用している技術者が、ユーザー間のビデオ録画を通じて、プロセスとサービス コールを包括的に文書化する機能。</span><span class="sxs-lookup"><span data-stu-id="35a03-115">The ability for technicians using Dynamics 365 Remote Assist for mobile to comprehensively document their processes and service calls through video recordings between users.</span></span> <span data-ttu-id="35a03-116">この機能は、現在、HoloLens では、グループ通話に使用できます。</span><span class="sxs-lookup"><span data-stu-id="35a03-116">This feature is available on HoloLens today for group calls.</span></span> 
 
- <span data-ttu-id="35a03-117">Dynamics 365 Field Service のユーザーが、ビデオ録画を既存の作業指示書に関連付ける機能。</span><span class="sxs-lookup"><span data-stu-id="35a03-117">The ability for Dynamics 365 Field Service users to associate a video recording with an existing work order.</span></span>

<!--feature detail end -->









