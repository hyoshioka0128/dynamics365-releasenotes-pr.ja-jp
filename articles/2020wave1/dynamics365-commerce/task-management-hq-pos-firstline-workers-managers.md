---
title: 第一線の作業者とマネージャー向けの HQ と POS でのタスク管理
description: Dynamics 365 Commerce でのタスク管理は、第一線の地域マネージャーや店舗マネージャーおよび作業者の生産性を高めるための機能で、タスク リストの作成、割り当て基準の管理、バック オフィスと販売時点管理 (POS) アプリケーション間でのステータスのシームレスな追跡を可能にします。
author: relnotes
ms.reviewer: josaw
ms.date: 04/06/2020
ms.assetid: 8063278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: gmohanv
dynamics365pdf: true
ms.openlocfilehash: a9f2cb5c45c73e7b210c287a33e77c0515a17392
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3256159"
---
# <a name="task-management-in-hq-and-pos-for-first-line-workers-and-managers"></a><span data-ttu-id="12ad2-103">第一線の作業者とマネージャー向けの HQ と POS でのタスク管理</span><span class="sxs-lookup"><span data-stu-id="12ad2-103">Task management in HQ and POS for first-line workers and managers</span></span>


| <span data-ttu-id="12ad2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="12ad2-104">Enabled for</span></span>    |  <span data-ttu-id="12ad2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="12ad2-105">Public preview</span></span> | <span data-ttu-id="12ad2-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="12ad2-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="12ad2-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="12ad2-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="12ad2-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="12ad2-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="12ad2-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="12ad2-109">Feb 3, 2020</span></span>| <span data-ttu-id="12ad2-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="12ad2-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="12ad2-111">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="12ad2-111">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="12ad2-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="12ad2-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="12ad2-113">小売業者がタスク リストを作成し、店舗と従業員にタスクを割り当て、ステータスを追跡できます。</span><span class="sxs-lookup"><span data-stu-id="12ad2-113">Retailers can create task lists, assign tasks to stores and workers, and track status.</span></span> <span data-ttu-id="12ad2-114">小売業者は店舗マネージャーや店員に対して、販売時点管理 (POS) で今後のタスクまたは期日が過ぎたタスクについて通知できます。</span><span class="sxs-lookup"><span data-stu-id="12ad2-114">Retailers can notify store managers and store workers about upcoming or past-due tasks in point of sale (POS).</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="12ad2-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="12ad2-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="12ad2-116">タスク管理には以下の機能があります。</span><span class="sxs-lookup"><span data-stu-id="12ad2-116">Task management includes the following features:</span></span>

- <span data-ttu-id="12ad2-117">店舗マネージャーは小売店用のタスク リストを作成し、店舗ごとまたは従業員ごとにステータスを追跡できます。</span><span class="sxs-lookup"><span data-stu-id="12ad2-117">Store managers can create task lists for retail stores and track their status by store or by worker.</span></span> <span data-ttu-id="12ad2-118">定期的なタスクを作成することもできます。</span><span class="sxs-lookup"><span data-stu-id="12ad2-118">Recurring tasks can also be created.</span></span> <span data-ttu-id="12ad2-119">たとえば、木曜日の夜の終業時または毎月の第 1 営業日にタスクを作成できます。</span><span class="sxs-lookup"><span data-stu-id="12ad2-119">For example, tasks can be created for Thursday night closures or the first day of the month.</span></span> 

- <span data-ttu-id="12ad2-120">店舗マネージャーは、POS 内で店舗内の個々の従業員にタスクを割り当て、今後のタスクまたは期日を過ぎたタスクを通知し、ステータスを更新して、アドホック タスクを作成できます。</span><span class="sxs-lookup"><span data-stu-id="12ad2-120">Store managers can assign tasks to individual workers in the store, notify them of upcoming or past-due tasks, update the status, and create ad-hoc tasks within POS.</span></span> 

- <span data-ttu-id="12ad2-121">店員は、POS 内で通知とタスクの詳細を確認し、タスク ステータスを更新できます。</span><span class="sxs-lookup"><span data-stu-id="12ad2-121">Store workers see notifications, view task details, and update the task status in POS.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="12ad2-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="12ad2-122">See also</span></span>

<!--docs start-->
<span data-ttu-id="12ad2-123">[タスク管理](https://docs.microsoft.com/dynamics365/commerce/task-mgmt-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="12ad2-123">[Task management](https://docs.microsoft.com/dynamics365/commerce/task-mgmt-overview) (docs)</span></span>
<!--docs end-->
