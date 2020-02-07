---
title: 複数の在庫資産の表現 (プレビュー)
description: この新しい機能は、国際組織やその子会社が複数の表現で在庫の会計を実行できるようにする包括的なソリューションを提供し、ローカル GAAP と IFRS / IAS の両方に対して同時に準拠することを可能にします。
author: relnotes
ms.reviewer: kamaybac
ms.date: 12/16/2019
ms.assetid: 1cb92a1e-80cb-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: aevengir
dynamics365pdf: true
ms.openlocfilehash: 7da793b73b300b885f54507e807ebe8ba8404808
ms.sourcegitcommit: 9ede92eba84a02579fc8fc63e6a9673b034ce30c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2020
ms.locfileid: "2976534"
---
# <a name="multiple-inventory-asset-representations-preview"></a><span data-ttu-id="3c97f-103">複数の在庫資産の表現 (プレビュー)</span><span class="sxs-lookup"><span data-stu-id="3c97f-103">Multiple inventory asset representations (Preview)</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="3c97f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3c97f-104">Enabled for</span></span>    |  <span data-ttu-id="3c97f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3c97f-105">Public preview</span></span> | <span data-ttu-id="3c97f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="3c97f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3c97f-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="3c97f-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="3c97f-108">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="3c97f-108">May 2020</span></span>| <span data-ttu-id="3c97f-109">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="3c97f-109">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3c97f-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3c97f-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3c97f-111">国際組織は、現地政府 (ローカル GAAP) および IFRS / IAS のような一般に認められた会計原則に準拠するよう、圧力にさらされています。</span><span class="sxs-lookup"><span data-stu-id="3c97f-111">International organizations are under increasing pressure to be compliant by local governments (local GAAP) and General Accepted Accounting Practices like IFRS/IAS, even in cases were these practices may be in direct conflict.</span></span> <span data-ttu-id="3c97f-112">現地通貨の為替変動が激しい国に子会社を持つ国際組織は、現地政府から現地通貨で在庫を計上および管理するよう要求される場合があります。</span><span class="sxs-lookup"><span data-stu-id="3c97f-112">International organizations having subsidiaries in countries with a hyper-fluctuation of local currency may be required by the local government to account and manage inventory in local currency.</span></span> <span data-ttu-id="3c97f-113">IFRS / IAS に準拠するために、こうした子会社はユーロや米国ドルなどの安定した通貨で在庫を計上および管理することを求められます。</span><span class="sxs-lookup"><span data-stu-id="3c97f-113">To comply with IFRS/IAS, the subsidiary is required to account and manage inventory in a stable currency like the euro or US dollar.</span></span>
<!-- bv end -->




## <a name="feature-details"></a><span data-ttu-id="3c97f-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3c97f-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3c97f-115">組織は多くの場合、管理会計設定の一部として、標準原価で在庫を計上することを選択します。</span><span class="sxs-lookup"><span data-stu-id="3c97f-115">Organizations often prefer to account inventory by standard cost as part of their management accounting setup.</span></span> <span data-ttu-id="3c97f-116">現地政府、税務当局、IFRS は、標準原価を会計原則として認識しておらず、多くの場合、平均、FIFO、固有の識別を求めます。</span><span class="sxs-lookup"><span data-stu-id="3c97f-116">Local governments, tax authorities, and IFRS do not recognize standard cost as an accounting principle and often require average, FIFO, or specific identification.</span></span>

<span data-ttu-id="3c97f-117">まとめると、こうした要件は、複数の在庫表現で在庫会計を行う機能をサポートする、包括的なソリューションで対処する必要があります。それぞれの表現は、特定の会計ポリシーで構成できます。</span><span class="sxs-lookup"><span data-stu-id="3c97f-117">Collectively these requirements must be addressed in a comprehensive solution that supports the ability to perform inventory accounting in multiple inventory representations, where each representation can be configured with a specific set of accounting policies.</span></span>

<span data-ttu-id="3c97f-118">この新しい機能により、顧客は必要な数の在庫表現を定義できます。</span><span class="sxs-lookup"><span data-stu-id="3c97f-118">With this new functionality, customers can define as many inventory representations as required.</span></span> <span data-ttu-id="3c97f-119">二重通貨と二重評価の在庫会計をサポートします。</span><span class="sxs-lookup"><span data-stu-id="3c97f-119">Inventory accounting in dual currency and inventory accounting in dual valuation is supported.</span></span>

<span data-ttu-id="3c97f-120">在庫会計は個々の元帳で処理します。</span><span class="sxs-lookup"><span data-stu-id="3c97f-120">Inventory accounting is performed in individual ledgers.</span></span> <span data-ttu-id="3c97f-121">組織内の法人に複数の元帳を作成して、複数の在庫表現をとることができるようにします。</span><span class="sxs-lookup"><span data-stu-id="3c97f-121">Several ledgers can be created for a legal entity in the organization ensuring that multiple inventory representations can be obtained.</span></span> <span data-ttu-id="3c97f-122">法人に転記したすべての文書 (発注書、販売注文、移動オーダーなど) は、法人に関連付けられたすべての元帳に計上されます。</span><span class="sxs-lookup"><span data-stu-id="3c97f-122">All documents (purchase order, sales order, transfer order, etc.) posted in a legal entity will be accounted in all the ledgers associated with the legal entity.</span></span>

<span data-ttu-id="3c97f-123">元帳は以下によって定義されます:</span><span class="sxs-lookup"><span data-stu-id="3c97f-123">A ledger is defined by:</span></span> 

