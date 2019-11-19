---
title: コール センターでの外部ギフト カードのサポート
description: Adyen コネクタによりコール センターで外部ギフト カードを利用できるようになります
author: relnotes
ms.reviewer: josaw
ms.date: 08/01/2019
ms.assetid: 9863278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: 01a955a5eb71a0e6e6d97cd5d9a8bc9abe11fe46
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2659839"
---
# <a name="external-gift-card-support-in-call-center"></a><span data-ttu-id="388a9-103">コール センターでの外部ギフト カードのサポート</span><span class="sxs-lookup"><span data-stu-id="388a9-103">External gift card support in call center</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="388a9-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="388a9-104">Enabled for</span></span>    |  <span data-ttu-id="388a9-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="388a9-105">Public preview</span></span> | <span data-ttu-id="388a9-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="388a9-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="388a9-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="388a9-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="388a9-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="388a9-108">Oct 2019</span></span>| <span data-ttu-id="388a9-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="388a9-109">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="388a9-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="388a9-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="388a9-111">多くの業者では、ギフト カードを法人や金融バックエンド システムにわたって引き換えられるようにするため、サード パーティにギフト カード サービスの管理を依頼しています。</span><span class="sxs-lookup"><span data-stu-id="388a9-111">Many merchants choose to have a third party manage their gift card services in order to ensure that the cards can be redeemed across legal entities and financial back-end systems.</span></span> <span data-ttu-id="388a9-112">この新しい機能により、支払い SDK を介してコール センターで外部ギフト カードを利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="388a9-112">With this new capability, external gift cards will be supported in the call center through the payments SDK.</span></span> <span data-ttu-id="388a9-113">その SDK を介したその新しい機能も、Adyen 用の Dynamics 365 支払いコネクタによって利用され、外部ギフト カードをコール センターで設定なしで利用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="388a9-113">The new capabilities through the SDK will also be leveraged by the Dynamics 365 payment connector for Adyen to support external gift cards out of the box in the call center.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="388a9-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="388a9-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="388a9-115">この機能では、外部ギフト カードでの支払いをコール センターのチャネルで設定なしで利用できるように構成するための標準サポートが追加されます。</span><span class="sxs-lookup"><span data-stu-id="388a9-115">This feature will add out-of-the-box support for configuring external gift card payments for use in call center channels.</span></span> <span data-ttu-id="388a9-116">外部ギフト カードを利用できるようにするために必要な SDK の変更に加えて、コール センターでの外部ギフト カードのセットアップに対応するために、バック オフィスでいくつかの変更が行われます。</span><span class="sxs-lookup"><span data-stu-id="388a9-116">In addition to the required SDK changes needed to support external gift cards, several changes will be made in the back office to support setup of external gift cards in call center.</span></span> <span data-ttu-id="388a9-117">Adyen 用の Dynamics 365 支払いコネクタも更新され、設定なしで外部ギフト カードを利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="388a9-117">The Dynamics 365 payment connector for Adyen will also be updated to support external gift cards out of the box.</span></span> 
<!--feature detail end -->









