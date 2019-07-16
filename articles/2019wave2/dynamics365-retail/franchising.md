---
title: フランチャイズ
description: フランチャイズ
author: anpurush
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 01da6c1e-126c-e911-a95f-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: anpurush
dynamics365pdf: true
ms.openlocfilehash: e311bb1fb05acdc15b3e4b6dcb013963ed51546b
ms.sourcegitcommit: 4620697dc1f4fc6903504a55406f3d22af75e361
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1693750"
---
# <a name="franchising"></a><span data-ttu-id="f5aeb-103">フランチャイズ</span><span class="sxs-lookup"><span data-stu-id="f5aeb-103">Franchising</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="f5aeb-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f5aeb-104">Enabled for</span></span>    |  <span data-ttu-id="f5aeb-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f5aeb-105">Public preview</span></span> | <span data-ttu-id="f5aeb-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f5aeb-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="f5aeb-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="f5aeb-107">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="f5aeb-108">2020 年 3 月</span><span class="sxs-lookup"><span data-stu-id="f5aeb-108">March 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="f5aeb-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f5aeb-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f5aeb-110">フランチャイズは、親会社 ("フランチャイザー") が他の起業家や企業 ("フランチャイジー") に親会社のブランド、製品、戦略、および商標の使用を許可するビジネス モデルです。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-110">Franchising is a business model in which a parent company (the “franchisor”) allows other entrepreneurs and businesses (the “franchisee”) to use the parent company's brand, products, strategies, and trademarks.</span></span> <span data-ttu-id="f5aeb-111">引き換えに、フランチャイジーはフランチャイザーに対価を支払いますが、これは一回限りまたは定期的な手数料と、収益に基づくロイヤルティの組み合わせである可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-111">In exchange, the franchisee pays a consideration to the franchisor which could be a combination of one-time or recurring fees and royalties based on revenues.</span></span> <span data-ttu-id="f5aeb-112">ほとんどのシナリオでは、フランチャイザーはフランチャイジーに、フランチャイズ契約の一部として、広告やトレーニング、IT システムなどを含むサポートも提供します。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-112">In most scenarios, the franchisor also provides the franchisee with support, including advertising and training, IT systems, and so on as part of the franchising agreement.</span></span> 

<span data-ttu-id="f5aeb-113">フランチャイズは、新規店舗が第三者によって所有および運営されている場合、親会社のコストがはるかに低くなるため、企業が所有する店舗を追加するより速くて安価な拡張方法です。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-113">Franchising is a faster, cheaper form of expansion than adding company-owned stores because it costs the parent company much less when new stores are owned and operated by a third party.</span></span> <span data-ttu-id="f5aeb-114">反対に、親会社は各新規店舗からの収益の一部しか取得できないため、収益成長の可能性はより限られています。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-114">On the flip side, potential for revenue growth is more limited because the parent company will only earn a percentage of the earnings from each new store.</span></span>  

<span data-ttu-id="f5aeb-115">フランチャイズ ビジネス モデルは、ファーストフード レストラン、ホテル、レンタルおよびリース サービスなどの複数の業界で広く使用されていますが、小売業界でのその重要性と利用は以下の指標に基づいて明らかなように明確ではありません。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-115">While the franchising business model is widely used in multiple industries, such as fast food restaurants and hotel, rental, and leasing services, its significance and usage in the retail industry is incomprehensible as is evident based on the below metrics:</span></span>
-   <span data-ttu-id="f5aeb-116">小売売上高の 50% がフランチャイズ店舗からのものです (出典:国際フランチャイズ協会)</span><span class="sxs-lookup"><span data-stu-id="f5aeb-116">50% of retail sales come from franchised outlets (Source: International Franchise Association)</span></span>
-   <span data-ttu-id="f5aeb-117">米国では 80 万の店舗を持つ 3000 の小売フランチャイザー (出典: 『Retail Management』、Berman、Evans 著)</span><span class="sxs-lookup"><span data-stu-id="f5aeb-117">3000 retail franchisors with 800,000 outlets in the US (Source: Retail Management by Berman, Evans)</span></span>

