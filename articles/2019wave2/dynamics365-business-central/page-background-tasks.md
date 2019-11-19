---
title: ページ バックグラウンド タスク
description: ページ バックグラウンド タスク - AL 開発者は、ページ内に子セッションを作成して、必要な読み取り専用の計算を実行できます。 計算が完了すると、親セッションに通知されます。
author: relnotes
ms.reviewer: jswymer
ms.date: 10/01/2019
ms.assetid: b0644392-306c-e911-a964-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 3c8f68cfde1029d504b5f0e4510a979c2cc5a2ac
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2666885"
---
# <a name="page-background-tasks"></a><span data-ttu-id="14aca-104">ページ バックグラウンド タスク</span><span class="sxs-lookup"><span data-stu-id="14aca-104">Page background tasks</span></span>


| <span data-ttu-id="14aca-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="14aca-105">Enabled for</span></span>    |  <span data-ttu-id="14aca-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="14aca-106">Public preview</span></span> | <span data-ttu-id="14aca-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="14aca-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="14aca-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="14aca-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="14aca-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="14aca-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="14aca-110">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="14aca-110">Aug 1, 2019</span></span>| <span data-ttu-id="14aca-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="14aca-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="14aca-112">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="14aca-112">Oct 1, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="14aca-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="14aca-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="14aca-114">ページ バックグラウンド タスクでは、ページ セッションの読み取り専用の子セッションで codeunit を (UI なしで) 実行できます。</span><span class="sxs-lookup"><span data-stu-id="14aca-114">A page background task can run a codeunit (without a UI) in a read-only child session of the page session.</span></span> <span data-ttu-id="14aca-115">タスクが完了すると、その結果を伴う完了トリガーがページ セッションで呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="14aca-115">On completion of the task, a completion trigger with the result is invoked on the page session.</span></span>

<span data-ttu-id="14aca-116">タスクが完了する前、またはページ レコード ID が変更される前にページが閉じられると、タスクはキャンセルされます。</span><span class="sxs-lookup"><span data-stu-id="14aca-116">If the page is closed before the task completes or the page record ID changed, the task is canceled.</span></span>
<!--feature detail end -->









