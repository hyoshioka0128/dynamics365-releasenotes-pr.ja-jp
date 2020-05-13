---
title: ピッキング作業作成ステップからの需要補充作業の分割
description: この機能により、ユーザーは補充作業トランザクションを作業作成の残りの部分から分離することができます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 03/19/2020
ms.assetid: 7a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: d5091ab8169a37cf682680bf62c28e32ba213f23
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178804"
---
# <a name="split-demand-replenishment-work-from-create-pick-work-step"></a><span data-ttu-id="66659-103">ピッキング作業作成ステップからの需要補充作業の分割</span><span class="sxs-lookup"><span data-stu-id="66659-103">Split demand replenishment work from create pick work step</span></span>


| <span data-ttu-id="66659-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="66659-104">Enabled for</span></span>    |  <span data-ttu-id="66659-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="66659-105">Public preview</span></span> | <span data-ttu-id="66659-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="66659-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="66659-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="66659-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="66659-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="66659-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="66659-109">2019 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="66659-109">Apr 1, 2019</span></span>| <span data-ttu-id="66659-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="66659-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="66659-111">2020 年 1 月 27 日</span><span class="sxs-lookup"><span data-stu-id="66659-111">Jan 27, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="66659-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="66659-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="66659-113">この機能により、各トランザクションの将来のパフォーマンス向上が可能になります。</span><span class="sxs-lookup"><span data-stu-id="66659-113">This feature allows for future performance enhancements of each of the transactions.</span></span> <span data-ttu-id="66659-114">また、トランザクション サイズを小さくすることで、潜在的なロックの影響も本質的に軽減します。</span><span class="sxs-lookup"><span data-stu-id="66659-114">It also intrinsically reduces the impact of a potential lock, by reducing the transaction size.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="66659-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="66659-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="66659-116">バージョン 7.1 のタイムフレームでは、マルチスレッドを導入することでウェーブの割り当てステップを改善しました。</span><span class="sxs-lookup"><span data-stu-id="66659-116">In the version 7.1 timeframe, we improved the allocation step of waving by introducing multithreading.</span></span> <span data-ttu-id="66659-117">残りのステップは、現在マルチスレッドではなく、単一の長いデータベース トランザクションで実行されます。</span><span class="sxs-lookup"><span data-stu-id="66659-117">The remainder of the steps are not currently multithreaded and run in a single long database transaction.</span></span> <span data-ttu-id="66659-118">ピッキング作業の作成が表す長いトランザクションの最適化に関する問題の 1 つは、需要の補充がそのトランザクション内で作成されるという事実です。</span><span class="sxs-lookup"><span data-stu-id="66659-118">One of the issues with optimizing the long transaction that creation of pick work represents is the fact that demand replenishment is created within that transaction.</span></span> <span data-ttu-id="66659-119">将来のパフォーマンス最適化の目的で、補充作業作成ステップを独自のトランザクションを持つ独自のスレッドに分離します。</span><span class="sxs-lookup"><span data-stu-id="66659-119">For future performance optimization purposes, we are separating the replenishment work creation step into its own thread that has its own transaction.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="66659-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="66659-120">See also</span></span>

<span data-ttu-id="66659-121">[倉庫管理の概要](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/warehousing/warehouse-management-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="66659-121">[Warehouse management overview](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/warehousing/warehouse-management-overview) (docs)</span></span>
