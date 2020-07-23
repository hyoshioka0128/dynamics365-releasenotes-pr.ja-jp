---
title: 計画
description: 流通シナリオの計画最適化サポート。
author: relnotes
ms.reviewer: ''
ms.date: 06/19/2020
ms.assetid: 19ec0ec2-57cb-e911-a96f-000d3a4f33c1
ms.topic: structure
ms.service: business-applications
ms.author: crytt
dynamics365pdf: true
ms.openlocfilehash: f251cadcb9528c9e73669b9f9b5a8ee8f6892ada
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3522391"
---
# <a name="planning"></a><span data-ttu-id="ec805-103">計画</span><span class="sxs-lookup"><span data-stu-id="ec805-103">Planning</span></span>

[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

<!--structure start-->
<span data-ttu-id="ec805-104">計画の最適化は、大量のデータを迅速に処理するために特別に設計されています。</span><span class="sxs-lookup"><span data-stu-id="ec805-104">Planning Optimization is specifically designed for fast calculations with massive data volume.</span></span> <span data-ttu-id="ec805-105">計画の最適化サービスは ERP システムからマスター プラン実行の負荷を取り除き、サーバーの負荷を最小に抑えるようデータ ストリームを処理します。</span><span class="sxs-lookup"><span data-stu-id="ec805-105">The Planning Optimization service will remove the load of master planning from your ERP system and work with a data stream that minimizes the server load.</span></span>

<span data-ttu-id="ec805-106">このリリースでは、流通シナリオの計画最適化サポートが有効になります。</span><span class="sxs-lookup"><span data-stu-id="ec805-106">This release enables Planning Optimization support for distribution scenarios.</span></span> <span data-ttu-id="ec805-107">計画製造オーダーの作成の計画最適化サポートはプレビュー段階であり、機能管理を使用して有効にすることができます。</span><span class="sxs-lookup"><span data-stu-id="ec805-107">Planning Optimization support for creation of planned production orders is available in preview and can be enabled via feature management.</span></span>

## <a name="customer-benefits"></a><span data-ttu-id="ec805-108">お客様のメリット</span><span class="sxs-lookup"><span data-stu-id="ec805-108">Customer benefits</span></span>

<span data-ttu-id="ec805-109">**バッチ ジョブを計画するために毎日時間を確保する必要がなくなる。**</span><span class="sxs-lookup"><span data-stu-id="ec805-109">**Eliminate daily time reserved for planning batch job.**</span></span>

* <span data-ttu-id="ec805-110">大規模なデータセットを持つお客様は、すべてのバッチ ジョブを夜間に完了するのに問題があります。</span><span class="sxs-lookup"><span data-stu-id="ec805-110">Customers with large data sets have issues completing all batch jobs at night.</span></span>
* <span data-ttu-id="ec805-111">年中無休で稼働する企業は、アクティブ ユーザーがいなければ時間帯を取得することが困難です。</span><span class="sxs-lookup"><span data-stu-id="ec805-111">Businesses that operate 24/7 have difficulty getting time slots without active users.</span></span>

<span data-ttu-id="ec805-112">**将来の事業の成長により計画システムが過負荷にならないという安心感を与える。**</span><span class="sxs-lookup"><span data-stu-id="ec805-112">**Comfort that future business growth will not overload the planning system.**</span></span>

* <span data-ttu-id="ec805-113">ハイパースケーラブルなサービスにより、計画が迅速に行われ、パフォーマンスに影響を与えることがなくなります。</span><span class="sxs-lookup"><span data-stu-id="ec805-113">A hyper-scalable service ensures that planning will be fast and without performance implications.</span></span>
* <span data-ttu-id="ec805-114">ダウンタイムなしでの最新バージョンへの自動アップグレード。</span><span class="sxs-lookup"><span data-stu-id="ec805-114">Automated upgrade to latest version without downtime.</span></span>
* <span data-ttu-id="ec805-115">日次または週次よりも高い頻度で計画を実行できる。</span><span class="sxs-lookup"><span data-stu-id="ec805-115">More frequent planning runs—not just daily or weekly.</span></span> 

<span data-ttu-id="ec805-116">**夜間の実行を待たずに、営業時間中に計画を更新する。**</span><span class="sxs-lookup"><span data-stu-id="ec805-116">**Update plan during office hours – you don’t have to wait for the nightly run.**</span></span>

* <span data-ttu-id="ec805-117">変更された計画パラメーターは数分で反映されます。</span><span class="sxs-lookup"><span data-stu-id="ec805-117">Changed planning parameters are reflected in minutes.</span></span> <span data-ttu-id="ec805-118">夜間の実行を待つ必要はありません。</span><span class="sxs-lookup"><span data-stu-id="ec805-118">No waiting for the nightly run.</span></span>
* <span data-ttu-id="ec805-119">計画のシミュレーションの結果をすぐに確認し、目的の結果が得られるまでパラメーターをオンザフライで調整し続けます。</span><span class="sxs-lookup"><span data-stu-id="ec805-119">See the result of planning simulations right away and keep tweaking parameters on the fly until you get the desired result.</span></span>

<span data-ttu-id="ec805-120">**総リードタイムの短縮による顧客サービスの向上。**</span><span class="sxs-lookup"><span data-stu-id="ec805-120">**Improved customer service with shorter total lead time.**</span></span>

* <span data-ttu-id="ec805-121">新しい需要がより早く検出され、管理されます。</span><span class="sxs-lookup"><span data-stu-id="ec805-121">New demands are detected and managed earlier.</span></span> 
* <span data-ttu-id="ec805-122">夜間の計画を待つ必要がないため、同日に注文できます。</span><span class="sxs-lookup"><span data-stu-id="ec805-122">Order same day because you don’t have to wait for the nightly plan.</span></span>
* <span data-ttu-id="ec805-123">供給がすぐに注文されるため、多くのお客様がリード タイムを 1 日短縮できます。</span><span class="sxs-lookup"><span data-stu-id="ec805-123">Many customers can save one day of lead time because supply is ordered right away.</span></span>

<span data-ttu-id="ec805-124">**在庫レベルの削減によるコストと資本の節約。**</span><span class="sxs-lookup"><span data-stu-id="ec805-124">**Cost and capital savings by reduced inventory levels.**</span></span>

* <span data-ttu-id="ec805-125">補充が速くなるため、必要な安全在庫が少なくなります。</span><span class="sxs-lookup"><span data-stu-id="ec805-125">Less safety stock is needed due to faster replenishment.</span></span>


## <a name="availability"></a><span data-ttu-id="ec805-126">公開形態</span><span class="sxs-lookup"><span data-stu-id="ec805-126">Availability</span></span>
<span data-ttu-id="ec805-127">計画最適化を開始する方法の詳細については、「[概要](https://aka.ms/poGetStarted)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ec805-127">For more information on how to get started with Planning Optimization, see [Get Started](https://aka.ms/poGetStarted).</span></span>
<!--structure end-->



