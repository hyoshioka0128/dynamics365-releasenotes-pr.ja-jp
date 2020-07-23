---
title: パートナー向け Application Insights の企業ライフサイクル テレメトリ
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは企業ライフサイクル イベントに関するテレメトリ (成功または失敗) を Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 06/08/2020
ms.assetid: 271a38ba-7f84-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 09317ea816ee9b4cc85d918702962d101e027b06
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3487473"
---
# <a name="company-lifecycle-telemetry-in-application-insights-for-partners"></a><span data-ttu-id="a164b-103">パートナー向け Application Insights の企業ライフサイクル テレメトリ</span><span class="sxs-lookup"><span data-stu-id="a164b-103">Company lifecycle telemetry in Application Insights for partners</span></span>


| <span data-ttu-id="a164b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a164b-104">Enabled for</span></span>    |  <span data-ttu-id="a164b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a164b-105">Public preview</span></span> | <span data-ttu-id="a164b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="a164b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a164b-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a164b-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="a164b-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a164b-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a164b-109">2020 年 6 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a164b-109">Jun 1, 2020</span></span>| <span data-ttu-id="a164b-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a164b-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a164b-111">2020 年 6 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a164b-111">Jun 1, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="a164b-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a164b-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a164b-113">Business Central Server は、企業ライフサイクル イベントに関するテレメトリ (成功または失敗) を送信します。</span><span class="sxs-lookup"><span data-stu-id="a164b-113">The Business Central server will emit telemetry about company lifecycle events (successful or failed).</span></span> 

<span data-ttu-id="a164b-114">試行が失敗した場合、その理由もメッセージに記録されます。</span><span class="sxs-lookup"><span data-stu-id="a164b-114">For failed attempts, the reason will be logged in the message as well.</span></span> 

<span data-ttu-id="a164b-115">以下のイベントが発行されます。</span><span class="sxs-lookup"><span data-stu-id="a164b-115">The following events will be emitted:</span></span>

- <span data-ttu-id="a164b-116">会社の作成 (成功)</span><span class="sxs-lookup"><span data-stu-id="a164b-116">Create company (success)</span></span>  
- <span data-ttu-id="a164b-117">会社の作成 (失敗)</span><span class="sxs-lookup"><span data-stu-id="a164b-117">Create company (failure)</span></span>  
- <span data-ttu-id="a164b-118">会社のコピー (成功)</span><span class="sxs-lookup"><span data-stu-id="a164b-118">Copy Company (success)</span></span>  
- <span data-ttu-id="a164b-119">会社のコピー (失敗)</span><span class="sxs-lookup"><span data-stu-id="a164b-119">Copy Company (failure)</span></span>  
- <span data-ttu-id="a164b-120">会社のコピー (キャンセル)</span><span class="sxs-lookup"><span data-stu-id="a164b-120">Copy Company (canceled)</span></span>  
- <span data-ttu-id="a164b-121">会社の削除 (成功)</span><span class="sxs-lookup"><span data-stu-id="a164b-121">Delete Company (success)</span></span>  
- <span data-ttu-id="a164b-122">会社の削除 (失敗)</span><span class="sxs-lookup"><span data-stu-id="a164b-122">Delete Company (failure)</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="a164b-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="a164b-123">See also</span></span>

<!--docs start-->
<span data-ttu-id="a164b-124">[会社のライフサイクル トレース テレメトリの分析](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/telemetry-company-lifecycle-trace) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="a164b-124">[Analyzing Company Lifecycle Trace Telemetry](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/telemetry-company-lifecycle-trace) (docs)</span></span>
<!--docs end-->
