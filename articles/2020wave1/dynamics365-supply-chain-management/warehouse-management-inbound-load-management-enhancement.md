---
title: 入庫積荷管理の機能強化
description: 入庫積荷管理の機能強化
author: relnotes
ms.reviewer: kamaybac
ms.date: 06/02/2020
ms.assetid: 3ba85dcc-b159-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: 21e2cd09f9c34651a0c4763866d62f9e840950e6
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3440789"
---
# <a name="inbound-load-management-enhancement"></a><span data-ttu-id="02723-103">入庫積荷管理の機能強化</span><span class="sxs-lookup"><span data-stu-id="02723-103">Inbound load management enhancement</span></span>


| <span data-ttu-id="02723-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="02723-104">Enabled for</span></span>    |  <span data-ttu-id="02723-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="02723-105">Public preview</span></span> | <span data-ttu-id="02723-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="02723-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="02723-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="02723-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="02723-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="02723-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="02723-109">2020 年 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="02723-109">Apr 17, 2020</span></span>| <span data-ttu-id="02723-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="02723-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="02723-111">2020 年 5 月 26 日</span><span class="sxs-lookup"><span data-stu-id="02723-111">May 26, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="02723-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="02723-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="02723-113">この機能により、発注書に対する入庫積荷の倉庫処理プロセスにいくつかの機能強化が追加されます。</span><span class="sxs-lookup"><span data-stu-id="02723-113">This feature adds several enhancements to the warehouse handling processes of inbound loads for purchase orders.</span></span> <span data-ttu-id="02723-114">これらの機能強化によって、独立系ソフトウェア ベンダー (ISV) は積荷エンティティと統合するときに、より堅牢なソリューションを構築できます。</span><span class="sxs-lookup"><span data-stu-id="02723-114">These enhancements will allow independent software vendors (ISVs) to build more robust solutions when integrating with the load entity.</span></span>

### <a name="enhancements-added-in-release-10011"></a><span data-ttu-id="02723-115">リリース 10.0.11 で追加された機能強化</span><span class="sxs-lookup"><span data-stu-id="02723-115">Enhancements added in release 10.0.11</span></span>

- <span data-ttu-id="02723-116">_積荷数量の超過入庫_。これにより、入庫積荷数量の超過入庫を許可するか禁止するかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="02723-116">_Over receipt of load quantities_ now lets you choose whether to allow or prevent over receipt of inbound load quantities.</span></span> <span data-ttu-id="02723-117">超過入庫は、作業者が選択した積荷の残りの未登録数量 (超過配送率の調整後) を超える数量を入力したときに発生します。</span><span class="sxs-lookup"><span data-stu-id="02723-117">Over receipts occur when a worker registers a quantity that is greater than the remaining unregistered quantity for a selected load (adjusted for overdelivery percentage).</span></span> <span data-ttu-id="02723-118">超過入庫の許可を選択する場合でも、終了した (状態が "受入済" である) 積荷に対しては禁止を選択できます。</span><span class="sxs-lookup"><span data-stu-id="02723-118">Even if you choose to allow over receipts, you can still choose to prevent them for loads that are closed (with status "Received").</span></span>

### <a name="enhancements-added-in-release-10010"></a><span data-ttu-id="02723-119">リリース 10.0.10 で追加された機能強化</span><span class="sxs-lookup"><span data-stu-id="02723-119">Enhancements added in release 10.0.10</span></span>

- <span data-ttu-id="02723-120">倉庫モバイル デバイスから入庫を行う際の、発注書在庫トランザクション (Inventtrans) と積荷 ID の新しい関連付け。</span><span class="sxs-lookup"><span data-stu-id="02723-120">A new association of the purchase order inventory transactions (Inventtrans) with the load ID when receiving from the Warehouse Mobile device.</span></span> 
- <span data-ttu-id="02723-121">発注書の積荷残数量の計算に対する機能強化。登録済数量が使用されるようになり、_発注書明細行の積荷残数量_の計算が、積荷の登録済数量がマークして表示されるビューに置き換えられました。</span><span class="sxs-lookup"><span data-stu-id="02723-121">Enhancements to the calculation of the purchase order quantity left to load, which is now using registered quantities, and the calculation of _Quantity left to load for a purchase order line_ is replaced with a view that shows the registered quantity marked with a load.</span></span> 
- <span data-ttu-id="02723-122">_積荷あたり複数の製品受領転記_と呼ばれる機能による、入庫積荷の倉庫処理操作の更新。</span><span class="sxs-lookup"><span data-stu-id="02723-122">Updated inbound load warehouse handling operation through a feature called _Multiple product receipt postings per load_.</span></span> <span data-ttu-id="02723-123">同じ積荷に対して複数の製品受領転記が可能になり、積荷受領プロセスの柔軟性が向上します。</span><span class="sxs-lookup"><span data-stu-id="02723-123">It adds flexibility to the load receiving process by allowing multiple product receipt postings for the same load.</span></span> <span data-ttu-id="02723-124">これにより倉庫管理者は、積荷に対して_製品受領書の更新_ジョブを実行した後もその積荷をオープン状態のままにでき、同じ積荷に対して追加の数量登録を実行できるようになります。</span><span class="sxs-lookup"><span data-stu-id="02723-124">It lets warehouse managers keep a load open even after running the _Update product receipts_ job for that load, thereby allowing additional quantity registrations for the same load.</span></span> <span data-ttu-id="02723-125">その後、製品受領が元帳に対して継続的に更新されます。</span><span class="sxs-lookup"><span data-stu-id="02723-125">Thereafter, product receipts are updated to the ledger on an ongoing basis.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="02723-126">関連項目</span><span class="sxs-lookup"><span data-stu-id="02723-126">See also</span></span>

<!--docs start-->
<span data-ttu-id="02723-127">[発注書に対する入庫積荷の倉庫処理](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/inbound-load-handling) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="02723-127">[Warehouse handling of inbound loads for purchase orders](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/inbound-load-handling) (docs)</span></span>
<!--docs end-->
