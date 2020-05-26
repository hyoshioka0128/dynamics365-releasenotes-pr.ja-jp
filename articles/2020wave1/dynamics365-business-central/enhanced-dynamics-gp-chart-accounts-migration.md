---
title: Dynamics GP の勘定科目表の移行の強化
description: 既存の Dynamics GP Cloud Migration ツールが更新され、主なセグメントを勘定として使用して勘定科目表を引き継ぎます。 移行には、他のセグメントも分析コードとして含まれます。 このツールでは、関連するトランザクションに自動的に割り当てられた分析コードを持つトランザクションが作成されます。
author: relnotes
ms.reviewer: edupont
ms.date: 04/06/2020
ms.assetid: 75b4769c-b60b-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: jenolson
dynamics365pdf: true
ms.openlocfilehash: f0624c24e5e773b03636dc92ad942500d814d0e7
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255103"
---
# <a name="enhanced-dynamics-gp-chart-of-accounts-migration"></a><span data-ttu-id="a691a-105">Dynamics GP の勘定科目表の移行の強化</span><span class="sxs-lookup"><span data-stu-id="a691a-105">Enhanced Dynamics GP Chart of Accounts migration</span></span>


| <span data-ttu-id="a691a-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="a691a-106">Enabled for</span></span>    |  <span data-ttu-id="a691a-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a691a-107">Public preview</span></span> | <span data-ttu-id="a691a-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="a691a-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a691a-109">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a691a-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="a691a-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a691a-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a691a-111">2020 年 3 月 2 日</span><span class="sxs-lookup"><span data-stu-id="a691a-111">Mar 2, 2020</span></span>| <span data-ttu-id="a691a-112">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a691a-112">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a691a-113">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a691a-113">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a691a-114">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a691a-114">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a691a-115">顧客は、Business Central の移行されたトランザクションに割り当てられた Dynamics GP のセグメントを確認できます。</span><span class="sxs-lookup"><span data-stu-id="a691a-115">Customers can see the segments from Dynamics GP assigned to the migrated transactions in Business Central.</span></span> <span data-ttu-id="a691a-116">これにより、顧客は分析コード別にレポートを実行して、それらの分析コード別の金額の内訳を確認することができます。</span><span class="sxs-lookup"><span data-stu-id="a691a-116">This way, customers can run reports by dimensions to see the breakdown of amounts by those dimensions.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a691a-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a691a-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a691a-118">このリリースでは、セグメントが G/L トランザクションの分析コードとして移行されるようにする移行ツールを構築します。</span><span class="sxs-lookup"><span data-stu-id="a691a-118">In this release, we will build out the migration tool to have the segments migrated as dimensions on the G/L transactions.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="a691a-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="a691a-119">See also</span></span>

<!--docs start-->
<span data-ttu-id="a691a-120">[Dynamics GP から Business Central Online に移行する](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/migrate-dynamics-gp) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="a691a-120">[Migrate to Business Central Online from Dynamics GP](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/migrate-dynamics-gp) (docs)</span></span>
<!--docs end-->
