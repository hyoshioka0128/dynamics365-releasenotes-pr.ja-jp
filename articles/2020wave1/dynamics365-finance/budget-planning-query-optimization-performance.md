---
title: パフォーマンスのための予算計画クエリの最適化
description: この機能は、データ処理時の予算計画モジュールのパフォーマンスを向上させます。
author: relnotes
ms.reviewer: roschlom
ms.date: 01/08/2020
ms.assetid: f16181ba-862e-ea11-a810-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: d833a0716ce42312ec38fe36d3345d1e39d3fef3
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986767"
---
# <a name="budget-planning-query-optimization-for-performance"></a><span data-ttu-id="81240-103">パフォーマンスのための予算計画クエリの最適化</span><span class="sxs-lookup"><span data-stu-id="81240-103">Budget planning query optimization for performance</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="81240-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="81240-104">Enabled for</span></span>    |  <span data-ttu-id="81240-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="81240-105">Public preview</span></span> | <span data-ttu-id="81240-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="81240-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="81240-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="81240-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="81240-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="81240-108">Feb 2020</span></span>| <span data-ttu-id="81240-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="81240-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="81240-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="81240-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="81240-111">予算計画データの処理のパフォーマンスを改善することにより、この機能はクエリがブロックされる可能性を減らします。</span><span class="sxs-lookup"><span data-stu-id="81240-111">By improving the performance of processing budget planning data, this feature reduces the likelihood that queries will be blocked.</span></span> <span data-ttu-id="81240-112">この機能は、データ処理で使用されるクエリに最適化も追加します。</span><span class="sxs-lookup"><span data-stu-id="81240-112">The feature also adds optimizations to the queries used in data processing.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="81240-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="81240-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="81240-114">新機能が機能管理内で利用可能になり、予算計画モジュールでデータを処理する際のパフォーマンスの向上に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="81240-114">A new feature is available within Feature management that helps improve performance when processing data in the Budget Planning module.</span></span> <span data-ttu-id="81240-115">10.0.9 の初期リリースでは、この機能を使用すると、Excel の**発行**ボタンを使用して既存のレコードを更新するときのパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="81240-115">On initial release in 10.0.9, this feature will improve performance when using the **Publish** button in Excel to update existing records.</span></span> 

<!--feature detail end -->









