---
title: インテリジェント キューの効果的な使用
description: 優先順位付けされた作業キューにより、営業担当者は次に最善の見込み顧客、コンバージョンの可能性が高い顧客、および成約する可能性が高い営業案件を特定できます。
author: relnotes
ms.reviewer: shujoshi
ms.date: 02/14/2020
ms.assetid: 9623e711-58cb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: efgilboa
dynamics365pdf: true
ms.openlocfilehash: 7cd3f561ef8819cd7be5d87cb24b9b57dc980ce6
ms.sourcegitcommit: 5164b04916273ffd769ce37c79b1fd63ce1bf937
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/24/2020
ms.locfileid: "3081939"
---
# <a name="work-effectively-with-an-intelligent-queue"></a><span data-ttu-id="9f05b-103">インテリジェント キューの効果的な使用</span><span class="sxs-lookup"><span data-stu-id="9f05b-103">Work effectively with an intelligent queue</span></span>
[!include[artificial-intelligence/dynamics365-sales-insights banner](../includes/artificial-intelligence/dynamics365-sales-insights.md)]

| <span data-ttu-id="9f05b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9f05b-104">Enabled for</span></span>    |  <span data-ttu-id="9f05b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9f05b-105">Public preview</span></span> | <span data-ttu-id="9f05b-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="9f05b-106">Early access</span></span> | <span data-ttu-id="9f05b-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="9f05b-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="9f05b-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="9f05b-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="9f05b-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="9f05b-109">Apr 2020</span></span>|-| -|


## <a name="business-value"></a><span data-ttu-id="9f05b-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9f05b-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9f05b-111">内部販売担当者は、1 日の売上予算を達成するために効率的に作業する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9f05b-111">Inside sellers need to work efficiently to meet their daily quota.</span></span> <span data-ttu-id="9f05b-112">このために、かなりの時間を費やして潜在顧客の長いリストを探索しています。</span><span class="sxs-lookup"><span data-stu-id="9f05b-112">To do this, they spend significant time exploring long lists of potential customers.</span></span> <span data-ttu-id="9f05b-113">営業の加速により、内部販売担当者は、最善の潜在顧客または最も成約が近い営業案件に対応していることを確信できます。</span><span class="sxs-lookup"><span data-stu-id="9f05b-113">With Sales Acceleration, inside sellers can trust that they are handling the lead or opportunity that is most likely to qualify or close successfully.</span></span> <span data-ttu-id="9f05b-114">関連情報に即時にアクセスできるため、すべてのコミュニケーションをより効果的にするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="9f05b-114">Immediate access to relevant information helps to make every communication more effective.</span></span> 

<span data-ttu-id="9f05b-115">営業の加速は、複数の分析コードを網羅する柔軟性を提供し、即時のニーズを満たすようにインテリジェント キューの順序を調整します。</span><span class="sxs-lookup"><span data-stu-id="9f05b-115">Sales Acceleration offers flexibility across multiple dimensions, tailoring the order of the intelligent queue to meet immediate needs.</span></span> <span data-ttu-id="9f05b-116">複数の属性でフィルター、並べ替え、またはグループ化が可能であるため、販売担当者は特定のニーズに該当する関連する顧客、つまりソーシャル メディアにより、すべての顧客にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="9f05b-116">Being able to filter, sort, or group by multiple attributes quickly empowers inside sellers to reach relevant customers, applicable to a specific need—that is, reach out to all customers from social media.</span></span> 

<span data-ttu-id="9f05b-117">内部販売担当者が次に最善の顧客を見逃さないように、リードが製品またはサービスに対して最近に関心を示したことでその新しいリードがキューに入るたびに、通知が送信されます。</span><span class="sxs-lookup"><span data-stu-id="9f05b-117">To ensure inside sellers never miss the next best customer, notifications are sent whenever a new prospect enters the queue—because that prospect expressed the most recent interest in your product or service.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9f05b-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9f05b-118">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="9f05b-119">**優先順位付けされた顧客リストのメリット**: 優先順位付けされた作業キューにより、次に最善のリード、コンバージョンの可能性が高い顧客、成約が近い営業案件を特定できます。</span><span class="sxs-lookup"><span data-stu-id="9f05b-119">**Benefit from a prioritized list of customers**: With a prioritized work queue, identify the next best lead, customers likely to convert, and opportunities likely to close as won.</span></span> <span data-ttu-id="9f05b-120">インテリジェント キューは、割り当て済み顧客の並べ替え済みリストと、関連付けられている次のタスクの期限を示します。</span><span class="sxs-lookup"><span data-stu-id="9f05b-120">The intelligent queue surfaces a sorted list of assigned customers with associated next tasks due.</span></span> <span data-ttu-id="9f05b-121">このキューは、販売スタジオで作成された定義に基づいて編成されます。</span><span class="sxs-lookup"><span data-stu-id="9f05b-121">The queue is organized based on definitions made in Sales Studio.</span></span> <span data-ttu-id="9f05b-122">既定の並べ替えは、複合スコアに基づいており、組織の営業リズムに基づいて次に最適なアクションを提示します。</span><span class="sxs-lookup"><span data-stu-id="9f05b-122">Default sorting is based on a composite scoring, presenting the next best action based on organizational sales cadences.</span></span>
- <span data-ttu-id="9f05b-123">**特定のニーズを満たすようにインテリジェント キューを調整する**: 特定のソースまたは地域からの顧客への連絡、特定の製品オファリングに関心のある顧客への連絡など、特定のニーズを満たすために、エンティティ属性 (メイン フィールド) で並べ替え、フィルター、またはグループ化を行います。</span><span class="sxs-lookup"><span data-stu-id="9f05b-123">**Tailor the intelligent queue to meet specific needs**: Sort, filter, or group by entity attributes (main fields) to meet specific needs like reaching out to customers from a specific source or geography, or reaching out to customers interested in a specific product offering.</span></span>
- <span data-ttu-id="9f05b-124">**オンライン通知の受信**: 新しいリードまたは営業案件がインテリジェント キューに入るか、再割り当てされるたびに通知されるため、見逃しを回避できます。</span><span class="sxs-lookup"><span data-stu-id="9f05b-124">**Receive online notification**: Get notified whenever a new lead or opportunity enters the intelligent queue or is reassigned to you, so nothing falls between the cracks.</span></span>

<!--feature detail end -->

<!--
![Work queue](media/work-queue-form.png "Work queue") -->
<!-- Picture 1 -->

> [!NOTE]
> <span data-ttu-id="9f05b-125">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="9f05b-125">This feature is available in the Unified Interface only.</span></span>






