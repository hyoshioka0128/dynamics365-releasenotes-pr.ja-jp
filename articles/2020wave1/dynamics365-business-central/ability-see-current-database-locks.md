---
title: 現在のデータベースのロックを確認する機能
description: 管理者が環境内の現在のデータベースのロックを確認できます。
author: relnotes
ms.reviewer: jswymer
ms.date: 04/15/2020
ms.assetid: 2b28feef-ac58-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 6210a737a7663d9ed2cbd10dc516faa685454325
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273667"
---
# <a name="ability-to-see-current-database-locks"></a><span data-ttu-id="3c087-103">現在のデータベースのロックを確認する機能</span><span class="sxs-lookup"><span data-stu-id="3c087-103">Ability to see current database locks</span></span>


| <span data-ttu-id="3c087-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3c087-104">Enabled for</span></span>    |  <span data-ttu-id="3c087-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3c087-105">Public preview</span></span> | <span data-ttu-id="3c087-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="3c087-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3c087-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="3c087-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="3c087-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3c087-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3c087-109">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="3c087-109">Apr 1, 2020</span></span>| <span data-ttu-id="3c087-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3c087-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3c087-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="3c087-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3c087-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3c087-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3c087-113">ロックの問題を特定するには、管理者がシステムの現在のデータベースのロックを確認することが重要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="3c087-113">To locate a locking issue, it is sometimes important for an administrator to see the current database locks in the system.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3c087-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3c087-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3c087-115">クライアントで**データベースのロック**という新しいページが利用できます。</span><span class="sxs-lookup"><span data-stu-id="3c087-115">A new page called **Database Locks** is available in the client.</span></span> 

<span data-ttu-id="3c087-116">このページには、すべてのデータベースのロックのスナップショットが表示されます。</span><span class="sxs-lookup"><span data-stu-id="3c087-116">The page shows a snapshot of all database locks.</span></span> <span data-ttu-id="3c087-117">詳細がわかる場合は、データベースのロックを引き起こしている AL セッションの詳細が表示されます。</span><span class="sxs-lookup"><span data-stu-id="3c087-117">Where possible, it displays details on the AL session that is causing the database lock.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="3c087-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="3c087-118">See also</span></span>

<!--docs start-->
<span data-ttu-id="3c087-119">[SQL Database のロックの監視](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/monitor-database-locks) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="3c087-119">[Monitoring SQL Database Locks](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/monitor-database-locks) (docs)</span></span>
<!--docs end-->
