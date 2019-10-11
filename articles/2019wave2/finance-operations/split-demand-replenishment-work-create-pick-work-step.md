---
title: ピッキング作業作成ステップからの需要補充作業の分割
description: この機能により、ユーザーは補充作業トランザクションを作業作成の残りの部分から分離することができます。
author: relnotes
ms.reviewer: josaw
ms.date: 08/02/2019
ms.assetid: 7a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: faab32b2490ca47ad878babaaba8693cd362195c
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141164"
---
# <a name="split-demand-replenishment-work-from-create-pick-work-step"></a><span data-ttu-id="f065f-103">ピッキング作業作成ステップからの需要補充作業の分割</span><span class="sxs-lookup"><span data-stu-id="f065f-103">Split demand replenishment work from create pick work step</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="f065f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f065f-104">Enabled for</span></span>    |  <span data-ttu-id="f065f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f065f-105">Public preview</span></span> | <span data-ttu-id="f065f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f065f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f065f-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="f065f-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="f065f-108">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="f065f-108">Apr 2019</span></span>| <span data-ttu-id="f065f-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="f065f-109">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="f065f-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f065f-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f065f-111">この機能により、各トランザクションの将来のパフォーマンス向上が可能になります。</span><span class="sxs-lookup"><span data-stu-id="f065f-111">This feature allows for future performance enhancements of each of the transactions.</span></span> <span data-ttu-id="f065f-112">また、トランザクション サイズを小さくすることで、潜在的なロックの影響も本質的に軽減します。</span><span class="sxs-lookup"><span data-stu-id="f065f-112">It also intrinsically reduces the impact of a potential lock, by reducing the transaction size.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f065f-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f065f-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f065f-114">バージョン 7.1 のタイムフレームでは、マルチスレッドを導入することでウェーブの割り当てステップを改善しました。</span><span class="sxs-lookup"><span data-stu-id="f065f-114">In the version 7.1 timeframe, we improved the allocation step of waving by introducing multithreading.</span></span> <span data-ttu-id="f065f-115">残りのステップは、現在マルチスレッドではなく、単一の長いデータベース トランザクションで実行されます。</span><span class="sxs-lookup"><span data-stu-id="f065f-115">The remainder of the steps are not currently multithreaded and run in a single long database transaction.</span></span> <span data-ttu-id="f065f-116">ピッキング作業の作成が表す長いトランザクションの最適化に関する問題の 1 つは、需要の補充がそのトランザクション内で作成されるという事実です。</span><span class="sxs-lookup"><span data-stu-id="f065f-116">One of the issues with optimizing the long transaction that creation of pick work represents is the fact that demand replenishment is created within that transaction.</span></span> <span data-ttu-id="f065f-117">将来のパフォーマンス最適化の目的で、補充作業作成ステップを独自のトランザクションを持つ独自のスレッドに分離します。</span><span class="sxs-lookup"><span data-stu-id="f065f-117">For future performance optimization purposes, we are separating the replenishment work creation step into its own thread that has its own transaction.</span></span>
<!--feature detail end -->











