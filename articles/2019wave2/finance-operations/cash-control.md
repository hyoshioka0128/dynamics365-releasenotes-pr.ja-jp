---
title: 現金管理
description: 現金管理では、利用可能な現金残高がない場合、またはトランザクションによって残高が定義した限度額を下回った場合に追加のトランザクションが転記されないようにする、その限度額を定義できます。
author: relnotes
ms.reviewer: roschlom
ms.date: 09/09/2019
ms.assetid: 2e7ce836-03d1-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: ab95a99cf8d4ecbff37299261523069a450a4d9f
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143888"
---
# <a name="cash-control"></a><span data-ttu-id="71bbf-103">現金管理</span><span class="sxs-lookup"><span data-stu-id="71bbf-103">Cash control</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="71bbf-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="71bbf-104">Enabled for</span></span>    |  <span data-ttu-id="71bbf-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="71bbf-105">Public preview</span></span> | <span data-ttu-id="71bbf-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="71bbf-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="71bbf-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="71bbf-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="71bbf-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="71bbf-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="71bbf-109">2019 年 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="71bbf-109">Aug 5, 2019</span></span>| <span data-ttu-id="71bbf-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="71bbf-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="71bbf-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="71bbf-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="71bbf-112">この機能により、現金支出をさらに制御できるようになるほか、ビジネス ニーズに合理的に対応するための柔軟性が提供されます。</span><span class="sxs-lookup"><span data-stu-id="71bbf-112">This feature provides additional control over cash disbursements while also giving you reasonable flexibility to address business needs.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="71bbf-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="71bbf-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="71bbf-114">買掛金勘定仕入先請求書および一般会計の詳細な元帳エントリは、作成、編集、および転記時に検証されます。</span><span class="sxs-lookup"><span data-stu-id="71bbf-114">Accounts payable vendor invoices and General ledger advanced ledger entries are validated when they are created, edited, and posted.</span></span> <span data-ttu-id="71bbf-115">トランザクションの転記が原因で、関連する現金勘定の残高がその勘定に定義されている限度額を下回ると、エラー メッセージが表示され、続行するにはユーザーが勘定を変更する必要があります。</span><span class="sxs-lookup"><span data-stu-id="71bbf-115">If the transaction’s posting will cause the related cash account’s balance to be reduced below the limit defined for the account, an error message will alert you and you’ll need to change the account to continue.</span></span>

<span data-ttu-id="71bbf-116">特定のユーザーが現金管理を上書きできるようにすることもできます。</span><span class="sxs-lookup"><span data-stu-id="71bbf-116">You can also allow specific users to override cash control.</span></span> <span data-ttu-id="71bbf-117">許可されたユーザーが、勘定の現金残高が限度額を下回るという警告を受けた場合、そのユーザーはトランザクションの転記を続行できます。</span><span class="sxs-lookup"><span data-stu-id="71bbf-117">If an authorized user receives a warning that the cash balance for the account will be reduced below the limit, they can continue posting the transaction.</span></span> <span data-ttu-id="71bbf-118">たとえば、経費をカバーするための資金を受け取る前にその経費を転記する必要がある場合、または承認された送金が行われる必要があるがまだ入力も転記もされていない場合、ユーザーは現金管理限度額を上書きできます。</span><span class="sxs-lookup"><span data-stu-id="71bbf-118">For example, you might override the cash control limit when the expenditure must be posted in advance of receiving the funds to cover it, or when it requires a transfer that’s been approved but that hasn’t been entered or posted yet.</span></span>

<span data-ttu-id="71bbf-119">現金管理限度額は、現金管理残高 (現金勘定残高からすべての転記済み未払い AP 請求書を差し引いたもの) と比較されます。</span><span class="sxs-lookup"><span data-stu-id="71bbf-119">The cash control limit is compared to the cash control balance (the cash account balance minus all posted, unpaid AP invoices).</span></span> <span data-ttu-id="71bbf-120">現金管理残高が現金管理限度額 (しきい値) を下回ると、限度額を超過します。</span><span class="sxs-lookup"><span data-stu-id="71bbf-120">The limit is surpassed when the cash control balance is less than the cash control limit (threshold).</span></span>

<!--feature detail end -->












## <a name="see-also"></a><span data-ttu-id="71bbf-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="71bbf-121">See also</span></span>

<span data-ttu-id="71bbf-122">[現金管理限度を使用する](https://docs.microsoft.com/dynamics365/unified-operations/financials/public-sector/cash-control) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="71bbf-122">[Use cash control limits](https://docs.microsoft.com/dynamics365/unified-operations/financials/public-sector/cash-control) (docs)</span></span>
