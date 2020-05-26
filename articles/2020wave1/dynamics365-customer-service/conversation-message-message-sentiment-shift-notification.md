---
title: 会話メッセージとメッセージの感情変化の通知
description: 会話メッセージとメッセージの感情変化の通知
author: relnotes
ms.reviewer: kabala
ms.date: 04/14/2020
ms.assetid: 1662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: srikot
dynamics365pdf: true
ms.openlocfilehash: 86d0a21b148a648ef77f40612b08d77ed26e3df8
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3272612"
---
# <a name="conversation-message-and-message-sentiment-shift-notification"></a><span data-ttu-id="d93fb-103">会話メッセージとメッセージの感情変化の通知</span><span class="sxs-lookup"><span data-stu-id="d93fb-103">Conversation message and message sentiment shift notification</span></span>


| <span data-ttu-id="d93fb-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="d93fb-104">Enabled for</span></span>    |  <span data-ttu-id="d93fb-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d93fb-105">Public preview</span></span> | <span data-ttu-id="d93fb-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="d93fb-106">Early access</span></span> | <span data-ttu-id="d93fb-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="d93fb-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="d93fb-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="d93fb-108">End users by admins, makers, or analysts</span></span>|-|-| <span data-ttu-id="d93fb-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="d93fb-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="d93fb-110">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="d93fb-110">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="d93fb-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d93fb-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d93fb-112">問題の重大度と影響度が高い場合、お客様はサポートとのやり取りにおいて感情的になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="d93fb-112">Customers can be highly emotional in their engagement with support when the severity and impact of the issue is high.</span></span> <span data-ttu-id="d93fb-113">お客様の感情とサポート エンゲージメント中に発生する可能性のある急速な変化を理解することで、サービス提供ではメッセージングをすばやく調整して顧客の感情を改善し、最高のサポートを提供できます。</span><span class="sxs-lookup"><span data-stu-id="d93fb-113">Understanding customer sentiment and the rapid shifts that might occur during the support engagement enables service delivery to quickly tune messaging to improve customer sentiment and provide the best support.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d93fb-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d93fb-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d93fb-115">この機能を使用すると、管理者はポジティブからネガティブへの感情の変化のしきい値を定義できるため、エージェントとスーパーバイザーは感情の変化を示すタイムリーなアラートを受け取り、アクションを実行できます。</span><span class="sxs-lookup"><span data-stu-id="d93fb-115">This feature allows administrators to define thresholds for sentiment shift from positive to negative so that agents and supervisors get timely alerts to indicate sentiment shift and allows them to take actions.</span></span> 

<span data-ttu-id="d93fb-116">この機能では次のことが可能です。</span><span class="sxs-lookup"><span data-stu-id="d93fb-116">This feature allows the following:</span></span>

-   <span data-ttu-id="d93fb-117">アラートを設定し、会話で感情が悪化しているときにエージェントとスーパーバイザーに表示します。</span><span class="sxs-lookup"><span data-stu-id="d93fb-117">Set up alerts and display them to agents and supervisors when a conversation is drifting toward a negative sentiment.</span></span>
-   <span data-ttu-id="d93fb-118">感情の動きに関する通知を構成します。</span><span class="sxs-lookup"><span data-stu-id="d93fb-118">Configure notifications for the sentiment drifts.</span></span>
-   <span data-ttu-id="d93fb-119">セッション タブに会話での感情の変化を適切に示して、エージェント (複数の会話を行っている) が、感情が低下傾向にあるためすぐに是正手順をとる必要がある会話に引き寄せられるようにします。</span><span class="sxs-lookup"><span data-stu-id="d93fb-119">Indicate the conversational sentiment shift appropriately in the session tab so that an agent (who is working on multiple conversations) is drawn toward the conversation that is trending low on sentiment and must be addressed with immediate remedial steps.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="d93fb-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="d93fb-120">See also</span></span>

<!--docs start-->
<span data-ttu-id="d93fb-121">[リアルタイムの顧客感情を分析する](https://docs.microsoft.com/dynamics365/omnichannel/administrator/enable-sentiment-analysis) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="d93fb-121">[Analyze real-time customer sentiment](https://docs.microsoft.com/dynamics365/omnichannel/administrator/enable-sentiment-analysis) (docs)</span></span>
<!--docs end-->
