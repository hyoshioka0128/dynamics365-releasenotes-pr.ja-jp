---
title: ビルドと展開でのアプリの依存関係の処理の改善
description: 依存関係を含む拡張機能のコンパイルと展開では、依存関係グラフが自動的に走査されて、これらが正しい順序で行われることが確認されるので、手動で処理する必要はありません。
author: relnotes
ms.reviewer: solsen
ms.date: 07/01/2019
ms.assetid: 7e1c615d-886d-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: pborring
dynamics365pdf: true
ms.openlocfilehash: 018d8671cefb5bcbfd95905dccfdbec2d4028d41
ms.sourcegitcommit: e5523d6228bfee2d93355b170028731509aed19a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/02/2019
ms.locfileid: "1722952"
---
# <a name="improved-app-dependency-handling-on-build-and-deploy"></a><span data-ttu-id="fa471-103">ビルドと展開でのアプリの依存関係の処理の改善</span><span class="sxs-lookup"><span data-stu-id="fa471-103">Improved app dependency handling on build and deploy</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="fa471-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="fa471-104">Enabled for</span></span>    |  <span data-ttu-id="fa471-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="fa471-105">Public preview</span></span> | <span data-ttu-id="fa471-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="fa471-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="fa471-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="fa471-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="fa471-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="fa471-108">August 2019</span></span>| <span data-ttu-id="fa471-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="fa471-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="fa471-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="fa471-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="fa471-111">正しい順序で拡張機能をコンパイルおよび展開する面倒な手作業を避けます。</span><span class="sxs-lookup"><span data-stu-id="fa471-111">Avoid tedious and manual work on compiling and deploying extensions in the correct order.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="fa471-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="fa471-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="fa471-113">これまでは、依存関係のあるプロジェクトが正しい順序でビルドされることを手動で確認する必要があり、依存関係のある拡張機能を展開するには依存する拡張機能を手動でアンインストールして再インストールする必要がありました。</span><span class="sxs-lookup"><span data-stu-id="fa471-113">Until now, you have been forced to manually ensure that projects with dependencies are built in the correct order, and deploying extensions with dependencies required manually uninstalling and reinstalling dependent extensions.</span></span> <span data-ttu-id="fa471-114">2019 年リリース ウェーブ 2 では、これはツールによる依存関係グラフの走査によって管理されるようになります。</span><span class="sxs-lookup"><span data-stu-id="fa471-114">With the 2019 release wave 2, this is managed by the tools, by traversing the dependency graph.</span></span>
<!--feature detail end -->










