---
title: 元帳の会計カレンダーを変更するときに「期間残高の再計算」が必要
description: この機能では、**元帳**ページで会計カレンダーを変更した後、会計期間を再計算する必要があります。
author: relnotes
ms.reviewer: roschlom
ms.date: 01/30/2020
ms.assetid: ba202472-ce42-ea11-a812-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 831a8287bc47f3347074f8a25f7e1e2c32e4a88f
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3032589"
---
# <a name="require-recalculate-ledger-periods-when-changing-fiscal-calendar-on-ledger"></a><span data-ttu-id="a831a-103">元帳の会計カレンダーを変更するときに「期間残高の再計算」が必要</span><span class="sxs-lookup"><span data-stu-id="a831a-103">Require 'Recalculate ledger periods' when changing fiscal calendar on Ledger</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="a831a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a831a-104">Enabled for</span></span>    |  <span data-ttu-id="a831a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a831a-105">Public preview</span></span> | <span data-ttu-id="a831a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="a831a-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a831a-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a831a-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="a831a-108">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="a831a-108">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a831a-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a831a-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a831a-110">この機能では、**元帳**ページで会計カレンダーを変更した後、会計期間を再計算する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a831a-110">This feature requires that fiscal periods be recalculated after changing the fiscal calendar on the **Ledger** page.</span></span> <span data-ttu-id="a831a-111">この要件により、トランザクションが新しいカレンダーの正しい期間に割り当てられるようになります。</span><span class="sxs-lookup"><span data-stu-id="a831a-111">This requirement helps ensure that transactions are assigned to the correct periods in the new calendar.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a831a-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a831a-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a831a-113">元帳に割り当てられた会計カレンダーはいつでも変更できます。</span><span class="sxs-lookup"><span data-stu-id="a831a-113">The fiscal calendar assigned to a ledger can be changed at any time.</span></span> <span data-ttu-id="a831a-114">カレンダーを変更するときは、元帳期間の再計算プロセスも実行する必要がありますが、プロセスをすぐに実行する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="a831a-114">When you change the calendar, you must also run the Recalculate ledger periods process, although the process doesn’t have to be run immediately.</span></span> <span data-ttu-id="a831a-115">ただし、期間を後で再計算した場合、またはプロセスをまったく実行しない場合は、レポートまたは年度の決算時に問題が発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="a831a-115">However, recalculating the periods later, or not running the process at all, can result in issues when reporting or in closing the year.</span></span> <span data-ttu-id="a831a-116">この機能を有効にした場合は、**元帳**ページで会計カレンダーを変更した後、すぐに会計期間を再計算する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a831a-116">Enabling this feature requires you to recalculate fiscal periods immediately when you change the fiscal calendar on the **Ledger** page.</span></span>
<!--feature detail end -->









