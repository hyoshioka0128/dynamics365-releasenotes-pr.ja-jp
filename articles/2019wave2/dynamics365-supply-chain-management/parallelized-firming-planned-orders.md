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
ms.openlocfilehash: fbb241b085b45e264d848cdf5aa7d169296e9e00
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660598"
---
# <a name="parallelized-firming-of-planned-orders"></a><span data-ttu-id="cf5a7-103">計画オーダーの並列確定</span><span class="sxs-lookup"><span data-stu-id="cf5a7-103">Parallelized firming of planned orders</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="cf5a7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cf5a7-104">Enabled for</span></span>    |  <span data-ttu-id="cf5a7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cf5a7-105">Public preview</span></span> | <span data-ttu-id="cf5a7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="cf5a7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="cf5a7-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="cf5a7-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="cf5a7-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="cf5a7-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="cf5a7-109">2019 年 9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="cf5a7-109">Sep 6, 2019</span></span>| <span data-ttu-id="cf5a7-110">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="cf5a7-110">Dec 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="cf5a7-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="cf5a7-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="cf5a7-112">一度に多数の注文を確定する予定がある場合、実行を並列化すると、実行時間またはパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="cf5a7-112">If you are planning to firm many orders at once, parallelizing the run can improve the runtime or performance.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="cf5a7-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cf5a7-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cf5a7-114">計画オーダー ページからの複数のスレッドによる並列確定により、ユーザーは複数のスレッド間で確定プロセスを並列化することで確定プロセスを高速化できます。</span><span class="sxs-lookup"><span data-stu-id="cf5a7-114">Parallelized firming with multiple threads from the planned orders page enables the user to speed up the firming process by parallelizing the firming process across multiple threads.</span></span> <span data-ttu-id="cf5a7-115">これは、多数の計画オーダーが確定されている場合に意味がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="cf5a7-115">This can be relevant when a high number of planned orders are firmed.</span></span> <span data-ttu-id="cf5a7-116">並列確定とスレッド数のオプションは、確定に対して複数の計画オーダーが選択されている場合に利用可能です。</span><span class="sxs-lookup"><span data-stu-id="cf5a7-116">The parallelize firming and number of threads options are available when multiple planned orders are selected for firming.</span></span> 
<!--feature detail end -->

<span data-ttu-id="cf5a7-117">![並列確定オプション](media/pf.png "並列確定オプション")</span><span class="sxs-lookup"><span data-stu-id="cf5a7-117">![Parallelized firming options](media/pf.png "Parallelized firming options")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="cf5a7-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="cf5a7-118">See also</span></span>

<span data-ttu-id="cf5a7-119">[並列確定](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/master-planning/maintain-planned-orders#parallelize-firming) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="cf5a7-119">[Parallelize firming](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/master-planning/maintain-planned-orders#parallelize-firming) (docs)</span></span>
