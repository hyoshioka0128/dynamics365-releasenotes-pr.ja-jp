---
title: グリッドの小計でグループ化
description: 1 つ以上の列に基づいてデータをグループ化し、組織化された方法でデータを表示して、Finance and Operations Web クライアントで簡単なアドホック データ分析を実行します。
author: relnotes
ms.reviewer: sericks
ms.date: 04/07/2020
ms.assetid: bc751b0a-83ca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: bf607e2b4970f6e23886167433642ff1329c179d
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3256192"
---
# <a name="grouping-with-subtotals-in-grids"></a><span data-ttu-id="0aaa5-103">グリッドの小計でグループ化</span><span class="sxs-lookup"><span data-stu-id="0aaa5-103">Grouping with subtotals in grids</span></span>


| <span data-ttu-id="0aaa5-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0aaa5-104">Enabled for</span></span>    |  <span data-ttu-id="0aaa5-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0aaa5-105">Public preview</span></span> | <span data-ttu-id="0aaa5-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="0aaa5-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0aaa5-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="0aaa5-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="0aaa5-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0aaa5-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0aaa5-109">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="0aaa5-109">Apr 3, 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="0aaa5-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0aaa5-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0aaa5-111">ユーザーは、しばしばデータのアドホック分析を実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0aaa5-111">Users often need to perform ad-hoc analysis of data.</span></span> <span data-ttu-id="0aaa5-112">これは現在、データを Microsoft Excel にエクスポートしてからピボットテーブルを使用して行うことができます。</span><span class="sxs-lookup"><span data-stu-id="0aaa5-112">This can be done currently by exporting data to Microsoft Excel and then using pivot tables.</span></span> <span data-ttu-id="0aaa5-113">Web クライアント内でのデータのグループ化を有効にし、以前に追加されている**合計**機能を拡張してグループ レベルで小計ができるようにすることで、ユーザーはこれらの分析情報を Finance and Operations アプリから直接取得できます。</span><span class="sxs-lookup"><span data-stu-id="0aaa5-113">By enabling the grouping of data within the web client and extending the previously added **Totals** feature to provide subtotals at the group level, users will be able to get these insights directly from Finance and Operations apps.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0aaa5-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0aaa5-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0aaa5-115">この機能は、新しいグリッド コントロールでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="0aaa5-115">This feature is only available with the new grid control.</span></span> <span data-ttu-id="0aaa5-116">リリース ウェーブを通して拡張され、最終的に、ユーザーは最大 5 つの列の値に基づいてグリッド内のデータをグループ化できるようになります。</span><span class="sxs-lookup"><span data-stu-id="0aaa5-116">It will evolve over the release wave to eventually allow users to group data in a grid based on the values in up to five columns.</span></span> <span data-ttu-id="0aaa5-117">ユーザーは、必要に応じてグループを展開または折りたたむことができます。これはデータの要約ビューを作成するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="0aaa5-117">Users will be able to expand or collapse groups as desired, which can help create a summarized view of data.</span></span> <span data-ttu-id="0aaa5-118">小計もグループ ヘッダー レベルに表示されます。</span><span class="sxs-lookup"><span data-stu-id="0aaa5-118">Subtotals will also be shown at the group header level.</span></span> 

<span data-ttu-id="0aaa5-119">**10.0.9 / Platform update 33** 単一の列に基づいてデータをグループ化します。</span><span class="sxs-lookup"><span data-stu-id="0aaa5-119">**10.0.9 / Platform update 33** Group data based on a single column.</span></span> <span data-ttu-id="0aaa5-120">これは、保存されたビュー機能が有効になっているときは、個人用設定を使用して保存できます。</span><span class="sxs-lookup"><span data-stu-id="0aaa5-120">This can be saved via personalization when the saved views feature is enabled.</span></span> <span data-ttu-id="0aaa5-121">グループを展開または縮小する機能は、将来の更新で計画されています。</span><span class="sxs-lookup"><span data-stu-id="0aaa5-121">The ability to expand or collapse groups is planned for a future update.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="0aaa5-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="0aaa5-122">See also</span></span>

<!--docs start-->
<span data-ttu-id="0aaa5-123">[グリッド機能](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/grid-capabilities) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="0aaa5-123">[Grid capabilities](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/grid-capabilities) (docs)</span></span>
<!--docs end-->
