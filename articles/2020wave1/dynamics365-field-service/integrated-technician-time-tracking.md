---
title: 統合された技術者の時間追跡
description: 統合された技術者の時間追跡
author: relnotes
ms.reviewer: krbjoran
ms.date: 04/20/2020
ms.assetid: 65137991-b7ca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: jacoh
dynamics365pdf: true
ms.openlocfilehash: a742b0c185656ebbdc5279718dfac6c122827505
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294052"
---
# <a name="integrated-technician-time-tracking"></a><span data-ttu-id="9cc90-103">統合された技術者の時間追跡</span><span class="sxs-lookup"><span data-stu-id="9cc90-103">Integrated technician time tracking</span></span>


| <span data-ttu-id="9cc90-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9cc90-104">Enabled for</span></span>    |  <span data-ttu-id="9cc90-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9cc90-105">Public preview</span></span> | <span data-ttu-id="9cc90-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="9cc90-106">Early access</span></span> | <span data-ttu-id="9cc90-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="9cc90-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="9cc90-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="9cc90-108">End users, automatically</span></span>|-|<span data-ttu-id="9cc90-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9cc90-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9cc90-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="9cc90-110">Feb 3, 2020</span></span>| <span data-ttu-id="9cc90-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9cc90-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9cc90-112">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="9cc90-112">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="9cc90-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9cc90-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9cc90-114">Dynamics 365 Field Service で簡単に表示して編集できる形式で時間をキャプチャすることは、多くの Field Service 組織にとってコストと収益を正確に記録するために必要なことです。</span><span class="sxs-lookup"><span data-stu-id="9cc90-114">Capturing time in an easily viewable and editable format within Dynamics 365 Field Service is needed by many Field Service organizations to accurately record cost and revenue.</span></span> <span data-ttu-id="9cc90-115">お客様は、Field Service で技術者の時間を追跡できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="9cc90-115">Customers can now track technician time in Field Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9cc90-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9cc90-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9cc90-117">Field Service の時間エントリでは、Dynamics 365 Project Service Automation と連携して、組織が Field Service、Project Service Automation、またはその両方を使用するかどうかに関わらず、Project Service Automation が一貫したキャプチャに使用する同じエンティティに、時間エントリがキャプチャされます。</span><span class="sxs-lookup"><span data-stu-id="9cc90-117">Field Service time entry aligns with Dynamics 365 Project Service Automation to capture time entries into the same entity that Project Service Automation has used for consistent capture, regardless of whether your organization uses Field Service, Project Service Automation, or both.</span></span>

<span data-ttu-id="9cc90-118">お客様は、Field Service の時間エントリをキャプチャするためだけに Project Service Automation をインストールする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="9cc90-118">Customers will not be required to install Project Service Automation simply to capture time entries within Field Service.</span></span> 

<span data-ttu-id="9cc90-119">Field Service では以下がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="9cc90-119">Field Service will support:</span></span>

- <span data-ttu-id="9cc90-120">予約タイムスタンプに基づく作業指示書の自動時間キャプチャ。</span><span class="sxs-lookup"><span data-stu-id="9cc90-120">Automatic time capture for work orders based on booking timestamps.</span></span>
- <span data-ttu-id="9cc90-121">手動時間キャプチャ。</span><span class="sxs-lookup"><span data-stu-id="9cc90-121">Manual time capture.</span></span>
- <span data-ttu-id="9cc90-122">特定の業務プロセスやニーズに固有のカスタム時間キャプチャのメカニズム。</span><span class="sxs-lookup"><span data-stu-id="9cc90-122">Custom time capture mechanisms unique to specific business processes or needs.</span></span>

<span data-ttu-id="9cc90-123">この機能では、承認された時間エントリからコストをキャプチャする時間実績をキャプチャできます。これにより組織はより正確な会計実務と損益計算を推進できます。</span><span class="sxs-lookup"><span data-stu-id="9cc90-123">This feature enbles you to capture time actuals that capture costs from approved time entries, enabling organizations to drive more accurate accounting practices and profit-loss calculations.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="9cc90-124">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="9cc90-124">This feature is available in the Unified Interface only.</span></span>







## <a name="see-also"></a><span data-ttu-id="9cc90-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="9cc90-125">See also</span></span>

<!--docs start-->
<span data-ttu-id="9cc90-126">[Dynamics 365 Field Service の時間エントリ](https://docs.microsoft.com/dynamics365/field-service/field-service-time-entry) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="9cc90-126">[Time entries for Dynamics 365 Field Service](https://docs.microsoft.com/dynamics365/field-service/field-service-time-entry) (docs)</span></span>
<!--docs end-->
