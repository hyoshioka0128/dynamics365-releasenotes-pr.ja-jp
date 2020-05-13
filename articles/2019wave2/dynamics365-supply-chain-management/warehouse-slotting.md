---
title: 倉庫のスロッティング
description: スロッティングを使用すると、注文の需要に基づいていつでも補充作業を作成し、需要が倉庫にリリースされたときにピッキングのために商品を準備およびステージングできます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/07/2020
ms.assetid: 6862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 9280bed8f45c00b95f8735d1e1664fe48d55d1d5
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320789"
---
# <a name="warehouse-slotting"></a><span data-ttu-id="0d0e8-103">倉庫のスロッティング</span><span class="sxs-lookup"><span data-stu-id="0d0e8-103">Warehouse slotting</span></span>


| <span data-ttu-id="0d0e8-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0d0e8-104">Enabled for</span></span>    |  <span data-ttu-id="0d0e8-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0d0e8-105">Public preview</span></span> | <span data-ttu-id="0d0e8-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="0d0e8-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0d0e8-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="0d0e8-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="0d0e8-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0d0e8-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0d0e8-109">2019 年 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="0d0e8-109">Mar 5, 2019</span></span>| <span data-ttu-id="0d0e8-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0d0e8-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0d0e8-111">2020 年 3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="0d0e8-111">Mar 27, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="0d0e8-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0d0e8-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0d0e8-113">ピッキング場所は、倉庫に注文をリリースする前に補充できます。</span><span class="sxs-lookup"><span data-stu-id="0d0e8-113">Picking locations can be replenished before releasing orders to the warehouse.</span></span> <span data-ttu-id="0d0e8-114">倉庫のスロッティングを使用すると、注文の需要に基づいていつでも補充作業を作成できます。</span><span class="sxs-lookup"><span data-stu-id="0d0e8-114">Warehouse slotting allows you to create replenishment work at any time based on order demand.</span></span> <span data-ttu-id="0d0e8-115">この機能は、ユーザー定義のクエリに基づいてシステム内の注文から需要を収集し、倉庫担当者が閲覧できる統合された需要を作成します。</span><span class="sxs-lookup"><span data-stu-id="0d0e8-115">This feature will collect demand from orders in the system based on a user-defined query and make the consolidated demand available to be viewed by warehouse personnel.</span></span> <span data-ttu-id="0d0e8-116">需要が識別されると、スロット プロセスはすべての需要をピッキング場所に割り当てます。</span><span class="sxs-lookup"><span data-stu-id="0d0e8-116">Once demand has been identified, the slotting process will assign all of the demand to picking locations.</span></span> <span data-ttu-id="0d0e8-117">ピッキング場所が特定された後、補充作業を作成して在庫をピッキング場所に移動させることができます。</span><span class="sxs-lookup"><span data-stu-id="0d0e8-117">After pick locations have been identified, replenishment work can be created to bring inventory to the pick locations.</span></span> <span data-ttu-id="0d0e8-118">需要が倉庫にリリースされると、"ちょうど" ピッキング場所に運ばれた在庫を使用できます。</span><span class="sxs-lookup"><span data-stu-id="0d0e8-118">When the demand is released to the warehouse, it can use the inventory that has “just” been brought to the pick location.</span></span> <span data-ttu-id="0d0e8-119">パート 2 の機能では、必要に応じて不完全な補充作業にリンクすることもできます。</span><span class="sxs-lookup"><span data-stu-id="0d0e8-119">A part 2 feature will also allow linking to any incomplete replenishment work as needed.</span></span>
<!--feature detail end -->









