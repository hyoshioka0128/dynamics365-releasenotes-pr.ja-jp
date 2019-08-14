---
title: クライアンテリング - 製品コレクションを使用したクロス セル
description: クライアンテリング - 製品コレクションを使用したクロス セル
author: relnotes
ms.reviewer: josaw
ms.date: 07/22/2019
ms.assetid: cde02389-9b6b-e911-a95f-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: shajain
dynamics365pdf: true
ms.openlocfilehash: ad77d4b7a6809aefc87e5f1b49567b2bbf10a0c5
ms.sourcegitcommit: 4101748c25acf79b22e31a01b73969500926ff91
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1793444"
---
# <a name="clienteling--cross-sell-using-product-collections"></a><span data-ttu-id="75a79-103">クライアンテリング - 製品コレクションを使用したクロス セル</span><span class="sxs-lookup"><span data-stu-id="75a79-103">Clienteling – Cross sell using product collections</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="75a79-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="75a79-104">Enabled for</span></span>    |  <span data-ttu-id="75a79-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="75a79-105">Public preview</span></span> | <span data-ttu-id="75a79-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="75a79-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="75a79-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="75a79-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="75a79-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="75a79-108">October 2019</span></span>| <span data-ttu-id="75a79-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="75a79-109">January 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="75a79-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="75a79-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="75a79-111">小売業者は一般に、さまざまなアップセルやクロスセルの手法を活用してトランザクションのバスケット サイズを増やす革新的な方法を探しています。</span><span class="sxs-lookup"><span data-stu-id="75a79-111">Retailers are commonly looking for innovative ways to increase the basket size of transactions by leveraging various upselling and cross-selling techniques.</span></span> <span data-ttu-id="75a79-112">クロスセルの一般的なメカニズムの 1 つは、特定の目的で製品のコレクションを表示することです。</span><span class="sxs-lookup"><span data-stu-id="75a79-112">One of the popular mechanisms for cross-selling is to display a collection of products for a particular intent.</span></span> <span data-ttu-id="75a79-113">たとえば、ファッション小売業者はパーティー衣装やビジネス ウェアのコレクションを作成し、家具小売業者はリビング ルームやベッドルームのコレクションを作成します。レストランはコース料理のコレクションを作成し、園芸小売業者は特定の気候に合った植物、土壌、堆肥のコレクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="75a79-113">For example, a fashion retailer might create a collection for party attire or office attire, a furniture retailer might create a collection for a living room or bedroom, a restaurant might create a collection for a multi-course meal, and a gardening retailer might create a collection for plants, soil, and compost for a particular climate.</span></span> <span data-ttu-id="75a79-114">顧客はこれらのコレクションを閲覧し、そのコレクションから 1 つ以上の品目を購入できます。これにより、バスケット サイズが大きくなります。</span><span class="sxs-lookup"><span data-stu-id="75a79-114">Customers can browse through these collections and buy one or more items from the collection, which results in a larger basket size.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="75a79-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="75a79-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="75a79-116">この機能により、さまざまな店舗に補充できる "製品コレクション" を商品管理マネージャーが作成できる機能が導入されます。</span><span class="sxs-lookup"><span data-stu-id="75a79-116">This feature introduces the capability for merchandizing managers to create "product collections" that can be assorted to various stores.</span></span> <span data-ttu-id="75a79-117">**製品詳細**ページから、顧客はこの製品が属するコレクションに簡単に移動し、コレクションから 1 つ以上の品目を購入することができます。</span><span class="sxs-lookup"><span data-stu-id="75a79-117">From the **Product detail** page, customers will be able to easily navigate to the collections where this product belongs and buy one or more items from the collection.</span></span> <span data-ttu-id="75a79-118">コレクションのすべての品目が購入された場合に小売業者が割引を作成することもできます。</span><span class="sxs-lookup"><span data-stu-id="75a79-118">Retailers will also be able to create discounts if all the items of the collections are bought.</span></span>

<span data-ttu-id="75a79-119">販売担当者は、プライベート コレクションを作成して、承認を受けるために商品管理マネージャーに送信することができます。</span><span class="sxs-lookup"><span data-stu-id="75a79-119">Sales associates will be able to create private collections and send them for approval to the merchandizing managers.</span></span> <span data-ttu-id="75a79-120">小売業者は、コレクションの業績が良い従業員に報酬を与えることを決定することもできます。</span><span class="sxs-lookup"><span data-stu-id="75a79-120">The retailers can optionally decide to reward employees whose collections perform well.</span></span>
<!--feature detail end -->











