---
title: 簡素化されたリード管理エクスペリエンス
description: 営業担当者による製品での手作業や不要なナビゲーションを減らし、それによってユーザーの生産性と顧客満足度を向上させるためのいくつかの改善が、一般的なワークフローとプロセスに対して行われています。
author: relnotes
ms.reviewer: shujoshi
ms.date: 10/16/2019
ms.assetid: c861278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pachatte
dynamics365pdf: true
ms.openlocfilehash: 80ad09556ad3667201913f3b826f02c3c93b8fbc
ms.sourcegitcommit: b0fef00d4f04f2507056a10ecce699767c669119
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2661726"
---
# <a name="simplified-lead-management-experience"></a><span data-ttu-id="6bb6c-103">簡素化されたリード管理エクスペリエンス</span><span class="sxs-lookup"><span data-stu-id="6bb6c-103">Simplified lead management experience</span></span>


| <span data-ttu-id="6bb6c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="6bb6c-104">Enabled for</span></span>    |  <span data-ttu-id="6bb6c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6bb6c-105">Public preview</span></span> | <span data-ttu-id="6bb6c-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="6bb6c-106">Early access</span></span> | <span data-ttu-id="6bb6c-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="6bb6c-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="6bb6c-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="6bb6c-108">End users, automatically</span></span>|-|<span data-ttu-id="6bb6c-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6bb6c-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6bb6c-110">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="6bb6c-110">Aug 2, 2019</span></span>| <span data-ttu-id="6bb6c-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6bb6c-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6bb6c-112">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="6bb6c-112">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="6bb6c-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="6bb6c-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="6bb6c-114">お客様の生産性を最大化するために、リード管理に関連する上位シナリオ全体にわたって改善を導入しています。</span><span class="sxs-lookup"><span data-stu-id="6bb6c-114">To help our customers maximize productivity, we are introducing improvements across top scenarios related to lead management.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="6bb6c-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6bb6c-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6bb6c-116">主なシナリオは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="6bb6c-116">Top scenarios include:</span></span>  

- <span data-ttu-id="6bb6c-117">営業担当者が新規リード作成時に既存の取引先担当者や取引先企業を選択した場合に、取引先担当者や会社関連項目を自動入力します。</span><span class="sxs-lookup"><span data-stu-id="6bb6c-117">Autopopulate contact and/or company-related fields when a sales rep selects an existing contact and/or account at the time of creating a new lead.</span></span>   
- <span data-ttu-id="6bb6c-118">リードが評価された後で営業案件レコードでリードをプロモートするときに、営業担当者によってキャプチャされたメモと添付ファイルを表示します。</span><span class="sxs-lookup"><span data-stu-id="6bb6c-118">Display notes and attachments captured by a sales rep when promoting a lead in the opportunity record after the lead is qualified.</span></span>  
- <span data-ttu-id="6bb6c-119">営業担当がリードを見込みありと評価して、販売サイクルの次のステージにすばやく移動し、必要に応じて、リード作成エクスペリエンスに対して管理者によって構成された組織レベルの設定に基づいて、営業案件、取引先企業、または取引先担当者のレコードを作成できるようにします。</span><span class="sxs-lookup"><span data-stu-id="6bb6c-119">Enable sales reps to qualify leads and quickly move to the next stage of the sales cycle; optionally create opportunity, account, or contact records based on the organization-level settings configured by the admin for the lead creation experience.</span></span> <span data-ttu-id="6bb6c-120">既定の設定は**はい**で、リードを見込みありと評価するときに取引先企業、取引先担当者、および営業案件が自動的に作成されます。</span><span class="sxs-lookup"><span data-stu-id="6bb6c-120">The default setting would be **Yes**, which would automatically create an account, contact, and opportunity when qualifying a lead.</span></span>

<span data-ttu-id="6bb6c-121">![リードの見込み評価中のオプション](media/additionaloptions.jpg "リードの見込み評価中のオプション")</span><span class="sxs-lookup"><span data-stu-id="6bb6c-121">![Options while qualifying a lead](media/additionaloptions.jpg "Options while qualifying a lead")</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="6bb6c-122">この機能は、従来の Web クライアントと統一インターフェイスの両方で使用できます。</span><span class="sxs-lookup"><span data-stu-id="6bb6c-122">This feature is available in both the legacy web client and Unified Interface.</span></span> <span data-ttu-id="6bb6c-123">この機能は、Dynamics 365 Sales Enterprise と Dynamics 365 Sales Professional で使用できます。</span><span class="sxs-lookup"><span data-stu-id="6bb6c-123">This capability is available in Dynamics 365 Sales Enterprise and Dynamics 365 Sales Professional.</span></span>







## <a name="see-also"></a><span data-ttu-id="6bb6c-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="6bb6c-124">See also</span></span>
<span data-ttu-id="6bb6c-125">[機能の探索](https://aka.ms/ROGS19RW2ROV1) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="6bb6c-125">[Feature exploration](https://aka.ms/ROGS19RW2ROV1) (video)</span></span>

<span data-ttu-id="6bb6c-126">[リードを見込みありと評価](https://docs.microsoft.com/dynamics365/customer-engagement/sales-enterprise/qualify-lead-convert-opportunity-sales) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="6bb6c-126">[Qualify Lead](https://docs.microsoft.com/dynamics365/customer-engagement/sales-enterprise/qualify-lead-convert-opportunity-sales) (docs)</span></span>
