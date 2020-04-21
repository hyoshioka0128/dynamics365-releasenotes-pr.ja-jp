---
title: かんばんビューで営業案件を処理する
description: 販売担当者は、良好な顧客リレーションシップの構築と取引の受注に時間を集中したいと考えています。 また、関連する情報へのアクセスを迅速に提供しながら、日常的なタスクを迅速かつ直感的に完了するのに役立つツールを求めています。
author: relnotes
ms.reviewer: shujoshi
ms.date: 02/04/2020
ms.assetid: 0944bedf-e321-ea11-a810-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: cindyliu
dynamics365pdf: true
ms.openlocfilehash: 4b7ca9107aed083f1405416541bf80784c7a54f5
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232332"
---
# <a name="work-with-opportunities-in-the-kanban-view"></a><span data-ttu-id="9cb7d-104">かんばんビューで営業案件を処理する</span><span class="sxs-lookup"><span data-stu-id="9cb7d-104">Work with opportunities in the Kanban view</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="9cb7d-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="9cb7d-105">Enabled for</span></span>    |  <span data-ttu-id="9cb7d-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9cb7d-106">Public preview</span></span> | <span data-ttu-id="9cb7d-107">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="9cb7d-107">Early access</span></span> | <span data-ttu-id="9cb7d-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="9cb7d-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="9cb7d-109">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="9cb7d-109">End users, automatically</span></span>|-|<span data-ttu-id="9cb7d-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9cb7d-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9cb7d-111">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="9cb7d-111">Feb 3, 2020</span></span>| <span data-ttu-id="9cb7d-112">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="9cb7d-112">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="9cb7d-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9cb7d-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9cb7d-114">Dynamics 365 Sales をより良く、より簡単かつ効率的にする方法について、お客様からのご意見に積極的に耳を傾けています。</span><span class="sxs-lookup"><span data-stu-id="9cb7d-114">We are actively listening to our customers to learn how we can make Dynamics 365 Sales better, easier, and more efficient.</span></span> <span data-ttu-id="9cb7d-115">Dynamics 365 Sales は、販売担当者がより深いリレーションシップを構築し、生産性を向上できるように支援することを目的としています。</span><span class="sxs-lookup"><span data-stu-id="9cb7d-115">Dynamics 365 Sales aims to help sellers develop deeper relationships and improve their productivity.</span></span> 

<span data-ttu-id="9cb7d-116">Dynamics 365 Sales を向上させるための取り組みの一環として、不要なストレスを取り除き、機能をより使いやすいものにする機能強化を継続的に導入しています。</span><span class="sxs-lookup"><span data-stu-id="9cb7d-116">As part of our commitment to make Dynamics 365 Sales better, we are continually introducing enhancements that remove unnecessary friction and make features easier to use.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9cb7d-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9cb7d-117">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="9cb7d-118">既存のグリッド ビューと新しいかんばんビューを簡単に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="9cb7d-118">Easily toggle between the existing grid view and the new Kanban view.</span></span>
- <span data-ttu-id="9cb7d-119">販売担当者は、かんばんボードで販売パスごとに営業案件パイプラインを表示できます。</span><span class="sxs-lookup"><span data-stu-id="9cb7d-119">Sellers can view their opportunity pipeline by sales path on the Kanban board.</span></span> 
- <span data-ttu-id="9cb7d-120">営業案件を別のステージに移動するための簡素化された直感的なエクスペリエンス。</span><span class="sxs-lookup"><span data-stu-id="9cb7d-120">Simplified and intuitive experience to move opportunities into a different stage.</span></span> <span data-ttu-id="9cb7d-121">かんばんビューを使用すると、営業チームはドラッグするだけで営業案件をあるステージから別のステージに移動できます。</span><span class="sxs-lookup"><span data-stu-id="9cb7d-121">The Kanban view allows your sales team to move opportunities from one stage to another by simply dragging them.</span></span>
<!--feature detail end -->

<span data-ttu-id="9cb7d-122">![Teams](media/microsoftteams-image.png "Teams")</span><span class="sxs-lookup"><span data-stu-id="9cb7d-122">![Teams](media/microsoftteams-image.png "Teams")</span></span>
<!-- Picture 1 -->

> [!NOTE]
> <span data-ttu-id="9cb7d-123">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="9cb7d-123">This feature is available in the Unified Interface only.</span></span> 
>
> <span data-ttu-id="9cb7d-124">この機能は、Dynamics 365 Sales Enterprise と Dynamics 365 Sales Professional で使用できます。</span><span class="sxs-lookup"><span data-stu-id="9cb7d-124">This capability is available in Dynamics 365 Sales Enterprise and Dynamics 365 Sales Professional.</span></span>







## <a name="see-also"></a><span data-ttu-id="9cb7d-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="9cb7d-125">See also</span></span>


<!--docs start-->
<span data-ttu-id="9cb7d-126">[かんばんビューで営業案件を処理する](https://docs.microsoft.com/dynamics365/sales-enterprise/opportunity-kanban-view) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="9cb7d-126">[Work with opportunities in the Kanban view](https://docs.microsoft.com/dynamics365/sales-enterprise/opportunity-kanban-view) (docs)</span></span>
<!--docs end-->

