---
title: 補充スロット計画 - パート I (スロット)
description: スロットを使用すると、注文の需要に基づいていつでも補充作業を作成し、需要が倉庫にリリースされたときにピッキングのために商品を準備およびステージングできます。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: 6862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: b8e2e184a2ae23719607738306faebdc93774f11
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854956"
---
# <a name="replenishment-slotting-plan---part-i-slotting"></a><span data-ttu-id="1880e-103">補充スロット計画 - パート I (スロット)</span><span class="sxs-lookup"><span data-stu-id="1880e-103">Replenishment Slotting Plan - part I (Slotting)</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="1880e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1880e-104">Enabled for</span></span>    |  <span data-ttu-id="1880e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1880e-105">Public preview</span></span> | <span data-ttu-id="1880e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="1880e-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="1880e-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="1880e-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1880e-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="1880e-108">August 2019</span></span>| <span data-ttu-id="1880e-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="1880e-109">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="1880e-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1880e-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1880e-111">ピッキング場所は、倉庫に注文をリリースする前に補充できます。</span><span class="sxs-lookup"><span data-stu-id="1880e-111">Picking locations can be replenished before releasing orders to the warehouse.</span></span> <span data-ttu-id="1880e-112">スロットを使用すると、注文の需要に基づいていつでも補充作業を作成できます。</span><span class="sxs-lookup"><span data-stu-id="1880e-112">Slotting allows you to create replenishment work at any time based on order demand.</span></span> <span data-ttu-id="1880e-113">この機能は、ユーザー定義のクエリに基づいてシステム内の注文から需要を収集し、倉庫担当者が閲覧できる統合された需要を作成します。</span><span class="sxs-lookup"><span data-stu-id="1880e-113">This feature will collect demand from orders in the system based on a user-defined query and make the consolidated demand available to be viewed by warehouse personnel.</span></span> <span data-ttu-id="1880e-114">需要が識別されると、スロット プロセスはすべての需要をピッキング場所に割り当てます。</span><span class="sxs-lookup"><span data-stu-id="1880e-114">Once demand has been identified, the slotting process will assign all of the demand to picking locations.</span></span> <span data-ttu-id="1880e-115">ピッキング場所が特定された後、補充作業を作成して在庫をピッキング場所に移動させることができます。</span><span class="sxs-lookup"><span data-stu-id="1880e-115">After pick locations have been identified, replenishment work can be created to bring inventory to the pick locations.</span></span> <span data-ttu-id="1880e-116">需要が倉庫にリリースされると、"ちょうど" ピッキング場所に運ばれた在庫を使用できます。</span><span class="sxs-lookup"><span data-stu-id="1880e-116">When the demand is released to the warehouse, it can use the inventory that has “just” been brought to the pick location.</span></span> <span data-ttu-id="1880e-117">パート 2 の機能では、必要に応じて不完全な補充作業にリンクすることもできます。</span><span class="sxs-lookup"><span data-stu-id="1880e-117">A part 2 feature will also allow linking to any incomplete replenishment work as needed.</span></span>
<!--feature detail end -->











