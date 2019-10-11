---
title: 簡素化されたリード管理エクスペリエンス
description: 営業担当者による製品での手作業や不要なナビゲーションを減らし、それによってユーザーの生産性と顧客満足度を向上させるためのいくつかの改善が、一般的なワークフローとプロセスに対して行われています。
author: relnotes
ms.reviewer: shujoshi
ms.date: 09/05/2019
ms.assetid: c861278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pachatte
dynamics365pdf: true
ms.openlocfilehash: 39ef595f5b2df535c6115f41fd3b21dcb83102b8
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141736"
---
# <a name="simplified-lead-management-experience"></a><span data-ttu-id="cc0dc-103">簡素化されたリード管理エクスペリエンス</span><span class="sxs-lookup"><span data-stu-id="cc0dc-103">Simplified lead management experience</span></span>
[!include[dynamics365-sales banner](../includes/dynamics365-sales.md)]

| <span data-ttu-id="cc0dc-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cc0dc-104">Enabled for</span></span>    |  <span data-ttu-id="cc0dc-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cc0dc-105">Public preview</span></span> | <span data-ttu-id="cc0dc-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="cc0dc-106">Early access</span></span> | <span data-ttu-id="cc0dc-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="cc0dc-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="cc0dc-108">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="cc0dc-108">Users, automatically</span></span>|-|<span data-ttu-id="cc0dc-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="cc0dc-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="cc0dc-110">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="cc0dc-110">Aug 2, 2019</span></span>| <span data-ttu-id="cc0dc-111">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="cc0dc-111">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="cc0dc-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="cc0dc-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="cc0dc-113">お客様の生産性を最大化するために、リード管理に関連する上位シナリオ全体にわたって改善を導入しています。</span><span class="sxs-lookup"><span data-stu-id="cc0dc-113">To help our customers maximize productivity, we are introducing improvements across top scenarios related to lead management.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="cc0dc-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cc0dc-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cc0dc-115">主なシナリオは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="cc0dc-115">Top scenarios include:</span></span>  

- <span data-ttu-id="cc0dc-116">営業担当者が新規リード作成時に既存の取引先担当者や取引先企業を選択した場合に、取引先担当者や会社関連項目を自動入力します。</span><span class="sxs-lookup"><span data-stu-id="cc0dc-116">Autopopulate contact and/or company-related fields when a sales rep selects an existing contact and/or account at the creation of a new lead.</span></span>   
- <span data-ttu-id="cc0dc-117">リードが評価された後で営業案件レコードでリードをプロモートするときに、営業担当者によってキャプチャされたメモと添付ファイルを表示します。</span><span class="sxs-lookup"><span data-stu-id="cc0dc-117">Display notes and attachments captured by a sales rep when promoting a lead in the opportunity record after the lead is qualified.</span></span>  
- <span data-ttu-id="cc0dc-118">営業担当がリードを評価して、販売サイクルの次のステージにすばやく移動し、必要に応じて、リード作成エクスペリエンスに対して管理者によって構成された組織レベルの設定に基づいて、営業案件、取引先企業、または取引先担当者のレコードを作成できるようにします。</span><span class="sxs-lookup"><span data-stu-id="cc0dc-118">Enable sales reps to qualify leads and quickly move to the next stage of the sales cycle: optionally create opportunity, account, or contact records based on the organization-level settings configured by the admin for the lead creation experience.</span></span> <span data-ttu-id="cc0dc-119">既定の設定は**はい**で、リードを見込みありと評価するときに取引先企業、取引先担当者、および営業案件が自動的に作成されます。</span><span class="sxs-lookup"><span data-stu-id="cc0dc-119">The default setting would be **Yes**, which would automatically create an account, contact, and opportunity when qualifying a lead.</span></span>

<span data-ttu-id="cc0dc-120">![リードの見込み評価中のオプション](media/additionaloptions.jpg "リードの見込み評価中のオプション")</span><span class="sxs-lookup"><span data-stu-id="cc0dc-120">![Options while qualifying a lead](media/additionaloptions.jpg "Options while qualifying a lead")</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="cc0dc-121">この機能は、従来の Web クライアントと統一インターフェイスの両方で使用できます。</span><span class="sxs-lookup"><span data-stu-id="cc0dc-121">This feature is available in both the legacy web client and Unified Interface.</span></span>









## <a name="see-also"></a><span data-ttu-id="cc0dc-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="cc0dc-122">See also</span></span>
<span data-ttu-id="cc0dc-123">[機能の探索](https://aka.ms/ROGS19RW2ROV1) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="cc0dc-123">[Feature exploration](https://aka.ms/ROGS19RW2ROV1) (video)</span></span>

<span data-ttu-id="cc0dc-124">[リードを見込みありと評価](https://docs.microsoft.com/dynamics365/customer-engagement/sales-enterprise/qualify-lead-convert-opportunity-sales) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="cc0dc-124">[Qualify Lead](https://docs.microsoft.com/dynamics365/customer-engagement/sales-enterprise/qualify-lead-convert-opportunity-sales) (docs)</span></span>
