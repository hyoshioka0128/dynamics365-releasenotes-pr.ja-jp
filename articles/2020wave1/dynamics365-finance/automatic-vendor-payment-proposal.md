---
title: 自動仕入先支払提案
description: この機能は、支払提案を自動的に生成し、承認のためのワークフロー プロセスにルーティングすることにより、仕入先支払のタイミングの最適化を支援します。
author: relnotes
ms.reviewer: roschlom
ms.date: 02/04/2020
ms.assetid: 6a2a6bad-4dcb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 381cd6cb2192514b4041c519792bfa6554573bd9
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3032611"
---
# <a name="automatic-vendor-payment-proposal"></a><span data-ttu-id="87403-103">自動仕入先支払提案</span><span class="sxs-lookup"><span data-stu-id="87403-103">Automatic vendor payment proposal</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="87403-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="87403-104">Enabled for</span></span>    |  <span data-ttu-id="87403-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="87403-105">Public preview</span></span> | <span data-ttu-id="87403-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="87403-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="87403-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="87403-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="87403-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="87403-108">Jul 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="87403-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="87403-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="87403-110">組織は通常、特定の状況に適用される一連のルールに従って仕入先への支払を行います。</span><span class="sxs-lookup"><span data-stu-id="87403-110">Organizations typically pay vendors according to a set of rules that apply to their specific circumstances.</span></span> <span data-ttu-id="87403-111">たとえば、仕入先を重要度の順にランク付けして、最も重要な仕入先から先に支払う場合があります。</span><span class="sxs-lookup"><span data-stu-id="87403-111">For example, they might rank vendors in order of importance and pay their most important vendors first.</span></span> <span data-ttu-id="87403-112">他の組織では、仕入先を分類する 1 つ以上の異なる方法を使用して、特定の日に特定のカテゴリーの仕入先に支払う場合もあります。</span><span class="sxs-lookup"><span data-stu-id="87403-112">Other organizations might use one or more different methods of categorizing their vendors and pay vendors in specific categories on specific days.</span></span> <span data-ttu-id="87403-113">このプロセスを自動化すると、組織は独自のルールを適用して、手動プロセスを使用するよりも一貫性のある効率的な方法で仕入先支払提案を作成できます。</span><span class="sxs-lookup"><span data-stu-id="87403-113">Automating this process helps organizations apply their own rules to create vendor payment proposals more consistently and efficiently than is possible using a manual process.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="87403-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="87403-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="87403-115">会計登録者と買掛金勘定マネージャーは、“ルール エンジン” を使用して製品内でルールを定義します。このルールにより、システムは支払う必要がある仕入先を学習し、それらの仕入先に対する支払時期を決定できます。</span><span class="sxs-lookup"><span data-stu-id="87403-115">A “rules engine” lets treasurers and accounts payable managers define rules within the product to help the system learn which vendors to pay, and then determine when to pay them.</span></span> <span data-ttu-id="87403-116">システムはこの情報を使用して支払提案を自動的に生成し、承認のためのワークフロー プロセスに送信します。</span><span class="sxs-lookup"><span data-stu-id="87403-116">The system then uses this information to generate payment proposals automatically and send them through a workflow process for approval.</span></span>  
<!--feature detail end -->









