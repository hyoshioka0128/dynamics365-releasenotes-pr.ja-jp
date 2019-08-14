---
title: 遅延プット処理
description: プット プロセスを非同期に設定することができます。 作業明細行の特定のしきい値を超えるとプット処理が遅延されるように、システムをセットアップすることができます。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: 7862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: 73c8291d440f8dfa37752f88df1e5ed5848667a4
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854308"
---
# <a name="deferred-put-processing"></a><span data-ttu-id="5e3de-104">遅延プット処理</span><span class="sxs-lookup"><span data-stu-id="5e3de-104">Deferred put processing</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="5e3de-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="5e3de-105">Enabled for</span></span>    |  <span data-ttu-id="5e3de-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5e3de-106">Public preview</span></span> | <span data-ttu-id="5e3de-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="5e3de-107">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="5e3de-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="5e3de-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="5e3de-109">2019 年 6 月</span><span class="sxs-lookup"><span data-stu-id="5e3de-109">June 2019</span></span>| <span data-ttu-id="5e3de-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="5e3de-110">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="5e3de-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5e3de-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5e3de-112">遅延プット処理により、モバイル デバイスは直ちに解放されて、ユーザーは新しいタスクを処理できます。</span><span class="sxs-lookup"><span data-stu-id="5e3de-112">Deferred put processing will free up mobile devices right away, allowing the user to pick up new tasks.</span></span> <span data-ttu-id="5e3de-113">また、システムは、プット処理のランダムなピーク時間にも耐性を持つようになります。すべての処理時間はバッチ サーバーによって処理されるため、倉庫の作業者は、プット登録のためのサーバー パフォーマンスの予期しない低下が発生した場合に中断されることなく操作できます。</span><span class="sxs-lookup"><span data-stu-id="5e3de-113">The system will also become resilient to random peak times of put processing—all processing time will be handled by batch servers, allowing warehouse workers to operate without disruption when there is unexpected slow server performance for registration of puts.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5e3de-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5e3de-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5e3de-115">これは、倉庫作業者の生産性向上に重点を置いたパフォーマンス関連の機能です。</span><span class="sxs-lookup"><span data-stu-id="5e3de-115">This is a performance-related feature focused on increasing the productivity of warehouse workers.</span></span> <span data-ttu-id="5e3de-116">モバイル デバイスが "フリーズ" する原因になる、プット完了のたびのさまざまなインベントリ更新のオンライン処理を行う必要がなく、そのプロセスを非同期的に実行できます。</span><span class="sxs-lookup"><span data-stu-id="5e3de-116">Instead of requiring online processing of the various inventory updates each time a put is complete, which “freezes” the mobile device, we will allow for that process to be performed asynchronously.</span></span> <span data-ttu-id="5e3de-117">倉庫作業者は、一定数の更新を必要とするすべての作業のパフォーマンスが向上します。たとえば、10 明細行を選択するプット登録には、関連する場所の 20 の在庫更新と 10 の元伝票明細行の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="5e3de-117">Warehouse workers will experience an increase of performance for all operations requiring a certain number of updates—for example, a put registration of a pick of 10 lines involves 20 inventory updates for the locations involved and 10 source document lines updates.</span></span> <span data-ttu-id="5e3de-118">これらの操作はバッチによって自動化され、システムの負荷はよりバランスがとれたものになります。</span><span class="sxs-lookup"><span data-stu-id="5e3de-118">These operations will be automated through batches, and the load of the system will be more balanced.</span></span> <span data-ttu-id="5e3de-119">倉庫作業者はシステムの散発的またはランダムなピーク使用率に依存しなくなります。</span><span class="sxs-lookup"><span data-stu-id="5e3de-119">Warehouse workers will not be dependent on sporadic or random peak utilization of the system.</span></span> <span data-ttu-id="5e3de-120">この機能は、一部の顧客でテストできるように提供されます。出荷ドキュメントのマニフェストと印刷などのさまざまなフォローアップ プロセスへの影響を理解したいと思います。</span><span class="sxs-lookup"><span data-stu-id="5e3de-120">The feature will be flighted so that we can test the feature with some customers—we want to understand the impact on various follow-up processes such as the manifesting and printing of shipping documents.</span></span>
<!--feature detail end -->

<span data-ttu-id="5e3de-121">![作業処理ポリシー](media/work-processing-policies.png "作業処理ポリシー")</span><span class="sxs-lookup"><span data-stu-id="5e3de-121">![Work processing policies](media/work-processing-policies.png "Work processing policies")</span></span>
<!-- Picture 1 -->










