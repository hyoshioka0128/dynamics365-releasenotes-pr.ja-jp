---
title: 販売促進の改善 – カテゴリ化製品、関連製品、分析コード グループに対するカスタム順序のサポートの追加
description: 販売促進関連のシナリオのサポートは、現在は実装パートナーからの拡張機能が必要な既存のシナリオとよく一致するように強化されます。
author: relnotes
ms.reviewer: josaw
ms.date: 11/15/2019
ms.assetid: aeb2e25b-69aa-e911-a963-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: asharchw
dynamics365pdf: true
ms.openlocfilehash: aea660dd45121d689b0aefb5777379095462644a
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2890060"
---
# <a name="merchandising-improvements--add-support-for-custom-order-for-categorized-products-related-products-and-dimension-groups"></a><span data-ttu-id="ec02f-103">販売促進の改善 – カテゴリ化製品、関連製品、分析コード グループに対するカスタム順序のサポートの追加</span><span class="sxs-lookup"><span data-stu-id="ec02f-103">Merchandising improvements – add support for custom order for categorized products, related products, and dimension groups</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="ec02f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ec02f-104">Enabled for</span></span>    |  <span data-ttu-id="ec02f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ec02f-105">Public preview</span></span> | <span data-ttu-id="ec02f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ec02f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ec02f-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="ec02f-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ec02f-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ec02f-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ec02f-109">2019 年 10 月 21 日</span><span class="sxs-lookup"><span data-stu-id="ec02f-109">Oct 21, 2019</span></span>| <span data-ttu-id="ec02f-110">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="ec02f-110">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ec02f-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ec02f-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ec02f-112">より多くの企業や大規模な組織がオンライン、コール センター、店舗のチャネルに Dynamics 365 Retail の機能を利用するようになっているので、これらの組織が必要とするいっそう複雑なビジネス プロセスをサポートするように Retail ソリューションも成長する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ec02f-112">As more businesses and larger organizations are leveraging the Dynamics 365 Retail functionality for online, call center, and store channels, the Retail solution needs to grow to support the more complex business processes that these organizations require.</span></span> 

<span data-ttu-id="ec02f-113">これらの複雑なビジネス シナリオの一部に対するサポートを標準製品に追加することで、組織が新しい販売チャネルを迅速に設定して稼働する能力を遅らせる可能性がある、複雑な拡張やカスタマイズの必要性をなくします。</span><span class="sxs-lookup"><span data-stu-id="ec02f-113">By adding support for some of these complex business scenarios to our standard product, we eliminate the need for more complex extensions and customizations that can delay the organization’s ability to quickly configure and be live on a new selling channel.</span></span> 

<span data-ttu-id="ec02f-114">シームレスなオムニチャネルの販売促進ソリューションを提供し、あらゆる小売チャネルの製品、カテゴリ、属性を小売業者が構成するための一貫したエクスペリエンスのセットを提供するため、これらの領域の一部を見直し、販売促進機能と、すべてのチャネルでのカタログ、製品、属性に関連するデータのフローの一貫性を保証する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ec02f-114">In order to provide a seamless omnichannel merchandising solution and provide a consistent set of experiences to our retailers for configuration of products, categories, and attributes for any retail channel, we must re-factor some of these areas to ensure consistency of merchandising features and the flow of data related to catalog, product, and attributes in all channels.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ec02f-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ec02f-115">Feature details</span></span>
<!--feature detail start -->
### <a name="custom-display-sort-order-for-various-merchandising-entities"></a><span data-ttu-id="ec02f-116">さまざまな販売促進エンティティに対するカスタム "表示並べ替え順序"</span><span class="sxs-lookup"><span data-stu-id="ec02f-116">Custom "Display sort order" for various merchandising entities</span></span>

<span data-ttu-id="ec02f-117">さまざまな販売促進エンティティに対するカスタム "表示並べ替え順序" 機能は、販売促進マネージャーが、本社やコール センターを含むすべてのエンド ユーザー クライアントのさまざまな販売促進エンティティに対してカスタムの並べ替え順序を構成できるようにします。</span><span class="sxs-lookup"><span data-stu-id="ec02f-117">The custom "Display sort order" for various merchandising entities feature will allow the merchandising manager to configure the custom sort order for various merchandising entities across all end-user clients including headquarters and call centers.</span></span> 

<span data-ttu-id="ec02f-118">以下のシナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="ec02f-118">The following scenarios will be supported:</span></span> 

- <span data-ttu-id="ec02f-119">**チャネルのナビゲーション階層**でカテゴリに関連付けられている**製品**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="ec02f-119">Configurable sort order for **Products** associated with category in **Navigation hierarchy of a channel**.</span></span>   
- <span data-ttu-id="ec02f-120">**カタログのナビゲーション階層**でカテゴリに関連付けられている**製品**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="ec02f-120">Configurable sort order for **Products** associated with category in **Navigation hierarchy of a catalog**.</span></span>    
- <span data-ttu-id="ec02f-121">**個々の製品**に関連付けられている**関連製品**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="ec02f-121">Configurable sort order for **Related products** associated with an **Individual product**.</span></span>                     
- <span data-ttu-id="ec02f-122">特定の**製品マスター**の**分析コード グループ**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="ec02f-122">Configurable sort order for **Dimension groups** for a given **Product master**.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="ec02f-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="ec02f-123">See also</span></span>

<span data-ttu-id="ec02f-124">[販売促進エンティティの並べ替え順序の変更](https://docs.microsoft.com/dynamics365/retail/custom-order-categories-nav-retail-prod-hierarchy) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="ec02f-124">[Change the sort order for merchandising entities](https://docs.microsoft.com/dynamics365/retail/custom-order-categories-nav-retail-prod-hierarchy) (docs)</span></span>
