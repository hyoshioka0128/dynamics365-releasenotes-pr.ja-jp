---
title: エージェント マクロの強化
description: エージェント マクロの強化
author: relnotes
ms.reviewer: nenellim
ms.date: 04/09/2020
ms.assetid: cf8ed4f6-7c58-ea11-a811-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: srikot
dynamics365pdf: true
ms.openlocfilehash: 7ffff1df766c1fd14c5633d490c2beca37b29c49
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3272600"
---
# <a name="agent-macro-enhancements"></a><span data-ttu-id="35836-103">エージェント マクロの強化</span><span class="sxs-lookup"><span data-stu-id="35836-103">Agent macro enhancements</span></span>


| <span data-ttu-id="35836-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="35836-104">Enabled for</span></span>    |  <span data-ttu-id="35836-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="35836-105">Public preview</span></span> | <span data-ttu-id="35836-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="35836-106">Early access</span></span> | <span data-ttu-id="35836-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="35836-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="35836-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="35836-108">End users by admins, makers, or analysts</span></span>|-|-| <span data-ttu-id="35836-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="35836-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="35836-110">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="35836-110">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="35836-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="35836-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="35836-112">マクロは、一連の一般的で反復的なタスクを自動化することでエージェントの生産性を高め、大規模なチーム全体でこれらのタスクの一貫性と品質を確保するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="35836-112">Macros enhance agent productivity by automating a series of common and repetitive tasks, helping to ensure consistency and quality of these tasks across large teams.</span></span> <span data-ttu-id="35836-113">このマクロの強化により、自動化プロセスにさらに複雑なロジックを適用して、エージェントの負担を軽減し、最適なサービス エクスペリエンスの一貫性を高め、顧客のサポートにかかる時間を短縮できます。</span><span class="sxs-lookup"><span data-stu-id="35836-113">This enhancement to macros enables more complex logic to be applied to the automation process to reduce the burden on agents, increase the consistency of optimal service experiences, and decrease the amount of time taken to help customers.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="35836-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="35836-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="35836-115">この機能を使用すると、管理者はマクロに決定分岐を作成して、コンテキスト変数をマクロ ステップとして評価するための論理条件を追加できます。</span><span class="sxs-lookup"><span data-stu-id="35836-115">This feature allows administrators to create decision branches in macros to add logical conditions for evaluating the context variables as macro steps.</span></span> <span data-ttu-id="35836-116">その後、ユーザーがマクロを実行すると、論理条件が評価され、マクロで定義されている適切なステップが実行されます。</span><span class="sxs-lookup"><span data-stu-id="35836-116">Subsequently, when users run the macros, the logical conditions will be evaluated and appropriate steps that are defined in the macros will be run.</span></span> <span data-ttu-id="35836-117">条件の例を次にいくつか示します。</span><span class="sxs-lookup"><span data-stu-id="35836-117">Some example conditions are as follows:</span></span>

-   <span data-ttu-id="35836-118">会話にケースが添付されている場合は、既存のケース フォームを開きます。それ以外の場合は、新しいケース フォームを開きます。</span><span class="sxs-lookup"><span data-stu-id="35836-118">If a conversation has a case attached, open the existing case form; otherwise, open a new case form.</span></span>
-   <span data-ttu-id="35836-119">顧客の優先度が高い場合は、"高優先度のメール テンプレート" を使用します。それ以外の場合は、"通常の確認応答テンプレート" を使用します。</span><span class="sxs-lookup"><span data-stu-id="35836-119">If the priority of a customer is high, use the "high-priority email template"; otherwise, use the "normal acknowledgement template".</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="35836-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="35836-120">See also</span></span>

<!--docs start-->
<span data-ttu-id="35836-121">[マクロでタスクを自動化](https://docs.microsoft.com/dynamics365/omnichannel/administrator/macros) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="35836-121">[Automate tasks with macros](https://docs.microsoft.com/dynamics365/omnichannel/administrator/macros) (docs)</span></span>
<!--docs end-->
