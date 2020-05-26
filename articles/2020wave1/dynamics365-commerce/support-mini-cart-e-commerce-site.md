---
title: eコマース サイトでのミニカートのサポート
description: この機能を使用すると、カートに商品が追加されたときに通知が表示されるようになります。 また、ミニ カートにより、カート ページに移動しなくてもカート内の品目の簡単な概要を確認できます。
author: relnotes
ms.reviewer: josaw
ms.date: 04/28/2020
ms.assetid: 9088a04a-b83d-ea11-a812-000d3a579c33
ms.topic: article
ms.service: business-applications
ms.author: anupamar
dynamics365pdf: true
ms.openlocfilehash: 85a3a2d760e4f99609c65a857c5ff3794fe0cb24
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350373"
---
# <a name="support-for-mini-cart-on-e-commerce-site"></a><span data-ttu-id="9aef5-104">eコマース サイトでのミニカートのサポート</span><span class="sxs-lookup"><span data-stu-id="9aef5-104">Support for mini-cart on e-commerce site</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="9aef5-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="9aef5-105">Enabled for</span></span>    |  <span data-ttu-id="9aef5-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9aef5-106">Public preview</span></span> | <span data-ttu-id="9aef5-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="9aef5-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="9aef5-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="9aef5-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="9aef5-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9aef5-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9aef5-110">2020 年 4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="9aef5-110">Apr 13, 2020</span></span>| <span data-ttu-id="9aef5-111">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="9aef5-111">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="9aef5-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9aef5-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9aef5-113">eコマース サイトでは、顧客のショッピング体験の継続性を確保し、ショッピング プロセスの中断を最小限に抑えることが求められます。</span><span class="sxs-lookup"><span data-stu-id="9aef5-113">On an e-commerce site, we want to ensure a customer's shopping journey is continuous and there are minimal disruptions to the shopping process.</span></span> <span data-ttu-id="9aef5-114">顧客が製品ページからカートに製品を追加したときに、引き続き製品ページを閲覧できるようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="9aef5-114">When a customer adds a product to the cart from the product page, we want the customer to be able to continue browsing on the product page.</span></span>  <span data-ttu-id="9aef5-115">顧客はサイトの閲覧中に、カート ページに移動せずにカートの概要を把握できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="9aef5-115">When browsing on the site, the customer should be able to get a cart summary without navigating to the cart page.</span></span> <span data-ttu-id="9aef5-116">このエクスペリエンスにより、より多くのクロスセルの機会が小売業者に提供されます。</span><span class="sxs-lookup"><span data-stu-id="9aef5-116">This experience provides more cross-selling opportunities for a retailer.</span></span> <span data-ttu-id="9aef5-117">Dynamics 365 Commerce では、通知とミニカード エクスペリエンスのサポートによってこの機能が実現します。</span><span class="sxs-lookup"><span data-stu-id="9aef5-117">In Dynamics 365 Commerce, we will enable  this functionality by supporting notifications and a mini-cart experience.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9aef5-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9aef5-118">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9aef5-119">ミニカートは、eコマース ページのヘッダー モジュールでサポートされるモジュールです。</span><span class="sxs-lookup"><span data-stu-id="9aef5-119">The mini-cart is a module that will be supported on the header module of the e-commerce page.</span></span> <span data-ttu-id="9aef5-120">このモジュールはホバーで起動できます。</span><span class="sxs-lookup"><span data-stu-id="9aef5-120">The module can be invoked on hover.</span></span> <span data-ttu-id="9aef5-121">カートに追加された品目、注文合計の簡単な概要が表示され、顧客がチェックアウトするための手段が提供されます。さらに、Dynamics 365 Commerce のサイト ビルダーでは、ユーザーがカート ページに移動しなくてもカートに品目が追加されると通知が表示されるように小売業者が設定できる、新しいサイト設定が公開されます。</span><span class="sxs-lookup"><span data-stu-id="9aef5-121">It shows items added to the cart, a quick summary of the order total, and provides a way for the customer to check out. In addition, in Dynamics 365 Commerce, the site builder will expose new site settings that allow the retailer to show notifications when items are added to the cart, without the user navigating to the cart page.</span></span>
<!--feature detail end -->









