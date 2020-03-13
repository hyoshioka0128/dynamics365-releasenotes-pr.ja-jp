---
title: 効率的なワークフローのための要件の依存関係
description: 要件やタスク間に依存関係を作成して、一貫した効率的なワークフローを推進するために必要な順序で実行されるようにします。
author: relnotes
ms.reviewer: krbjoran
ms.date: 02/17/2020
ms.assetid: f9f164ca-0c1e-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: ragguru
dynamics365pdf: true
ms.openlocfilehash: dd13f32dca735bf68beb5fda2de6af146187351e
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3079601"
---
# <a name="requirement-dependency-for-efficient-workflow"></a><span data-ttu-id="0f72c-103">効率的なワークフローのための要件の依存関係</span><span class="sxs-lookup"><span data-stu-id="0f72c-103">Requirement dependency for efficient workflow</span></span>
[!include[dynamics365-field-service banner](../includes/dynamics365-field-service.md)]

| <span data-ttu-id="0f72c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0f72c-104">Enabled for</span></span>    |  <span data-ttu-id="0f72c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0f72c-105">Public preview</span></span> | <span data-ttu-id="0f72c-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="0f72c-106">Early access</span></span> | <span data-ttu-id="0f72c-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="0f72c-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="0f72c-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="0f72c-108">End users, automatically</span></span>|-|<span data-ttu-id="0f72c-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0f72c-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0f72c-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="0f72c-110">Feb 3, 2020</span></span>| <span data-ttu-id="0f72c-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="0f72c-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="0f72c-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0f72c-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0f72c-113">正しい順序で作業が実施されるように、作業を順序付けることが必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="0f72c-113">Sometimes it's necessary to sequence work in order to make sure that it's done in the correct order.</span></span> <span data-ttu-id="0f72c-114">たとえば、電気的な配線を行う前に物理的な設置を行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="0f72c-114">For example, a physical installation must occur before electrical connection.</span></span> <span data-ttu-id="0f72c-115">企業は、依存タスクが順番に実行されるようにすることで、運用ワークフローを最適化できます。</span><span class="sxs-lookup"><span data-stu-id="0f72c-115">Businesses can optimize operations workflows by ensuring dependent tasks are done in order.</span></span> <span data-ttu-id="0f72c-116">この機能により、組織は特定の順序で作業を完了することができます。</span><span class="sxs-lookup"><span data-stu-id="0f72c-116">This feature allows organizations to complete work in a specific order.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0f72c-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0f72c-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0f72c-118">この機能を使用すると、技術者が最適なワークフローに従い、最も効率的なサービス運用を実現するように、要件の依存関係を構成できます。</span><span class="sxs-lookup"><span data-stu-id="0f72c-118">This feature enables the configuration of requirement dependencies to ensure technicians follow the optimal workflow and achieve the most efficient service operation.</span></span> <span data-ttu-id="0f72c-119">要件の依存関係により、顧客は、先行する要件と後続する要件の依存関係に基づいて、特定の順序で要件をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="0f72c-119">Requirement dependencies allow customers to schedule requirements in a specific order by relating them through a predecessor and successor dependency relationship.</span></span> <span data-ttu-id="0f72c-120">たとえば、技術者は倉庫から特殊な部品をピックアップし、顧客のサイトで作業を行うことが必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="0f72c-120">For example, a technician might need to pick up a unique part from the warehouse and then perform work at the customer's site.</span></span> <span data-ttu-id="0f72c-121">相互に依存する一連のタスクが必要な重要なジョブを、先行するタスクと後続するタスクとしてリンクし、リソース スケジューリング オプティマイザーを介して予約できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0f72c-121">Critical jobs that rely on a series of tasks dependent on one another can now be linked together as predecessors and successors and booked through the resource scheduling optimizer.</span></span> 
 
<span data-ttu-id="0f72c-122">2020 年リリース ウェーブ 1 では、この機能は、スケジュール ボードでこうした予約を表示できるリソース スケジュール最適化 (RSO) によってのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="0f72c-122">In 2020 release wave 1, this feature will only be supported by resource scheduling optimization with the ability to view these bookings on the schedule board.</span></span> <span data-ttu-id="0f72c-123">また、これらの依存関係は、単一リソースかつ単一日のシナリオでのみ機能します。</span><span class="sxs-lookup"><span data-stu-id="0f72c-123">Also these dependencies will work only for single-resource, single-day scenarios.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="0f72c-124">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="0f72c-124">This feature is available in the Unified Interface only.</span></span>







## <a name="see-also"></a><span data-ttu-id="0f72c-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="0f72c-125">See also</span></span>

<span data-ttu-id="0f72c-126">[要件の依存関係の順にスケジュールする](https://docs.microsoft.com/dynamics365/field-service/rso-requirement-dependency) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="0f72c-126">[Schedule in sequence with requirement dependencies](https://docs.microsoft.com/dynamics365/field-service/rso-requirement-dependency) (docs)</span></span>
