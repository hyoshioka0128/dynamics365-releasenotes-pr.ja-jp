---
title: 自動仕入先支払提案
description: この機能は、支払提案を自動的に生成することにより、仕入先支払のタイミングの最適化を支援します。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/06/2020
ms.assetid: 6a2a6bad-4dcb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 26c0a175c004075f228ff0fb334e613d51e83a4a
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255697"
---
# <a name="automatic-vendor-payment-proposal"></a><span data-ttu-id="974c5-103">自動仕入先支払提案</span><span class="sxs-lookup"><span data-stu-id="974c5-103">Automatic vendor payment proposal</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="974c5-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="974c5-104">Enabled for</span></span>    |  <span data-ttu-id="974c5-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="974c5-105">Public preview</span></span> | <span data-ttu-id="974c5-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="974c5-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="974c5-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="974c5-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="974c5-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="974c5-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="974c5-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="974c5-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="974c5-110">組織は通常、特定の状況に適用される一連のルールに従って仕入先への支払を行います。</span><span class="sxs-lookup"><span data-stu-id="974c5-110">Organizations typically pay vendors according to a set of rules that apply to their specific circumstances.</span></span> <span data-ttu-id="974c5-111">たとえば、仕入先を重要度の順にランク付けして、最も重要な仕入先から先に支払う場合があります。</span><span class="sxs-lookup"><span data-stu-id="974c5-111">For example, they might rank vendors in order of importance and pay their most important vendors first.</span></span> <span data-ttu-id="974c5-112">他の組織では、仕入先を分類する 1 つ以上の異なる方法を使用して、特定の日に特定のカテゴリーの仕入先に支払う場合もあります。</span><span class="sxs-lookup"><span data-stu-id="974c5-112">Other organizations might use one or more different methods of categorizing their vendors and pay vendors in specific categories on specific days.</span></span> <span data-ttu-id="974c5-113">このプロセスを自動化すると、組織は独自のスケジュールを適用して、手動プロセスを使用するよりも一貫性のある効率的な方法で仕入先支払提案を作成できます。</span><span class="sxs-lookup"><span data-stu-id="974c5-113">Automating this process helps organizations apply their own schedules to create vendor payment proposals more consistently and efficiently than is possible using a manual process.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="974c5-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="974c5-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="974c5-115">新しいプロセス自動化フレームワークにより、買掛金勘定 (AP) 管理者は、どの仕入先に支払うか、いつ支払うかを定義する自動化スケジュールを定義できます。</span><span class="sxs-lookup"><span data-stu-id="974c5-115">A new process automation framework allows accounts payable (AP) managers to define automation schedules that define what vendors will be paid, and when they'll be paid.</span></span> <span data-ttu-id="974c5-116">一連の支払提案により、AP 管理者は支払う仕入先請求書を選択するための基準を定義できます。</span><span class="sxs-lookup"><span data-stu-id="974c5-116">The payment proposal series allows the AP manager to define the criteria for selecting vendor invoices for payment.</span></span>
 
<!--feature detail end -->









