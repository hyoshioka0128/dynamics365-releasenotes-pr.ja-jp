---
title: 小売チャネル間での支払管理の一貫性
description: オムニチャネルの小売では、注文の支払いを管理するときに一貫性が必要です。 これには、チャネル間での払戻の処理、支払いの変更、ポリシーの有効化が含まれます。 この機能により、eコマース、コール センター、販売時点情報の間で支払いの一貫性が保たれます。
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: ce1a4e4d-426c-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: 45626356f6ea83e60933f72d1371459ff9255ff8
ms.sourcegitcommit: 4620697dc1f4fc6903504a55406f3d22af75e361
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1694311"
---
# <a name="consistency-in-payments-management-across-retail-channels"></a><span data-ttu-id="de26b-105">小売チャネル間での支払管理の一貫性</span><span class="sxs-lookup"><span data-stu-id="de26b-105">Consistency in payments management across retail channels</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="de26b-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="de26b-106">Enabled for</span></span>    |  <span data-ttu-id="de26b-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="de26b-107">Public preview</span></span> | <span data-ttu-id="de26b-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="de26b-108">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="de26b-109">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="de26b-109">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="de26b-110">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="de26b-110">December 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="de26b-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="de26b-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="de26b-112">小売業者は、すべてのチャネルにわたって同じレベルの顧客サービスを提供しながら、バック オフィスの従業員がこれらの注文を管理する際のエクスペリエンスが一貫するようにしたいと考えています。</span><span class="sxs-lookup"><span data-stu-id="de26b-112">Retailers want to provide the same level of customer service across all channels while ensuring that back office employees have a consistent experience when managing those orders.</span></span> <span data-ttu-id="de26b-113">現在、注文が行われたチャネルに応じて、バック オフィスの従業員は、注文が作成された場所に応じてこれらの注文の支払いを管理するためにさまざまなツールを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="de26b-113">Today, depending on which channel an order was placed in, back office employees must use different tools to manage payments for those orders depending on where the order was created.</span></span> <span data-ttu-id="de26b-114">また、支払いに関して、他のチャネルよりも柔軟性が高いチャネルがあります。</span><span class="sxs-lookup"><span data-stu-id="de26b-114">In addition, some channels have more flexibility than others when it comes to payments.</span></span> <span data-ttu-id="de26b-115">この機能は、注文が発生したチャネルに関係なく、一貫性のある堅牢な注文支払い管理エクスペリエンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="de26b-115">This feature provides a consistent and robust order payment management experience regardless of the channel where the order originated.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="de26b-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="de26b-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="de26b-117">この機能により、**コール センター顧客サービス** ページを使用して販売時点管理 (POS) と eコマースの注文支払を管理できます。</span><span class="sxs-lookup"><span data-stu-id="de26b-117">This feature will enable the management of point of sale (POS) and e-commerce order payments using the **Call center customer service** page.</span></span> <span data-ttu-id="de26b-118">現在、これらの注文がコール センターに表示されている場合、支払管理機能は利用できません。</span><span class="sxs-lookup"><span data-stu-id="de26b-118">Currently, when those orders are displayed in the call center, the payments management capabilities are not available.</span></span> <span data-ttu-id="de26b-119">この機能により、コール センターのユーザーはすべての小売チャネルからの注文に対して同じ支払管理能力を持つことができます。</span><span class="sxs-lookup"><span data-stu-id="de26b-119">This feature will allow call center users to have equal payments management capabilities for orders from all retail channels.</span></span>
<!--feature detail end -->










