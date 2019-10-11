---
redirect_url: ../change-history#dynamics-365-for-retail
title: 空間主導の分析情報によるインテリジェント ストア
description: 空間主導の分析情報によるインテリジェント ストア
author: anpurush
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: a9e58046-746b-e911-a95f-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: anpurush
dynamics365pdf: true
ms.openlocfilehash: d283a63dcc996bda97032fad7bd7cc32c77e94cf
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141901"
---
# <a name="intelligent-stores-through-spatial-driven-insights"></a><span data-ttu-id="8b633-103">空間主導の分析情報によるインテリジェント ストア</span><span class="sxs-lookup"><span data-stu-id="8b633-103">Intelligent stores through spatial-driven insights</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="8b633-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8b633-104">Enabled for</span></span>    |  <span data-ttu-id="8b633-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8b633-105">Public preview</span></span> | <span data-ttu-id="8b633-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8b633-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="8b633-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="8b633-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="8b633-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="8b633-108">October 2019</span></span>| <span data-ttu-id="8b633-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="8b633-109">January 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="8b633-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8b633-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8b633-111">今日の小売業者は、デジタル プラットフォームで収集されたデータを A/B テスト、クリックスルー分析、破棄されたカート情報などを使用して分析することで、分析情報を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="8b633-111">Retailers today can derive insights from data collected and analyzed on digital platforms by using A/B testing, click-through analysis, abandoned carts information, and so on.</span></span> <span data-ttu-id="8b633-112">この分析は、小売業者がオンラインの行動パターンを見つけるのに役立ち、消費者のエクスペリエンスをパーソナライズするのに役立つ場合があります。</span><span class="sxs-lookup"><span data-stu-id="8b633-112">This analysis helps retailers find online behavioral patterns, which can help them to personalize consumer experiences.</span></span> 

<span data-ttu-id="8b633-113">ただし、現実の世界から分析情報を得るとなると、高度さのレベルはオンラインと同じではありません。</span><span class="sxs-lookup"><span data-stu-id="8b633-113">However, when it comes to gaining insights from the physical world, the level of sophistication is not the same as online.</span></span> <span data-ttu-id="8b633-114">空間データに関して物理的世界からの信号をオーバーレイし、それをトランザクション データに関連付けて分析情報と成功する行動を導き出すソリューションは多くありません。</span><span class="sxs-lookup"><span data-stu-id="8b633-114">There are not many solutions that overlay signals from the physical world in terms of spatial data and co-relate that to transactional data to derive insights and successful actions.</span></span> <span data-ttu-id="8b633-115">この機能を使用すると、小売業者は空間データとトランザクション データをオーバーレイすることができ、損失防止、客足分析、滞留時間分析、実験などのユース ケースに関する分析情報をマイニングできます。</span><span class="sxs-lookup"><span data-stu-id="8b633-115">This feature will allow retailers to overlay spatial data with transactional data, enabling them to mine insights for use cases like loss prevention, foot traffic analysis, dwell time analysis, and experimentation.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8b633-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8b633-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8b633-117">この機能では、小売業者の以下のユース ケースが可能になります。</span><span class="sxs-lookup"><span data-stu-id="8b633-117">This feature will enable the following use cases for retailers:</span></span>

- <span data-ttu-id="8b633-118">**損失防止分析**: 2017 会計年度に、小売業者は小売店での盗難や窃盗のために 420 億ドルの損失を被りました。</span><span class="sxs-lookup"><span data-stu-id="8b633-118">**Loss prevention analysis**: In fiscal year 2017, retailers suffered losses worth $42 billion due to theft and pilferages in retail stores.</span></span> <span data-ttu-id="8b633-119">このうち、米国は 420 億ドルを占めています。</span><span class="sxs-lookup"><span data-stu-id="8b633-119">Of this, the United States accounted for $42 billion.</span></span> <span data-ttu-id="8b633-120">非常に競争が激しく薄利の環境では、これらの損失は小売業者の収益性に大きな影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="8b633-120">In a highly competitive and wafer-thin margin environment, these losses cause a significant dent in a retailer’s profitability.</span></span> <span data-ttu-id="8b633-121">現在、Dynamics 365 では、小売業の顧客が直面しているこの長年の問題に対する実際のソリューションは提供されていません。</span><span class="sxs-lookup"><span data-stu-id="8b633-121">Currently, Dynamics 365 does not offer any real solutions to this perennial problem faced by its retail customers.</span></span> 

  <span data-ttu-id="8b633-122">Dynamics 365 Loss Prevention Analytics 機能では、従業員の盗難による窃盗と返済に焦点が当てられています。</span><span class="sxs-lookup"><span data-stu-id="8b633-122">The Dynamics 365 Loss Prevention Analytics feature will focus on pilferages due to employee theft and returns.</span></span> <span data-ttu-id="8b633-123">この機能は、ファースト パーティのデバイスと小売店の既存のカメラ インフラストラクチャを使用したファースト パーティとサード パーティのビデオ フィード ソリューションによって補完されます。</span><span class="sxs-lookup"><span data-stu-id="8b633-123">This feature will be complemented by both first-party and third-party video feed solutions using first-party devices and the existing camera infrastructure in the retailer’s store.</span></span> <span data-ttu-id="8b633-124">この機能では、トランザクション データに関連付けられる埋め込みビデオ フィードを使用してトランザクション データに基づくレポートが作成されます。これは、小売業者が従業員の盗難や返済を調査および修正するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="8b633-124">The feature will create reports based on transaction data with embedded video feed that co-relates to the transaction data, which will help retailers to investigate and remediate employee theft and returns.</span></span> <span data-ttu-id="8b633-125">大量のトランザクションがある場合、この機能は小売業者がビデオ証拠によって裏付けられた関心のあるトランザクションに注目できるようにし、それによって意味のある方法で窃盗捜査にリソースを割り当てられるようにします。</span><span class="sxs-lookup"><span data-stu-id="8b633-125">Among the huge volume of transactions, this feature will allow retailers to focus on transactions of concern backed by video evidence, thereby allowing them to dedicate resources on pilferage investigations in a meaningful way.</span></span> <span data-ttu-id="8b633-126">現在、ほとんどのソリューションでは、監視対象を理解するためのトップダウン分析を備えていないビデオ監視機能、またはビデオ フィードで補完された結果を確認する機能を備えていないトップダウン ドリルスルー機能が提供されています。</span><span class="sxs-lookup"><span data-stu-id="8b633-126">Currently, most solutions either provide video surveillance without the top-down analysis to understand what to monitor or provide the top-down drill-through without the ability to confirm findings complemented by video feeds.</span></span>

