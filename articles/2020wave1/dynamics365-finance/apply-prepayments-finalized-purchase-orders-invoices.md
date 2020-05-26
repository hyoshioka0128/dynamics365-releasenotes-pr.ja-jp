---
title: 確定した発注書の前払を請求書に適用する
description: この機能を使用すると、確定した発注書の前払金額を他の発注書の請求書に適用できます。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/15/2020
ms.assetid: 79e6c10e-707f-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: ee50dd2a24355054830c7e501f51462e48037b86
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294944"
---
# <a name="apply-prepayments-for-finalized-purchase-orders-to-invoices"></a><span data-ttu-id="4a2f9-103">確定した発注書の前払を請求書に適用する</span><span class="sxs-lookup"><span data-stu-id="4a2f9-103">Apply prepayments for finalized purchase orders to invoices</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="4a2f9-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="4a2f9-104">Enabled for</span></span>    |  <span data-ttu-id="4a2f9-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="4a2f9-105">Public preview</span></span> | <span data-ttu-id="4a2f9-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="4a2f9-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="4a2f9-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="4a2f9-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="4a2f9-108">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="4a2f9-108">Aug 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="4a2f9-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="4a2f9-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="4a2f9-110">未適用の前払金額がある場合でも発注書を確定できるようにすることで、不要な制限がなくなり、前払決済をできるだけ効率的に修正しやすくなります。</span><span class="sxs-lookup"><span data-stu-id="4a2f9-110">Allowing a purchase order to be finalized, even with an unapplied prepayment amount, removes unnecessary restrictions and makes it easier to correct prepayment settlements as efficiently as possible.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="4a2f9-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="4a2f9-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="4a2f9-112">この機能を使用すると、前払金額が完全には適用されていない発注書を確定できます。</span><span class="sxs-lookup"><span data-stu-id="4a2f9-112">This feature lets you finalize purchase orders that have a prepayment amount that hasn’t been fully applied.</span></span> <span data-ttu-id="4a2f9-113">この機能では、未適用の前払金額を同じ仕入先の他の発注書の請求書に分配できます。</span><span class="sxs-lookup"><span data-stu-id="4a2f9-113">The feature lets you distribute the unapplied prepayment amount to invoices for other purchase orders for the same vendor.</span></span> 
<!--feature detail end -->









