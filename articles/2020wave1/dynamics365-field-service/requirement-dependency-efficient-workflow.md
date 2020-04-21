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
ms.openlocfilehash: b24d84c5851488c84f225b392bb798232207af85
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232057"
---
# <a name="requirement-dependency-for-efficient-workflow"></a><span data-ttu-id="1d475-103">効率的なワークフローのための要件の依存関係</span><span class="sxs-lookup"><span data-stu-id="1d475-103">Requirement dependency for efficient workflow</span></span>
[!include[dynamics365-field-service banner](../includes/dynamics365-field-service.md)]

| <span data-ttu-id="1d475-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1d475-104">Enabled for</span></span>    |  <span data-ttu-id="1d475-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1d475-105">Public preview</span></span> | <span data-ttu-id="1d475-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="1d475-106">Early access</span></span> | <span data-ttu-id="1d475-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="1d475-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="1d475-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="1d475-108">End users, automatically</span></span>|-|<span data-ttu-id="1d475-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1d475-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1d475-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="1d475-110">Feb 3, 2020</span></span>| <span data-ttu-id="1d475-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="1d475-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1d475-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1d475-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1d475-113">正しい順序で作業が実施されるように、作業を順序付けることが必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="1d475-113">Sometimes it's necessary to sequence work in order to make sure that it's done in the correct order.</span></span> <span data-ttu-id="1d475-114">たとえば、電気的な配線を行う前に物理的な設置を行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="1d475-114">For example, a physical installation must occur before electrical connection.</span></span> <span data-ttu-id="1d475-115">企業は、依存タスクが順番に実行されるようにすることで、運用ワークフローを最適化できます。</span><span class="sxs-lookup"><span data-stu-id="1d475-115">Businesses can optimize operations workflows by ensuring dependent tasks are done in order.</span></span> <span data-ttu-id="1d475-116">この機能により、組織は特定の順序で作業を完了することができます。</span><span class="sxs-lookup"><span data-stu-id="1d475-116">This feature allows organizations to complete work in a specific order.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1d475-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1d475-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1d475-118">この機能を使用すると、技術者が最適なワークフローに従い、最も効率的なサービス運用を実現するように、要件の依存関係を構成できます。</span><span class="sxs-lookup"><span data-stu-id="1d475-118">This feature enables the configuration of requirement dependencies to ensure technicians follow the optimal workflow and achieve the most efficient service operation.</span></span> <span data-ttu-id="1d475-119">要件の依存関係により、顧客は、先行する要件と後続する要件の依存関係に基づいて、特定の順序で要件をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="1d475-119">Requirement dependencies allow customers to schedule requirements in a specific order by relating them through a predecessor and successor dependency relationship.</span></span> <span data-ttu-id="1d475-120">たとえば、技術者は倉庫から特殊な部品をピックアップし、顧客のサイトで作業を行うことが必要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="1d475-120">For example, a technician might need to pick up a unique part from the warehouse and then perform work at the customer's site.</span></span> <span data-ttu-id="1d475-121">相互に依存する一連のタスクが必要な重要なジョブを、先行するタスクと後続するタスクとしてリンクし、リソース スケジューリング オプティマイザーを介して予約できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="1d475-121">Critical jobs that rely on a series of tasks dependent on one another can now be linked together as predecessors and successors and booked through the resource scheduling optimizer.</span></span> 
 
<span data-ttu-id="1d475-122">2020 年リリース ウェーブ 1 では、この機能は、スケジュール ボードでこうした予約を表示できるリソース スケジュール最適化 (RSO) によってのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="1d475-122">In 2020 release wave 1, this feature will only be supported by resource scheduling optimization with the ability to view these bookings on the schedule board.</span></span> <span data-ttu-id="1d475-123">また、これらの依存関係は、単一リソースかつ単一日のシナリオでのみ機能します。</span><span class="sxs-lookup"><span data-stu-id="1d475-123">Also these dependencies will work only for single-resource, single-day scenarios.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="1d475-124">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="1d475-124">This feature is available in the Unified Interface only.</span></span>







## <a name="see-also"></a><span data-ttu-id="1d475-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="1d475-125">See also</span></span>


<!--docs start-->
<span data-ttu-id="1d475-126">[要件の依存関係の順にスケジュールする](https://docs.microsoft.com/dynamics365/field-service/rso-requirement-dependency) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="1d475-126">[Schedule in sequence with requirement dependencies](https://docs.microsoft.com/dynamics365/field-service/rso-requirement-dependency) (docs)</span></span>
<!--docs end-->

