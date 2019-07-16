---
title: 製品の見つけやすさの改善
description: 製品の見つけやすさの改善
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 8463278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: asharchw
dynamics365pdf: true
ms.openlocfilehash: e3fe93939ded4eadba80aa13052e81eb3a6f03d6
ms.sourcegitcommit: ce44199897bc0c276cd02c99cc1d216f198734b0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1691702"
---
# <a name="enhancements-for-product-discoverability"></a><span data-ttu-id="cd5c2-103">製品の見つけやすさの改善</span><span class="sxs-lookup"><span data-stu-id="cd5c2-103">Enhancements for product discoverability</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="cd5c2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cd5c2-104">Enabled for</span></span>    |  <span data-ttu-id="cd5c2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cd5c2-105">Public preview</span></span> | <span data-ttu-id="cd5c2-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="cd5c2-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="cd5c2-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="cd5c2-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="cd5c2-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="cd5c2-108">October 2019</span></span>| |


## <a name="business-value"></a><span data-ttu-id="cd5c2-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="cd5c2-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="cd5c2-110">製品の見つけやすさは、小売顧客がカテゴリをブラウズし、検索とフィルタリングを使用して製品を見つけることができるようにするための迅速で簡単な方法です。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-110">Product discoverability is a quick and easy way for a retail customer to be able to discover products by browsing through categories and using search and filtering.</span></span> <span data-ttu-id="cd5c2-111">製品の見つけやすさは、顧客との対話において、全小売チャネルにわたって重要なツールです。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-111">Product discovery is a primary tool for customer interaction across all retail channels.</span></span> 

<span data-ttu-id="cd5c2-112">顧客は、Web 検索エンジン、洗練された eコマース Web サイト、入力中に関連検索を提案するソーシャル アプリ、ファセット ナビゲーション、一致用語ハイライト表示などの機能をすべてほぼ瞬時の応答時間で利用することに慣れています。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-112">Customers are used to web search engines, sophisticated e-commerce websites, and social apps that offer relevant search suggestions as you type, faceted navigation, highlighting matching terms, and more—all with near-instantaneous response times.</span></span> <span data-ttu-id="cd5c2-113">消費者は、適切な製品を十分にすばやく見つけられないと、パフォーマンスがより優れた別の小売サイトに躊躇なく移動します。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-113">If consumers do not find the right product quickly enough, they do not hesitate to move to another retail site that offers better performance.</span></span> 

<span data-ttu-id="cd5c2-114">Dynamics 365 for Retail での製品の見つけやすさを向上させるこの取り組みにより、小売業者は消費者のショッピング体験を支援してその期待を満たすことができ、eコマースや POS などのすべてのチャネルにおいて消費者の維持率とコンバージョン率を高めるのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-114">This investment for enhancing product discoverability in Dynamics 365 for Retail will empower retailers to meet expectations of their consumers by assisting them in their shopping journey, which would help retailers grow their share of consumer retention and conversion rates across all channels, including both e-commerce and POS.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="cd5c2-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cd5c2-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cd5c2-116">Microsoft が市場に提供しているソリューションで使用可能なリファイナーを使用した検索、閲覧、フィルターの現在のサポートは低速で、特に堅牢でもありません。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-116">Current support for search, browse, and filter using refiners available with our in-market solution is slow and not particularly robust.</span></span> <span data-ttu-id="cd5c2-117">Retail の新機能により製品の見つけやすさが向上し、検出はスケーラブルかつ高パフォーマンスになります。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-117">New functionality in Retail will provide better product discoverability, and discovery will be scalable and performant.</span></span>

-  <span data-ttu-id="cd5c2-118">**閲覧と検索**: 製品の見つけやすさは、主に情報を取得するための検索とコンテンツのナビゲーションに依存するため、オムニチャネル エクスペリエンスにとって検索の関連性とパフォーマンスを高めることが重要です。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-118">**Browse and search**: Search relevance and performance is key to our omnichannel experience, as product discovery relies primarily on search for information retrieval and content navigation.</span></span> <span data-ttu-id="cd5c2-119">効果的かつ効率的な検索は、コンバージョン率の向上に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-119">An effective and efficient search helps increase conversion.</span></span> 

-  <span data-ttu-id="cd5c2-120">**リファイナー/ファセット ナビゲーション**: ファセット ナビゲーションは、用語セット内の用語に紐付けられているリファイナーに対してフィルターを適用することで、ユーザーがコンテンツをより簡単に閲覧できるようにします。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-120">**Refiners/faceted navigation**: Faceted navigation helps users browse for content more easily by filtering on refiners that are tied to terms in a term set.</span></span> <span data-ttu-id="cd5c2-121">ファセット ナビゲーションを使用すると、追加のページを作成することなく、用語セット内の異なる用語に対して別個のリファイナーを構成できます。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-121">By using faceted navigation, you can configure different refiners for different terms in a term set without having to create additional pages.</span></span>

- <span data-ttu-id="cd5c2-122">**イマーシブな自動提案**: 現在の自動提案では、一致するキーワードの検索をトリガーするキーワードだけが表示されます。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-122">**Immersive auto-suggest**: Current auto-suggest shows only keywords that trigger search for the matching keyword.</span></span> <span data-ttu-id="cd5c2-123">新しい機能拡張により、ユーザーは製品詳細に直接移動できる製品へのリンクを表示できます。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-123">With new enhancements, users will be able to surface links to products, directly navigable to product details.</span></span> <span data-ttu-id="cd5c2-124">ユーザーがカテゴリ内で一致するキーワードの数を確認し、そのカテゴリのキーワードの検索をトリガーできるようにする "さまざまなカテゴリ内のキーワードの照合" もサポートされます。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-124">There will also be support for "keywords match in various categories" which enables users to see the count of matching keywords in categories and trigger the search for the keyword for that category.</span></span> 

- <span data-ttu-id="cd5c2-125">**並べ替え**: この機能拡張により、ユーザーは価格、製品名、製品番号、新規、ベストセラー、最近追加されたものなどの詳細で検索結果を並べ替え、参照し、絞り込むことができます。</span><span class="sxs-lookup"><span data-stu-id="cd5c2-125">**Sort**: With this enhancement, users will be able to sort search, browse, and refine search results by details, such as price, product name, product number, new, top-selling, or recently added.</span></span>
<!--feature detail end -->










