---
title: 高度なクロスドッキング
description: クロスドッキングを使用すると、作業者は、既に出庫指示に対してマークされている在庫の入庫プット アウェイと出庫ピッキングをスキップすることができます。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: 9862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: e06bb7ec70ae449b65657f524ea9a54ec4f00f27
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854132"
---
# <a name="advanced-cross-docking"></a><span data-ttu-id="61487-103">高度なクロスドッキング</span><span class="sxs-lookup"><span data-stu-id="61487-103">Advanced cross-docking</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="61487-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="61487-104">Enabled for</span></span>    |  <span data-ttu-id="61487-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="61487-105">Public preview</span></span> | <span data-ttu-id="61487-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="61487-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="61487-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="61487-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="61487-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="61487-108">August 2019</span></span>| <span data-ttu-id="61487-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="61487-109">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="61487-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="61487-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="61487-111">この機能により、注文を満たすために必要な在庫数量が、入庫または作成から正しい出荷ドックまたはステージング領域に直接送られる、高度な計画的クロスドッキングが導入されます。</span><span class="sxs-lookup"><span data-stu-id="61487-111">This functionality introduces advanced planned cross-docking where the inventory quantity required to satisfy an order will be directed to the correct outbound dock or staging area straight from receipt or creation.</span></span> <span data-ttu-id="61487-112">入庫ソースからのすべての残余在庫が、通常のプット アウェイ プロセスを通じて正しい保存場所に送られます。</span><span class="sxs-lookup"><span data-stu-id="61487-112">All remaining inventory from the inbound source will be directed to the correct storage location through regular put-away process.</span></span> <span data-ttu-id="61487-113">したがって、クロスドッキングを使用すると、作業者は、既に出庫指示にマークされている在庫の入庫プット アウェイと出庫ピッキングをスキップすることができます。</span><span class="sxs-lookup"><span data-stu-id="61487-113">Cross-docking therefore allows a worker to skip inbound put away and outbound picking of inventory that is already marked to an outbound order.</span></span> <span data-ttu-id="61487-114">その結果、在庫に触れる回数が可能な限り最小限に抑えられるだけでなく、システムとのやり取りが少なくなるため、倉庫の作業現場での時間とスペースを大幅に節約できます。</span><span class="sxs-lookup"><span data-stu-id="61487-114">The result is a minimized number of touches of inventory where possible, together with greater time and space savings on the warehouse shop floor due to less interaction with the system.</span></span> <span data-ttu-id="61487-115">ユーザーは、クロスドッキングに対する供給元とその他の要件を指定した新しいクロスドッキング テンプレートを構成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="61487-115">The user must configure a new cross-dock template where the supply source and other requirements for cross-docking are specified.</span></span> <span data-ttu-id="61487-116">出庫指示が作成されたら、同じ品目を含む入庫指示に対して明細行がマークされる必要があります。</span><span class="sxs-lookup"><span data-stu-id="61487-116">As the outbound order is created, the line must be marked against an inbound order containing the identical item.</span></span> <span data-ttu-id="61487-117">マーキングは、入庫在庫と出庫指示を突き合わせるプロセスです。</span><span class="sxs-lookup"><span data-stu-id="61487-117">Marking is the process of matching the outbound order with inbound inventory.</span></span> <span data-ttu-id="61487-118">クロスドッキング作業指示書の作成に使用され、倉庫へのリリースによって手動または自動で行うことができます。</span><span class="sxs-lookup"><span data-stu-id="61487-118">It will be used to create the cross-dock work order, and it can be done manually or automatically via release to warehouse.</span></span> <span data-ttu-id="61487-119">入庫指示を受け取った時点で、クロスドッキング設定によってクロスドッキングの必要性が自動的に識別され、場所のディレクティブの設定に基づいて必要な数量の移動作業が作成されます。</span><span class="sxs-lookup"><span data-stu-id="61487-119">At the time of inbound order receiving, cross-docking setup will automatically identify the need for a cross-dock and create the movement work for the required quantity based on location directive setup.</span></span>
<!--feature detail end -->











