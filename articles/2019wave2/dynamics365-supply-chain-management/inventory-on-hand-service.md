---
title: 手持在庫サービス
description: 手持在庫サービスは、独立した非常にスケーラブルなマイクロサービスであり、Dynamics 365 Supply Chain Management の手持ち在庫情報を外部システムで利用できるようにします。これにより、外部システムとの統合が簡素化され、手持在庫情報にほぼリアルタイムでアクセスする必要がある新しいシナリオが可能になります。
author: relnotes
ms.reviewer: josaw
ms.date: 09/30/2019
ms.assetid: 4c62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: sorenand
dynamics365pdf: true
ms.openlocfilehash: 511392a2e20dc954398366296c08144d084ea36b
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660605"
---
# <a name="inventory-on-hand-service"></a><span data-ttu-id="a0de8-103">手持在庫サービス</span><span class="sxs-lookup"><span data-stu-id="a0de8-103">Inventory on-hand service</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="a0de8-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a0de8-104">Enabled for</span></span>    |  <span data-ttu-id="a0de8-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a0de8-105">Public preview</span></span> | <span data-ttu-id="a0de8-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="a0de8-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a0de8-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="a0de8-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="a0de8-108">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="a0de8-108">Dec 2019</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="a0de8-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a0de8-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a0de8-110">個別のマイクロサービスを通じて手持在庫情報へのほぼリアルタイムのアクセスを提供することにより、Dynamics 365 Supply Chain Management での外部システムとの統合を簡素化し、応答時間を最適化して、増分的な負荷やパフォーマンスへの影響を軽減します。</span><span class="sxs-lookup"><span data-stu-id="a0de8-110">Providing near real-time access to inventory on-hand information through a separate micro-service simplifies integration with external systems, optimizes response times, and reduces the incremental load and performance impact on Dynamics 365 Supply Chain Management.</span></span>

<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a0de8-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a0de8-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a0de8-112">手持在庫の管理に Dynamics 365 Supply Chain Management を活用している組織は、手持在庫情報によってメリットが得られる他の外部システムを使用している場合があります。</span><span class="sxs-lookup"><span data-stu-id="a0de8-112">Organizations that leverage Dynamics 365 Supply Chain Management for managing their inventory on-hand might also have other external systems that could benefit from on-hand inventory information.</span></span> <span data-ttu-id="a0de8-113">そのような例として、外部販売ソリューションやモバイル ソリューションがあります。</span><span class="sxs-lookup"><span data-stu-id="a0de8-113">These could be external sales solutions or mobile solutions.</span></span> <span data-ttu-id="a0de8-114">他のシナリオとして、取引相手と手持在庫情報を共有することが必要な場合もあります。</span><span class="sxs-lookup"><span data-stu-id="a0de8-114">Other scenarios include the requirement to share inventory on-hand information with trading partners.</span></span> 

<span data-ttu-id="a0de8-115">手持在庫サービスは、Dynamics 365 Supply Chain Management の負荷を増加させたりパフォーマンスを低下させたりすることなく、非常にスケーラブルかつ高パフォーマンスな方法で手持在庫情報を提供する個別のマイクロサービスです。</span><span class="sxs-lookup"><span data-stu-id="a0de8-115">The inventory on-hand service is a separate micro-service that provides on-hand information in a hyper-scalable, hyper-performant manner without incurring additional load or compromising the performance of Dynamics 365 Supply Chain Management.</span></span> 

<span data-ttu-id="a0de8-116">手持在庫情報に関連するすべての情報は、低レベルの SQL 統合により、ほぼリアルタイムで手持在庫サービスにエクスポートされます。</span><span class="sxs-lookup"><span data-stu-id="a0de8-116">All information that relates to on-hand information is exported in near real-time to the inventory on-hand service through low-level SQL integration.</span></span> <span data-ttu-id="a0de8-117">外部システムは、RESTful API を介して手持在庫サービスにアクセスします。それにより、特定の分析コード セットに関する手持在庫情報を照会し、利用可能な手持在庫の位置のリストを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="a0de8-117">External systems access the inventory on-hand service through RESTful APIs that enable on-hand information on given sets of dimensions to be queried, and that enables retrieval of a list of available on-hand positions.</span></span>

<span data-ttu-id="a0de8-118">また、外部システムが手持在庫サービスを使用して手持在庫情報を更新することもできます。</span><span class="sxs-lookup"><span data-stu-id="a0de8-118">The inventory on-hand service also enables external systems to update on-hand information.</span></span> <span data-ttu-id="a0de8-119">これらのシナリオでは、Dynamics 365 Supply Chain Management で手持在庫の変更が (たとえば日次のインポート ジョブによって) 大幅に遅れて処理される場合でも、サービスはほぼリアルタイムで正確な手持在庫情報を維持できます。</span><span class="sxs-lookup"><span data-stu-id="a0de8-119">In these scenarios, the service will maintain on-hand information that is accurate in near real time, even though the on-hand changes are processed in Dynamics 365 Supply Chain Management with significant delay (for example, through a daily import job).</span></span>
<!--feature detail end -->









