---
title: 読み取りスケールアウト
description: Business Central Server では、Azure SQL Database や SQL Server (使用可能な場合) で読み取り専用のレプリカを使用できます。
author: relnotes
ms.reviewer: jswymer
ms.date: 04/15/2020
ms.assetid: eda564e4-e71b-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 9d53467c70e28a642a6c381f29e7a426357837b8
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273711"
---
# <a name="read-scale-out"></a><span data-ttu-id="b6618-103">読み取りスケールアウト</span><span class="sxs-lookup"><span data-stu-id="b6618-103">Read scale-out</span></span>


| <span data-ttu-id="b6618-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b6618-104">Enabled for</span></span>    |  <span data-ttu-id="b6618-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b6618-105">Public preview</span></span> | <span data-ttu-id="b6618-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b6618-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b6618-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="b6618-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="b6618-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b6618-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b6618-109">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b6618-109">Apr 1, 2020</span></span>| <span data-ttu-id="b6618-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b6618-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b6618-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b6618-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="b6618-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b6618-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b6618-113">顧客は、データベースの読み取り専用レプリカで選択したレポート、クエリ、Web サービスの呼び出しを実行することを選択できます。</span><span class="sxs-lookup"><span data-stu-id="b6618-113">Customers can choose to run selected reports, queries, and web service calls on a read-only replica of the database.</span></span> <span data-ttu-id="b6618-114">これにより、分析ワークロードがプライマリ データベースに影響を与えることはありません。</span><span class="sxs-lookup"><span data-stu-id="b6618-114">This way, analytical workloads will not have any impact on the primary database.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b6618-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b6618-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b6618-116">Business Central のアーティファクト (レポート、API ページ、クエリ) で、データベースの読み取り専用レプリカにアクセスできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="b6618-116">Business Central artifacts (Reports, API Pages, and Queries) now can get access to a read-only replica of the database.</span></span> 

<span data-ttu-id="b6618-117">ページ、レポート、クエリの各オブジェクトには、ReadOnly または ReadWrite の値を取ることができる "DataAccessIntent" という新しいプロパティがあります。</span><span class="sxs-lookup"><span data-stu-id="b6618-117">The Page, Report, and Query objects have a new property called “DataAccessIntent” that can take values ReadOnly or ReadWrite.</span></span> <span data-ttu-id="b6618-118">このプロパティは、可能であればセカンダリ レプリカに接続するサーバーのヒントとして機能します。</span><span class="sxs-lookup"><span data-stu-id="b6618-118">This property works as a hint for the server, which will connect to the secondary replica if possible.</span></span> <span data-ttu-id="b6618-119">レプリカに対してワークロードが実行されると、挿入/削除/変更操作を実行できないため、ReadOnly オブジェクトに新しい検証が導入されます。</span><span class="sxs-lookup"><span data-stu-id="b6618-119">When a workload is executed against the replica, insert/delete/modify operations are not possible, so a new validation is introduced for ReadOnly objects.</span></span> <span data-ttu-id="b6618-120">これらの操作はいずれも実行時に例外をスローします (将来、新しいコンパイル時検証が追加される予定です)。</span><span class="sxs-lookup"><span data-stu-id="b6618-120">Any of these operations will throw an exception at runtime (new compile-time validation will be added in the future).</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="b6618-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="b6618-121">See also</span></span>

<!--docs start-->
<span data-ttu-id="b6618-122">[パフォーマンス向上のための読み取りスケールアウトの使用](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/database-read-scale-out-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b6618-122">[Using Read Scale-Out for Better Performance](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/database-read-scale-out-overview) (docs)</span></span>
<!--docs end-->
