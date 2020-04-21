---
title: eコマース サイトでのミニカートのサポート
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 03/17/2020
ms.assetid: 9088a04a-b83d-ea11-a812-000d3a579c33
ms.topic: article
ms.service: business-applications
ms.author: anupamar
dynamics365pdf: true
ms.openlocfilehash: 4ce42c70cf198162619863d79a939fdf5dd4fbf6
ms.sourcegitcommit: 773ea4a9be0440714ed67e25d1ba572a6a25072e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2020
ms.locfileid: "3153883"
---
# <a name="support-for-mini-cart-on-e-commerce-site"></a><span data-ttu-id="83e6a-102">eコマース サイトでのミニカートのサポート</span><span class="sxs-lookup"><span data-stu-id="83e6a-102">Support for mini-cart on e-commerce site</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="83e6a-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="83e6a-103">Enabled for</span></span>    |  <span data-ttu-id="83e6a-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="83e6a-104">Public preview</span></span> | <span data-ttu-id="83e6a-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="83e6a-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="83e6a-106">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="83e6a-106">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="83e6a-107">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="83e6a-107">Apr 2020</span></span>| <span data-ttu-id="83e6a-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="83e6a-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="83e6a-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="83e6a-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="83e6a-110">eコマース サイトでは、顧客のショッピング体験の継続性を確保し、ショッピング プロセスの中断を最小限に抑えることが求められます。</span><span class="sxs-lookup"><span data-stu-id="83e6a-110">On an e-commerce site, we want to ensure a customer's shopping journey is continuous and there are minimal disruptions to the shopping process.</span></span> <span data-ttu-id="83e6a-111">顧客が製品ページからカートに製品を追加したときに、引き続き製品ページを閲覧できるようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="83e6a-111">When a customer adds a product to the cart from the product page, we want the customer to be able to continue browsing on the product page.</span></span>  <span data-ttu-id="83e6a-112">顧客はサイトの閲覧中に、カート ページに移動せずにカートの概要を把握できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="83e6a-112">When browsing on the site, the customer should be able to get a cart summary without navigating to the cart page.</span></span> <span data-ttu-id="83e6a-113">このエクスペリエンスにより、より多くのクロスセルの機会が小売業者に提供されます。</span><span class="sxs-lookup"><span data-stu-id="83e6a-113">This experience provides more cross-selling opportunities for a retailer.</span></span> <span data-ttu-id="83e6a-114">Dynamics 365 Commerce では、通知とミニカード エクスペリエンスのサポートによってこの機能が実現します。</span><span class="sxs-lookup"><span data-stu-id="83e6a-114">In Dynamics 365 Commerce, we will enable  this functionality by supporting notifications and a mini-cart experience.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="83e6a-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="83e6a-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="83e6a-116">ミニカートは、eコマース ページのヘッダー モジュールでサポートされるモジュールです。</span><span class="sxs-lookup"><span data-stu-id="83e6a-116">The mini-cart is a module that will be supported on the header module of the e-commerce page.</span></span> <span data-ttu-id="83e6a-117">このモジュールはホバーで起動できます。</span><span class="sxs-lookup"><span data-stu-id="83e6a-117">The module can be invoked on hover.</span></span> <span data-ttu-id="83e6a-118">カートに追加された品目、注文合計の簡単な概要が表示され、顧客がチェックアウトするための手段が提供されます。さらに、Dynamics 365 Commerce のサイト ビルダーでは、ユーザーがカート ページに移動しなくてもカートに品目が追加されると通知が表示されるように小売業者が設定できる、新しいサイト設定が公開されます。</span><span class="sxs-lookup"><span data-stu-id="83e6a-118">It shows items added to the cart, a quick summary of the order total, and provides a way for the customer to check out. In addition, in Dynamics 365 Commerce, the site builder will expose new site settings that allow the retailer to show notifications when items are added to the cart, without the user navigating to the cart page.</span></span>
<!--feature detail end -->









