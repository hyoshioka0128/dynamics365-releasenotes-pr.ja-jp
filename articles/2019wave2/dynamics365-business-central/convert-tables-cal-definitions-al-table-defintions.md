---
title: C/AL 定義から AL テーブル定義にテーブルを変換する
description: Sync-NAVApp PowerShell コマンドレットを使用することで、パートナーは、データベースのオーバーヘッドを最小限に抑えながら、アップグレード コードを記述する必要なく、C/AL で定義されたデータベース内のすべてのテーブルを AL で定義されたテーブルに変換できます。
author: relnotes
ms.reviewer: edupont
ms.date: 11/15/2019
ms.assetid: 0d941009-b786-e911-a960-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: ee6f230a84a63ddce8d1e7a3521398704ded3753
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892231"
---
# <a name="convert-tables-from-cal-definitions-to-al-table-definitions"></a><span data-ttu-id="41f62-103">C/AL 定義から AL テーブル定義にテーブルを変換する</span><span class="sxs-lookup"><span data-stu-id="41f62-103">Convert tables from C/AL definitions to AL table definitions</span></span>


| <span data-ttu-id="41f62-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="41f62-104">Enabled for</span></span>    |  <span data-ttu-id="41f62-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="41f62-105">Public preview</span></span> | <span data-ttu-id="41f62-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="41f62-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="41f62-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="41f62-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="41f62-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="41f62-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="41f62-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="41f62-109">Aug 1, 2019</span></span>| <span data-ttu-id="41f62-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="41f62-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="41f62-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="41f62-111">Oct 1, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="41f62-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="41f62-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="41f62-113">Windows PowerShell のコマンドレット Sync-NAVApp が更新され、データベースのオーバーヘッドを最小限に抑えながら、アップグレード コードを記述する必要なく、すべての C/AL テーブルを AL テーブルに変換できます。</span><span class="sxs-lookup"><span data-stu-id="41f62-113">The Windows PowerShell cmdlet Sync-NAVApp is updated so that you can convert all C/AL tables to AL tables with a minimal database overhead and without the need to write any upgrade code.</span></span> <span data-ttu-id="41f62-114">コマンド `Sync-NAVApp -Mode Sync` を使用すると、テナント データベースのテーブルの名前が、AL テーブルの命名規則に準拠するように変更されます。</span><span class="sxs-lookup"><span data-stu-id="41f62-114">The command `Sync-NAVApp -Mode Sync` renames tables on the tenant database to conform with the naming convention for AL tables.</span></span> <span data-ttu-id="41f62-115">これは、テナントの技術的なアップグレードに対応し、以前のバージョンの基本アプリケーションのテーブル構造が AL アプリ用のテーブル構造に変換されます。</span><span class="sxs-lookup"><span data-stu-id="41f62-115">This corresponds to a technical upgrade of the tenant, converting the table structure from the base application in earlier versions to the table structure for AL apps.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="41f62-116">関連項目</span><span class="sxs-lookup"><span data-stu-id="41f62-116">See also</span></span>

<span data-ttu-id="41f62-117">[Sync-NAVApp](https://docs.microsoft.com/powershell/module/microsoft.dynamics.nav.apps.management/sync-navapp?view=businesscentral-ps-15) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="41f62-117">[Sync-NAVApp](https://docs.microsoft.com/powershell/module/microsoft.dynamics.nav.apps.management/sync-navapp?view=businesscentral-ps-15) (docs)</span></span>
