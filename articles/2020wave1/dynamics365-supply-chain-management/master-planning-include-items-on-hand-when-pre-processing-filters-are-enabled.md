---
title: 前処理フィルターが有効になっている場合に、手持在庫のある品目がマスター プランに含まれる
description: 前処理フィルターが有効になっている場合に、手持在庫のある品目がマスター プランに含まれる
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/14/2020
ms.assetid: 39eb3f7d-9563-ea11-a811-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: crytt
dynamics365pdf: true
ms.openlocfilehash: a7d8e6bc38e6494a435f7cb8227001cc909383da
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273887"
---
# <a name="master-planning-includes-items-with-on-hand-inventory-when-pre-processing-filters-are-enabled"></a><span data-ttu-id="81a63-103">前処理フィルターが有効になっている場合に、手持在庫のある品目がマスター プランに含まれる</span><span class="sxs-lookup"><span data-stu-id="81a63-103">Master planning includes items with on-hand inventory when pre-processing filters are enabled</span></span>


| <span data-ttu-id="81a63-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="81a63-104">Enabled for</span></span>    |  <span data-ttu-id="81a63-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="81a63-105">Public preview</span></span> | <span data-ttu-id="81a63-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="81a63-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="81a63-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="81a63-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="81a63-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="81a63-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="81a63-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="81a63-109">Feb 1, 2020</span></span>| <span data-ttu-id="81a63-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="81a63-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="81a63-111">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="81a63-111">Apr 3, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="81a63-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="81a63-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="81a63-113">この機能を使用すると、**マスター プランのパラメーター** ページで**前処理: 直納品目で自動的にフィルター処理する**設定が有効になっている場合に、実行されたマスター プランに手持在庫のある品目が常に含まれるようになります。</span><span class="sxs-lookup"><span data-stu-id="81a63-113">This feature ensures that items with on-hand inventory will always be included in the master planning run when the **Pre-processing: Automatically filter by items with direct demand** setting is enabled on the **Master planning parameters** page.</span></span> 

<span data-ttu-id="81a63-114">この機能を使用するには、[機能管理](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/feature-management/feature-management-overview?toc=/dynamics365/supply-chain/toc.json)で_前処理フィルターが有効になっている場合に手持在庫のある品目を含める_機能を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="81a63-114">To use this capability, you must enable the _Include items with on-hand when pre-processing filters are enabled_ feature in [Feature management](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/feature-management/feature-management-overview?toc=/dynamics365/supply-chain/toc.json).</span></span>

> [!IMPORTANT]
> <span data-ttu-id="81a63-115">製造計画プロセスで*展開*または*正味変更の更新*機能を使用している場合は、この機能を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="81a63-115">If you are relying on *Explosion* or *Net change update* functionality for manufacturing planning processes, then this feature must be enabled.</span></span> <span data-ttu-id="81a63-116">そうしないと、**正味必要量**フォームに直納以外の品目の誤った手持在庫のデータが表示され、展開時に誤った計画オーダーが生成される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="81a63-116">Otherwise, incorrect on-hand data might show up in the **Net requirements** form for the items without direct demand, and incorrect planned orders might be generated during explosion.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="81a63-117">関連項目</span><span class="sxs-lookup"><span data-stu-id="81a63-117">See also</span></span>

<!--docs start-->
<span data-ttu-id="81a63-118">[直納品目で自動的にフィルター処理する](https://docs.microsoft.com/dynamics365/supply-chain/master-planning/master-planning-performance#automatically-filter-by-items-with-direct-demand) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="81a63-118">[Automatically filter by items with direct demand](https://docs.microsoft.com/dynamics365/supply-chain/master-planning/master-planning-performance#automatically-filter-by-items-with-direct-demand) (docs)</span></span>
<!--docs end-->
