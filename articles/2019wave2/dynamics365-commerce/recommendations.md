---
title: レコメンデーション
description: レコメンデーションにより、顧客は必要な製品をすばやく簡単に見つけることができます。
author: relnotes
ms.reviewer: josaw
ms.date: 02/06/2020
ms.assetid: ae63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: moonma
dynamics365pdf: true
ms.openlocfilehash: 035fcfd425354ca0dcd2d8d9cdb8f18cb414f90c
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3058664"
---
# <a name="recommendations"></a><span data-ttu-id="5ef27-103">レコメンデーション</span><span class="sxs-lookup"><span data-stu-id="5ef27-103">Recommendations</span></span>


| <span data-ttu-id="5ef27-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="5ef27-104">Enabled for</span></span>    |  <span data-ttu-id="5ef27-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5ef27-105">Public preview</span></span> | <span data-ttu-id="5ef27-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="5ef27-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5ef27-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="5ef27-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="5ef27-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5ef27-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5ef27-109">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5ef27-109">Oct 1, 2019</span></span>| <span data-ttu-id="5ef27-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5ef27-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5ef27-111">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="5ef27-111">Feb 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="5ef27-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5ef27-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5ef27-113">レコメンデーションは、すべての小売スペースにまたがる革新的なビジネス アプリケーションであり、リッチで魅力的なカスタマイズされた製品の見つけやすさのエクスペリエンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="5ef27-113">Recommendations is a transformative business application that spans all retail spaces to create rich, engaging, and tailored product discovery experiences.</span></span> <span data-ttu-id="5ef27-114">レコメンデーションを使用すると、お客様は、必要な製品をすばやく簡単に見つけることができ (**妥当**)、当初に意図していたよりも多くのものを見つけることができます (**クロスセル**、**アップセル**)。そのすべてを優れたエクスペリエンスで行うことができます (**満足**)。</span><span class="sxs-lookup"><span data-stu-id="5ef27-114">Recommendations enables customers to easily and quickly find the products they need and want (**relevant**), find more than they had originally intended (**cross-sell**, **upsell**), all the while having an experience that serves them well (**satisfaction**).</span></span> <span data-ttu-id="5ef27-115">小売業者にとって、検出は、すべての顧客と製品にわたって変換の機会を生み出すさまざまなテクノロジ (ML-AI、アルゴリズム、人間、またはハイブリッド) によって大規模に促進されます。その結果、総売上収益と顧客の満足度が向上します。</span><span class="sxs-lookup"><span data-stu-id="5ef27-115">For retailers, the discovery is powered by a variety of technologies at large scale (ML-AI, algorithms, humans, or a hybrid) that drive conversion opportunities across all customers and products, resulting in more all-up sales revenue and customer satisfaction.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5ef27-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5ef27-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5ef27-117">レコメンデーション アプリケーションは、トランザクションデータと顧客の行動データを使用して、高スケールかつ少ない待ち時間で機械学習 (ML) およびトレンド リストを生成するように構築されています。</span><span class="sxs-lookup"><span data-stu-id="5ef27-117">The Recommendations application is built for high scale and low latency using transactional data and customer behavioral data to generate machine learning (ML) and trending lists.</span></span>

<span data-ttu-id="5ef27-118">レコメンデーション リストのタイプと具体的な例は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="5ef27-118">Types of recommendation lists and specific examples include the following:</span></span>

