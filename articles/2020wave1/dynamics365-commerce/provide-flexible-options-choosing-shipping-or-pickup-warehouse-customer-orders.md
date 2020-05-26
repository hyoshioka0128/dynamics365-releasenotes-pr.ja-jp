---
title: 顧客の注文に対して出荷/集荷元倉庫を選択するための柔軟なオプションを提供する
description: この機能により、DOM ルールに対して出荷倉庫を選択するオプションが管理者に提供されます。
author: relnotes
ms.reviewer: josaw
ms.date: 04/30/2020
ms.assetid: b5b8b554-948a-ea11-a812-000d3a563be2
ms.topic: article
ms.service: business-applications
ms.author: rapraj
dynamics365pdf: true
ms.openlocfilehash: b605c21f337df03a0d2352419d6a859e4b675588
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350920"
---
# <a name="provide-flexible-options-for-choosing-shipping-or-pickup-warehouse-for-customer-orders"></a><span data-ttu-id="c42cd-103">顧客の注文に対して出荷/集荷元倉庫を選択するための柔軟なオプションを提供する</span><span class="sxs-lookup"><span data-stu-id="c42cd-103">Provide flexible options for choosing shipping or pickup warehouse for customer orders</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="c42cd-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c42cd-104">Enabled for</span></span>    |  <span data-ttu-id="c42cd-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c42cd-105">Public preview</span></span> | <span data-ttu-id="c42cd-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c42cd-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c42cd-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c42cd-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c42cd-108">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="c42cd-108">May 2020</span></span>| <span data-ttu-id="c42cd-109">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="c42cd-109">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c42cd-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c42cd-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c42cd-111">この機能により、分散型注文管理 (DOM) フルフィルメント プロファイルに対してルールを実行する際の効率が向上します。</span><span class="sxs-lookup"><span data-stu-id="c42cd-111">This functionality will improve efficiency when running rules against distributed order management (DOM) fulfillment profiles.</span></span> <span data-ttu-id="c42cd-112">この機能を使用すると、DOM ルールが出荷倉庫の場所に対してのみ実行され、より大きな場所のサブセットに対しては実行されなくなります。</span><span class="sxs-lookup"><span data-stu-id="c42cd-112">The functionality ensures that DOM rules run only against the shipping warehouse locations and not against the larger subset of locations.</span></span> 

<span data-ttu-id="c42cd-113">DOM フルフィルメント プロファイルに関連付けられた、フルフィルメント グループに含まれている出荷倉庫のフィルター処理されたリストのみを使用することにより、DOM ルールがより効果的かつ効率的に実行されるようにします。</span><span class="sxs-lookup"><span data-stu-id="c42cd-113">By only using the filtered list of  shipping warehouses that are included in the fulfillment group, as associated to the DOM fulfillment profile, we ensure that the DOM rules are run more effectively and efficiently.</span></span>  
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c42cd-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c42cd-114">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="c42cd-115">出荷される品目の一部またはすべてに対して注文が作成されると、DOM は出荷場所のリストからの製品の在庫状況に基づいて、注文を処理するための最適化された計画を実行します。</span><span class="sxs-lookup"><span data-stu-id="c42cd-115">When orders are created for either some or all of the items to be shipped, DOM will run the optimized plan for processing the orders based on availability of products from a list of shipping locations.</span></span>  

- <span data-ttu-id="c42cd-116">注文管理サービスが処理されて注文が実行されると、DOM プロファイルは関連付けられているフルフィルメント グループから利用可能なすべての出荷場所を調べ、そのグループ内の出荷場所に対してルールを実行します。</span><span class="sxs-lookup"><span data-stu-id="c42cd-116">When the order management services are processed to run the order, the DOM profiles will look at all the available shipping locations from the associated fulfilment groups and then run rules against the shipping locations in the groups.</span></span> 

- <span data-ttu-id="c42cd-117">関連付けられている出荷場所またはフルフィルメント グループがない場合、DOM フルフィルメント プロファイル内のルールを実行する現在のプロセスに変わりはありません。</span><span class="sxs-lookup"><span data-stu-id="c42cd-117">If there are no shipping locations or fulfilment groups associated, there will be no change from the current process of running the rules in the DOM fulfilment profile.</span></span> 
<!--feature detail end -->









