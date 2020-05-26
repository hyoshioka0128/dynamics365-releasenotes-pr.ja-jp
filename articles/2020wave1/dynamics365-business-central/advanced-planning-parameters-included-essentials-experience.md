---
title: Essentials エクスペリエンスに含まれる高度な計画パラメーター
description: 供給計画は、卸売活動、製造、組立管理に従事する企業にとって特に重要です。 これらのビジネスをサポートするために、Business Central では、実際と予測の需要および可用性と、リード タイム、再発注ポイントと安全在庫ポイント、最小数量と最大数量などの各種計画パラメーターに基づいて、在庫の補充に関する最適な提案を生成できます。 これらの高度な供給計画機能は、より広く利用できるように、Essentials エクスペリエンスにも含まれるようになりました。
author: relnotes
ms.reviewer: edupont
ms.date: 04/06/2020
ms.assetid: 995790da-3b69-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: andreipa
dynamics365pdf: true
ms.openlocfilehash: f4916764d4b8fe2c244778890899cc3c406ab540
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255191"
---
# <a name="advanced-planning-parameters-included-in-the-essentials-experience"></a><span data-ttu-id="2a4a2-105">Essentials エクスペリエンスに含まれる高度な計画パラメーター</span><span class="sxs-lookup"><span data-stu-id="2a4a2-105">Advanced planning parameters included in the Essentials experience</span></span>


| <span data-ttu-id="2a4a2-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="2a4a2-106">Enabled for</span></span>    |  <span data-ttu-id="2a4a2-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2a4a2-107">Public preview</span></span> | <span data-ttu-id="2a4a2-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="2a4a2-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="2a4a2-109">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="2a4a2-109">End users, automatically</span></span>|<span data-ttu-id="2a4a2-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2a4a2-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2a4a2-111">2020 年 2 月 19 日</span><span class="sxs-lookup"><span data-stu-id="2a4a2-111">Feb 19, 2020</span></span>| <span data-ttu-id="2a4a2-112">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2a4a2-112">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2a4a2-113">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2a4a2-113">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="2a4a2-114">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2a4a2-114">Business value</span></span>

<!-- bv start -->
<span data-ttu-id="2a4a2-115">供給計画は、卸売活動、製造、組立管理に従事する企業にとって特に重要です。</span><span class="sxs-lookup"><span data-stu-id="2a4a2-115">Supply planning is especially important to businesses that are involved in wholesale activities, manufacturing, and assembly management.</span></span> <span data-ttu-id="2a4a2-116">これらのビジネスをサポートするために、Business Central では、実際と予測の需要および可用性と、リード タイム、再発注ポイントと安全在庫ポイント、最小数量と最大数量などの各種計画パラメーターに基づいて、在庫の補充に関する最適な提案を生成できます。</span><span class="sxs-lookup"><span data-stu-id="2a4a2-116">To support these businesses, Business Central can generate optimal suggestions for replenishing inventory based on actual and forecasted demand and availability, as well as a variety of planning parameters such as lead times, reorder and safe stock points, and minimum and maximum quantities.</span></span> <span data-ttu-id="2a4a2-117">これらの高度な供給計画機能は、より広く利用できるように、Essentials エクスペリエンスにも含まれるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2a4a2-117">To make these advanced supply planning capabilities more widely available, they are now included in the Essentials experience.</span></span> 
<!-- bv end -->


## <a name="feature-details"></a><span data-ttu-id="2a4a2-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2a4a2-118">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="2a4a2-119">Essentials エクスペリエンスでは、**製造設定**ページで会社のプロセスに合わせて計画エンジンを構成できます。</span><span class="sxs-lookup"><span data-stu-id="2a4a2-119">In the Essentials experience, you can configure the planning engine to fit your company processes on the **Manufacturing Setup** page.</span></span> <span data-ttu-id="2a4a2-120">たとえば、複数の場所の計画、MPS/MRP パラメーターの同時計算を設定し、各種既定値を指定します。</span><span class="sxs-lookup"><span data-stu-id="2a4a2-120">For example, set up planning for multiple locations, simultaneous calculation of MPS/MRP parameters, specify various defaults.</span></span> 
<!--feature detail end -->

<span data-ttu-id="2a4a2-121">![製造設定](media/manufacturingsetup.png "製造設定")</span><span class="sxs-lookup"><span data-stu-id="2a4a2-121">![Manufacturing Setup](media/manufacturingsetup.png "Manufacturing Setup")</span></span>
<!-- Picture 1 -->








## <a name="thank-you-for-your-idea"></a><span data-ttu-id="2a4a2-122">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="2a4a2-122">Thank you for your idea</span></span>
<span data-ttu-id="2a4a2-123">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=7d246dbd-6d38-ea11-8454-0003ff68a0ea)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="2a4a2-123">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=7d246dbd-6d38-ea11-8454-0003ff68a0ea).</span></span> <span data-ttu-id="2a4a2-124">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="2a4a2-124">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="2a4a2-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="2a4a2-125">See also</span></span>

<!--docs start-->
<span data-ttu-id="2a4a2-126">[計画](https://docs.microsoft.com/dynamics365/business-central/production-planning) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="2a4a2-126">[Planning](https://docs.microsoft.com/dynamics365/business-central/production-planning) (docs)</span></span>
<!--docs end-->
