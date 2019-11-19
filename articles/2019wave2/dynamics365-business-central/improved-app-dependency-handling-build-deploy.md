---
title: ビルドと展開でのアプリの依存関係の処理の改善
description: 依存関係を含む拡張機能のコンパイルと展開では、依存関係グラフが自動的に走査されて、これらが正しい順序で行われることが確認されるので、手動で処理する必要はありません。
author: relnotes
ms.reviewer: solsen
ms.date: 10/04/2019
ms.assetid: 7e1c615d-886d-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 25974668e0c1995b73ea5e596a44398435b9232d
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2667325"
---
# <a name="improved-app-dependency-handling-on-build-and-deploy"></a><span data-ttu-id="f32ab-103">ビルドと展開でのアプリの依存関係の処理の改善</span><span class="sxs-lookup"><span data-stu-id="f32ab-103">Improved app dependency handling on build and deploy</span></span>


| <span data-ttu-id="f32ab-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f32ab-104">Enabled for</span></span>    |  <span data-ttu-id="f32ab-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f32ab-105">Public preview</span></span> | <span data-ttu-id="f32ab-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f32ab-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f32ab-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="f32ab-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="f32ab-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="f32ab-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="f32ab-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="f32ab-109">Aug 1, 2019</span></span>| <span data-ttu-id="f32ab-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="f32ab-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="f32ab-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="f32ab-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="f32ab-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f32ab-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f32ab-113">正しい順序で拡張機能を手作業でコンパイルして展開するという煩雑さを回避します。</span><span class="sxs-lookup"><span data-stu-id="f32ab-113">Avoid tedious and manual work on compiling and deploying extensions in the correct order.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f32ab-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f32ab-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f32ab-115">これまでは、依存関係のあるプロジェクトが正しい順序でビルドされることを手動で確認する必要があり、依存関係のある拡張機能を展開するには依存する拡張機能を手動でアンインストールして再インストールする必要がありました。</span><span class="sxs-lookup"><span data-stu-id="f32ab-115">Until now, you have had to manually ensure that projects with dependencies are built in the correct order, and deploying extensions with dependencies required manually uninstalling and reinstalling dependent extensions.</span></span> <span data-ttu-id="f32ab-116">2019 年リリース ウェーブ 2 では、これはツールによる依存関係グラフの走査によって管理されるようになります。</span><span class="sxs-lookup"><span data-stu-id="f32ab-116">With the 2019 release wave 2, this is managed by the tools, by traversing the dependency graph.</span></span>
<!--feature detail end -->









