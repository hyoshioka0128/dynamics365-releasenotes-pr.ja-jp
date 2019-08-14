---
title: C/AL 定義から AL テーブル定義にテーブルを変換する
description: Sync-NAVApp PowerShell コマンドレットを使用することで、パートナーは、データベースのオーバーヘッドを最小限に抑えながら、アップグレード コードを記述する必要なく、C/AL で定義されたデータベース内のすべてのテーブルを AL で定義されたテーブルに変換できます。
author: relnotes
ms.reviewer: edupont
ms.date: 07/22/2019
ms.assetid: 0d941009-b786-e911-a960-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 8882c18272d09b1e29c90b45165cf6fff1e92879
ms.sourcegitcommit: f28876e2cf349523ecec57dd71f4cb6db56e6695
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1795815"
---
# <a name="convert-tables-from-cal-definitions-to-al-table-definitions"></a><span data-ttu-id="e940c-103">C/AL 定義から AL テーブル定義にテーブルを変換する</span><span class="sxs-lookup"><span data-stu-id="e940c-103">Convert tables from C/AL definitions to AL table definitions</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="e940c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="e940c-104">Enabled for</span></span>    |  <span data-ttu-id="e940c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e940c-105">Public preview</span></span> | <span data-ttu-id="e940c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="e940c-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="e940c-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="e940c-107">Admins, makers, or analysts, automatically</span></span>|| <span data-ttu-id="e940c-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="e940c-108">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="e940c-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e940c-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e940c-110">Windows PowerShell のコマンドレット Sync-NAVApp が更新され、データベースのオーバーヘッドを最小限に抑えながら、アップグレード コードを記述する必要なく、すべての C/AL テーブルを AL テーブルに変換できます。</span><span class="sxs-lookup"><span data-stu-id="e940c-110">The Windows PowerShell cmdlet Sync-NAVApp is updated so that you can convert all C/AL tables to AL tables with a minimal database overhead and without the need to write any upgrade code.</span></span> <span data-ttu-id="e940c-111">コマンド `Sync-NAVApp -Mode BaseAppUpgrade` を使用すると、テナント データベースのテーブルの名前が、AL テーブルの命名規則に準拠するように変更されます。</span><span class="sxs-lookup"><span data-stu-id="e940c-111">The command `Sync-NAVApp -Mode BaseAppUpgrade` renames tables on the tenant database to conform with the naming convention for AL tables.</span></span> <span data-ttu-id="e940c-112">これは、テナントの技術的なアップグレードに対応し、以前のバージョンの基本アプリケーションのテーブル構造が AL アプリ用のテーブル構造に変換されます。</span><span class="sxs-lookup"><span data-stu-id="e940c-112">This corresponds to a technical upgrade of the tenant, converting the table structure from the base application in earlier versions to the table structure for AL apps.</span></span>
<!--feature detail end -->











