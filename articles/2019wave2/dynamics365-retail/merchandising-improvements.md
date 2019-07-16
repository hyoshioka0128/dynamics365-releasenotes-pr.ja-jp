---
title: 販売促進の改善
description: 販売促進関連のシナリオのサポートは、現在は実装パートナーからの拡張機能が必要な既存のシナリオとよく一致するように強化されます。
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 8263278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: asharchw
dynamics365pdf: true
ms.openlocfilehash: e4cb6bc8867ff55a9164a4b3179a0d0cd367bb34
ms.sourcegitcommit: ce44199897bc0c276cd02c99cc1d216f198734b0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1691757"
---
# <a name="merchandising-improvements"></a><span data-ttu-id="46d1a-103">販売促進の改善</span><span class="sxs-lookup"><span data-stu-id="46d1a-103">Merchandising improvements</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="46d1a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="46d1a-104">Enabled for</span></span>    |  <span data-ttu-id="46d1a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="46d1a-105">Public preview</span></span> | <span data-ttu-id="46d1a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="46d1a-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="46d1a-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="46d1a-107">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="46d1a-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="46d1a-108">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="46d1a-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="46d1a-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="46d1a-110">より多くの企業や大規模な組織がオンライン、コール センター、店舗のチャネルに Dynamics 365 for Retail の機能を利用するようになっているので、これらの組織が必要とするいっそう複雑なビジネス プロセスをサポートするように小売りソリューションも成長する必要があります。</span><span class="sxs-lookup"><span data-stu-id="46d1a-110">As more businesses and larger organizations are leveraging the Dynamics 365 for Retail functionality for online, call center, and store channels, the Retail solution needs to grow to support the more complex business processes that these organizations require.</span></span> 

<span data-ttu-id="46d1a-111">これらの複雑なビジネス シナリオの一部に対するサポートを標準製品に追加することで、組織が新しい販売チャネルを迅速に設定して稼働する能力を遅らせる可能性がある、複雑な拡張やカスタマイズの必要性をなくします。</span><span class="sxs-lookup"><span data-stu-id="46d1a-111">By adding support for some of these complex business scenarios to our standard product, we eliminate the need for more complex extensions and customizations that can delay the organization’s ability to quickly configure and be live on a new selling channel.</span></span> 

<span data-ttu-id="46d1a-112">シームレスなオムニチャネルの販売促進ソリューションを提供し、あらゆる小売チャネルの製品、カテゴリ、属性を小売業者が構成するための一貫したエクスペリエンスのセットを提供するため、これらの領域の一部を見直し、販売促進機能と、すべてのチャネルでのカタログ、製品、属性関連データのフローの一貫性を保証する必要があります。</span><span class="sxs-lookup"><span data-stu-id="46d1a-112">In order to provide a seamless omnichannel merchandising solution and provide a consistent set of experiences to our retailers for configuration of products, categories, and attributes for any retail channel, we must re-factor some of these areas to ensure consistency of merchandising features and the flow of catalog, products, and attributes related data in all channels.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="46d1a-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="46d1a-113">Feature details</span></span>
<!--feature detail start -->
### <a name="custom-display-sort-order-for-various-merchandising-entities"></a><span data-ttu-id="46d1a-114">さまざまな販売促進エンティティに対するカスタム "表示並べ替え順序"</span><span class="sxs-lookup"><span data-stu-id="46d1a-114">Custom "Display sort order" for various merchandising entities</span></span>

<span data-ttu-id="46d1a-115">さまざまな販売促進エンティティに対するカスタム "表示並べ替え順序" 機能は、販売促進マネージャーが、本社やコール センターを含むすべてのエンド ユーザー クライアントのさまざまな販売促進エンティティに対してカスタムの並べ替え順序を構成できるようにします。</span><span class="sxs-lookup"><span data-stu-id="46d1a-115">The custom "Display sort order" for various merchandising entities feature will empower the merchandising manager to be able to configure the custom sort order for various merchandising entities across all end-user clients including HQ and call center.</span></span> 

<span data-ttu-id="46d1a-116">以下のシナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="46d1a-116">The following scenarios will be supported.</span></span> 

- <span data-ttu-id="46d1a-117">チャネル **ナビゲーション階層**での**カテゴリ**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="46d1a-117">Configurable sort order for **categories** in channel **navigation hierarchy**.</span></span>                                
- <span data-ttu-id="46d1a-118">**チャネルのナビゲーション階層**でカテゴリに関連付けられている**製品**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="46d1a-118">Configurable sort order for **products** associated with category in **navigation hierarchy of a channel**.</span></span>   
- <span data-ttu-id="46d1a-119">**カタログのナビゲーション階層**でカテゴリに関連付けられている**製品**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="46d1a-119">Configurable sort order for **products** associated with category in **navigation hierarchy of a catalog**.</span></span>    
- <span data-ttu-id="46d1a-120">**個々の製品**に関連付けられている**関連製品**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="46d1a-120">Configurable sort order for **related products** associated with an **individual product**.</span></span>                     
- <span data-ttu-id="46d1a-121">特定の**製品マスター**の**分析コード グループ**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="46d1a-121">Configurable sort order for **dimension groups** for a given **product master**.</span></span>                                
- <span data-ttu-id="46d1a-122">**小売製品階層**での**カテゴリ**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="46d1a-122">Configurable sort order for **categories** in the **Retail product hierarchy**.</span></span>                                 
- <span data-ttu-id="46d1a-123">**小売製品階層**での**製品**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="46d1a-123">Configurable sort order for **products** in the **Retail product hierarchy**.</span></span>                                  
- <span data-ttu-id="46d1a-124">製品の**属性グループ**で定義されている**属性**に対する表示順序に従う。</span><span class="sxs-lookup"><span data-stu-id="46d1a-124">Observe the display order for **attributes** defined in **attribute groups** for products.</span></span>                     
- <span data-ttu-id="46d1a-125">**固定リスト**属性タイプに対する**属性値**の構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="46d1a-125">Configurable sort order of **attribute values** for **fixed list** attribute type.</span></span>                           
- <span data-ttu-id="46d1a-126">**構成**製品**分析コード値**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="46d1a-126">Configurable sort order for **configuration** product **dimension values**.</span></span>                                  
- <span data-ttu-id="46d1a-127">補助階層のようなすべての**他のカテゴリ階層目的**の**製品とカテゴリ**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="46d1a-127">Configurable sort order for **products & categories** for all **other category hierarchy purposes** like supplemental hierarchy.</span></span>
<!--feature detail end -->










