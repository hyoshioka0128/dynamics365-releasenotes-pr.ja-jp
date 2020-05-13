---
title: 拡張性
description: Dynamics 365 Commerce では拡張性がサポートされていて、顧客やシステム インテグレーターがソリューションを簡単にカスタマイズできます。 Commerce ストア スターター キットのサービス モジュールを拡張したり、新しいモジュールやテンプレートを導入したりできます。 拡張性モジュールは、カスタマイズのコーディング、パッケージ化、展開時に開発者の時間を節約するように設計されています。
author: relnotes
ms.reviewer: rhaertle
ms.date: 04/15/2020
ms.assetid: a663278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: brshoo
dynamics365pdf: true
ms.openlocfilehash: 0b2d378c8599ead952273fcd563b8c0e868fd883
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320459"
---
# <a name="extensibility"></a><span data-ttu-id="2b47e-105">拡張性</span><span class="sxs-lookup"><span data-stu-id="2b47e-105">Extensibility</span></span>


| <span data-ttu-id="2b47e-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="2b47e-106">Enabled for</span></span>    |  <span data-ttu-id="2b47e-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2b47e-107">Public preview</span></span> | <span data-ttu-id="2b47e-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="2b47e-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="2b47e-109">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="2b47e-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="2b47e-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2b47e-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2b47e-111">2020 年 2 月 2 日</span><span class="sxs-lookup"><span data-stu-id="2b47e-111">Feb 2, 2020</span></span>| <span data-ttu-id="2b47e-112">近日発表</span><span class="sxs-lookup"><span data-stu-id="2b47e-112">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="2b47e-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2b47e-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="2b47e-114">小売業者は、eコマース サイトにサード パーティのサービスとデータを統合することが必要になる場合がよくあります。</span><span class="sxs-lookup"><span data-stu-id="2b47e-114">Retailers often want to integrate third-party services and data into their e-commerce sites.</span></span> <span data-ttu-id="2b47e-115">Microsoft の拡張性モデルにより、社内開発者とシステム インテグレーター (SI) は、Dynamics 365 Commerce Web サイトでこれらのサービスを使用してデータを表示する拡張機能を簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="2b47e-115">Our extensibility model gives in-house developers and system integrators (SIs) the ability to easily create extensions that consume and present these services and their data into Dynamics 365 Commerce websites.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="2b47e-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2b47e-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="2b47e-117">Dynamics 365 Commerce は、小売業者が eコマース ストア スターター キットで提供されるもの以上のカスタマイズを必要とするときに、より少ない開発時間と投資で拡張性をサポートします。</span><span class="sxs-lookup"><span data-stu-id="2b47e-117">When a retailer needs customization beyond what the e-commerce store starter kit provides, Dynamics 365 Commerce supports extensibility with less development time and investment.</span></span> <span data-ttu-id="2b47e-118">Commerce では、さまざまな市場でのさまざまな外観に適応する UX モジュールや、スイッチを押すだけでアクティブになるサービス統合など、eコマース ストア スターター キットと同じ価値をカスタマイズによってオペレーション チームに提供できます。</span><span class="sxs-lookup"><span data-stu-id="2b47e-118">Commerce allows customizations to provide the same value to the operations team as the e-commerce store starter kit, including UX modules that adapt to different looks in different markets and service integrations that activate with the flip of a switch.</span></span> <span data-ttu-id="2b47e-119">拡張性のストーリーでは、小売業者の開発チームが、新しいテンプレート、新しいモジュール、新しいモジュール用バリアントを作成するか、オープンソース コミュニティを使用して既存のコード (またはモジュール) を取得し変更するかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="2b47e-119">With the extensibility story, the retailer’s development team has the option to create new templates, new modules, new variants for a module, or use the open source community to take an existing piece of code (or module) and modify it for use.</span></span> <span data-ttu-id="2b47e-120">目標は、開発者の時間を生産的にし、カスタマイズを作成するプロセスを簡単にすることです。</span><span class="sxs-lookup"><span data-stu-id="2b47e-120">The goal is to ensure the developer’s time is productive and to simplify the process of building customizations.</span></span> 

<span data-ttu-id="2b47e-121">新しい UX が追加されただけでなく、複雑なサード パーティ サービス統合をパッケージ化するのも簡単であるため、小売業者はそれらを短時間で自信を持って有効にできます。</span><span class="sxs-lookup"><span data-stu-id="2b47e-121">In addition to adding new UX, it is also easy to package complex third-party service integrations so that the retailer can quickly and confidently enable them.</span></span> <span data-ttu-id="2b47e-122">小売業者は 1 つの構成で、評価とレビューから実験、分析までの各タイプのサービスに対してサイトおよび市場ごとのプロバイダーを選択し、後で変更することができます。</span><span class="sxs-lookup"><span data-stu-id="2b47e-122">For each type of service, from ratings and reviews to experimentation to analytics, the retailer is able to pick the provider per site and market and change it later with a single configuration.</span></span> <span data-ttu-id="2b47e-123">ターゲット プロバイダーは、すべてのページでの JavaScript、ユーザーのセグメントのサーバー側呼び出し、推奨製品を取得するための特別な API を必要としていませんか。</span><span class="sxs-lookup"><span data-stu-id="2b47e-123">Does your targeting provider require JavaScript on every page, a server-side call for the user’s segment, and a special API to fetch recommended products?</span></span> <span data-ttu-id="2b47e-124">問題ありません。</span><span class="sxs-lookup"><span data-stu-id="2b47e-124">Not a problem.</span></span> <span data-ttu-id="2b47e-125">プラットフォームは、管理者がこれらの要素を 1 ステップでまとめてアクティブ化または非アクティブ化できるように調整します。</span><span class="sxs-lookup"><span data-stu-id="2b47e-125">The platform orchestrates these pieces so that admins activate or deactivate them all together in one step.</span></span>

<span data-ttu-id="2b47e-126">![拡張性](media/extensibility_releasenote.png "拡張性")</span><span class="sxs-lookup"><span data-stu-id="2b47e-126">![Extensibility](media/extensibility_releasenote.png "Extensibility")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="2b47e-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="2b47e-127">See also</span></span>

<!--docs start-->
<span data-ttu-id="2b47e-128">[オンライン チャネルの拡張性](https://docs.microsoft.com/dynamics365/commerce/e-commerce-extensibility/overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="2b47e-128">[Online channel extensibility](https://docs.microsoft.com/dynamics365/commerce/e-commerce-extensibility/overview) (docs)</span></span>
<!--docs end-->
