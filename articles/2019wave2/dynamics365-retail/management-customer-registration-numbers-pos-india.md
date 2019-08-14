---
title: インド用 POS からの顧客登録番号の管理
description: この機能を使用すると、Retail POS から新しい顧客レコードを作成するときに、GSTIN などの顧客の登録番号を入力できます。 登録番号は、請求書作成およびレポート作成の目的にも使用されます。
author: relnotes
ms.reviewer: josaw
ms.date: 07/22/2019
ms.assetid: 9c63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: epopov
dynamics365pdf: true
ms.openlocfilehash: 0fbd53ec7c79c6be30792b9877a1eca3d08e2735
ms.sourcegitcommit: 4101748c25acf79b22e31a01b73969500926ff91
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1793389"
---
# <a name="management-of-customer-registration-numbers-from-pos-for-india"></a><span data-ttu-id="ca9cf-104">インド用 POS からの顧客登録番号の管理</span><span class="sxs-lookup"><span data-stu-id="ca9cf-104">Management of customer registration numbers from POS for India</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="ca9cf-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="ca9cf-105">Enabled for</span></span>    |  <span data-ttu-id="ca9cf-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ca9cf-106">Public preview</span></span> | <span data-ttu-id="ca9cf-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="ca9cf-107">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="ca9cf-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="ca9cf-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ca9cf-109">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="ca9cf-109">September 2019</span></span>| <span data-ttu-id="ca9cf-110">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="ca9cf-110">November 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="ca9cf-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ca9cf-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ca9cf-112">多くの場合、小売販売では特定の顧客に対して GSTIN 番号を指定することが必要です。</span><span class="sxs-lookup"><span data-stu-id="ca9cf-112">In many cases, having a GSTIN number specified for a named customer is required in retail sales.</span></span> <span data-ttu-id="ca9cf-113">Retail POS から顧客登録番号を管理する機能がない場合、唯一の回避策は、Retail Headquarters から登録番号を管理することですが、これでは追加の作業とデータ同期による大幅な遅延が発生します。</span><span class="sxs-lookup"><span data-stu-id="ca9cf-113">Without the ability to manage customer registration numbers from Retail point of sale (POS), the only workaround is to manage the registration numbers from retail headquarters, which leads to additional efforts and significant delays due to data synchronization.</span></span> <span data-ttu-id="ca9cf-114">これは、新しい顧客レコードが POS から作成されているときは特に重要です。</span><span class="sxs-lookup"><span data-stu-id="ca9cf-114">This is especially critical when a new customer record is being created from POS.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ca9cf-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ca9cf-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ca9cf-116">この機能では、ユーザーに以下の機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="ca9cf-116">This functionality provides a user with the following capabilities:</span></span>

-  <span data-ttu-id="ca9cf-117">POS から新しい顧客レコードを作成するときに、顧客登録番号を入力します。</span><span class="sxs-lookup"><span data-stu-id="ca9cf-117">Enter a customer registration number when creating a new customer record from POS.</span></span> <span data-ttu-id="ca9cf-118">データを Retail Headquarters と同期します。</span><span class="sxs-lookup"><span data-stu-id="ca9cf-118">Synchronize the data to retail headquarters.</span></span> 

-  <span data-ttu-id="ca9cf-119">POS で顧客登録番号を表示および変更します。</span><span class="sxs-lookup"><span data-stu-id="ca9cf-119">View and modify customer registration numbers in POS.</span></span> 

-  <span data-ttu-id="ca9cf-120">POS で顧客登録番号により検索を行います。</span><span class="sxs-lookup"><span data-stu-id="ca9cf-120">Search by customer registration number in POS.</span></span> 

-  <span data-ttu-id="ca9cf-121">小売販売の領収書に顧客登録番号を印刷します。</span><span class="sxs-lookup"><span data-stu-id="ca9cf-121">Print customer registration numbers in receipts for retail sales.</span></span>
<!--feature detail end -->






## <a name="geographic-areas"></a><span data-ttu-id="ca9cf-122">地域</span><span class="sxs-lookup"><span data-stu-id="ca9cf-122">Geographic areas</span></span>
<span data-ttu-id="ca9cf-123">この機能は、以下の Microsoft Azure 地域でリリースされる予定です。</span><span class="sxs-lookup"><span data-stu-id="ca9cf-123">This feature will be released into the following Microsoft Azure geographic area:</span></span>

- <span data-ttu-id="ca9cf-124">インド</span><span class="sxs-lookup"><span data-stu-id="ca9cf-124">India</span></span>

<span data-ttu-id="ca9cf-125">地域、データ センター (リージョン)、データ ストレージ、レプリケーションの詳細については、[データの場所のページ](https://www.microsoft.com/trust-center/privacy/data-location)で**すべて展開**をクリックして、この機能に対する Microsoft Cloud Service を確認してください。</span><span class="sxs-lookup"><span data-stu-id="ca9cf-125">For more information about geographic areas, data centers (regions), data storage, and replication, click **expand all** on the [Where your data is located page](https://www.microsoft.com/trust-center/privacy/data-location) and find the Microsoft cloud service for this feature.</span></span> 




