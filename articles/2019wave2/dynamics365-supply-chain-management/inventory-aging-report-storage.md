---
title: 在庫エイジング レポート ストレージ
description: 在庫エイジング レポート ストレージを使用すると、在庫エイジング レポートを実行し、出力を Dynamics 365 Supply Chain Management のフォームのシンプルなリストとしてアクセスできるようにするか、結果をグラフで視覚化できます。 また、外部アプリケーションで使用するために、データ エンティティを介して在庫エイジング レポートからの出力をエクスポートすることもできます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 01/07/2020
ms.assetid: a816499f-67e0-e911-a814-000d3a4f1244
ms.topic: article
ms.service: business-applications
ms.author: aevengir
dynamics365pdf: true
ms.openlocfilehash: 84c3de92cb3d5e7cacf764f11f4c0ffb5273777d
ms.sourcegitcommit: 7d5d14ac84333ba166265755f410f7e16035a64e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2948343"
---
# <a name="inventory-aging-report-storage"></a><span data-ttu-id="3709e-104">在庫エイジング レポート ストレージ</span><span class="sxs-lookup"><span data-stu-id="3709e-104">Inventory aging report storage</span></span>


| <span data-ttu-id="3709e-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="3709e-105">Enabled for</span></span>    |  <span data-ttu-id="3709e-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3709e-106">Public preview</span></span> | <span data-ttu-id="3709e-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="3709e-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3709e-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="3709e-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="3709e-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3709e-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3709e-110">2019 年 10 月 21 日</span><span class="sxs-lookup"><span data-stu-id="3709e-110">Oct 21, 2019</span></span>| <span data-ttu-id="3709e-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3709e-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3709e-112">2020 年 1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="3709e-112">Jan 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3709e-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3709e-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3709e-114">この新しい在庫エイジング レポートの実行方法は、出力に多数の行が含まれる場合に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="3709e-114">This new way of executing the inventory aging report is beneficial in cases where the output contains a large number of lines.</span></span> <span data-ttu-id="3709e-115">たとえば、50,000 の品目と 300 の店舗があるシナリオで品目グループ、品目、サイト、倉庫別の在庫エイジングを要求すると、データの確認が困難な非常に長いレポートが生成されます。</span><span class="sxs-lookup"><span data-stu-id="3709e-115">For example, requesting the inventory aging by item group, item, site, and warehouse in a scenario with 50,000 items and 300 stores would yield a very long report where data is difficult to review.</span></span> 

<span data-ttu-id="3709e-116">新しいグラフの視覚化により、拡張された在庫エイジングの概要がより短時間で提供されます。</span><span class="sxs-lookup"><span data-stu-id="3709e-116">A new chart visualization provides a faster, enhanced overview of inventory aging.</span></span> <span data-ttu-id="3709e-117">結果を並べ替えてフィルター処理し、結果を外部システムにエクスポートする機能により、在庫エイジング レポートの結果を短時間で簡単に確認できるようになります。</span><span class="sxs-lookup"><span data-stu-id="3709e-117">Facilities for sorting and filtering the results and for exporting the results to an external system, makes the inventory aging report results faster and easier to navigate.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3709e-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3709e-118">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3709e-119">新しい在庫エイジング レポート ストレージ機能が導入されました。</span><span class="sxs-lookup"><span data-stu-id="3709e-119">A new inventory aging report storage capability has been introduced.</span></span> <span data-ttu-id="3709e-120">新しい在庫エイジング レポートの実行を開始するときは、特定の実行に対して一意の名前を指定する必要があり、レポート生成の結果はその名前で保存されます。</span><span class="sxs-lookup"><span data-stu-id="3709e-120">When you initiate a new execution of the inventory aging report, you will have to provide a unique name for the specific execution, and the results of the report generation will be stored under this name.</span></span> <span data-ttu-id="3709e-121">実行した日時も記録されます。</span><span class="sxs-lookup"><span data-stu-id="3709e-121">The execution date and time will also be recorded.</span></span> <span data-ttu-id="3709e-122">この新しい機能により、同じ期間の在庫エイジング レポートを複数回再生成する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="3709e-122">This new functionality eliminates the need for regenerating the inventory aging report multiple times for the same period.</span></span>

<span data-ttu-id="3709e-123">レポート実行の出力は、**在庫エイジング レポート ストレージの詳細**ページの単純なリストとして、またはフィルター処理とドリルスルーの両方をサポートする新しい在庫エイジング グラフ内の集計ページからアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="3709e-123">The output of the report execution will be accessible on the **inventory aging report storage details** page as a simple list or in an aggregated page in the new inventory aging chart, which supports both filtering and drill-through.</span></span> <span data-ttu-id="3709e-124">このページでは、在庫エイジング レポートの構成に応じて列が動的に調整され、残高が集計されます。</span><span class="sxs-lookup"><span data-stu-id="3709e-124">This page dynamically adjusts columns and aggregates balances depending on the inventory aging report configuration.</span></span> <span data-ttu-id="3709e-125">現在の在庫エイジング レポートの構成をすべて使用できます。</span><span class="sxs-lookup"><span data-stu-id="3709e-125">All your current inventory aging report configurations can be used.</span></span>

<span data-ttu-id="3709e-126">新しい在庫エイジング レポート データ エンティティも導入されました。</span><span class="sxs-lookup"><span data-stu-id="3709e-126">A new inventory aging data entity has also been introduced.</span></span> <span data-ttu-id="3709e-127">これにより、保存した在庫エイジング レポートの出力を、データ管理でサポートされている任意の形式でエクスポートできます。</span><span class="sxs-lookup"><span data-stu-id="3709e-127">This enables you to export the output of a saved inventory aging report to any format supported by data management.</span></span>
<!--feature detail end -->

<span data-ttu-id="3709e-128">![在庫エイジング グラフ](media/chart-final.png "在庫エイジング グラフ")</span><span class="sxs-lookup"><span data-stu-id="3709e-128">![Inventory aging chart](media/chart-final.png "Inventory aging chart")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="3709e-129">関連項目</span><span class="sxs-lookup"><span data-stu-id="3709e-129">See also</span></span>

<span data-ttu-id="3709e-130">[Dynamics 365 Supply Chain Management 10.0.6 (2019 年 11 月) の新機能および変更された機能](https://docs.microsoft.com/dynamics365/supply-chain/get-started/whats-new-scm-10-0-6) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="3709e-130">[What's new or changed in Dynamics 365 Supply Chain Management 10.0.6 (November 2019)](https://docs.microsoft.com/dynamics365/supply-chain/get-started/whats-new-scm-10-0-6) (docs)</span></span>
