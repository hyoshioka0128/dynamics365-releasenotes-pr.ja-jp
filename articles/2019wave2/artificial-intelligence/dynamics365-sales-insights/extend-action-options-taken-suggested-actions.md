---
title: 推奨アクションから実行するアクション オプションを拡張する
description: ''
author: relnotes
ms.reviewer: udag
ms.date: 01/31/2020
ms.assetid: eac57080-f3d4-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: nataln
dynamics365pdf: true
ms.openlocfilehash: e2bd192b3c5a23872f5c505697374eac86cdc3a4
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3059148"
---
# <a name="extend-action-options-taken-from-the-suggested-actions"></a><span data-ttu-id="c87d3-102">推奨アクションから実行するアクション オプションを拡張する</span><span class="sxs-lookup"><span data-stu-id="c87d3-102">Extend action options taken from the suggested actions</span></span>


| <span data-ttu-id="c87d3-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="c87d3-103">Enabled for</span></span>    |  <span data-ttu-id="c87d3-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c87d3-104">Public preview</span></span> | <span data-ttu-id="c87d3-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="c87d3-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c87d3-106">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="c87d3-106">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="c87d3-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c87d3-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c87d3-108">2020 年 1 月 18 日</span><span class="sxs-lookup"><span data-stu-id="c87d3-108">Jan 18, 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="c87d3-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c87d3-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c87d3-110">販売担当者は、一度に多くのことを追跡する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c87d3-110">Sellers must track many things at once.</span></span> <span data-ttu-id="c87d3-111">推奨アクションは、販売担当者が次のステップを決定するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="c87d3-111">Suggested actions can help them determine their next steps.</span></span> <span data-ttu-id="c87d3-112">それらをフォローアップするのは大変な作業ですが、自動化によって販売担当者の生産性を向上できます。</span><span class="sxs-lookup"><span data-stu-id="c87d3-112">Following up on them can be a lot of work, but automation can improve sellers' productivity.</span></span> 

<span data-ttu-id="c87d3-113">今回のリリースでは、組織が販売担当者の実行可能なアクションを拡張できるようになります。</span><span class="sxs-lookup"><span data-stu-id="c87d3-113">With this release, organizations have the option to extend the actions a seller can take.</span></span> <span data-ttu-id="c87d3-114">これまでは、販売担当者は営業案件などのエンティティを開くか、推奨アクションのフォローアップとして URL を開くことしかできませんでした。</span><span class="sxs-lookup"><span data-stu-id="c87d3-114">Previously, sellers could only open an entity, like an opportunity, or open a URL as a follow-up for suggested action.</span></span> <span data-ttu-id="c87d3-115">カスタム アクション、REST API、プレイブックの起動、フローのトリガーのためにそれらのアクションを拡張する機能をプレビューできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c87d3-115">Now, you can preview extending those actions for custom actions, REST APIs, launching a playbook, and triggering a flow.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c87d3-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c87d3-116">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="c87d3-117">**表示されるアクションの名前を変更する**: アクションをよりわかりやすくします。</span><span class="sxs-lookup"><span data-stu-id="c87d3-117">**Change the name of the displayed action**: Make your actions more descriptive.</span></span> <span data-ttu-id="c87d3-118">現在、販売担当者に表示されるオプションは**開く**のみです。</span><span class="sxs-lookup"><span data-stu-id="c87d3-118">Currently, the only option to show to the seller is **Open**.</span></span> <span data-ttu-id="c87d3-119">必要に応じてテキストをカスタマイズできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c87d3-119">Now, you can customize the texts for your needs.</span></span>
- <span data-ttu-id="c87d3-120">**Flow で推奨アクションを自動化する**: Dynamics 365 のカスタム アクションと同様に、システムと対話する販売担当者への応答として Power Automate を実行できます。</span><span class="sxs-lookup"><span data-stu-id="c87d3-120">**Automate suggested actions with flows**: Like a custom action in Dynamics 365, you can run Power Automate as a response to your seller interacting with the system.</span></span> <span data-ttu-id="c87d3-121">たとえば、メールでのドキュメントの送信を自動化できます。</span><span class="sxs-lookup"><span data-stu-id="c87d3-121">You can, for example, automate sending a document via email.</span></span>
- <span data-ttu-id="c87d3-122">**カスタム アクションで推奨アクションを自動化する**: 販売担当者が推奨アクションからカスタム アクションの実行をトリガーできるようにします。</span><span class="sxs-lookup"><span data-stu-id="c87d3-122">**Automate suggested actions with custom actions**: Let your sellers trigger the execution of a custom action from a suggested action.</span></span> <span data-ttu-id="c87d3-123">フィールドの更新などの単純なアクションを推奨アクション内から直接トリガーできます。</span><span class="sxs-lookup"><span data-stu-id="c87d3-123">Simple actions, like updating a field, can be triggered directly from within the suggested action.</span></span> 
- <span data-ttu-id="c87d3-124">**REST API を使用して自動化する**: Power Automate やカスタム アクションを使用してアクションを自動化できない場合は、販売担当者が Dynamics 365 内の推奨アクションから自動アクションを直接実行できるように REST API 呼び出しを構成できます。</span><span class="sxs-lookup"><span data-stu-id="c87d3-124">**Automate using a REST API call**: If you can't use Power Automate or a custom action to help to automate an action, you can configure a REST API call that lets sellers execute any automatic action directly from the suggested action within Dynamics 365.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="c87d3-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="c87d3-125">See also</span></span>

<span data-ttu-id="c87d3-126">[カードにアクションを追加する](https://docs.microsoft.com/dynamics365/ai/sales/create-insight-cards-flow#add-actions-to-cards) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c87d3-126">[Add actions to cards](https://docs.microsoft.com/dynamics365/ai/sales/create-insight-cards-flow#add-actions-to-cards) (docs)</span></span>
