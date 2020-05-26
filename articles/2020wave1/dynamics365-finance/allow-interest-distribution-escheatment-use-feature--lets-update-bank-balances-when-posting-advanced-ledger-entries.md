---
title: 利息配賦および没収で転記時に銀行残高を更新できるようにする
description: この機能により、利息配賦および没収の詳細な元帳エントリを転記するときに銀行残高を更新できます。
author: relnotes
ms.reviewer: roschlom
ms.date: 05/05/2020
ms.assetid: ac7a6595-b04e-ea11-a812-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: db8c694421859b6f792d28f077450bf4290ccbe4
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3349877"
---
# <a name="allow-interest-distribution-and-escheatment-to-update-bank-balances-when-posting"></a><span data-ttu-id="9ce5c-103">利息配賦および没収で転記時に銀行残高を更新できるようにする</span><span class="sxs-lookup"><span data-stu-id="9ce5c-103">Allow interest distribution and escheatment to update bank balances when posting</span></span>


| <span data-ttu-id="9ce5c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9ce5c-104">Enabled for</span></span>    |  <span data-ttu-id="9ce5c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9ce5c-105">Public preview</span></span> | <span data-ttu-id="9ce5c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="9ce5c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="9ce5c-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="9ce5c-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="9ce5c-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9ce5c-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9ce5c-109">2020 年 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="9ce5c-109">May 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="9ce5c-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9ce5c-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9ce5c-111">この機能では、転記プロセスの 1 つのステップで詳細な元帳エントリの銀行業務部分を更新できるようにすることで、利息配賦と没収のプロセスを強化します。</span><span class="sxs-lookup"><span data-stu-id="9ce5c-111">This feature enhances the interest distribution and escheatment processes by letting you update the banking portion of the Advanced ledger entry in a single step in the posting process.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9ce5c-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9ce5c-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9ce5c-113">これにより、詳細な元帳エントリを使用して影響を受けるトランザクションを転記する、以前にリリースされた 2 つの機能 (**利息配賦**と**没収**) が強化されます。</span><span class="sxs-lookup"><span data-stu-id="9ce5c-113">This enhances two previously released features, **Interest distribution** and **Escheatment**, which use the Advanced ledger entry to post the affected transactions.</span></span> <span data-ttu-id="9ce5c-114">この機能を使用すると、1 つ以上の銀行の主勘定に関連付けられている詳細な元帳エントリを転記するときに、銀行残高を更新できます。</span><span class="sxs-lookup"><span data-stu-id="9ce5c-114">This feature lets you update bank balances when posting advanced ledger entries that are associated with one or more banking main accounts.</span></span>
<!--feature detail end -->









