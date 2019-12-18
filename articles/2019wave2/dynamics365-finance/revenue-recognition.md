---
title: 収益認識
description: 収益認識管理は、会計担当者と財務担当者が International Financial Reporting Standard (IFRS) 15 および Accounting Standards Codification (ASC) 606 に準拠するための手順を自動化できるよう支援します。
author: relnotes
ms.reviewer: roschlom
ms.date: 11/15/2019
ms.assetid: a4e50cf1-ada9-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: d3b8b5545ad72708290dba8b07991a442b22aadc
ms.sourcegitcommit: cf8b2ba74d2b553c2a721942221c285ffcf184c5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892749"
---
# <a name="revenue-recognition"></a><span data-ttu-id="c6c06-103">収益認識</span><span class="sxs-lookup"><span data-stu-id="c6c06-103">Revenue Recognition</span></span>


| <span data-ttu-id="c6c06-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c6c06-104">Enabled for</span></span>    |  <span data-ttu-id="c6c06-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c6c06-105">Public preview</span></span> | <span data-ttu-id="c6c06-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c6c06-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c6c06-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="c6c06-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c6c06-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c6c06-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c6c06-109">2019 年 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="c6c06-109">Aug 5, 2019</span></span>| <span data-ttu-id="c6c06-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c6c06-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c6c06-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c6c06-111">Oct 1, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="c6c06-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c6c06-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c6c06-113">新機能には、次のような製品バンドルとキットのサポートが含まれます。</span><span class="sxs-lookup"><span data-stu-id="c6c06-113">New capabilities will include support for product bundles and kits such as:</span></span>

- <span data-ttu-id="c6c06-114">ソフトウェアとメンテナンス</span><span class="sxs-lookup"><span data-stu-id="c6c06-114">Software and maintenance</span></span>
- <span data-ttu-id="c6c06-115">ソフトウェアとサービス</span><span class="sxs-lookup"><span data-stu-id="c6c06-115">Software and services</span></span>
- <span data-ttu-id="c6c06-116">ソフトウェア</span><span class="sxs-lookup"><span data-stu-id="c6c06-116">Software</span></span>
- <span data-ttu-id="c6c06-117">ハードウェアとサービス</span><span class="sxs-lookup"><span data-stu-id="c6c06-117">Hardware and service</span></span>

<span data-ttu-id="c6c06-118">これらの機能は次の機能に対応します。</span><span class="sxs-lookup"><span data-stu-id="c6c06-118">These capabilities will handle the following features:</span></span>

- <span data-ttu-id="c6c06-119">収益の価格設定</span><span class="sxs-lookup"><span data-stu-id="c6c06-119">Revenue pricing</span></span> 
- <span data-ttu-id="c6c06-120">収益スケジュール</span><span class="sxs-lookup"><span data-stu-id="c6c06-120">Revenue schedules</span></span>
- <span data-ttu-id="c6c06-121">バンドルの設定</span><span class="sxs-lookup"><span data-stu-id="c6c06-121">Bundle setup</span></span> 
- <span data-ttu-id="c6c06-122">複数の販売注文の再配賦</span><span class="sxs-lookup"><span data-stu-id="c6c06-122">Multiple sales order reallocation</span></span>
- <span data-ttu-id="c6c06-123">ワークスペースのナビゲーションとレポート作成</span><span class="sxs-lookup"><span data-stu-id="c6c06-123">Workspace navigation and reporting</span></span>

### <a name="revenue-pricing"></a><span data-ttu-id="c6c06-124">収益の価格設定</span><span class="sxs-lookup"><span data-stu-id="c6c06-124">Revenue pricing</span></span>
<span data-ttu-id="c6c06-125">ユーザーは自身が認識する価格として、顧客に請求するのとは異なる価格を入力できます。</span><span class="sxs-lookup"><span data-stu-id="c6c06-125">Users can enter a different price that they will recognize as different from what they charge the customer.</span></span>

<span data-ttu-id="c6c06-126">![収益の価格設定](media/revenuepricing.png "収益の価格設定")</span><span class="sxs-lookup"><span data-stu-id="c6c06-126">![Revenue pricing](media/revenuepricing.png "Revenue pricing")</span></span>

### <a name="revenue-schedules"></a><span data-ttu-id="c6c06-127">収益スケジュール</span><span class="sxs-lookup"><span data-stu-id="c6c06-127">Revenue schedules</span></span>
<span data-ttu-id="c6c06-128">収益スケジュールでは、収益を繰り延べる月数を決めることができます。</span><span class="sxs-lookup"><span data-stu-id="c6c06-128">Revenue schedules determine the number of months for the revenue deferral.</span></span> <span data-ttu-id="c6c06-129">スケジュールは、その月の実際の日付に基づいて作成する、月で均等に分割する、設定した発生回数に基づいて設定することができます。</span><span class="sxs-lookup"><span data-stu-id="c6c06-129">Options are available to create the schedule based on actual days of the month, splitting equally across month or based on a set number of occurrences.</span></span>

<span data-ttu-id="c6c06-130">![収益スケジュール](media/revenueschedules.png "収益スケジュール")</span><span class="sxs-lookup"><span data-stu-id="c6c06-130">![Revenue schedules](media/revenueschedules.png "Revenue schedule")</span></span>

### <a name="multiple-sales-order-reallocation"></a><span data-ttu-id="c6c06-131">複数の販売注文の再配賦</span><span class="sxs-lookup"><span data-stu-id="c6c06-131">Multiple sales order reallocation</span></span>

<span data-ttu-id="c6c06-132">![複数の販売注文の再配賦](media/multiplesalesorderreallocation.png "複数の販売注文の再配賦")</span><span class="sxs-lookup"><span data-stu-id="c6c06-132">![Multiple sales order reallocation](media/multiplesalesorderreallocation.png "Multiple sales order reallocation")</span></span>

### <a name="workspace"></a><span data-ttu-id="c6c06-133">ワークスペース</span><span class="sxs-lookup"><span data-stu-id="c6c06-133">Workspace</span></span> 
<span data-ttu-id="c6c06-134">新しいワークスペースは、繰延収益用に作成された収益スケジュールのレコードのステータスを調べるために使用されます。</span><span class="sxs-lookup"><span data-stu-id="c6c06-134">The new workspace is used to look at the status of the revenues schedule records created for deferred revenue.</span></span>

<span data-ttu-id="c6c06-135">![収益認識ワークスペース](media/revenuerecognitionworkspace.png "収益認識ワークスペース")</span><span class="sxs-lookup"><span data-stu-id="c6c06-135">![Revenue recognition workspace](media/revenuerecognitionworkspace.png "Revenue recognition workspace")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="c6c06-136">関連項目</span><span class="sxs-lookup"><span data-stu-id="c6c06-136">See also</span></span>

<span data-ttu-id="c6c06-137">[収益認識の概要](https://docs.microsoft.com/dynamics365/unified-operations/financials/accounts-receivable/revenue-recognition-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c6c06-137">[Revenue recognition overview](https://docs.microsoft.com/dynamics365/unified-operations/financials/accounts-receivable/revenue-recognition-overview) (docs)</span></span>
