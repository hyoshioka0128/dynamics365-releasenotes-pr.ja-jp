---
title: 請求スケジュール
description: 請求スケジュールを使用すると、販売注文に対する請求ルールを定義する際の柔軟性が高まります。
author: relnotes
ms.reviewer: roschlom
ms.date: 07/31/2019
ms.assetid: b5eabd7b-32a6-e911-a968-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 140b83acaf8123e173e5bf135276777ed6b4e448
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854143"
---
# <a name="billing-schedules"></a><span data-ttu-id="60a88-103">請求スケジュール</span><span class="sxs-lookup"><span data-stu-id="60a88-103">Billing schedules</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="60a88-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="60a88-104">Enabled for</span></span>    |  <span data-ttu-id="60a88-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="60a88-105">Public preview</span></span> | <span data-ttu-id="60a88-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="60a88-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="60a88-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="60a88-107">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="60a88-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="60a88-108">February 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="60a88-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="60a88-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="60a88-110">請求スケジュールでは、顧客販売注文に対する柔軟な請求ルールを作成できます。</span><span class="sxs-lookup"><span data-stu-id="60a88-110">Billing schedules let you create flexible billing rules against customer sales orders.</span></span> <span data-ttu-id="60a88-111">たとえば、販売注文の明細ごとに異なる請求スケジュールを定義できます。</span><span class="sxs-lookup"><span data-stu-id="60a88-111">For example, you can define a different billing schedule for each line of a sales order.</span></span> 

<span data-ttu-id="60a88-112">現在は、支払スケジュールを使用して、支払スケジュールで定義された期間に分散されている売掛金勘定に売上の全額をすぐに転記できます。</span><span class="sxs-lookup"><span data-stu-id="60a88-112">Currently, you can use payment schedules to immediately post the full amount of a sale to accounts receivable distributed over the periods defined in the payment schedule.</span></span> 

<span data-ttu-id="60a88-113">請求スケジュールでは、売上の全額を未請求売掛金勘定に転記してから、請求スケジュールに基づいて請求書を作成します。</span><span class="sxs-lookup"><span data-stu-id="60a88-113">Billing schedules post the full sale amount to unbilled accounts receivable and then create invoices based on the billing schedule.</span></span> <span data-ttu-id="60a88-114">請求書ごとに、未請求売掛金勘定から売掛金勘定に残高を移動するための簿記入力が作成されます。</span><span class="sxs-lookup"><span data-stu-id="60a88-114">Each invoice will create an accounting entry to move the balance from unbilled accounts receivable to accounts receivable.</span></span> <span data-ttu-id="60a88-115">これにより、請求書が転記されるまで将来の期間を保留中にすることができます。</span><span class="sxs-lookup"><span data-stu-id="60a88-115">This lets future periods remain on hold until the invoice is posted.</span></span>
<!--feature detail end -->











