---
title: 拡張性
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 11/15/2019
ms.assetid: a663278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: brendans
dynamics365pdf: true
ms.openlocfilehash: 7ce35838ba5375135aa2cf7d4267d6c0a04d9031
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2890313"
---
# <a name="extensibility"></a><span data-ttu-id="307ad-102">拡張性</span><span class="sxs-lookup"><span data-stu-id="307ad-102">Extensibility</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="307ad-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="307ad-103">Enabled for</span></span>    |  <span data-ttu-id="307ad-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="307ad-104">Public preview</span></span> | <span data-ttu-id="307ad-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="307ad-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="307ad-106">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="307ad-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="307ad-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="307ad-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="307ad-108">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="307ad-108">Oct 1, 2019</span></span>| <span data-ttu-id="307ad-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="307ad-109">Feb 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="307ad-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="307ad-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="307ad-111">マーケティング チームは、eコマース サイト内でサード パーティのサービスとデータの活用が必要になることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="307ad-111">Marketing teams often want to leverage third-party services and data within their e-commerce sites.</span></span> <span data-ttu-id="307ad-112">Microsoft の拡張性モデルにより、社内の開発者とシステム インテグレーター (SI) は、マーチャンダイザーやマーケティング担当者がこれらのサービスとそのデータを Web サイトで使用して表示できるようにする拡張機能を作成できます。</span><span class="sxs-lookup"><span data-stu-id="307ad-112">Our extensibility model provides in-house developers and system integrators (SIs) the ability to create extensions that enable merchandisers and marketers to consume and present these services and their data into their websites.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="307ad-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="307ad-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="307ad-114">Dynamics 365 Commerce は、小売業者が eコマース ストア スターター キットを超えたカスタマイズを必要とするときに、より少ない開発時間と投資で拡張性をサポートします。</span><span class="sxs-lookup"><span data-stu-id="307ad-114">When a retailer needs customization beyond the e-commerce store starter kit, Dynamics 365 Commerce supports extensibility with less development time and investment.</span></span> <span data-ttu-id="307ad-115">Dynamics 365 Commerce では、さまざまな市場でのさまざまな外観に適応する UX モジュールや、スイッチを押すだけでアクティブになるサービス統合など、eコマース ストア スターター キットと同じ価値をカスタマイズによってオペレーション チームに提供できます。</span><span class="sxs-lookup"><span data-stu-id="307ad-115">Dynamics 365 Commerce allows customizations to provide the same value to the operations team as the e-commerce store starter kit, including UX modules that adapt to different looks in different markets and service integrations that activate with the flip of a switch.</span></span> <span data-ttu-id="307ad-116">拡張性のストーリーでは、小売業者の開発チームが、新しいテンプレート、新しいモジュール、新しいモジュール用バリアントを作成するか、オープンソース コミュニティを使用して既存のコード (またはモジュール) を取得し変更するかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="307ad-116">With the extensibility story, the retailer’s development team has the option to create new templates, new modules, new variants for a module, or utilize the open source community to take an existing piece of code (or module) and modify it for use.</span></span> <span data-ttu-id="307ad-117">目標は、開発者の時間を生産的にし、変更の手順を簡単にすることです。</span><span class="sxs-lookup"><span data-stu-id="307ad-117">The goal is to ensure the developer’s time is productive and to simplify the process of making changes.</span></span> 

<span data-ttu-id="307ad-118">新しい UX が追加されただけでなく、複雑なサード パーティ サービス統合をパッケージ化するのも簡単であるため、小売業者はそれらを短時間で自信を持って有効にできます。</span><span class="sxs-lookup"><span data-stu-id="307ad-118">In addition to adding new UX, it is also easy to package complex third-party service integrations so that the retailer can quickly and confidently enable them.</span></span> <span data-ttu-id="307ad-119">小売業者は 1 つの構成で、評価とレビューから実験、分析までの各タイプのサービスに対してサイトおよび市場ごとのプロバイダーを選択し、後で変更することができます。</span><span class="sxs-lookup"><span data-stu-id="307ad-119">For each type of service, from ratings and review to experimentation to analytics, the retailer is able to pick the provider per site and market and change it later with a single configuration.</span></span> <span data-ttu-id="307ad-120">ターゲット プロバイダーは、すべてのページでの JavaScript、ユーザーのセグメントのサーバー側呼び出し、推奨製品を取得するための特別な API を必要としていませんか。</span><span class="sxs-lookup"><span data-stu-id="307ad-120">Does your targeting provider require JavaScript on every page, a server-side call for the user’s segment, and a special API to fetch recommended products?</span></span> <span data-ttu-id="307ad-121">問題ありません。</span><span class="sxs-lookup"><span data-stu-id="307ad-121">Not a problem.</span></span> <span data-ttu-id="307ad-122">プラットフォームは、管理者がこれらの要素を 1 ステップでまとめてアクティブ化または非アクティブ化できるように調整します。</span><span class="sxs-lookup"><span data-stu-id="307ad-122">The platform orchestrates these pieces so that admins activate or deactivate them all together in one step.</span></span>

<span data-ttu-id="307ad-123">![拡張性](media/extensibility.png "拡張性")</span><span class="sxs-lookup"><span data-stu-id="307ad-123">![Extensibility](media/extensibility.png "Extensibility")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="307ad-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="307ad-124">See also</span></span>

<span data-ttu-id="307ad-125">[オンライン チャネルの拡張性](https://docs.microsoft.com/dynamics365/commerce/e-commerce-extensibility/overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="307ad-125">[Online channel extensibility](https://docs.microsoft.com/dynamics365/commerce/e-commerce-extensibility/overview) (docs)</span></span>
