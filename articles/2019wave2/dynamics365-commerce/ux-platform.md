---
title: UX プラットフォーム
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 09/16/2019
ms.assetid: a263278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: brendans
dynamics365pdf: true
ms.openlocfilehash: c61b0e4fe81d819446e67411acc78e278a3f4184
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2142385"
---
# <a name="ux-platform"></a><span data-ttu-id="6c512-102">UX プラットフォーム</span><span class="sxs-lookup"><span data-stu-id="6c512-102">UX platform</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="6c512-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="6c512-103">Enabled for</span></span>    |  <span data-ttu-id="6c512-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6c512-104">Public preview</span></span> | <span data-ttu-id="6c512-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="6c512-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6c512-106">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="6c512-106">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="6c512-107">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="6c512-107">Oct 2019</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="6c512-108">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="6c512-108">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="6c512-109">販売促進マネージャーとマーケティング マネージャーには、Web マーケティング ページとコンテンツをレイアウトするための簡単で直感的な方法が必要です。</span><span class="sxs-lookup"><span data-stu-id="6c512-109">Merchandising and marketing managers need an easy and intuitive way to lay out web marketing pages and content.</span></span> <span data-ttu-id="6c512-110">UX プラットフォームは、社内の開発者とシステム インテグレーター (SI) が、魅力的で収益性の高い Web サイトの作成をサポートする再利用可能なレイアウト テンプレートと応答性の高いモジュールを作成できるようにします。</span><span class="sxs-lookup"><span data-stu-id="6c512-110">The UX platform provides in-house developers and system integrators (SIs) the ability to create reusable layout templates and responsive modules that support the creation of stunning and profitable websites.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="6c512-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6c512-111">Feature details</span></span>
<!--feature detail start -->
 <span data-ttu-id="6c512-112">Dynamics 365 Commerce では、小売業者の店舗は、マイクロソフトが独自の統合された学習と購入の eコマース エクスペリエンスを実行するために開発したのと同じ UX プラットフォーム (microsoft.com\\store) で実行されます。</span><span class="sxs-lookup"><span data-stu-id="6c512-112">In Dynamics 365 Commerce, a retailer’s store runs on the same UX platform Microsoft developed to run its own integrated learn-and-buy e-commerce experience (microsoft.com\\store).</span></span> <span data-ttu-id="6c512-113">Azure が構築したこの最新のクラウド Web インフラストラクチャにより、小売業者は、マイクロソフトの約 300 億ページ ビュー、1 か月あたり 5000 億の資産ビュー、および年間 100 億ドルのオンライン収益を促進するパフォーマンス、可用性、スケールを保証されます。</span><span class="sxs-lookup"><span data-stu-id="6c512-113">This Azure-built, modern cloud web infrastructure guarantees the retailer the performance, availability, and scale that powers Microsoft’s nearly 30 billion page views, half-trillion asset views per month, and $10 billion in annual online revenue.</span></span> 


<span data-ttu-id="6c512-114">UX プラットフォームでは、小売業者は、テンプレートとページ (ホーム ページ、部門ページ、統合された学習と購入製品の詳細ページなど) からサイトを構築します。</span><span class="sxs-lookup"><span data-stu-id="6c512-114">In the UX platform, the retailer builds the site out of templates and pages such as a home page, department page, and an integrated learn-and-buy product detail page.</span></span> <span data-ttu-id="6c512-115">これらのページは、ページが関連付けられているテンプレートの制約に従うモジュール (表示方法と動作方法を認識している UX のモジュール ピース) で構成されています。</span><span class="sxs-lookup"><span data-stu-id="6c512-115">These pages are made up of modules—a modular piece of UX that know how to display and behave—that follow the constraints of the template the page is associated with.</span></span> <span data-ttu-id="6c512-116">モジュールは、Commerce インスタンス、コンテンツ管理システム (CMS)、その他のデータ リポジトリから直接情報を自動的にフィードするデータ プロバイダーにバインドされています。</span><span class="sxs-lookup"><span data-stu-id="6c512-116">Modules are bound to a data provider that automatically feeds information straight from the Commerce instance, content management system (CMS), or other data repository.</span></span> 

<span data-ttu-id="6c512-117">次に、小売業者はテーマを適用して、モジュール全体の色、境界線、フォント、パディングなどのスタイルを制御します。</span><span class="sxs-lookup"><span data-stu-id="6c512-117">The retailer then applies a theme to control styling, such as colors, borders, fonts, padding, and so on across modules.</span></span> <span data-ttu-id="6c512-118">テーマは年間を通じて変わる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="6c512-118">Themes might change throughout the year.</span></span> <span data-ttu-id="6c512-119">たとえば、休日のテーマや新学期のテーマがある場合があり、テーマは小売業者のブランドに合わせてカスタマイズされます。</span><span class="sxs-lookup"><span data-stu-id="6c512-119">For example, there might be a holiday theme or a back-to-school theme, and the themes are customized to the retailer’s brand.</span></span> <span data-ttu-id="6c512-120">テンプレート、ページ、モジュール、およびそれらの中のコンテンツは、認証されたセキュリティ、バージョン管理、グローバルな冗長性、メディア ストリーミング機能を提供する Dynamics 365 e-commerce CMS に存在します。</span><span class="sxs-lookup"><span data-stu-id="6c512-120">Templates, pages, modules, and the content within them reside in the Dynamics 365 e-commerce CMS, which provides authenticated security, versioning, global redundancy, and media streaming capabilities.</span></span> <span data-ttu-id="6c512-121">CMS に保存されたデータは、eコマース レンダリング サービスによって消費されます。このサービスは、すべての一般的なディスプレイ サイズに適合するように応答性と柔軟性を備えたレンダリング HTML を提供します。</span><span class="sxs-lookup"><span data-stu-id="6c512-121">Data stored in the CMS is consumed by the e-commerce rendering service, which provides rendered HTML that is responsive and flexible to fit all common display sizes.</span></span>
<!--feature detail end -->











