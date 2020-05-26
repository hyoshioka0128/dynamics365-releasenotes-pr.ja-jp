---
title: テーブルのサイズを確認する機能
description: 管理者は、環境内の各テーブルのレコード数とテーブルの合計サイズを確認できます。
author: relnotes
ms.reviewer: jswymer
ms.date: 04/21/2020
ms.assetid: 019b327a-ac58-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 4e50f113a5c6e0881da3308fb8fa314a6f49d579
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3293821"
---
# <a name="ability-to-see-table-sizes"></a><span data-ttu-id="42e98-103">テーブルのサイズを確認する機能</span><span class="sxs-lookup"><span data-stu-id="42e98-103">Ability to see table sizes</span></span>


| <span data-ttu-id="42e98-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="42e98-104">Enabled for</span></span>    |  <span data-ttu-id="42e98-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="42e98-105">Public preview</span></span> | <span data-ttu-id="42e98-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="42e98-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="42e98-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="42e98-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="42e98-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="42e98-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="42e98-109">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="42e98-109">Apr 1, 2020</span></span>| <span data-ttu-id="42e98-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="42e98-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="42e98-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="42e98-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="42e98-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="42e98-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="42e98-113">パフォーマンスの問題をトラブルシューティングする際には、テーブル間のデータ サイズの分布を確認する必要がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="42e98-113">When troubleshooting performance issues, sometimes it is necessary to see the distribution of data size across tables.</span></span> <span data-ttu-id="42e98-114">この機能により、管理者はこの情報を簡単に確認できます。</span><span class="sxs-lookup"><span data-stu-id="42e98-114">This feature makes it easy for an administrator to look up this information.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="42e98-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="42e98-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="42e98-116">**Table Information** と呼ばれる新しいページには、次の情報が表示されます。</span><span class="sxs-lookup"><span data-stu-id="42e98-116">A new page called **Table Information** shows the following:</span></span>

- <span data-ttu-id="42e98-117">会社名</span><span class="sxs-lookup"><span data-stu-id="42e98-117">Company Name</span></span>  
- <span data-ttu-id="42e98-118">テーブル名</span><span class="sxs-lookup"><span data-stu-id="42e98-118">Table Name</span></span>
- <span data-ttu-id="42e98-119">テーブル番号</span><span class="sxs-lookup"><span data-stu-id="42e98-119">Table No.</span></span> 
- <span data-ttu-id="42e98-120">レコードの</span><span class="sxs-lookup"><span data-stu-id="42e98-120">No.</span></span> <span data-ttu-id="42e98-121">数</span><span class="sxs-lookup"><span data-stu-id="42e98-121">of Records</span></span>    
- <span data-ttu-id="42e98-122">レコードのサイズ</span><span class="sxs-lookup"><span data-stu-id="42e98-122">Record Size</span></span>
- <span data-ttu-id="42e98-123">サイズ (KB)</span><span class="sxs-lookup"><span data-stu-id="42e98-123">Size (KB)</span></span>

<span data-ttu-id="42e98-124">ユーザーが SUPER アクセス許可を持つすべての会社の情報が表示されます。</span><span class="sxs-lookup"><span data-stu-id="42e98-124">Information is shown for all companies for which the user has SUPER permissions.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="42e98-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="42e98-125">See also</span></span>

<!--docs start-->
<span data-ttu-id="42e98-126">[テーブル情報の表示](https://docs.microsoft.com/dynamics365/business-central/admin-view-table-information) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="42e98-126">[Viewing Table Information](https://docs.microsoft.com/dynamics365/business-central/admin-view-table-information) (docs)</span></span>
<!--docs end-->
