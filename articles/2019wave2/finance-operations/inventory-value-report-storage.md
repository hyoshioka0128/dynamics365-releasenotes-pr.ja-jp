---
title: 在庫金額レポート ストレージ
description: 在庫金額レポート ストレージを使用すると、在庫金額レポートを実行して、Dynamics 365 Supply Chain のフォーム内で出力にアクセスできるようにしたり、外部アプリケーションで使用するためにデータ エンティティを通じて出力をエクスポートしたりできます。
author: relnotes
ms.reviewer: josaw
ms.date: 09/16/2019
ms.assetid: eda2b127-79ca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aevengir
dynamics365pdf: true
ms.openlocfilehash: 971e0a973e52653b6c1b8fecddf82b1829d0accb
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143078"
---
# <a name="inventory-value-report-storage"></a><span data-ttu-id="2866f-103">在庫金額レポート ストレージ</span><span class="sxs-lookup"><span data-stu-id="2866f-103">Inventory value report storage</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="2866f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="2866f-104">Enabled for</span></span>    |  <span data-ttu-id="2866f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2866f-105">Public preview</span></span> | <span data-ttu-id="2866f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="2866f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="2866f-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="2866f-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="2866f-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2866f-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2866f-109">2019 年 9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="2866f-109">Sep 6, 2019</span></span>| <span data-ttu-id="2866f-110">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="2866f-110">Nov 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="2866f-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2866f-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="2866f-112">この新しい在庫金額レポートの実行方法は、出力に多数の行が含まれる場合に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="2866f-112">This new way of executing the inventory value report is beneficial in cases where the output contains a large number of lines.</span></span> <span data-ttu-id="2866f-113">たとえば、50.000 の品目と 300 の店舗があるシナリオで品目、サイト、倉庫別の在庫期末残高を要求すると、データの確認が困難な非常に長いレポートが生成されます。</span><span class="sxs-lookup"><span data-stu-id="2866f-113">For example, requesting the inventory ending balance by item, site, and warehouse in a scenario with 50.000 items and 300 stores would yield a very long report, where data is difficult to review.</span></span> <span data-ttu-id="2866f-114">結果を並べ替えてフィルター処理したり、結果を外部システムにエクスポートしたりできると、在庫金額レポートの結果をすばやく簡単に確認できます。</span><span class="sxs-lookup"><span data-stu-id="2866f-114">Being able to sort and filter the results, or to export the results to an external system, makes the inventory value report results faster and easier to navigate.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="2866f-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2866f-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="2866f-116">新しい在庫金額レポート ストレージ機能が導入されました。</span><span class="sxs-lookup"><span data-stu-id="2866f-116">A new inventory value report storage capability has been introduced.</span></span> <span data-ttu-id="2866f-117">新しい在庫金額レポートの実行を開始するときは、特定の実行に対して一意の名前を指定する必要があり、レポート生成の結果はその名前で保存されます。</span><span class="sxs-lookup"><span data-stu-id="2866f-117">When you initiate a new execution of the inventory value report, you will have to provide a unique name for the specific execution, and the results of the report generation will be stored under this name.</span></span> <span data-ttu-id="2866f-118">これにより、同じ期間に対して複数の在庫金額レポートを実行する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="2866f-118">This eliminates the need for running multiple inventory value reports for the same period.</span></span> 

<span data-ttu-id="2866f-119">レポート実行の出力には、在庫金額レポート ストレージの詳細フォーム内でアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="2866f-119">The output of the report execution will be accessible in the inventory value report storage details form.</span></span> <span data-ttu-id="2866f-120">このフォームでは、構成された在庫金額レポートのレイアウトに応じて列が動的に調整され、残高が集計されます。</span><span class="sxs-lookup"><span data-stu-id="2866f-120">This form dynamically adjust columns and aggregate balances depending on the inventory value report layout configured.</span></span> <span data-ttu-id="2866f-121">現在の在庫金額レポートの構成をすべて使用できます。</span><span class="sxs-lookup"><span data-stu-id="2866f-121">All your current inventory value report configurations can be used.</span></span> 

<span data-ttu-id="2866f-122">新しい在庫金額レポート データ エンティティも導入されました。</span><span class="sxs-lookup"><span data-stu-id="2866f-122">A new inventory value report data entity has also been introduced.</span></span> <span data-ttu-id="2866f-123">これにより、実行された特定の名前付き在庫金額レポートの出力を、データ管理でサポートされている任意の形式でエクスポートできます。</span><span class="sxs-lookup"><span data-stu-id="2866f-123">This enables you to export the output of a specific, named inventory value report run to any format supported by data management.</span></span>
<!--feature detail end -->

