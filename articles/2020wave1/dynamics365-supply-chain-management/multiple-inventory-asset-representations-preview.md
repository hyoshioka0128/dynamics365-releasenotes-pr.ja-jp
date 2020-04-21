---
title: 複数の在庫資産の表現 (プレビュー)
description: この新しい機能は、国際組織やその子会社が複数の表現で在庫の会計処理を実行できるようにする包括的なソリューションを提供して、ローカル GAAP と IFRS/IAS の両方に同時に準拠することを可能にします。
author: relnotes
ms.reviewer: kamaybac
ms.date: 02/28/2020
ms.assetid: 1cb92a1e-80cb-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: aevengir
dynamics365pdf: true
ms.openlocfilehash: c82569b39bee556a7a34f7143dac7cd5282149c4
ms.sourcegitcommit: 2928661abcc468748ffc7c33516ebc8e3cd5d653
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/04/2020
ms.locfileid: "3098599"
---
# <a name="multiple-inventory-asset-representations-preview"></a><span data-ttu-id="5430b-103">複数の在庫資産の表現 (プレビュー)</span><span class="sxs-lookup"><span data-stu-id="5430b-103">Multiple inventory asset representations (preview)</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="5430b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="5430b-104">Enabled for</span></span>    |  <span data-ttu-id="5430b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5430b-105">Public preview</span></span> | <span data-ttu-id="5430b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="5430b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5430b-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="5430b-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="5430b-108">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="5430b-108">May 2020</span></span>| <span data-ttu-id="5430b-109">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="5430b-109">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="5430b-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5430b-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5430b-111">国際組織は、現地政府機関の会計基準 (ローカル GAAP) と、IFRS/IAS などの一般に公正妥当と認められる会計基準に (それらの基準が直接対立する場合であっても) 準拠する必要性にますます迫られています。</span><span class="sxs-lookup"><span data-stu-id="5430b-111">International organizations are under increasing pressure to be compliant by local governments (local GAAP) and General Accepted Accounting Practices like IFRS/IAS, even in cases where these practices might be in direct conflict.</span></span> <span data-ttu-id="5430b-112">現地通貨の為替変動が激しい国に子会社を持つ国際組織は、現地通貨で在庫を会計処理および管理することを現地政府機関から求められる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="5430b-112">International organizations having subsidiaries in countries with a hyper-fluctuation of local currency might be required by the local government to account and manage inventory in local currency.</span></span> <span data-ttu-id="5430b-113">こうした子会社は、IFRS/IAS に準拠するために、ユーロや米ドルなどの安定した通貨で在庫を会計処理および管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5430b-113">To comply with IFRS/IAS, the subsidiary is required to account and manage inventory in a stable currency like the euro or US dollar.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5430b-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5430b-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5430b-115">組織は多くの場合、管理会計設定の一部として、標準原価で在庫の会計処理を行うことを選択します。</span><span class="sxs-lookup"><span data-stu-id="5430b-115">Organizations often prefer to account for inventory by standard cost as part of their management accounting setup.</span></span> <span data-ttu-id="5430b-116">現地政府機関、税務当局、IFRS では標準原価を会計原則として認めておらず、多くの場合、平均または固有 ID を必要とします。</span><span class="sxs-lookup"><span data-stu-id="5430b-116">Local governments, tax authorities, and IFRS do not recognize standard cost as an accounting principle and often require average or specific identification.</span></span>

<span data-ttu-id="5430b-117">これらの要件にまとめて対処するには、複数の在庫表現で在庫の会計処理を実行する機能をサポートし、個別の会計処理ポリシーのセットを使用して各表現を構成できるような包括的なソリューションが必要となります。</span><span class="sxs-lookup"><span data-stu-id="5430b-117">Collectively these requirements must be addressed in a comprehensive solution that supports the ability to perform inventory accounting in multiple inventory representations, where each representation can be configured with a specific set of accounting policies.</span></span>

<span data-ttu-id="5430b-118">この新しい機能により、顧客は必要な数の在庫表現を定義できます。</span><span class="sxs-lookup"><span data-stu-id="5430b-118">With this new functionality, customers can define as many inventory representations as required.</span></span> <span data-ttu-id="5430b-119">二重通貨と二重評価の在庫会計をサポートします。</span><span class="sxs-lookup"><span data-stu-id="5430b-119">Inventory accounting in dual currency and inventory accounting in dual valuation is supported.</span></span>

