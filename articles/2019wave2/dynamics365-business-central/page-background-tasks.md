---
title: ページ バックグラウンド タスク
description: ページ バックグラウンド タスク - AL 開発者は、ページ内に子セッションを作成して、必要な読み取り専用の計算を実行できます。 計算が完了すると、親セッションに通知されます。
author: relnotes
ms.reviewer: jswymer
ms.date: 07/22/2019
ms.assetid: b0644392-306c-e911-a964-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 998f2db19041371c21ecad786a95ded2c741f316
ms.sourcegitcommit: f28876e2cf349523ecec57dd71f4cb6db56e6695
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1795375"
---
# <a name="page-background-tasks"></a><span data-ttu-id="b996d-104">ページ バックグラウンド タスク</span><span class="sxs-lookup"><span data-stu-id="b996d-104">Page background tasks</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="b996d-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="b996d-105">Enabled for</span></span>    |  <span data-ttu-id="b996d-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b996d-106">Public preview</span></span> | <span data-ttu-id="b996d-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="b996d-107">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="b996d-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="b996d-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="b996d-109">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="b996d-109">August 2019</span></span>| <span data-ttu-id="b996d-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="b996d-110">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="b996d-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b996d-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b996d-112">ページ バックグラウンド タスクでは、ページ セッションの読み取り専用の子セッションで codeunit を (UI なしで) 実行できます。</span><span class="sxs-lookup"><span data-stu-id="b996d-112">A page background task can run a codeunit (without an UI) in a read-only child session of the page session.</span></span> <span data-ttu-id="b996d-113">タスクが完了すると、その結果を伴う完了トリガーがページ セッションで呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="b996d-113">On completion of the task, a completion trigger with the result is invoked on the page session.</span></span>

<span data-ttu-id="b996d-114">タスクが完了する前、またはページ レコード ID が変更される前にページが閉じられると、タスクはキャンセルされます。</span><span class="sxs-lookup"><span data-stu-id="b996d-114">If the page is closed before the task completes or the page record ID changed, the task is cancelled.</span></span>
<!--feature detail end -->











