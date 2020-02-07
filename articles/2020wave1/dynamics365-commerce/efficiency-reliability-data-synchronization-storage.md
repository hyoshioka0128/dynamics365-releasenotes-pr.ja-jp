---
title: データの同期および保存の効率と信頼性
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 01/11/2020
ms.assetid: 9b3daeb0-73fb-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: b4ed0b81d824697a0ea19c58ec8fb98fd93ce5c4
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986643"
---
# <a name="efficiency-and-reliability-of-data-synchronization-and-storage"></a><span data-ttu-id="d1f8c-102">データの同期および保存の効率と信頼性</span><span class="sxs-lookup"><span data-stu-id="d1f8c-102">Efficiency and reliability of data synchronization and storage</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="d1f8c-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="d1f8c-103">Enabled for</span></span>    |  <span data-ttu-id="d1f8c-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d1f8c-104">Public preview</span></span> | <span data-ttu-id="d1f8c-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="d1f8c-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d1f8c-106">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="d1f8c-106">End users, automatically</span></span>|<span data-ttu-id="d1f8c-107">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="d1f8c-107">May 2020</span></span>| <span data-ttu-id="d1f8c-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="d1f8c-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="d1f8c-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d1f8c-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d1f8c-110">Channel Data Exchange (CDX) コンポーネントは、Commerce チャネル データベース (同じ場所に配置されたクラウド チャネル、Commerce Cloud Scale Unit、Commerce Store Scale Unit、およびオフライン サポート付きの最新の販売時点管理 (POS)) 間でデータを同期します。</span><span class="sxs-lookup"><span data-stu-id="d1f8c-110">Our Channel Data Exchange (CDX) component synchronizes data between Commerce Channel Databases (co-located cloud channel, Commerce Cloud Scale Unit, Commerce Store Scale Unit, and Modern point of sale (POS) with offline support).</span></span>

<span data-ttu-id="d1f8c-111">データの利用不可、他のコンポーネントの速度低下、またはデータベース データとログ サイズへの影響に関する問題を解決するいくつかのパフォーマンスと信頼性の更新プログラムが実装されました。</span><span class="sxs-lookup"><span data-stu-id="d1f8c-111">A number of performance and reliability updates have been implemented that solve issues regarding data unavailability, slowness on other components, or impact on database data and log sizes.</span></span> <span data-ttu-id="d1f8c-112">データ同期フレームワーク (CDX) の可用性、信頼性、効率の最大化には常に重点が置かれています。</span><span class="sxs-lookup"><span data-stu-id="d1f8c-112">It is a constant focus to maximize availability, reliability, and efficiency in our data synchronization framework (CDX).</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d1f8c-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d1f8c-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d1f8c-114">この機能には、次の領域でのいくつかの独立した改善が含まれます。</span><span class="sxs-lookup"><span data-stu-id="d1f8c-114">This feature will contain several independent improvements in the following areas:</span></span>

- <span data-ttu-id="d1f8c-115">本社でのデータ パッケージ生成の改善。</span><span class="sxs-lookup"><span data-stu-id="d1f8c-115">Improve data package generation in headquarters.</span></span>
- <span data-ttu-id="d1f8c-116">チャネル データベースに適用する際のデータ パッケージの改善。</span><span class="sxs-lookup"><span data-stu-id="d1f8c-116">Improve data package when applying to a channel database.</span></span>
- <span data-ttu-id="d1f8c-117">必要な完全同期の数の削減と、避けられない場合はパフォーマンスへの影響の最小化。</span><span class="sxs-lookup"><span data-stu-id="d1f8c-117">Reduce the number of required full synchronizations and, when unavoidable, minimize the performance impact.</span></span>
- <span data-ttu-id="d1f8c-118">チャネル レベルでのマスター データ削除、DB 統計の更新、同期中のインデックス作成など、複数のデータ最適化。</span><span class="sxs-lookup"><span data-stu-id="d1f8c-118">Multiple data optimizations, including master data stripping at the channel level, updating DB statistics, and indexing during synchronization.</span></span>
<!--feature detail end -->









