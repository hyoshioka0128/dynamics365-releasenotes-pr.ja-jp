---
title: クロスドッキング
description: クロスドッキングを使用すると、作業者は、既に出庫指示に対してマークされている在庫の入庫プット アウェイと出庫ピッキングをスキップすることができます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/07/2020
ms.assetid: 9862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: a8c600f0658cd325ee919daf0c8784f3bd2b59b3
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3319997"
---
# <a name="cross-docking"></a><span data-ttu-id="41216-103">クロスドッキング</span><span class="sxs-lookup"><span data-stu-id="41216-103">Cross-docking</span></span>


| <span data-ttu-id="41216-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="41216-104">Enabled for</span></span>    |  <span data-ttu-id="41216-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="41216-105">Public preview</span></span> | <span data-ttu-id="41216-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="41216-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="41216-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="41216-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="41216-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="41216-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="41216-109">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="41216-109">Aug 2, 2019</span></span>| <span data-ttu-id="41216-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="41216-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="41216-111">2020 年 3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="41216-111">Mar 31, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="41216-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="41216-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="41216-113">この機能により、既存の注文を満たすために必要なすべての入庫在庫を、プット アウェイしなくても正しい出荷ドックまたはステージング領域に直接移動できる、計画された高度なクロスドッキングが導入されます。</span><span class="sxs-lookup"><span data-stu-id="41216-113">This functionality introduces advanced, planned cross-docking where all of the inbound inventory required to satisfy an existing order can be moved directly to the correct outbound dock or staging area without being put away.</span></span> <span data-ttu-id="41216-114">入庫ソースからのすべての残余在庫が、通常のプット アウェイ プロセスを通じて正しい保存場所に送られます。</span><span class="sxs-lookup"><span data-stu-id="41216-114">All remaining inventory from the inbound source is directed to the correct storage location through the regular put-away process.</span></span> <span data-ttu-id="41216-115">クロスドッキングを使用すると、作業者は、既に出庫指示で対象としてマークされている在庫の入庫プット アウェイと出庫ピッキングをスキップすることができます。</span><span class="sxs-lookup"><span data-stu-id="41216-115">Cross-docking allows workers to skip inbound put-away and outbound picking of inventory that is already marked for inclusion in an outbound order.</span></span> <span data-ttu-id="41216-116">その結果、在庫に触れる回数が可能な限り最小限に抑えられると同時に、システムを操作する回数が減るため、倉庫の作業現場での時間とスペースを節約できます。</span><span class="sxs-lookup"><span data-stu-id="41216-116">The result minimizes the number of inventory touches where possible while saving time and space on the warehouse shop floor by reducing the number of interactions with the system.</span></span> 

<span data-ttu-id="41216-117">ユーザーは、新しいクロスドッキング テンプレートをを使って、クロスドッキングに対する供給元とその他の要件を指定できます。</span><span class="sxs-lookup"><span data-stu-id="41216-117">The new cross-dock template enables users to specify the supply source and other requirements for cross-docking.</span></span> <span data-ttu-id="41216-118">入庫在庫と出庫指示を突き合わせるプロセスは、_マーキング_と呼ばれます。</span><span class="sxs-lookup"><span data-stu-id="41216-118">The process of matching an outbound order to inbound inventory is called _marking_.</span></span> <span data-ttu-id="41216-119">出庫指示を作成する際、ユーザーは必要な品目を含む入庫指示と一致するように各関連行をマークする必要があります。</span><span class="sxs-lookup"><span data-stu-id="41216-119">On creating an outbound order, the user must mark each relevant line to match an inbound order that contains the required items.</span></span> <span data-ttu-id="41216-120">このプロセスでは、クロスドッキング作業指示書が作成され、倉庫へのリリースによって手動または自動で行うことができます。</span><span class="sxs-lookup"><span data-stu-id="41216-120">This process creates the cross-dock work order and can be done manually or automatically via release-to-warehouse.</span></span> <span data-ttu-id="41216-121">入庫指示を受け取ったら、クロスドッキング設定によってクロスドッキングの必要性が自動的に識別され、場所のディレクティブの設定に基づいて必要な数量の移動作業が作成されます。</span><span class="sxs-lookup"><span data-stu-id="41216-121">On receiving an inbound order, the cross-docking setup automatically identifies the need for a cross-dock and creates the movement work for the required quantity based on the location-directive setup.</span></span>

<span data-ttu-id="41216-122">自動リリース出荷機能は、クロスドッキング フレームワークに基づいています。また、クロスドッキング戦略をサポートしており、需要数量を供給する製造オーダーが完了したと報告されたときに販売注文または移動オーダーを倉庫に自動的にリリースできます。</span><span class="sxs-lookup"><span data-stu-id="41216-122">The auto-release shipment feature builds on the cross-docking framework and supports a cross-docking strategy that lets you automatically release a sales or transfer order to the warehouse when the production order that supplies the demand quantity is reported as finished.</span></span> <span data-ttu-id="41216-123">このようにして、需要オーダーを履行するのに必要な数量が、生産出荷の場所から出庫の場所に直接移動されます。</span><span class="sxs-lookup"><span data-stu-id="41216-123">In this way, the quantity required to fulfil the demand order is moved directly from the production output location to the outbound location.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="41216-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="41216-124">See also</span></span>
<span data-ttu-id="41216-125">[機能の探索](https://www.microsoft.com/videoplayer/embed/RE4f7LF) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="41216-125">[Feature exploration](https://www.microsoft.com/videoplayer/embed/RE4f7LF) (video)</span></span>

<!--docs start-->
<span data-ttu-id="41216-126">[倉庫管理の概要](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="41216-126">[Warehouse management overview](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (docs)</span></span>
<!--docs end-->
