---
title: 仕訳帳別転記済みトランザクション レポートのデータ範囲
description: 仕訳帳別転記済みトランザクション レポートで、レポートの生成時に日付範囲の指定が必須となりました。 既定では、この機能は無効になっています。
author: relnotes
ms.reviewer: roschlom
ms.date: 02/19/2020
ms.assetid: b7cd1474-eb21-ea11-a810-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: d6f652f0fc976e23dc5083480af2feb88f12620c
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3080338"
---
# <a name="date-range-for-posted-transactions-by-journals-report"></a><span data-ttu-id="acb71-104">仕訳帳別転記済みトランザクション レポートのデータ範囲</span><span class="sxs-lookup"><span data-stu-id="acb71-104">Date range for Posted transactions by journals report</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="acb71-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="acb71-105">Enabled for</span></span>    |  <span data-ttu-id="acb71-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="acb71-106">Public preview</span></span> | <span data-ttu-id="acb71-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="acb71-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="acb71-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="acb71-108">End users, automatically</span></span>|<span data-ttu-id="acb71-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="acb71-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="acb71-110">2020 年 2 月 10 日</span><span class="sxs-lookup"><span data-stu-id="acb71-110">Feb 10, 2020</span></span>| <span data-ttu-id="acb71-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="acb71-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="acb71-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="acb71-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="acb71-113">仕訳帳別転記済みトランザクション レポートで、日付範囲の指定が必須となりました。これにより、レポートの生成が迅速化されます。</span><span class="sxs-lookup"><span data-stu-id="acb71-113">The Posted transactions by journals report now requires a date range, which allows it to be generated faster.</span></span> <span data-ttu-id="acb71-114">日付範囲を指定することで、仕訳帳別転記済みトランザクション レポートで処理されるデータの量が制限されます。</span><span class="sxs-lookup"><span data-stu-id="acb71-114">Specifying a date range limits the amount of data that’s processed for the Posted transactions by journals report.</span></span> <span data-ttu-id="acb71-115">制限がないと、処理されるデータの量が膨大になり、システムのパフォーマンスが大幅に低下する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="acb71-115">Without any restriction, the amount of data that’s processed can be huge, and can significantly degrade system performance.</span></span>  
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="acb71-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="acb71-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="acb71-117">既定では、この機能は無効になっています。</span><span class="sxs-lookup"><span data-stu-id="acb71-117">This feature is enabled by default.</span></span> <span data-ttu-id="acb71-118">この変更により、ユーザー インターフェイスに 2 つのフィールドが追加されます。**開始日**フィールドと**終了日**フィールドです (仕訳帳別転記済みトランザクション レポートのレポート ダイアログに表示されます)。</span><span class="sxs-lookup"><span data-stu-id="acb71-118">This change adds two fields to the user interface, a **From date** field and a **To date** field, on the report dialog for the Posted transactions by journals report.</span></span> <span data-ttu-id="acb71-119">一般会計での仕訳帳の処理の詳細については、「[一般仕訳帳の処理](https://docs.microsoft.com/dynamics365/finance/general-ledger/general-journal-processing)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="acb71-119">For more information about processing a journal in the General ledger, see [General journal processing](https://docs.microsoft.com/dynamics365/finance/general-ledger/general-journal-processing).</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="acb71-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="acb71-120">See also</span></span>

<span data-ttu-id="acb71-121">[一般仕訳帳の処理](https://docs.microsoft.com/dynamics365/finance/general-ledger/general-journal-processing) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="acb71-121">[General journal processing](https://docs.microsoft.com/dynamics365/finance/general-ledger/general-journal-processing) (docs)</span></span>
