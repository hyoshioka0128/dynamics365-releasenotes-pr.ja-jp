---
title: Microsoft Flow を使用した承認のサポート
description: Microsoft Flow を使用した承認のサポート
author: jain-shailesh
ms.reviewer: kamaybac
ms.date: 09/09/2019
ms.assetid: c661278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: shjain
dynamics365pdf: true
ms.openlocfilehash: 53c041b32bb7b1026d2510be6a950a6bf199d11a
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143705"
---
# <a name="support-approvals-using-microsoft-flow"></a><span data-ttu-id="0e806-103">Microsoft Flow を使用した承認のサポート</span><span class="sxs-lookup"><span data-stu-id="0e806-103">Support approvals using Microsoft Flow</span></span>
[!include[dynamics365-marketing banner](../includes/dynamics365-marketing.md)]

| <span data-ttu-id="0e806-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0e806-104">Enabled for</span></span>    |  <span data-ttu-id="0e806-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0e806-105">Public preview</span></span> | <span data-ttu-id="0e806-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="0e806-106">Early access</span></span> | <span data-ttu-id="0e806-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="0e806-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="0e806-108">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="0e806-108">Users, automatically</span></span>|-|<span data-ttu-id="0e806-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0e806-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0e806-110">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="0e806-110">Aug 2, 2019</span></span>| <span data-ttu-id="0e806-111">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="0e806-111">Oct 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="0e806-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0e806-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0e806-113">Dynamics 365 Marketing では、カスタマイズ可能な承認ワークフローがサポートされるようになり、新しいマーケティング資料やキャンペーンが有効になる前に適切に承認されます。</span><span class="sxs-lookup"><span data-stu-id="0e806-113">Dynamics 365 Marketing now supports a customizable approval workflow that helps make sure new marketing materials and campaigns are properly approved before going into effect.</span></span> 

<span data-ttu-id="0e806-114">マーケティング電子メールや顧客体験などの新しいレコードの設定を完了したマーケティング担当者は、1 回クリックするだけで、そのレコードを承認のために送信できます。</span><span class="sxs-lookup"><span data-stu-id="0e806-114">After marketers finish setting up a new record, such as a marketing email or customer journey, they can send that record for approval with just a single click.</span></span> <span data-ttu-id="0e806-115">承認ワークフローの設定方法に基づいて、関連マネージャーに承認要求が通知されます。</span><span class="sxs-lookup"><span data-stu-id="0e806-115">Based on how the approval workflow is set up, the relevant manager is then notified of the approval request.</span></span> <span data-ttu-id="0e806-116">コア承認シナリオには以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="0e806-116">Core approval scenarios include:</span></span> 

-  <span data-ttu-id="0e806-117">レコードの承認を要求する</span><span class="sxs-lookup"><span data-stu-id="0e806-117">Request approval for a record</span></span> 
-  <span data-ttu-id="0e806-118">承認の要求を取り消す</span><span class="sxs-lookup"><span data-stu-id="0e806-118">Cancel request for approval</span></span> 
-  <span data-ttu-id="0e806-119">承認要求を承認または却下する</span><span class="sxs-lookup"><span data-stu-id="0e806-119">Approve or reject an approval request</span></span> 
-  <span data-ttu-id="0e806-120">承認依頼を委任する</span><span class="sxs-lookup"><span data-stu-id="0e806-120">Delegate a request for approval</span></span>
-  <span data-ttu-id="0e806-121">期限切れの承認要求を管理する</span><span class="sxs-lookup"><span data-stu-id="0e806-121">Manage an overdue approval request</span></span> 

<span data-ttu-id="0e806-122">承認システムは、コア マーケティング エンティティに基づいて簡単な承認プロセスを強制することができる Microsoft Flow アプリとして配布されます。</span><span class="sxs-lookup"><span data-stu-id="0e806-122">The approval system is delivered as a Microsoft Flow app that can enforce a simple approval process based on core marketing entities.</span></span> <span data-ttu-id="0e806-123">各組織にはそれぞれ独自のビジネス プロセスと階層があるため、Microsoft Flow ではビジネス ユーザー、作成者、またはパートナーによる簡単なカスタマイズに必要な柔軟性が提供されます。</span><span class="sxs-lookup"><span data-stu-id="0e806-123">Because each organization probably has its own business process and hierarchy, Microsoft Flow provides the flexibility required for easy customization by business users, makers, or partners.</span></span>
<!--feature detail end -->

<span data-ttu-id="0e806-124">![承認ワークフロー デザイナー](media/approval-workflow.png "承認ワークフロー デザイナー")</span><span class="sxs-lookup"><span data-stu-id="0e806-124">![Approval workflow designer](media/approval-workflow.png "Approval workflow designer")</span></span>
<!-- Picture 1 -->











## <a name="see-also"></a><span data-ttu-id="0e806-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="0e806-125">See also</span></span>

<span data-ttu-id="0e806-126">[8 月の更新プログラムと早期アクセス](https://cloudblogs.microsoft.com/dynamics365/it/2019/08/03/dynamics-365-for-marketing-august-update-and-early-access-are-rolling-out-now/) (ブログ)</span><span class="sxs-lookup"><span data-stu-id="0e806-126">[August update and early access](https://cloudblogs.microsoft.com/dynamics365/it/2019/08/03/dynamics-365-for-marketing-august-update-and-early-access-are-rolling-out-now/) (blog)</span></span>

<span data-ttu-id="0e806-127">[承認機能の構築](https://docs.microsoft.com/dynamics365/customer-engagement/marketing/developer/marketing-approvals-feature) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="0e806-127">[Build an approvals feature](https://docs.microsoft.com/dynamics365/customer-engagement/marketing/developer/marketing-approvals-feature) (docs)</span></span>
