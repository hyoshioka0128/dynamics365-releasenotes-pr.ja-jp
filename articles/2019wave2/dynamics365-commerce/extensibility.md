---
title: 拡張性
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 09/16/2019
ms.assetid: a663278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: brendans
dynamics365pdf: true
ms.openlocfilehash: 4023aed9661977cbfea0d626230bb0390aa627dc
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140262"
---
# <a name="extensibility"></a><span data-ttu-id="2dca9-102">拡張性</span><span class="sxs-lookup"><span data-stu-id="2dca9-102">Extensibility</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="2dca9-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="2dca9-103">Enabled for</span></span>    |  <span data-ttu-id="2dca9-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2dca9-104">Public preview</span></span> | <span data-ttu-id="2dca9-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="2dca9-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="2dca9-106">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="2dca9-106">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="2dca9-107">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="2dca9-107">Oct 2019</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="2dca9-108">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2dca9-108">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="2dca9-109">マーケティング チームは、e コマース サイト内でサード パーティのサービスとデータを活用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2dca9-109">Marketing teams will need to leverage third-party services and data within their e-commerce sites.</span></span> <span data-ttu-id="2dca9-110">最新の拡張性機能により、社内の開発者とシステム インテグレーター (SI) は、マーチャンダイザーやマーケティング担当者がこれらのサービスとそのデータを Web サイトで使用および表示できるようにする拡張機能を作成できます。</span><span class="sxs-lookup"><span data-stu-id="2dca9-110">Our latest extensibility feature provides in-house developers and system integrators (SIs) the ability to create extensions that enable merchandisers and marketers to consume and present these services and their data in their websites.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="2dca9-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2dca9-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="2dca9-112">Commerce は、小売業者が e-Commerce Starter Kit を超えたカスタマイズを必要とするときに、より少ない開発時間と投資で拡張性をサポートします。</span><span class="sxs-lookup"><span data-stu-id="2dca9-112">When a retailer needs customization beyond the e-commerce starter kit, Commerce supports extensibility with less development time and investment.</span></span> <span data-ttu-id="2dca9-113">Commerce では、さまざまな市場でのさまざまな外観に適応する UX モジュールや、スイッチを押すだけでアクティブになるサービス統合など、e-Commerce Starter Kit と同じ価値をカスタマイズによってオペレーション チームに提供できます。</span><span class="sxs-lookup"><span data-stu-id="2dca9-113">Commerce allows customizations to provide the same value to the operations team as the e-commerce starter kit, including UX modules that adapt to different looks in different markets and service integrations that activate with the flip of a switch.</span></span> 

<span data-ttu-id="2dca9-114">拡張性のストーリーでは、小売業者の開発チームが、新しいテンプレート、新しいモジュール、新しいモジュール用バリアントを作成するか、またはオープンソース コミュニティを使用して既存のコード (またはモジュール) を取得し変更するかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="2dca9-114">With the extensibility story, the retailer’s development team has the option to create new templates, new modules, new variants for a module, or use the open source community and take an existing piece of code (or module) and modify it.</span></span> <span data-ttu-id="2dca9-115">目標は、開発者の時間を生産的にし、変更を簡単にすることです。</span><span class="sxs-lookup"><span data-stu-id="2dca9-115">The goal is to ensure the developer’s time is productive, and to simplify making changes.</span></span> 

<span data-ttu-id="2dca9-116">新しい UX の追加だけでなく、複雑なサード パーティ サービス統合をパッケージ化して、小売業者がそれらを迅速に自信を持って有効にできるようにすることも簡単です。</span><span class="sxs-lookup"><span data-stu-id="2dca9-116">In addition to adding new UX, it is also easy to package complex third-party service integrations so that the retailer can quickly and confidently enable them.</span></span> <span data-ttu-id="2dca9-117">小売業者は 1 つの構成で、評価とレビューから実験、分析までの各タイプのサービスに対してサイトおよび市場ごとのプロバイダーを選択し、後で変更することができます。</span><span class="sxs-lookup"><span data-stu-id="2dca9-117">For each type of service, from ratings and review to experimentation to analytics, the retailer is able to pick the provider per site and market and change it later with a single configuration.</span></span> <span data-ttu-id="2dca9-118">ターゲット プロバイダーは、すべてのページでの JavaScript、ユーザーのセグメントのサーバー側呼び出し、推奨製品を取得するための特別な API を必要としていますか?</span><span class="sxs-lookup"><span data-stu-id="2dca9-118">Does your targeting provider require JavaScript on every page, a server-side call for the user’s segment, and a special API to fetch recommended products?</span></span> <span data-ttu-id="2dca9-119">プラットフォームは、管理者がこれらの要素を 1 ステップでまとめてアクティブ化または非アクティブ化できるように調整します。</span><span class="sxs-lookup"><span data-stu-id="2dca9-119">The platform orchestrates these pieces so that admins activate or deactivate them all together in one step.</span></span>
<!--feature detail end -->











