---
title: インド用 POS からの顧客登録番号の管理
description: この機能を使用すると、Retail POS から新しい顧客レコードを作成するときに、GSTIN などの顧客の登録番号を入力できます。 登録番号は、請求書作成およびレポート作成の目的にも使用されます。
author: relnotes
ms.reviewer: josaw
ms.date: 09/17/2019
ms.assetid: 9c63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: epopov
dynamics365pdf: true
ms.openlocfilehash: 5470ce5db838bf8d9739f9024b8ed6020fa05a9d
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143549"
---
# <a name="management-of-customer-registration-numbers-from-pos-for-india"></a><span data-ttu-id="aeb5a-104">インド用 POS からの顧客登録番号の管理</span><span class="sxs-lookup"><span data-stu-id="aeb5a-104">Management of customer registration numbers from POS for India</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="aeb5a-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="aeb5a-105">Enabled for</span></span>    |  <span data-ttu-id="aeb5a-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="aeb5a-106">Public preview</span></span> | <span data-ttu-id="aeb5a-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="aeb5a-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="aeb5a-108">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="aeb5a-108">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="aeb5a-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="aeb5a-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="aeb5a-110">2019 年 9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="aeb5a-110">Sep 6, 2019</span></span>| <span data-ttu-id="aeb5a-111">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="aeb5a-111">Nov 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="aeb5a-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="aeb5a-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="aeb5a-113">多くの場合、小売販売では特定の顧客に対して GSTIN 番号を指定することが必要です。</span><span class="sxs-lookup"><span data-stu-id="aeb5a-113">In many cases, having a GSTIN number specified for a named customer is required in retail sales.</span></span> <span data-ttu-id="aeb5a-114">Retail POS から顧客登録番号を管理する機能がない場合、唯一の回避策は、Retail Headquarters から登録番号を管理することですが、これでは追加の作業とデータ同期による大幅な遅延が発生します。</span><span class="sxs-lookup"><span data-stu-id="aeb5a-114">Without the ability to manage customer registration numbers from Retail point of sale (POS), the only workaround is to manage the registration numbers from retail headquarters, which leads to additional efforts and significant delays due to data synchronization.</span></span> <span data-ttu-id="aeb5a-115">これは、新しい顧客レコードが POS から作成されているときは特に重要です。</span><span class="sxs-lookup"><span data-stu-id="aeb5a-115">This is especially critical when a new customer record is being created from POS.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="aeb5a-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="aeb5a-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="aeb5a-117">この機能では、ユーザーに以下の機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="aeb5a-117">This functionality provides a user with the following capabilities:</span></span>

-  <span data-ttu-id="aeb5a-118">POS から新しい顧客レコードを作成するときに、顧客登録番号を入力します。</span><span class="sxs-lookup"><span data-stu-id="aeb5a-118">Enter a customer registration number when creating a new customer record from POS.</span></span> <span data-ttu-id="aeb5a-119">データを Retail Headquarters と同期します。</span><span class="sxs-lookup"><span data-stu-id="aeb5a-119">Synchronize the data to retail headquarters.</span></span> 

-  <span data-ttu-id="aeb5a-120">POS で顧客登録番号を表示および変更します。</span><span class="sxs-lookup"><span data-stu-id="aeb5a-120">View and modify customer registration numbers in POS.</span></span> 

-  <span data-ttu-id="aeb5a-121">POS で顧客登録番号により検索を行います。</span><span class="sxs-lookup"><span data-stu-id="aeb5a-121">Search by customer registration number in POS.</span></span> 

-  <span data-ttu-id="aeb5a-122">小売販売の領収書に顧客登録番号を印刷します。</span><span class="sxs-lookup"><span data-stu-id="aeb5a-122">Print customer registration numbers in receipts for retail sales.</span></span>
<!--feature detail end -->






## <a name="geographic-areas"></a><span data-ttu-id="aeb5a-123">地域</span><span class="sxs-lookup"><span data-stu-id="aeb5a-123">Geographic areas</span></span>
<span data-ttu-id="aeb5a-124">この機能は、以下の Microsoft Azure 地域でリリースされる予定です。</span><span class="sxs-lookup"><span data-stu-id="aeb5a-124">This feature will be released into the following Microsoft Azure geographic area:</span></span>

- <span data-ttu-id="aeb5a-125">インド</span><span class="sxs-lookup"><span data-stu-id="aeb5a-125">India</span></span>

<span data-ttu-id="aeb5a-126">地域、データ センター (リージョン)、データ ストレージ、レプリケーションの詳細については、[データの場所のページ](https://www.microsoft.com/trust-center/privacy/data-location)で**すべて展開**を選択して、この機能に対する Microsoft Cloud Service を確認してください。</span><span class="sxs-lookup"><span data-stu-id="aeb5a-126">For more information about geographic areas, data centers (regions), data storage, and replication, select **expand all** on the [Where your data is located page](https://www.microsoft.com/trust-center/privacy/data-location) and find the Microsoft cloud service for this feature.</span></span> 





## <a name="see-also"></a><span data-ttu-id="aeb5a-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="aeb5a-127">See also</span></span>

<span data-ttu-id="aeb5a-128">[POS からの顧客登録番号の管理](https://docs.microsoft.com/dynamics365/unified-operations/retail/localizations/apac-ind-cash-registers#manage-customer-registration-numbers-from-pos) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="aeb5a-128">[Manage customer registration numbers from POS](https://docs.microsoft.com/dynamics365/unified-operations/retail/localizations/apac-ind-cash-registers#manage-customer-registration-numbers-from-pos) (docs)</span></span>
