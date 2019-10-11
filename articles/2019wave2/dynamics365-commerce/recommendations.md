---
title: 製品レコメンデーションと個人用設定
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 09/16/2019
ms.assetid: ae63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: brendans
dynamics365pdf: true
ms.openlocfilehash: 77935cfd941600152af6495d979467d03899d3c2
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2142275"
---
# <a name="product-recommendations-and-personalization"></a><span data-ttu-id="26680-102">製品レコメンデーションと個人用設定</span><span class="sxs-lookup"><span data-stu-id="26680-102">Product recommendations and personalization</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="26680-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="26680-103">Enabled for</span></span>    |  <span data-ttu-id="26680-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="26680-104">Public preview</span></span> | <span data-ttu-id="26680-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="26680-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="26680-106">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="26680-106">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="26680-107">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="26680-107">Oct 2019</span></span>| -|





## <a name="business-value"></a><span data-ttu-id="26680-108">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="26680-108">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="26680-109">レコメンデーションは、すべての小売スペースにまたがる革新的なビジネス アプリケーションであり、リッチで魅力的なカスタマイズされた製品の見つけやすさのエクスペリエンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="26680-109">Recommendations is a transformative business application that spans all retail spaces to create rich, engaging, and tailored product discovery experiences.</span></span> <span data-ttu-id="26680-110">レコメンデーションを使用すると、お客様は、必要な製品をすばやく簡単に見つけることができ (妥当)、当初に意図していたよりも多くのものを見つけることができます (クロスセル、アップセル)。そのすべてを優れたエクスペリエンスで行うことができます (満足)。</span><span class="sxs-lookup"><span data-stu-id="26680-110">Recommendations enables customers to easily and quickly find products they need and want (relevant), find more than they had originally intended (cross-sell, upsell), all the while having an experience that serves them well (satisfaction).</span></span>

<span data-ttu-id="26680-111">小売業者にとって、検出は、すべての顧客と製品にわたって変換の機会を生み出すさまざまなテクノロジ (ML-AI、アルゴリズム、人間、またはハイブリッド) によって大規模に促進されます。その結果、総売上収益と最終顧客の満足度が向上します。</span><span class="sxs-lookup"><span data-stu-id="26680-111">For retailers, the discovery is powered by a variety of technologies at large scale (ML-AI, algorithms, humans, or a hybrid) that create conversion opportunities across all customers and products, resulting in more all-up sales revenue and end-customer satisfaction.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="26680-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="26680-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="26680-113">Dynamics 365 Commerce レコメンデーション サービスでは、トランザクション データと製品情報を使用して、小売チャネルに適切にスコープ設定された機械学習およびトレンド リストが生成されます。</span><span class="sxs-lookup"><span data-stu-id="26680-113">The Dynamics 365 Commerce Recommendations service uses transactions data and product information to generate machine learning and trending lists appropriately scoped for a retail channel.</span></span>

<span data-ttu-id="26680-114">レコメンデーション リストの種類と具体的な例は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="26680-114">Types of recommendations lists and specific examples include:</span></span>

-  <span data-ttu-id="26680-115">パーソナライズされたレコメンデーション: 過去にストアから何かを購入したサインイン済みの最終顧客ごとの「あなたへのお勧め」。</span><span class="sxs-lookup"><span data-stu-id="26680-115">Personalized recommendations:  "Pick for you" for each signed-in end customer who has purchased something from the store in the past.</span></span>

-  <span data-ttu-id="26680-116">カートとチェックアウトのレコメンデーション: 「よく一緒に購入されるもの」リスト。</span><span class="sxs-lookup"><span data-stu-id="26680-116">Cart and checkout recommendations: “Frequently bought together” lists.</span></span>

-  <span data-ttu-id="26680-117">製品詳細ページ (PDP) のレコメンデーション: 「他のユーザーはこちらも購入しています。」</span><span class="sxs-lookup"><span data-stu-id="26680-117">Product detail page (PDP) recommendations: “People also buy these.”</span></span>

-  <span data-ttu-id="26680-118">ランディング ページと閲覧ページ: 「新規」、「ベスト セラー」、「人気上昇中」。</span><span class="sxs-lookup"><span data-stu-id="26680-118">Landing and browse pages: “New,” “Best selling,” “Trending.”</span></span>

-  <span data-ttu-id="26680-119">人間が精選したリスト: 小売業者が作成した「スポットライト」コレクション (「母の日セール」など)。</span><span class="sxs-lookup"><span data-stu-id="26680-119">Human-curated lists: “Spotlight,” collections created by retailers (for example, “Mother’s Day sale”).</span></span>

<span data-ttu-id="26680-120">すべてのリストには、小売業者が修正を加えて特定の製品をリストの先頭に含めたり不要な品目を除外したりできる機能があるため、AI の能力と人間の知識が連携します。</span><span class="sxs-lookup"><span data-stu-id="26680-120">All of the lists have the capability for retailers to make amendments to include specific products at the beginning of the list, or exclude unwanted items, thus marrying the power of AI with human knowledge.</span></span>

<span data-ttu-id="26680-121">オムニチャネルのレコメンデーションを利用可能にすることで、小売業者は製品が簡単に見つかるエクスペリエンスを買い物客に提供して、売上収益とユーザーの満足度を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="26680-121">By making omnichannel recommendations available, retailers can increase sales revenue and user satisfaction by providing an easy product discovery experience for shoppers.</span></span>
<!--feature detail end -->











