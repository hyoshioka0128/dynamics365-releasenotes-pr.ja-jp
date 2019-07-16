---
title: eコマースおよびコール センターでの Adyen コネクタに対する外部ギフト カードのサポート
description: eコマースおよびコール センターでの Adyen コネクタに対する外部ギフト カードのサポート
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 9863278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: 5af48ff7e80d38cc90233951fb58488ff9708d75
ms.sourcegitcommit: 4620697dc1f4fc6903504a55406f3d22af75e361
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1694290"
---
# <a name="external-gift-card-support-for-adyen-connector-in-e-commerce-and-call-center"></a><span data-ttu-id="91edc-103">eコマースおよびコール センターでの Adyen コネクタに対する外部ギフト カードのサポート</span><span class="sxs-lookup"><span data-stu-id="91edc-103">External gift card support for Adyen connector in e-commerce and call center</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="91edc-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="91edc-104">Enabled for</span></span>    |  <span data-ttu-id="91edc-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="91edc-105">Public preview</span></span> | <span data-ttu-id="91edc-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="91edc-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="91edc-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="91edc-107">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="91edc-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="91edc-108">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="91edc-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="91edc-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="91edc-110">オンライン ショッピングの出現により、実際の贈り物の代わりにギフト カードを贈ることが、eコマース自体と同じように成長しています。</span><span class="sxs-lookup"><span data-stu-id="91edc-110">With the advent of online shopping, giving gift cards in lieu of actual gifts has experienced about the same growth as e-commerce itself.</span></span> <span data-ttu-id="91edc-111">そのため、業者は、オンライン注文の一環としてギフト カードを発行し、支払いの一環としてそれらを受け入れることができなければなりません。</span><span class="sxs-lookup"><span data-stu-id="91edc-111">As such, merchants must be able to issue gift cards as part of an online order and accept them as a form of payment.</span></span> <span data-ttu-id="91edc-112">多くの業者では、カードを法人や金融バックエンド システムで交換できるようにするため、サード パーティにギフト カード サービスを管理させることも選択しています。</span><span class="sxs-lookup"><span data-stu-id="91edc-112">Many merchants also choose to have a third party manage their gift card services in order to ensure that the cards can be redeemed across legal entities and financial backend systems.</span></span> <span data-ttu-id="91edc-113">この新しい機能により、外部のギフト カードは、eコマースおよびコール センターのシナリオで Adyen 用の Dynamics 365 支払いコネクタによってサポートされるようになります。</span><span class="sxs-lookup"><span data-stu-id="91edc-113">With this new capability, external gift cards will be supported through the Dynamics 365 payment connector for Adyen in e-commerce and call center scenarios.</span></span> <span data-ttu-id="91edc-114">さらに、ISV には、支払い SDK を使用して、同じチャネルで他の外部ギフト カード コネクタを有効にするための完全にサポートされたパスがあります。</span><span class="sxs-lookup"><span data-stu-id="91edc-114">In addition, ISVs will have a fully supported path for enabling other external gift card connectors for those same channels using the payments SDK.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="91edc-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="91edc-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="91edc-116">この機能では、eコマースおよびコール センターのチャネルで使用するための SVS および Givex ギフト カードの支払いの構成に対する標準サポートが追加されます。</span><span class="sxs-lookup"><span data-stu-id="91edc-116">This feature will add out-of-the-box support for configuring SVS and Givex gift card payments for use in e-commerce and call center channels.</span></span> <span data-ttu-id="91edc-117">この機能により、小売業者は Dynamics 365 で外部ギフト カード ソリューションを利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="91edc-117">With this feature, retailers will have an external gift card solution in Dynamics 365.</span></span> <span data-ttu-id="91edc-118">この機能では、コア製品への組み込みと、支払い SDK への機能強化が行われます。</span><span class="sxs-lookup"><span data-stu-id="91edc-118">This capability is being built into the core product and brings enhancements to the payment SDK.</span></span> <span data-ttu-id="91edc-119">つまり、小売業者が標準でサポートされているギフト カード スキームを使用していない場合は、支払い SDK を使用して必要なサポートを実装できます。</span><span class="sxs-lookup"><span data-stu-id="91edc-119">This means that if a retailer doesn't use one of the out-of-the-box supported gift card schemes, the payments SDK can be used to implement the needed support.</span></span>
<!--feature detail end -->










