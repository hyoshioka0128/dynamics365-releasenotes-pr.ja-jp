---
title: 詳細な元帳エントリを使用してトランザクションを転記するときに銀行残高を更新する
description: この機能を使うと、銀行口座を 1 つ以上の主勘定に関連付けることができます。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/06/2020
ms.assetid: 7a7f888d-2a42-ea11-a812-000d3a563be2
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: bd09a286e4926575b5e1685dabe966b2af4047cf
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3256401"
---
# <a name="update-bank-balances-when-posting-transactions-using-advanced-ledger-entry"></a><span data-ttu-id="1f705-103">詳細な元帳エントリを使用してトランザクションを転記するときに銀行残高を更新する</span><span class="sxs-lookup"><span data-stu-id="1f705-103">Update bank balances when posting transactions using advanced ledger entry</span></span>


| <span data-ttu-id="1f705-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1f705-104">Enabled for</span></span>    |  <span data-ttu-id="1f705-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1f705-105">Public preview</span></span> | <span data-ttu-id="1f705-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="1f705-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1f705-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="1f705-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1f705-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1f705-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1f705-109">2020 年 3 月 2 日</span><span class="sxs-lookup"><span data-stu-id="1f705-109">Mar 2, 2020</span></span>| <span data-ttu-id="1f705-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1f705-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1f705-111">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="1f705-111">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1f705-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1f705-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1f705-113">この機能により、銀行口座を 1 つ以上の主勘定に関連付けて、組織とビジネスの状況に最適な方法で口座を柔軟に整理できます。</span><span class="sxs-lookup"><span data-stu-id="1f705-113">This features adds flexibility to organize your accounts in a way that's optimal for your organization and business situation by letting you associate a bank account with one or more main accounts.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1f705-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1f705-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1f705-115">銀行口座には、口座番号と支店コードが関連付けられている必要があります。</span><span class="sxs-lookup"><span data-stu-id="1f705-115">The bank account must have an account number and routing number associated with it.</span></span>
<!--feature detail end -->









