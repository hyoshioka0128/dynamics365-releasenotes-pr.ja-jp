---
redirect_url: ../change-history#dynamics-365-for-retail
title: 保証の設定と販売
description: 延長保証は、小売業者が提供できるサービスです。 マイクロソフトでは、製品に保証をマッピングし、さまざまな小売チャネルで販売することができるサービス品目としての保証の概念を導入しています。
author: relnotes
ms.reviewer: josaw
ms.date: 08/05/2019
ms.assetid: a9ed0835-6bb5-e911-a963-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: asharchw
dynamics365pdf: true
ms.openlocfilehash: 057dc645ea4291cdaae16399357c6a1cc5fbb92d
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143464"
---
# <a name="warranty-set-up-and-sell"></a><span data-ttu-id="89b84-104">保証の設定と販売</span><span class="sxs-lookup"><span data-stu-id="89b84-104">Warranty set up and sell</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="89b84-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="89b84-105">Enabled for</span></span>    |  <span data-ttu-id="89b84-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="89b84-106">Public preview</span></span> | <span data-ttu-id="89b84-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="89b84-107">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="89b84-108">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="89b84-108">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="89b84-109">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="89b84-109">November 2019</span></span>| <span data-ttu-id="89b84-110">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="89b84-110">February 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="89b84-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="89b84-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="89b84-112">電話、コンピューター、カードなど、プレミアム価格ポイントで販売する消費者向け製品の場合には特に、顧客は製品を購入する際に延長サポートとサービスを選択します。延長保証は、最初の購入時または最初の購入後の限られた期間に小売チャネルで販売できます。</span><span class="sxs-lookup"><span data-stu-id="89b84-112">Customers are opting for extended support and services when they buy products, especially for consumer products that sell at a premium price point like phones, computers, cards, etc. Extended warranties can be sold in the retail channel during the initial purchase or for a limited time period after the initial purchase.</span></span> <span data-ttu-id="89b84-113">小売業者にとって、延長保証の提供は顧客ロイヤルティの構築に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="89b84-113">For a retailer, providing an extended warranty can help build customer loyalty.</span></span> <span data-ttu-id="89b84-114">延長保証の購入により、顧客は問題が発生した場合にサービスとサポートを受ける場所を認識し、問題が適切に処理されるという自信を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="89b84-114">With the extended warranty purchase, customers know where to go for service and support in case of issues and can gain the confidence that their issues will be handled well.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="89b84-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="89b84-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="89b84-116">**保証品目の設定**:</span><span class="sxs-lookup"><span data-stu-id="89b84-116">**Warranty item set up**:</span></span>

<span data-ttu-id="89b84-117">マイクロソフトでは、製品と保証品目間の関連付け、保証の価格、保証期間など、保証品目の種類を設定し、品目の属性を設定する機能を提供しています。</span><span class="sxs-lookup"><span data-stu-id="89b84-117">We are providing the functionality to set up a warranty item type and set attributes for the item including the association between a product and warranty item, price of the warranty, warranty duration, and more.</span></span>

<span data-ttu-id="89b84-118">保証品目が設定されて組織単位にリリースされると、小売業者は、Modern POS、オンライン、およびその他の小売チャネルを通じて保証を販売できるようになります。</span><span class="sxs-lookup"><span data-stu-id="89b84-118">Once the warranty item is set up and released to the organizational unit, a retailer will then be able to sell warranties through Modern POS, online, and across other retail channels.</span></span>

 

<span data-ttu-id="89b84-119">**保証品目の販売**:</span><span class="sxs-lookup"><span data-stu-id="89b84-119">**Warranty item sell**:</span></span>

<span data-ttu-id="89b84-120">延長保証は、最初の購入時または最初の購入後の限られた期間に小売チャネルで販売されます。</span><span class="sxs-lookup"><span data-stu-id="89b84-120">Extended warranties are sold in a retail channel during the initial purchase or for a limited timeframe after the initial purchase.</span></span> <span data-ttu-id="89b84-121">販売時点管理 (POS) では、関連する製品がカートに追加されると、販売担当者が延長保証の検討を促されます。</span><span class="sxs-lookup"><span data-stu-id="89b84-121">In point of sale (POS), a sales associate will be prompted to consider an extended warranty when a related product is added to cart.</span></span> <span data-ttu-id="89b84-122">これは、販売フローの一部として、販売担当者にアップセルまたはクロスセルのチャンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="89b84-122">This provides an upsell or cross-sell opportunity to the sales associate as part of the sales flow.</span></span> <span data-ttu-id="89b84-123">顧客は後で戻って、製品の延長保証を購入することもできます。</span><span class="sxs-lookup"><span data-stu-id="89b84-123">A customer can also come back later and buy an extended warranty for the product.</span></span> <span data-ttu-id="89b84-124">この場合、販売担当者は元の取引を検索し、関連する延長保証を顧客に販売できます。</span><span class="sxs-lookup"><span data-stu-id="89b84-124">In this case, sales associates can look up the original transaction and sell the customer the related extended warranty.</span></span>

 

<span data-ttu-id="89b84-125">**保証ポリシー**:</span><span class="sxs-lookup"><span data-stu-id="89b84-125">**Warranty policy**:</span></span>

<span data-ttu-id="89b84-126">延長保証が販売されると、保証ポリシー エンティティが作成されます。</span><span class="sxs-lookup"><span data-stu-id="89b84-126">Once the extended warranty is sold, a warranty policy entity will be created.</span></span> <span data-ttu-id="89b84-127">保証ポリシー番号を顧客と共有して、購入された延長保証のリファレンスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="89b84-127">The warranty policy number can be shared to the customer to give them a reference for the extended warranty purchased.</span></span> <span data-ttu-id="89b84-128">保証ポリシーには、販売された保証の開始日、終了日、契約条件、品目のシリアル番号などが含まれます。</span><span class="sxs-lookup"><span data-stu-id="89b84-128">The warranty policy will include the start date, end date, terms and conditions, serial number of the item, and more for the warranty sold.</span></span>
<!--feature detail end -->











