---
title: 会話インテリジェンス
description: ''
author: relnotes
ms.reviewer: shubhadaj
ms.date: 09/27/2019
ms.assetid: 6568f6b4-e9c9-e911-a96a-000d3a4f36ce
ms.topic: structure
ms.service: business-applications
ms.author: joegan
dynamics365pdf: true
ms.openlocfilehash: 6576d281943fcaeeaa3f2e19a579cb6fd1e3a874
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986840"
---
# <a name="conversation-intelligence"></a><span data-ttu-id="a5b6d-102">会話インテリジェンス</span><span class="sxs-lookup"><span data-stu-id="a5b6d-102">Conversation intelligence</span></span>

[!include[artificial-intelligence/dynamics365-sales-insights banner](../includes/artificial-intelligence/dynamics365-sales-insights.md)]

<!--structure start-->
<span data-ttu-id="a5b6d-103">顧客と直接話し合うことは、販売サイクルの重要な部分です。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-103">Talking directly with customers is an important part of any sales cycle.</span></span> <span data-ttu-id="a5b6d-104">多くの組織には既に大量の会話データが蓄積されていますが、大きな可能性にもかかわらず、ほとんどの組織はこれらの対話から価値を引き出していません。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-104">While many organizations have already amassed large volumes of conversational data, most are not deriving any value from these interactions, despite the tremendous potential.</span></span> <span data-ttu-id="a5b6d-105">今日のリソースに制約のある環境では、既存のデータから価値を引き出すことは収益性の高い成長に不可欠です。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-105">In today’s resource-constrained environment, extracting value from existing data is vital for profitable growth.</span></span> <span data-ttu-id="a5b6d-106">会話インテリジェンスでは、AI と自然言語処理における Microsoft の最近の進歩を利用することにより、取引の迅速な成立と新しい営業案件の識別に役立つよう、これらの分析情報が自動的に抽出されます。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-106">By leveraging Microsoft’s recent advancements in AI and natural language processing, Conversation intelligence automatically extracts these insights to help close deals faster and to identify new opportunities.</span></span>

<span data-ttu-id="a5b6d-107">会話インテリジェンスでは、自動的な通話の文字起こしと、コンテンツ、感情、行動スタイルの分析により、有意義な分析情報が提供されます。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-107">By automatically transcribing calls and analyzing content, sentiment, and behavioral style, Conversation intelligence provides meaningful insights.</span></span> <span data-ttu-id="a5b6d-108">販売担当者は、実証済みの会話技術を使用して、購入者を効果的に購入に導くことができます。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-108">Sellers can effectively guide buyers toward a purchase using proven conversation techniques.</span></span> <span data-ttu-id="a5b6d-109">マネージャーは、新しい市場動向を明らかにすることにより、新しい営業活動または営業トレーニングの戦略的意思決定を改善できます。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-109">Managers can make better strategic decisions for new sales motion or sales training by identifying new market trends.</span></span> <span data-ttu-id="a5b6d-110">成績上位の販売担当者に固有の行動を理解することにより、マネージャーはそれらの学習をチームの残りのメンバーに伝授して、チームのパフォーマンスを向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-110">By understanding unique behaviors of top sellers, managers can bring those learnings to the rest of the team to lift the team performance.</span></span>

<span data-ttu-id="a5b6d-111">2020 年のリリース ウェーブ 1 では、Dynamics 365 Sales に通話の概要とアクション項目の抽出を組み込むことで、販売担当者が顧客との電話を終えるたびに貴重な時間を節約できるようにします。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-111">In the 2020 release wave 1, we bring call summary and action item extraction right within Dynamics 365 Sales to help sellers save precious time after every customer call.</span></span>  <span data-ttu-id="a5b6d-112">また、顧客との会話の中で議論された感情や高レベルのトピックを検出する新しい AI モデルも導入されます。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-112">We are also introducing new AI models that detect emotions and high-level topics discussed during customer conversations.</span></span>  

<span data-ttu-id="a5b6d-113">会話インテリジェンスはチームの全員に関連しています。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-113">Conversation intelligence is relevant to everyone on the team:</span></span>

- <span data-ttu-id="a5b6d-114">**販売担当者**には、すべての会話を最大限に活用するために、会話を追跡し、ベスト プラクティスに従うようにする、簡単な方法が必要です。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-114">**Sellers** need a simple way to keep track of conversations and ensure they follow best practices to make the most out of every conversation.</span></span>
- <span data-ttu-id="a5b6d-115">**マネージャー**は、営業売上予算を効率的に達成し、顧客を満足させるため、トップ販売担当者が支援され、成功した行動が広まり、潜在的なギャップがすぐに対処されるよう、チームのパフォーマンスをリアルタイムで追跡する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a5b6d-115">**Managers** need to keep track of team performance in real time, so top sellers are reinforced, successful behaviors propagated, and potential gaps immediately addressed to meet sales quotas effectively and to ensure customer satisfaction.</span></span>
<!--structure end-->



