---
title: 現金持高の照会
description: ''
author: relnotes
ms.reviewer: roschlom
ms.date: 03/23/2020
ms.assetid: e49d627e-d6f9-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 207802fa772c00fe22629c738554074bda59aedd
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178749"
---
# <a name="cash-position-inquiry"></a><span data-ttu-id="c4c5e-102">現金持高の照会</span><span class="sxs-lookup"><span data-stu-id="c4c5e-102">Cash Position Inquiry</span></span>


| <span data-ttu-id="c4c5e-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="c4c5e-103">Enabled for</span></span>    |  <span data-ttu-id="c4c5e-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c4c5e-104">Public preview</span></span> | <span data-ttu-id="c4c5e-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="c4c5e-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c4c5e-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c4c5e-106">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="c4c5e-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c4c5e-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c4c5e-108">2020 年 2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="c4c5e-108">Feb 28, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c4c5e-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c4c5e-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c4c5e-110">この照会により、自己残高コードを含む財務分析コード セットの対応する現金持高を調べることができます。</span><span class="sxs-lookup"><span data-stu-id="c4c5e-110">This inquiry lets you determine the corresponding cash positions for financial dimension sets that contain self-balancing dimensions.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c4c5e-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c4c5e-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c4c5e-112">照会には、次の項目が表示されます。</span><span class="sxs-lookup"><span data-stu-id="c4c5e-112">The inquiry shows the following items:</span></span>

-   <span data-ttu-id="c4c5e-113">期首現金残高</span><span class="sxs-lookup"><span data-stu-id="c4c5e-113">The beginning cash balance</span></span>
-   <span data-ttu-id="c4c5e-114">現金受領の加算効果</span><span class="sxs-lookup"><span data-stu-id="c4c5e-114">The effect of the addition of cash receipts</span></span>
-   <span data-ttu-id="c4c5e-115">現金支出の減算</span><span class="sxs-lookup"><span data-stu-id="c4c5e-115">The subtraction of cash disbursements</span></span>
-   <span data-ttu-id="c4c5e-116">期末残高に到達するための資金間振替の減算</span><span class="sxs-lookup"><span data-stu-id="c4c5e-116">The subtraction of interfund transfers to arrive at an ending balance</span></span>
-   <span data-ttu-id="c4c5e-117">非債務残高に到達するための、期末残高からの一般予算引当、債務、または事前債務の減算。</span><span class="sxs-lookup"><span data-stu-id="c4c5e-117">The subtraction of general budget reservations, encumbrances, or pre-encumbrances from the ending balance to arrive at an unencumbered balance</span></span>

<span data-ttu-id="c4c5e-118">この照会により、ユーザーは現金の観点から収入と支出を追跡できるようになるため、**資金** や **残高** などの財務分析コードの残高を監視できます。</span><span class="sxs-lookup"><span data-stu-id="c4c5e-118">This inquiry gives users the capability to track revenues and expenditures from a cash point of view letting users monitor the balance of financial dimensions, such as **Fund** and **Project**.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="c4c5e-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="c4c5e-119">See also</span></span>

<span data-ttu-id="c4c5e-120">[現金持高の照会](https://docs.microsoft.com/dynamics365/finance/public-sector/cash-position-inquiry) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c4c5e-120">[Cash position inquiry](https://docs.microsoft.com/dynamics365/finance/public-sector/cash-position-inquiry) (docs)</span></span>
