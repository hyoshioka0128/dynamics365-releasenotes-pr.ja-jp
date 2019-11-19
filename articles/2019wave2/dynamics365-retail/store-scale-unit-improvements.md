---
title: 店舗のスケール ユニットの向上
description: 店舗のスケール ユニットの向上
author: relnotes
ms.reviewer: josaw
ms.date: 10/07/2019
ms.assetid: 5263278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: eb3bffd14a507d3169e39a631f42f04e22916b62
ms.sourcegitcommit: c843aacec8dddcb0d6693c79fbace7f19bf09565
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/11/2019
ms.locfileid: "2574383"
---
# <a name="store-scale-unit-improvements"></a><span data-ttu-id="1c35b-103">店舗のスケール ユニットの向上</span><span class="sxs-lookup"><span data-stu-id="1c35b-103">Store Scale Unit improvements</span></span>


| <span data-ttu-id="1c35b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1c35b-104">Enabled for</span></span>    |  <span data-ttu-id="1c35b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1c35b-105">Public preview</span></span> | <span data-ttu-id="1c35b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="1c35b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1c35b-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="1c35b-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="1c35b-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1c35b-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1c35b-109">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="1c35b-109">Aug 2, 2019</span></span>| <span data-ttu-id="1c35b-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1c35b-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1c35b-111">2019 年 10 月 2 日</span><span class="sxs-lookup"><span data-stu-id="1c35b-111">Oct 2, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="1c35b-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1c35b-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1c35b-113">Retail Store Scale Unit では、接続とネットワーク インフラストラクチャの問題がある場所で稼働時間を確保し、待ち時間を短縮するのに役立つ、店舗内 (オンプレミス) 展開オプションが小売業者に提供されます。</span><span class="sxs-lookup"><span data-stu-id="1c35b-113">A Retail Store Scale Unit provides a retailer with an in-store (on-premises) deployment option to help ensure uptime and reduce latency in locations with connectivity and network infrastructure issues.</span></span> <span data-ttu-id="1c35b-114">このスケール ユニットが常に信頼性と安全性を維持することが重要です。</span><span class="sxs-lookup"><span data-stu-id="1c35b-114">It is important that this scale unit maintains reliability and security at all times.</span></span> <span data-ttu-id="1c35b-115">このニーズを満たすには、接続が制限されているか存在しない場合でもスケール ユニットの使用が継続されることが重要です。</span><span class="sxs-lookup"><span data-stu-id="1c35b-115">To fulfill this need, it is critical for the usage of the scale unit to continue when connectivity is limited or nonexistent.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1c35b-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1c35b-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1c35b-117">この機能は現在多くのリリースでサポートされており、世界中の多くの小売店で使用されています。ただし、必要に応じてスケール ユニットを使用できない、いくつかの設計上の制限があります。</span><span class="sxs-lookup"><span data-stu-id="1c35b-117">This feature has been supported for many releases now and has been used by many retailers worldwide; however, there are some design limitations that prohibit the use of the scale unit as needed.</span></span> <span data-ttu-id="1c35b-118">この取り組みでは、セキュリティを維持しながら認証トークンを更新するときに、Retail Store Scale Unit がバックオフィス (本社) との接続について持っている依存関係を減らします。</span><span class="sxs-lookup"><span data-stu-id="1c35b-118">This investment reduces the dependency a Retail Store Scale Unit has with back-office (headquarters) connectivity when renewing authentication tokens, while still maintaining security.</span></span> <span data-ttu-id="1c35b-119">この機能により、バック オフィスが利用できない場合でもクロスターミナル シナリオで販売時点管理 (POS) が機能できるようになり、ハイブリッド スタイルの展開のより大きいオファリングと深度が提供されます。</span><span class="sxs-lookup"><span data-stu-id="1c35b-119">This functionality will allow point of sale (POS) to function in cross-terminal scenarios even when the back office is not available, providing greater offerings and depths of hybrid-style deployments.</span></span>
<!--feature detail end -->




