---
title: バッチ ジョブの優先順位ベースのスケジューリング
description: バッチ ジョブの優先順位ベースのスケジューリング
author: ''
ms.reviewer: sericks
ms.date: 06/18/2019
ms.assetid: f462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: cgarty
dynamics365pdf: true
ms.openlocfilehash: 05a53792749cb6973d8da6920678924dcdd6b3b9
ms.sourcegitcommit: d6ff62c145bfdd7742034a67a29bf75938823eb0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/24/2019
ms.locfileid: "1701700"
---
# <a name="priority-based-scheduling-for-batch-jobs"></a><span data-ttu-id="142f2-103">バッチ ジョブの優先順位ベースのスケジューリング</span><span class="sxs-lookup"><span data-stu-id="142f2-103">Priority-based scheduling for batch jobs</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="142f2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="142f2-104">Enabled for</span></span>    |  <span data-ttu-id="142f2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="142f2-105">Public preview</span></span> | <span data-ttu-id="142f2-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="142f2-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="142f2-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="142f2-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="142f2-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="142f2-108">September 2019</span></span>| <span data-ttu-id="142f2-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="142f2-109">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="142f2-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="142f2-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="142f2-111">弾力性とスケーラビリティが緊急に必要とされているため、バッチ処理を処理するためのよりスマートなアプローチが必要です。</span><span class="sxs-lookup"><span data-stu-id="142f2-111">With the urgent need for elasticity and scalability, a smarter approach to handling batch processing is needed.</span></span> <span data-ttu-id="142f2-112">さらに、バッチ グループに基づいてバッチ ジョブをバッチ サーバーに割り当てることは、現代のクラウド サービスにおける複雑なビジネス プロセスの要件を満たしません。</span><span class="sxs-lookup"><span data-stu-id="142f2-112">Additionally, assigning batch jobs to batch servers based on batch groups does not meet the complexity of business-process requirements in a modern cloud service.</span></span> <span data-ttu-id="142f2-113">お客様は、アプリケーションのインフラストラクチャを気にする必要はなく、ビジネス プロセスに集中できます。</span><span class="sxs-lookup"><span data-stu-id="142f2-113">Customers do not need to be concerned about their application’s infrastructure—they would rather focus on their business processes.</span></span> 
 
<span data-ttu-id="142f2-114">これらの理由から、管理者がビジネス プロセスに従ってバッチ ジョブの優先順位を設定できるようにします。バッチ グループを管理する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="142f2-114">With these reasons in mind, we will enable administrators to prioritize their batch jobs per business process, and they will not need to manage batch groups.</span></span>
<!--feature detail end -->










