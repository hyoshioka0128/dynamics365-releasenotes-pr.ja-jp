---
title: パフォーマンスのための予算計画クエリの最適化
description: この機能は、データ処理時の予算計画モジュールのパフォーマンスを向上させます。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/06/2020
ms.assetid: f16181ba-862e-ea11-a810-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: e6117b5814e98b8b4e017b6231af2fe3ed704b9d
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3256456"
---
# <a name="budget-planning-query-optimization-for-performance"></a><span data-ttu-id="c3e1c-103">パフォーマンスのための予算計画クエリの最適化</span><span class="sxs-lookup"><span data-stu-id="c3e1c-103">Budget planning query optimization for performance</span></span>


| <span data-ttu-id="c3e1c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c3e1c-104">Enabled for</span></span>    |  <span data-ttu-id="c3e1c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c3e1c-105">Public preview</span></span> | <span data-ttu-id="c3e1c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c3e1c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c3e1c-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c3e1c-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c3e1c-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c3e1c-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c3e1c-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="c3e1c-109">Feb 3, 2020</span></span>| <span data-ttu-id="c3e1c-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c3e1c-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c3e1c-111">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="c3e1c-111">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c3e1c-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c3e1c-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c3e1c-113">予算計画データの処理のパフォーマンスを改善することにより、この機能はクエリがブロックされる可能性を減らします。</span><span class="sxs-lookup"><span data-stu-id="c3e1c-113">By improving the performance of processing budget planning data, this feature reduces the likelihood that queries will be blocked.</span></span> <span data-ttu-id="c3e1c-114">この機能は、データ処理で使用されるクエリに最適化も追加します。</span><span class="sxs-lookup"><span data-stu-id="c3e1c-114">The feature also adds optimizations to the queries used in data processing.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c3e1c-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c3e1c-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c3e1c-116">新機能が機能管理内で利用可能になり、予算計画モジュールでデータを処理する際のパフォーマンスの向上に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="c3e1c-116">A new feature is available within Feature management that helps improve performance when processing data in the Budget Planning module.</span></span> <span data-ttu-id="c3e1c-117">10.0.9 の初期リリースでは、この機能を使用すると、Excel の**発行**ボタンを使用して既存のレコードを更新するときのパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="c3e1c-117">On initial release in 10.0.9, this feature will improve performance when using the **Publish** button in Excel to update existing records.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="c3e1c-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="c3e1c-118">See also</span></span>

<!--docs start-->
<span data-ttu-id="c3e1c-119">[予算計画の構成](https://go.microsoft.com/fwlink/?linkid=2103507) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c3e1c-119">[Configuring budget planning](https://go.microsoft.com/fwlink/?linkid=2103507) (docs)</span></span>
<!--docs end-->
