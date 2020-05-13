---
title: バッチ ジョブの優先順位ベースのスケジューリング
description: バッチ ジョブの優先順位ベースのスケジューリング
author: relnotes
ms.reviewer: kfend
ms.date: 02/03/2020
ms.assetid: f462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: peakerbl
dynamics365pdf: true
ms.openlocfilehash: 44afe0212e5c9e700956e4dd8e8302a53a66e352
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3058554"
---
# <a name="priority-based-scheduling-for-batch-jobs"></a><span data-ttu-id="ba273-103">バッチ ジョブの優先順位ベースのスケジューリング</span><span class="sxs-lookup"><span data-stu-id="ba273-103">Priority-based scheduling for batch jobs</span></span>


| <span data-ttu-id="ba273-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ba273-104">Enabled for</span></span>    |  <span data-ttu-id="ba273-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ba273-105">Public preview</span></span> | <span data-ttu-id="ba273-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ba273-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ba273-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="ba273-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="ba273-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ba273-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ba273-109">2020 年 1 月 31 日</span><span class="sxs-lookup"><span data-stu-id="ba273-109">Jan 31, 2020</span></span>| -|






## <a name="feature-details"></a><span data-ttu-id="ba273-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ba273-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ba273-111">優先順位ベースのスケジューリングは、バッチ グループをインフラストラクチャから切り離します。</span><span class="sxs-lookup"><span data-stu-id="ba273-111">Priority-based scheduling decouples batch groups from the infrastructure.</span></span> <span data-ttu-id="ba273-112">サーバーにバッチ ジョブを割り当てる必要がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="ba273-112">It is no longer necessary to assign batch jobs to servers.</span></span> <span data-ttu-id="ba273-113">代わりに、ビジネス要件に基づく相対的なスケジューリング優先順位を使用して、使用可能なバッチ サーバー間でタスクが実行される順序が決定されます。</span><span class="sxs-lookup"><span data-stu-id="ba273-113">Instead, relative scheduling priorities based on business requirements are used to determine the order in which tasks are run across available batch servers.</span></span> <span data-ttu-id="ba273-114">この機能によって、バッチ サーバーを使用した自動的な最適化が有効になります。</span><span class="sxs-lookup"><span data-stu-id="ba273-114">The feature enables automatic optimizing with the use of batch servers.</span></span> <span data-ttu-id="ba273-115">スケジューリングの優先順位の分類は、相対的な優先順位を宣言し、ジョブおよびビジネス プロセスの処理順序を決定するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="ba273-115">The scheduling priority classifications are used to declare relative priorities and to determine the processing order of jobs and business processes.</span></span>

<span data-ttu-id="ba273-116">この機能は環境で徐々に有効化されています。</span><span class="sxs-lookup"><span data-stu-id="ba273-116">This feature is gradually being enabled on environments.</span></span>  <span data-ttu-id="ba273-117">関心をお持ちのお客様で、**機能管理**にこれが表示されない場合は、バッチ ジョブの優先順位ベースのスケジューリングへのアクセスを要請するために、Microsoft にご連絡いただくことができます。</span><span class="sxs-lookup"><span data-stu-id="ba273-117">Customers who are interested and can't see it in **Feature management** can contact Microsoft to request access to Priority-based scheduling for batch jobs.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="ba273-118">この機能は、Platform update 31 から限定プレビューで利用できます。</span><span class="sxs-lookup"><span data-stu-id="ba273-118">The feature is available in restricted preview from Platform update 31.</span></span>







## <a name="see-also"></a><span data-ttu-id="ba273-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="ba273-119">See also</span></span>

<span data-ttu-id="ba273-120">[優先順位に基づくバッチ スケジューリング](https://aka.ms/prioritybasedbatchscheduling) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="ba273-120">[Priority-based batch scheduling](https://aka.ms/prioritybasedbatchscheduling) (docs)</span></span>
