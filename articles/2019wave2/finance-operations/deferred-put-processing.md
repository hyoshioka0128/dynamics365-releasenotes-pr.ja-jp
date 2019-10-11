---
title: 遅延プット処理
description: プット プロセスを非同期に設定することができます。 作業明細行の特定のしきい値を超えるとプット処理が遅延されるように、システムをセットアップすることができます。
author: relnotes
ms.reviewer: josaw
ms.date: 08/13/2019
ms.assetid: 7862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: 5fbe3120a505c6c87eaa967d3505d4511cc319eb
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141494"
---
# <a name="deferred-put-processing"></a><span data-ttu-id="a83ba-104">遅延プット処理</span><span class="sxs-lookup"><span data-stu-id="a83ba-104">Deferred put processing</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="a83ba-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="a83ba-105">Enabled for</span></span>    |  <span data-ttu-id="a83ba-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a83ba-106">Public preview</span></span> | <span data-ttu-id="a83ba-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="a83ba-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a83ba-108">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a83ba-108">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="a83ba-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a83ba-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a83ba-110">2019 年 6 月 5 日</span><span class="sxs-lookup"><span data-stu-id="a83ba-110">Jun 5, 2019</span></span>| <span data-ttu-id="a83ba-111">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="a83ba-111">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="a83ba-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a83ba-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a83ba-113">遅延プット処理により、モバイル デバイスは直ちに解放されて、ユーザーは新しいタスクを処理できます。</span><span class="sxs-lookup"><span data-stu-id="a83ba-113">Deferred put processing will free up mobile devices right away, allowing the user to pick up new tasks.</span></span> <span data-ttu-id="a83ba-114">また、システムは、プット処理のランダムなピーク時間にも耐性を持つようになります。すべての処理時間はバッチ サーバーによって処理されるため、倉庫の作業者は、プット登録のためのサーバー パフォーマンスの予期しない低下が発生した場合に中断されることなく操作できます。</span><span class="sxs-lookup"><span data-stu-id="a83ba-114">The system will also become resilient to random peak times of put processing—all processing time will be handled by batch servers, allowing warehouse workers to operate without disruption when there is unexpected slow server performance for registration of puts.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a83ba-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a83ba-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a83ba-116">これは、倉庫作業者の生産性向上に重点を置いたパフォーマンス関連の機能です。</span><span class="sxs-lookup"><span data-stu-id="a83ba-116">This is a performance-related feature focused on increasing the productivity of warehouse workers.</span></span> <span data-ttu-id="a83ba-117">モバイル デバイスが "フリーズ" する原因になる、プット完了のたびのさまざまなインベントリ更新のオンライン処理を行う必要がなく、そのプロセスを非同期的に実行できます。</span><span class="sxs-lookup"><span data-stu-id="a83ba-117">Instead of requiring online processing of the various inventory updates each time a put is complete, which “freezes” the mobile device, we will allow for that process to be performed asynchronously.</span></span> <span data-ttu-id="a83ba-118">倉庫作業者は、一定数の更新を必要とするすべての作業のパフォーマンスが向上します。たとえば、10 明細行を選択するプット登録には、関連する場所の 20 の在庫更新と 10 の元伝票明細行の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="a83ba-118">Warehouse workers will experience an increase of performance for all operations requiring a certain number of updates—for example, a put registration of a pick of 10 lines involves 20 inventory updates for the locations involved and 10 source document lines updates.</span></span> <span data-ttu-id="a83ba-119">これらの操作はバッチによって自動化され、システムの負荷はよりバランスがとれたものになります。</span><span class="sxs-lookup"><span data-stu-id="a83ba-119">These operations will be automated through batches, and the load of the system will be more balanced.</span></span> <span data-ttu-id="a83ba-120">倉庫作業者はシステムの散発的またはランダムなピーク使用率に依存しなくなります。</span><span class="sxs-lookup"><span data-stu-id="a83ba-120">Warehouse workers will not be dependent on sporadic or random peak utilization of the system.</span></span> 

<span data-ttu-id="a83ba-121">この機能は、一部の顧客でテストできるように提供されます。出荷ドキュメントのマニフェストと印刷などのさまざまなフォローアップ プロセスへの影響を理解する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a83ba-121">The feature will be flighted so that we can test the feature with some customers—we want to understand the impact on various follow-up processes such as the manifesting and printing of shipping documents.</span></span>
<!--feature detail end -->

<span data-ttu-id="a83ba-122">![作業処理ポリシー](media/work-processing-policies.png "作業処理ポリシー")</span><span class="sxs-lookup"><span data-stu-id="a83ba-122">![Work processing policies](media/work-processing-policies.png "Work processing policies")</span></span>
<!-- Picture 1 -->











## <a name="see-also"></a><span data-ttu-id="a83ba-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="a83ba-123">See also</span></span>

<span data-ttu-id="a83ba-124">[倉庫作業の繰延処理](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/warehousing/deferred-put) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="a83ba-124">[Deferred processing of warehouse work](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/warehousing/deferred-put) (docs)</span></span>