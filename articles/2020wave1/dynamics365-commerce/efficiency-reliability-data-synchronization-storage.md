---
title: データの同期および保存の効率と信頼性
description: この機能は、CDX バックグラウンド最適化を提供し、パフォーマンスと信頼性を向上させるための機能を複数の方法で強化します。
author: relnotes
ms.reviewer: josaw
ms.date: 05/26/2020
ms.assetid: 9b3daeb0-73fb-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: 735da0fc9b1b98e1d7bf7a2cdc65beea538862d4
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3416361"
---
# <a name="efficiency-and-reliability-of-data-synchronization-and-storage"></a><span data-ttu-id="0d297-103">データの同期および保存の効率と信頼性</span><span class="sxs-lookup"><span data-stu-id="0d297-103">Efficiency and reliability of data synchronization and storage</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="0d297-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0d297-104">Enabled for</span></span>    |  <span data-ttu-id="0d297-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0d297-105">Public preview</span></span> | <span data-ttu-id="0d297-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="0d297-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0d297-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="0d297-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="0d297-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0d297-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0d297-109">2020 年 5 月 18 日</span><span class="sxs-lookup"><span data-stu-id="0d297-109">May 18, 2020</span></span>| <span data-ttu-id="0d297-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="0d297-110">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="0d297-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0d297-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0d297-112">Channel Data Exchange (CDX) コンポーネントは、Commerce チャネル データベース (同じ場所に配置されたクラウド チャネル、Commerce Cloud Scale Unit、Commerce Store Scale Unit、およびオフライン サポート付きの最新の販売時点管理 (MPOS)) 間でデータを同期します。</span><span class="sxs-lookup"><span data-stu-id="0d297-112">The Channel Data Exchange (CDX) component synchronizes data between Commerce Channel Databases (co-located cloud channel, Commerce Cloud Scale Unit, Commerce Store Scale Unit, and Modern point of sale (MPOS) with offline support).</span></span>

<span data-ttu-id="0d297-113">データの利用不可、他のコンポーネントの速度低下、またはデータベース データとログ サイズへの影響に関する問題を解決するいくつかのパフォーマンスと信頼性の更新プログラムが実装されました。</span><span class="sxs-lookup"><span data-stu-id="0d297-113">A number of performance and reliability updates have been implemented that solve issues regarding data unavailability, slowness on other components, or impact on database data and log sizes.</span></span> <span data-ttu-id="0d297-114">データ同期フレームワーク (CDX) の可用性、信頼性、効率の最大化には常に重点が置かれています。</span><span class="sxs-lookup"><span data-stu-id="0d297-114">It is a constant focus to maximize availability, reliability, and efficiency in our data synchronization framework (CDX).</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0d297-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0d297-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0d297-116">この機能には、次の領域でのいくつかの独立した改善が含まれます。</span><span class="sxs-lookup"><span data-stu-id="0d297-116">This feature will contain several independent improvements in the following areas:</span></span>

- <span data-ttu-id="0d297-117">コマース本部でのデータ パッケージ生成の改善。</span><span class="sxs-lookup"><span data-stu-id="0d297-117">Improve data package generation in Commerce headquarters.</span></span>
- <span data-ttu-id="0d297-118">チャネル データベースに適用する際のデータ パッケージの改善。</span><span class="sxs-lookup"><span data-stu-id="0d297-118">Improve data package when applying to a channel database.</span></span>
- <span data-ttu-id="0d297-119">必要な完全同期の数の削減と、避けられない場合はパフォーマンスへの影響の最小化。</span><span class="sxs-lookup"><span data-stu-id="0d297-119">Reduce the number of required full synchronizations and, when unavoidable, minimize the performance impact.</span></span>
- <span data-ttu-id="0d297-120">チャネル レベルでのマスター データ削除、DB 統計の更新、同期中のインデックス作成など、複数のデータ最適化。</span><span class="sxs-lookup"><span data-stu-id="0d297-120">Multiple data optimizations, including master data stripping at the channel level, updating DB statistics, and indexing during synchronization.</span></span>
<!--feature detail end -->









