---
title: 統合された技術者の時間追跡
description: 統合された技術者の時間追跡
author: relnotes
ms.reviewer: krbjoran
ms.date: 02/17/2020
ms.assetid: 65137991-b7ca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: jacoh
dynamics365pdf: true
ms.openlocfilehash: c2a7d060cb978cbb6d6100da706ff04fe7961998
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232111"
---
# <a name="integrated-technician-time-tracking"></a><span data-ttu-id="91445-103">統合された技術者の時間追跡</span><span class="sxs-lookup"><span data-stu-id="91445-103">Integrated technician time tracking</span></span>
[!include[dynamics365-field-service banner](../includes/dynamics365-field-service.md)]

| <span data-ttu-id="91445-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="91445-104">Enabled for</span></span>    |  <span data-ttu-id="91445-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="91445-105">Public preview</span></span> | <span data-ttu-id="91445-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="91445-106">Early access</span></span> | <span data-ttu-id="91445-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="91445-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="91445-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="91445-108">End users, automatically</span></span>|-|<span data-ttu-id="91445-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="91445-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="91445-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="91445-110">Feb 3, 2020</span></span>| <span data-ttu-id="91445-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="91445-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="91445-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="91445-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="91445-113">Dynamics 365 Field Service で簡単に表示して編集できる形式で時間をキャプチャすることは、多くの Field Service 組織にとってコストと収益を正確に記録するために必要なことです。</span><span class="sxs-lookup"><span data-stu-id="91445-113">Capturing time in an easily viewable and editable format within Dynamics 365 Field Service is needed by many Field Service organizations to accurately record cost and revenue.</span></span> <span data-ttu-id="91445-114">お客様は、Field Service で技術者の時間を追跡できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="91445-114">Customers can now track technician time in Field Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="91445-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="91445-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="91445-116">Field Service の時間エントリでは、Dynamics 365 Project Service Automation と連携して、組織が Field Service、Project Service Automation、またはその両方を使用するかどうかに関わらず、Project Service Automation が一貫したキャプチャに使用する同じエンティティに、時間エントリがキャプチャされます。</span><span class="sxs-lookup"><span data-stu-id="91445-116">Field Service time entry aligns with Dynamics 365 Project Service Automation to capture time entries into the same entity that Project Service Automation has used for consistent capture, regardless of whether your organization uses Field Service, Project Service Automation, or both.</span></span>

<span data-ttu-id="91445-117">お客様は、Field Service の時間エントリをキャプチャするためだけに Project Service Automation をインストールする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="91445-117">Customers will not be required to install Project Service Automation simply to capture time entries within Field Service.</span></span> 

<span data-ttu-id="91445-118">Field Service では以下がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="91445-118">Field Service will support:</span></span>

- <span data-ttu-id="91445-119">予約タイムスタンプに基づく作業指示書の自動時間キャプチャ。</span><span class="sxs-lookup"><span data-stu-id="91445-119">Automatic time capture for work orders based on booking timestamps.</span></span>
- <span data-ttu-id="91445-120">手動時間キャプチャ。</span><span class="sxs-lookup"><span data-stu-id="91445-120">Manual time capture.</span></span>
- <span data-ttu-id="91445-121">特定の業務プロセスやニーズに固有のカスタム時間キャプチャのメカニズム。</span><span class="sxs-lookup"><span data-stu-id="91445-121">Custom time capture mechanisms unique to specific business processes or needs.</span></span>

<span data-ttu-id="91445-122">この機能では、承認された時間エントリからコストをキャプチャする時間実績をキャプチャできます。これにより組織はより正確な会計実務と損益計算を推進できます。</span><span class="sxs-lookup"><span data-stu-id="91445-122">This feature enbles you to capture time actuals that capture costs from approved time entries, enabling organizations to drive more accurate accounting practices and profit-loss calculations.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="91445-123">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="91445-123">This feature is available in the Unified Interface only.</span></span>







## <a name="see-also"></a><span data-ttu-id="91445-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="91445-124">See also</span></span>


<!--docs start-->
<span data-ttu-id="91445-125">[Dynamics 365 Field Service の時間エントリ](https://docs.microsoft.com/dynamics365/field-service/field-service-time-entry) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="91445-125">[Time entries for Dynamics 365 Field Service](https://docs.microsoft.com/dynamics365/field-service/field-service-time-entry) (docs)</span></span>
<!--docs end-->

