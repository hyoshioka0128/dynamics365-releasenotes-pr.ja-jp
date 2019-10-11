---
title: 会話インテリジェンスでの販売担当者コーチングの改善
description: 2019 年 4 月の時点で、営業マネージャーは販売担当者に対してよりスマートなコーチングを提供することができるようになっています。 今後は、販売担当者に会話インテリジェンス機能も提供します。 また、新しいモデルの追加、NLP ベースのデータ探索の導入、より深い分析情報の提供を行い、それらでの販売データと会話データの統合によって、スマート コーチングも改善します。
author: relnotes
ms.reviewer: udag
ms.date: 09/12/2019
ms.assetid: cc63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: joegan
dynamics365pdf: true
ms.openlocfilehash: 4b5ad35ca276b19a51f35e02d9c881581443dfbd
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2142594"
---
# <a name="improve-seller-coaching-with-conversation-intelligence"></a><span data-ttu-id="f5413-105">会話インテリジェンスでの販売担当者コーチングの改善</span><span class="sxs-lookup"><span data-stu-id="f5413-105">Improve seller coaching with Conversation intelligence</span></span>
[!include[artificial-intelligence/dynamics365-sales-insights banner](../includes/artificial-intelligence/dynamics365-sales-insights.md)]

| <span data-ttu-id="f5413-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="f5413-106">Enabled for</span></span>    |  <span data-ttu-id="f5413-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f5413-107">Public preview</span></span> | <span data-ttu-id="f5413-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="f5413-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f5413-109">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="f5413-109">Users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="f5413-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="f5413-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="f5413-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f5413-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f5413-112">顧客との会話は営業サイクルの重要な部分であり、販売と収益の創出に直接寄与します。</span><span class="sxs-lookup"><span data-stu-id="f5413-112">Customer conversations are a critical part of the sales cycle, directly contributing to sales and revenue generation.</span></span> <span data-ttu-id="f5413-113">会話インテリジェンスでは、複数チャネルでの会話を分析するためのシームレスで自動化されたプロセスが提供され、品質の継続的な監視と改善が保証されます。</span><span class="sxs-lookup"><span data-stu-id="f5413-113">Conversation intelligence offers a seamless and automated process for analyzing conversations across multiple channels to ensure quality is monitored and improved over time.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f5413-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f5413-114">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="f5413-115">**感情とブランドの検出**: 感情検出の新しい AI モデルでは、通話中の顧客の感情のきめ細かい理解が提供されます。</span><span class="sxs-lookup"><span data-stu-id="f5413-115">**Emotion and brand detection**: New AI models for emotion detection provide granularity to understand customer sentiments during calls.</span></span> <span data-ttu-id="f5413-116">ブランド検出は、顧客がセールス コールで話している新製品やブランドを見つけるのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="f5413-116">Brand detection helps to discover new products and brands that customers are talking about in sales calls.</span></span>

- <span data-ttu-id="f5413-117">**タイムリーな分析情報**: アプリのアシスタントが、独自のタイムリーな分析情報を継続して提供します。</span><span class="sxs-lookup"><span data-stu-id="f5413-117">**Timely insights**: Assistant in the app continuously provides unique and timely insights.</span></span>  

- <span data-ttu-id="f5413-118">**自然言語での Q&A:** 販売と会話データのデータ探査により、英語で簡単な質問をして、それに答えるレポートを動的に受け取る機会が提供されます。</span><span class="sxs-lookup"><span data-stu-id="f5413-118">**Natural language Q&A**: Data exploration of sales and conversational data offers an opportunity to ask simple questions in English and to dynamically receive reports that address these questions.</span></span> 

- <span data-ttu-id="f5413-119">**販売担当者の行動の分析:** トップ販売担当者の行動の分析により、マネージャーは売上向上につながる共通パターンを理解できます。</span><span class="sxs-lookup"><span data-stu-id="f5413-119">**Analyze seller behaviors**: Analysis of top seller behaviors empowers managers to understand common patterns leading to positive sales outcomes.</span></span> 

- <span data-ttu-id="f5413-120">**クロスチャネルおよび営業の KPI**: チーム全体で営業の獲得/失注につながる貴重な情報が標準で強調されます。</span><span class="sxs-lookup"><span data-stu-id="f5413-120">**Cross-channel and sales KPIs**: Highlight valuable information leading to win/loss in sales, across the team, out of the box.</span></span>
 
- <span data-ttu-id="f5413-121">**会話レビュー:** 会話の詳細なビューにより、有効な領域と失敗した領域が示され、販売担当者のコーチングの効果があるブランドの言及とギャップが強調して示されます。</span><span class="sxs-lookup"><span data-stu-id="f5413-121">**Conversation review**: A detailed view of conversations, surfacing areas that are effective versus those that are unsuccessful, highlighting brand mentions and gaps where sellers can benefit from coaching.</span></span> 

<span data-ttu-id="f5413-122">![営業コーチング体験](media/releasenotes0ct19.png "営業コーチング体験")</span><span class="sxs-lookup"><span data-stu-id="f5413-122">![Sales coaching journey](media/releasenotes0ct19.png "Sales coaching journey")</span></span>
<!--feature detail end -->












## <a name="see-also"></a><span data-ttu-id="f5413-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="f5413-123">See also</span></span>
<span data-ttu-id="f5413-124">[機能の探索](https://aka.ms/ROGSI19RW2ROV5) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="f5413-124">[Feature exploration](https://aka.ms/ROGSI19RW2ROV5) (video)</span></span>