- <span data-ttu-id="3c97f-124">カレンダー</span><span class="sxs-lookup"><span data-stu-id="3c97f-124">Calendar</span></span>
- <span data-ttu-id="3c97f-125">通貨</span><span class="sxs-lookup"><span data-stu-id="3c97f-125">Currency</span></span>
- <span data-ttu-id="3c97f-126">為替レート表</span><span class="sxs-lookup"><span data-stu-id="3c97f-126">Exchange rate table</span></span>
- <span data-ttu-id="3c97f-127">規則</span><span class="sxs-lookup"><span data-stu-id="3c97f-127">Convention</span></span>

<span data-ttu-id="3c97f-128">規則は、1 つ以上の元帳に関連付けできる在庫会計ポリシーのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="3c97f-128">A convention is a collection of inventory accounting policies that can be associated to one or more ledgers.</span></span> <span data-ttu-id="3c97f-129">これにより、組織内で共通の規則を共有できます。</span><span class="sxs-lookup"><span data-stu-id="3c97f-129">This provides the ability to share a common convention in the organization.</span></span>

<span data-ttu-id="3c97f-130">複数の在庫表現は、複数の在庫会計ポリシーをサポートしています。</span><span class="sxs-lookup"><span data-stu-id="3c97f-130">The multiple inventory representations support multiple inventory accounting policies.</span></span> <span data-ttu-id="3c97f-131">それぞれのポリシーごとに単一のルールを選択でき、それがすべての製品に適用されます。</span><span class="sxs-lookup"><span data-stu-id="3c97f-131">For each policy, a single rule can be selected, and it applies to all products.</span></span>

<span data-ttu-id="3c97f-132">入力測定基準:</span><span class="sxs-lookup"><span data-stu-id="3c97f-132">Input measurement basis:</span></span>
- <span data-ttu-id="3c97f-133">通常の履歴</span><span class="sxs-lookup"><span data-stu-id="3c97f-133">Normal historical</span></span>
- <span data-ttu-id="3c97f-134">標準</span><span class="sxs-lookup"><span data-stu-id="3c97f-134">Standard</span></span>

<span data-ttu-id="3c97f-135">原価フロー仮定:</span><span class="sxs-lookup"><span data-stu-id="3c97f-135">Cost flow assumption:</span></span>
- <span data-ttu-id="3c97f-136">平均</span><span class="sxs-lookup"><span data-stu-id="3c97f-136">Average</span></span>
- <span data-ttu-id="3c97f-137">固有 ID (バッチ)</span><span class="sxs-lookup"><span data-stu-id="3c97f-137">Specific identification (Batch)</span></span>

<span data-ttu-id="3c97f-138">記録間隔:</span><span class="sxs-lookup"><span data-stu-id="3c97f-138">Recording interval:</span></span>
- <span data-ttu-id="3c97f-139">永続</span><span class="sxs-lookup"><span data-stu-id="3c97f-139">Perpetual</span></span>

<span data-ttu-id="3c97f-140">複数の在庫表現は主要な測定と KPI を提供し、在庫パフォーマンスに対する分析情報を有効化します。</span><span class="sxs-lookup"><span data-stu-id="3c97f-140">The multiple inventory representations provide key measures and KPIs, enabling insights to inventory performance:</span></span>
- <span data-ttu-id="3c97f-141">期首残高</span><span class="sxs-lookup"><span data-stu-id="3c97f-141">Beginning balance</span></span>
- <span data-ttu-id="3c97f-142">差分変更</span><span class="sxs-lookup"><span data-stu-id="3c97f-142">Net change</span></span>
- <span data-ttu-id="3c97f-143">差分変更インフロー</span><span class="sxs-lookup"><span data-stu-id="3c97f-143">Net change inflow</span></span>
- <span data-ttu-id="3c97f-144">差分変更アウトフロー</span><span class="sxs-lookup"><span data-stu-id="3c97f-144">Net change outflow</span></span>
- <span data-ttu-id="3c97f-145">期末残高</span><span class="sxs-lookup"><span data-stu-id="3c97f-145">Ending balance</span></span>
- <span data-ttu-id="3c97f-146">在庫回転</span><span class="sxs-lookup"><span data-stu-id="3c97f-146">Inventory turn</span></span>
- <span data-ttu-id="3c97f-147">在庫の正確性</span><span class="sxs-lookup"><span data-stu-id="3c97f-147">Inventory accuracy</span></span>
- <span data-ttu-id="3c97f-148">在庫の日数</span><span class="sxs-lookup"><span data-stu-id="3c97f-148">Days of inventory</span></span>

<span data-ttu-id="3c97f-149">Power BI を使用する主要なビジュアル、そして以下に対して製品、場所、時間のドリルスルーとスライスも提供します。</span><span class="sxs-lookup"><span data-stu-id="3c97f-149">Key visuals using Power BI and enabling drill-through and slicing by product, location, and time are also provided for:</span></span>
- <span data-ttu-id="3c97f-150">在庫状態</span><span class="sxs-lookup"><span data-stu-id="3c97f-150">Inventory status</span></span>
- <span data-ttu-id="3c97f-151">在庫エイジング</span><span class="sxs-lookup"><span data-stu-id="3c97f-151">Inventory aging</span></span>
- <span data-ttu-id="3c97f-152">ABC 分析</span><span class="sxs-lookup"><span data-stu-id="3c97f-152">ABC analysis</span></span>
- <span data-ttu-id="3c97f-153">差異分析</span><span class="sxs-lookup"><span data-stu-id="3c97f-153">Variance analysis</span></span>

<span data-ttu-id="3c97f-154">最後に、このソリューションは、Supply Chain Management に投稿された元のドキュメントまで遡って、原価会計測定からの詳細な監査証跡を提供します。</span><span class="sxs-lookup"><span data-stu-id="3c97f-154">Lastly, this solution provides a detailed audit trail from a cost-accounting measure all the way back to the original document posted in Supply Chain Management.</span></span>
<!--feature detail end -->










