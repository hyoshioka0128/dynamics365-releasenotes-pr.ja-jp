---
title: POS での製品レコメンデーション
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 11/25/2019
ms.assetid: 9772d018-c2d4-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: moonma
dynamics365pdf: true
ms.openlocfilehash: 0d591b349c7d92b50b0600402a40f5779a487c3b
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889987"
---
# <a name="product-recommendations-in-pos"></a><span data-ttu-id="b4f32-102">POS での製品レコメンデーション</span><span class="sxs-lookup"><span data-stu-id="b4f32-102">Product Recommendations in POS</span></span>


| <span data-ttu-id="b4f32-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="b4f32-103">Enabled for</span></span>    |  <span data-ttu-id="b4f32-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b4f32-104">Public preview</span></span> | <span data-ttu-id="b4f32-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="b4f32-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b4f32-106">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="b4f32-106">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="b4f32-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b4f32-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b4f32-108">2019 年 11 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b4f32-108">Nov 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="b4f32-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b4f32-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b4f32-110">製品レコメンデーションは、すべての小売スペースにまたがる革新的なビジネス アプリケーションであり、リッチで魅力的なカスタマイズされた製品の見つけやすさのエクスペリエンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="b4f32-110">Product Recommendations is a transformative business application that spans all retail spaces to create rich, engaging, and tailored product discovery experiences.</span></span> <span data-ttu-id="b4f32-111">製品レコメンデーションを使用すると、お客様は、必要な製品をすばやく簡単に見つけることができ (妥当)、当初に意図していたよりも多くのものを見つけることができます (クロスセル、アップセル)。そのすべてを優れたエクスペリエンスで行うことができます (満足)。</span><span class="sxs-lookup"><span data-stu-id="b4f32-111">Product Recommendations enables customers to easily and quickly find products they need and want (relevant), find more than they had originally intended (cross-sell, upsell), all the while having an experience that serves them well (satisfaction).</span></span> <span data-ttu-id="b4f32-112">小売業者にとって、検出は、すべての顧客と製品にわたって変換の機会を生み出すさまざまなテクノロジ (ML-AI、アルゴリズム、人間、またはハイブリッド) によって大規模に促進されます。その結果、総売上収益と最終顧客の満足度が向上します。</span><span class="sxs-lookup"><span data-stu-id="b4f32-112">For retailers, the discovery is powered by a variety of technologies at large scale (ML-AI, algorithms, humans, or a hybrid) that create conversion opportunities across all customers and products, resulting in more all-up sales revenue and end-customer satisfaction.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b4f32-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b4f32-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b4f32-114">製品レコメンデーション サービスでは、トランザクション データと製品情報を使用して、それぞれの小売チャネルに適切にスコープ設定された機械学習およびトレンド リストが生成されます。</span><span class="sxs-lookup"><span data-stu-id="b4f32-114">The Product Recommendations service uses transactions data and product information to generate machine learning and trending lists appropriately scoped for the respective retail channel.</span></span>

<span data-ttu-id="b4f32-115">レコメンデーション リストの種類と具体的な例は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="b4f32-115">Types of recommendations lists and specific examples include:</span></span>

-  <span data-ttu-id="b4f32-116">トランザクション画面のレコメンデーション:「よく一緒に購入されるもの」リスト。</span><span class="sxs-lookup"><span data-stu-id="b4f32-116">Transaction screen recommendations: “Frequently bought together” list.</span></span>

-  <span data-ttu-id="b4f32-117">製品詳細ページ (PDP) のレコメンデーション: 製品をシードとして活用する、コンテキストに応じた「お勧めの製品」リスト。</span><span class="sxs-lookup"><span data-stu-id="b4f32-117">Product details page (PDP) recommendations: contextual “Recommended Products” list, leveraging the product as seed.</span></span>

-  <span data-ttu-id="b4f32-118">パーソナライズされた顧客の詳細ページのレコメンデーション: 認証されたユーザーに、購入履歴 (オムニチャネル) に基づいて呼び出される推奨製品のパーソナライズされたリストを提供する、コンテキストに応じた「お客様にお勧めの製品」リスト。</span><span class="sxs-lookup"><span data-stu-id="b4f32-118">Personalized customer details page recommendations: contextual "Recommended for customer" list, providing authenticated users a personalized list of suggested products called based on their purchase history (omni-channel).</span></span>  


<span data-ttu-id="b4f32-119">すべてのリストには、小売業者が修正を加えて特定の製品をリストの先頭に含めたり不要な品目を除外したりできる機能があります。</span><span class="sxs-lookup"><span data-stu-id="b4f32-119">All of the lists have the capability for retailers to make amendments to include specific products at the beginning of the list or exclude unwanted items.</span></span> <span data-ttu-id="b4f32-120">この機能は、AI の能力と人間の知識を組み合わせたものです。</span><span class="sxs-lookup"><span data-stu-id="b4f32-120">This functionality combines the power of AI with human knowledge.</span></span> 

<span data-ttu-id="b4f32-121">オムニチャネルのレコメンデーションを利用可能にすることで、小売業者は製品が簡単に見つかるエクスペリエンスを買い物客に提供して、売上収益とユーザーの満足度を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="b4f32-121">By making omnichannel recommendations available, retailers can increase sales revenue and user satisfaction by providing an easy product discovery experience for shoppers.</span></span>
<!--feature detail end -->









