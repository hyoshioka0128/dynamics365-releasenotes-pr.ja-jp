---
title: 梱包ステーションの後のパレット作成
description: パレット作成では、梱包ステーションの後で梱包済みコンテナーを正しいパレットに並べて、梱包階層を作成することができます。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: 8662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 55408d8a572720945c8588e02276b0c3f8ae14bc
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1855111"
---
# <a name="pallet-building-post-packing-station"></a><span data-ttu-id="ba418-103">梱包ステーションの後のパレット作成</span><span class="sxs-lookup"><span data-stu-id="ba418-103">Pallet building post-packing station</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="ba418-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ba418-104">Enabled for</span></span>    |  <span data-ttu-id="ba418-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ba418-105">Public preview</span></span> | <span data-ttu-id="ba418-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ba418-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="ba418-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="ba418-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ba418-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="ba418-108">August 2019</span></span>| <span data-ttu-id="ba418-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="ba418-109">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="ba418-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ba418-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ba418-111">パレット作成では、梱包ステーションの後で梱包済みコンテナーを正しいパレットに並べて、梱包階層を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="ba418-111">Pallet building offers the ability to sort packed containers to a correct pallet after the packing station and to build a packing hierarchy.</span></span> <span data-ttu-id="ba418-112">後で、すべての梱包済みコンテナーを取り込む単一の作業指示書により、そのようなパレットを正しいステージング場所に移動できます。</span><span class="sxs-lookup"><span data-stu-id="ba418-112">Such pallets can later be moved to the correct staging location with a single work order capturing all packed containers.</span></span> <span data-ttu-id="ba418-113">倉庫作業者は、梱包済みコンテナーを置くパレット、パレットに置くことができるボックスの最大数、および特定のシナリオで必要なパレットの数を自由に選択できます。</span><span class="sxs-lookup"><span data-stu-id="ba418-113">The warehouse worker has the freedom to choose which pallet the packed container should be put to, the maximum number of boxes a pallet can have, and how many pallets are needed in any given scenario.</span></span> 

<span data-ttu-id="ba418-114">コンテナー梱包ポリシーと並べ替え場所プロファイルは、梱包ステーションから梱包済みコンテナーを取り扱う際の柔軟性を高めるためにまとめて導入されました。</span><span class="sxs-lookup"><span data-stu-id="ba418-114">A container packing policy and a sorting location profile are introduced, which together offer greater flexibility in handling packed containers from the packing station.</span></span> <span data-ttu-id="ba418-115">さまざまな統合基準が導入され、ユーザーが各移動先パレットの基準を割り当てた後、後続のすべての梱包済みコンテナーは一致するパレットに誘導され、作業員は作業指図のプット ステップを確認するだけで済みます。</span><span class="sxs-lookup"><span data-stu-id="ba418-115">Different consolidation criteria are introduced—after the user has assigned a criterion for each destination pallet, all subsequent packed containers will be guided to the matching pallet, and the worker must confirm only the put step of the work order.</span></span> <span data-ttu-id="ba418-116">パレットがいっぱいになると、パレット位置は閉じられ、1 つの単位として移動できます。</span><span class="sxs-lookup"><span data-stu-id="ba418-116">When the pallet is full, the pallet position is closed, and it can be moved as a single unit.</span></span> <span data-ttu-id="ba418-117">これにより、倉庫内での梱包済みコンテナーの移動に必要な手順が減るため、コンテナーの取り扱いが速くなり、概要がわかりやすくなります。</span><span class="sxs-lookup"><span data-stu-id="ba418-117">This means faster handling and better overview of containers because it reduces the necessary steps for movement of packed containers within the warehouse.</span></span> <span data-ttu-id="ba418-118">この機能では、複数のコンテナーを 1 つのパレットにマージするときにコンテナー詰めプロセスを使用しませんが、既存のコンテナー グループ ライセンス プレート機能が拡張されます。</span><span class="sxs-lookup"><span data-stu-id="ba418-118">This feature does not use containerization processes when merging containers to a pallet, but it extends the existing container group license plate functionality.</span></span> <span data-ttu-id="ba418-119">したがって、パレットの内容一覧はこの拡張では印刷できません。</span><span class="sxs-lookup"><span data-stu-id="ba418-119">The pallet content list can therefore not be printed via this enhancement.</span></span> <span data-ttu-id="ba418-120">この機能は既存のシステム機能と統合されるため、変更される場合があります。</span><span class="sxs-lookup"><span data-stu-id="ba418-120">This feature is subject to change as it is integrated with existing system features.</span></span>
<!--feature detail end -->











