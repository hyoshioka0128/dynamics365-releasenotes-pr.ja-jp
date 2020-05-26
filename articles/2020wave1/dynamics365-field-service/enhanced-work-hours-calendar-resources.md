---
title: 強化されたリソースの作業時間カレンダー
description: 作業カレンダー管理のユーザー エクスペリエンスの向上
author: relnotes
ms.reviewer: krbjoran
ms.date: 04/20/2020
ms.assetid: d51c9ef4-0b1e-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: sampatn
dynamics365pdf: true
ms.openlocfilehash: adc8495e2a2bf74edf79db0ceea53dc330b5ba95
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294096"
---
# <a name="enhanced-work-hours-calendar-for-resources"></a><span data-ttu-id="bb577-103">強化されたリソースの作業時間カレンダー</span><span class="sxs-lookup"><span data-stu-id="bb577-103">Enhanced work hours calendar for resources</span></span>


| <span data-ttu-id="bb577-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="bb577-104">Enabled for</span></span>    |  <span data-ttu-id="bb577-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="bb577-105">Public preview</span></span> | <span data-ttu-id="bb577-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="bb577-106">Early access</span></span> | <span data-ttu-id="bb577-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="bb577-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="bb577-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="bb577-108">End users, automatically</span></span>|-|<span data-ttu-id="bb577-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="bb577-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="bb577-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="bb577-110">Feb 3, 2020</span></span>| <span data-ttu-id="bb577-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="bb577-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="bb577-112">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="bb577-112">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="bb577-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="bb577-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="bb577-114">リソースの空き時間の管理は、ビジネスのサービス運用の効率性における重要な要素です。</span><span class="sxs-lookup"><span data-stu-id="bb577-114">Managing resource availability is a key factor in the efficiency of a business's service operation.</span></span> <span data-ttu-id="bb577-115">この機能強化により、ユーザー エクスペリエンスが向上し、勤務時間と休暇の管理が容易になります。</span><span class="sxs-lookup"><span data-stu-id="bb577-115">This enhancement improves the user experience, making it easier to manage work hours and time off.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="bb577-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="bb577-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="bb577-117">現在、リソース マネージャーはリソースのカレンダーにより、勤務時間と休暇を設定しています。</span><span class="sxs-lookup"><span data-stu-id="bb577-117">Resource managers currently set resources' calendars, establishing work hours and time off.</span></span> <span data-ttu-id="bb577-118">今回、勤務時間を管理するための新しいシンプルなエクスペリエンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="bb577-118">This is a new and simplified experience for maintaining working hours.</span></span> <span data-ttu-id="bb577-119">このエクスペリエンスはアクセス可能で、統一インターフェイスのエクスペリエンスとの一貫性があります。</span><span class="sxs-lookup"><span data-stu-id="bb577-119">The experience is accessible and consistent with Unified Interface experiences.</span></span> <span data-ttu-id="bb577-120">さらに、カレンダー コントロールは、Power Apps component framework コントロールになります。これは、パートナーや顧客がキャンバス アプリなどの外部エンティティ フォームやビューからリソースの作業時間を変更するシナリオに対応できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="bb577-120">Additionally, the calendar control will be a Power Apps component framework control, meaning that partners and customers can enable scenarios to modify resources' working hours from outside entity forms and views, like with a canvas app.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="bb577-121">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="bb577-121">This feature is available in the Unified Interface only.</span></span>







## <a name="see-also"></a><span data-ttu-id="bb577-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="bb577-122">See also</span></span>

<!--docs start-->
<span data-ttu-id="bb577-123">[作業時間の追加](https://docs.microsoft.com/dynamics365/field-service/set-up-bookable-resources#add-work-hours) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="bb577-123">[Add work hours](https://docs.microsoft.com/dynamics365/field-service/set-up-bookable-resources#add-work-hours) (docs)</span></span>
<!--docs end-->
