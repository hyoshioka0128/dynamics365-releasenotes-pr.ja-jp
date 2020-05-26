---
title: パートナー向け Application Insights の拡張機能ライフサイクル テレメトリ
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは拡張ライフサイクル イベントに関するテレメトリ (成功または失敗) を Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 04/24/2020
ms.assetid: 2fb3756a-9184-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: c3facbd3b398d1cc9d1aec29abaf3d7ad29ab0a8
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350925"
---
# <a name="extension-lifecycle-telemetry-in-application-insights-for-partners"></a><span data-ttu-id="ba302-103">パートナー向け Application Insights の拡張機能ライフサイクル テレメトリ</span><span class="sxs-lookup"><span data-stu-id="ba302-103">Extension lifecycle telemetry in Application Insights for partners</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="ba302-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ba302-104">Enabled for</span></span>    |  <span data-ttu-id="ba302-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ba302-105">Public preview</span></span> | <span data-ttu-id="ba302-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ba302-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ba302-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="ba302-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ba302-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="ba302-108">Jul 2020</span></span>| <span data-ttu-id="ba302-109">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="ba302-109">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ba302-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ba302-110">Business value</span></span>
<span data-ttu-id="ba302-111">環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは拡張ライフサイクル イベントに関するテレメトリ (成功または失敗) を Application Insights に送信します。</span><span class="sxs-lookup"><span data-stu-id="ba302-111">If a telemetry key for an environment has been specified in the Business Central administration center, the server will emit telemetry about extension lifecycle events (successful or failed) to Application Insights.</span></span>


## <a name="feature-details"></a><span data-ttu-id="ba302-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ba302-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ba302-113">Business Central Server は、拡張ライフサイクル イベントに関するテレメトリ (成功または失敗) を送信します。</span><span class="sxs-lookup"><span data-stu-id="ba302-113">The Business Central server will emit telemetry about extension lifecycle events (successful or failed).</span></span> <span data-ttu-id="ba302-114">操作が失敗した場合、その理由もメッセージに記録されます。</span><span class="sxs-lookup"><span data-stu-id="ba302-114">For failed operations, the reason will be logged in the message as well.</span></span> 

<span data-ttu-id="ba302-115">以下のイベントが発行されます。</span><span class="sxs-lookup"><span data-stu-id="ba302-115">The following events will be emitted:</span></span>

- <span data-ttu-id="ba302-116">拡張機能が同期されました (成功)</span><span class="sxs-lookup"><span data-stu-id="ba302-116">Extension synchronized (success)</span></span>
- <span data-ttu-id="ba302-117">拡張機能が同期されました (失敗)</span><span class="sxs-lookup"><span data-stu-id="ba302-117">Extension synchronized (failure)</span></span>
- <span data-ttu-id="ba302-118">拡張機能がインストールされました (成功)</span><span class="sxs-lookup"><span data-stu-id="ba302-118">Extension installed (success)</span></span>
- <span data-ttu-id="ba302-119">拡張機能がインストールされました (失敗)</span><span class="sxs-lookup"><span data-stu-id="ba302-119">Extension installed (failure)</span></span>
- <span data-ttu-id="ba302-120">拡張機能が更新されました (成功)</span><span class="sxs-lookup"><span data-stu-id="ba302-120">Extension updated (success)</span></span>
- <span data-ttu-id="ba302-121">拡張機能が更新されました (失敗)</span><span class="sxs-lookup"><span data-stu-id="ba302-121">Extension updated (failure)</span></span>
- <span data-ttu-id="ba302-122">拡張機能がアンインストールされました (成功)</span><span class="sxs-lookup"><span data-stu-id="ba302-122">Extension uninstalled (success)</span></span>
- <span data-ttu-id="ba302-123">拡張機能がアンインストールされました (失敗)</span><span class="sxs-lookup"><span data-stu-id="ba302-123">Extension uninstalled (failure)</span></span>
<!--feature detail end -->