<span data-ttu-id="5430b-120">在庫会計は個々の元帳で処理します。</span><span class="sxs-lookup"><span data-stu-id="5430b-120">Inventory accounting is performed in individual ledgers.</span></span> <span data-ttu-id="5430b-121">組織内の 1 つの法人に対して複数の元帳を作成して、複数の在庫表現をとることができるようにします。</span><span class="sxs-lookup"><span data-stu-id="5430b-121">Several ledgers can be created for a legal entity in the organization, ensuring that multiple inventory representations can be obtained.</span></span> <span data-ttu-id="5430b-122">1 つの法人に転記されたすべての文書 (発注書、販売注文、移動オーダーなど) が、その法人に関連付けられたすべての元帳に計上されます。</span><span class="sxs-lookup"><span data-stu-id="5430b-122">All documents (purchase orders, sales orders, transfer orders, and so on) posted in a legal entity will be accounted in all the ledgers associated with the legal entity.</span></span>

<span data-ttu-id="5430b-123">元帳は以下によって定義されます:</span><span class="sxs-lookup"><span data-stu-id="5430b-123">A ledger is defined by:</span></span> 

- <span data-ttu-id="5430b-124">カレンダー</span><span class="sxs-lookup"><span data-stu-id="5430b-124">Calendar</span></span>
- <span data-ttu-id="5430b-125">通貨</span><span class="sxs-lookup"><span data-stu-id="5430b-125">Currency</span></span>
- <span data-ttu-id="5430b-126">為替レート表</span><span class="sxs-lookup"><span data-stu-id="5430b-126">Exchange rate table</span></span>
- <span data-ttu-id="5430b-127">規則</span><span class="sxs-lookup"><span data-stu-id="5430b-127">Convention</span></span>

<span data-ttu-id="5430b-128">規則は、1 つ以上の元帳に関連付けできる在庫会計ポリシーのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="5430b-128">A convention is a collection of inventory accounting policies that can be associated with one or more ledgers.</span></span> <span data-ttu-id="5430b-129">これにより、組織内で共通の規則を共有できます。</span><span class="sxs-lookup"><span data-stu-id="5430b-129">This provides the ability to share a common convention in the organization.</span></span>

<span data-ttu-id="5430b-130">複数の在庫表現は、複数の在庫会計ポリシーをサポートしています。</span><span class="sxs-lookup"><span data-stu-id="5430b-130">The multiple inventory representations support multiple inventory accounting policies.</span></span> <span data-ttu-id="5430b-131">それぞれのポリシーごとに単一のルールを選択でき、それがすべての製品に適用されます。</span><span class="sxs-lookup"><span data-stu-id="5430b-131">For each policy, a single rule can be selected, and it applies to all products.</span></span>

<span data-ttu-id="5430b-132">入力測定基準:</span><span class="sxs-lookup"><span data-stu-id="5430b-132">Input measurement basis:</span></span>

- <span data-ttu-id="5430b-133">通常の履歴</span><span class="sxs-lookup"><span data-stu-id="5430b-133">Normal historical</span></span>
- <span data-ttu-id="5430b-134">標準</span><span class="sxs-lookup"><span data-stu-id="5430b-134">Standard</span></span>

<span data-ttu-id="5430b-135">原価フロー仮定:</span><span class="sxs-lookup"><span data-stu-id="5430b-135">Cost flow assumption:</span></span>

- <span data-ttu-id="5430b-136">平均</span><span class="sxs-lookup"><span data-stu-id="5430b-136">Average</span></span>
- <span data-ttu-id="5430b-137">固有 ID (バッチ)</span><span class="sxs-lookup"><span data-stu-id="5430b-137">Specific identification (Batch)</span></span>

<span data-ttu-id="5430b-138">記録間隔:</span><span class="sxs-lookup"><span data-stu-id="5430b-138">Recording interval:</span></span>

- <span data-ttu-id="5430b-139">永続</span><span class="sxs-lookup"><span data-stu-id="5430b-139">Perpetual</span></span>

<span data-ttu-id="5430b-140">最後に、このソリューションは、Supply Chain Management に転記された元の文書まで遡って、原価会計測定からの詳細な監査証跡を提供します。</span><span class="sxs-lookup"><span data-stu-id="5430b-140">Lastly, this solution provides a detailed audit trail from a cost-accounting measure all the way back to the original document posted in Supply Chain Management.</span></span>
<!--feature detail end -->









