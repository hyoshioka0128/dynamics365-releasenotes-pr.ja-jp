---
title: レコメンデーション
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 10/01/2019
ms.assetid: ae63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: bsokolov
dynamics365pdf: true
ms.openlocfilehash: ef61c62846a900e8ddb1a2032b3721472f4b522e
ms.sourcegitcommit: b0fef00d4f04f2507056a10ecce699767c669119
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2662243"
---
# <a name="recommendations"></a><span data-ttu-id="1da50-102">レコメンデーション</span><span class="sxs-lookup"><span data-stu-id="1da50-102">Recommendations</span></span>


| <span data-ttu-id="1da50-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="1da50-103">Enabled for</span></span>    |  <span data-ttu-id="1da50-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1da50-104">Public preview</span></span> | <span data-ttu-id="1da50-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="1da50-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1da50-106">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="1da50-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1da50-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1da50-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1da50-108">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="1da50-108">Oct 1, 2019</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="1da50-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1da50-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1da50-110">レコメンデーションは、すべての小売スペースにまたがる革新的なビジネス アプリケーションであり、リッチで魅力的なカスタマイズされた製品の見つけやすさのエクスペリエンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="1da50-110">Recommendations is a transformative business application that spans all retail spaces to create rich, engaging, and tailored product discovery experiences.</span></span> <span data-ttu-id="1da50-111">レコメンデーションを使用すると、お客様は、必要な製品をすばやく簡単に見つけることができ (**妥当**)、当初に意図していたよりも多くのものを見つけることができます (**クロスセル**、**アップセル**)。そのすべてを優れたエクスペリエンスで行うことができます (**満足**)。</span><span class="sxs-lookup"><span data-stu-id="1da50-111">Recommendations enables customers to easily and quickly find the products they need and want (**relevant**), find more than they had originally intended (**cross-sell**, **upsell**), all the while having an experience that serves them well (**satisfaction**).</span></span> <span data-ttu-id="1da50-112">小売業者にとって、検出は、すべての顧客と製品にわたって変換の機会を生み出すさまざまなテクノロジ (ML-AI、アルゴリズム、人間、またはハイブリッド) によって大規模に促進されます。その結果、総売上収益と顧客の満足度が向上します。</span><span class="sxs-lookup"><span data-stu-id="1da50-112">For retailers, the discovery is powered by a variety of technologies at large scale (ML-AI, algorithms, humans, or a hybrid) that drive conversion opportunities across all customers and products resulting in more all-up sales revenue and customer satisfaction.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1da50-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1da50-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1da50-114">レコメンデーション アプリケーションは、トランザクションデータと顧客の行動データを使用して、高スケールかつ少ない待ち時間で機械学習 (ML) およびトレンド リストを生成するように構築されています。</span><span class="sxs-lookup"><span data-stu-id="1da50-114">The Recommendations application is built for high scale and low latency using transactional data and customer behavioral data to generate machine learning (ML) and trending lists.</span></span>

<span data-ttu-id="1da50-115">レコメンデーション リストのタイプと具体的な例は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="1da50-115">Types of recommendation lists and specific examples include the following:</span></span>

-  <span data-ttu-id="1da50-116">**パーソナライズされたレコメンデーション**: 過去にストアから何かを購入したサインイン済みの最終顧客ごとの "あなたへのお勧め"。</span><span class="sxs-lookup"><span data-stu-id="1da50-116">**Personalized recommendations**: "Picks for you" for each signed-in customer who has purchased something from the store in the past.</span></span>

-  <span data-ttu-id="1da50-117">**カートとチェックアウトのレコメンデーション**: "よく一緒に購入されるもの" リスト。</span><span class="sxs-lookup"><span data-stu-id="1da50-117">**Cart and checkout recommendations**: “Frequently bought together” lists.</span></span>

-  <span data-ttu-id="1da50-118">**製品詳細ページ (PDP) のレコメンデーション**: "他のユーザーはこちらも購入しています"。</span><span class="sxs-lookup"><span data-stu-id="1da50-118">**Product detail page (PDP) recommendations**: “People also buy these."</span></span>

-  <span data-ttu-id="1da50-119">**ランディング ページと閲覧ページ**: "新規"、"ベスト セラー"、"人気上昇中"。</span><span class="sxs-lookup"><span data-stu-id="1da50-119">**Landing and browse pages**: “New,” “Best-selling,” “Trending.”</span></span>

-  <span data-ttu-id="1da50-120">**人間が精選したリスト**: 小売業者が作成した "スポットライト" コレクション ("母の日セール" など)。</span><span class="sxs-lookup"><span data-stu-id="1da50-120">**Human editorial lists**: “Spotlight” collections created by retailers (e.g., “Mother’s Day sale”).</span></span>

<span data-ttu-id="1da50-121">Dynamics 365 Commerce のすべての小売チャネルでレコメンデーションを利用可能にし、顧客のショッピング エクスペリエンス全体で一貫したエクスペリエンスを提供することで、小売業者はすべてのチャネルで売上収益を増やし、ユーザーの満足度を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="1da50-121">By making recommendations available for all retail channels in Dynamics 365 Commerce and providing a consistent experience throughout the shopping experience for the customer, retailers can increase sales revenue and increase customer satisfaction across all channels.</span></span>

<span data-ttu-id="1da50-122">![レコメンデーション 1](media/recommendations_1.jpg "レコメンデーション 1")</span><span class="sxs-lookup"><span data-stu-id="1da50-122">![Recommendations 1](media/recommendations_1.jpg "Recommendations 1")</span></span>

<span data-ttu-id="1da50-123">![レコメンデーション 2](media/recommendations_2.png "レコメンデーション 2")</span><span class="sxs-lookup"><span data-stu-id="1da50-123">![Recommendations 2](media/recommendations_2.png "Recommendations 2")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="1da50-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="1da50-124">See also</span></span>
<span data-ttu-id="1da50-125">[機能の探索](https://aka.ms/ROGC19RW2ROV4) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="1da50-125">[Feature exploration](https://aka.ms/ROGC19RW2ROV4) (video)</span></span>

<span data-ttu-id="1da50-126">[製品レコメンデーションの概要](https://docs.microsoft.com/dynamics365/commerce/product-recommendations) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="1da50-126">[Product recommendations overview](https://docs.microsoft.com/dynamics365/commerce/product-recommendations) (docs)</span></span>
