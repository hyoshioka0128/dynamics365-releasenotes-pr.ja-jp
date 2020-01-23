---
title: クロスドッキング用の自動リリース出荷
description: この機能は、クロスドッキング戦略をサポートしており、需要数量を供給する製造オーダーが完了したと報告されたときに需要オーダーを倉庫に自動的にリリースできます。 このようにして、需要オーダーの履行に必要な数量が、生産出荷の場所から出庫の場所に直接移動されます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 01/08/2020
ms.assetid: 9e62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: omulvad
dynamics365pdf: true
ms.openlocfilehash: 90a59613c3df57bdaadd9ddbe401245df54bddb0
ms.sourcegitcommit: 7d5d14ac84333ba166265755f410f7e16035a64e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2948114"
---
# <a name="auto-release-shipment-for-cross-dock"></a><span data-ttu-id="88186-104">クロスドッキング用の自動リリース出荷</span><span class="sxs-lookup"><span data-stu-id="88186-104">Auto-release shipment for cross dock</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="88186-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="88186-105">Enabled for</span></span>    |  <span data-ttu-id="88186-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="88186-106">Public preview</span></span> | <span data-ttu-id="88186-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="88186-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="88186-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="88186-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="88186-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="88186-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="88186-110">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="88186-110">Aug 2, 2019</span></span>| <span data-ttu-id="88186-111">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="88186-111">Jan 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="88186-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="88186-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="88186-113">自動リリース出荷機能は、クロスドッキング フレームワークに基づいており、次の特性があります。</span><span class="sxs-lookup"><span data-stu-id="88186-113">The auto-release shipment feature builds on the cross-docking framework and has these characteristics:</span></span>

- <span data-ttu-id="88186-114">供給として製造オーダーのみ、需要として販売注文および移動オーダーのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="88186-114">It supports only production orders as supply and only sales and transfer orders as demand.</span></span>
- <span data-ttu-id="88186-115">クロスドッキング工程は、供給受領が登録される前に (つまり、生産が終了したと報告される前に) 需要オーダーが倉庫にリリースされなかった場合でも開始できます。</span><span class="sxs-lookup"><span data-stu-id="88186-115">The cross-docking operation can be started even if the demand order wasn't released to the warehouse before the supply receipt was registered (that is, before the production was reported as finished).</span></span>

<span data-ttu-id="88186-116">このクロスドッキング機能には 2 つの利点があります。</span><span class="sxs-lookup"><span data-stu-id="88186-116">This cross-docking functionality has two advantages:</span></span>

1. <span data-ttu-id="88186-117">倉庫工程では、出庫指示を完了するために数量が再びピックアップされるだけの場合、通常の倉庫保管領域に完成品の数量をプット アウェイするステップをスキップできます。</span><span class="sxs-lookup"><span data-stu-id="88186-117">The warehouse operations can skip the step of putting away quantities of finished goods to the regular warehouse storage area if those quantities will just be picked up again to fulfill an outbound order.</span></span> <span data-ttu-id="88186-118">代わりに、数量を出荷の場所から梱包/配送の場所に一度移動できます。</span><span class="sxs-lookup"><span data-stu-id="88186-118">Instead, the quantities can be moved one time, from the output location to a packing/shipping location.</span></span> <span data-ttu-id="88186-119">このように、この機能により、在庫の処理回数を最小限に抑えることができ、最終的に、倉庫の作業現場で時間とスペースを最大限に節約できます。</span><span class="sxs-lookup"><span data-stu-id="88186-119">In this way, the functionality helps minimize the number of times that stock is handled and, ultimately, helps maximize time and space savings on the warehouse shop floor.</span></span>
2. <span data-ttu-id="88186-120">倉庫工程では、関連する製造オーダーの完成品の出荷が終了したと報告されるまで、販売注文のリリースを延期して倉庫に移動することができます。</span><span class="sxs-lookup"><span data-stu-id="88186-120">The warehouse operations can postpone the release of sales orders and transfer orders to the warehouse until the output of finished goods for the associated production order is reported as finished.</span></span> <span data-ttu-id="88186-121">これは、製造リード タイムが見込み生産環境のリード タイムよりも長くなる傾向がある場合に、受注生産環境で特にメリットとなる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="88186-121">This advantage might be especially relevant in make-to-order production environments where manufacturing lead times tend to be longer than the lead times in make-to-stock environments.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="88186-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="88186-122">See also</span></span>

<span data-ttu-id="88186-123">[クロスドッキング用の自動リリース出荷](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/auto-release-shipment-for-cross-docking) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="88186-123">[Auto-release shipment for cross-docking](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/auto-release-shipment-for-cross-docking) (docs)</span></span>
