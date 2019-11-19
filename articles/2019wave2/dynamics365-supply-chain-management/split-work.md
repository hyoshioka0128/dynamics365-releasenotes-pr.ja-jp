---
title: 作業を分割する
description: この機能により、倉庫マネージャーは残りの作業明細行を分割することができます。
author: relnotes
ms.reviewer: josaw
ms.date: 10/04/2019
ms.assetid: 7662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 60a013a4fccb60587427a7d70e223876a15ce071
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660573"
---
# <a name="split-work"></a><span data-ttu-id="ce5d9-103">作業を分割する</span><span class="sxs-lookup"><span data-stu-id="ce5d9-103">Split work</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="ce5d9-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ce5d9-104">Enabled for</span></span>    |  <span data-ttu-id="ce5d9-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ce5d9-105">Public preview</span></span> | <span data-ttu-id="ce5d9-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ce5d9-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ce5d9-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="ce5d9-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ce5d9-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ce5d9-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ce5d9-109">2019 年 6 月 3 日</span><span class="sxs-lookup"><span data-stu-id="ce5d9-109">Jun 3, 2019</span></span>| <span data-ttu-id="ce5d9-110">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="ce5d9-110">Dec 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="ce5d9-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ce5d9-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ce5d9-112">この機能は、倉庫従業員の稼働率を高め、日々の作業を柔軟に計画できるようにします。</span><span class="sxs-lookup"><span data-stu-id="ce5d9-112">This feature helps to increase the utilization of the warehouse workforce, allowing for flexibility in planning day-to-day tasks.</span></span> <span data-ttu-id="ce5d9-113">ユーザーは、自動的に作成された一部の割り当てを手動で修正することができます。</span><span class="sxs-lookup"><span data-stu-id="ce5d9-113">It allows the user to manually correct some automatically created assignments.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ce5d9-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ce5d9-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ce5d9-115">この機能は、1 人の従業員では一定時間内に職務を完了できず、他のユーザーがそれを完了するのを助けることができるという、ビジネス上の課題を解決するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="ce5d9-115">This feature helps solve the business challenge in which a single employee cannot finalize work within a given time and other users are available to assist completing it.</span></span> <span data-ttu-id="ce5d9-116">利用可能な従業員に割り当てるために、作業を 2 つ以上の作業ヘッダーに分割できます。</span><span class="sxs-lookup"><span data-stu-id="ce5d9-116">The work can be split in two or more work headers in order to assign it to available employees.</span></span> <span data-ttu-id="ce5d9-117">この機能により、作成されてオープン状態または進行中の状態になった後でも、作業を柔軟に再構成できます。</span><span class="sxs-lookup"><span data-stu-id="ce5d9-117">The feature adds the flexibility of restructuring work after it has been created and is in either an open or in-progress state.</span></span> <span data-ttu-id="ce5d9-118">作業者は、同時に別のユーザーに分割される可能性がある作業明細行を続行することはできません。</span><span class="sxs-lookup"><span data-stu-id="ce5d9-118">A worker will not be able to proceed with work lines that might concurrently be split to another user.</span></span> <span data-ttu-id="ce5d9-119">既存のブロック メカニズムがリファクタリングされました。</span><span class="sxs-lookup"><span data-stu-id="ce5d9-119">The existing blocking mechanism has been refactored.</span></span>
<!--feature detail end -->









