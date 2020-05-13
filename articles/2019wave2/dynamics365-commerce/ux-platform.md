---
title: UX プラットフォーム
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 02/11/2020
ms.assetid: a263278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: brshoo
dynamics365pdf: true
ms.openlocfilehash: 8dd27f4a8d82eab385ee2830262ae65b7e3353c6
ms.sourcegitcommit: bfe05af05f11f2c318a77bb3138c3df0796c7187
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/27/2020
ms.locfileid: "3088715"
---
# <a name="ux-platform"></a><span data-ttu-id="30c69-102">UX プラットフォーム</span><span class="sxs-lookup"><span data-stu-id="30c69-102">UX Platform</span></span>


| <span data-ttu-id="30c69-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="30c69-103">Enabled for</span></span>    |  <span data-ttu-id="30c69-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="30c69-104">Public preview</span></span> | <span data-ttu-id="30c69-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="30c69-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="30c69-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="30c69-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="30c69-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="30c69-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="30c69-108">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="30c69-108">Oct 1, 2019</span></span>| <span data-ttu-id="30c69-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="30c69-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="30c69-110">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="30c69-110">Feb 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="30c69-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="30c69-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="30c69-112">販売促進マネージャーとマーケティング マネージャーには、Web マーケティング ページとコンテンツをレイアウトするための簡単で直感的な方法が必要です。</span><span class="sxs-lookup"><span data-stu-id="30c69-112">Merchandising and marketing managers need an easy and intuitive way to lay out web marketing pages and content.</span></span> <span data-ttu-id="30c69-113">UX プラットフォームは、社内の開発者とシステム インテグレーター (SI) が、魅力的で収益性の高い Web サイトの作成をサポートする再利用可能なレイアウト テンプレートと応答性の高いモジュールを作成できるようにします。</span><span class="sxs-lookup"><span data-stu-id="30c69-113">The UX platform provides in-house developers and system integrators (SIs) the ability to create reusable layout templates and responsive modules that support the creation of stunning and profitable websites.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="30c69-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="30c69-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="30c69-115">Dynamics 365 Commerce では、小売店舗は、マイクロソフトが独自の統合された学習と購入の eコマース エクスペリエンスを実行するために開発したのと同じ UX プラットフォーム (microsoft.com\/store) で実行されます。</span><span class="sxs-lookup"><span data-stu-id="30c69-115">With Dynamics 365 Commerce, a retail store runs on the same UX platform Microsoft developed to run its own integrated learn-and-buy e-commerce experience (microsoft.com\/store).</span></span> <span data-ttu-id="30c69-116">Azure が構築した最新のクラウド Web インフラストラクチャにより、Microsoft のオンライン小売およびマーケティング Web サイトを強化するパフォーマンス、可用性、スケールが実現します。</span><span class="sxs-lookup"><span data-stu-id="30c69-116">The Azure-built, modern cloud web infrastructure enables the performance, availability, and scale that power Microsoft’s online retail and marketing websites.</span></span> <span data-ttu-id="30c69-117">UX プラットフォームでは、小売業者は、テンプレートとページ (ホーム ページ、カテゴリ ページ、統合された学習と購入製品の詳細ページなど) を使用してサイトを構築します。</span><span class="sxs-lookup"><span data-stu-id="30c69-117">With the UX platform, the retailer builds their site with templates and pages, including a home page, category page, and an integrated learn and buy product detail page.</span></span> <span data-ttu-id="30c69-118">これらのページは、モジュール (コンテンツの表示方法と動作方法が定義されている UX のモジュール ピース) で構成されています。</span><span class="sxs-lookup"><span data-stu-id="30c69-118">These pages are made up of modules—a modular piece of UX that has a defined way to display content and behave.</span></span> 

