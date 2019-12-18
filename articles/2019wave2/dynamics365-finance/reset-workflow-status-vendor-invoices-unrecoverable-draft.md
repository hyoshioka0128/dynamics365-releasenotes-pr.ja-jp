---
title: 仕入先請求書のワークフローの状態を回復不能から下書きにリセットする
description: システムが中断された後に、ドキュメントが回復不能状態になることがあります。 ユーザーは、サポートに連絡して支援を依頼しなくても、自分でドキュメントの状態を下書きにリセットできます。
author: relnotes
ms.reviewer: roschlom
ms.date: 11/15/2019
ms.assetid: 36ae1e1a-b0a9-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 95b8b0f694a8f0786f98739ab5cda2f63468d0e6
ms.sourcegitcommit: cf8b2ba74d2b553c2a721942221c285ffcf184c5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892782"
---
# <a name="reset-workflow-status-for-vendor-invoices-from-unrecoverable-to-draft"></a><span data-ttu-id="6143b-104">仕入先請求書のワークフローの状態を回復不能から下書きにリセットする</span><span class="sxs-lookup"><span data-stu-id="6143b-104">Reset workflow status for vendor invoices from Unrecoverable to Draft</span></span>


| <span data-ttu-id="6143b-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="6143b-105">Enabled for</span></span>    |  <span data-ttu-id="6143b-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6143b-106">Public preview</span></span> | <span data-ttu-id="6143b-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="6143b-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6143b-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="6143b-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="6143b-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6143b-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6143b-110">2019 年 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="6143b-110">Aug 5, 2019</span></span>| <span data-ttu-id="6143b-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6143b-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6143b-112">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="6143b-112">Oct 1, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="6143b-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6143b-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6143b-114">**ワークフロー履歴**ページを使用して、ワークフローの状態を下書きにリセットできます。</span><span class="sxs-lookup"><span data-stu-id="6143b-114">You can use the **Workflow history** page to reset the workflow status to Draft.</span></span> <span data-ttu-id="6143b-115">このページは、**仕入先請求書**ページから、または**共通** > **照会** > **ワークフロー**に移動して開くことができます。</span><span class="sxs-lookup"><span data-stu-id="6143b-115">This page can be opened from the **Vendor invoice** page or by going to **Common** > **Inquires** > **Workflow**.</span></span> <span data-ttu-id="6143b-116">ワークフローの状態を下書きにリセットするには、**取り消し**を選択します。</span><span class="sxs-lookup"><span data-stu-id="6143b-116">To reset the workflow status to Draft, select **Recall**.</span></span> <span data-ttu-id="6143b-117">**仕入先請求書**または**保留中の仕入先請求書**ページで取り消しアクションを選択することでワークフローの状態を下書きにリセットすることもできます。</span><span class="sxs-lookup"><span data-stu-id="6143b-117">You can also reset the workflow status to Draft by selecting the Recall action on either the **Vendor invoice** or **Pending vendor invoices** page.</span></span> <span data-ttu-id="6143b-118">ワークフローの状態が下書きにリセットされると、**仕入先請求書**ページで編集可能になります。</span><span class="sxs-lookup"><span data-stu-id="6143b-118">After the workflow status is reset to Draft, it becomes available for editing on the **Vendor invoice** page.</span></span>
<!--feature detail end -->







