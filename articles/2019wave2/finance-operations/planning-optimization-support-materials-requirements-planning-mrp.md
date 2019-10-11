---
title: 資材所要量計画 (MRP) の計画最適化サポート
description: 計画の最適化により、リアルタイムに近い計画が独立したサービスとして促進されます。 企業は MRP に依存して生産を計画し、必要な材料と製品を確実に入手できるようにします。
author: relnotes
ms.reviewer: josaw
ms.date: 09/13/2019
ms.assetid: 5862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: crytt
dynamics365pdf: true
ms.openlocfilehash: faa35c0ef081446a75691284df8fc4ce78007986
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143892"
---
# <a name="planning-optimization-support-for-materials-requirements-planning-mrp"></a><span data-ttu-id="d0a57-104">資材所要量計画 (MRP) の計画最適化サポート</span><span class="sxs-lookup"><span data-stu-id="d0a57-104">Planning Optimization support for materials requirements planning (MRP)</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="d0a57-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="d0a57-105">Enabled for</span></span>    |  <span data-ttu-id="d0a57-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d0a57-106">Public preview</span></span> | <span data-ttu-id="d0a57-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="d0a57-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d0a57-108">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="d0a57-108">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="d0a57-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="d0a57-109">Feb 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="d0a57-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d0a57-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d0a57-111">製造業者にとっての価値:</span><span class="sxs-lookup"><span data-stu-id="d0a57-111">Value for manufacturers:</span></span>

-   <span data-ttu-id="d0a57-112">バッチ ジョブを計画するために毎日時間を確保する必要がなくなる。</span><span class="sxs-lookup"><span data-stu-id="d0a57-112">Eliminate daily time reserved for planning batch job.</span></span>

-   <span data-ttu-id="d0a57-113">将来の事業の成長により計画システムが過負荷にならない。</span><span class="sxs-lookup"><span data-stu-id="d0a57-113">Future business growth will not overload the planning system.</span></span>

-   <span data-ttu-id="d0a57-114">日次または週次よりも高い頻度で計画を実行できる。</span><span class="sxs-lookup"><span data-stu-id="d0a57-114">More frequent planning runs – not just daily or weekly.</span></span>

-   <span data-ttu-id="d0a57-115">総リードタイムの短縮による顧客サービスの向上。</span><span class="sxs-lookup"><span data-stu-id="d0a57-115">Improved customer service with shorter total lead time.</span></span>

-   <span data-ttu-id="d0a57-116">在庫レベルの削減によるコストと資本の節約。</span><span class="sxs-lookup"><span data-stu-id="d0a57-116">Cost and capital savings by reduced inventory levels.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d0a57-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d0a57-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d0a57-118">資材所要量計画 (MRP) は、製造会社の計画担当者が資材を生産に使用できるようにし、製品を顧客に出荷できるようにするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d0a57-118">Material requirements planning (MRP) helps planners at manufacturing companies ensure that materials are available for production and that products are available for delivery to customers.</span></span> <span data-ttu-id="d0a57-119">計画の最適化機能により、リアルタイムに近い計画が独立したサービスとして促進されます。</span><span class="sxs-lookup"><span data-stu-id="d0a57-119">Planning optimization functionality facilitates close to real-time planning, as a separate service.</span></span> <span data-ttu-id="d0a57-120">企業は MRP に依存して生産を計画し、必要な材料と製品を確実に入手できるようにします。</span><span class="sxs-lookup"><span data-stu-id="d0a57-120">Businesses rely on MRP to plan their production and ensure that needed material and products are available.</span></span> 

<span data-ttu-id="d0a57-121">MRP の計画最適化サポートにより、製造会社には次のメリットがあります。</span><span class="sxs-lookup"><span data-stu-id="d0a57-121">With planning optimization support for MRP, manufacturers can benefit from:</span></span> 

-  <span data-ttu-id="d0a57-122">データ量が多い場合のパフォーマンスの向上。</span><span class="sxs-lookup"><span data-stu-id="d0a57-122">Improved performance with high data volume.</span></span>

-  <span data-ttu-id="d0a57-123">ERP システムからマスター計画の負荷を取り除きます。</span><span class="sxs-lookup"><span data-stu-id="d0a57-123">Removing the load of master planning from their ERP system.</span></span>

-  <span data-ttu-id="d0a57-124">要件の変更に対してほぼリアルタイムの分析情報。</span><span class="sxs-lookup"><span data-stu-id="d0a57-124">Close to real-time insight to requirement changes.</span></span>

<span data-ttu-id="d0a57-125">計画担当者は、計画の最適化により、製造オーダーと関連要件を計画できます。</span><span class="sxs-lookup"><span data-stu-id="d0a57-125">Planners will be able to plan production orders and the related requirements with planning optimization:</span></span>

-  <span data-ttu-id="d0a57-126">生産に関する提案を提供します。</span><span class="sxs-lookup"><span data-stu-id="d0a57-126">Supply suggestions for production.</span></span>

-  <span data-ttu-id="d0a57-127">部品表 (BOM) をサポートします。</span><span class="sxs-lookup"><span data-stu-id="d0a57-127">Support for bill of materials (BOM).</span></span>

-  <span data-ttu-id="d0a57-128">ファントム BOM をサポートします。</span><span class="sxs-lookup"><span data-stu-id="d0a57-128">Support for phantom BOMs.</span></span>

-  <span data-ttu-id="d0a57-129">スクラップ ルールを使用した計画。</span><span class="sxs-lookup"><span data-stu-id="d0a57-129">Planning with scrap rules.</span></span>
<!--feature detail end -->











