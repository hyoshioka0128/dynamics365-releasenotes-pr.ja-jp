---
title: 名刺のスキャン
description: 名刺をスキャンして Dynamics 365 に読み込むと、入力に時間を費やさずにすみます。
author: relnotes
ms.reviewer: shujoshi
ms.date: 12/24/2019
ms.assetid: cc61278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: naitikds
dynamics365pdf: true
ms.openlocfilehash: 1c1d3fb150016292ba700a00876598b5a53b4760
ms.sourcegitcommit: ba5b15c33dc3669937bf5219b1b38995cffb661b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2947604"
---
# <a name="business-card-scan"></a><span data-ttu-id="7724d-103">名刺のスキャン</span><span class="sxs-lookup"><span data-stu-id="7724d-103">Business card scan</span></span>


| <span data-ttu-id="7724d-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7724d-104">Enabled for</span></span>    |  <span data-ttu-id="7724d-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7724d-105">Public preview</span></span> | <span data-ttu-id="7724d-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="7724d-106">Early access</span></span> | <span data-ttu-id="7724d-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="7724d-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="7724d-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="7724d-108">End users, automatically</span></span>|-|<span data-ttu-id="7724d-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7724d-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7724d-110">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7724d-110">Aug 1, 2019</span></span>| <span data-ttu-id="7724d-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7724d-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7724d-112">2019 年 10 月 6 日</span><span class="sxs-lookup"><span data-stu-id="7724d-112">Oct 6, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="7724d-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7724d-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7724d-114">顧客から最も多い要望です。</span><span class="sxs-lookup"><span data-stu-id="7724d-114">A top request by customers.</span></span> 

<span data-ttu-id="7724d-115">会議でよく名刺を受け取りますが、その後どこかに置き忘れたり、なくしたりしがちです。</span><span class="sxs-lookup"><span data-stu-id="7724d-115">Business cards are typically handed out at meetings, then often misplaced or lost.</span></span> <span data-ttu-id="7724d-116">営業のプロフェッショナルは、これらの名刺から情報をすばやく収集して、より重要なタスクに集中できるようにする方法を必要とします。</span><span class="sxs-lookup"><span data-stu-id="7724d-116">Sales professionals need a way to quickly capture information from these cards, freeing them to focus on more important tasks.</span></span> <span data-ttu-id="7724d-117">名刺のスキャンは、カンファレンスやオフサイトでの会議などの外出中に特に便利です。</span><span class="sxs-lookup"><span data-stu-id="7724d-117">Scanning business cards is particularly useful when on the go, at conferences, or at offsite meetings.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7724d-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7724d-118">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7724d-119">名刺を携帯電話や Web でスキャンできます。</span><span class="sxs-lookup"><span data-stu-id="7724d-119">Business cards can be scanned via mobile or web.</span></span> <span data-ttu-id="7724d-120">スキャナーは、名刺の関連情報を分析し、システム内の各フィールドを自動的に更新します。</span><span class="sxs-lookup"><span data-stu-id="7724d-120">The scanner will analyze the card for relevant information and automatically update respective fields in the system.</span></span> <span data-ttu-id="7724d-121">この機能では、設定する代替フィールドをユーザーが選択できるようにする構成も提供されます。</span><span class="sxs-lookup"><span data-stu-id="7724d-121">The feature also offers configuration, allowing users to select alternative fields to populate.</span></span>

<span data-ttu-id="7724d-122">名刺機能の対応状況については、「[リージョン別の使用可能な機能とそのリリースの状態](https://docs.microsoft.com/ai-builder/availability-region#availability-and-release-status-of-features-by-region)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="7724d-122">To learn about the availability of the business card feature, see [Feature availability by region](https://docs.microsoft.com/ai-builder/availability-region#availability-and-release-status-of-features-by-region).</span></span>
<!--feature detail end -->

<span data-ttu-id="7724d-123">![名刺のスキャン](media/BusinessCardScan_Mockups.png "名刺のスキャン")</span><span class="sxs-lookup"><span data-stu-id="7724d-123">![Business card scan](media/BusinessCardScan_Mockups.png "Business card scan")</span></span>
<!-- Picture 1 -->

> [!NOTE]
> <span data-ttu-id="7724d-124">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="7724d-124">This feature is available in the Unified Interface only.</span></span> <span data-ttu-id="7724d-125">Dynamics 365 Sales Enterprise のみを対象としています。</span><span class="sxs-lookup"><span data-stu-id="7724d-125">It is intended only for Dynamics 365 Sales Enterprise.</span></span>





## <a name="see-also"></a><span data-ttu-id="7724d-126">関連項目</span><span class="sxs-lookup"><span data-stu-id="7724d-126">See also</span></span>
<span data-ttu-id="7724d-127">[名刺のスキャン](https://docs.microsoft.com/dynamics365/customer-engagement/sales-enterprise/scan-business-cards) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="7724d-127">[Scan business cards](https://docs.microsoft.com/dynamics365/customer-engagement/sales-enterprise/scan-business-cards) (docs)</span></span>
