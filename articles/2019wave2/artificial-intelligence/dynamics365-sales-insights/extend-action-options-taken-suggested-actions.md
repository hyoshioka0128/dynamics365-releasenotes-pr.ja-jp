---
title: 推奨アクションから実行するアクション オプションを拡張する
description: ''
author: relnotes
ms.reviewer: udag
ms.date: 09/16/2019
ms.assetid: eac57080-f3d4-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: joegan
dynamics365pdf: true
ms.openlocfilehash: 871fea22a95a694d1f81c131b220ef5d6d54180e
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143891"
---
# <a name="extend-action-options-taken-from-the-suggested-actions"></a><span data-ttu-id="20826-102">推奨アクションから実行するアクション オプションを拡張する</span><span class="sxs-lookup"><span data-stu-id="20826-102">Extend action options taken from the suggested actions</span></span>
[!include[artificial-intelligence/dynamics365-sales-insights banner](../includes/artificial-intelligence/dynamics365-sales-insights.md)]

| <span data-ttu-id="20826-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="20826-103">Enabled for</span></span>    |  <span data-ttu-id="20826-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="20826-104">Public preview</span></span> | <span data-ttu-id="20826-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="20826-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="20826-106">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="20826-106">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="20826-107">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="20826-107">Oct 2019</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="20826-108">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="20826-108">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="20826-109">販売担当者は、一度に多くのことを追跡する必要があります。</span><span class="sxs-lookup"><span data-stu-id="20826-109">Sellers must track many things at once.</span></span> <span data-ttu-id="20826-110">推奨アクションは、販売担当者が次のステップを決定するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="20826-110">Suggested actions can help them determine their next steps.</span></span> <span data-ttu-id="20826-111">それらをフォローアップするのは大変な作業ですが、自動化によって販売担当者の生産性を向上できます。</span><span class="sxs-lookup"><span data-stu-id="20826-111">Following up on them can be a lot of work, but automation can improve sellers' productivity.</span></span> 

<span data-ttu-id="20826-112">今回のリリースでは、組織が販売担当者の実行可能なアクションを拡張できるようになります。</span><span class="sxs-lookup"><span data-stu-id="20826-112">With this release, organizations have the option to extend the actions a seller can take.</span></span> <span data-ttu-id="20826-113">これまでは、販売担当者は営業案件などのエンティティを開くか、推奨アクションのフォローアップとして URL を開くことしかできませんでした。</span><span class="sxs-lookup"><span data-stu-id="20826-113">Previously, sellers could only open an entity, like an opportunity, or open an URL as a follow up for suggested action.</span></span> <span data-ttu-id="20826-114">カスタム アクション、REST API、プレイブックの起動、フローのトリガーのためにそれらのアクションを拡張する機能をプレビューできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="20826-114">Now, you can preview extending those actions for custom actions, REST APIs, launching a playbook, and triggering a flow.</span></span> 

<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="20826-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="20826-115">Feature details</span></span>
<!--feature detail start --><span data-ttu-id="20826-116">
-\*\*表示されるアクションの名前を変更する\*\*: アクションをよりわかりやすくします。</span><span class="sxs-lookup"><span data-stu-id="20826-116">
-\*\*Change the name of the displayed action\*\*: Make your actions more descriptive.</span></span> <span data-ttu-id="20826-117">現在、販売担当者に表示されるオプションは**開く**のみです。</span><span class="sxs-lookup"><span data-stu-id="20826-117">Currently, the only option to show to the seller is **Open**.</span></span> <span data-ttu-id="20826-118">必要に応じてテキストをカスタマイズできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="20826-118">Now, you can customize the texts for your needs.</span></span><span data-ttu-id="20826-119">
-\*\*Flow で推奨アクションを自動化する\*\*: Dynamics 365 のカスタム アクションと同様に、システムと対話する販売担当者への応答として Microsoft Flow を実行できます。</span><span class="sxs-lookup"><span data-stu-id="20826-119">
-\*\*Automate suggested actions with Flow\*\*: Like a custom action in Dynamics 365, you can run a Microsoft Flow as a response to your seller interacting with the system.</span></span> <span data-ttu-id="20826-120">たとえば、メールでのドキュメントの送信を自動化できます。</span><span class="sxs-lookup"><span data-stu-id="20826-120">You can, for example, automate sending a document via email.</span></span><span data-ttu-id="20826-121">
-\*\*カスタム アクションで推奨アクションを自動化する\*\*: 販売担当者が推奨アクションからカスタム アクションの実行をトリガーできるようにします。</span><span class="sxs-lookup"><span data-stu-id="20826-121">
-\*\*Automate suggested actions with custom actions\*\*: Let your sellers trigger the execution of a custom action from a suggested action.</span></span> <span data-ttu-id="20826-122">フィールドの更新などの単純なアクションを推奨アクション内から直接トリガーできます。</span><span class="sxs-lookup"><span data-stu-id="20826-122">Simple actions, like updating a field, can be triggered directly from within the suggested action.</span></span><span data-ttu-id="20826-123"> 
\-\**REST API 呼び出しを使用して自動化す\る\**: Microsoft Flow またはカスタム アクションを使用してアクションを自動化できない場合は、販売担当者が Dynamics 365 内の推奨アクションから自動アクションを直接実行できるように REST API 呼び出しを構成できます。</span><span class="sxs-lookup"><span data-stu-id="20826-123"> 
\-\**Automate using a REST API cal\l\**: If you can't use Microsoft Flow or a custom action to help to automate an action, you can configure a REST API call that lets sellers execute any automatic action directly from the suggested action within Dynamics 365.</span></span>
<!--feature detail end -->











