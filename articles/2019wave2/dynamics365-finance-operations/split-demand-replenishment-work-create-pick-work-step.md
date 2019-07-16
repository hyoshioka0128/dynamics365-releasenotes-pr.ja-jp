---
title: ピッキング作業作成ステップからの需要補充作業の分割
description: この機能により、ユーザーは補充作業トランザクションを作業作成の残りの部分から分離することができます。
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 7a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: d2a456cdce5301f0677d588b76a94627d79c841a
ms.sourcegitcommit: d6ff62c145bfdd7742034a67a29bf75938823eb0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/24/2019
ms.locfileid: "1701458"
---
# <a name="split-demand-replenishment-work-from-create-pick-work-step"></a><span data-ttu-id="e95df-103">ピッキング作業作成ステップからの需要補充作業の分割</span><span class="sxs-lookup"><span data-stu-id="e95df-103">Split demand replenishment work from create pick work step</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="e95df-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="e95df-104">Enabled for</span></span>    |  <span data-ttu-id="e95df-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e95df-105">Public preview</span></span> | <span data-ttu-id="e95df-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="e95df-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="e95df-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="e95df-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="e95df-108">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="e95df-108">April 2019</span></span>| <span data-ttu-id="e95df-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="e95df-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="e95df-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e95df-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e95df-111">この機能により、各トランザクションの将来のパフォーマンス向上が可能になります。</span><span class="sxs-lookup"><span data-stu-id="e95df-111">This feature allows for future performance enhancements of each of the transactions.</span></span> <span data-ttu-id="e95df-112">また、トランザクション サイズを小さくすることで、潜在的なロックの影響も本質的に軽減します。</span><span class="sxs-lookup"><span data-stu-id="e95df-112">It also intrinsically reduces the impact of a potential lock, by reducing the transaction size.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e95df-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e95df-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e95df-114">バージョン 7.1 のタイムフレームでは、マルチスレッドを導入することでウェーブの割り当てステップを改善しました。</span><span class="sxs-lookup"><span data-stu-id="e95df-114">In the version 7.1 timeframe, we improved the allocation step of waving by introducing multithreading.</span></span> <span data-ttu-id="e95df-115">残りのステップは、現在マルチスレッドではなく、単一の長いデータベース トランザクションで実行されます。</span><span class="sxs-lookup"><span data-stu-id="e95df-115">The remainder of the steps are not currently multithreaded and run in a single long database transaction.</span></span> <span data-ttu-id="e95df-116">ピッキング作業の作成が表す長いトランザクションの最適化に関する問題の 1 つは、需要の補充がそのトランザクション内で作成されるという事実です。</span><span class="sxs-lookup"><span data-stu-id="e95df-116">One of the issues with optimizing the long transaction that creation of pick work represents is the fact that demand replenishment is created within that transaction.</span></span> <span data-ttu-id="e95df-117">将来のパフォーマンス最適化の目的で、補充作業作成ステップを独自のトランザクションを持つ独自のスレッドに分離します。</span><span class="sxs-lookup"><span data-stu-id="e95df-117">For future performance optimization purposes, we are separating the replenishment work creation step into its own thread that has its own transaction.</span></span>
<!--feature detail end -->









