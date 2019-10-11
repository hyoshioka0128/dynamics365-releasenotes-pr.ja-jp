---
title: 計画オーダーの並列確定
description: 計画オーダー ページから複数のスレッドによる並列確定を有効にします。
author: relnotes
ms.reviewer: josaw
ms.date: 09/12/2019
ms.assetid: 70517981-13cb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: crytt
dynamics365pdf: true
ms.openlocfilehash: 06917cb5704084f969bdb89ef632d2777e2d1ff2
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143001"
---
# <a name="parallelized-firming-of-planned-orders"></a><span data-ttu-id="c86f0-103">計画オーダーの並列確定</span><span class="sxs-lookup"><span data-stu-id="c86f0-103">Parallelized firming of planned orders</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="c86f0-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c86f0-104">Enabled for</span></span>    |  <span data-ttu-id="c86f0-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c86f0-105">Public preview</span></span> | <span data-ttu-id="c86f0-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c86f0-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c86f0-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c86f0-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="c86f0-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c86f0-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c86f0-109">2019 年 9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="c86f0-109">Sep 6, 2019</span></span>| <span data-ttu-id="c86f0-110">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="c86f0-110">Dec 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="c86f0-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c86f0-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c86f0-112">一度に多数の注文を確定する予定がある場合、実行を並列化すると、実行時間またはパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="c86f0-112">If you are planning to firm many orders at once, parallelizing the run can improve the run time or performance.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c86f0-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c86f0-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c86f0-114">計画オーダー ページからの複数のスレッドによる並列確定により、ユーザーは複数のスレッド間で確定プロセスを並列化することで確定プロセスを高速化できます。</span><span class="sxs-lookup"><span data-stu-id="c86f0-114">Parallelized firming with multiple threads from the planned orders page enables the user to speed up the firming process by parallelizing the firming process across multiple threads.</span></span> <span data-ttu-id="c86f0-115">これは、多数の計画オーダーが確定されている場合に意味がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="c86f0-115">This can be relevant when a high number of planned orders are firmed.</span></span> <span data-ttu-id="c86f0-116">並列確定とスレッド数のオプションは、確定に対して複数の計画オーダーが選択されている場合に利用可能です。</span><span class="sxs-lookup"><span data-stu-id="c86f0-116">The parallelize firming and number of threads options are available when multiple planned orders are selected for firming.</span></span> 
<!--feature detail end -->

<span data-ttu-id="c86f0-117">![並列確定オプション](media/pf.png "並列確定オプション")</span><span class="sxs-lookup"><span data-stu-id="c86f0-117">![Parallelized firming options](media/pf.png "Parallelized firming options")</span></span>
<!-- Picture 1 -->











## <a name="see-also"></a><span data-ttu-id="c86f0-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="c86f0-118">See also</span></span>

<span data-ttu-id="c86f0-119">[並列確定](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/master-planning/maintain-planned-orders#parallelize-firming) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c86f0-119">[Parallelize firming](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/master-planning/maintain-planned-orders#parallelize-firming) (docs)</span></span>
