---
title: eコマースおよびコール センターでの外部ギフト カードのサポート
description: この新しい機能により、Adyen 用の Dynamics 365 支払いコネクタを通じて、eコマースやコール センターで Givex と SVS がサポートされるようになります。 さらに、ISV には、支払い SDK を使用して、eコマースやコール センターで他の外部ギフト カード コネクタを有効にするための完全にサポートされたパスがあります。
author: relnotes
ms.reviewer: josaw
ms.date: 05/04/2020
ms.assetid: 3d4ca51e-f1c9-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: d1afb8c149d4dc08acc8cc1621f4304b1dc73569
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3349646"
---
# <a name="external-gift-card-support-in-e-commerce-and-call-center"></a><span data-ttu-id="e902b-104">eコマースおよびコール センターでの外部ギフト カードのサポート</span><span class="sxs-lookup"><span data-stu-id="e902b-104">External gift card support in e-commerce and call center</span></span>


| <span data-ttu-id="e902b-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="e902b-105">Enabled for</span></span>    |  <span data-ttu-id="e902b-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e902b-106">Public preview</span></span> | <span data-ttu-id="e902b-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="e902b-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="e902b-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="e902b-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="e902b-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e902b-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e902b-110">2020 年 2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="e902b-110">Feb 24, 2020</span></span>| <span data-ttu-id="e902b-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e902b-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e902b-112">2020 年 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="e902b-112">May 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="e902b-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e902b-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e902b-114">この機能により、Dynamics 365 Commerce eコマース ストアフロントやコール センターで外部ギフト カードのサポートが追加されます。</span><span class="sxs-lookup"><span data-stu-id="e902b-114">This feature adds support for external gift cards in the Dynamics 365 Commerce e-commerce storefront and call center.</span></span> <span data-ttu-id="e902b-115">SVS や Givex とのすぐに使用できる統合、Adyen 用の Dynamics 365 支払いコネクタを介した外部ギフト カードの提供に加えて、この機能により、サード パーティの外部ギフト カードをすぐに使用できる eコマース ストアフロントに統合する、または eコマース SDK を介して統合する、SDK サポートが追加されます。</span><span class="sxs-lookup"><span data-stu-id="e902b-115">In addition to providing an out-of-the-box integration to SVS and Givex, external gift cards via the Dynamics 365 Payment Connector for Adyen, this feature adds SDK support to integrate third-party external gift cards into the out-of-the-box e-commerce storefront or through the e-commerce SDK.</span></span> <span data-ttu-id="e902b-116">以前は、これらの統合には、支払いとバック オフィスで多くのカスタム コードが必要でした。</span><span class="sxs-lookup"><span data-stu-id="e902b-116">Previously these integrations required a lot of custom code for payments and in the back office.</span></span> <span data-ttu-id="e902b-117">この機能は、使用するストアフロントに応じて、統合コストを削減または排除するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="e902b-117">This feature helps to reduce or eliminate integration costs, depending on which storefront is used.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e902b-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e902b-118">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e902b-119">この機能は、eコマースを介して、Givex や SVS ギフト カードとすぐに使用できる統合を提供します。</span><span class="sxs-lookup"><span data-stu-id="e902b-119">This feature provides an out-of-the-box integration with Givex and SVS gift cards through e-commerce.</span></span> <span data-ttu-id="e902b-120">すぐに使用できる統合は、Adyen 用の Dynamics 365 支払いコネクタを介して提供されます。</span><span class="sxs-lookup"><span data-stu-id="e902b-120">The out-of-the-box integration is provided via the Dynamics 365 Payment Connector for Adyen.</span></span> <span data-ttu-id="e902b-121">すぐに使用できる統合に加えて、外部ギフト カードをサポートするサード パーティの支払いコネクタの機能強化をサポートするように、支払い SDK が更新されました。</span><span class="sxs-lookup"><span data-stu-id="e902b-121">In addition to the out-of-the-box integration, the payment SDK has been updated to support enhancements to third-party payment connectors to support external gift cards.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="e902b-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="e902b-122">See also</span></span>

<!--docs start-->
<span data-ttu-id="e902b-123">[外部ギフト カードのサポート](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/gift-card) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="e902b-123">[Support for external gift cards](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/gift-card) (docs)</span></span>
<!--docs end-->
