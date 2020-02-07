---
title: 保証の設定と販売
description: 延長保証は、小売業者が提供する可能性のあるサービスです。 Microsoft では、製品に保証をマッピングし、さまざまな小売チャネルで販売することができるサービス品目としての保証の概念を導入しています。
author: relnotes
ms.reviewer: josaw
ms.date: 01/10/2020
ms.assetid: a9ed0835-6bb5-e911-a963-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: boycez
dynamics365pdf: true
ms.openlocfilehash: 52e54d88a2904b9c56c1450b38c09c65268c40e0
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986633"
---
# <a name="warranty-setup-and-sell"></a><span data-ttu-id="3b2c5-104">保証の設定と販売</span><span class="sxs-lookup"><span data-stu-id="3b2c5-104">Warranty setup and sell</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="3b2c5-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="3b2c5-105">Enabled for</span></span>    |  <span data-ttu-id="3b2c5-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3b2c5-106">Public preview</span></span> | <span data-ttu-id="3b2c5-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="3b2c5-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3b2c5-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="3b2c5-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="3b2c5-109">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="3b2c5-109">May 2020</span></span>| <span data-ttu-id="3b2c5-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="3b2c5-110">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3b2c5-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3b2c5-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3b2c5-112">顧客は、製品を購入する際に、特にプレミアム価格で販売されるコンピューターやスマートフォンなどのコンシューマー向け製品の場合、サポートやサービスを延長することを選択します。</span><span class="sxs-lookup"><span data-stu-id="3b2c5-112">Customers are opting for extended support and services when they buy products, especially for consumer products such as computers and phones that sell at a premium price point.</span></span> <span data-ttu-id="3b2c5-113">延長保証は、最初の購入時または購入後の限られた期間に小売チャネルで販売される場合があります。</span><span class="sxs-lookup"><span data-stu-id="3b2c5-113">Extended warranties can be sold in the retail channel during the initial purchase or for a limited time afterward.</span></span> <span data-ttu-id="3b2c5-114">小売業者にとって、延長保証の提供は顧客ロイヤルティの構築に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="3b2c5-114">For a retailer, providing an extended warranty can help build customer loyalty.</span></span> <span data-ttu-id="3b2c5-115">延長保証の購入により、顧客は問題が発生した場合にどこでサービスとサポートを受けられるかがわかり、問題が適切に処理されるという安心感を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="3b2c5-115">With the extended warranty purchase, customers know where to go for service and support in case of issues and they can gain the confidence that their issues will be handled well.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3b2c5-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3b2c5-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3b2c5-117">**保証品目の設定**: Microsoft では、製品と保証品目間の関連付け、保証の価格、保証期間など、保証品目の種類を設定し、品目の属性を設定する機能を提供しています。</span><span class="sxs-lookup"><span data-stu-id="3b2c5-117">**Warranty item setup**: We are providing the functionality to set up a warranty item type and set attributes for the item including the association between a product and warranty item, price of the warranty, warranty duration, and more.</span></span> <span data-ttu-id="3b2c5-118">保証品目が設定されて組織単位にリリースされると、小売業者は、販売時点管理 (POS) を通じて保証を販売できるようになります。</span><span class="sxs-lookup"><span data-stu-id="3b2c5-118">Once the warranty item is set up and released to the organizational unit, a retailer will then be able to sell warranties through point of sale (POS).</span></span>

<span data-ttu-id="3b2c5-119">**保証品目の販売**: 延長保証は、最初の購入時または最初の購入後の限られた期間に小売チャネルで販売されます。</span><span class="sxs-lookup"><span data-stu-id="3b2c5-119">**Warranty item sell**: Extended warranties are sold in a retail channel during the initial purchase or for a limited time after the initial purchase.</span></span> <span data-ttu-id="3b2c5-120">POS では、関連する製品がカートに追加されると、販売担当者が延長保証の検討を促されます。</span><span class="sxs-lookup"><span data-stu-id="3b2c5-120">In POS, a sales associate will be prompted to consider an extended warranty when a related product is added to the cart.</span></span> <span data-ttu-id="3b2c5-121">これは、販売フローの一部として、販売担当者にアップセルまたはクロスセルのチャンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="3b2c5-121">This provides an upsell or cross-sell opportunity to the sales associate as part of the sales flow.</span></span> <span data-ttu-id="3b2c5-122">顧客は後で戻って、製品の延長保証を購入することもできます。</span><span class="sxs-lookup"><span data-stu-id="3b2c5-122">A customer can also come back later and buy an extended warranty for the product.</span></span> <span data-ttu-id="3b2c5-123">この場合、販売担当者は元の取引を検索し、関連する延長保証を顧客に販売できます。</span><span class="sxs-lookup"><span data-stu-id="3b2c5-123">In this case, sales associates can look up the original transaction and sell the customer the related extended warranty.</span></span>
<!--feature detail end -->









