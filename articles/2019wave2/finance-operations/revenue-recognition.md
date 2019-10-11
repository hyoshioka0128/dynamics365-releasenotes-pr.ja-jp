---
title: 収益認識
description: 収益認識管理は、会計担当者と財務担当者が International Financial Reporting Standard (IFRS) 15 および Accounting Standards Codification (ASC) 606 に準拠するための手順を自動化できるよう支援します。
author: relnotes
ms.reviewer: roschlom
ms.date: 08/07/2019
ms.assetid: a4e50cf1-ada9-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: f187320d56f38a0e27aaf25423265b1f02608d27
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2142847"
---
# <a name="revenue-recognition"></a><span data-ttu-id="d2578-103">収益認識</span><span class="sxs-lookup"><span data-stu-id="d2578-103">Revenue Recognition</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="d2578-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="d2578-104">Enabled for</span></span>    |  <span data-ttu-id="d2578-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d2578-105">Public preview</span></span> | <span data-ttu-id="d2578-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="d2578-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d2578-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="d2578-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="d2578-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="d2578-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="d2578-109">2019 年 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="d2578-109">Aug 5, 2019</span></span>| <span data-ttu-id="d2578-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="d2578-110">Oct 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="d2578-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d2578-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d2578-112">新機能には、次のような製品バンドルとキットのサポートが含まれます。</span><span class="sxs-lookup"><span data-stu-id="d2578-112">New capabilities will include support for product bundles and kits such as:</span></span>

- <span data-ttu-id="d2578-113">ソフトウェアとメンテナンス</span><span class="sxs-lookup"><span data-stu-id="d2578-113">Software and maintenance</span></span>
- <span data-ttu-id="d2578-114">ソフトウェアとサービス</span><span class="sxs-lookup"><span data-stu-id="d2578-114">Software and services</span></span>
- <span data-ttu-id="d2578-115">ソフトウェア</span><span class="sxs-lookup"><span data-stu-id="d2578-115">Software</span></span>
- <span data-ttu-id="d2578-116">ハードウェアとサービス</span><span class="sxs-lookup"><span data-stu-id="d2578-116">Hardware and service</span></span>

<span data-ttu-id="d2578-117">これらの機能は次の機能に対応します。</span><span class="sxs-lookup"><span data-stu-id="d2578-117">These capabilities will handle the following features:</span></span>

- <span data-ttu-id="d2578-118">収益の価格設定</span><span class="sxs-lookup"><span data-stu-id="d2578-118">Revenue pricing</span></span> 
- <span data-ttu-id="d2578-119">収益のスケジュール設定</span><span class="sxs-lookup"><span data-stu-id="d2578-119">Revenue schedules</span></span>
- <span data-ttu-id="d2578-120">バンドルの設定</span><span class="sxs-lookup"><span data-stu-id="d2578-120">Bundle setup</span></span> 
- <span data-ttu-id="d2578-121">複数の販売注文の再割り当て</span><span class="sxs-lookup"><span data-stu-id="d2578-121">Multiple sales order reallocation</span></span>
- <span data-ttu-id="d2578-122">ワークスペースのナビゲーションとレポート作成</span><span class="sxs-lookup"><span data-stu-id="d2578-122">Workspace navigation and reporting</span></span>

## <a name="revenue-pricing"></a><span data-ttu-id="d2578-123">収益の価格設定</span><span class="sxs-lookup"><span data-stu-id="d2578-123">Revenue pricing</span></span>
<span data-ttu-id="d2578-124">ユーザーは自身が認識する価格として、顧客に請求するのとは異なる価格を入力できます。</span><span class="sxs-lookup"><span data-stu-id="d2578-124">Users can enter a different price that they will recognize as different from what they charge the customer.</span></span>

<span data-ttu-id="d2578-125">![収益の価格設定のスクリーンショット](media/revenuepricing.png "収益の価格設定のスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="d2578-125">![Revenue pricing screenshot](media/revenuepricing.png "Revenue pricing screenshot")</span></span>

## <a name="revenue-schedules"></a><span data-ttu-id="d2578-126">収益のスケジュール設定</span><span class="sxs-lookup"><span data-stu-id="d2578-126">Revenue schedules</span></span>
<span data-ttu-id="d2578-127">収益のスケジュールでは、収益を繰り延べる月数を決めることができます。</span><span class="sxs-lookup"><span data-stu-id="d2578-127">Revenue schedules determine the number of months for the revenue deferral.</span></span> <span data-ttu-id="d2578-128">スケジュールは、その月の実際の日付に基づいて作成する、月で均等に分割する、設定した発生回数に基づいて設定することができます。</span><span class="sxs-lookup"><span data-stu-id="d2578-128">Options are available to create the schedule based on actual days of the month, splitting equally across month or based on a set number of occurrences.</span></span>

<span data-ttu-id="d2578-129">![収益のスケジュール設定のスクリーンショット](media/revenueschedules.png "収益のスケジュール設定のスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="d2578-129">![Revenue schedules screenshot](media/revenueschedules.png "Revenue schedule screenshot")</span></span>

## <a name="multiple-sales-order-reallocation"></a><span data-ttu-id="d2578-130">複数の販売注文の再割り当て</span><span class="sxs-lookup"><span data-stu-id="d2578-130">Multiple sales order reallocation</span></span>

<span data-ttu-id="d2578-131">![複数の販売注文の再割り当て](media/multiplesalesorderreallocation.png "複数の販売注文の再割り当て")</span><span class="sxs-lookup"><span data-stu-id="d2578-131">![Multiple sales order reallocation screenshot](media/multiplesalesorderreallocation.png "Multiple sales order reallocation")</span></span>

## <a name="workspace"></a><span data-ttu-id="d2578-132">ワークスペース</span><span class="sxs-lookup"><span data-stu-id="d2578-132">Workspace</span></span> 
<span data-ttu-id="d2578-133">新しいワークスペースは、繰延収益用に作成された収益スケジュールのレコードのステータスを調べるために使用されます。</span><span class="sxs-lookup"><span data-stu-id="d2578-133">The new workspace is used to look at the status of the revenues schedule records created for deferred revenue.</span></span>

<span data-ttu-id="d2578-134">![収益認識ワークスペースのスクリーンショット](media/revenuerecognitionworkspace.png "収益認識ワークスペースのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="d2578-134">![Revenue recognition workspace screenshot](media/revenuerecognitionworkspace.png "Revenue recognition workspace screenshot")</span></span>
<!--feature detail end -->












## <a name="see-also"></a><span data-ttu-id="d2578-135">関連項目</span><span class="sxs-lookup"><span data-stu-id="d2578-135">See also</span></span>

<span data-ttu-id="d2578-136">[収益認識の概要](https://docs.microsoft.com/dynamics365/unified-operations/financials/accounts-receivable/revenue-recognition-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="d2578-136">[Revenue recognition overview](https://docs.microsoft.com/dynamics365/unified-operations/financials/accounts-receivable/revenue-recognition-overview) (docs)</span></span>
