---
title: 保証の設定と販売
description: 延長保証は、小売業者が提供する可能性のあるサービスです。 Microsoft では、製品に保証をマッピングし、さまざまな小売チャネルで販売することができるサービス品目としての保証の概念を導入しています。
author: relnotes
ms.reviewer: josaw
ms.date: 05/19/2020
ms.assetid: a9ed0835-6bb5-e911-a963-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: boycez
dynamics365pdf: true
ms.openlocfilehash: 86dccc23a262a777a42eeab196d0bd6c88549984
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3415602"
---
# <a name="warranty-setup-and-sell"></a><span data-ttu-id="2bf78-104">保証の設定と販売</span><span class="sxs-lookup"><span data-stu-id="2bf78-104">Warranty setup and sell</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="2bf78-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="2bf78-105">Enabled for</span></span>    |  <span data-ttu-id="2bf78-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2bf78-106">Public preview</span></span> | <span data-ttu-id="2bf78-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="2bf78-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="2bf78-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="2bf78-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="2bf78-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2bf78-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2bf78-110">2020 年 5 月 18 日</span><span class="sxs-lookup"><span data-stu-id="2bf78-110">May 18, 2020</span></span>| <span data-ttu-id="2bf78-111">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="2bf78-111">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="2bf78-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2bf78-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="2bf78-113">顧客は、製品を購入する際に、特にプレミアム価格で販売されるコンピューターやスマートフォンなどのコンシューマー向け製品の場合、サポートやサービスを延長することを選択します。</span><span class="sxs-lookup"><span data-stu-id="2bf78-113">Customers are opting for extended support and services when they buy products, especially for consumer products such as computers and phones that sell at a premium price point.</span></span> <span data-ttu-id="2bf78-114">延長保証は、最初の購入時または購入後の限られた期間に小売チャネルで販売される場合があります。</span><span class="sxs-lookup"><span data-stu-id="2bf78-114">Extended warranties can be sold in the retail channel during the initial purchase or for a limited time afterward.</span></span> <span data-ttu-id="2bf78-115">小売業者にとって、延長保証の提供は顧客ロイヤルティの構築に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="2bf78-115">For a retailer, providing an extended warranty can help build customer loyalty.</span></span> <span data-ttu-id="2bf78-116">延長保証の購入により、顧客は問題が発生した場合にどこでサービスとサポートを受けられるかがわかり、問題が適切に処理されるという安心感を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="2bf78-116">With the extended warranty purchase, customers know where to go for service and support in case of issues and they can gain the confidence that their issues will be handled well.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="2bf78-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2bf78-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="2bf78-118">**保証品目の設定**: Microsoft では、製品と保証品目間の関連付け、保証の価格、保証期間など、保証品目の種類を設定し、品目の属性を設定する機能を提供しています。</span><span class="sxs-lookup"><span data-stu-id="2bf78-118">**Warranty item setup**: We are providing the functionality to set up a warranty item type and set attributes for the item including the association between a product and warranty item, price of the warranty, warranty duration, and more.</span></span> <span data-ttu-id="2bf78-119">保証品目が設定されて組織単位にリリースされると、小売業者は、販売時点管理 (POS) を通じて保証を販売できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2bf78-119">Once the warranty item is set up and released to the organizational unit, a retailer will then be able to sell warranties through point of sale (POS).</span></span>

<span data-ttu-id="2bf78-120">**保証品目の販売**: 延長保証は、最初の購入時または最初の購入後の限られた期間に小売チャネルで販売されます。</span><span class="sxs-lookup"><span data-stu-id="2bf78-120">**Warranty item sell**: Extended warranties are sold in a retail channel during the initial purchase or for a limited time after the initial purchase.</span></span> <span data-ttu-id="2bf78-121">POS では、関連する製品がカートに追加されると、販売担当者が延長保証の検討を促されます。</span><span class="sxs-lookup"><span data-stu-id="2bf78-121">In POS, a sales associate will be prompted to consider an extended warranty when a related product is added to the cart.</span></span> <span data-ttu-id="2bf78-122">これは、販売フローの一部として、販売担当者にアップセルまたはクロスセルのチャンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="2bf78-122">This provides an upsell or cross-sell opportunity to the sales associate as part of the sales flow.</span></span> <span data-ttu-id="2bf78-123">顧客は後で戻って、製品の延長保証を購入することもできます。</span><span class="sxs-lookup"><span data-stu-id="2bf78-123">A customer can also come back later and buy an extended warranty for the product.</span></span> <span data-ttu-id="2bf78-124">この場合、販売担当者は元の取引を検索し、関連する延長保証を顧客に販売できます。</span><span class="sxs-lookup"><span data-stu-id="2bf78-124">In this case, sales associates can look up the original transaction and sell the customer the related extended warranty.</span></span>
<!--feature detail end -->









