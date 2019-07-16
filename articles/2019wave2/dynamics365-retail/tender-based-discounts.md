---
title: 支払/入金ベースの割引
description: 支払/入金ベースの割引
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: b7b43518-5d6c-e911-a964-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: shajain
dynamics365pdf: true
ms.openlocfilehash: f47e43cbe90ca24e732d3b1b67d47ba663217741
ms.sourcegitcommit: 4620697dc1f4fc6903504a55406f3d22af75e361
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1693706"
---
# <a name="tender-based-discounts"></a><span data-ttu-id="d05d7-103">支払/入金ベースの割引</span><span class="sxs-lookup"><span data-stu-id="d05d7-103">Tender based discounts</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="d05d7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="d05d7-104">Enabled for</span></span>    |  <span data-ttu-id="d05d7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d05d7-105">Public preview</span></span> | <span data-ttu-id="d05d7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="d05d7-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="d05d7-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="d05d7-107">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="d05d7-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="d05d7-108">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="d05d7-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d05d7-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d05d7-110">大手小売店がプライベート ブランドのクレジット カードを発行するのは一般的なやり方です。</span><span class="sxs-lookup"><span data-stu-id="d05d7-110">It is a common practice for large retailers to release private branded credit cards.</span></span> <span data-ttu-id="d05d7-111">小売業者は銀行から優先レートを取得することで恩恵を受けます。また、GE Capital Retail Finance による調査によると、このようなクレジット カードは店舗の訪問頻度の増加をもたらし、小売業者の収益を直接改善します。</span><span class="sxs-lookup"><span data-stu-id="d05d7-111">Retailers benefit from getting preferred rates from the banks, and according to a study by GE Capital Retail Finance, such credits cards result in an increase in the store visit frequency, thus directly improving the bottom line of the retailer.</span></span> <span data-ttu-id="d05d7-112">その結果、小売業者はクレジット カードの使用頻度を増やすことに積極的になり、支払/入金ベースの割引は一般的に使われる動機付けです。</span><span class="sxs-lookup"><span data-stu-id="d05d7-112">As a result, retailers are motivated to increase the usage frequency of their credit cards and tender based discounts is a commonly used motivator.</span></span> <span data-ttu-id="d05d7-113">同様に、一部の小売業者は、顧客に代替手段 (たとえば、現金、小切手、ロイヤルティなど) で支払いをするように動機付けし、それによってクレジット カード処理手数料の費用を削減することを望んでいます。</span><span class="sxs-lookup"><span data-stu-id="d05d7-113">Similarly, some retailers want to motivate the customers to pay by alternate means (for example, cash, check, or loyalty) and thus reduce the expense in credit card processing fees.</span></span> <span data-ttu-id="d05d7-114">そのような小売業者は、これらの代わりの支払/入金タイプに対する割引を作成したいと考えています。</span><span class="sxs-lookup"><span data-stu-id="d05d7-114">Such retailers want to create discounts for these alternate tender types.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d05d7-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d05d7-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d05d7-116">この取り組みにより、小売業者は選択した支払/入金タイプで割引率を設定できるようになります。</span><span class="sxs-lookup"><span data-stu-id="d05d7-116">With this investment, we will allow the retailer to configure discount percentage on a selected tender type.</span></span> <span data-ttu-id="d05d7-117">割引が構成された支払/入金が選択されると、顧客には割引金額が新しい残高として表示されます。</span><span class="sxs-lookup"><span data-stu-id="d05d7-117">When a tender with configured discount is selected, the customer will see the discounted amount as the new balance.</span></span> <span data-ttu-id="d05d7-118">顧客は一部支払または全額支払のどちらを実行するかを選択でき、それに応じて適切な割引金額を取得します。</span><span class="sxs-lookup"><span data-stu-id="d05d7-118">The customer can choose to do partial payment or a full payment and would accordingly get the appropriate discount amount.</span></span> <span data-ttu-id="d05d7-119">割引情報は、紙の物理的レシートに印刷したり、仮想レシートを使用してメールで送信したりできます。</span><span class="sxs-lookup"><span data-stu-id="d05d7-119">The discount information can be printed on a physical paper receipt or sent via email using a virtual receipt.</span></span>
<!--feature detail end -->

<span data-ttu-id="d05d7-120">![支払/入金割引の計算](media/tender-discounts.png "支払/入金割引の計算")</span><span class="sxs-lookup"><span data-stu-id="d05d7-120">![Calculating tender discount](media/tender-discounts.png "Calculating tender discount")</span></span>
<!-- Picture 1 -->










