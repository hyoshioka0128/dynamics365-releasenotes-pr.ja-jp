---
title: Dynamics 365 資産管理
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: 11307d1e-5faa-e911-a963-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: arijitba
dynamics365pdf: true
ms.openlocfilehash: 693ddda7de976d1a936e8c68014f2fbe6bda2887
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854286"
---
# <a name="dynamics-365-asset-management"></a><span data-ttu-id="1eec2-102">Dynamics 365 資産管理</span><span class="sxs-lookup"><span data-stu-id="1eec2-102">Dynamics 365 Asset Management</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="1eec2-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="1eec2-103">Enabled for</span></span>    |  <span data-ttu-id="1eec2-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1eec2-104">Public preview</span></span> | <span data-ttu-id="1eec2-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="1eec2-105">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="1eec2-106">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="1eec2-106">End users, automatically</span></span>|<span data-ttu-id="1eec2-107">2019 年 7 月 23 日</span><span class="sxs-lookup"><span data-stu-id="1eec2-107">July 23, 2019</span></span>| <span data-ttu-id="1eec2-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="1eec2-108">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="1eec2-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1eec2-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1eec2-110">この機能は以下を提供します。</span><span class="sxs-lookup"><span data-stu-id="1eec2-110">This functionality provides:</span></span>

- <span data-ttu-id="1eec2-111">資産の障害を減らし、機器の平均寿命を延ばす予防メンテナンス機能による、マシンの有効性の向上。</span><span class="sxs-lookup"><span data-stu-id="1eec2-111">Improved machine effectiveness with preventive maintenance capabilities that reduces asset failure and extended equipment life expectancy.</span></span>

- <span data-ttu-id="1eec2-112">資産のライフサイクル コストを削減する条件ベースのメンテナンス (CBM)。</span><span class="sxs-lookup"><span data-stu-id="1eec2-112">Condition-based Maintenance (CBM), which reduces asset lifecycle costs.</span></span>

- <span data-ttu-id="1eec2-113">顧客が事前に計画するのに役立つ生産実績の可視性の向上。</span><span class="sxs-lookup"><span data-stu-id="1eec2-113">Improved visibility into production performance, which helps customers to plan ahead.</span></span>

- <span data-ttu-id="1eec2-114">インテリジェントな分析により、ユーザーが情報に基づいてデータ主導の意思決定を行えるようにする、ダウンタイムの分析情報。</span><span class="sxs-lookup"><span data-stu-id="1eec2-114">Insight into downtime, with intelligent analytics helping users make informed data-driven decisions.</span></span>

- <span data-ttu-id="1eec2-115">リスクを制限するためのメンテナンス ワークフローの自動管理。</span><span class="sxs-lookup"><span data-stu-id="1eec2-115">Automated management of maintenance workflows to limit risks.</span></span>

- <span data-ttu-id="1eec2-116">資産の品目消費の概要を完全に把握し、それによってメンテナンス プロセスを最適化する、効率的なスペア パーツ管理。</span><span class="sxs-lookup"><span data-stu-id="1eec2-116">Efficient spare parts management, ensuring complete overview of item consumption on assets, thereby optimizing the maintenance process.</span></span>

- <span data-ttu-id="1eec2-117">サイトおよび部門全体の資産の可視性の強化による、生産コストの削減。</span><span class="sxs-lookup"><span data-stu-id="1eec2-117">Reduced production costs via enhanced visibility of assets across sites and departments.</span></span>
<span data-ttu-id="1eec2-118"></span><span class="sxs-lookup"><span data-stu-id="1eec2-118"></span></span>   
- <span data-ttu-id="1eec2-119">リアルタイムの資産財務情報の可視性。</span><span class="sxs-lookup"><span data-stu-id="1eec2-119">Visibility into real-time asset financial information.</span></span>

- <span data-ttu-id="1eec2-120">資産、場所、障害、労働時間、作業指示書の高度なコスト管理。</span><span class="sxs-lookup"><span data-stu-id="1eec2-120">Advanced cost control on assets, locations, faults, work hours, and work orders.</span></span>

- <span data-ttu-id="1eec2-121">メンテナンスの時間外作業、人件費、契約社員のコストの削減。</span><span class="sxs-lookup"><span data-stu-id="1eec2-121">Reduction in maintenance overtime, labor, and contractor costs.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1eec2-122">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1eec2-122">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1eec2-123">Dynamics 365 Asset Management により、顧客はメンテナンス プロセスを最適化し、保守計画、実行、分析を支援できます。</span><span class="sxs-lookup"><span data-stu-id="1eec2-123">Dynamics 365 Asset Management will enable customers to optimize maintenance processes and help with maintenance planning, execution, and analytics.</span></span> <span data-ttu-id="1eec2-124">この機能は、ダウンタイムと全体的なメンテナンス コストの削減に役立ち、Microsoft Dynamics 365 for Finance and Operations の中核部分となります。</span><span class="sxs-lookup"><span data-stu-id="1eec2-124">The functionality will help to reduce downtime and overall maintenance cost, and will be a core part of Microsoft Dynamics 365 for Finance and Operations.</span></span> 
<!--feature detail end -->












## <a name="see-also"></a><span data-ttu-id="1eec2-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="1eec2-125">See also</span></span>

[<span data-ttu-id="1eec2-126">資産管理のプレビュー</span><span class="sxs-lookup"><span data-stu-id="1eec2-126">Asset management preview</span></span>](https://community.dynamics.com/365/financeandoperations/b/dynamics-365-for-finance-and-operations/posts/microsoft-dynamics-365-asset-management-preview)