---
title: Dynamics GP の勘定科目表の移行の強化
description: 既存の Dynamics GP Cloud Migration ツールが、主なセグメントを勘定として使用して勘定科目表を引き継ぎ、他のセグメントと分析コードも含めるように更新されます。 また、このツールで、関連するトランザクションに自動的に割り当てられた分析コードを持つトランザクションも作成されます。
author: relnotes
ms.reviewer: edupont
ms.date: 12/05/2019
ms.assetid: 75b4769c-b60b-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: jenolson
dynamics365pdf: true
ms.openlocfilehash: 7b858f59c1765869235a0af662d60678e76d393a
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986669"
---
# <a name="enhanced-dynamics-gp-chart-of-accounts-migration"></a><span data-ttu-id="7e330-104">Dynamics GP の勘定科目表の移行の強化</span><span class="sxs-lookup"><span data-stu-id="7e330-104">Enhanced Dynamics GP Chart of Accounts migration</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="7e330-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="7e330-105">Enabled for</span></span>    |  <span data-ttu-id="7e330-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7e330-106">Public preview</span></span> | <span data-ttu-id="7e330-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="7e330-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7e330-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="7e330-108">End users, automatically</span></span>|<span data-ttu-id="7e330-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="7e330-109">Feb 2020</span></span>| <span data-ttu-id="7e330-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="7e330-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="7e330-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7e330-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7e330-112">顧客は、Business Central のトランザクションに割り当てられた Dynamics GP のセグメントを確認できるようになります。</span><span class="sxs-lookup"><span data-stu-id="7e330-112">Customers will be able to see the segments from Dynamics GP assigned to the transactions in Business Central.</span></span> <span data-ttu-id="7e330-113">これにより、顧客は分析コード別にレポートを実行して、それらの分析コード別の金額の内訳を確認することができます。</span><span class="sxs-lookup"><span data-stu-id="7e330-113">This way, customers can run reports by dimensions to see the breakdown of amounts by those dimensions.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7e330-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7e330-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7e330-115">このリリースでは、セグメントが G/L トランザクションの分析コードとして移行されるようにする拡張機能を構築します。</span><span class="sxs-lookup"><span data-stu-id="7e330-115">In this release, we build out the extension to have the segments migrated as dimensions on the G/L transactions.</span></span>  
<!--feature detail end -->









