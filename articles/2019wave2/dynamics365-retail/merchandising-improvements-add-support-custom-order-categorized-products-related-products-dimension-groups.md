---
title: 販売促進の改善 – カテゴリ化製品、関連製品、分析コード グループに対するカスタム順序のサポートの追加
description: 販売促進関連のシナリオのサポートは、現在は実装パートナーからの拡張機能が必要な既存のシナリオとよく一致するように強化されます。
author: relnotes
ms.reviewer: josaw
ms.date: 08/26/2019
ms.assetid: aeb2e25b-69aa-e911-a963-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: asharchw
dynamics365pdf: true
ms.openlocfilehash: 0bdc3838f31a4823d57e25589c8fc544e76be174
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2659982"
---
# <a name="merchandising-improvements--add-support-for-custom-order-for-categorized-products-related-products-and-dimension-groups"></a><span data-ttu-id="bd178-103">販売促進の改善 – カテゴリ化製品、関連製品、分析コード グループに対するカスタム順序のサポートの追加</span><span class="sxs-lookup"><span data-stu-id="bd178-103">Merchandising improvements – add support for custom order for categorized products, related products, and dimension groups</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="bd178-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="bd178-104">Enabled for</span></span>    |  <span data-ttu-id="bd178-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="bd178-105">Public preview</span></span> | <span data-ttu-id="bd178-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="bd178-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="bd178-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="bd178-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="bd178-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="bd178-108">Oct 2019</span></span>| <span data-ttu-id="bd178-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="bd178-109">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="bd178-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="bd178-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="bd178-111">より多くの企業や大規模な組織がオンライン、コール センター、店舗のチャネルに Dynamics 365 Retail の機能を利用するようになっているので、これらの組織が必要とするいっそう複雑なビジネス プロセスをサポートするように Retail ソリューションも成長する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bd178-111">As more businesses and larger organizations are leveraging the Dynamics 365 Retail functionality for online, call center, and store channels, the Retail solution needs to grow to support the more complex business processes that these organizations require.</span></span> 

<span data-ttu-id="bd178-112">これらの複雑なビジネス シナリオの一部に対するサポートを標準製品に追加することで、組織が新しい販売チャネルを迅速に設定して稼働する能力を遅らせる可能性がある、複雑な拡張やカスタマイズの必要性をなくします。</span><span class="sxs-lookup"><span data-stu-id="bd178-112">By adding support for some of these complex business scenarios to our standard product, we eliminate the need for more complex extensions and customizations that can delay the organization’s ability to quickly configure and be live on a new selling channel.</span></span> 

<span data-ttu-id="bd178-113">シームレスなオムニチャネルの販売促進ソリューションを提供し、あらゆる小売チャネルの製品、カテゴリ、属性を小売業者が構成するための一貫したエクスペリエンスのセットを提供するため、これらの領域の一部を見直し、販売促進機能と、すべてのチャネルでのカタログ、製品、属性に関連するデータのフローの一貫性を保証する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bd178-113">In order to provide a seamless omnichannel merchandising solution and provide a consistent set of experiences to our retailers for configuration of products, categories, and attributes for any retail channel, we must re-factor some of these areas to ensure consistency of merchandising features and the flow of data related to catalog, product, and attributes in all channels.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="bd178-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="bd178-114">Feature details</span></span>
<!--feature detail start -->
### <a name="custom-display-sort-order-for-various-merchandising-entities"></a><span data-ttu-id="bd178-115">さまざまな販売促進エンティティに対するカスタム "表示並べ替え順序"</span><span class="sxs-lookup"><span data-stu-id="bd178-115">Custom "Display sort order" for various merchandising entities</span></span>

<span data-ttu-id="bd178-116">さまざまな販売促進エンティティに対するカスタム "表示並べ替え順序" 機能は、販売促進マネージャーが、本社やコール センターを含むすべてのエンド ユーザー クライアントのさまざまな販売促進エンティティに対してカスタムの並べ替え順序を構成できるようにします。</span><span class="sxs-lookup"><span data-stu-id="bd178-116">The custom "Display sort order" for various merchandising entities feature will allow the merchandising manager to configure the custom sort order for various merchandising entities across all end-user clients including headquarters and call centers.</span></span> 

<span data-ttu-id="bd178-117">以下のシナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="bd178-117">The following scenarios will be supported:</span></span> 

- <span data-ttu-id="bd178-118">**チャネルのナビゲーション階層**でカテゴリに関連付けられている**製品**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="bd178-118">Configurable sort order for **Products** associated with category in **Navigation hierarchy of a channel**.</span></span>   
- <span data-ttu-id="bd178-119">**カタログのナビゲーション階層**でカテゴリに関連付けられている**製品**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="bd178-119">Configurable sort order for **Products** associated with category in **Navigation hierarchy of a catalog**.</span></span>    
- <span data-ttu-id="bd178-120">**個々の製品**に関連付けられている**関連製品**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="bd178-120">Configurable sort order for **Related products** associated with an **Individual product**.</span></span>                     
- <span data-ttu-id="bd178-121">特定の**製品マスター**の**分析コード グループ**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="bd178-121">Configurable sort order for **Dimension groups** for a given **Product master**.</span></span>
<!--feature detail end -->









