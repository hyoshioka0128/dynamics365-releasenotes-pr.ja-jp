---
title: '[営業案件のクローズ] ダイアログ ボックスのカスタマイズ'
description: この機能強化により、営業案件クローズという重要なステップのために製品をさらにカスタマイズすることができます。 [営業案件のクローズ] ダイアログ ボックスは、組織固有のビジネス ニーズに基づいてカスタマイズできます。
author: relnotes
ms.reviewer: shujoshi
ms.date: 09/09/2019
ms.assetid: ce61278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pachatte
dynamics365pdf: true
ms.openlocfilehash: 061a02bf630eceb9477dbbc0a380d2a321748d62
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143481"
---
# <a name="customization-of-opportunity-close-dialog-box"></a><span data-ttu-id="e3984-104">[営業案件のクローズ] ダイアログ ボックスのカスタマイズ</span><span class="sxs-lookup"><span data-stu-id="e3984-104">Customization of Opportunity Close dialog box</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="e3984-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="e3984-105">Enabled for</span></span>    |  <span data-ttu-id="e3984-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e3984-106">Public preview</span></span> | <span data-ttu-id="e3984-107">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="e3984-107">Early access</span></span> | <span data-ttu-id="e3984-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="e3984-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="e3984-109">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="e3984-109">Users by admins, makers, or analysts</span></span>|-|<span data-ttu-id="e3984-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e3984-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e3984-111">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="e3984-111">Aug 1, 2019</span></span>| <span data-ttu-id="e3984-112">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="e3984-112">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="e3984-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e3984-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e3984-114">顧客から最も多い要望です。</span><span class="sxs-lookup"><span data-stu-id="e3984-114">A top request by customers.</span></span> 

<span data-ttu-id="e3984-115">営業案件をクローズするときに、企業は過去の損失や成功を踏まえるため、または成約率を向上させるための新しい戦略を試すために、営業案件を失注または受注した理由を理解する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e3984-115">When closing an opportunity, businesses often need to understand why the opportunity was lost or won to build upon past losses and successes or to try new strategies for improving win rates.</span></span> <span data-ttu-id="e3984-116">[営業案件のクローズ] ダイアログ ボックスのカスタマイズをサポートすることで、Dynamics 365 Sales は企業が戦略的な営業イニシアチブに基づいて成約/獲得の詳細を収集することを支援します。</span><span class="sxs-lookup"><span data-stu-id="e3984-116">By supporting customization of the Opportunity Close dialog box, Dynamics 365 Sales helps companies capture close/win details based on their strategic sales initiatives.</span></span> <span data-ttu-id="e3984-117">さらに、営業マネージャーは、どの競合他社が失注する傾向があるか、または何が受注の成功につながったのかを確認できます。</span><span class="sxs-lookup"><span data-stu-id="e3984-117">Furthermore, sales managers can see which competitors are trending in losses, or what drove success in wins.</span></span> <span data-ttu-id="e3984-118">この情報は、マネージャーが業績の良い製品やサービスを特定し、将来の製品やサービスの戦略を形成するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="e3984-118">This information helps managers identify products and services that are performing well, to form future product and service strategies.</span></span> <span data-ttu-id="e3984-119">さらに、収集されたデータは分析や機械学習モデルにメリットをもたらし、将来の営業案件がクローズする可能性を予測するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="e3984-119">In addition, the data captured can benefit analysis and machine learning models, helping to predict the likelihood of future opportunities to close.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e3984-120">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e3984-120">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="e3984-121">管理者は、[利益率] や [受注商品] などのフィールドを、営業案件エンティティの [受注としてクローズ] フォーム/ダイアログ ボックスに追加できます。</span><span class="sxs-lookup"><span data-stu-id="e3984-121">Administrators can add fields such as Profit Margin or Winning Product in the Close as Won form/dialog box of the Opportunity entity.</span></span> 
- <span data-ttu-id="e3984-122">管理者は、[競争優位性] などのフィールドを、営業案件エンティティの [失注としてクローズ] フォーム/ダイアログ ボックスに追加できます。</span><span class="sxs-lookup"><span data-stu-id="e3984-122">Administrators can add fields such as Competitive Advantage in the Close as Lost form/dialog box of the Opportunity entity.</span></span> 
- <span data-ttu-id="e3984-123">管理者は、新しいクライアント側ビジネス検証を導入したり、既存の検証を削除したりできます。</span><span class="sxs-lookup"><span data-stu-id="e3984-123">Administrators can introduce new client-side business validations or remove existing ones.</span></span> 
- <span data-ttu-id="e3984-124">管理者は、営業案件のクローズ エンティティをカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="e3984-124">Administrators can customize the Opportunity Close entity.</span></span> 
- <span data-ttu-id="e3984-125">管理者は、カスタマイズ不可能なモーダル ダイアログ エクスペリエンス (既定の設定) またはカスタマイズ可能なフォーム エクスペリエンスを選択できます。</span><span class="sxs-lookup"><span data-stu-id="e3984-125">Administrators can choose between the non-customizable modal dialog experience (default setting) and the customizable form experience.</span></span> 
- <span data-ttu-id="e3984-126">営業担当者は、デスクトップまたはモバイル アプリで営業案件をクローズし、営業案件のクローズに関して組織が必要とする関連詳細情報を提供することができます。</span><span class="sxs-lookup"><span data-stu-id="e3984-126">Sales reps can close an opportunity via the desktop or mobile app and provide relevant details required by their organization for closing the opportunity.</span></span>
<!--feature detail end -->

<span data-ttu-id="e3984-127">![営業案件のクローズ](media/opportunity-close.jpg "営業案件のクローズ")</span><span class="sxs-lookup"><span data-stu-id="e3984-127">![Opportunity Close](media/opportunity-close.jpg "Opportunity Close")</span></span>
<!-- Picture 1 -->

> [!NOTE]
> <span data-ttu-id="e3984-128">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="e3984-128">This feature is available in the Unified Interface only.</span></span>








## <a name="thank-you-for-your-idea"></a><span data-ttu-id="e3984-129">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="e3984-129">Thank you for your idea</span></span>
<span data-ttu-id="e3984-130">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=4792dfee-121a-e611-80e2-c4346badc228)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="e3984-130">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=4792dfee-121a-e611-80e2-c4346badc228).</span></span> <span data-ttu-id="e3984-131">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="e3984-131">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="e3984-132">関連項目</span><span class="sxs-lookup"><span data-stu-id="e3984-132">See also</span></span>

<span data-ttu-id="e3984-133">[営業案件クローズ フォームのカスタマイズ](https://docs.microsoft.com/dynamics365/customer-engagement/sales-enterprise/customize-opportunity-close-experience) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="e3984-133">[Customize the Opportunity Close form](https://docs.microsoft.com/dynamics365/customer-engagement/sales-enterprise/customize-opportunity-close-experience) (docs)</span></span>