<span data-ttu-id="30c69-119">モジュールは、ページが関連付けられているテンプレートの制約に従います。</span><span class="sxs-lookup"><span data-stu-id="30c69-119">Modules follow the constraints of the template the page is associated with.</span></span> <span data-ttu-id="30c69-120">モジュールは、Commerce インスタンス、コンテンツ管理システム (CMS)、その他のデータ リポジトリから情報を自動的にフィードするデータ プロバイダーにバインドされています。</span><span class="sxs-lookup"><span data-stu-id="30c69-120">Modules are bound to a data provider that automatically feeds information from the Commerce instance, Content Management System (CMS), or other data repository.</span></span> <span data-ttu-id="30c69-121">次に、小売業者はテーマを適用して、モジュール全体の色、境界線、フォント、パディングなどのスタイルを制御します。</span><span class="sxs-lookup"><span data-stu-id="30c69-121">The retailer then applies a theme to control styling, such as colors, borders, fonts, padding, and more across modules.</span></span> <span data-ttu-id="30c69-122">テーマは年間を通じて変わる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="30c69-122">Themes may change throughout the year.</span></span> <span data-ttu-id="30c69-123">たとえば、12 月には祝日のテーマ、8 月には "新学期" のテーマがあり、テーマは小売業者のブランドに合わせてカスタマイズされます。</span><span class="sxs-lookup"><span data-stu-id="30c69-123">For example, there might be a holiday theme in December and a “back to school” theme in August, and themes are customized to the retailer’s brand.</span></span> 

<span data-ttu-id="30c69-124">テンプレート、ページ、モジュール、およびそれらの中のコンテンツは、認証されたセキュリティ、バージョン管理、グローバルな冗長性、メディア ストリーミング機能を提供する Dynamics の eコマース CMS 内に存在します。</span><span class="sxs-lookup"><span data-stu-id="30c69-124">Templates, pages, modules, and the content within them reside in the Dynamics e-commerce CMS, which offers authenticated security, versioning, global redundancy, and media streaming capabilities.</span></span> <span data-ttu-id="30c69-125">CMS に保存されたデータは、Dynamics の eコマース レンダリング サービスによって消費されます。このサービスは、すべての一般的なディスプレイ サイズに適合するように応答性と柔軟性を備えたレンダリング HTML を提供します。</span><span class="sxs-lookup"><span data-stu-id="30c69-125">Data stored in the CMS is consumed by the Dynamics e-commerce rendering service, which provides rendered HTML that is responsive and flexible to accommodate all common display sizes.</span></span> 

<span data-ttu-id="30c69-126">**応答性のあるデザイン:** Dynamics 365 Commerce ストア スターター キットのモジュールは、デスクトップ、ラップトップ、タブレット、および大小の携帯電話のエクスペリエンス向けにさまざまなビュー ポート構成をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="30c69-126">**Responsive design:** The modules in the Dynamics 365 Commerce store starter kit support various view port configurations for desktop, laptop, tablet, and large and small mobile phone experiences.</span></span> <span data-ttu-id="30c69-127">これらのモジュールは、ビュー ポートの構成が変更されるとリフローします。</span><span class="sxs-lookup"><span data-stu-id="30c69-127">These modules reflow as the view port configuration changes.</span></span> <span data-ttu-id="30c69-128">コンテナーなどの一部のモジュールでは、これらのビュー ポートの特別な構成が可能であるため、エクスペリエンスをさらにカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="30c69-128">Some modules, such as containers, allow special configurations for these view ports so the experience can be further customized.</span></span> <span data-ttu-id="30c69-129">ヘッダーやリファイナー モジュールなど一部の他のケースでは、より最適化されたエクスペリエンスのために、小さいビュー ポート (携帯電話など) ではモジュールに異なるレイアウトが使用されます。</span><span class="sxs-lookup"><span data-stu-id="30c69-129">In some other cases, as with a header or refiner module, the module has a different layout in smaller view ports, such as mobile for a more optimized experience.</span></span>

<span data-ttu-id="30c69-130">![UX プラットフォーム](media/ux_platform.jpg "UX プラットフォーム")</span><span class="sxs-lookup"><span data-stu-id="30c69-130">![UX Platform](media/ux_platform.jpg "UX Platform")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="30c69-131">関連項目</span><span class="sxs-lookup"><span data-stu-id="30c69-131">See also</span></span>

<span data-ttu-id="30c69-132">[スターター キットの概要](https://docs.microsoft.com/dynamics365/commerce/starter-kit-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="30c69-132">[Starter kit overview](https://docs.microsoft.com/dynamics365/commerce/starter-kit-overview) (docs)</span></span>
