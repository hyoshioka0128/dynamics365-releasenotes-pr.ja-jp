---
title: 容積測定データの製品バリアントの取り込み
description: この機能は、AWAX 機能を標準の WHS 機能に統合するという Blue Horseshoe との契約から始まります。 この機能により、製品バリアントの物理寸法を保存し、輸送費や保管に必要なスペースに関連した正しい容積測定データの計算など、後工程でこれらを使用できるようになります。
author: relnotes
ms.reviewer: josaw
ms.date: 10/07/2019
ms.assetid: aa62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: henrikan
dynamics365pdf: true
ms.openlocfilehash: a54336b1cab422b3bb6b927119fd3cfa43718ff6
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660593"
---
# <a name="product-variant-uptake-of-volumetric-data"></a><span data-ttu-id="d46ba-104">容積測定データの製品バリアントの取り込み</span><span class="sxs-lookup"><span data-stu-id="d46ba-104">Product variant uptake of volumetric data</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="d46ba-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="d46ba-105">Enabled for</span></span>    |  <span data-ttu-id="d46ba-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d46ba-106">Public preview</span></span> | <span data-ttu-id="d46ba-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="d46ba-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d46ba-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="d46ba-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="d46ba-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="d46ba-109">Jan 2020</span></span>| <span data-ttu-id="d46ba-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="d46ba-110">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="d46ba-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d46ba-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d46ba-112">物理寸法が異なるバリアントのある製品を購入、製造、または販売する企業は、正確な容積測定データをキャプチャでき、正確な容積測定データに依存し制約される料金、スペース、および機器を正しく計算して最適に使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="d46ba-112">Businesses that buy, make, or sell products with variants that have different physical dimensions can now capture the precise volumetric data so that charges, space, and equipment that are dependent on and constrained by accurate volumetric data are correctly calculated and optimally used.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d46ba-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d46ba-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d46ba-114">この機能により、製品バリアントの物理寸法を作成できるようになります。</span><span class="sxs-lookup"><span data-stu-id="d46ba-114">This functionality adds the ability to create physical dimensions for a product variant.</span></span> <span data-ttu-id="d46ba-115">寸法の値 (長さ、幅、奥行き) は、異なる製品バリアントの容積測定データを表します。</span><span class="sxs-lookup"><span data-stu-id="d46ba-115">The dimensional values (length, width, and depth) give the volumetric data of a distinct product variant.</span></span> <span data-ttu-id="d46ba-116">容積測定データは、製品バリアントの正確な容積測定情報に基づく料金の計算など、保管スペース、倉庫設備、コンテナ サイズの要件などを計算するために、倉庫および輸送プロセスで使用されます。</span><span class="sxs-lookup"><span data-stu-id="d46ba-116">The volumetric data is used in warehouse and transportation processes to calculate storage space, warehouse equipment, container size requirements, and more, including calculating charges based on the exact volumetric information for the product variant.</span></span> <span data-ttu-id="d46ba-117">この機能を使用すると、大きいサイズのシャツと小さいサイズのシャツで容積測定要件が異なるようなシナリオが可能になり、計算された容積測定データを下流のプロセスで使用できます。</span><span class="sxs-lookup"><span data-stu-id="d46ba-117">The feature enables scenarios such as one in which one unit of large-size shirts has a different volumetric requirement than one unit of small-size shirts and then uses the calculated volumetric data for downstream processes.</span></span>
<!--feature detail end -->









