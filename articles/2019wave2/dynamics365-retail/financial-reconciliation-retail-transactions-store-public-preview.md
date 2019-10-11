---
title: 店舗での小売トランザクションの財務調整 (パブリック プレビュー)
description: 店舗での小売トランザクションの財務調整 (パブリック プレビュー)
author: anpurush
ms.reviewer: josaw
ms.date: 09/04/2019
ms.assetid: 66751c33-f6c9-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: anpurush
dynamics365pdf: true
ms.openlocfilehash: ce81bafc9866f1d7233886ccbde23c169a2e1a9c
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143889"
---
# <a name="financial-reconciliation-of-retail-transactions-in-the-store-public-preview"></a><span data-ttu-id="693b0-103">店舗での小売トランザクションの財務調整 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="693b0-103">Financial reconciliation of retail transactions in the store (Public Preview)</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="693b0-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="693b0-104">Enabled for</span></span>    |  <span data-ttu-id="693b0-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="693b0-105">Public preview</span></span> | <span data-ttu-id="693b0-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="693b0-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="693b0-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="693b0-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="693b0-108">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="693b0-108">Nov 2019</span></span>| <span data-ttu-id="693b0-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="693b0-109">Feb 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="693b0-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="693b0-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="693b0-111">小売店舗では、店舗マネージャーが店内での現金の処理と調整のすべての側面に関する説明義務と責任を負います。</span><span class="sxs-lookup"><span data-stu-id="693b0-111">In a retail store, store managers are accountable and responsible for all aspects of cash handling and reconciliation in the store.</span></span> <span data-ttu-id="693b0-112">店舗マネージャーはシフトの終わりに、そのシフトの現金エントリの調整と転記を行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="693b0-112">At the end of their shift, they are required to reconcile and post the cash entries for their shift.</span></span> <span data-ttu-id="693b0-113">この作業を POS クライアントで実行できるようにすることは、店舗マネージャーが責任を果たすために必要な重要な機能です。</span><span class="sxs-lookup"><span data-stu-id="693b0-113">Having the capability to do so in the POS client is a key capability that is needed by the store managers to perform their responsibilities.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="693b0-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="693b0-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="693b0-115">この機能は[トリクル フィード命令の作成](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-retail/enhancements-retail-statement-posting#trickle-feed-order-creation)プロセスでのみ使用でき、小売業者が財務諸表を MPOS/CPOS クライアントで作成するかまたは Retail Headquarters で作成するかを決定するパラメーターによって駆動されます。</span><span class="sxs-lookup"><span data-stu-id="693b0-115">This feature will only work with the [trickle feed order creation](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-retail/enhancements-retail-statement-posting#trickle-feed-order-creation) process and will be driven by a parameter for retailers to decide if they want to create financial statements in the MPOS/CPOS client or in the Retail headquarters.</span></span> <span data-ttu-id="693b0-116">この機能を使用すると、店舗マネージャーは次のことができます。</span><span class="sxs-lookup"><span data-stu-id="693b0-116">This feature will enable store managers to:</span></span>

1. <span data-ttu-id="693b0-117">シフトの財務小売明細書を MPOS/CPOS で作成する。</span><span class="sxs-lookup"><span data-stu-id="693b0-117">Create financial retail statements for their shift in MPOS/CPOS.</span></span>
2. <span data-ttu-id="693b0-118">現在利用可能な現金管理トランザクション タイプを使用して、必要に応じて現金エントリの調整を行う。</span><span class="sxs-lookup"><span data-stu-id="693b0-118">Make adjustment entries for cash, as needed, using the currently available cash management transaction types.</span></span>
3. <span data-ttu-id="693b0-119">MPOS/CPOS で財務小売明細書を転記する。</span><span class="sxs-lookup"><span data-stu-id="693b0-119">Post financial retail statements in MPOS/CPOS.</span></span>
4. <span data-ttu-id="693b0-120">MPOS/CPOS に転記された財務諸表を使用して、同じものを Retail Headquarters に転記する。</span><span class="sxs-lookup"><span data-stu-id="693b0-120">Use financial statements posted in MPOS/CPOS and post the same in Retail headquarters.</span></span>

<span data-ttu-id="693b0-121">このプロセスにより、Retail Headquarters で財務諸表の作成と転記を行う必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="693b0-121">This process will eliminate the need to create and post financial statements in Retail headquarters.</span></span>
<!--feature detail end -->











