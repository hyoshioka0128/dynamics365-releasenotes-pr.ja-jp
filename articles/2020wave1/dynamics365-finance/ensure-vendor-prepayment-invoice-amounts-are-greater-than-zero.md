---
title: 仕入先の前払請求額がゼロより大きいことを確認する
description: この機能は、仕入先前払請求額が確実にゼロより大きくなるようにします。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/16/2020
ms.assetid: 66b50591-707f-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 3c1c7b56e12f53039a1fcc5b9134b8f704609393
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294943"
---
# <a name="ensure-vendor-prepayment-invoice-amounts-are-greater-than-zero"></a><span data-ttu-id="15fb9-103">仕入先の前払請求額がゼロより大きいことを確認する</span><span class="sxs-lookup"><span data-stu-id="15fb9-103">Ensure vendor prepayment invoice amounts are greater than zero</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="15fb9-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="15fb9-104">Enabled for</span></span>    |  <span data-ttu-id="15fb9-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="15fb9-105">Public preview</span></span> | <span data-ttu-id="15fb9-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="15fb9-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="15fb9-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="15fb9-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="15fb9-108">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="15fb9-108">Aug 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="15fb9-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="15fb9-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="15fb9-110">仕入先前払請求額が確実にゼロよりも大きくなるようにすると、その後の前払処理を正常に完了できるように予防手段が提供されます。</span><span class="sxs-lookup"><span data-stu-id="15fb9-110">Ensuring that vendor prepayment invoice amounts are greater than zero provides a safeguard that subsequent prepayment processing can be completed successfully.</span></span>  
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="15fb9-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="15fb9-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="15fb9-112">この機能により、通貨金額がゼロの前払請求書を転記できなくなります。</span><span class="sxs-lookup"><span data-stu-id="15fb9-112">This feature prevents posting prepayment invoices with a zero currency amount.</span></span> <span data-ttu-id="15fb9-113">前払請求書に正の金額を要求すると、後続の処理が正常に完了することを保証できます。</span><span class="sxs-lookup"><span data-stu-id="15fb9-113">Requiring prepayment invoices to have a positive currency amount helps ensure that subsequent processing is completed successfully.</span></span> <span data-ttu-id="15fb9-114">この変更は必須であり、既定でオンになっています。</span><span class="sxs-lookup"><span data-stu-id="15fb9-114">This change is required and is turned on by default.</span></span>
<!--feature detail end -->









