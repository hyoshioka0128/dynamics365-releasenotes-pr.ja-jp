---
title: 読み取りスケールアウト
description: Business Central Server では、Azure SQL Database や SQL Server (使用可能な場合) で読み取り専用のレプリカを使用できます。
author: relnotes
ms.reviewer: jswymer
ms.date: 01/10/2020
ms.assetid: eda564e4-e71b-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: fb8b6581a6fe73cb0f91628c803410d1d3f0eb00
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986653"
---
# <a name="read-scale-out"></a><span data-ttu-id="1ea96-103">読み取りスケールアウト</span><span class="sxs-lookup"><span data-stu-id="1ea96-103">Read scale-out</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="1ea96-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1ea96-104">Enabled for</span></span>    |  <span data-ttu-id="1ea96-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1ea96-105">Public preview</span></span> | <span data-ttu-id="1ea96-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="1ea96-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1ea96-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="1ea96-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="1ea96-108">2020 年 3 月</span><span class="sxs-lookup"><span data-stu-id="1ea96-108">Mar 2020</span></span>| <span data-ttu-id="1ea96-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="1ea96-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1ea96-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1ea96-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1ea96-111">顧客は、データベースの読み取り専用レプリカで選択したレポート、クエリ、Web サービスの呼び出しを実行することを選択できます。</span><span class="sxs-lookup"><span data-stu-id="1ea96-111">Customers can choose to run selected reports, queries, and web service calls on a read-only replica of the database.</span></span> <span data-ttu-id="1ea96-112">これにより、分析ワークロードがプライマリ データベースに影響を与えることはありません。</span><span class="sxs-lookup"><span data-stu-id="1ea96-112">This way, analytical workloads will not have any impact on the primary database.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1ea96-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1ea96-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1ea96-114">Business Central のアーティファクト (レポート、API ページ、クエリ) で、データベースの読み取り専用レプリカにアクセスできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="1ea96-114">Business Central artifacts (Reports, API Pages, and Queries) now can get access to a read-only replica of the database.</span></span> 

<span data-ttu-id="1ea96-115">ページ、レポート、クエリの各オブジェクトには、ReadOnly または ReadWrite の値を取ることができる "DataAccessIntent" という新しいプロパティがあります。</span><span class="sxs-lookup"><span data-stu-id="1ea96-115">The Page, Report and Query objects have a new property called “DataAccessIntent” that can take values ReadOnly or ReadWrite.</span></span> <span data-ttu-id="1ea96-116">このプロパティは、可能であればセカンダリ レプリカに接続するサーバーのヒントとして機能します。</span><span class="sxs-lookup"><span data-stu-id="1ea96-116">This property works as a hint for the server, which will connect to the secondary replica if possible.</span></span> <span data-ttu-id="1ea96-117">レプリカに対してワークロードが実行されると、挿入/削除/変更操作を実行できないため、ReadOnly オブジェクトに新しい検証が導入されます。</span><span class="sxs-lookup"><span data-stu-id="1ea96-117">When a workload is executed against the replica, insert/delete/modify operations are not possible, so a new validation is introduced for ReadOnly objects.</span></span> <span data-ttu-id="1ea96-118">これらの操作はいずれも実行時に例外をスローします (将来、新しいコンパイル時検証が追加される予定です)。</span><span class="sxs-lookup"><span data-stu-id="1ea96-118">Any of these operations will throw an exception at runtime (new compile-time validation will be added in the future).</span></span>
<!--feature detail end -->









