---
title: ピッキング作業作成ステップからの需要補充作業の分割
description: この機能により、ユーザーは補充作業トランザクションを作業作成の残りの部分から分離することができます。
author: relnotes
ms.reviewer: josaw
ms.date: 11/19/2019
ms.assetid: 7a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: 4e2d99ef7131409652ef9c8084cb350af87892af
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889598"
---
# <a name="split-demand-replenishment-work-from-create-pick-work-step"></a><span data-ttu-id="aa38e-103">ピッキング作業作成ステップからの需要補充作業の分割</span><span class="sxs-lookup"><span data-stu-id="aa38e-103">Split demand replenishment work from create pick work step</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="aa38e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="aa38e-104">Enabled for</span></span>    |  <span data-ttu-id="aa38e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="aa38e-105">Public preview</span></span> | <span data-ttu-id="aa38e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="aa38e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="aa38e-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="aa38e-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="aa38e-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="aa38e-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="aa38e-109">2019 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="aa38e-109">Apr 1, 2019</span></span>| <span data-ttu-id="aa38e-110">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="aa38e-110">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="aa38e-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="aa38e-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="aa38e-112">この機能により、各トランザクションの将来のパフォーマンス向上が可能になります。</span><span class="sxs-lookup"><span data-stu-id="aa38e-112">This feature allows for future performance enhancements of each of the transactions.</span></span> <span data-ttu-id="aa38e-113">また、トランザクション サイズを小さくすることで、潜在的なロックの影響も本質的に軽減します。</span><span class="sxs-lookup"><span data-stu-id="aa38e-113">It also intrinsically reduces the impact of a potential lock, by reducing the transaction size.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="aa38e-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="aa38e-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="aa38e-115">バージョン 7.1 のタイムフレームでは、マルチスレッドを導入することでウェーブの割り当てステップを改善しました。</span><span class="sxs-lookup"><span data-stu-id="aa38e-115">In the version 7.1 timeframe, we improved the allocation step of waving by introducing multithreading.</span></span> <span data-ttu-id="aa38e-116">残りのステップは、現在マルチスレッドではなく、単一の長いデータベース トランザクションで実行されます。</span><span class="sxs-lookup"><span data-stu-id="aa38e-116">The remainder of the steps are not currently multithreaded and run in a single long database transaction.</span></span> <span data-ttu-id="aa38e-117">ピッキング作業の作成が表す長いトランザクションの最適化に関する問題の 1 つは、需要の補充がそのトランザクション内で作成されるという事実です。</span><span class="sxs-lookup"><span data-stu-id="aa38e-117">One of the issues with optimizing the long transaction that creation of pick work represents is the fact that demand replenishment is created within that transaction.</span></span> <span data-ttu-id="aa38e-118">将来のパフォーマンス最適化の目的で、補充作業作成ステップを独自のトランザクションを持つ独自のスレッドに分離します。</span><span class="sxs-lookup"><span data-stu-id="aa38e-118">For future performance optimization purposes, we are separating the replenishment work creation step into its own thread that has its own transaction.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="aa38e-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="aa38e-119">See also</span></span>

<span data-ttu-id="aa38e-120">[倉庫管理の概要](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/warehousing/warehouse-management-overview) (docs)</span><span class="sxs-lookup"><span data-stu-id="aa38e-120">[Warehouse management overview](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/warehousing/warehouse-management-overview) (docs)</span></span>
