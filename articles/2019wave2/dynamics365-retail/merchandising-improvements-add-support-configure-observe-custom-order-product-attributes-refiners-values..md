---
title: 販売促進の改善 - 製品属性、リファイナー、値に対するカスタム順序を構成および遵守するためのサポートの追加
description: 販売促進関連のシナリオのサポートは、現在は実装パートナーからの拡張機能が必要な既存のシナリオとよく一致するように強化されます。
author: relnotes
ms.reviewer: josaw
ms.date: 09/17/2019
ms.assetid: 302bbe16-6baa-e911-a963-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: asharchw
dynamics365pdf: true
ms.openlocfilehash: e6570d81f4d52d793884b4ecb64d7edae12f7c3d
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143562"
---
# <a name="merchandising-improvements--add-support-to-configure-and-observe-the-custom-order-for-product-attributes-refiners-and-values"></a><span data-ttu-id="8a3b4-103">販売促進の改善 - 製品属性、リファイナー、値に対するカスタム順序を構成および遵守するためのサポートの追加</span><span class="sxs-lookup"><span data-stu-id="8a3b4-103">Merchandising improvements – add support to configure and observe the custom order for product attributes, refiners, and values</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="8a3b4-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8a3b4-104">Enabled for</span></span>    |  <span data-ttu-id="8a3b4-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8a3b4-105">Public preview</span></span> | <span data-ttu-id="8a3b4-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8a3b4-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8a3b4-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="8a3b4-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="8a3b4-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="8a3b4-108">Oct 2019</span></span>| <span data-ttu-id="8a3b4-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="8a3b4-109">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="8a3b4-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8a3b4-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8a3b4-111">より多くの企業や大規模な組織がオンライン、コール センター、店舗のチャネルに Dynamics 365 Retail の機能を利用するようになっているので、これらの組織が必要とするいっそう複雑なビジネス プロセスをサポートするように Retail ソリューションも成長する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8a3b4-111">As more businesses and larger organizations leverage the Dynamics 365 Retail functionality for online, call center, and store channels, the Retail solution needs to grow to support the more complex business processes that these organizations require.</span></span> 

<span data-ttu-id="8a3b4-112">これらの複雑なビジネス シナリオの一部に対するサポートを標準製品に追加することで、組織が新しい販売チャネルを迅速に設定して稼働する能力を遅らせる可能性がある、複雑な拡張やカスタマイズの必要性をなくします。</span><span class="sxs-lookup"><span data-stu-id="8a3b4-112">By adding support for some of these complex business scenarios to our standard product, we eliminate the need for more complex extensions and customizations that can delay the organization’s ability to quickly configure and be live on a new selling channel.</span></span> 

<span data-ttu-id="8a3b4-113">シームレスなオムニチャネルの販売促進ソリューションを提供し、あらゆる小売チャネルの製品、カテゴリ、属性を小売業者が構成するための一貫したエクスペリエンスのセットを提供するため、これらの領域の一部を見直し、販売促進機能と、すべてのチャネルでのカタログ、製品、属性に関連するデータのフローの一貫性を保証する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8a3b4-113">In order to provide a seamless omnichannel merchandising solution and provide a consistent set of experiences to our retailers for configuration of products, categories, and attributes for any retail channel, we must re-factor some of these areas to ensure consistency of merchandising features and the flow of data related to catalog, product, and attributes in all channels.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8a3b4-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8a3b4-114">Feature details</span></span>
<!--feature detail start -->
## <a name="custom-display-sort-order-for-various-merchandising-entities"></a><span data-ttu-id="8a3b4-115">さまざまな販売促進エンティティに対するカスタム "表示並べ替え順序"</span><span class="sxs-lookup"><span data-stu-id="8a3b4-115">Custom "Display sort order" for various merchandising entities</span></span>

<span data-ttu-id="8a3b4-116">さまざまな販売促進エンティティに対するカスタム "表示並べ替え順序" 機能は、販売促進マネージャーが、本社やコール センターを含むすべてのエンド ユーザー クライアントのさまざまな販売促進エンティティに対してカスタムの並べ替え順序を構成できるようにします。</span><span class="sxs-lookup"><span data-stu-id="8a3b4-116">The custom "Display sort order" for various merchandising entities feature will empower the merchandising manager to be able to configure the custom sort order for various merchandising entities across all end-user clients including headquarters and call centers.</span></span> 

<span data-ttu-id="8a3b4-117">以下のシナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="8a3b4-117">The following scenarios will be supported:</span></span> 
                
- <span data-ttu-id="8a3b4-118">製品の**属性グループ**で定義されている**属性**に対する表示順序に従う。</span><span class="sxs-lookup"><span data-stu-id="8a3b4-118">Observe the display order for **Attributes** defined in **Attribute groups** for products.</span></span>     
- <span data-ttu-id="8a3b4-119">リファイナーの**属性グループ**で定義されている**属性**に対する表示順序に従う。</span><span class="sxs-lookup"><span data-stu-id="8a3b4-119">Observe the display order for **Attributes** defined in **Attribute groups** for refiners.</span></span>               
- <span data-ttu-id="8a3b4-120">**固定リスト**属性タイプに対する**属性値**の構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="8a3b4-120">Configurable sort order of **Attribute values** for **Fixed list** attribute type.</span></span>   
- <span data-ttu-id="8a3b4-121">リファイナーの**固定リスト**の**属性値**に対する表示順序に従う。</span><span class="sxs-lookup"><span data-stu-id="8a3b4-121">Observe the display order for **Attribute values** for **Fixed list** for refiner values.</span></span>                        
- <span data-ttu-id="8a3b4-122">**分析コード値、固定リスト属性タイプ、およびカテゴリー**に定義されている**リファイナー値**に対する表示順序に従う。</span><span class="sxs-lookup"><span data-stu-id="8a3b4-122">Observe the display order for **Refiner values** defined for **Dimension values, fixed list attribute types, and categories**.</span></span>
<!--feature detail end -->











