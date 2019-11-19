---
title: 現金管理
description: 現金管理では、利用可能な現金残高がない場合、またはトランザクションによって残高が定義した限度額を下回った場合に追加のトランザクションが転記されないようにする、その限度額を定義できます。
author: relnotes
ms.reviewer: sericks
ms.date: 10/04/2019
ms.assetid: 2e7ce836-03d1-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: ffbafbcf91ea6f2971c10ea747b51944d3f36ca0
ms.sourcegitcommit: b5be4afdeec589f0490a82495e8206a2b3aee287
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2668282"
---
# <a name="cash-control"></a><span data-ttu-id="93b48-103">現金管理</span><span class="sxs-lookup"><span data-stu-id="93b48-103">Cash control</span></span>


| <span data-ttu-id="93b48-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="93b48-104">Enabled for</span></span>    |  <span data-ttu-id="93b48-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="93b48-105">Public preview</span></span> | <span data-ttu-id="93b48-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="93b48-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="93b48-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="93b48-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="93b48-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="93b48-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="93b48-109">2019 年 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="93b48-109">Aug 5, 2019</span></span>| <span data-ttu-id="93b48-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="93b48-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="93b48-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="93b48-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="93b48-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="93b48-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="93b48-113">この機能により、現金支出をさらに制御できるようになるほか、ビジネス ニーズに合理的に対応するための柔軟性が提供されます。</span><span class="sxs-lookup"><span data-stu-id="93b48-113">This feature provides additional control over cash disbursements while also giving you reasonable flexibility to address business needs.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="93b48-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="93b48-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="93b48-115">買掛金勘定仕入先請求書および一般会計の詳細な元帳エントリは、作成、編集、および転記時に検証されます。</span><span class="sxs-lookup"><span data-stu-id="93b48-115">Accounts payable vendor invoices and General ledger advanced ledger entries are validated when they are created, edited, and posted.</span></span> <span data-ttu-id="93b48-116">トランザクションの転記が原因で、関連する現金勘定の残高がその勘定に定義されている限度額を下回ると、エラー メッセージが表示され、続行するにはユーザーが勘定を変更する必要があります。</span><span class="sxs-lookup"><span data-stu-id="93b48-116">If the transaction’s posting will cause the related cash account’s balance to be reduced below the limit defined for the account, an error message will alert you and you’ll need to change the account to continue.</span></span>

<span data-ttu-id="93b48-117">特定のユーザーが現金管理を上書きできるようにすることもできます。</span><span class="sxs-lookup"><span data-stu-id="93b48-117">You can also allow specific users to override cash control.</span></span> <span data-ttu-id="93b48-118">許可されたユーザーが、勘定の現金残高が限度額を下回るという警告を受けた場合、そのユーザーはトランザクションの転記を続行できます。</span><span class="sxs-lookup"><span data-stu-id="93b48-118">If an authorized user receives a warning that the cash balance for the account will be reduced below the limit, they can continue posting the transaction.</span></span> <span data-ttu-id="93b48-119">たとえば、経費をカバーするための資金を受け取る前にその経費を転記する必要がある場合、または承認された送金が行われる必要があるがまだ入力も転記もされていない場合、ユーザーは現金管理限度額を上書きできます。</span><span class="sxs-lookup"><span data-stu-id="93b48-119">For example, you might override the cash control limit when the expenditure must be posted in advance of receiving the funds to cover it, or when it requires a transfer that’s been approved but that hasn’t been entered or posted yet.</span></span>

<span data-ttu-id="93b48-120">現金管理限度額は、現金管理残高 (現金勘定残高からすべての転記済み未払い AP 請求書を差し引いたもの) と比較されます。</span><span class="sxs-lookup"><span data-stu-id="93b48-120">The cash control limit is compared to the cash control balance (the cash account balance minus all posted, unpaid AP invoices).</span></span> <span data-ttu-id="93b48-121">現金管理残高が現金管理限度額 (しきい値) を下回ると、限度額を超過します。</span><span class="sxs-lookup"><span data-stu-id="93b48-121">The limit is surpassed when the cash control balance is less than the cash control limit (threshold).</span></span>

<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="93b48-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="93b48-122">See also</span></span>

<span data-ttu-id="93b48-123">[現金管理限度を使用する](https://docs.microsoft.com/dynamics365/unified-operations/financials/public-sector/cash-control) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="93b48-123">[Use cash control limits](https://docs.microsoft.com/dynamics365/unified-operations/financials/public-sector/cash-control) (docs)</span></span>
