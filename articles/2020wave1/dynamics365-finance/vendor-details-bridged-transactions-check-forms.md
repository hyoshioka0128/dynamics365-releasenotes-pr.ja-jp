---
title: つなぎ勘定トランザクションと小切手フォームに対する仕入先の詳細
description: '**つなぎ勘定トランザクション**、**銀行トランザクション**、および**小切手**ページに、調整に役立つ追加の銀行情報と仕入先情報が表示されるようになりました。'
author: relnotes
ms.reviewer: roschlom
ms.date: 03/17/2020
ms.assetid: f4727359-f8d0-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: ebfa94c0294bfa1c87b1868f8c00f0de5a2a17d9
ms.sourcegitcommit: 773ea4a9be0440714ed67e25d1ba572a6a25072e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2020
ms.locfileid: "3153889"
---
# <a name="vendor-details-to-bridged-transactions-and-check-forms"></a><span data-ttu-id="d9a59-103">つなぎ勘定トランザクションと小切手フォームに対する仕入先の詳細</span><span class="sxs-lookup"><span data-stu-id="d9a59-103">Vendor details to bridged transactions and check forms</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="d9a59-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="d9a59-104">Enabled for</span></span>    |  <span data-ttu-id="d9a59-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d9a59-105">Public preview</span></span> | <span data-ttu-id="d9a59-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="d9a59-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d9a59-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="d9a59-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="d9a59-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="d9a59-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="d9a59-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d9a59-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d9a59-110">以前のバージョンの**つなぎ勘定トランザクション** ページでは、仕入先の詳細が表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="d9a59-110">In the earlier version, the **Bridged transactions** page didn’t display any vendor details.</span></span> <span data-ttu-id="d9a59-111">買掛金勘定の**小切手**ページでは、つなぎ勘定の状態や仕入先の詳細が表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="d9a59-111">The Accounts payable **Checks** page didn’t display the bridging status or vendor details.</span></span> <span data-ttu-id="d9a59-112">**銀行トランザクション**ページでも、つなぎ勘定の状態が表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="d9a59-112">The **Bank transactions** page did not display any bridging status, either.</span></span> <span data-ttu-id="d9a59-113">この機能では、**つなぎ勘定トランザクション**、**銀行トランザクション**、および**小切手**ページにより多くの情報を表示することで、これらの欠点に対処します。</span><span class="sxs-lookup"><span data-stu-id="d9a59-113">This feature addresses these shortcomings by displaying more information on the **Bridged transactions**, **Bank transactions**, and **Checks** pages.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d9a59-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d9a59-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d9a59-115">この機能により、次の変更が導入されます。</span><span class="sxs-lookup"><span data-stu-id="d9a59-115">This feature introduces the following changes:</span></span> 
 
- <span data-ttu-id="d9a59-116">**つなぎ勘定トランザクション** ページが、仕入先の番号、名前、住所、支払先情報を表示するように更新されます。</span><span class="sxs-lookup"><span data-stu-id="d9a59-116">Updates the **Bridged transactions** page to display the vendor number, name, address, and pay-to information in the inquiry.</span></span>
- <span data-ttu-id="d9a59-117">**銀行トランザクション** ページが、**解除された日付**を表示するように更新されます。</span><span class="sxs-lookup"><span data-stu-id="d9a59-117">Updates the **Bank transactions** page to display the **Cleared date**.</span></span>
- <span data-ttu-id="d9a59-118">既存の**小切手**フォームが、仕入先の名前、住所、支払先名と小切手が解除されたかどうかを**解除された日付**と共に表示するように更新されます。</span><span class="sxs-lookup"><span data-stu-id="d9a59-118">Updates the existing **Checks** form to display the vendor name, address, and pay-to name and whether the check has cleared along with the **Cleared date**.</span></span>

<!--feature detail end -->









