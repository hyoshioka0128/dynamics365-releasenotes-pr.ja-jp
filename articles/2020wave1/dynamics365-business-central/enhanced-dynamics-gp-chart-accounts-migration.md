---
title: Dynamics GP の勘定科目表の移行の強化
description: 既存の Dynamics GP Cloud Migration ツールが更新され、主なセグメントを勘定として使用して勘定科目表を引き継ぎます。 移行には、他のセグメントも分析コードとして含まれます。 このツールでは、関連するトランザクションに自動的に割り当てられた分析コードを持つトランザクションが作成されます。
author: relnotes
ms.reviewer: edupont
ms.date: 03/19/2020
ms.assetid: 75b4769c-b60b-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: jenolson
dynamics365pdf: true
ms.openlocfilehash: 6f4c90b694941a7687fff17c2d8c3b6dee53668e
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232893"
---
# <a name="enhanced-dynamics-gp-chart-of-accounts-migration"></a><span data-ttu-id="1ccc3-105">Dynamics GP の勘定科目表の移行の強化</span><span class="sxs-lookup"><span data-stu-id="1ccc3-105">Enhanced Dynamics GP Chart of Accounts migration</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="1ccc3-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="1ccc3-106">Enabled for</span></span>    |  <span data-ttu-id="1ccc3-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1ccc3-107">Public preview</span></span> | <span data-ttu-id="1ccc3-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="1ccc3-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1ccc3-109">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="1ccc3-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1ccc3-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1ccc3-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1ccc3-111">2020 年 3 月 2 日</span><span class="sxs-lookup"><span data-stu-id="1ccc3-111">Mar 2, 2020</span></span>| <span data-ttu-id="1ccc3-112">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="1ccc3-112">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1ccc3-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1ccc3-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1ccc3-114">顧客は、Business Central の移行されたトランザクションに割り当てられた Dynamics GP のセグメントを確認できます。</span><span class="sxs-lookup"><span data-stu-id="1ccc3-114">Customers can see the segments from Dynamics GP assigned to the migrated transactions in Business Central.</span></span> <span data-ttu-id="1ccc3-115">これにより、顧客は分析コード別にレポートを実行して、それらの分析コード別の金額の内訳を確認することができます。</span><span class="sxs-lookup"><span data-stu-id="1ccc3-115">This way, customers can run reports by dimensions to see the breakdown of amounts by those dimensions.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1ccc3-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1ccc3-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1ccc3-117">このリリースでは、セグメントが G/L トランザクションの分析コードとして移行されるようにする移行ツールを構築します。</span><span class="sxs-lookup"><span data-stu-id="1ccc3-117">In this release, we will build out the migration tool to have the segments migrated as dimensions on the G/L transactions.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="1ccc3-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="1ccc3-118">See also</span></span>


<!--docs start-->
<span data-ttu-id="1ccc3-119">[Dynamics GP からの移行](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/migrate-dynamics-gp) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="1ccc3-119">[Migrate from Dynamics GP](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/migrate-dynamics-gp) (docs)</span></span>
<!--docs end-->

