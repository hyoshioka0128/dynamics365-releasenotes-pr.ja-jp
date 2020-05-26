---
title: パートナー向け Application Insights の企業ライフサイクル テレメトリ
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは企業ライフサイクル イベントに関するテレメトリ (成功または失敗) を Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 04/24/2020
ms.assetid: 271a38ba-7f84-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 15da6e34461c35790ebe7ec24b414298768cceea
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294941"
---
# <a name="company-lifecycle-telemetry-in-application-insights-for-partners"></a><span data-ttu-id="64ff1-103">パートナー向け Application Insights の企業ライフサイクル テレメトリ</span><span class="sxs-lookup"><span data-stu-id="64ff1-103">Company lifecycle telemetry in Application Insights for partners</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="64ff1-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="64ff1-104">Enabled for</span></span>    |  <span data-ttu-id="64ff1-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="64ff1-105">Public preview</span></span> | <span data-ttu-id="64ff1-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="64ff1-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="64ff1-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="64ff1-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="64ff1-108">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="64ff1-108">Jun 2020</span></span>| <span data-ttu-id="64ff1-109">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="64ff1-109">Jun 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="64ff1-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="64ff1-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="64ff1-111">Business Central Server は、企業ライフサイクル イベントに関するテレメトリ (成功または失敗) を送信します。</span><span class="sxs-lookup"><span data-stu-id="64ff1-111">The Business Central server will emit telemetry about company lifecycle events (successful or failed).</span></span> 

<span data-ttu-id="64ff1-112">試行が失敗した場合、その理由もメッセージに記録されます。</span><span class="sxs-lookup"><span data-stu-id="64ff1-112">For failed attempts, the reason will be logged in the message as well.</span></span> 

<span data-ttu-id="64ff1-113">以下のイベントが発行されます。</span><span class="sxs-lookup"><span data-stu-id="64ff1-113">The following events will be emitted:</span></span>

- <span data-ttu-id="64ff1-114">会社の作成 (成功)</span><span class="sxs-lookup"><span data-stu-id="64ff1-114">Create company (success)</span></span>  
- <span data-ttu-id="64ff1-115">会社の作成 (失敗)</span><span class="sxs-lookup"><span data-stu-id="64ff1-115">Create company (failure)</span></span>  
- <span data-ttu-id="64ff1-116">会社のコピー (成功)</span><span class="sxs-lookup"><span data-stu-id="64ff1-116">Copy Company (success)</span></span>  
- <span data-ttu-id="64ff1-117">会社のコピー (失敗)</span><span class="sxs-lookup"><span data-stu-id="64ff1-117">Copy Company (failure)</span></span>  
- <span data-ttu-id="64ff1-118">会社のコピー (キャンセル)</span><span class="sxs-lookup"><span data-stu-id="64ff1-118">Copy Company (canceled)</span></span>  
- <span data-ttu-id="64ff1-119">会社の削除 (成功)</span><span class="sxs-lookup"><span data-stu-id="64ff1-119">Delete Company (success)</span></span>  
- <span data-ttu-id="64ff1-120">会社の削除 (失敗)</span><span class="sxs-lookup"><span data-stu-id="64ff1-120">Delete Company (failure)</span></span>  
<!--feature detail end -->









