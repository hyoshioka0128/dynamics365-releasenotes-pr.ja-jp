---
title: Common Data Service エンティティを通じて Dynamics 365 Guides のコンテンツにアクセスする
description: Common Data Service API を使用して、Dynamics 365 Guides のコンテンツ エンティティからデジタル エンタープライズ エコシステムに簡単かつ確実に接続できます。
author: relnotes
ms.reviewer: v-brycho
ms.date: 05/04/2020
ms.assetid: 8a64278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: algodin
dynamics365pdf: true
ms.openlocfilehash: e75d07b289a70e4aa69afce960ae9ac45ef576a7
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350262"
---
# <a name="access-dynamics-365-guides-content-through-common-data-service-entities"></a><span data-ttu-id="acdd0-103">Common Data Service エンティティを通じて Dynamics 365 Guides のコンテンツにアクセスする</span><span class="sxs-lookup"><span data-stu-id="acdd0-103">Access Dynamics 365 Guides content through Common Data Service entities</span></span>


| <span data-ttu-id="acdd0-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="acdd0-104">Enabled for</span></span>    |  <span data-ttu-id="acdd0-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="acdd0-105">Public preview</span></span> | <span data-ttu-id="acdd0-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="acdd0-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="acdd0-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="acdd0-107">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="acdd0-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="acdd0-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="acdd0-109">2020 年 4 月 28 日</span><span class="sxs-lookup"><span data-stu-id="acdd0-109">Apr 28, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="acdd0-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="acdd0-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="acdd0-111">Dynamics 365 Guides データに簡単かつ確実にアクセスして、顧客やパートナーがそれをデジタル エンタープライズ エコシステムに接続できるようにします。</span><span class="sxs-lookup"><span data-stu-id="acdd0-111">Easy and reliable access to Dynamics 365 Guides data so that customers and partners can connect it to their digital enterprise ecosystems.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="acdd0-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="acdd0-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="acdd0-113">Dynamics 365 Guides では、すべてのコンテンツ (命令、テキスト、写真、ビデオ、3D モデル) が Common Data Service に格納されます。</span><span class="sxs-lookup"><span data-stu-id="acdd0-113">Dynamics 365 Guides stores all content (instructions, text, pictures, videos, and 3D models) in the Common Data Service.</span></span> <span data-ttu-id="acdd0-114">このコンテンツへのアクセスを向上させるために、コンテンツが格納されるデータ構造を定義する一連の Common Data Service エンティティにこのデータを移行しています。</span><span class="sxs-lookup"><span data-stu-id="acdd0-114">To provide better access to this content, we are moving this data to a set of Common Data Service entities that define the data structures the content is stored in.</span></span> <span data-ttu-id="acdd0-115">顧客やパートナーは、Common Data Service API を使用して、これらのコンテンツ エンティティの読み取りと書き込み、Dynamics 365 Guides との間でのコンテンツのプッシュとプル、カスタム統合の構築を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="acdd0-115">Using the Common Data Service API, customers and partners will be able to read and write these content entities, push and pull content to and from Dynamics 365 Guides, and build custom integrations.</span></span> <span data-ttu-id="acdd0-116">たとえば、システム インテグレーターは、Dynamics 365 Guides のコンテンツを読み取って、HoloLens にアクセスできないエキスパート ワーカーのためにモバイル デバイスに表示するアプリを、Power Apps で作成できます。</span><span class="sxs-lookup"><span data-stu-id="acdd0-116">For example, a system integrator will be able to build an app in Power Apps that reads Dynamics 365 Guides content and displays it on a mobile device for expert workers that don’t have access to a HoloLens.</span></span>
<!--feature detail end -->









