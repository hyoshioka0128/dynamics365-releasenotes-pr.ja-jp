---
title: ゾーンしきい値の補充
description: この機能により、動的な場所を使用する会社は、最小/最大補充プロセスを使用できます。たとえば、短期間で多数の在庫のある商品を扱う小売業者などです。
author: relnotes
ms.reviewer: josaw
ms.date: 10/04/2019
ms.assetid: 8462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: ed51441ba4c23256cf8ac00c7d688302b21ade2b
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660564"
---
# <a name="zone-threshold-replenishment"></a><span data-ttu-id="512b0-103">ゾーンしきい値の補充</span><span class="sxs-lookup"><span data-stu-id="512b0-103">Zone threshold replenishment</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="512b0-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="512b0-104">Enabled for</span></span>    |  <span data-ttu-id="512b0-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="512b0-105">Public preview</span></span> | <span data-ttu-id="512b0-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="512b0-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="512b0-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="512b0-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="512b0-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="512b0-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="512b0-109">2019 年 4 月 8 日</span><span class="sxs-lookup"><span data-stu-id="512b0-109">Apr 8, 2019</span></span>| <span data-ttu-id="512b0-110">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="512b0-110">Dec 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="512b0-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="512b0-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="512b0-112">ゾーンベースの補充機能では、最小/最大補充戦略が使用されますが、個々の場所ではなく倉庫ゾーンが評価されます。</span><span class="sxs-lookup"><span data-stu-id="512b0-112">Zone-based replenishment is a feature that uses min/max replenishment strategy but evaluates warehouse zones instead of individual locations.</span></span> <span data-ttu-id="512b0-113">固定の場所の設定に依存しないことで、この機能では動的な場所の補充が可能になります。</span><span class="sxs-lookup"><span data-stu-id="512b0-113">By not taking a dependency on a fixed location setup, the functionality allows for replenishment of dynamic locations.</span></span> <span data-ttu-id="512b0-114">これにより、動的な場所を使用する会社は、最小/最大補充プロセスを使用できます。たとえば、短期間で多数の在庫のある商品を扱う小売業者などです。</span><span class="sxs-lookup"><span data-stu-id="512b0-114">This opens up a min/max replenishment process for companies using dynamic locations, such as retailers that have numerous stocked items with a short live time.</span></span> 

<span data-ttu-id="512b0-115">最小/最大補充用の補充テンプレートでは、ユーザーはしきい値を場所ごとまたはゾーンごとのどちらで評価する必要があるかを指定します。</span><span class="sxs-lookup"><span data-stu-id="512b0-115">At the replenishment template for min/max replenishment, the user specifies whether the threshold should be evaluated per location or per zone.</span></span> <span data-ttu-id="512b0-116">ゾーンの場合は、特定のゾーンがゾーン選択クエリに追加されます。</span><span class="sxs-lookup"><span data-stu-id="512b0-116">In the case of zones, specific zones are then added to the zone-selection query.</span></span> <span data-ttu-id="512b0-117">場所ベースの最小/最大補充では、ゾーン ベースの最小/最大補充は、選択した品目および品目バリアントの補充作業指示書の作成をトリガーする在庫の最小しきい値の設定に基づいています。</span><span class="sxs-lookup"><span data-stu-id="512b0-117">As it is for location-based min/max replenishment, zone-based min/max replenishment is based on setting up a minimum threshold of inventory that triggers the creation of a replenishment work order for selected items and item variants.</span></span> <span data-ttu-id="512b0-118">結果として、在庫を目的のゾーン最大しきい値まで増加させる数量の補充が作成されます。</span><span class="sxs-lookup"><span data-stu-id="512b0-118">In return, replenishment will be created for the quantity that increases inventory up to the desired zone maximum threshold.</span></span>
<!--feature detail end -->








