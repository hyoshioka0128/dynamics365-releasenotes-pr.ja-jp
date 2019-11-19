---
title: 倉庫のスロッティング
description: スロッティングを使用すると、注文の需要に基づいていつでも補充作業を作成し、需要が倉庫にリリースされたときにピッキングのために商品を準備およびステージングできます。
author: relnotes
ms.reviewer: josaw
ms.date: 10/04/2019
ms.assetid: 6862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 7d41a9beef1b6c6ae9e7c36e0c5ecf1e0a963f20
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660569"
---
# <a name="warehouse-slotting"></a><span data-ttu-id="34dd9-103">倉庫のスロッティング</span><span class="sxs-lookup"><span data-stu-id="34dd9-103">Warehouse slotting</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="34dd9-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="34dd9-104">Enabled for</span></span>    |  <span data-ttu-id="34dd9-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="34dd9-105">Public preview</span></span> | <span data-ttu-id="34dd9-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="34dd9-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="34dd9-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="34dd9-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="34dd9-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="34dd9-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="34dd9-109">2019 年 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="34dd9-109">Mar 5, 2019</span></span>| <span data-ttu-id="34dd9-110">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="34dd9-110">Feb 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="34dd9-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="34dd9-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="34dd9-112">ピッキング場所は、倉庫に注文をリリースする前に補充できます。</span><span class="sxs-lookup"><span data-stu-id="34dd9-112">Picking locations can be replenished before releasing orders to the warehouse.</span></span> <span data-ttu-id="34dd9-113">倉庫のスロッティングを使用すると、注文の需要に基づいていつでも補充作業を作成できます。</span><span class="sxs-lookup"><span data-stu-id="34dd9-113">Warehouse slotting allows you to create replenishment work at any time based on order demand.</span></span> <span data-ttu-id="34dd9-114">この機能は、ユーザー定義のクエリに基づいてシステム内の注文から需要を収集し、倉庫担当者が閲覧できる統合された需要を作成します。</span><span class="sxs-lookup"><span data-stu-id="34dd9-114">This feature will collect demand from orders in the system based on a user-defined query and make the consolidated demand available to be viewed by warehouse personnel.</span></span> <span data-ttu-id="34dd9-115">需要が識別されると、スロット プロセスはすべての需要をピッキング場所に割り当てます。</span><span class="sxs-lookup"><span data-stu-id="34dd9-115">Once demand has been identified, the slotting process will assign all of the demand to picking locations.</span></span> <span data-ttu-id="34dd9-116">ピッキング場所が特定された後、補充作業を作成して在庫をピッキング場所に移動させることができます。</span><span class="sxs-lookup"><span data-stu-id="34dd9-116">After pick locations have been identified, replenishment work can be created to bring inventory to the pick locations.</span></span> <span data-ttu-id="34dd9-117">需要が倉庫にリリースされると、"ちょうど" ピッキング場所に運ばれた在庫を使用できます。</span><span class="sxs-lookup"><span data-stu-id="34dd9-117">When the demand is released to the warehouse, it can use the inventory that has “just” been brought to the pick location.</span></span> <span data-ttu-id="34dd9-118">パート 2 の機能では、必要に応じて不完全な補充作業にリンクすることもできます。</span><span class="sxs-lookup"><span data-stu-id="34dd9-118">A part 2 feature will also allow linking to any incomplete replenishment work as needed.</span></span>
<!--feature detail end -->









