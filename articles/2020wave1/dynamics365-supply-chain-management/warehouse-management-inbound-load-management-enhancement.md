---
title: 倉庫管理 – 入庫積荷管理の機能強化
description: ''
author: relnotes
ms.reviewer: kamaybac
ms.date: 02/28/2020
ms.assetid: 3ba85dcc-b159-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: 4ffa2243f5f020989b547310a55ed2330f978b12
ms.sourcegitcommit: 2928661abcc468748ffc7c33516ebc8e3cd5d653
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/04/2020
ms.locfileid: "3099211"
---
# <a name="warehouse-management--inbound-load-management-enhancement"></a><span data-ttu-id="33b76-102">倉庫管理 – 入庫積荷管理の機能強化</span><span class="sxs-lookup"><span data-stu-id="33b76-102">Warehouse management – inbound load management enhancement</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="33b76-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="33b76-103">Enabled for</span></span>    |  <span data-ttu-id="33b76-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="33b76-104">Public preview</span></span> | <span data-ttu-id="33b76-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="33b76-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="33b76-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="33b76-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="33b76-107">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="33b76-107">Apr 2020</span></span>| <span data-ttu-id="33b76-108">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="33b76-108">May 2020</span></span>|


## <a name="feature-details"></a><span data-ttu-id="33b76-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="33b76-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="33b76-110">この機能は以下で構成されます。</span><span class="sxs-lookup"><span data-stu-id="33b76-110">This feature consists of:</span></span>

-  <span data-ttu-id="33b76-111">倉庫モバイル デバイスから入庫を行う際の、発注書在庫トランザクション (Inventtrans) と貨物 ID の新しい関連付け。</span><span class="sxs-lookup"><span data-stu-id="33b76-111">A new association of the purchase order inventory transactions (Inventtrans) with the load ID when receiving from the Warehouse Mobile device.</span></span> 
- <span data-ttu-id="33b76-112">発注書の未積み込み数量の計算に関する機能強化。登録された数量が使用されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="33b76-112">Enhancements on the calculation of the purchase order quantity left to load that is now using registered quantities.</span></span>
- <span data-ttu-id="33b76-113">入庫積荷の倉庫処理操作の更新。</span><span class="sxs-lookup"><span data-stu-id="33b76-113">An update to the inbound load warehouse handling operations.</span></span> <span data-ttu-id="33b76-114">この機能は、"積荷あたり複数の製品受領転記" と呼ばれます。</span><span class="sxs-lookup"><span data-stu-id="33b76-114">The feature is called "Multiple product receipt postings per load."</span></span> <span data-ttu-id="33b76-115">同じ積荷に対して複数の製品受領転記が可能になり、積荷受領プロセスの柔軟性が向上します。</span><span class="sxs-lookup"><span data-stu-id="33b76-115">It adds flexibility to the load receiving process by allowing multiple product receipt postings for the same load.</span></span> <span data-ttu-id="33b76-116">これにより倉庫管理者は、積荷に対して_製品受領書の更新_ジョブを実行した後もその積荷をオープン状態のままにでき、同じ積荷に対して追加の数量登録を実行できるようになります。</span><span class="sxs-lookup"><span data-stu-id="33b76-116">It lets warehouse managers keep a load open even after running the _Update product receipts_ job for that load, thereby allowing additional quantity registrations for the same load.</span></span> <span data-ttu-id="33b76-117">その後、製品受領が元帳に対して継続的に更新されます。</span><span class="sxs-lookup"><span data-stu-id="33b76-117">Thereafter, product receipts are updated to the ledger on an ongoing basis.</span></span>

<span data-ttu-id="33b76-118">これらの機能強化により、ISV は積荷エンティティと統合するときに、より堅牢なソリューションを構築できます。</span><span class="sxs-lookup"><span data-stu-id="33b76-118">These enhancements will allow ISVs to build more robust solutions when integrating with the load entity.</span></span>
<!--feature detail end -->









