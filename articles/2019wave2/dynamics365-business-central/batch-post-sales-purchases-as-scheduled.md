---
title: 販売と購入をスケジュールに従って一括転記する
description: バッチ転記は常にバックグラウンドで実行されるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 11/15/2019
ms.assetid: 2aad2c2f-ccde-e911-a812-000d3a4f15f1
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 3f305b1db557f98d9e173be7b87745298bbd10d8
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892264"
---
# <a name="batch-post-sales-and-purchases-as-scheduled"></a><span data-ttu-id="966a7-103">販売と購入をスケジュールに従って一括転記する</span><span class="sxs-lookup"><span data-stu-id="966a7-103">Batch-post sales and purchases as scheduled</span></span>


| <span data-ttu-id="966a7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="966a7-104">Enabled for</span></span>    |  <span data-ttu-id="966a7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="966a7-105">Public preview</span></span> | <span data-ttu-id="966a7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="966a7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="966a7-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="966a7-107">End users, automatically</span></span>|<span data-ttu-id="966a7-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="966a7-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="966a7-109">2019 年 9 月 1 日</span><span class="sxs-lookup"><span data-stu-id="966a7-109">Sep 1, 2019</span></span>| <span data-ttu-id="966a7-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="966a7-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="966a7-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="966a7-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="966a7-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="966a7-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="966a7-113">一度に大量のドキュメントを転記すると、処理に時間がかかり、従業員の生産時間が減る可能性があります。</span><span class="sxs-lookup"><span data-stu-id="966a7-113">Posting a large number of documents at once can take a while, reducing productive time for your employees.</span></span> <span data-ttu-id="966a7-114">このようなプロセスは通常、オフピーク時間にスケジュールするか、バックグラウンド アクティビティとして処理できます。これにより、ドキュメントを 1 つずつ処理する必要がなくなり、ユーザーは処理の完了を待つだけで済むようになります。</span><span class="sxs-lookup"><span data-stu-id="966a7-114">Such processes usually can be scheduled for off-peak hours or simply processed as background activities, eliminating the need to process documents one by one and making users wait for processing to be completed.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="966a7-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="966a7-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="966a7-116">長時間のプロセス実行によって業務に支障が出ないよう、バッチ転記がすべてバックグラウンド化されました。</span><span class="sxs-lookup"><span data-stu-id="966a7-116">You can now execute batch posting only in the background to avoid having long-running processes interfere with your work.</span></span> <span data-ttu-id="966a7-117">ドキュメントのバッチ転記中に発生する可能性がある問題については、**エラー メッセージ レジスタ** ページで確認できます。</span><span class="sxs-lookup"><span data-stu-id="966a7-117">Potential issues that occur during batch posting of documents can be found on the **Error Message Register** page.</span></span> <span data-ttu-id="966a7-118">バッチ転記の結果 (プリントアウトなど) は、ロール センターの **レポート受信トレイ** で確認できます。</span><span class="sxs-lookup"><span data-stu-id="966a7-118">You can find the results of batch posting (for example: printouts) in the **Report Inbox** on your Role Center.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="966a7-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="966a7-119">See also</span></span>

<span data-ttu-id="966a7-120">[複数のドキュメントを同時に転記する](https://docs.microsoft.com/dynamics365/business-central/ui-batch-posting) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="966a7-120">[Post Multiple Documents at the Same Time](https://docs.microsoft.com/dynamics365/business-central/ui-batch-posting) (docs)</span></span>
