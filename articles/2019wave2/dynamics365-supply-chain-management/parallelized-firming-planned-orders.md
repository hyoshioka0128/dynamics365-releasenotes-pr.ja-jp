---
title: 計画オーダーの並列確定
description: 計画オーダー ページから複数のスレッドによる並列確定を有効にします。
author: relnotes
ms.reviewer: josaw
ms.date: 12/02/2019
ms.assetid: 70517981-13cb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: crytt
dynamics365pdf: true
ms.openlocfilehash: d692499c0218c0113be64b88d54b57e41657b4b6
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889653"
---
# <a name="parallelized-firming-of-planned-orders"></a><span data-ttu-id="084a0-103">計画オーダーの並列確定</span><span class="sxs-lookup"><span data-stu-id="084a0-103">Parallelized firming of planned orders</span></span>


| <span data-ttu-id="084a0-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="084a0-104">Enabled for</span></span>    |  <span data-ttu-id="084a0-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="084a0-105">Public preview</span></span> | <span data-ttu-id="084a0-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="084a0-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="084a0-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="084a0-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="084a0-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="084a0-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="084a0-109">2019 年 9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="084a0-109">Sep 6, 2019</span></span>| <span data-ttu-id="084a0-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="084a0-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="084a0-111">2019 年 12 月 1 日</span><span class="sxs-lookup"><span data-stu-id="084a0-111">Dec 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="084a0-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="084a0-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="084a0-113">一度に多数の注文を確定する予定がある場合、実行を並列化すると、実行時間またはパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="084a0-113">If you are planning to firm many orders at once, parallelizing the run can improve the runtime or performance.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="084a0-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="084a0-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="084a0-115">計画オーダー ページからの複数のスレッドによる並列確定により、ユーザーは複数のスレッド間で確定プロセスを並列化することで確定プロセスを高速化できます。</span><span class="sxs-lookup"><span data-stu-id="084a0-115">Parallelized firming with multiple threads from the planned orders page enables the user to speed up the firming process by parallelizing the firming process across multiple threads.</span></span> <span data-ttu-id="084a0-116">これは、多数の計画オーダーが確定されている場合に意味がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="084a0-116">This can be relevant when a high number of planned orders are firmed.</span></span> <span data-ttu-id="084a0-117">並列確定とスレッド数のオプションは、確定に対して複数の計画オーダーが選択されている場合に利用可能です。</span><span class="sxs-lookup"><span data-stu-id="084a0-117">The parallelize firming and number of threads options are available when multiple planned orders are selected for firming.</span></span>
<!--feature detail end -->

<span data-ttu-id="084a0-118">![並列確定オプション](media/pf.png "並列確定オプション")</span><span class="sxs-lookup"><span data-stu-id="084a0-118">![Parallelized firming options](media/pf.png "Parallelized firming options")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="084a0-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="084a0-119">See also</span></span>

<span data-ttu-id="084a0-120">[並列確定](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/master-planning/maintain-planned-orders#parallelize-firming) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="084a0-120">[Parallelize firming](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/master-planning/maintain-planned-orders#parallelize-firming) (docs)</span></span>
