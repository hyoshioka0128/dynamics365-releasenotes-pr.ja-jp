---
title: グリッドの小計でグループ化
description: 1 つ以上の列に基づいてデータをグループ化し、組織化された方法でデータを表示して、Web クライアントで簡単なアドホック データ分析を実行します。
author: relnotes
ms.reviewer: sericks
ms.date: 01/13/2020
ms.assetid: bc751b0a-83ca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: 36e10267e838b88a93b69275444b307cb6773f53
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986585"
---
# <a name="grouping-with-subtotals-in-grids"></a><span data-ttu-id="7d404-103">グリッドの小計でグループ化</span><span class="sxs-lookup"><span data-stu-id="7d404-103">Grouping with subtotals in grids</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="7d404-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7d404-104">Enabled for</span></span>    |  <span data-ttu-id="7d404-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7d404-105">Public preview</span></span> | <span data-ttu-id="7d404-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7d404-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7d404-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="7d404-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="7d404-108">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="7d404-108">Apr 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="7d404-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7d404-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7d404-110">ユーザーは、しばしばデータのアドホック分析を実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7d404-110">Users often need to perform ad-hoc analysis of data.</span></span> <span data-ttu-id="7d404-111">これは現在、データを Microsoft Excel にエクスポートしてからピボットテーブルを使用して行うことができます。</span><span class="sxs-lookup"><span data-stu-id="7d404-111">This can be done currently by exporting data to Microsoft Excel and then using pivot tables.</span></span> <span data-ttu-id="7d404-112">Web クライアント内でのデータのグループ化を有効にし、以前に追加されている**合計**機能を拡張してグループ レベルで小計ができるようにすることで、ユーザーはこれらの分析情報を Finance and Operations アプリから直接取得できます。</span><span class="sxs-lookup"><span data-stu-id="7d404-112">By enabling the grouping of data within the web client and extending the previously added **Totals** feature to provide subtotals at the group level, users will be able to get these insights directly from Finance and Operations apps.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7d404-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7d404-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7d404-114">この機能は、新しいグリッド コントロールでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="7d404-114">This feature is only available with the new grid control.</span></span> <span data-ttu-id="7d404-115">リリース ウェーブを通して拡張され、最終的に、ユーザーは最大 5 つの列の値に基づいてグリッド内のデータをグループ化できるようになります。</span><span class="sxs-lookup"><span data-stu-id="7d404-115">It will evolve over the release wave to eventually allow users to group data in a grid based on the values in up to five columns.</span></span> <span data-ttu-id="7d404-116">ユーザーは、必要に応じてグループを展開または折りたたむことができます。これはデータの要約ビューを作成するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="7d404-116">Users will be able to expand or collapse groups as desired, which can help create a summarized view of data.</span></span> <span data-ttu-id="7d404-117">小計もグループ ヘッダー レベルに表示されます。</span><span class="sxs-lookup"><span data-stu-id="7d404-117">Subtotals will also be shown at the group header level.</span></span> 

<span data-ttu-id="7d404-118">**10.0.9/Platform update 33**</span><span class="sxs-lookup"><span data-stu-id="7d404-118">**10.0.9 / Platform update 33**</span></span>

<span data-ttu-id="7d404-119">単一の列に基づいてデータをグループ化します。</span><span class="sxs-lookup"><span data-stu-id="7d404-119">Group data based on a single column.</span></span> <span data-ttu-id="7d404-120">これは、保存されたビュー機能が有効になっているときは、個人用設定を使用して保存できます。</span><span class="sxs-lookup"><span data-stu-id="7d404-120">This can be saved via personalization when the saved views feature is enabled.</span></span> <span data-ttu-id="7d404-121">現時点では、グループの展開または折りたたみの機能はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="7d404-121">At this time, the ability to expand or collapse groups is not supported.</span></span>
<!--feature detail end -->









