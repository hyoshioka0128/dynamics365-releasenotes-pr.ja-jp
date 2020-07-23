---
title: 顧客の注文に対して出荷/集荷元倉庫を選択するための柔軟なオプションを提供する
description: この機能により、DOM ルールに対して出荷倉庫を選択するオプションが管理者に提供されます。
author: relnotes
ms.reviewer: josaw
ms.date: 06/08/2020
ms.assetid: b5b8b554-948a-ea11-a812-000d3a563be2
ms.topic: article
ms.service: business-applications
ms.author: rapraj
dynamics365pdf: true
ms.openlocfilehash: b9a7c8ef52262f1ce0428c866c898d9489310da9
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3488133"
---
# <a name="provide-flexible-options-for-choosing-shipping-or-pickup-warehouse-for-customer-orders"></a><span data-ttu-id="5702d-103">顧客の注文に対して出荷/集荷元倉庫を選択するための柔軟なオプションを提供する</span><span class="sxs-lookup"><span data-stu-id="5702d-103">Provide flexible options for choosing shipping or pickup warehouse for customer orders</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="5702d-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="5702d-104">Enabled for</span></span>    |  <span data-ttu-id="5702d-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5702d-105">Public preview</span></span> | <span data-ttu-id="5702d-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="5702d-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5702d-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="5702d-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="5702d-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5702d-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5702d-109">2020 年 5 月 25 日</span><span class="sxs-lookup"><span data-stu-id="5702d-109">May 25, 2020</span></span>| <span data-ttu-id="5702d-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="5702d-110">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="5702d-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5702d-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5702d-112">この機能により、分散型注文管理 (DOM) フルフィルメント プロファイルに対してルールを実行する際の効率が向上します。</span><span class="sxs-lookup"><span data-stu-id="5702d-112">This functionality will improve efficiency when running rules against distributed order management (DOM) fulfillment profiles.</span></span> <span data-ttu-id="5702d-113">この機能を使用すると、DOM ルールが出荷倉庫の場所に対してのみ実行され、より大きな場所のサブセットに対しては実行されなくなります。</span><span class="sxs-lookup"><span data-stu-id="5702d-113">The functionality ensures that DOM rules run only against the shipping warehouse locations and not against the larger subset of locations.</span></span> 

<span data-ttu-id="5702d-114">DOM フルフィルメント プロファイルに関連付けられた、フルフィルメント グループに含まれている出荷倉庫のフィルター処理されたリストのみを使用することにより、DOM ルールがより効果的かつ効率的に実行されるようにします。</span><span class="sxs-lookup"><span data-stu-id="5702d-114">By only using the filtered list of  shipping warehouses that are included in the fulfillment group, as associated to the DOM fulfillment profile, we ensure that the DOM rules are run more effectively and efficiently.</span></span>  
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5702d-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5702d-115">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="5702d-116">出荷される品目の一部またはすべてに対して注文が作成されると、DOM は出荷場所のリストからの製品の在庫状況に基づいて、注文を処理するための最適化された計画を実行します。</span><span class="sxs-lookup"><span data-stu-id="5702d-116">When orders are created for either some or all of the items to be shipped, DOM will run the optimized plan for processing the orders based on availability of products from a list of shipping locations.</span></span>  

- <span data-ttu-id="5702d-117">注文管理サービスが処理されて注文が実行されると、DOM プロファイルは関連付けられているフルフィルメント グループから利用可能なすべての出荷場所を調べ、そのグループ内の出荷場所に対してルールを実行します。</span><span class="sxs-lookup"><span data-stu-id="5702d-117">When the order management services are processed to run the order, the DOM profiles will look at all the available shipping locations from the associated fulfilment groups and then run rules against the shipping locations in the groups.</span></span> 

- <span data-ttu-id="5702d-118">関連付けられている出荷場所またはフルフィルメント グループがない場合、DOM フルフィルメント プロファイル内のルールを実行する現在のプロセスに変わりはありません。</span><span class="sxs-lookup"><span data-stu-id="5702d-118">If there are no shipping locations or fulfilment groups associated, there will be no change from the current process of running the rules in the DOM fulfilment profile.</span></span> 
<!--feature detail end -->









