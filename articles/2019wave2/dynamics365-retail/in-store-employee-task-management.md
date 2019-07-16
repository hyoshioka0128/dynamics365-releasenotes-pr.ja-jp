---
title: 店内従業員のタスク管理
description: 店内従業員のタスク管理
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 8063278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: gmohanv
dynamics365pdf: true
ms.openlocfilehash: a4fbc22332aeb8e25912093d4b2b4f8d92984e07
ms.sourcegitcommit: ce44199897bc0c276cd02c99cc1d216f198734b0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1691581"
---
# <a name="in-store-employee-task-management"></a><span data-ttu-id="d1b4e-103">店内従業員のタスク管理</span><span class="sxs-lookup"><span data-stu-id="d1b4e-103">In-store employee task management</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="d1b4e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="d1b4e-104">Enabled for</span></span>    |  <span data-ttu-id="d1b4e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d1b4e-105">Public preview</span></span> | <span data-ttu-id="d1b4e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="d1b4e-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="d1b4e-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="d1b4e-107">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="d1b4e-108">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="d1b4e-108">December 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="d1b4e-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d1b4e-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d1b4e-110">注文を出すチャネルと注文が履行されるチャネルが異なっていてもよい小売業のオムニチャネルの世界では、顧客への好影響を確実にするために、さまざまなチャネル間での効率的な情報の流れが必要です。</span><span class="sxs-lookup"><span data-stu-id="d1b4e-110">In the omnichannel world of retail where orders can be placed from one channel and the fulfillment can happen from another, there is need for efficient information flow between the various channels to ensure positive customer impact.</span></span> <span data-ttu-id="d1b4e-111">さらに、本社の特定のペルソナ (地域マネージャーなど) は、1 つ以上の店舗で実行する必要があるさまざまなイニシアチブや活動のために、これらの店舗のためのタスクを作成する機能を必要としています。</span><span class="sxs-lookup"><span data-stu-id="d1b4e-111">Moreover, certain personas in headquarters (such as regional managers) want the capability to create tasks for one or more stores for various initiatives and activities that these stores need to perform.</span></span> <span data-ttu-id="d1b4e-112">その結果、店舗マネージャーは、割り当てられたロールを果たすために行う必要があることをすばやく見つける必要がある作業者にタスクを簡単に割り当てる機能を求めています。</span><span class="sxs-lookup"><span data-stu-id="d1b4e-112">Consequently, store managers want the ability to easily allocate tasks to workers who should be empowered to quickly find what they need to do to perform their assigned roles.</span></span> <span data-ttu-id="d1b4e-113">これまで、小売業者はそのようなコミュニケーションのために電子メール、電話会議、またはバインダーのようなツールに頼っていました。</span><span class="sxs-lookup"><span data-stu-id="d1b4e-113">Historically, retailers have relied on tools such as email, conference calls, or binders for such communications.</span></span> <span data-ttu-id="d1b4e-114">これらのツールには多くの課題があります。たとえば、重要な電子メールが重要でない電子メールに埋もれる、本社のペルソナや店舗のマネージャーはタスクの進捗状況をリアルタイムで把握できない、最新の優先順位付きタスク リストが利用できない、といった場合があります。 
</span><span class="sxs-lookup"><span data-stu-id="d1b4e-114">These tools have numerous challenges, for example, important emails can get buried under unimportant emails, headquarters personas and store managers may not have real time visibility in to the progress of tasks, and an updated prioritized list of tasks may not be available. 
</span></span><!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d1b4e-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d1b4e-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d1b4e-116">新しいタスク管理ソリューションは、本社のペルソナと店舗のマネージャーがタスクを素早く作成し、進捗状況をリアルタイムで表示できるようにすることを目的としています。</span><span class="sxs-lookup"><span data-stu-id="d1b4e-116">The new task management solution aims to allow headquarters personas and store managers to quickly create tasks and view their progress in real time.</span></span> <span data-ttu-id="d1b4e-117">店員は、優先順位の付けられたタスクのリストにアクセスできるため、他のタスクよりも重要なタスクを選ぶことができます。</span><span class="sxs-lookup"><span data-stu-id="d1b4e-117">Store workers will have access to a prioritized list of tasks, enabling them to pick the critical tasks ahead of the other tasks.</span></span> <span data-ttu-id="d1b4e-118">このタスク管理ソリューションを利用することで、店舗のコンプライアンスと効率も向上します。</span><span class="sxs-lookup"><span data-stu-id="d1b4e-118">Leveraging this task management solution will also result in improvement in the store compliance and efficiency.</span></span>
<!--feature detail end -->










