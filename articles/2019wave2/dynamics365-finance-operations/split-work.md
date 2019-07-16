---
title: 作業を分割する
description: この機能により、倉庫マネージャーは残りの作業明細行を分割することができます。
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 7662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: e65ea2feedbcdee48b9989536f9f95ed2f2ae417
ms.sourcegitcommit: d6ff62c145bfdd7742034a67a29bf75938823eb0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/24/2019
ms.locfileid: "1702272"
---
# <a name="split-work"></a><span data-ttu-id="70282-103">作業を分割する</span><span class="sxs-lookup"><span data-stu-id="70282-103">Split work</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="70282-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="70282-104">Enabled for</span></span>    |  <span data-ttu-id="70282-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="70282-105">Public preview</span></span> | <span data-ttu-id="70282-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="70282-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="70282-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="70282-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="70282-108">2019 年 5 月</span><span class="sxs-lookup"><span data-stu-id="70282-108">May 2019</span></span>| <span data-ttu-id="70282-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="70282-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="70282-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="70282-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="70282-111">この機能は、倉庫従業員の稼働率を高め、日々の作業を柔軟に計画できるようにします。</span><span class="sxs-lookup"><span data-stu-id="70282-111">This feature helps to increase the utilization of the warehouse workforce, allowing for flexibility in planning day-to-day tasks.</span></span> <span data-ttu-id="70282-112">ユーザーは、自動的に作成された一部の割り当てを手動で修正することができます。</span><span class="sxs-lookup"><span data-stu-id="70282-112">It allows the user to manually correct some automatically created assignments.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="70282-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="70282-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="70282-114">この機能は、1 人の従業員では一定時間内に職務を完了できず、他のユーザーがそれを完了するのを助けることができるという、ビジネス上の課題を解決するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="70282-114">This feature helps solve the business challenge in which a single employee cannot finalize work within a given time and other users are available to assist completing it.</span></span> <span data-ttu-id="70282-115">利用可能な従業員に割り当てるために、作業を 2 つ以上の作業ヘッダーに分割できます。</span><span class="sxs-lookup"><span data-stu-id="70282-115">The work can be split in two or more work headers in order to assign it to available employees.</span></span> <span data-ttu-id="70282-116">この機能により、作成されてオープン状態または進行中の状態になった後でも、作業を柔軟に再構成できます。</span><span class="sxs-lookup"><span data-stu-id="70282-116">The feature adds the flexibility of restructuring work after it has been created and is in either an open or in-progress state.</span></span> <span data-ttu-id="70282-117">作業者は、同時に別のユーザーに分割される可能性がある作業明細行を続行することはできません。</span><span class="sxs-lookup"><span data-stu-id="70282-117">A worker will not be able to proceed with work lines that might concurrently be split to another user.</span></span> <span data-ttu-id="70282-118">既存のブロック メカニズムがリファクタリングされました。</span><span class="sxs-lookup"><span data-stu-id="70282-118">The existing blocking mechanism has been refactored.</span></span>
<!--feature detail end -->










