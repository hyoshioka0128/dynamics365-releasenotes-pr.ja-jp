---
title: 壁へのプット/ストアへのプット
description: この機能を使用すると、構成可能な基準に基づいて、パッケージ品目ステージング領域への製品の統合が要求されるシナリオが可能になります。
author: relnotes
ms.reviewer: josaw
ms.date: 08/02/2019
ms.assetid: 8a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 595d5f0f0be9f8ef02f580cad1ef7f8e89a05ac1
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141296"
---
# <a name="put-to-wallput-to-store"></a><span data-ttu-id="0efc2-103">壁へのプット/ストアへのプット</span><span class="sxs-lookup"><span data-stu-id="0efc2-103">Put to wall/Put to store</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="0efc2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0efc2-104">Enabled for</span></span>    |  <span data-ttu-id="0efc2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0efc2-105">Public preview</span></span> | <span data-ttu-id="0efc2-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="0efc2-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0efc2-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="0efc2-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="0efc2-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="0efc2-108">Aug 2019</span></span>| <span data-ttu-id="0efc2-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="0efc2-109">Oct 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="0efc2-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0efc2-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0efc2-111">この機能では、構成可能な基準に基づいて、パッケージ品目ステージング領域への製品の統合が要求されるシナリオを処理できます。</span><span class="sxs-lookup"><span data-stu-id="0efc2-111">With this feature, you can handle scenarios where consolidation of product to a prepack staging area based on configurable criteria is required.</span></span> <span data-ttu-id="0efc2-112">単一のターゲット ライセンス プレートへのピッキングが可能になり、クラスター ピッキングより多くのプット位置を活用できるため、店舗に出荷する企業や小さい商品を行う企業は、ピッキング時間が短縮されるため、この機能を使用するメリットがあります。</span><span class="sxs-lookup"><span data-stu-id="0efc2-112">Companies shipping to stores or handling small items will benefit from this functionality due to decreased picking time—it allows for picking to a single target license plate, and it can leverage a greater number of put positions than cluster picking.</span></span> <span data-ttu-id="0efc2-113">壁へのプット ワークフローでは、ピッキングされた製品は、さまざまな種類のコンテナーに分けるため選別場所に送られます。</span><span class="sxs-lookup"><span data-stu-id="0efc2-113">The put-to-wall workflow directs picked products to a sorting location for distribution into various types of containers.</span></span> <span data-ttu-id="0efc2-114">一般に、各選別場所には複数の選別位置が含まれます。</span><span class="sxs-lookup"><span data-stu-id="0efc2-114">Generally, each sorting location includes multiple sort positions.</span></span> <span data-ttu-id="0efc2-115">各選別位置は、ビジネス プロセス、最も一般的な送り先、店舗、出荷、または積荷によって設定された基準に従って割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="0efc2-115">Each sort position is assigned according to the criteria set by the business process, most commonly destination, store, shipment, or load.</span></span> 

<span data-ttu-id="0efc2-116">ピッキングされた製品は、選別ステーションに運ばれ、注文、送り先、出荷、または積荷に関連する数量で選別位置に分配されます。</span><span class="sxs-lookup"><span data-stu-id="0efc2-116">Once the product is picked, it is taken to the sorting station and distributed to the sort position by the quantity associated to the order, destination, shipment, or load.</span></span> <span data-ttu-id="0efc2-117">コンテナーがいっぱいになるか完成すると、ビジネス プロセスに応じて、さらに処理するためにステージング場所または出荷場所に移動されます。</span><span class="sxs-lookup"><span data-stu-id="0efc2-117">When a container is full or complete, it is moved to a staging location or a shipping location for further handling, depending on the business process.</span></span> <span data-ttu-id="0efc2-118">技術的には、壁にプット機能により、個々の品目または数量を、ピッキング中に割り当てられたターゲット ライセンス プレートから取得し、選別位置に選別し、通常はコンテナーを表す選別ライセンス プレートに割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="0efc2-118">Technically, the put-to-wall functionality allows for individual items or quantities to be taken from the target license plate assigned during picking, sorted to a sort position, and assigned to a sort license plate, typically representing a container.</span></span> <span data-ttu-id="0efc2-119">選別位置がクローズされると、倉庫管理設定に従って作業が作成されます。</span><span class="sxs-lookup"><span data-stu-id="0efc2-119">As the sort position is closed, work is created according to the warehouse management setup.</span></span>
<!--feature detail end -->











