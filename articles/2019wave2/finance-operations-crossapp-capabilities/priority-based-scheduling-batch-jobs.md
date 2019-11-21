---
title: バッチ ジョブの優先順位ベースのスケジューリング
description: バッチ ジョブの優先順位ベースのスケジューリング
author: relnotes
ms.reviewer: sericks
ms.date: 08/21/2019
ms.assetid: f462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: peakerbl
dynamics365pdf: true
ms.openlocfilehash: 5c8367da8a10a8b061215212dcd5dc616a862a2f
ms.sourcegitcommit: b5be4afdeec589f0490a82495e8206a2b3aee287
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2668018"
---
# <a name="priority-based-scheduling-for-batch-jobs"></a><span data-ttu-id="7d28e-103">バッチ ジョブの優先順位ベースのスケジューリング</span><span class="sxs-lookup"><span data-stu-id="7d28e-103">Priority-based scheduling for batch jobs</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="7d28e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7d28e-104">Enabled for</span></span>    |  <span data-ttu-id="7d28e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7d28e-105">Public preview</span></span> | <span data-ttu-id="7d28e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7d28e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7d28e-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="7d28e-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="7d28e-108">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="7d28e-108">Nov 2019</span></span>| <span data-ttu-id="7d28e-109">近日発表</span><span class="sxs-lookup"><span data-stu-id="7d28e-109">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="7d28e-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7d28e-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7d28e-111">弾力性とスケーラビリティが緊急に必要とされているため、バッチ処理を処理するためのよりスマートなアプローチが必要です。</span><span class="sxs-lookup"><span data-stu-id="7d28e-111">With the urgent need for elasticity and scalability, a smarter approach to handling batch processing is needed.</span></span> <span data-ttu-id="7d28e-112">さらに、バッチ グループに基づいてバッチ ジョブをバッチ サーバーに割り当てることは、現代のクラウド サービスにおける複雑なビジネス プロセスの要件を満たしません。</span><span class="sxs-lookup"><span data-stu-id="7d28e-112">Additionally, assigning batch jobs to batch servers based on batch groups does not meet the complexity of business-process requirements in a modern cloud service.</span></span> <span data-ttu-id="7d28e-113">お客様は、アプリケーションのインフラストラクチャを気にする必要はなく、ビジネス プロセスに集中できます。</span><span class="sxs-lookup"><span data-stu-id="7d28e-113">Customers do not need to be concerned about their application’s infrastructure—they would rather focus on their business processes.</span></span> 
 
<span data-ttu-id="7d28e-114">これらの理由から、管理者がビジネス プロセスに従ってバッチ ジョブの優先順位を設定できるようにします。バッチ グループを管理する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="7d28e-114">With these reasons in mind, we will enable administrators to prioritize their batch jobs per business process, and they will not need to manage batch groups.</span></span>
<!--feature detail end -->








