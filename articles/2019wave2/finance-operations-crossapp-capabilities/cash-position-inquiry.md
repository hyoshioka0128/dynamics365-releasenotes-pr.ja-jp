---
title: 現金持高の照会
description: ''
author: relnotes
ms.reviewer: roschlom
ms.date: 12/09/2019
ms.assetid: e49d627e-d6f9-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 84ae0e14df2e73b3c3d3dc32497312d0898cc1cb
ms.sourcegitcommit: 50510b41ebc81897993a45f689651d9eda6c4247
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/20/2019
ms.locfileid: "2912946"
---
# <a name="cash-position-inquiry"></a><span data-ttu-id="9fa8f-102">現金持高の照会</span><span class="sxs-lookup"><span data-stu-id="9fa8f-102">Cash Position Inquiry</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="9fa8f-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="9fa8f-103">Enabled for</span></span>    |  <span data-ttu-id="9fa8f-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9fa8f-104">Public preview</span></span> | <span data-ttu-id="9fa8f-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="9fa8f-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="9fa8f-106">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="9fa8f-106">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="9fa8f-107">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="9fa8f-107">Feb 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="9fa8f-108">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9fa8f-108">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9fa8f-109">この照会により、自己残高コードを含む財務分析コード セットの対応する現金持高を調べることができます。</span><span class="sxs-lookup"><span data-stu-id="9fa8f-109">This inquiry lets you determine the corresponding cash positions for financial dimension sets that contain self-balancing dimensions.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9fa8f-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9fa8f-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9fa8f-111">照会には、次の項目が表示されます。</span><span class="sxs-lookup"><span data-stu-id="9fa8f-111">The inquiry shows the following items:</span></span>

-   <span data-ttu-id="9fa8f-112">期首現金残高</span><span class="sxs-lookup"><span data-stu-id="9fa8f-112">The beginning cash balance</span></span>
-   <span data-ttu-id="9fa8f-113">現金受領の加算効果</span><span class="sxs-lookup"><span data-stu-id="9fa8f-113">The effect of the addition of cash receipts</span></span>
-   <span data-ttu-id="9fa8f-114">現金支出の減算</span><span class="sxs-lookup"><span data-stu-id="9fa8f-114">The subtraction of cash disbursements</span></span>
-   <span data-ttu-id="9fa8f-115">期末残高に到達するための資金間振替の減算</span><span class="sxs-lookup"><span data-stu-id="9fa8f-115">The subtraction of interfund transfers to arrive at an ending balance</span></span>
-   <span data-ttu-id="9fa8f-116">非債務残高に到達するための、期末残高からの一般予算引当、債務、または事前債務の減算。</span><span class="sxs-lookup"><span data-stu-id="9fa8f-116">The subtraction of general budget reservations, encumbrances, or pre-encumbrances from the ending balance to arrive at an unencumbered balance</span></span>

<span data-ttu-id="9fa8f-117">この照会により、ユーザーは現金の観点から収入と支出を追跡できるようになるため、**資金** や **残高** などの財務分析コードの残高を監視できます。</span><span class="sxs-lookup"><span data-stu-id="9fa8f-117">This inquiry gives users the capability to track revenues and expenditures from a cash point of view letting users monitor the balance of financial dimensions, such as **Fund** and **Project**.</span></span>

<!--feature detail end -->









