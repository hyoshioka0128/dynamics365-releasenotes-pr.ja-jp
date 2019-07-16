---
title: 遅延プット処理
description: プット プロセスを非同期に設定することができます。 作業明細行の特定のしきい値を超えるとプット処理が遅延されるように、システムをセットアップすることができます。
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 7862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: 88a606032304b512603c01cc51a4ed821ab1aa64
ms.sourcegitcommit: d6ff62c145bfdd7742034a67a29bf75938823eb0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/24/2019
ms.locfileid: "1701810"
---
# <a name="deferred-put-processing"></a><span data-ttu-id="f8177-104">遅延プット処理</span><span class="sxs-lookup"><span data-stu-id="f8177-104">Deferred put processing</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="f8177-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="f8177-105">Enabled for</span></span>    |  <span data-ttu-id="f8177-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f8177-106">Public preview</span></span> | <span data-ttu-id="f8177-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="f8177-107">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="f8177-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="f8177-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="f8177-109">2019 年 6 月</span><span class="sxs-lookup"><span data-stu-id="f8177-109">June 2019</span></span>| <span data-ttu-id="f8177-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="f8177-110">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="f8177-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f8177-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f8177-112">遅延プット処理により、モバイル デバイスは直ちに解放されて、ユーザーは新しいタスクを処理できます。</span><span class="sxs-lookup"><span data-stu-id="f8177-112">Deferred put processing will free up mobile devices right away, allowing the user to pick up new tasks.</span></span> <span data-ttu-id="f8177-113">また、システムは、プット処理のランダムなピーク時間にも耐性を持つようになります。すべての処理時間はバッチ サーバーによって処理されるため、倉庫の作業者は、プット登録のためのサーバー パフォーマンスの予期しない低下が発生した場合に中断されることなく操作できます。</span><span class="sxs-lookup"><span data-stu-id="f8177-113">The system will also become resilient to random peak times of put processing—all processing time will be handled by batch servers, allowing warehouse workers to operate without disruption when there is unexpected slow server performance for registration of puts.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f8177-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f8177-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f8177-115">これは、倉庫作業者の生産性向上に重点を置いたパフォーマンス関連の機能です。</span><span class="sxs-lookup"><span data-stu-id="f8177-115">This is a performance-related feature focused on increasing the productivity of warehouse workers.</span></span> <span data-ttu-id="f8177-116">モバイル デバイスが "フリーズ" する原因になる、プット完了のたびのさまざまなインベントリ更新のオンライン処理を行う必要がなく、そのプロセスを非同期的に実行できます。</span><span class="sxs-lookup"><span data-stu-id="f8177-116">Instead of requiring online processing of the various inventory updates each time a put is complete, which “freezes” the mobile device, we will allow for that process to be performed asynchronously.</span></span> <span data-ttu-id="f8177-117">倉庫作業者は、一定数の更新を必要とするすべての作業のパフォーマンスが向上します。たとえば、10 明細行を選択するプット登録には、関連する場所の 20 の在庫更新と 10 の元伝票明細行の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="f8177-117">Warehouse workers will experience an increase of performance for all operations requiring a certain number of updates—for example, a put registration of a pick of 10 lines involves 20 inventory updates for the locations involved and 10 source document lines updates.</span></span> <span data-ttu-id="f8177-118">これらの操作はバッチによって自動化され、システムの負荷はよりバランスがとれたものになります。</span><span class="sxs-lookup"><span data-stu-id="f8177-118">These operations will be automated through batches, and the load of the system will be more balanced.</span></span> <span data-ttu-id="f8177-119">倉庫作業者はシステムの散発的またはランダムなピーク使用率に依存しなくなります。</span><span class="sxs-lookup"><span data-stu-id="f8177-119">Warehouse workers will not be dependent on sporadic or random peak utilization of the system.</span></span> <span data-ttu-id="f8177-120">この機能は、一部の顧客でテストできるように提供されます。出荷文書のマニフェストと印刷などのさまざまなフォローアップ プロセスへの影響を理解したいと思います。</span><span class="sxs-lookup"><span data-stu-id="f8177-120">The feature will be flighted so that we can test the feature with some customers—we want to understand the impact on various follow-up processes such as the manifesting and printing of shipping documents.</span></span>
<!--feature detail end -->

<span data-ttu-id="f8177-121">![Work processing policies.png](media/work-processing-policies.png "Work processing policies.png")</span><span class="sxs-lookup"><span data-stu-id="f8177-121">![Work processing policies.png](media/work-processing-policies.png "Work processing policies.png")</span></span>
<!-- Picture 1 -->










