---
title: 場所のディレクティブ在庫ピッキング エイジング
description: 2 つの新しいピッキング場所ディレクティブ戦略として、FIFO (先入れ先出し) と LIFO (後入れ先出し) が導入されました。 これらは場所とライセンス プレートのエイジング日付フィールドと連携して機能し、在庫が最初に倉庫に入ったときを追跡します。
author: relnotes
ms.reviewer: kamaybac
ms.date: 01/06/2020
ms.assetid: 8262278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: e21848902363fd9a5b154aa7193c3249ad2e1fde
ms.sourcegitcommit: 7d5d14ac84333ba166265755f410f7e16035a64e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2947980"
---
# <a name="location-directive-inventory-picking-aging"></a><span data-ttu-id="8b1fd-104">場所のディレクティブ在庫ピッキング エイジング</span><span class="sxs-lookup"><span data-stu-id="8b1fd-104">Location directive inventory picking aging</span></span>


| <span data-ttu-id="8b1fd-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="8b1fd-105">Enabled for</span></span>    |  <span data-ttu-id="8b1fd-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8b1fd-106">Public preview</span></span> | <span data-ttu-id="8b1fd-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="8b1fd-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8b1fd-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="8b1fd-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="8b1fd-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8b1fd-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8b1fd-110">2019 年 4 月 8 日</span><span class="sxs-lookup"><span data-stu-id="8b1fd-110">Apr 8, 2019</span></span>| <span data-ttu-id="8b1fd-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8b1fd-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8b1fd-112">2019 年 12 月 19 日</span><span class="sxs-lookup"><span data-stu-id="8b1fd-112">Dec 19, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="8b1fd-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8b1fd-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8b1fd-114">2 つの新しいピッキング場所ディレクティブ戦略として、FIFO (先入れ先出し) と LIFO (後入れ先出し) が導入されました。</span><span class="sxs-lookup"><span data-stu-id="8b1fd-114">Two new picking-location directive strategies are introduced: FIFO (first in, first out) and LIFO (last in, first out).</span></span> <span data-ttu-id="8b1fd-115">これらは場所とライセンス プレートのエイジング日付フィールドと連携して機能し、在庫が最初に倉庫に入ったときを追跡します。</span><span class="sxs-lookup"><span data-stu-id="8b1fd-115">These work in conjunction with aging date fields on the location and license plate to track when inventory first entered the warehouse.</span></span> <span data-ttu-id="8b1fd-116">これらの戦略を、バッチと非バッチの両方の追跡対象品目、および在庫が倉庫に入った時期に基づいて顧客に品目を出荷するのに使用できます。</span><span class="sxs-lookup"><span data-stu-id="8b1fd-116">These strategies can be used for both batch and nonbatch tracked items and to ship items to customers based on when the inventory entered the warehouse.</span></span> <span data-ttu-id="8b1fd-117">これは、有効期限がソートに使用できない非バッチの追跡対象在庫に対して特に便利です。</span><span class="sxs-lookup"><span data-stu-id="8b1fd-117">This can be especially useful for nonbatch tracked inventory where an expiration date is not available to use for sorting.</span></span> 

<span data-ttu-id="8b1fd-118">在庫が倉庫内に最初に入庫または作成されたときに、現在の日付がエイジング日付として入力されてライセンス プレートが更新されます。</span><span class="sxs-lookup"><span data-stu-id="8b1fd-118">When inventory is first received or created in the warehouse, the license plate is updated with the current date populated as the aging date.</span></span> <span data-ttu-id="8b1fd-119">その後、この日付は、戦略で倉庫内の最も古い在庫または最も新しい在庫を特定するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="8b1fd-119">This date is then used by the strategies to determine the oldest or youngest inventory in the warehouse.</span></span> <span data-ttu-id="8b1fd-120">在庫がライセンス プレートによる追跡対象でない場所に移動された場合、その場所自体がエイジング日付を反映して更新され、戦略でも使用されます。</span><span class="sxs-lookup"><span data-stu-id="8b1fd-120">If inventory is moved to a non-license-plate-tracked location, the location itself is updated with an aging date, which will also be used by the strategies.</span></span>
<!--feature detail end -->





