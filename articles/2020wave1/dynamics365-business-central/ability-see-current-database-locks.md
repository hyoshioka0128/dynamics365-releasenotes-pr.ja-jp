---
title: 現在のデータベースのロックを確認する機能
description: 管理者が環境内の現在のデータベースのロックを確認できます。
author: relnotes
ms.reviewer: jswymer
ms.date: 03/25/2020
ms.assetid: 2b28feef-ac58-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 160aa20571f76f53f1a1b78210126a881b343944
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3233058"
---
# <a name="ability-to-see-current-database-locks"></a><span data-ttu-id="e2daf-103">現在のデータベースのロックを確認する機能</span><span class="sxs-lookup"><span data-stu-id="e2daf-103">Ability to see current database locks</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="e2daf-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="e2daf-104">Enabled for</span></span>    |  <span data-ttu-id="e2daf-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e2daf-105">Public preview</span></span> | <span data-ttu-id="e2daf-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="e2daf-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="e2daf-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="e2daf-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="e2daf-108">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="e2daf-108">Apr 2020</span></span>| <span data-ttu-id="e2daf-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="e2daf-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="e2daf-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e2daf-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e2daf-111">ロックの問題を特定するには、管理者がシステムの現在のデータベースのロックを確認することが重要になる場合があります。</span><span class="sxs-lookup"><span data-stu-id="e2daf-111">To locate a locking issue, it is sometimes important for an administrator to see the current database locks in the system.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e2daf-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e2daf-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e2daf-113">クライアントで**データベースのロック**という新しいページが利用できます。</span><span class="sxs-lookup"><span data-stu-id="e2daf-113">A new page called **Database Locks** is available in the client.</span></span> 

<span data-ttu-id="e2daf-114">このページには、すべてのデータベースのロックのスナップショットが表示されます。</span><span class="sxs-lookup"><span data-stu-id="e2daf-114">The page shows a snapshot of all database locks.</span></span> <span data-ttu-id="e2daf-115">詳細がわかる場合は、データベースのロックを引き起こしている AL セッションの詳細が表示されます。</span><span class="sxs-lookup"><span data-stu-id="e2daf-115">Where possible, it displays details on the AL session that is causing the database lock.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="e2daf-116">関連項目</span><span class="sxs-lookup"><span data-stu-id="e2daf-116">See also</span></span>


<!--docs start-->
<span data-ttu-id="e2daf-117">[SQL Database のロックの監視](https://review.docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/monitor-database-locks) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="e2daf-117">[Monitoring SQL Database Locks](https://review.docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/monitor-database-locks) (docs)</span></span>
<!--docs end-->

