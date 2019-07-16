---
title: 高度な割り当て戦略 - FIFO と LIFO
description: 2 つの新しいピッキング場所ディレクティブ戦略として、FIFO (先入れ先出し) と LIFO (後入れ先出し) が導入されました。 これらは場所とライセンス プレートのエイジング日付フィールドと連携して機能し、在庫が最初に倉庫に入ったときを追跡します。
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 8262278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: c1d2ff78ac439634ddf2c06908917c1d6a05a416
ms.sourcegitcommit: d6ff62c145bfdd7742034a67a29bf75938823eb0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/24/2019
ms.locfileid: "1701975"
---
# <a name="advanced-allocation-strategies-fifo-and-lifo"></a><span data-ttu-id="66f66-104">高度な割り当て戦略: FIFO と LIFO</span><span class="sxs-lookup"><span data-stu-id="66f66-104">Advanced allocation strategies: FIFO and LIFO</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="66f66-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="66f66-105">Enabled for</span></span>    |  <span data-ttu-id="66f66-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="66f66-106">Public preview</span></span> | <span data-ttu-id="66f66-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="66f66-107">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="66f66-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="66f66-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="66f66-109">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="66f66-109">April 2019</span></span>| <span data-ttu-id="66f66-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="66f66-110">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="66f66-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="66f66-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="66f66-112">2 つの新しいピッキング場所ディレクティブ戦略として、FIFO (先入れ先出し) と LIFO (後入れ先出し) が導入されました。</span><span class="sxs-lookup"><span data-stu-id="66f66-112">Two new picking-location directive strategies are introduced: FIFO (first in, first out) and LIFO (last in, first out).</span></span> <span data-ttu-id="66f66-113">これらは場所とライセンス プレートのエイジング日付フィールドと連携して機能し、在庫が最初に倉庫に入ったときを追跡します。</span><span class="sxs-lookup"><span data-stu-id="66f66-113">These work in conjunction with aging date fields on the location and license plate to track when inventory first entered the warehouse.</span></span> <span data-ttu-id="66f66-114">これらの戦略をバッチと非バッチの両方の追跡対象品目に使用し、在庫が倉庫に入った時期に基づいて顧客に品目を出荷できます。</span><span class="sxs-lookup"><span data-stu-id="66f66-114">These strategies can be used for both batch and nonbatch tracked items, to ship items to customers based on when the inventory entered the warehouse.</span></span> <span data-ttu-id="66f66-115">これは、有効期限がソートに使用できない非バッチの追跡対象在庫に対して特に便利です。</span><span class="sxs-lookup"><span data-stu-id="66f66-115">This can be especially useful for nonbatch tracked inventory where an expiration date is not available to use for sorting.</span></span> <span data-ttu-id="66f66-116">在庫が倉庫内に最初に入庫または作成されたときに、現在の日付がエイジング日付として入力されてライセンス プレートが更新されます。</span><span class="sxs-lookup"><span data-stu-id="66f66-116">When inventory is first received/created in the warehouse, the license plate is updated with the current date populated as the aging date.</span></span> <span data-ttu-id="66f66-117">その後、この日付は、戦略で倉庫内の最も古い在庫または最も新しい在庫を特定するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="66f66-117">This date is then used by the strategies to determine the oldest/youngest inventory in the warehouse.</span></span> <span data-ttu-id="66f66-118">在庫がライセンス プレートによる追跡対象でない場所に移動された場合、その場所自体がエイジング日付を反映して更新され、戦略でも使用されます。</span><span class="sxs-lookup"><span data-stu-id="66f66-118">If inventory is moved to a non-license-plate-tracked location, the location itself is updated with an aging date, which will also be used by the strategies.</span></span>
<!--feature detail end -->










