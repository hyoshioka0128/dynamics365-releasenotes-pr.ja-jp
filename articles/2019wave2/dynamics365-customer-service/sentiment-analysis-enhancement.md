---
title: 感情分析の強化
description: 強化された顧客センチメント エクスペリエンス。
author: relnotes
ms.reviewer: laalexan
ms.date: 01/27/2020
ms.assetid: 1c62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: chrg
dynamics365pdf: true
ms.openlocfilehash: 75908576a99996b6cc6d40b63491f8f7027f2900
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3058229"
---
# <a name="sentiment-analysis-enhancements"></a><span data-ttu-id="b62d5-103">感情分析の強化</span><span class="sxs-lookup"><span data-stu-id="b62d5-103">Sentiment analysis enhancements</span></span>


| <span data-ttu-id="b62d5-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b62d5-104">Enabled for</span></span>    |  <span data-ttu-id="b62d5-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b62d5-105">Public preview</span></span> | <span data-ttu-id="b62d5-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="b62d5-106">Early access</span></span> | <span data-ttu-id="b62d5-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="b62d5-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="b62d5-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="b62d5-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="b62d5-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b62d5-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b62d5-110">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b62d5-110">Oct 1, 2019</span></span>|-| <span data-ttu-id="b62d5-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b62d5-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b62d5-112">2020 年 1 月 24 日</span><span class="sxs-lookup"><span data-stu-id="b62d5-112">Jan 24, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="b62d5-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b62d5-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b62d5-114">顧客センチメントを理解することで、エージェントは顧客によりパーソナライズされた共感的なサービスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="b62d5-114">Understanding customer sentiment helps agents provide more personalized and empathetic service to customers.</span></span> <span data-ttu-id="b62d5-115">追加言語サポート、新しいアイコン、およびアクセシビリティ機能によるセンチメント機能の強化は、エージェントが顧客サービスの提供を改善するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="b62d5-115">Enhancing sentiment features with additional language support, new icons, and accessibility features helps agents improve customer service delivery.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b62d5-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b62d5-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b62d5-117">進行中のメッセージング セッションで否定的な感情イベントを識別する機能は、エージェントとスーパーバイザーがそのデータに基づいて行動し、顧客の肯定的な結果を確実にする機会を提供するため、重要です。</span><span class="sxs-lookup"><span data-stu-id="b62d5-117">The ability to identify negative sentiment events in ongoing messaging sessions is key as it provides an opportunity for agents and supervisors to act on that data and ensure a positive customer outcome.</span></span> <span data-ttu-id="b62d5-118">この機能は、エージェントがセンチメントを使用して顧客により優れたサービスを提供できるようにする追加のセンチメント機能拡張を導入します。</span><span class="sxs-lookup"><span data-stu-id="b62d5-118">This feature introduces additional sentiment enhancements that enable agents to use sentiment to better serve customers:</span></span>

- <span data-ttu-id="b62d5-119">**追加言語のサポート**: 感情分析のサポートには追加言語が含まれるので、テキスト分析機能を利用できる市場が増えます。</span><span class="sxs-lookup"><span data-stu-id="b62d5-119">**Additional language support**: Sentiment analysis support includes additional languages, making the text analytics feature available to additional markets.</span></span>
- <span data-ttu-id="b62d5-120">**エージェントのセンチメントの可視性の向上**: リアルタイムのセンチメント エクスペリエンスでは、アイコンが更新され、見ることに困難のあるユーザー向けのサポート機能を含むアクセシビリティが強化されました。</span><span class="sxs-lookup"><span data-stu-id="b62d5-120">**Improved agent sentiment visibility**: The real-time sentiment experience now has updated icons and accessibility enhancements including supporting features for the visually impaired.</span></span> <span data-ttu-id="b62d5-121">エージェントは、サポート セッションがうまくいっていないときにそれをより簡単に識別でき、早めにスーパーバイザーや同僚に助けを求めて問題に対処できます。</span><span class="sxs-lookup"><span data-stu-id="b62d5-121">Agents can more easily identify when a support session doesn't go well, and they can proactively request supervisor or peer help in addressing the issue.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="b62d5-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="b62d5-122">See also</span></span>

<span data-ttu-id="b62d5-123">[感情分析を有効化する](https://docs.microsoft.com/dynamics365/omnichannel/administrator/enable-sentiment-analysis) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b62d5-123">[Enable sentiment analysis](https://docs.microsoft.com/dynamics365/omnichannel/administrator/enable-sentiment-analysis) (docs)</span></span>
