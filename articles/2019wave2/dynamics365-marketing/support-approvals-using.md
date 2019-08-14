---
title: Microsoft Flow を使用した承認のサポート
description: Microsoft Flow を使用した承認のサポート
author: jain-shailesh
ms.reviewer: kamaybac
ms.date: 07/31/2019
ms.assetid: c661278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: shjain
dynamics365pdf: true
ms.openlocfilehash: 3b3edadeb5bbad232d32065d4cf57dcf9e43b45c
ms.sourcegitcommit: d7e3131b7435c3c6581f61ee059895f9045cc379
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/03/2019
ms.locfileid: "1856217"
---
# <a name="support-approvals-using-microsoft-flow"></a><span data-ttu-id="8f591-103">Microsoft Flow を使用した承認のサポート</span><span class="sxs-lookup"><span data-stu-id="8f591-103">Support approvals using Microsoft Flow</span></span>
[!include[dynamics365-marketing banner](../includes/dynamics365-marketing.md)]

| <span data-ttu-id="8f591-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8f591-104">Enabled for</span></span>    |  <span data-ttu-id="8f591-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8f591-105">Public preview</span></span> | <span data-ttu-id="8f591-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8f591-106">General availability</span></span> | <span data-ttu-id="8f591-107">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="8f591-107">Early Access</span></span> |
| ---------- | ---------- |---------- |---------- |
|<span data-ttu-id="8f591-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="8f591-108">End users, automatically</span></span>|| <span data-ttu-id="8f591-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="8f591-109">October 2019</span></span>|<span data-ttu-id="8f591-110">はい</span><span class="sxs-lookup"><span data-stu-id="8f591-110">Yes</span></span> |






## <a name="feature-details"></a><span data-ttu-id="8f591-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8f591-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8f591-112">Dynamics 365 for Marketing では、カスタマイズ可能な承認ワークフローがサポートされるようになり、新しいマーケティング資料やキャンペーンが有効になる前に適切に承認されます。</span><span class="sxs-lookup"><span data-stu-id="8f591-112">Dynamics 365 for Marketing now supports a customizable approval workflow that helps make sure new marketing materials and campaigns are properly approved before going into effect.</span></span> 

<span data-ttu-id="8f591-113">マーケティング電子メールや顧客体験などの新しいレコードの設定を完了したマーケティング担当者は、1 回クリックするだけで、そのレコードを承認のために送信できます。</span><span class="sxs-lookup"><span data-stu-id="8f591-113">After marketers finish setting up a new record, such as a marketing email or customer journey, they can send that record for approval with just a single click.</span></span> <span data-ttu-id="8f591-114">承認ワークフローの設定方法に基づいて、関連マネージャーに承認要求が通知されます。</span><span class="sxs-lookup"><span data-stu-id="8f591-114">Based on how the approval workflow is set up, the relevant manager is then notified of the approval request.</span></span> <span data-ttu-id="8f591-115">コア承認シナリオには以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="8f591-115">Core approval scenarios include:</span></span> 

-  <span data-ttu-id="8f591-116">レコードの承認を要求する</span><span class="sxs-lookup"><span data-stu-id="8f591-116">Request approval for a record</span></span> 
-  <span data-ttu-id="8f591-117">承認の要求を取り消す</span><span class="sxs-lookup"><span data-stu-id="8f591-117">Cancel request for approval</span></span> 
-  <span data-ttu-id="8f591-118">承認要求を承認または却下する</span><span class="sxs-lookup"><span data-stu-id="8f591-118">Approve or reject an approval request</span></span> 
-  <span data-ttu-id="8f591-119">承認依頼を委任する</span><span class="sxs-lookup"><span data-stu-id="8f591-119">Delegate a request for approval</span></span>
-  <span data-ttu-id="8f591-120">期限切れの承認要求を管理する</span><span class="sxs-lookup"><span data-stu-id="8f591-120">Manage an overdue approval request</span></span> 

<span data-ttu-id="8f591-121">承認システムは、コア マーケティング エンティティに基づいて簡単な承認プロセスを強制することができる Microsoft Flow アプリとして配布されます。</span><span class="sxs-lookup"><span data-stu-id="8f591-121">The approval system is delivered as a Microsoft Flow app that can enforce a simple approval process based on core marketing entities.</span></span> <span data-ttu-id="8f591-122">各組織にはそれぞれ独自のビジネス プロセスと階層があるため、Microsoft Flow ではビジネス ユーザー、作成者、またはパートナーによる簡単なカスタマイズに必要な柔軟性が提供されます。</span><span class="sxs-lookup"><span data-stu-id="8f591-122">Because each organization probably has its own business process and hierarchy, Microsoft Flow provides the flexibility required for easy customization by business users, makers, or partners.</span></span>
<!--feature detail end -->

<span data-ttu-id="8f591-123">![承認ワークフロー デザイナー](media/approval-workflow.png "承認ワークフロー デザイナー")</span><span class="sxs-lookup"><span data-stu-id="8f591-123">![Approval workflow designer](media/approval-workflow.png "Approval workflow designer")</span></span>
<!-- Picture 1 -->