<span data-ttu-id="f5aeb-118">現在、Dynamics 365 では、すべてのフランチャイジー間でマスター データと参照データを共有する機能、フランチャイジー間でのオムニチャネル シナリオをサポートする機能など、小売業者がフランチャイジーの店舗をモデル化するための完全な機能は提供されていません。この機能は、顧客や企業が要求する、パートナーと顧客が同じものを利用してエンドツーエンドのフランチャイズ ソリューションを構築できるようにするコア プラットフォームとアプリ レベルの機能を提供するためのものです。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-118">As of date, Dynamics 365 does not provide fully rounded capability for a retailer to model franchisee stores in their environment, which includes the capability to share master and referential data among all the franchisees, support omnichannel scenarios across the franchisees, data segregation among the franchisees, etc. This feature aims to deliver some core platform and app level capabilities that will enable partners and customers to leverage the same to build out an end-to-end franchisee solution as required by their customers and businesses.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f5aeb-119">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f5aeb-119">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f5aeb-120">この機能は、各フランチャイジー エンティティをソリューション内の個別の法人としてモデル化し、各法人の下に関連する小売店舗を構成することで、フランチャイズ ソリューションに必要な複数のシナリオを可能にします。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-120">This feature will enable multiple scenarios that are required by a franchising solution by modeling each franchisee entity as an individual legal entity in the solution with each legal entity having relevant retail stores configured under them.</span></span> <span data-ttu-id="f5aeb-121">この機能では、以下のシナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-121">The following scenarios will be supported by this feature.</span></span>

- <span data-ttu-id="f5aeb-122">すべてのアイテム属性 (フィールド) をグローバルに一元管理する機能を備えた、フランチャイジー組織が利用できるアイテムのグループをリストおよびリスト解除する機能。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-122">Ability to list and de-list group of items that will be available for a Franchisee organization with the capability for global and centralized management of all item attributes (fields).</span></span>

- <span data-ttu-id="f5aeb-123">フランチャイジーが法人に対して独自のローカル アイテムをリストする機能。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-123">Ability for franchisees to list their own local items for their legal entity.</span></span>

- <span data-ttu-id="f5aeb-124">フランチャイザーがすべてのアイテムに対して推奨される価格と割引を定義し、フランチャイジーが自己の法人に対してそれを上書きする (増減する) ことができる機能。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-124">Ability for franchisor to define recommended prices and discounts for all items which can be overridden (increased or decreased) by the franchisees for their own legal entities.</span></span>

- <span data-ttu-id="f5aeb-125">フランチャイザーがすべてのフランチャイジー法人に対して有効なロイヤルティ スキームとプログラムを集中的に定義および管理する機能。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-125">Ability for franchisor to centrally define and manage loyalty schemes and programs that work across all franchisee legal entities.</span></span>

- <span data-ttu-id="f5aeb-126">フランチャイジーが、自己の法人について仕入先および購買発注を作成および管理するための機能。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-126">Ability for franchisees to create and maintain vendors and purchase orders for their own legal entities.</span></span>

- <span data-ttu-id="f5aeb-127">法人内のユーザーが自分の法人に関連するレコードのみを表示できるようにする、システム内のすべてのグローバル エンティティのデータ削除。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-127">Data stripping of all global entities in the system so that a user in a legal entity can only see records that are relevant to their legal entities.</span></span>

- <span data-ttu-id="f5aeb-128">各法人のユーザーが自分に関係のあるデータだけを表示および管理できるようにする、印刷管理およびバッチジョブ処理に関するシステム機能の強化。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-128">Enhanced system capabilities around print management and batch jobs processing so that users in each legal entity can see and manage data that is only relevant to them.</span></span>

- <span data-ttu-id="f5aeb-129">各法人のシステム管理者がユーザー管理、ワークフロー、その他のシステム管理機能に関するデータのみを表示および管理できるようにする、これらのエンティティに関するフランチャイジー システム管理機能の強化。</span><span class="sxs-lookup"><span data-stu-id="f5aeb-129">Enhanced franchisee system admin capabilities around user management, workflows, and other sysadmin functions so that only relevant data for these entities are presented and managed by the system administrators of each legal entity.</span></span>
<!--feature detail end -->










