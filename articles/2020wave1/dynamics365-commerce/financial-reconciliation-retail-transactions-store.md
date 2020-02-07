---
title: 店舗での小売トランザクションの財務調整
description: 店舗での小売トランザクションの財務調整
author: anpurush
ms.reviewer: josaw
ms.date: 12/16/2019
ms.assetid: 648f8c75-e91d-ea11-a811-000d3a8f004f
ms.topic: article
ms.service: business-applications
ms.author: anpurush
dynamics365pdf: true
ms.openlocfilehash: ceb8c0c3bf608d741c1a28a6af0a9aaf00575455
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986642"
---
# <a name="financial-reconciliation-of-retail-transactions-in-the-store"></a><span data-ttu-id="95240-103">店舗での小売トランザクションの財務調整</span><span class="sxs-lookup"><span data-stu-id="95240-103">Financial reconciliation of retail transactions in the store</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="95240-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="95240-104">Enabled for</span></span>    |  <span data-ttu-id="95240-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="95240-105">Public preview</span></span> | <span data-ttu-id="95240-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="95240-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="95240-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="95240-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="95240-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="95240-108">Feb 2020</span></span>| <span data-ttu-id="95240-109">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="95240-109">May 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="95240-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="95240-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="95240-111">この機能は[トリクル フィード命令の作成](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-retail/enhancements-retail-statement-posting#trickle-feed-order-creation)プロセスでのみ使用可能で、小売業者が財務諸表を販売時点管理 (MPOS) または クラウド販売時点管理 (CPOS) クライアントで作成するか、Retail Headquarters で作成するかを決定するパラメーターによって駆動されます。</span><span class="sxs-lookup"><span data-stu-id="95240-111">This feature will only work with the [trickle feed order creation](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-retail/enhancements-retail-statement-posting#trickle-feed-order-creation) process and will be driven by a parameter for retailers to decide if they want to create financial statements in the Modern point of sale (MPOS) or Cloud point of sale (CPOS) client or in the Retail headquarters.</span></span> <span data-ttu-id="95240-112">この機能を使用すると、店舗マネージャーは次のことを実行できます。</span><span class="sxs-lookup"><span data-stu-id="95240-112">This feature will enable store managers to:</span></span>

- <span data-ttu-id="95240-113">シフトの財務小売明細書を MPOS/CPOS で作成する。</span><span class="sxs-lookup"><span data-stu-id="95240-113">Create financial retail statements for their shift in MPOS/CPOS.</span></span>

- <span data-ttu-id="95240-114">現在利用可能な現金管理トランザクション タイプを使用して、必要に応じて現金エントリの調整を行う。</span><span class="sxs-lookup"><span data-stu-id="95240-114">Make adjustment entries for cash, as needed, using the currently available cash management transaction types.</span></span>

- <span data-ttu-id="95240-115">MPOS/CPOS で財務小売明細書を転記する。</span><span class="sxs-lookup"><span data-stu-id="95240-115">Post financial retail statements in MPOS/CPOS.</span></span>

- <span data-ttu-id="95240-116">MPOS/CPOS に転記された財務諸表を使用して、同じものを Retail Headquarters に転記する。</span><span class="sxs-lookup"><span data-stu-id="95240-116">Use financial statements posted in MPOS/CPOS and post the same in Retail headquarters.</span></span>

<span data-ttu-id="95240-117">このプロセスにより、Retail Headquarters で財務諸表の作成と転記を行う必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="95240-117">This process will eliminate the need to create and post financial statements in Retail headquarters.</span></span>
<!--feature detail end -->