- <span data-ttu-id="8b633-127">**店内分析**: 実際の店での顧客の行動に基づいて分析し、是正措置を講じることには問題があります。</span><span class="sxs-lookup"><span data-stu-id="8b633-127">**In-store analytics**: There is a void in analyzing and taking remedial action based on customer behavior at physical stores.</span></span> <span data-ttu-id="8b633-128">現在は、店舗での滞在時間と客足を把握するためにアプリケーションとデータが切り離されています。</span><span class="sxs-lookup"><span data-stu-id="8b633-128">At present, retailers have disjointed applications and data to understand dwell time and foot traffic in their stores.</span></span> <span data-ttu-id="8b633-129">この機能では、質問に答えるための小売店からの物理的な入力情報が Dynamics 365 に提供されます。</span><span class="sxs-lookup"><span data-stu-id="8b633-129">This feature will provide Dynamics 365 with physical inputs from retail stores to answer and address questions.</span></span> <span data-ttu-id="8b633-130">たとえば、顧客が店舗内の特定の部分に費やす時間、店内の客足が多い場所と少ない場所、店舗の特定の場所の滞在時間と販売の相関関係、客足が多い場所でプロモーションが行われているか、店内配置に基づいてどのようにプロモーションに影響を与えるか、などです。</span><span class="sxs-lookup"><span data-stu-id="8b633-130">For example, how much time customers spend in certain parts of the store, where there is high foot traffic versus low foot traffic in the store, how does dwell time in certain parts of the store co-relate with sales, are promotions placed in areas that attract high foot traffic, or how to impact promotions based on in-store placement.</span></span> 

  <span data-ttu-id="8b633-131">この機能は、ビデオ分析に基づき、実店舗での深い顧客体験と結び付けることができます。</span><span class="sxs-lookup"><span data-stu-id="8b633-131">This feature, based on video analysis, can stitch together an in-depth customer journey at physical stores.</span></span> <span data-ttu-id="8b633-132">この過程は、デジタル プラットフォームでの顧客の行動を理解することができる、デジタル プラットフォーム上の*クリック ストリーム分析*と同等です。</span><span class="sxs-lookup"><span data-stu-id="8b633-132">This journey is the equivalent of a *click stream analysis* on digital platforms, which allows digital platforms to understand customer behavior.</span></span> <span data-ttu-id="8b633-133">"客足/滞在時間/実験ワークスペース" により、この機能を使用することで小売業者は製品および販売促進分析を行って収益を増加させることができます。</span><span class="sxs-lookup"><span data-stu-id="8b633-133">Through a “foot traffic/dwell time/experimentation workspace,” this feature will enable retailers to increase revenue by product and promotional analysis.</span></span> <span data-ttu-id="8b633-134">ワークスペースを使用すると、店舗マネージャーはタイムライン ビューで自分の店のビデオ フィードにアクセスできるようになります。これには、高、中、低の客足/滞在時間を示す赤、黄、緑のカラー コードで表される客足または滞在時間データをオーバーレイできます。</span><span class="sxs-lookup"><span data-stu-id="8b633-134">Using the workspace, the feature will enable a store manager to have access to video feeds for their store on a timeline view, which can be overlaid with either foot traffic data or dwell time data that will be expressed as color codes of red, yellow, and green, indicating high, medium, or low foot traffic/dwell time.</span></span> <span data-ttu-id="8b633-135">この機能では、店舗レイアウトや店内の商品の配置をマッピングすることもでき、これに基づいて、客足/滞在時間を相互に関連付けて、商品の配置、プロモーションなどの効果を判断できます。</span><span class="sxs-lookup"><span data-stu-id="8b633-135">The feature will also have the ability to map the store layout and product placements in the store and, based on this, co-relate the foot traffic/dwell time to determine the effectiveness of product placements, promotions, and so on.</span></span>
<!--feature detail end -->











