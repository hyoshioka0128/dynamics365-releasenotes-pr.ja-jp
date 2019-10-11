---
title: Common Data Service のデータ – フェーズ 2
description: Common Data Service のデータ – フェーズ 2
author: RamaKrishnamoorthy
ms.reviewer: sericks
ms.date: 09/12/2019
ms.assetid: 3105d865-6faa-e911-a963-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: ramasri
dynamics365pdf: true
ms.openlocfilehash: 43cd767ac1ce86958fc31dc44048d77a7862b93f
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141472"
---
# <a name="data-in-common-data-service--phase-2"></a><span data-ttu-id="e122d-103">Common Data Service のデータ – フェーズ 2</span><span class="sxs-lookup"><span data-stu-id="e122d-103">Data in Common Data Service – Phase 2</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="e122d-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="e122d-104">Enabled for</span></span>    |  <span data-ttu-id="e122d-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e122d-105">Public preview</span></span> | <span data-ttu-id="e122d-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="e122d-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="e122d-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="e122d-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="e122d-108">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="e122d-108">Dec 2019</span></span>| <span data-ttu-id="e122d-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="e122d-109">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="e122d-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e122d-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e122d-111">この機能は、Common Data Service とのシームレスなデータ交換を容易にします。</span><span class="sxs-lookup"><span data-stu-id="e122d-111">This feature facilitates seamless data exchange with Common Data Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e122d-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e122d-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e122d-113">Common Data Service のデータを取得し、最新の状態に保ちます。</span><span class="sxs-lookup"><span data-stu-id="e122d-113">Get your data in Common Data Service and keep it up to date.</span></span> 

<span data-ttu-id="e122d-114">Microsoft では、二重書き込みのフレームワークを特別な設定が不要なエクスペリエンスにしています。</span><span class="sxs-lookup"><span data-stu-id="e122d-114">We are making the dual-write framework an out-of-the-box experience.</span></span> <span data-ttu-id="e122d-115">これにより、企業はアプリの境界を超えてリアルタイムに近いデータを同期双方向方式でシームレスに交換できます。</span><span class="sxs-lookup"><span data-stu-id="e122d-115">This will allow businesses to seamlessly exchange near real-time data in a synchronous, bidirectional fashion, beyond application boundaries.</span></span> <span data-ttu-id="e122d-116">Microsoft では、ユーザーに "1 つの Dynamics 365" エクスペリエンスを提供したいと考えています。</span><span class="sxs-lookup"><span data-stu-id="e122d-116">We want to provide users a "One Dynamics 365" experience.</span></span> 

<span data-ttu-id="e122d-117">すべてのビジネスが固有のものであることがわかっているので、二重書き込みフレームワークを拡張可能にしました。</span><span class="sxs-lookup"><span data-stu-id="e122d-117">Knowing every business is unique, we have made the dual-write framework extensible.</span></span> <span data-ttu-id="e122d-118">これには、カスタム エンティティの有効化に加え、Common Data Service と最重要ビジネス データ用の関連ツールをフル活用するための既存のエンティティへの拡張が含まれます。</span><span class="sxs-lookup"><span data-stu-id="e122d-118">This includes enabling custom entities, as well as extensions to existing entities, to fully utilize Common Data Service and surrounding tools for your most important business data.</span></span>

<span data-ttu-id="e122d-119">フェーズ 1 では、顧客、ベンダー、製品にマルチマスター機能を提供する一連のエンティティをリリースしました。</span><span class="sxs-lookup"><span data-stu-id="e122d-119">In Phase 1, we released a set of entities that provides multi-mastering capabilities for customers, vendors, and products.</span></span> <span data-ttu-id="e122d-120">また、会社の概念を紹介し、組織階層に可視性を提供しました。</span><span class="sxs-lookup"><span data-stu-id="e122d-120">We also introduced the company concept and provided visibility to organization hierarchy.</span></span>

## <a name="phase-2-release"></a><span data-ttu-id="e122d-121">フェーズ 2 リリース</span><span class="sxs-lookup"><span data-stu-id="e122d-121">Phase 2 release</span></span>
<span data-ttu-id="e122d-122">フェーズ 2 リリースでは、プロジェクト、在庫、販売、調達から財務までをカバーするエンドツーエンドのシナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="e122d-122">The Phase 2 release will target supporting end-to-end scenarios covering project, inventory, sales, and procurement through to financials.</span></span> <span data-ttu-id="e122d-123">これらの分野で最も重要なエンティティをサポートする、すぐに使えるなシナリオが既定で提供されます。</span><span class="sxs-lookup"><span data-stu-id="e122d-123">Out-of-the-box scenarios supporting the most important entities in these areas will be provided by default.</span></span> <span data-ttu-id="e122d-124">これらのシナリオは、ユーザーとパートナーによってさらに充実させることができます。</span><span class="sxs-lookup"><span data-stu-id="e122d-124">These scenarios can be further enriched by customers and partners.</span></span> 

<span data-ttu-id="e122d-125">これらの機能は 11 月から 12 月の期間にパブリック プレビューでリリースされ、1 月には一般提供される予定です。</span><span class="sxs-lookup"><span data-stu-id="e122d-125">These features will be released for public preview in the November-December timeframe and made generally available in the January timeframe.</span></span> <span data-ttu-id="e122d-126">対象となるエンティティは後日発表されます。</span><span class="sxs-lookup"><span data-stu-id="e122d-126">Entity coverage will be revealed at a future date.</span></span>
<!--feature detail end -->











