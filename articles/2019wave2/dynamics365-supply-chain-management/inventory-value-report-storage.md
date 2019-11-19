---
title: 在庫金額レポート ストレージ
description: 在庫金額レポート ストレージを使用すると、在庫金額レポートを実行して、Dynamics 365 Supply Chain Management のフォーム内で出力にアクセスできるようにしたり、外部アプリケーションで使用するためにデータ エンティティを通じて出力をエクスポートしたりできます。
author: relnotes
ms.reviewer: josaw
ms.date: 10/09/2019
ms.assetid: eda2b127-79ca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aevengir
dynamics365pdf: true
ms.openlocfilehash: 04423faa5bad5a21108e039858609a216b654821
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660606"
---
# <a name="inventory-value-report-storage"></a><span data-ttu-id="8d75e-103">在庫金額レポート ストレージ</span><span class="sxs-lookup"><span data-stu-id="8d75e-103">Inventory value report storage</span></span>


| <span data-ttu-id="8d75e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8d75e-104">Enabled for</span></span>    |  <span data-ttu-id="8d75e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8d75e-105">Public preview</span></span> | <span data-ttu-id="8d75e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8d75e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8d75e-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="8d75e-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="8d75e-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8d75e-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8d75e-109">2019 年 9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="8d75e-109">Sep 6, 2019</span></span>| <span data-ttu-id="8d75e-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8d75e-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8d75e-111">2019 年 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="8d75e-111">Oct 8, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="8d75e-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8d75e-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8d75e-113">この新しい在庫金額レポートの実行方法は、出力に多数の行が含まれる場合に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="8d75e-113">This new way of executing the inventory value report is beneficial in cases where the output contains a large number of lines.</span></span> <span data-ttu-id="8d75e-114">たとえば、50.000 の品目と 300 の店舗があるシナリオで品目、サイト、倉庫別の在庫期末残高を要求すると、データの確認が困難な非常に長いレポートが生成されます。</span><span class="sxs-lookup"><span data-stu-id="8d75e-114">For example, requesting the inventory ending balance by item, site, and warehouse in a scenario with 50,000 items and 300 stores would yield a very long report, where data is difficult to review.</span></span> <span data-ttu-id="8d75e-115">結果を並べ替えてフィルター処理したり、結果を外部システムにエクスポートしたりできると、在庫金額レポートの結果をすばやく簡単に確認できます。</span><span class="sxs-lookup"><span data-stu-id="8d75e-115">Being able to sort and filter the results, or to export the results to an external system, makes the inventory value report results faster and easier to navigate.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8d75e-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8d75e-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8d75e-117">新しい在庫金額レポート ストレージ機能が導入されました。</span><span class="sxs-lookup"><span data-stu-id="8d75e-117">A new inventory value report storage capability has been introduced.</span></span> <span data-ttu-id="8d75e-118">新しい在庫金額レポートの実行を開始するときは、特定の実行に対して一意の名前を指定する必要があり、レポート生成の結果はその名前で保存されます。</span><span class="sxs-lookup"><span data-stu-id="8d75e-118">When you initiate a new execution of the inventory value report, you will have to provide a unique name for the specific execution, and the results of the report generation will be stored under this name.</span></span> <span data-ttu-id="8d75e-119">これにより、同じ期間に対して複数の在庫金額レポートを実行する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="8d75e-119">This eliminates the need for running multiple inventory value reports for the same period.</span></span> 

<span data-ttu-id="8d75e-120">レポート実行の出力には、在庫金額レポート ストレージの詳細フォーム内でアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="8d75e-120">The output of the report execution will be accessible in the inventory value report storage details form.</span></span> <span data-ttu-id="8d75e-121">このフォームでは、構成された在庫金額レポートのレイアウトに応じて列が動的に調整され、残高が集計されます。</span><span class="sxs-lookup"><span data-stu-id="8d75e-121">This form dynamically adjusts columns and aggregates balances depending on the inventory value report layout configured.</span></span> <span data-ttu-id="8d75e-122">現在の在庫金額レポートの構成をすべて使用できます。</span><span class="sxs-lookup"><span data-stu-id="8d75e-122">All your current inventory value report configurations can be used.</span></span> 

<span data-ttu-id="8d75e-123">新しい在庫金額レポート データ エンティティも導入されました。</span><span class="sxs-lookup"><span data-stu-id="8d75e-123">A new inventory value report data entity has also been introduced.</span></span> <span data-ttu-id="8d75e-124">これにより、実行された特定の名前付き在庫金額レポートの出力を、データ管理でサポートされている任意の形式でエクスポートできます。</span><span class="sxs-lookup"><span data-stu-id="8d75e-124">This enables you to export the output of a specific, named inventory value report run to any format supported by data management.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="8d75e-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="8d75e-125">See also</span></span>

<span data-ttu-id="8d75e-126">[在庫金額レポート](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/cost-management/inventory-value-report) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="8d75e-126">[Inventory value report](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/cost-management/inventory-value-report) (docs)</span></span>
