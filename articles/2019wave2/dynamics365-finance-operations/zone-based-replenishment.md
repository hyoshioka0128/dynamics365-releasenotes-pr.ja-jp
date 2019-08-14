---
title: ゾーン ベースの補充
description: この機能により、動的な場所を使用する会社は、最小/最大補充プロセスを使用できます。たとえば、短期間で多数の在庫のある商品を扱う小売業者などです。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: 8462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: d0ae252886c52d7709bf9e6f131139afc85b9588
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854616"
---
# <a name="zone-based-replenishment"></a><span data-ttu-id="b1d15-103">ゾーン ベースの補充</span><span class="sxs-lookup"><span data-stu-id="b1d15-103">Zone-based replenishment</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="b1d15-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b1d15-104">Enabled for</span></span>    |  <span data-ttu-id="b1d15-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b1d15-105">Public preview</span></span> | <span data-ttu-id="b1d15-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b1d15-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="b1d15-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="b1d15-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="b1d15-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="b1d15-108">August 2019</span></span>| <span data-ttu-id="b1d15-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="b1d15-109">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="b1d15-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b1d15-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b1d15-111">ゾーンベースの補充機能では、最小/最大補充戦略が使用されますが、個々の場所ではなく倉庫ゾーンが評価されます。</span><span class="sxs-lookup"><span data-stu-id="b1d15-111">Zone-based replenishment is a feature that utilizes min/max replenishment strategy but evaluates warehouse zones instead of individual locations.</span></span> <span data-ttu-id="b1d15-112">固定の場所の設定に依存しないことで、この機能では動的な場所の補充が可能になります。</span><span class="sxs-lookup"><span data-stu-id="b1d15-112">By not taking a dependency on a fixed location setup, the functionality allows for replenishment of dynamic locations.</span></span> <span data-ttu-id="b1d15-113">これにより、動的な場所を使用する会社は、最小/最大補充プロセスを使用できます。たとえば、短期間で多数の在庫のある商品を扱う小売業者などです。</span><span class="sxs-lookup"><span data-stu-id="b1d15-113">This opens up a min/max replenishment process for companies using dynamic locations, such as retailers that have numerous stocked items with a short live time.</span></span> <span data-ttu-id="b1d15-114">最小/最大補充用の補充テンプレートでは、ユーザーはしきい値を場所ごとまたはゾーンごとのどちらで評価する必要があるかを指定します。</span><span class="sxs-lookup"><span data-stu-id="b1d15-114">At the replenishment template for min/max replenishment, the user specifies whether the threshold should be evaluated per location or per zone.</span></span> <span data-ttu-id="b1d15-115">ゾーンの場合は、特定のゾーンがゾーン選択クエリに追加されます。</span><span class="sxs-lookup"><span data-stu-id="b1d15-115">In the case of zones, specific zones are then added to the zone-selection query.</span></span> <span data-ttu-id="b1d15-116">場所ベースの最小/最大補充では、ゾーン ベースの最小/最大補充は、選択した品目および品目バリアントの補充作業指示書の作成をトリガーする在庫の最小しきい値の設定に基づいています。</span><span class="sxs-lookup"><span data-stu-id="b1d15-116">As it is for location-based min/max replenishment, zone-based min/max replenishment is based on setting up a minimum threshold of inventory that triggers the creation of a replenishment work order for selected items and item variants.</span></span> <span data-ttu-id="b1d15-117">結果として、在庫を目的のゾーン最大しきい値まで増加させる数量の補充が作成されます。</span><span class="sxs-lookup"><span data-stu-id="b1d15-117">In return, replenishment will be created for the quantity that increases inventory up to the desired zone maximum threshold.</span></span>
<!--feature detail end -->











