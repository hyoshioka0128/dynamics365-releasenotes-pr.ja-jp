---
title: 高度な割り当て戦略 - FIFO と LIFO
description: 2 つの新しいピッキング場所ディレクティブ戦略として、FIFO (先入れ先出し) と LIFO (後入れ先出し) が導入されました。 これらは場所とライセンス プレートのエイジング日付フィールドと連携して機能し、在庫が最初に倉庫に入ったときを追跡します。
author: relnotes
ms.reviewer: josaw
ms.date: 08/02/2019
ms.assetid: 8262278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: af33c1d7c762274f73e86ca5926438920402bc31
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141681"
---
# <a name="advanced-allocation-strategies---fifo-and-lifo"></a><span data-ttu-id="77f74-104">高度な割り当て戦略 - FIFO と LIFO</span><span class="sxs-lookup"><span data-stu-id="77f74-104">Advanced allocation strategies - FIFO and LIFO</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="77f74-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="77f74-105">Enabled for</span></span>    |  <span data-ttu-id="77f74-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="77f74-106">Public preview</span></span> | <span data-ttu-id="77f74-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="77f74-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="77f74-108">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="77f74-108">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="77f74-109">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="77f74-109">Aug 2019</span></span>| <span data-ttu-id="77f74-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="77f74-110">Oct 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="77f74-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="77f74-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="77f74-112">2 つの新しいピッキング場所ディレクティブ戦略として、FIFO (先入れ先出し) と LIFO (後入れ先出し) が導入されました。</span><span class="sxs-lookup"><span data-stu-id="77f74-112">Two new picking-location directive strategies are introduced: FIFO (first in, first out) and LIFO (last in, first out).</span></span> <span data-ttu-id="77f74-113">これらは場所とライセンス プレートのエイジング日付フィールドと連携して機能し、在庫が最初に倉庫に入ったときを追跡します。</span><span class="sxs-lookup"><span data-stu-id="77f74-113">These work in conjunction with aging date fields on the location and license plate to track when inventory first entered the warehouse.</span></span> <span data-ttu-id="77f74-114">これらの戦略をバッチと非バッチの両方の追跡対象品目に使用し、在庫が倉庫に入った時期に基づいて顧客に品目を出荷できます。</span><span class="sxs-lookup"><span data-stu-id="77f74-114">These strategies can be used for both batch and nonbatch tracked items, to ship items to customers based on when the inventory entered the warehouse.</span></span> <span data-ttu-id="77f74-115">これは、有効期限がソートに使用できない非バッチの追跡対象在庫に対して特に便利です。</span><span class="sxs-lookup"><span data-stu-id="77f74-115">This can be especially useful for nonbatch tracked inventory where an expiration date is not available to use for sorting.</span></span> <span data-ttu-id="77f74-116">在庫が倉庫内に最初に入庫または作成されたときに、現在の日付がエイジング日付として入力されてライセンス プレートが更新されます。</span><span class="sxs-lookup"><span data-stu-id="77f74-116">When inventory is first received or created in the warehouse, the license plate is updated with the current date populated as the aging date.</span></span> <span data-ttu-id="77f74-117">その後、この日付は、戦略で倉庫内の最も古い在庫または最も新しい在庫を特定するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="77f74-117">This date is then used by the strategies to determine the oldest or youngest inventory in the warehouse.</span></span> <span data-ttu-id="77f74-118">在庫がライセンス プレートによる追跡対象でない場所に移動された場合、その場所自体がエイジング日付を反映して更新され、戦略でも使用されます。</span><span class="sxs-lookup"><span data-stu-id="77f74-118">If inventory is moved to a non-license-plate-tracked location, the location itself is updated with an aging date, which will also be used by the strategies.</span></span>
<!--feature detail end -->











