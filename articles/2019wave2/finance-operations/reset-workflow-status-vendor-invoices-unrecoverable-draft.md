---
title: 仕入先請求書のワークフローの状態を回復不能から下書きにリセットする
description: システムが中断された後に、ドキュメントが回復不能状態になることがあります。 ユーザーは、サポートに連絡して支援を依頼しなくても、自分でドキュメントの状態を下書きにリセットできます。
author: relnotes
ms.reviewer: roschlom
ms.date: 08/09/2019
ms.assetid: 36ae1e1a-b0a9-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 6700b3ca2e3b00e8f2ecc9e89ea711aa00737789
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2142924"
---
# <a name="reset-workflow-status-for-vendor-invoices-from-unrecoverable-to-draft"></a><span data-ttu-id="ab5af-104">仕入先請求書のワークフローの状態を回復不能から下書きにリセットする</span><span class="sxs-lookup"><span data-stu-id="ab5af-104">Reset workflow status for vendor invoices from Unrecoverable to Draft</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="ab5af-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="ab5af-105">Enabled for</span></span>    |  <span data-ttu-id="ab5af-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ab5af-106">Public preview</span></span> | <span data-ttu-id="ab5af-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="ab5af-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ab5af-108">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="ab5af-108">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="ab5af-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ab5af-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ab5af-110">2019 年 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="ab5af-110">Aug 5, 2019</span></span>| <span data-ttu-id="ab5af-111">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="ab5af-111">Oct 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="ab5af-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ab5af-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ab5af-113">ワークフロー履歴ページを使用して、ワークフローの状態を下書きにリセットできます。</span><span class="sxs-lookup"><span data-stu-id="ab5af-113">You can use the Workflow history page to reset the workflow status to Draft.</span></span> <span data-ttu-id="ab5af-114">このページは、仕入先請求書ページから、または**共通** > **照会** > **ワークフロー**に移動して開くことができます。</span><span class="sxs-lookup"><span data-stu-id="ab5af-114">This page can be opened from the Vendor invoice page or by going to **Common** > **Inquires** > **Workflow**.</span></span> <span data-ttu-id="ab5af-115">ワークフローの状態を下書きにリセットするには、**取り消し**を選択します。</span><span class="sxs-lookup"><span data-stu-id="ab5af-115">To reset the workflow status to Draft, select **Recall**.</span></span> <span data-ttu-id="ab5af-116">仕入先請求書または保留中の仕入先請求書ページで取り消しアクションを選択することでワークフローの状態を下書きにリセットすることもできます。</span><span class="sxs-lookup"><span data-stu-id="ab5af-116">You can also reset the workflow status to Draft by selecting the Recall action on either the Vendor invoice or Pending vendor invoices page.</span></span> <span data-ttu-id="ab5af-117">ワークフローの状態が下書きにリセットされると、仕入先請求書ページで編集可能になります。</span><span class="sxs-lookup"><span data-stu-id="ab5af-117">After the workflow status is reset to Draft, it becomes available for editing on the Vendor invoice page.</span></span>
<!--feature detail end -->
