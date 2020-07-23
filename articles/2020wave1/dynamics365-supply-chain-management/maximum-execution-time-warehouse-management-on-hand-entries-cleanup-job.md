---
title: 倉庫管理の手持在庫エントリのクリーンアップ ジョブの最大実行時間
description: 倉庫管理の手持在庫エントリのクリーンアップ ジョブの機能強化
author: relnotes
ms.reviewer: kamaybac
ms.date: 06/04/2020
ms.assetid: 22aeafda-e18a-ea11-a812-000d3a4e3654
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: 0a257fb70dd8a695c0d1632b9e31d8af81e229e9
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3440888"
---
# <a name="maximum-execution-time-for-the-warehouse-management-on-hand-entries-cleanup-job"></a><span data-ttu-id="aa90a-103">倉庫管理の手持在庫エントリのクリーンアップ ジョブの最大実行時間</span><span class="sxs-lookup"><span data-stu-id="aa90a-103">Maximum execution time for the warehouse management on-hand entries cleanup job</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="aa90a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="aa90a-104">Enabled for</span></span>    |  <span data-ttu-id="aa90a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="aa90a-105">Public preview</span></span> | <span data-ttu-id="aa90a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="aa90a-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="aa90a-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="aa90a-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="aa90a-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="aa90a-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="aa90a-109">2020 年 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="aa90a-109">May 29, 2020</span></span>| <span data-ttu-id="aa90a-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="aa90a-110">Jul 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="aa90a-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="aa90a-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="aa90a-112">この機能を使用すると、手持在庫エントリのクリーンアップ ジョブの処理に対して許可される最大時間を設定できます。</span><span class="sxs-lookup"><span data-stu-id="aa90a-112">This feature lets you establish the maximum time allowed for processing the on-hand entries cleanup job.</span></span> <span data-ttu-id="aa90a-113">指定した時間数以内にジョブが完了しない場合は、それまでに完了した作業を保存して終了します。</span><span class="sxs-lookup"><span data-stu-id="aa90a-113">If the job doesn't complete before the specified number of hours, it will save the work completed so far and then exit.</span></span> <span data-ttu-id="aa90a-114">この機能は、在庫の使用率が高い実装に特に関連しています。</span><span class="sxs-lookup"><span data-stu-id="aa90a-114">This capability is especially relevant for implementations that have high inventory usage.</span></span> <span data-ttu-id="aa90a-115">この場合、システムの負荷ができるだけ低いときにジョブが実行されるようにスケジュールする必要があります。</span><span class="sxs-lookup"><span data-stu-id="aa90a-115">In this case you should schedule the job to run at times when the system is as lightly loaded as possible.</span></span> <span data-ttu-id="aa90a-116">バッチ ジョブが完了するまで実行を継続できるようにするには、値「0」を入力するか、空白のままにします。</span><span class="sxs-lookup"><span data-stu-id="aa90a-116">Enter a value of "0" (or leave blank) to allow the batch job to continue running until it has finished.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="aa90a-117">関連項目</span><span class="sxs-lookup"><span data-stu-id="aa90a-117">See also</span></span>

<!--docs start-->
<span data-ttu-id="aa90a-118">[倉庫管理の手持在庫エントリのクリーンアップ ジョブ](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/onhand-cleanup) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="aa90a-118">[Warehouse management on-hand entries cleanup job](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/onhand-cleanup) (docs)</span></span>
<!--docs end-->
