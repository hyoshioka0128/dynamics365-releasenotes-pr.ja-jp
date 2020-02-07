---
title: eコマースおよびコール センターでの外部ギフト カードのサポート
description: この新しい機能により、Adyen 用の Dynamics 365 支払いコネクタを通じて、eコマースやコール センターで Givex と SVS がサポートされるようになります。 さらに、ISV には、支払い SDK を使用して、eコマースやコール センターで他の外部ギフト カード コネクタを有効にするための完全にサポートされたパスがあります。
author: relnotes
ms.reviewer: josaw
ms.date: 01/10/2020
ms.assetid: 3d4ca51e-f1c9-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: cc2b4cea311e70ce80ba176785305bac320eee61
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986806"
---
# <a name="external-gift-card-support-in-e-commerce-and-call-center"></a><span data-ttu-id="21b38-104">eコマースおよびコール センターでの外部ギフト カードのサポート</span><span class="sxs-lookup"><span data-stu-id="21b38-104">External gift card support in e-commerce and call center</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="21b38-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="21b38-105">Enabled for</span></span>    |  <span data-ttu-id="21b38-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="21b38-106">Public preview</span></span> | <span data-ttu-id="21b38-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="21b38-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="21b38-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="21b38-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="21b38-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="21b38-109">Feb 2020</span></span>| <span data-ttu-id="21b38-110">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="21b38-110">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="21b38-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="21b38-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="21b38-112">この機能により、Dynamics 365 Commerce eコマース ストアフロントやコール センターで外部ギフト カードのサポートが追加されます。</span><span class="sxs-lookup"><span data-stu-id="21b38-112">This feature adds support for external gift cards in the Dynamics 365 Commerce e-commerce storefront and call center.</span></span> <span data-ttu-id="21b38-113">SVS や Givex とのすぐに使用できる統合、Adyen 用の Dynamics 365 支払いコネクタを介した外部ギフト カードの提供に加えて、この機能により、サード パーティの外部ギフト カードをすぐに使用できる eコマース ストアフロントに統合する、または eコマース SDK を介して統合する、SDK サポートが追加されます。</span><span class="sxs-lookup"><span data-stu-id="21b38-113">In addition to providing an out-of-the-box integration to SVS and Givex, external gift cards via the Dynamics 365 Payment Connector for Adyen, this feature adds SDK support to integrate third-party external gift cards into the out-of-the-box e-commerce storefront or through the e-commerce SDK.</span></span> <span data-ttu-id="21b38-114">以前は、これらの統合には、支払いとバック オフィスで多くのカスタム コードが必要でした。</span><span class="sxs-lookup"><span data-stu-id="21b38-114">Previously these integrations required a lot of custom code for payments and in the back office.</span></span> <span data-ttu-id="21b38-115">この機能は、使用するストアフロントに応じて、統合コストを削減または排除するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="21b38-115">This feature helps to reduce or eliminate integration costs, depending on which storefront is used.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="21b38-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="21b38-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="21b38-117">この機能は、eコマースを介して、Givex や SVS ギフト カードとすぐに使用できる統合を提供します。</span><span class="sxs-lookup"><span data-stu-id="21b38-117">This feature provides an out-of-the-box integration with Givex and SVS gift cards through e-commerce.</span></span> <span data-ttu-id="21b38-118">すぐに使用できる統合は、Adyen 用の Dynamics 365 支払いコネクタを介して提供されます。</span><span class="sxs-lookup"><span data-stu-id="21b38-118">The out-of-the-box integration is provided via the Dynamics 365 Payment Connector for Adyen.</span></span> <span data-ttu-id="21b38-119">すぐに使用できる統合に加えて、外部ギフト カードをサポートするサード パーティの支払いコネクタの機能強化をサポートするように、支払い SDK が更新されました。</span><span class="sxs-lookup"><span data-stu-id="21b38-119">In addition to the out-of-the-box integration, the payment SDK has been updated to support enhancements to third-party payment connectors to support external gift cards.</span></span> 
<!--feature detail end -->









