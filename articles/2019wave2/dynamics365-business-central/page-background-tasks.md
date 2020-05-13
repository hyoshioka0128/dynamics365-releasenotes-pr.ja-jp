---
title: ページ バックグラウンド タスク
description: ページ バックグラウンド タスク - AL 開発者は、ページ内に子セッションを作成して、必要な読み取り専用の計算を実行できます。 計算が完了すると、親セッションに通知されます。
author: relnotes
ms.reviewer: jswymer
ms.date: 03/25/2020
ms.assetid: b0644392-306c-e911-a964-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: a5f0fa44d17b1b88c11cad369e51bb507fdebf77
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178991"
---
# <a name="page-background-tasks"></a><span data-ttu-id="57b12-104">ページ バックグラウンド タスク</span><span class="sxs-lookup"><span data-stu-id="57b12-104">Page background tasks</span></span>


| <span data-ttu-id="57b12-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="57b12-105">Enabled for</span></span>    |  <span data-ttu-id="57b12-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="57b12-106">Public preview</span></span> | <span data-ttu-id="57b12-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="57b12-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="57b12-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="57b12-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="57b12-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="57b12-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="57b12-110">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="57b12-110">Aug 1, 2019</span></span>| <span data-ttu-id="57b12-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="57b12-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="57b12-112">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="57b12-112">Oct 1, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="57b12-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="57b12-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="57b12-114">ページ バックグラウンド タスクでは、ページ セッションの読み取り専用の子セッションで codeunit を (UI なしで) 実行できます。</span><span class="sxs-lookup"><span data-stu-id="57b12-114">A page background task can run a codeunit (without a UI) in a read-only child session of the page session.</span></span> <span data-ttu-id="57b12-115">タスクが完了すると、その結果を伴う完了トリガーがページ セッションで呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="57b12-115">On completion of the task, a completion trigger with the result is invoked on the page session.</span></span>

<span data-ttu-id="57b12-116">タスクが完了する前、またはページ レコード ID が変更される前にページが閉じられると、タスクはキャンセルされます。</span><span class="sxs-lookup"><span data-stu-id="57b12-116">If the page is closed before the task completes or the page record ID changed, the task is canceled.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="57b12-117">関連項目</span><span class="sxs-lookup"><span data-stu-id="57b12-117">See also</span></span>

<span data-ttu-id="57b12-118">[ページ バックグラウンド タスク](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-page-background-tasks) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="57b12-118">[Page Background Tasks](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-page-background-tasks) (docs)</span></span>
