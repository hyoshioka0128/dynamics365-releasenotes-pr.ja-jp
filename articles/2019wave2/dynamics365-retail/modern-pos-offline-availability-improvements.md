---
title: Modern POS のオフライン時の利用可能性の向上
description: Modern POS のオフライン シナリオの可用性の拡大
author: relnotes
ms.reviewer: josaw
ms.date: 10/07/2019
ms.assetid: 859dc757-73aa-e911-a964-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: 86a087d98cea1236d1dd5204460069cc5a8b5e51
ms.sourcegitcommit: c843aacec8dddcb0d6693c79fbace7f19bf09565
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/11/2019
ms.locfileid: "2574482"
---
# <a name="modern-pos-offline-availability-improvements"></a><span data-ttu-id="845c8-103">Modern POS のオフライン時の利用可能性の向上</span><span class="sxs-lookup"><span data-stu-id="845c8-103">Modern POS offline availability improvements</span></span>


| <span data-ttu-id="845c8-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="845c8-104">Enabled for</span></span>    |  <span data-ttu-id="845c8-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="845c8-105">Public preview</span></span> | <span data-ttu-id="845c8-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="845c8-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="845c8-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="845c8-107">End users, automatically</span></span>|<span data-ttu-id="845c8-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="845c8-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="845c8-109">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="845c8-109">Aug 2, 2019</span></span>| <span data-ttu-id="845c8-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="845c8-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="845c8-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="845c8-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="845c8-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="845c8-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="845c8-113">Modern POS (MPOS) のオフライン機能は、ビジネス継続性と継続的な店舗運営にとって非常に重要です。</span><span class="sxs-lookup"><span data-stu-id="845c8-113">Offline functionality in Modern POS (MPOS) is critical to business continuity and continuous store operations.</span></span> <span data-ttu-id="845c8-114">MPOS は必要なときにいつでも利用できる必要があり、その結果、最も広範なシナリオのセットに対してオフライン モードが提供されることが重要となります。</span><span class="sxs-lookup"><span data-stu-id="845c8-114">MPOS must be available whenever needed, and as a result, it is critical that offline mode is provided for the broadest set of scenarios.</span></span> <span data-ttu-id="845c8-115">この機能により、既に堅牢な MPOS の可用性を強化する追加のシナリオがさらに組み込まれます。</span><span class="sxs-lookup"><span data-stu-id="845c8-115">This feature further incorporates additional scenarios enhancing the already robust MPOS availability.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="845c8-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="845c8-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="845c8-117">この機能は、MPOS に存在するシームレスなオフライン機能をさらに拡張します。</span><span class="sxs-lookup"><span data-stu-id="845c8-117">This feature further expands the seamless offline functionality that exists in MPOS.</span></span> <span data-ttu-id="845c8-118">拡張されるシナリオには、MPOS にサインインする前に手動でオフラインに切り替える機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="845c8-118">Expanded scenarios include the ability to switch to offline manually prior to signing in to MPOS.</span></span> <span data-ttu-id="845c8-119">これにより、災害時でもオフラインに移行して引き続き POS 操作を使用することができます。</span><span class="sxs-lookup"><span data-stu-id="845c8-119">This enables the ability to go offline and continue using POS operations even in disaster scenarios.</span></span> <span data-ttu-id="845c8-120">サインイン プロセスは、端末がオフラインに切り替わるシナリオが最も多く発生する可能性がある箇所です。</span><span class="sxs-lookup"><span data-stu-id="845c8-120">The sign-in process is where the largest number of scenarios could occur to cause the terminal to switch to offline.</span></span> <span data-ttu-id="845c8-121">これに対応するため、サインイン中に MPOS がより迅速かつ頻繁にオフラインにシームレスに切り替わる高度なシナリオ向けに、本社で有効または無効にできるオフライン構成が実装されました。</span><span class="sxs-lookup"><span data-stu-id="845c8-121">To accommodate this, we have implemented an offline configuration that can be enabled or disabled in headquarters for advanced scenarios where MPOS will more quickly and more frequently switch seamlessly to offline during sign-in.</span></span> <span data-ttu-id="845c8-122">例としては、レジ係またはマネージャーがアプリケーションにサインインするときなどが挙げられます。</span><span class="sxs-lookup"><span data-stu-id="845c8-122">For example, when a cashier or manager signs in to the application.</span></span>
<!--feature detail end -->




