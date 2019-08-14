---
title: 支払/入金ベースの割引
description: 支払/入金ベースの割引
author: relnotes
ms.reviewer: josaw
ms.date: 07/22/2019
ms.assetid: b7b43518-5d6c-e911-a964-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: shajain
dynamics365pdf: true
ms.openlocfilehash: d65392a548024c0b18fbf3e90058af72325dc5a5
ms.sourcegitcommit: 4101748c25acf79b22e31a01b73969500926ff91
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1793862"
---
# <a name="tender-based-discounts"></a><span data-ttu-id="adffe-103">支払/入金ベースの割引</span><span class="sxs-lookup"><span data-stu-id="adffe-103">Tender-based discounts</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="adffe-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="adffe-104">Enabled for</span></span>    |  <span data-ttu-id="adffe-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="adffe-105">Public preview</span></span> | <span data-ttu-id="adffe-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="adffe-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="adffe-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="adffe-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="adffe-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="adffe-108">October 2019</span></span>| <span data-ttu-id="adffe-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="adffe-109">January 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="adffe-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="adffe-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="adffe-111">大手小売店がプライベート ブランドのクレジット カードを発行するのは一般的なことです。</span><span class="sxs-lookup"><span data-stu-id="adffe-111">It's a common practice for large retailers to release private branded credit cards.</span></span> <span data-ttu-id="adffe-112">小売業者は銀行から優先レートを取得することで恩恵を受けます。また、GE Capital Retail Finance による調査によると、このようなクレジット カードは店舗の訪問頻度の増加をもたらし、小売業者の収益を直接改善します。</span><span class="sxs-lookup"><span data-stu-id="adffe-112">Retailers benefit from getting preferred rates from the banks, and according to a study by GE Capital Retail Finance, such credits cards result in an increase in the store visit frequency, thus directly improving the bottom line of the retailer.</span></span> <span data-ttu-id="adffe-113">その結果、小売業者はクレジット カードの使用頻度を増やすことに積極的になり、支払/入金ベースの割引は一般的に使われる動機付けです。</span><span class="sxs-lookup"><span data-stu-id="adffe-113">As a result, retailers are motivated to increase the usage frequency of their credit cards, and tender-based discounts are a commonly used motivator.</span></span> <span data-ttu-id="adffe-114">同様に、一部の小売業者は、顧客に代替手段 (たとえば、現金、小切手、ロイヤルティなど) で支払いをするように動機付けし、それによってクレジット カード処理手数料の費用を削減することを望んでいます。</span><span class="sxs-lookup"><span data-stu-id="adffe-114">Similarly, some retailers want to motivate the customers to pay by alternate means (for example, cash, check, or loyalty) and thus reduce the expense in credit card processing fees.</span></span> <span data-ttu-id="adffe-115">そのような小売業者は、これらの代わりの支払/入金タイプに対する割引を作成したいと考えています。</span><span class="sxs-lookup"><span data-stu-id="adffe-115">Such retailers want to create discounts for these alternate tender types.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="adffe-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="adffe-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="adffe-117">この取り組みにより、小売業者は選択した支払/入金タイプで割引率を設定できるようになります。</span><span class="sxs-lookup"><span data-stu-id="adffe-117">With this investment, we will allow the retailer to configure discount percentage on a selected tender type.</span></span> <span data-ttu-id="adffe-118">割引が構成された支払/入金が選択されると、顧客には割引金額が新しい残高として表示されます。</span><span class="sxs-lookup"><span data-stu-id="adffe-118">When a tender with configured discount is selected, the customer will see the discounted amount as the new balance.</span></span> <span data-ttu-id="adffe-119">顧客は一部支払または全額支払のどちらを実行するかを選択でき、それに応じて適切な割引金額を取得します。</span><span class="sxs-lookup"><span data-stu-id="adffe-119">The customer can choose to do partial payment or a full payment and would accordingly get the appropriate discount amount.</span></span> <span data-ttu-id="adffe-120">割引情報は、紙の物理的レシートに印刷したり、仮想レシートを使用してメールで送信したりできます。</span><span class="sxs-lookup"><span data-stu-id="adffe-120">The discount information can be printed on a physical paper receipt or sent via email using a virtual receipt.</span></span>

<span data-ttu-id="adffe-121">![支払/入金割引の計算](media/tender-discounts.png "支払/入金割引の計算")</span><span class="sxs-lookup"><span data-stu-id="adffe-121">![Calculating tender discount](media/tender-discounts.png "Calculating tender discount")</span></span>
<!--feature detail end -->











