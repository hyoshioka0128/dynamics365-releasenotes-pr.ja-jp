---
title: インド用 POS からの顧客登録番号の管理
description: この機能を使用すると、Retail POS から新しい顧客レコードを作成するときに、GSTIN などの顧客の登録番号を入力できます。 登録番号は、請求書作成およびレポート作成の目的にも使用されます。
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 9c63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: epopov
dynamics365pdf: true
ms.openlocfilehash: 20a0df902fdb65f0edf59100d0a931c328503453
ms.sourcegitcommit: 4620697dc1f4fc6903504a55406f3d22af75e361
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1693717"
---
# <a name="management-of-customer-registration-numbers-from-pos-for-india"></a><span data-ttu-id="dd9c9-104">インド用 POS からの顧客登録番号の管理</span><span class="sxs-lookup"><span data-stu-id="dd9c9-104">Management of customer registration numbers from POS for India</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="dd9c9-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="dd9c9-105">Enabled for</span></span>    |  <span data-ttu-id="dd9c9-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="dd9c9-106">Public preview</span></span> | <span data-ttu-id="dd9c9-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="dd9c9-107">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="dd9c9-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="dd9c9-108">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="dd9c9-109">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="dd9c9-109">November 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="dd9c9-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="dd9c9-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="dd9c9-111">多くの場合、小売販売では特定の顧客に対して GSTIN 番号を指定することが必要です。</span><span class="sxs-lookup"><span data-stu-id="dd9c9-111">In many cases, having a GSTIN number specified for a named customer is required in retail sales.</span></span> <span data-ttu-id="dd9c9-112">Retail POS から顧客登録番号を管理する機能がない場合、唯一の回避策は、Retail Headquarters (HQ) から登録番号を管理することですが、これでは追加の作業とデータ同期による大幅な遅延が発生します。</span><span class="sxs-lookup"><span data-stu-id="dd9c9-112">Without the ability to manage customer registration numbers from Retail point of sale (POS), the only workaround is to manage the registration numbers from Retail Headquarters (HQ), which leads to additional efforts and significant delays due to data synchronization.</span></span> <span data-ttu-id="dd9c9-113">これは、新しい顧客レコードが POS から作成されているときは特に重要です。</span><span class="sxs-lookup"><span data-stu-id="dd9c9-113">This is especially critical when a new customer record is being created from POS.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="dd9c9-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="dd9c9-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="dd9c9-115">この機能では、ユーザーに以下の機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="dd9c9-115">This functionality provides a user with the following capabilities:</span></span>

-  <span data-ttu-id="dd9c9-116">POS から新しい顧客レコードを作成するときに、顧客登録番号を入力します。</span><span class="sxs-lookup"><span data-stu-id="dd9c9-116">Enter a customer registration number when creating a new customer record from POS.</span></span> <span data-ttu-id="dd9c9-117">データを Retail HQ と同期します。</span><span class="sxs-lookup"><span data-stu-id="dd9c9-117">Synchronize the data to Retail HQ.</span></span> 

-  <span data-ttu-id="dd9c9-118">POS で顧客登録番号を表示および変更します。</span><span class="sxs-lookup"><span data-stu-id="dd9c9-118">View and modify customer registration numbers in POS.</span></span> 

-  <span data-ttu-id="dd9c9-119">POS で顧客登録番号により検索を行います。</span><span class="sxs-lookup"><span data-stu-id="dd9c9-119">Search by customer registration number in POS.</span></span> 

-  <span data-ttu-id="dd9c9-120">小売販売の領収書に顧客登録番号を印刷します。</span><span class="sxs-lookup"><span data-stu-id="dd9c9-120">Print customer registration numbers in receipts for retail sales.</span></span>
<!--feature detail end -->










