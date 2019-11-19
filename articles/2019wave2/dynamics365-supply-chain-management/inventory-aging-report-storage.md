---
title: 在庫エイジング レポート ストレージ
description: 在庫エイジング レポート ストレージを使用すると、在庫エイジング レポートを実行し、出力を Dynamics 365 Supply Chain Management のフォームのシンプルなリストとしてアクセスできるようにするか、結果をグラフで視覚化できます。 また、外部アプリケーションで使用するために、データ エンティティを介して在庫エイジング レポートからの出力をエクスポートすることもできます。
author: relnotes
ms.reviewer: josaw
ms.date: 10/09/2019
ms.assetid: a816499f-67e0-e911-a814-000d3a4f1244
ms.topic: article
ms.service: business-applications
ms.author: aevengir
dynamics365pdf: true
ms.openlocfilehash: 569126273bf62af7f9fba56d946ac141430bfc0f
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660608"
---
# <a name="inventory-aging-report-storage"></a><span data-ttu-id="25abe-104">在庫エイジング レポート ストレージ</span><span class="sxs-lookup"><span data-stu-id="25abe-104">Inventory aging report storage</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="25abe-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="25abe-105">Enabled for</span></span>    |  <span data-ttu-id="25abe-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="25abe-106">Public preview</span></span> | <span data-ttu-id="25abe-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="25abe-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="25abe-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="25abe-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="25abe-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="25abe-109">Oct 2019</span></span>| <span data-ttu-id="25abe-110">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="25abe-110">Nov 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="25abe-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="25abe-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="25abe-112">この新しい在庫エイジング レポートの実行方法は、出力に多数の行が含まれる場合に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="25abe-112">This new way of executing the inventory aging report is beneficial in cases where the output contains a large number of lines.</span></span> <span data-ttu-id="25abe-113">たとえば、50,000 の品目と 300 の店舗があるシナリオで品目グループ、品目、サイト、倉庫別の在庫エイジングを要求すると、データの確認が困難な非常に長いレポートが生成されます。</span><span class="sxs-lookup"><span data-stu-id="25abe-113">For example, requesting the inventory aging by item group, item, site, and warehouse in a scenario with 50,000 items and 300 stores would yield a very long report where data is difficult to review.</span></span> 

<span data-ttu-id="25abe-114">新しいグラフの視覚化により、拡張された在庫エイジングの概要がより短時間で提供されます。</span><span class="sxs-lookup"><span data-stu-id="25abe-114">A new chart visualization provides a faster, enhanced overview of inventory aging.</span></span> <span data-ttu-id="25abe-115">結果を並べ替えてフィルター処理し、結果を外部システムにエクスポートする機能により、在庫エイジング レポートの結果を短時間で簡単に確認できるようになります。</span><span class="sxs-lookup"><span data-stu-id="25abe-115">Facilities for sorting and filtering the results and for exporting the results to an external system, makes the inventory aging report results faster and easier to navigate.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="25abe-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="25abe-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="25abe-117">新しい在庫エイジング レポート ストレージ機能が導入されました。</span><span class="sxs-lookup"><span data-stu-id="25abe-117">A new inventory aging report storage capability has been introduced.</span></span> <span data-ttu-id="25abe-118">新しい在庫エイジング レポートの実行を開始するときは、特定の実行に対して一意の名前を指定する必要があり、レポート生成の結果はその名前で保存されます。</span><span class="sxs-lookup"><span data-stu-id="25abe-118">When you initiate a new execution of the inventory aging report, you will have to provide a unique name for the specific execution, and the results of the report generation will be stored under this name.</span></span> <span data-ttu-id="25abe-119">実行した日時も記録されます。</span><span class="sxs-lookup"><span data-stu-id="25abe-119">The execution date and time will also be recorded.</span></span> <span data-ttu-id="25abe-120">この新しい機能により、同じ期間の在庫エイジング レポートを複数回再生成する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="25abe-120">This new functionality eliminates the need for regenerating the inventory aging report multiple times for the same period.</span></span>

<span data-ttu-id="25abe-121">レポート実行の出力は、**在庫エイジング レポート ストレージの詳細**ページの単純なリストとして、またはフィルター処理とドリルスルーの両方をサポートする新しい在庫エイジング グラフ内の集計ページからアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="25abe-121">The output of the report execution will be accessible on the **inventory aging report storage details** page as a simple list or in an aggregated page in the new inventory aging chart, which supports both filtering and drill-through.</span></span> <span data-ttu-id="25abe-122">このページでは、在庫エイジング レポートの構成に応じて列が動的に調整され、残高が集計されます。</span><span class="sxs-lookup"><span data-stu-id="25abe-122">This page dynamically adjusts columns and aggregates balances depending on the inventory aging report configuration.</span></span> <span data-ttu-id="25abe-123">現在の在庫エイジング レポートの構成をすべて使用できます。</span><span class="sxs-lookup"><span data-stu-id="25abe-123">All your current inventory aging report configurations can be used.</span></span>

<span data-ttu-id="25abe-124">新しい在庫エイジング レポート データ エンティティも導入されました。</span><span class="sxs-lookup"><span data-stu-id="25abe-124">A new inventory aging data entity has also been introduced.</span></span> <span data-ttu-id="25abe-125">これにより、保存した在庫エイジング レポートの出力を、データ管理でサポートされている任意の形式でエクスポートできます。</span><span class="sxs-lookup"><span data-stu-id="25abe-125">This enables you to export the output of a saved inventory aging report to any format supported by data management.</span></span>
<!--feature detail end -->

<span data-ttu-id="25abe-126">![在庫エイジング グラフ](media/chart-final.png "在庫エイジング グラフ")</span><span class="sxs-lookup"><span data-stu-id="25abe-126">![Inventory aging chart](media/chart-final.png "Inventory aging chart")</span></span>
<!-- Picture 1 -->








