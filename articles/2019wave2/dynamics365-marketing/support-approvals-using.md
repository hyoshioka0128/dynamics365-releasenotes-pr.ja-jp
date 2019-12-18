---
title: Power Automate を使用した承認のサポート
description: Power Automate を使用した承認のサポート
author: jain-shailesh
ms.reviewer: kamaybac
ms.date: 11/15/2019
ms.assetid: c661278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: shjain
dynamics365pdf: true
ms.openlocfilehash: b942c7dd43e3d0c0eb11671dabb071a23939602d
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2891769"
---
# <a name="support-approvals-using-power-automate"></a><span data-ttu-id="7141a-103">Power Automate を使用した承認のサポート</span><span class="sxs-lookup"><span data-stu-id="7141a-103">Support approvals using Power Automate</span></span>


| <span data-ttu-id="7141a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7141a-104">Enabled for</span></span>    |  <span data-ttu-id="7141a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7141a-105">Public preview</span></span> | <span data-ttu-id="7141a-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="7141a-106">Early access</span></span> | <span data-ttu-id="7141a-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="7141a-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="7141a-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="7141a-108">End users, automatically</span></span>|-|<span data-ttu-id="7141a-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7141a-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7141a-110">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="7141a-110">Aug 2, 2019</span></span>| <span data-ttu-id="7141a-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7141a-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7141a-112">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7141a-112">Oct 1, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="7141a-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7141a-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7141a-114">Dynamics 365 Marketing では、カスタマイズ可能な承認ワークフローがサポートされるようになり、新しいマーケティング資料やキャンペーンが有効になる前に適切に承認されます。</span><span class="sxs-lookup"><span data-stu-id="7141a-114">Dynamics 365 Marketing now supports a customizable approval workflow that helps make sure new marketing materials and campaigns are properly approved before going into effect.</span></span> 

<span data-ttu-id="7141a-115">マーケティング電子メールや顧客体験などの新しいレコードの設定を完了したマーケティング担当者は、1 回クリックするだけで、そのレコードを承認のために送信できます。</span><span class="sxs-lookup"><span data-stu-id="7141a-115">After marketers finish setting up a new record, such as a marketing email or customer journey, they can send that record for approval with just a single click.</span></span> <span data-ttu-id="7141a-116">承認ワークフローの設定方法に基づいて、関連マネージャーに承認要求が通知されます。</span><span class="sxs-lookup"><span data-stu-id="7141a-116">Based on how the approval workflow is set up, the relevant manager is then notified of the approval request.</span></span> <span data-ttu-id="7141a-117">コア承認シナリオには以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="7141a-117">Core approval scenarios include:</span></span> 

-  <span data-ttu-id="7141a-118">レコードの承認を要求する</span><span class="sxs-lookup"><span data-stu-id="7141a-118">Request approval for a record</span></span> 
-  <span data-ttu-id="7141a-119">承認の要求を取り消す</span><span class="sxs-lookup"><span data-stu-id="7141a-119">Cancel request for approval</span></span> 
-  <span data-ttu-id="7141a-120">承認要求を承認または却下する</span><span class="sxs-lookup"><span data-stu-id="7141a-120">Approve or reject an approval request</span></span> 
-  <span data-ttu-id="7141a-121">承認依頼を委任する</span><span class="sxs-lookup"><span data-stu-id="7141a-121">Delegate a request for approval</span></span>
-  <span data-ttu-id="7141a-122">期限切れの承認要求を管理する</span><span class="sxs-lookup"><span data-stu-id="7141a-122">Manage an overdue approval request</span></span> 

<span data-ttu-id="7141a-123">承認システムは、コア マーケティング エンティティに基づいて簡単な承認プロセスを強制することができる Power Automate アプリとして配布されます。</span><span class="sxs-lookup"><span data-stu-id="7141a-123">The approval system is delivered as a Power Automate app that can enforce a simple approval process based on core marketing entities.</span></span> <span data-ttu-id="7141a-124">各組織にはそれぞれ独自のビジネス プロセスと階層があるため、Power Automate ではビジネス ユーザー、作成者、またはパートナーによる簡単なカスタマイズに必要な柔軟性が提供されます。</span><span class="sxs-lookup"><span data-stu-id="7141a-124">Because each organization probably has its own business process and hierarchy, Power Automate provides the flexibility required for easy customization by business users, makers, or partners.</span></span>
<!--feature detail end -->

<span data-ttu-id="7141a-125">![承認ワークフロー デザイナー](media/approval-workflow.png "承認ワークフロー デザイナー")</span><span class="sxs-lookup"><span data-stu-id="7141a-125">![Approval workflow designer](media/approval-workflow.png "Approval workflow designer")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="7141a-126">関連項目</span><span class="sxs-lookup"><span data-stu-id="7141a-126">See also</span></span>

<span data-ttu-id="7141a-127">[8 月の更新プログラムと早期アクセス](https://cloudblogs.microsoft.com/dynamics365/it/2019/08/03/dynamics-365-for-marketing-august-update-and-early-access-are-rolling-out-now/) (ブログ)</span><span class="sxs-lookup"><span data-stu-id="7141a-127">[August update and early access](https://cloudblogs.microsoft.com/dynamics365/it/2019/08/03/dynamics-365-for-marketing-august-update-and-early-access-are-rolling-out-now/) (blog)</span></span>

<span data-ttu-id="7141a-128">[承認機能の構築](https://docs.microsoft.com/dynamics365/marketing/developer/marketing-approvals-feature) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="7141a-128">[Build an approvals feature](https://docs.microsoft.com/dynamics365/marketing/developer/marketing-approvals-feature) (docs)</span></span>
