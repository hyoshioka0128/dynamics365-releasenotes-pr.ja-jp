---
title: 製品の見つけやすさの改善
description: 製品の見つけやすさの改善
author: relnotes
ms.reviewer: josaw
ms.date: 04/24/2020
ms.assetid: 8463278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: asharchw
dynamics365pdf: true
ms.openlocfilehash: 4bc1321d0d1795e06243ce2aaa531de3aeda4e14
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320294"
---
# <a name="enhancements-for-product-discoverability"></a><span data-ttu-id="a9272-103">製品の見つけやすさの改善</span><span class="sxs-lookup"><span data-stu-id="a9272-103">Enhancements for product discoverability</span></span>


| <span data-ttu-id="a9272-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a9272-104">Enabled for</span></span>    |  <span data-ttu-id="a9272-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a9272-105">Public preview</span></span> | <span data-ttu-id="a9272-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="a9272-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a9272-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a9272-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="a9272-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a9272-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a9272-109">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a9272-109">Oct 1, 2019</span></span>| <span data-ttu-id="a9272-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a9272-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a9272-111">2020 年 1 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a9272-111">Jan 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a9272-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a9272-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a9272-113">製品の見つけやすさは、小売顧客がカテゴリをブラウズし、検索とフィルタリングを使用して製品を見つけることができるようにするための迅速で簡単な方法です。</span><span class="sxs-lookup"><span data-stu-id="a9272-113">Product discoverability is a quick and easy way for a retail customer to be able to discover products by browsing through categories and using search and filtering.</span></span> <span data-ttu-id="a9272-114">製品の見つけやすさは、顧客との対話において、全小売チャネルにわたって重要なツールです。</span><span class="sxs-lookup"><span data-stu-id="a9272-114">Product discovery is a primary tool for customer interaction across all retail channels.</span></span> 

<span data-ttu-id="a9272-115">顧客は、Web 検索エンジン、洗練された eコマース Web サイト、入力中に関連検索を提案するソーシャル アプリ、ファセット ナビゲーション、一致用語ハイライト表示などの機能をすべてほぼ瞬時の応答時間で利用することに慣れています。</span><span class="sxs-lookup"><span data-stu-id="a9272-115">Customers are used to web search engines, sophisticated e-commerce websites, and social apps that offer relevant search suggestions as you type, faceted navigation, highlighting matching terms, and more—all with near-instantaneous response times.</span></span> <span data-ttu-id="a9272-116">消費者は、適切な製品を十分にすばやく見つけられないと、パフォーマンスがより優れた別の小売サイトに躊躇なく移動します。</span><span class="sxs-lookup"><span data-stu-id="a9272-116">If consumers do not find the right product quickly enough, they do not hesitate to move to another retail site that offers better performance.</span></span> 

<span data-ttu-id="a9272-117">Dynamics 365 Retail での製品の見つけやすさを向上させるこの投資により、小売業者は消費者のショッピング体験を支援してその期待を満たすことができ、eコマースや POS などのすべてのチャネルにおいて消費者の維持率とコンバージョン率を高めるのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="a9272-117">This investment for enhancing product discoverability in Dynamics 365 Retail will empower retailers to meet expectations of their consumers by assisting them in their shopping journey, which would help retailers grow their share of consumer retention and conversion rates across all channels, including both e-commerce and POS.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a9272-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a9272-118">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a9272-119">Microsoft が市場に提供しているソリューションで使用可能なリファイナーを使用した検索、閲覧、フィルターの現在のサポートは低速で、特に堅牢でもありません。</span><span class="sxs-lookup"><span data-stu-id="a9272-119">Current support for search, browse, and filter using refiners available with our in-market solution is slow and not particularly robust.</span></span> <span data-ttu-id="a9272-120">Retail の新機能により製品の見つけやすさが向上し、検出はスケーラブルかつ高パフォーマンスになります。</span><span class="sxs-lookup"><span data-stu-id="a9272-120">New functionality in Retail will provide better product discoverability, and discovery will be scalable and performant.</span></span>

-  <span data-ttu-id="a9272-121">**閲覧と検索**: 製品の見つけやすさは、主に情報を取得するための検索とコンテンツのナビゲーションに依存するため、オムニチャネル エクスペリエンスにとって検索の関連性とパフォーマンスを高めることが重要です。</span><span class="sxs-lookup"><span data-stu-id="a9272-121">**Browse and search**: Search relevance and performance is key to our omnichannel experience, as product discovery relies primarily on search for information retrieval and content navigation.</span></span> <span data-ttu-id="a9272-122">効果的かつ効率的な検索は、コンバージョン率の向上に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="a9272-122">An effective and efficient search helps increase conversion.</span></span> 

-  <span data-ttu-id="a9272-123">**リファイナー/ファセット ナビゲーション**: ファセット ナビゲーションは、用語セット内の用語に紐付けられているリファイナーに対してフィルターを適用することで、ユーザーがコンテンツをより簡単に閲覧できるようにします。</span><span class="sxs-lookup"><span data-stu-id="a9272-123">**Refiners/faceted navigation**: Faceted navigation helps users browse for content more easily by filtering on refiners that are tied to terms in a term set.</span></span> <span data-ttu-id="a9272-124">ファセット ナビゲーションを使用すると、追加のページを作成することなく、用語セット内の異なる用語に対して別個のリファイナーを構成できます。</span><span class="sxs-lookup"><span data-stu-id="a9272-124">By using faceted navigation, you can configure different refiners for different terms in a term set without having to create additional pages.</span></span>

- <span data-ttu-id="a9272-125">**イマーシブな自動提案**: 現在の自動提案では、一致するキーワードの検索をトリガーするキーワードだけが表示されます。</span><span class="sxs-lookup"><span data-stu-id="a9272-125">**Immersive auto-suggest**: Current auto-suggest shows only keywords that trigger search for the matching keyword.</span></span> <span data-ttu-id="a9272-126">新しい機能拡張により、ユーザーは製品詳細に直接移動できる製品へのリンクを表示できます。</span><span class="sxs-lookup"><span data-stu-id="a9272-126">With new enhancements, users will be able to surface links to products, directly navigable to product details.</span></span> <span data-ttu-id="a9272-127">ユーザーがカテゴリ内で一致するキーワードの数を確認し、そのカテゴリのキーワードの検索をトリガーできるようにする "さまざまなカテゴリ内のキーワードの照合" もサポートされます。</span><span class="sxs-lookup"><span data-stu-id="a9272-127">There will also be support for "keywords match in various categories," which enables users to see the count of matching keywords in categories and trigger the search for the keyword for that category.</span></span> 

- <span data-ttu-id="a9272-128">**並べ替え**: この機能拡張により、ユーザーは価格、製品名、製品番号、新規、ベストセラー、最近追加されたものなどの詳細で検索結果を並べ替え、参照し、絞り込むことができます。</span><span class="sxs-lookup"><span data-stu-id="a9272-128">**Sort**: With this enhancement, users will be able to sort search, browse, and refine search results by details, such as price, product name, product number, new, top-selling, or recently added.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="a9272-129">関連項目</span><span class="sxs-lookup"><span data-stu-id="a9272-129">See also</span></span>

<!--docs start-->
<span data-ttu-id="a9272-130">[クラウドを利用した検索の概要](https://docs.microsoft.com/dynamics365/commerce/cloud-powered-search-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="a9272-130">[Cloud-powered search overview](https://docs.microsoft.com/dynamics365/commerce/cloud-powered-search-overview) (docs)</span></span>
<!--docs end-->
