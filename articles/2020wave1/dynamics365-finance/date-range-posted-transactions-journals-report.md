---
title: 仕訳帳別転記済みトランザクション レポートのデータ範囲
description: 仕訳帳別転記済みトランザクション レポートで、レポートの生成時に日付範囲の指定が必須となりました。 既定では、この機能は無効になっています。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/06/2020
ms.assetid: b7cd1474-eb21-ea11-a810-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 0f2f8ad824cb8af83774e5baf80d88cb705ac0e8
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255488"
---
# <a name="date-range-for-posted-transactions-by-journals-report"></a><span data-ttu-id="173d8-104">仕訳帳別転記済みトランザクション レポートのデータ範囲</span><span class="sxs-lookup"><span data-stu-id="173d8-104">Date range for Posted transactions by journals report</span></span>


| <span data-ttu-id="173d8-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="173d8-105">Enabled for</span></span>    |  <span data-ttu-id="173d8-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="173d8-106">Public preview</span></span> | <span data-ttu-id="173d8-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="173d8-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="173d8-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="173d8-108">End users, automatically</span></span>|<span data-ttu-id="173d8-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="173d8-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="173d8-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="173d8-110">Feb 3, 2020</span></span>| <span data-ttu-id="173d8-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="173d8-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="173d8-112">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="173d8-112">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="173d8-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="173d8-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="173d8-114">仕訳帳別転記済みトランザクション レポートで、日付範囲の指定が必須となりました。これにより、レポートの生成が迅速化されます。</span><span class="sxs-lookup"><span data-stu-id="173d8-114">The Posted transactions by journals report now requires a date range, which allows it to be generated faster.</span></span> <span data-ttu-id="173d8-115">日付範囲を指定することで、仕訳帳別転記済みトランザクション レポートで処理されるデータの量が制限されます。</span><span class="sxs-lookup"><span data-stu-id="173d8-115">Specifying a date range limits the amount of data that’s processed for the Posted transactions by journals report.</span></span> <span data-ttu-id="173d8-116">制限がないと、処理されるデータの量が膨大になり、システムのパフォーマンスが大幅に低下する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="173d8-116">Without any restriction, the amount of data that’s processed can be huge, and can significantly degrade system performance.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="173d8-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="173d8-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="173d8-118">既定では、この機能は無効になっています。</span><span class="sxs-lookup"><span data-stu-id="173d8-118">This feature is enabled by default.</span></span> <span data-ttu-id="173d8-119">この変更により、ユーザー インターフェイスに 2 つのフィールドが追加されます。**開始日**フィールドと**終了日**フィールドです (仕訳帳別転記済みトランザクション レポートのレポート ダイアログに表示されます)。</span><span class="sxs-lookup"><span data-stu-id="173d8-119">This change adds two fields to the user interface, a **From date** field and a **To date** field, on the report dialog for the Posted transactions by journals report.</span></span> <span data-ttu-id="173d8-120">一般会計での仕訳帳の処理の詳細については、「[一般仕訳帳の処理](https://docs.microsoft.com/dynamics365/finance/general-ledger/general-journal-processing)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="173d8-120">For more information about processing a journal in the General ledger, see [General journal processing](https://docs.microsoft.com/dynamics365/finance/general-ledger/general-journal-processing).</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="173d8-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="173d8-121">See also</span></span>

<!--docs start-->
<span data-ttu-id="173d8-122">[一般仕訳帳の処理](https://docs.microsoft.com/dynamics365/finance/general-ledger/general-journal-processing) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="173d8-122">[General journal processing](https://docs.microsoft.com/dynamics365/finance/general-ledger/general-journal-processing) (docs)</span></span>
<!--docs end-->
