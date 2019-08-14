---
title: 出荷の自動更新
description: この機能は、AWAX 機能を標準の WHS 機能に統合するという Blue Horseshoe との契約から始まります。 この機能では、関連する注文からの出荷数量のリアルタイム表現が提供され、それがウェーブで処理されていない限り、倉庫にリリースされた後でシステムは出荷の数量を自動的に更新することができます。
author: relnotes
ms.reviewer: josaw
ms.date: 08/01/2019
ms.assetid: 9062278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: henrikan
dynamics365pdf: true
ms.openlocfilehash: 8c923aad99ea195738ba6c752472ce8a68dc155d
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854814"
---
# <a name="shipment-auto-update"></a><span data-ttu-id="0f1c4-104">出荷の自動更新</span><span class="sxs-lookup"><span data-stu-id="0f1c4-104">Shipment auto update</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="0f1c4-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="0f1c4-105">Enabled for</span></span>    |  <span data-ttu-id="0f1c4-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0f1c4-106">Public preview</span></span> | <span data-ttu-id="0f1c4-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="0f1c4-107">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="0f1c4-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="0f1c4-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="0f1c4-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="0f1c4-109">August 01, 2019</span></span>| <span data-ttu-id="0f1c4-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="0f1c4-110">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="0f1c4-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0f1c4-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0f1c4-112">この機能を使用すると、企業は、注文明細の更新が関連する出荷や積荷に反映されないことを心配することなく、倉庫に更新をシームレスに提供できます。</span><span class="sxs-lookup"><span data-stu-id="0f1c4-112">This feature allows a business to seamlessly provide updates to a warehouse without having to worry about order line updates not being reflected on related shipments and loads.</span></span> <span data-ttu-id="0f1c4-113">この機能がないと、注文数量が増えた場合や新しい注文明細行が追加された場合、ユーザーは手動で更新または削除した後でその明細を再度リリースする必要があります。</span><span class="sxs-lookup"><span data-stu-id="0f1c4-113">Without this feature, users have to manually update or delete and then re-release lines if order quantities increase or new order lines are added.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0f1c4-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0f1c4-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0f1c4-115">この機能は、倉庫にリリースされた後で出荷に関連付けられた積荷明細行の数量を自動的に更新 (増減) します。</span><span class="sxs-lookup"><span data-stu-id="0f1c4-115">This functionality in this feature automatically updates quantities, increases as well as decreases, on a load line associated with a shipment after it’s been released to warehouse.</span></span> <span data-ttu-id="0f1c4-116">これは、出荷の積荷明細行または積荷がウェーブで処理されていない場合に限り行われます。</span><span class="sxs-lookup"><span data-stu-id="0f1c4-116">This will occur as long as the load line on the shipment or load has not been processed on a wave.</span></span> <span data-ttu-id="0f1c4-117">これは、倉庫作業が作成されていない限り、機能によって、手動での介入なしに、注文の更新が自動的に倉庫に流れることを意味します。</span><span class="sxs-lookup"><span data-stu-id="0f1c4-117">This implies that the feature will allow any order updates to automatically flow through to the warehouse without manual intervention as long as warehouse work hasn’t been created.</span></span> <span data-ttu-id="0f1c4-118">この機能がないと、倉庫作業が作成されていない場合に自動的に流れるのは数量の減少のみです。</span><span class="sxs-lookup"><span data-stu-id="0f1c4-118">Without this feature, only quantity decrease automatically flows through for as long as warehouse work hasn’t been created.</span></span> <span data-ttu-id="0f1c4-119">この機能は、販売注文明細行と移動オーダー明細行に適用されます。</span><span class="sxs-lookup"><span data-stu-id="0f1c4-119">This feature applies to sales order lines and transfer order lines.</span></span> 
 
<span data-ttu-id="0f1c4-120">この機能は特定の倉庫に対して有効にされます。</span><span class="sxs-lookup"><span data-stu-id="0f1c4-120">The feature is enabled for a specific warehouse.</span></span> <span data-ttu-id="0f1c4-121">これにより、会社は必要に応じて、倉庫ごとに異なる出荷自動更新ポリシーを適用できます。</span><span class="sxs-lookup"><span data-stu-id="0f1c4-121">This allows the company to apply different shipment auto update policies across warehouses, when required.</span></span> <span data-ttu-id="0f1c4-122">既定では、倉庫管理プロセスを使用するすべての倉庫に適用される出荷自動更新ポリシーは、数量の減少についてです。</span><span class="sxs-lookup"><span data-stu-id="0f1c4-122">By default, the shipment auto update policy applied for all warehouses that use a warehouse management process is on quantity decrease.</span></span> <span data-ttu-id="0f1c4-123">このポリシーを設定すると、倉庫作業が作成されていない場合に自動的に流れるのは、出荷と積荷に対する数量の減少のみです。</span><span class="sxs-lookup"><span data-stu-id="0f1c4-123">With this policy setting, only quantity decreases automatically flow through to a shipment and load for as long as warehouse work hasn’t been created.</span></span>
<!--feature detail end -->












## <a name="see-also"></a><span data-ttu-id="0f1c4-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="0f1c4-124">See also</span></span>

[<span data-ttu-id="0f1c4-125">出荷の自動更新</span><span class="sxs-lookup"><span data-stu-id="0f1c4-125">Shipment auto update</span></span>](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-finance-operations/shipment-auto-update)
