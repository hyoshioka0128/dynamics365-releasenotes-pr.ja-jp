---
title: 顧客支払予測
description: 顧客支払予測は、未払い請求書に対する顧客の支払時期を予測することにより、正確なキャッシュ フロー予測を実現します。
author: relnotes
ms.reviewer: roschlom
ms.date: 03/14/2020
ms.assetid: 6daafc9c-d5ca-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 2b2dc20a8952c7dfa129fc1fee8e571c595caf25
ms.sourcegitcommit: 773ea4a9be0440714ed67e25d1ba572a6a25072e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2020
ms.locfileid: "3152150"
---
# <a name="customer-payment-predictions"></a><span data-ttu-id="a121f-103">顧客支払予測</span><span class="sxs-lookup"><span data-stu-id="a121f-103">Customer payment predictions</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="a121f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a121f-104">Enabled for</span></span>    |  <span data-ttu-id="a121f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a121f-105">Public preview</span></span> | <span data-ttu-id="a121f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="a121f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a121f-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a121f-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="a121f-108">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="a121f-108">May 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="a121f-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a121f-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a121f-110">組織では、顧客がいつ請求書を支払うかを予測するのが難しいと感じることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="a121f-110">Organizations often find it challenging to predict when customers will pay their invoices.</span></span> <span data-ttu-id="a121f-111">この分析情報の欠如は、不正確なキャッシュ フロー予測と非効率的な取立プロセスにつながる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="a121f-111">This lack of insight can lead to inaccurate cash flow forecasts and inefficient collection processes.</span></span> <span data-ttu-id="a121f-112">顧客支払予測では、請求書または販売注文がいつ支払われるかを機械学習を使用して予測します。</span><span class="sxs-lookup"><span data-stu-id="a121f-112">Customer payment predictions will use machine learning to predict when an invoice or sales order will be paid.</span></span> <span data-ttu-id="a121f-113">組織はこれらの支払予測を使用して、先を見越した取立を行い、キャッシュ フロー予測の精度を向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="a121f-113">Organizations will be able to use these payment predictions to make collections proactive and improve the accuracy of cash flow forecasting.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a121f-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a121f-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a121f-115">顧客支払予測は、次のような質問に建設的に答え、対応するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="a121f-115">Customer payment predictions helps answer and respond constructively to the following questions:</span></span> 

-   <span data-ttu-id="a121f-116">請求書または販売注文がいつ支払われるか?</span><span class="sxs-lookup"><span data-stu-id="a121f-116">When will an invoice or sales order be paid?</span></span>
-   <span data-ttu-id="a121f-117">どの顧客が期限どおりまたは遅れて支払うか?</span><span class="sxs-lookup"><span data-stu-id="a121f-117">What customers will pay on time or late?</span></span>
-   <span data-ttu-id="a121f-118">どの請求書または注文が支払われるか?</span><span class="sxs-lookup"><span data-stu-id="a121f-118">What invoices or orders will they pay?</span></span>
<!--feature detail end -->









