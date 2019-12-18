---
title: 出荷の自動更新
description: この機能は、AWAX 機能を標準の WHS 機能に統合するという Blue Horseshoe との契約から始まります。 この機能では、関連する注文からの出荷数量のリアルタイム表現が提供され、それがウェーブで処理されていない限り、倉庫にリリースされた後でシステムは出荷の数量を自動的に更新することができます。
author: relnotes
ms.reviewer: josaw
ms.date: 12/02/2019
ms.assetid: 9062278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: henrikan
dynamics365pdf: true
ms.openlocfilehash: fd802de56c4376317dc3050535c9aef121cd2f7e
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889617"
---
# <a name="shipment-auto-update"></a><span data-ttu-id="6e747-104">出荷の自動更新</span><span class="sxs-lookup"><span data-stu-id="6e747-104">Shipment auto update</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="6e747-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="6e747-105">Enabled for</span></span>    |  <span data-ttu-id="6e747-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6e747-106">Public preview</span></span> | <span data-ttu-id="6e747-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="6e747-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6e747-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="6e747-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="6e747-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6e747-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6e747-110">2019 年 11 月 25 日</span><span class="sxs-lookup"><span data-stu-id="6e747-110">Nov 25, 2019</span></span>| <span data-ttu-id="6e747-111">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="6e747-111">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="6e747-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="6e747-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="6e747-113">この機能を使用すると、企業は、注文明細の更新が関連する出荷や積荷に反映されないことを心配することなく、倉庫に更新をシームレスに提供できます。</span><span class="sxs-lookup"><span data-stu-id="6e747-113">This feature allows a business to seamlessly provide updates to a warehouse without having to worry about order line updates not being reflected on related shipments and loads.</span></span> <span data-ttu-id="6e747-114">この機能がないと、注文数量が増えた場合や新しい注文明細行が追加された場合、ユーザーは手動で更新または削除した後でその明細を再度リリースする必要があります。</span><span class="sxs-lookup"><span data-stu-id="6e747-114">Without this feature, users have to manually update or delete and then re-release lines if order quantities increase or new order lines are added.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="6e747-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6e747-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6e747-116">この機能は、倉庫にリリースされた後で出荷に関連付けられた積荷明細行の数量を自動的に更新 (増減) します。</span><span class="sxs-lookup"><span data-stu-id="6e747-116">This functionality in this feature automatically updates quantities, increases as well as decreases, on a load line associated with a shipment after it’s been released to warehouse.</span></span> <span data-ttu-id="6e747-117">これは、出荷の積荷明細行または積荷がウェーブで処理されていない場合に限り行われます。</span><span class="sxs-lookup"><span data-stu-id="6e747-117">This will occur as long as the load line on the shipment or load has not been processed on a wave.</span></span> <span data-ttu-id="6e747-118">これは、倉庫作業が作成されていない限り、機能によって、手動での介入なしに、注文の更新が自動的に倉庫に流れることを意味します。</span><span class="sxs-lookup"><span data-stu-id="6e747-118">This implies that the feature will allow any order updates to automatically flow through to the warehouse without manual intervention as long as warehouse work hasn’t been created.</span></span> <span data-ttu-id="6e747-119">この機能がないと、倉庫作業が作成されていない場合に自動的に流れるのは数量の減少のみです。</span><span class="sxs-lookup"><span data-stu-id="6e747-119">Without this feature, only quantity decrease automatically flows through for as long as warehouse work hasn’t been created.</span></span> <span data-ttu-id="6e747-120">この機能は、販売注文明細行と移動オーダー明細行に適用されます。</span><span class="sxs-lookup"><span data-stu-id="6e747-120">This feature applies to sales order lines and transfer order lines.</span></span> 
 
<span data-ttu-id="6e747-121">この機能は特定の倉庫に対して有効にされます。</span><span class="sxs-lookup"><span data-stu-id="6e747-121">The feature is enabled for a specific warehouse.</span></span> <span data-ttu-id="6e747-122">これにより、会社は必要に応じて、倉庫ごとに異なる出荷自動更新ポリシーを適用できます。</span><span class="sxs-lookup"><span data-stu-id="6e747-122">This allows the company to apply different shipment auto update policies across warehouses, when required.</span></span> <span data-ttu-id="6e747-123">既定では、倉庫管理プロセスを使用するすべての倉庫に適用される出荷自動更新ポリシーは、数量の減少についてです。</span><span class="sxs-lookup"><span data-stu-id="6e747-123">By default, the shipment auto update policy applied for all warehouses that use a warehouse management process is on quantity decrease.</span></span> <span data-ttu-id="6e747-124">このポリシーを設定すると、倉庫作業が作成されていない場合に自動的に流れるのは、出荷と積荷に対する数量の減少のみです。</span><span class="sxs-lookup"><span data-stu-id="6e747-124">With this policy setting, only quantity decreases automatically flow through to a shipment and load for as long as warehouse work hasn’t been created.</span></span>
<!--feature detail end -->








