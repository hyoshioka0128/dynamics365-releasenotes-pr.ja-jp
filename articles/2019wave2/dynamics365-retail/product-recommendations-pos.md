---
title: POS での製品レコメンデーション
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 09/13/2019
ms.assetid: 9772d018-c2d4-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: bsokolov
dynamics365pdf: true
ms.openlocfilehash: 9042d4cec827b5d9e948eb53a807558d2a1b6d71
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2659778"
---
# <a name="product-recommendations-in-pos"></a><span data-ttu-id="63a78-102">POS での製品レコメンデーション</span><span class="sxs-lookup"><span data-stu-id="63a78-102">Product Recommendations in POS</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="63a78-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="63a78-103">Enabled for</span></span>    |  <span data-ttu-id="63a78-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="63a78-104">Public preview</span></span> | <span data-ttu-id="63a78-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="63a78-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="63a78-106">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="63a78-106">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="63a78-107">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="63a78-107">Nov 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="63a78-108">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="63a78-108">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="63a78-109">製品レコメンデーションは、すべての小売スペースにまたがる革新的なビジネス アプリケーションであり、リッチで魅力的なカスタマイズされた製品の見つけやすさのエクスペリエンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="63a78-109">Product Recommendations is a transformative business application that spans across all retail spaces to create rich, engaging, and tailored product discovery experiences.</span></span> <span data-ttu-id="63a78-110">製品レコメンデーションを使用すると、お客様は、必要な製品をすばやく簡単に見つけることができ (妥当)、当初に意図していたよりも多くのものを見つけることができます (クロスセル、アップセル)。そのすべてを優れたエクスペリエンスで行うことができます (満足)。</span><span class="sxs-lookup"><span data-stu-id="63a78-110">Product Recommendations enables customers to easily and quickly find products they need and want (relevant), find more than they had originally intended (cross-sell, upsell), all the while having an experience that serves them well (satisfaction).</span></span> <span data-ttu-id="63a78-111">小売業者にとって、検出は、すべての顧客と製品にわたって変換の機会を生み出すさまざまなテクノロジ (ML-AI、アルゴリズム、人間、またはハイブリッド) によって大規模に促進されます。その結果、総売上収益と最終顧客の満足度が向上します。</span><span class="sxs-lookup"><span data-stu-id="63a78-111">For retailers, the discovery is powered by a variety of technologies at large scale (ML-AI, algorithms, humans, or a hybrid) that create conversion opportunities across all customers and products, resulting in more all-up sales revenue and end-customer satisfaction.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="63a78-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="63a78-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="63a78-113">製品レコメンデーション サービスでは、トランザクション データと製品情報を使用して、それぞれの小売チャネルに適切にスコープ設定された機械学習およびトレンド リストが生成されます。</span><span class="sxs-lookup"><span data-stu-id="63a78-113">The Product Recommendations service uses transactions data and product information to generate machine learning and trending lists appropriately scoped for the respective retail channel.</span></span>

<span data-ttu-id="63a78-114">レコメンデーション リストの種類と具体的な例は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="63a78-114">Types of recommendations lists and specific examples include:</span></span>

-  <span data-ttu-id="63a78-115">トランザクション画面のレコメンデーション:「よく一緒に購入されるもの」リスト。</span><span class="sxs-lookup"><span data-stu-id="63a78-115">Transaction screen recommendations: “Frequently bought together” list.</span></span>

-  <span data-ttu-id="63a78-116">製品詳細ページ (PDP) のレコメンデーション: 製品をシードとして活用する、コンテキストに応じた「お勧めの製品」リスト。</span><span class="sxs-lookup"><span data-stu-id="63a78-116">Product details page (PDP) recommendations: contextual “Recommended Products” list, leveraging the product as seed.</span></span>

-  <span data-ttu-id="63a78-117">顧客の詳細ページのレコメンデーション: 顧客の欲しい物のリストをシードとして活用する、コンテキストに応じた「お勧めの製品」リスト。</span><span class="sxs-lookup"><span data-stu-id="63a78-117">Customer details page recommendations: contextual "Recommended Products" list, leveraging the customer's wish list as seed.</span></span>

<span data-ttu-id="63a78-118">すべてのリストには、小売業者が修正を加えて特定の製品をリストの先頭に含めたり不要な品目を除外したりできる機能があります。</span><span class="sxs-lookup"><span data-stu-id="63a78-118">All of the lists have the capability for retailers to make amendments to include specific products at the beginning of the list or exclude unwanted items.</span></span> <span data-ttu-id="63a78-119">この機能は、AI の能力と人間の知識を組み合わせたものです。</span><span class="sxs-lookup"><span data-stu-id="63a78-119">This functionality combines the power of AI with human knowledge.</span></span> 

<span data-ttu-id="63a78-120">オムニチャネルのレコメンデーションを利用可能にすることで、小売業者は製品が簡単に見つかるエクスペリエンスを買い物客に提供して、売上収益とユーザーの満足度を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="63a78-120">By making omnichannel recommendations available, retailers can increase sales revenue and user satisfaction by providing an easy product discovery experience for shoppers.</span></span>
<!--feature detail end -->









