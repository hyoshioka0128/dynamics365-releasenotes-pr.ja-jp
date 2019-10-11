---
title: ページ バックグラウンド タスク
description: ページ バックグラウンド タスク - AL 開発者は、ページ内に子セッションを作成して、必要な読み取り専用の計算を実行できます。 計算が完了すると、親セッションに通知されます。
author: relnotes
ms.reviewer: jswymer
ms.date: 08/13/2019
ms.assetid: b0644392-306c-e911-a964-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: cd748e369f7b819863e2a2004fa47400d446bb41
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140449"
---
# <a name="page-background-tasks"></a><span data-ttu-id="53918-104">ページ バックグラウンド タスク</span><span class="sxs-lookup"><span data-stu-id="53918-104">Page background tasks</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="53918-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="53918-105">Enabled for</span></span>    |  <span data-ttu-id="53918-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="53918-106">Public preview</span></span> | <span data-ttu-id="53918-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="53918-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="53918-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="53918-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="53918-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="53918-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="53918-110">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="53918-110">Aug 1, 2019</span></span>| <span data-ttu-id="53918-111">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="53918-111">Oct 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="53918-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="53918-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="53918-113">ページ バックグラウンド タスクでは、ページ セッションの読み取り専用の子セッションで codeunit を (UI なしで) 実行できます。</span><span class="sxs-lookup"><span data-stu-id="53918-113">A page background task can run a codeunit (without a UI) in a read-only child session of the page session.</span></span> <span data-ttu-id="53918-114">タスクが完了すると、その結果を伴う完了トリガーがページ セッションで呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="53918-114">On completion of the task, a completion trigger with the result is invoked on the page session.</span></span>

<span data-ttu-id="53918-115">タスクが完了する前、またはページ レコード ID が変更される前にページが閉じられると、タスクはキャンセルされます。</span><span class="sxs-lookup"><span data-stu-id="53918-115">If the page is closed before the task completes or the page record ID changed, the task is canceled.</span></span>
<!--feature detail end -->











