---
title: 店舗および宛先に基づく外税の顧客控除を計算する
description: この機能を使用すると、小売業者は店舗ベースの税を使用しながら、顧客の控除が適用されるかどうかも確認できます。 これは外税価格のシナリオのみを対象としたものです。この機能での税込み価格のサポートは、現在計画中です。
author: relnotes
ms.reviewer: josaw
ms.date: 03/06/2020
ms.assetid: 14fe4af2-19e2-e911-a814-000d3a4f1244
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: e3f564aadc585186ba57e4c49476efbba9045912
ms.sourcegitcommit: 8756c08fc492e62cc366fa85ee3e510af3d16f70
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/18/2020
ms.locfileid: "3139570"
---
# <a name="calculate-customer-exemptions-for-store--and-destination-based-exclusive-taxes"></a><span data-ttu-id="569de-104">店舗および宛先に基づく外税の顧客控除を計算する</span><span class="sxs-lookup"><span data-stu-id="569de-104">Calculate customer exemptions for store- and destination-based exclusive taxes</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="569de-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="569de-105">Enabled for</span></span>    |  <span data-ttu-id="569de-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="569de-106">Public preview</span></span> | <span data-ttu-id="569de-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="569de-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="569de-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="569de-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="569de-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="569de-109">Oct 2019</span></span>| <span data-ttu-id="569de-110">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="569de-110">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="569de-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="569de-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="569de-112">特定の業界では、小売業者が企業間現金売りトランザクションを行うことが一般的です。</span><span class="sxs-lookup"><span data-stu-id="569de-112">In certain industries it is common for retailers to conduct business-to-business cash-and-carry transactions.</span></span> <span data-ttu-id="569de-113">そのような場合、特定の顧客が特定の税金を免除されることがありますが、免除されないその他の税については、支払う必要があります。</span><span class="sxs-lookup"><span data-stu-id="569de-113">In those cases, certain customers might be exempt from certain taxes but should pay other taxes for which they are not exempt.</span></span> <span data-ttu-id="569de-114">この機能では、このようなシナリオにそのまま使用できる機能が用意されているので、回避策を講じる必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="569de-114">This feature adds out-of-the-box functionality for this scenario and obviates the need for workarounds.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="569de-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="569de-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="569de-116">店舗で "店舗ベース" や "宛先ベース" の税が使用されている場合、税は常に、販売される商品と、その商品を顧客が入手する店舗や場所での税に基づいて計算されます。</span><span class="sxs-lookup"><span data-stu-id="569de-116">When a store is using "Store-based" and "Destination-based" tax, the tax is always calculated based on what is being sold and the applicable taxes at the store or place where the goods will come into the customer's possession.</span></span> <span data-ttu-id="569de-117">これらの設定では、顧客が特定の税を免除されるシナリオが考慮されません。</span><span class="sxs-lookup"><span data-stu-id="569de-117">Those settings do not account for scenarios where a customer might be exempt from certain taxes.</span></span> 

<span data-ttu-id="569de-118">今回この機能が追加されたことで、**顧客控除を計算する** というパラメーターが、小売店レベルで導入されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="569de-118">With the addition of this feature, a parameter called **Calculate customer exempt** is introduced at the retail store level.</span></span> <span data-ttu-id="569de-119">このパラメーターを有効にすると、トランザクションに適用される税が、顧客の構成した消費税と照合されます。</span><span class="sxs-lookup"><span data-stu-id="569de-119">When this parameter is enabled, the applicable taxes for the transaction will be checked against the customer's configured sales taxes.</span></span> <span data-ttu-id="569de-120">現在のトランザクションに適用される税が顧客レベルで**控除**対象としてマークされている場合、それらの税はそのトランザクションには適用されません。</span><span class="sxs-lookup"><span data-stu-id="569de-120">If taxes applicable for the current transaction are found to be marked **Exempt** at the customer level, those taxes will not be applied for that transaction.</span></span>
<!--feature detail end -->









