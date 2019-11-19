---
title: 仕入先請求書のワークフローの状態を回復不能から下書きにリセットする
description: システムが中断された後に、ドキュメントが回復不能状態になることがあります。 ユーザーは、サポートに連絡して支援を依頼しなくても、自分でドキュメントの状態を下書きにリセットできます。
author: relnotes
ms.reviewer: sericks
ms.date: 10/04/2019
ms.assetid: 36ae1e1a-b0a9-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 1522570ef0441437041004cfff7f5ea349806ee1
ms.sourcegitcommit: b0fef00d4f04f2507056a10ecce699767c669119
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2662534"
---
# <a name="reset-workflow-status-for-vendor-invoices-from-unrecoverable-to-draft"></a><span data-ttu-id="963c8-104">仕入先請求書のワークフローの状態を回復不能から下書きにリセットする</span><span class="sxs-lookup"><span data-stu-id="963c8-104">Reset workflow status for vendor invoices from Unrecoverable to Draft</span></span>


| <span data-ttu-id="963c8-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="963c8-105">Enabled for</span></span>    |  <span data-ttu-id="963c8-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="963c8-106">Public preview</span></span> | <span data-ttu-id="963c8-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="963c8-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="963c8-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="963c8-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="963c8-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="963c8-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="963c8-110">2019 年 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="963c8-110">Aug 5, 2019</span></span>| <span data-ttu-id="963c8-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="963c8-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="963c8-112">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="963c8-112">Oct 1, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="963c8-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="963c8-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="963c8-114">**ワークフロー履歴**ページを使用して、ワークフローの状態を下書きにリセットできます。</span><span class="sxs-lookup"><span data-stu-id="963c8-114">You can use the **Workflow history** page to reset the workflow status to Draft.</span></span> <span data-ttu-id="963c8-115">このページは、**仕入先請求書**ページから、または**共通** > **照会** > **ワークフロー**に移動して開くことができます。</span><span class="sxs-lookup"><span data-stu-id="963c8-115">This page can be opened from the **Vendor invoice** page or by going to **Common** > **Inquires** > **Workflow**.</span></span> <span data-ttu-id="963c8-116">ワークフローの状態を下書きにリセットするには、**取り消し**を選択します。</span><span class="sxs-lookup"><span data-stu-id="963c8-116">To reset the workflow status to Draft, select **Recall**.</span></span> <span data-ttu-id="963c8-117">**仕入先請求書**または**保留中の仕入先請求書**ページで取り消しアクションを選択することでワークフローの状態を下書きにリセットすることもできます。</span><span class="sxs-lookup"><span data-stu-id="963c8-117">You can also reset the workflow status to Draft by selecting the Recall action on either the **Vendor invoice** or **Pending vendor invoices** page.</span></span> <span data-ttu-id="963c8-118">ワークフローの状態が下書きにリセットされると、**仕入先請求書**ページで編集可能になります。</span><span class="sxs-lookup"><span data-stu-id="963c8-118">After the workflow status is reset to Draft, it becomes available for editing on the **Vendor invoice** page.</span></span>
<!--feature detail end -->