-  <span data-ttu-id="5ef27-119">**パーソナライズされたレコメンデーション**: レコメンデーション サービスは、小売業者がオンラインおよび POS エクスペリエンスで実装できる 3 つの新機能をリリースしています。</span><span class="sxs-lookup"><span data-stu-id="5ef27-119">**Personalized recommendations**: The Recommendations service is releasing three new features for retailers to implement in their online and POS experiences:</span></span>

   - <span data-ttu-id="5ef27-120">**あなたへのお勧め**: 認証済みユーザーは、購入履歴 (オムニチャネル) に基づいて、「あなたへのお勧め」と呼ばれる推奨製品のパーソナライズされたリストを表示できます。</span><span class="sxs-lookup"><span data-stu-id="5ef27-120">**Picks for you**: An authenticated user can see a personalized list of suggested products called “Picks for you” based on their purchase history (omnichannel).</span></span> <span data-ttu-id="5ef27-121">このリストは、eコマースおよび 販売時点管理 (POS) ストア エクスペリエンスで利用できます。</span><span class="sxs-lookup"><span data-stu-id="5ef27-121">This list is available for e-commerce and point of sale (POS) store experiences.</span></span> 

   - <span data-ttu-id="5ef27-122">**リストの個人用設定**: 小売業者は、既存のレコメンデーション リスト (すべてのグラフ、"その他のおすすめ"、"よく一緒に購入される製品") に "個人用設定を適用" できます。これにより、ユーザーが以前に購入したアイテムがリストから削除されます。</span><span class="sxs-lookup"><span data-stu-id="5ef27-122">**List personalization**: Retailers can “Apply personalization” to existing recommendation lists (all charts, "People also like," and "Frequently bought together"), which will remove items from the list that a user has previously purchased.</span></span>  

   - <span data-ttu-id="5ef27-123">**個人用設定のオプトアウト**: 小売業者は、ユーザーのプライバシーを保護するための GDPR 要件を順守して、アカウント管理の個人用設定シナリオから顧客をオプトアウトできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5ef27-123">**Personalization opt-out**: Retailers can now opt customers out of personalization scenarios from account management, honoring GDPR requirements to protect the privacy of their users.</span></span>

-  <span data-ttu-id="5ef27-124">**カートとチェックアウトのレコメンデーション**: "よく一緒に購入されるもの" リスト。</span><span class="sxs-lookup"><span data-stu-id="5ef27-124">**Cart and checkout recommendations**: “Frequently bought together” lists.</span></span>

-  <span data-ttu-id="5ef27-125">**製品詳細ページ (PDP) のレコメンデーション**: "他のユーザーはこちらも購入しています"。</span><span class="sxs-lookup"><span data-stu-id="5ef27-125">**Product detail page (PDP) recommendations**: “People also buy these."</span></span>

-  <span data-ttu-id="5ef27-126">**ランディング ページと閲覧ページ**: "新規"、"ベスト セラー"、"人気上昇中"。</span><span class="sxs-lookup"><span data-stu-id="5ef27-126">**Landing and browse pages**: “New,” “Best-selling,” “Trending.”</span></span>

-  <span data-ttu-id="5ef27-127">**人間が精選したリスト**: 小売業者が作成した「スポットライト」コレクション (「母の日セール」など)。</span><span class="sxs-lookup"><span data-stu-id="5ef27-127">**Human editorial lists**: “Spotlight” collections created by retailers (for example, “Mother’s Day sale”).</span></span>

<span data-ttu-id="5ef27-128">Dynamics 365 Commerce のすべての小売チャネルでレコメンデーションを利用可能にし、顧客のショッピング エクスペリエンス全体で一貫したエクスペリエンスを提供することで、小売業者はすべてのチャネルで売上収益を増やし、ユーザーの満足度を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="5ef27-128">By making recommendations available for all retail channels in Dynamics 365 Commerce and providing a consistent experience throughout the shopping experience for the customer, retailers can increase sales revenue and increase customer satisfaction across all channels.</span></span>

<span data-ttu-id="5ef27-129">![レコメンデーション リスト](media/recommendations_1.jpg "レコメンデーション リスト")</span><span class="sxs-lookup"><span data-stu-id="5ef27-129">![Recommendations list](media/recommendations_1.jpg "Recommendations list")</span></span>

<span data-ttu-id="5ef27-130">![その他のレコメンデーション](media/recommendations_2.png "その他のレコメンデーション")</span><span class="sxs-lookup"><span data-stu-id="5ef27-130">![Other recommendations](media/recommendations_2.png "Other recommendations")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="5ef27-131">関連項目</span><span class="sxs-lookup"><span data-stu-id="5ef27-131">See also</span></span>
<span data-ttu-id="5ef27-132">[機能の探索](https://aka.ms/ROGC19RW2ROV4) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="5ef27-132">[Feature exploration](https://aka.ms/ROGC19RW2ROV4) (video)</span></span>

<span data-ttu-id="5ef27-133">[製品レコメンデーションの概要](https://docs.microsoft.com/dynamics365/commerce/product-recommendations) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="5ef27-133">[Product recommendations overview](https://docs.microsoft.com/dynamics365/commerce/product-recommendations) (docs)</span></span>
