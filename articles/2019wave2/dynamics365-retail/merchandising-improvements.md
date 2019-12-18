---
title: 販売促進の改善 - カテゴリのカスタム表示並べ替え順序のサポート
description: 販売促進関連のシナリオのサポートは、現在は実装パートナーからの拡張機能が必要な既存のシナリオとよく一致するように強化されます。
author: relnotes
ms.reviewer: josaw
ms.date: 11/15/2019
ms.assetid: 8263278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: asharchw
dynamics365pdf: true
ms.openlocfilehash: df2c878043ba4862ae93d561b7244de9165dfe06
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2890049"
---
# <a name="merchandising-improvements--support-to-custom-sort-the-display-order-of-categories"></a><span data-ttu-id="8d446-103">販売促進の改善 - カテゴリのカスタム表示並べ替え順序のサポート</span><span class="sxs-lookup"><span data-stu-id="8d446-103">Merchandising improvements – support to custom sort the display order of categories</span></span> 


| <span data-ttu-id="8d446-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8d446-104">Enabled for</span></span>    |  <span data-ttu-id="8d446-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8d446-105">Public preview</span></span> | <span data-ttu-id="8d446-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8d446-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8d446-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="8d446-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="8d446-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8d446-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8d446-109">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="8d446-109">Aug 2, 2019</span></span>| <span data-ttu-id="8d446-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8d446-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8d446-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="8d446-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="8d446-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8d446-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8d446-113">より多くの企業や大規模な組織がオンライン、コール センター、店舗のチャネルに Dynamics 365 Retail の機能を利用するようになっているので、これらの組織が必要とするいっそう複雑なビジネス プロセスをサポートするように Retail ソリューションも成長する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d446-113">As more businesses and larger organizations are leveraging the Dynamics 365 Retail functionality for online, call center, and store channels, the Retail solution needs to grow to support the more complex business processes that these organizations require.</span></span> 

<span data-ttu-id="8d446-114">これらの複雑なビジネス シナリオの一部に対するサポートを標準製品に追加することで、組織が新しい販売チャネルを迅速に設定して稼働する能力を遅らせる可能性がある、複雑な拡張やカスタマイズの必要性をなくします。</span><span class="sxs-lookup"><span data-stu-id="8d446-114">By adding support for some of these complex business scenarios to our standard product, we eliminate the need for more complex extensions and customizations that can delay the organization’s ability to quickly configure and be live on a new selling channel.</span></span> 

<span data-ttu-id="8d446-115">シームレスなオムニチャネルの販売促進ソリューションを提供し、あらゆる小売チャネルの製品、カテゴリ、属性を小売業者が構成するための一貫したエクスペリエンスのセットを提供するため、これらの領域の一部を見直し、販売促進機能と、すべてのチャネルでのカタログ、製品、属性関連データのフローの一貫性を保証する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8d446-115">In order to provide a seamless omnichannel merchandising solution and provide a consistent set of experiences to our retailers for configuration of products, categories, and attributes for any retail channel, we must re-factor some of these areas to ensure consistency of merchandising features and the flow of catalog-, product-, and attributes-related data in all channels.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8d446-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8d446-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8d446-117">さまざまな販売促進エンティティに対するカスタム表示並べ替え順序は、販売促進マネージャーが、本社やコール センターを含むすべてのエンド ユーザー クライアントのさまざまな販売促進エンティティに対してカスタムの並べ替え順序を構成できるようにします。</span><span class="sxs-lookup"><span data-stu-id="8d446-117">Custom display sort order for various merchandising entities empowers the merchandising manager to configure the custom sort order for various merchandising entities across all end-user clients including headquarters and call centers.</span></span> 

<span data-ttu-id="8d446-118">以下のシナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="8d446-118">The following scenarios will be supported:</span></span> 

- <span data-ttu-id="8d446-119">チャネルの**小売製品階層**での**カテゴリ**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="8d446-119">Configurable sort order for **categories** in the channel **Retail product hierarchy**.</span></span>    
     
- <span data-ttu-id="8d446-120">チャネルの**チャネル ナビゲーション階層**での**カテゴリ**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="8d446-120">Configurable sort order for **categories** in the channel **Channel navigation hierarchy**.</span></span> 
                               
- <span data-ttu-id="8d446-121">**補助階層**での**カテゴリ**に対する構成可能な並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="8d446-121">Configurable sort order for **categories** in the **Supplemental hierarchies**.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="8d446-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="8d446-122">See also</span></span>

<span data-ttu-id="8d446-123">[販売促進エンティティの並べ替え順序の変更](https://docs.microsoft.com/dynamics365/unified-operations/retail/custom-order-categories-nav-retail-prod-hierarchy) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="8d446-123">[Change the sort order for merchandising entities](https://docs.microsoft.com/dynamics365/unified-operations/retail/custom-order-categories-nav-retail-prod-hierarchy) (docs)</span></span>
