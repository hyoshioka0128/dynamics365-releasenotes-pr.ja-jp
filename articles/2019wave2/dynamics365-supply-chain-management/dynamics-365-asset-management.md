---
title: 資産管理
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 10/07/2019
ms.assetid: 11307d1e-5faa-e911-a963-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: arijitba
dynamics365pdf: true
ms.openlocfilehash: 0f07aad0f24bee3cf772951464fd4418c9e35ba6
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660559"
---
# <a name="asset-management-for-dynamics-365-supply-chain-management"></a><span data-ttu-id="1710c-102">Dynamics 365 Supply Chain Management の資産管理</span><span class="sxs-lookup"><span data-stu-id="1710c-102">Asset Management for Dynamics 365 Supply Chain Management</span></span>


| <span data-ttu-id="1710c-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="1710c-103">Enabled for</span></span>    |  <span data-ttu-id="1710c-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1710c-104">Public preview</span></span> | <span data-ttu-id="1710c-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="1710c-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1710c-106">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="1710c-106">End users, automatically</span></span>|<span data-ttu-id="1710c-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1710c-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1710c-108">2019 年 7 月 23 日</span><span class="sxs-lookup"><span data-stu-id="1710c-108">Jul 23, 2019</span></span>| <span data-ttu-id="1710c-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1710c-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1710c-110">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="1710c-110">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="1710c-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1710c-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1710c-112">この機能は以下を提供します。</span><span class="sxs-lookup"><span data-stu-id="1710c-112">This functionality provides:</span></span>

- <span data-ttu-id="1710c-113">資産の障害を減らし、機器の平均寿命を延ばす予防メンテナンス機能による、マシンの有効性の向上。</span><span class="sxs-lookup"><span data-stu-id="1710c-113">Improved machine effectiveness with preventive maintenance capabilities that reduces asset failure and extended equipment life expectancy.</span></span>

- <span data-ttu-id="1710c-114">資産のライフサイクル コストを削減する条件ベースのメンテナンス (CBM)。</span><span class="sxs-lookup"><span data-stu-id="1710c-114">Condition-based maintenance (CBM), which reduces asset lifecycle costs.</span></span>

- <span data-ttu-id="1710c-115">顧客が事前に計画するのに役立つ生産実績の可視性の向上。</span><span class="sxs-lookup"><span data-stu-id="1710c-115">Improved visibility into production performance, which helps customers to plan ahead.</span></span>

- <span data-ttu-id="1710c-116">インテリジェントな分析により、ユーザーが情報に基づいてデータ主導の意思決定を行えるようにする、ダウンタイムの分析情報。</span><span class="sxs-lookup"><span data-stu-id="1710c-116">Insight into downtime, with intelligent analytics helping users make informed data-driven decisions.</span></span>

- <span data-ttu-id="1710c-117">リスクを制限するためのメンテナンス ワークフローの自動管理。</span><span class="sxs-lookup"><span data-stu-id="1710c-117">Automated management of maintenance workflows to limit risks.</span></span>

- <span data-ttu-id="1710c-118">資産の品目消費の概要を完全に把握し、それによってメンテナンス プロセスを最適化する、効率的なスペア パーツ管理。</span><span class="sxs-lookup"><span data-stu-id="1710c-118">Efficient spare parts management, ensuring complete overview of item consumption on assets, thereby optimizing the maintenance process.</span></span>

- <span data-ttu-id="1710c-119">サイトおよび部門全体の資産の可視性の強化による、生産コストの削減。</span><span class="sxs-lookup"><span data-stu-id="1710c-119">Reduced production costs via enhanced visibility of assets across sites and departments.</span></span>
<span data-ttu-id="1710c-120"></span><span class="sxs-lookup"><span data-stu-id="1710c-120"></span></span>   
- <span data-ttu-id="1710c-121">リアルタイムの資産財務情報の可視性。</span><span class="sxs-lookup"><span data-stu-id="1710c-121">Visibility into real-time asset financial information.</span></span>

- <span data-ttu-id="1710c-122">資産、場所、障害、労働時間、作業指示書の高度なコスト管理。</span><span class="sxs-lookup"><span data-stu-id="1710c-122">Advanced cost control on assets, locations, faults, work hours, and work orders.</span></span>

- <span data-ttu-id="1710c-123">メンテナンスの時間外作業、人件費、契約社員のコストの削減。</span><span class="sxs-lookup"><span data-stu-id="1710c-123">Reduction in maintenance overtime, labor, and contractor costs.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1710c-124">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1710c-124">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1710c-125">Dynamics 365 Supply Chain Management の資産管理を使用すると、メンテナンス プロセスを最適化し、保守計画、実行、分析の有効性を改善することができます。</span><span class="sxs-lookup"><span data-stu-id="1710c-125">Asset Management for Dynamics 365 Supply Chain Management will enable customers to optimize maintenance processes and help with maintenance planning, execution, and analytics.</span></span> <span data-ttu-id="1710c-126">この機能は、ダウンタイムと全体的なメンテナンス コストの削減に役立ち、Finance and Operations クロス アプリ機能の中核部分となります。</span><span class="sxs-lookup"><span data-stu-id="1710c-126">The functionality will help to reduce downtime and overall maintenance cost, and will be a core part of Finance and Operations cross-app capabilities.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="1710c-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="1710c-127">See also</span></span>

<span data-ttu-id="1710c-128">[資産管理プレビュー](https://community.dynamics.com/365/financeandoperations/b/dynamics-365-for-finance-and-operations/posts/microsoft-dynamics-365-asset-management-preview) (ブログ)</span><span class="sxs-lookup"><span data-stu-id="1710c-128">[Asset management preview](https://community.dynamics.com/365/financeandoperations/b/dynamics-365-for-finance-and-operations/posts/microsoft-dynamics-365-asset-management-preview) (blog)</span></span>

<span data-ttu-id="1710c-129">[資産管理の概要](https://docs.microsoft.com/dynamics365/supply-chain/asset-management/index) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="1710c-129">[Asset management overview](https://docs.microsoft.com/dynamics365/supply-chain/asset-management/index) (docs)</span></span>