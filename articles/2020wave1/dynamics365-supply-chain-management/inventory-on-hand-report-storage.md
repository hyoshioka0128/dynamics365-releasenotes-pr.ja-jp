---
title: 手持在庫レポート ストレージ
description: Dynamics 365 Supply Chain Management で直接探索したり、エクスポートして外部アプリケーションで使用したりできる手持在庫レポートを生成します。
author: RichardLuan
ms.reviewer: kamaybac
ms.date: 06/02/2020
ms.assetid: 2a3532b4-5c73-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: riluan
dynamics365pdf: true
ms.openlocfilehash: cbca6abae5afc05ec810ffac65c797f0949be331
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3441713"
---
# <a name="inventory-on-hand-report-storage"></a><span data-ttu-id="2a0f5-103">手持在庫レポート ストレージ</span><span class="sxs-lookup"><span data-stu-id="2a0f5-103">Inventory on-hand report storage</span></span>


| <span data-ttu-id="2a0f5-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="2a0f5-104">Enabled for</span></span>    |  <span data-ttu-id="2a0f5-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2a0f5-105">Public preview</span></span> | <span data-ttu-id="2a0f5-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="2a0f5-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="2a0f5-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="2a0f5-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="2a0f5-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2a0f5-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2a0f5-109">2020 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="2a0f5-109">Apr 16, 2020</span></span>| <span data-ttu-id="2a0f5-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2a0f5-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2a0f5-111">2020 年 5 月 26 日</span><span class="sxs-lookup"><span data-stu-id="2a0f5-111">May 26, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="2a0f5-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2a0f5-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="2a0f5-113">この新しい手持在庫レポートの生成方法は、出力に多数の行が含まれる場合に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="2a0f5-113">This new way of generating an on-hand inventory report is beneficial in cases where the output contains a large number of lines.</span></span> <span data-ttu-id="2a0f5-114">たとえば、50,000 の品目と 300 の店舗があるシナリオで品目、サイト、倉庫別の手持在庫を要求すると、データの確認を困難にする非常に長いレポートが生成されます。</span><span class="sxs-lookup"><span data-stu-id="2a0f5-114">For example, requesting the on-hand inventory by item, site, and warehouse in a scenario for 50,000 items and 300 stores would yield a very long report, making the data difficult to review.</span></span> <span data-ttu-id="2a0f5-115">アプリケーション内で結果を並べ替えてフィルター処理したり、結果を外部システムにエクスポートしたりする機能により、手持在庫レポートの結果をすばやく簡単に確認できます。</span><span class="sxs-lookup"><span data-stu-id="2a0f5-115">The ability to sort and filter the results in the application or to export the results to an external system makes the on-hand inventory report results faster and easier to navigate.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="2a0f5-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2a0f5-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="2a0f5-117">新しい*手持在庫レポート ストレージ*機能では、手持在庫レポートが生成され、その結果が Supply Chain Management に保存されます。Supply Chain Management では、結果をオンラインで探索したり、外部システムで使用するためにエクスポートしたりできます。</span><span class="sxs-lookup"><span data-stu-id="2a0f5-117">The new *Inventory on-hand report storage* feature generates an on-hand inventory report and then saves the results in Supply Chain Management, where you can explore the results online and/or export them for use in an external system.</span></span> 

<span data-ttu-id="2a0f5-118">この機能を使用してレポートを生成すると、レポートに一意の名前を指定するよう求められ、生成されたレポートはこの名前で保存されます。</span><span class="sxs-lookup"><span data-stu-id="2a0f5-118">When you generate a report using this feature, you'll be asked to specify a unique name for it, and then the generated report will be stored under this name.</span></span> <span data-ttu-id="2a0f5-119">これにより、同じ期間に対して複数の手持在庫レポートを実行する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="2a0f5-119">This eliminates the need for running multiple on-hand inventory reports for the same period.</span></span> <span data-ttu-id="2a0f5-120">ユーザーは、**手持在庫レポート ストレージ詳細**ページに移動することで保存されたレポートを参照できます。</span><span class="sxs-lookup"><span data-stu-id="2a0f5-120">Users can browse any stored report by going to the **Inventory on-hand report storage details** page.</span></span>

<span data-ttu-id="2a0f5-121">*手持在庫レポート ストレージ* レポートは新しいデータ エンティティに保存されます。これにより、特定の名前付き手持在庫レポートの出力を、データ管理でサポートされている任意の形式にエクスポートできます。</span><span class="sxs-lookup"><span data-stu-id="2a0f5-121">*Inventory on-hand report storage* reports are stored in a new data entity, which enables you export the output of any specific, named inventory on-hand report to any format supported by data management.</span></span>
<!--feature detail end -->









