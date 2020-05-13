---
title: 検索エンジン最適化
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 02/11/2020
ms.assetid: aa63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: brshoo
dynamics365pdf: true
ms.openlocfilehash: 928b580fe64912b9ba0f96eb450857d93d25f9ba
ms.sourcegitcommit: bfe05af05f11f2c318a77bb3138c3df0796c7187
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/27/2020
ms.locfileid: "3088748"
---
# <a name="search-engine-optimization"></a><span data-ttu-id="c20b1-102">検索エンジン最適化</span><span class="sxs-lookup"><span data-stu-id="c20b1-102">Search engine optimization</span></span>


| <span data-ttu-id="c20b1-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="c20b1-103">Enabled for</span></span>    |  <span data-ttu-id="c20b1-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c20b1-104">Public preview</span></span> | <span data-ttu-id="c20b1-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="c20b1-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c20b1-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c20b1-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c20b1-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c20b1-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c20b1-108">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c20b1-108">Oct 1, 2019</span></span>| <span data-ttu-id="c20b1-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c20b1-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c20b1-110">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c20b1-110">Feb 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c20b1-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c20b1-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c20b1-112">正規 URL は、ページのメイン URL として機能するようにマーケティング マネージャーによって選択された URL のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="c20b1-112">A canonical URL is the version of a URL that has been selected by the marketing manager to act as the main URL for a page.</span></span> <span data-ttu-id="c20b1-113">例として、同じページに次の 2 つの URL が関連付けられているサイトについて考えます。</span><span class="sxs-lookup"><span data-stu-id="c20b1-113">As an example, consider a site that has the following two URLs associated with the same page:</span></span>   

- <span data-ttu-id="c20b1-114">contoso.com/womenswear/dresses/pid=9999</span><span class="sxs-lookup"><span data-stu-id="c20b1-114">contoso.com/womenswear/dresses/pid=9999</span></span> 

- <span data-ttu-id="c20b1-115">contoso.com/sale/clearance/dresses/pid=9999</span><span class="sxs-lookup"><span data-stu-id="c20b1-115">contoso.com/sale/clearance/dresses/pid=9999</span></span> 

<span data-ttu-id="c20b1-116">マーケティング マネージャーは、どの URL がページの最も代表的な URL であるかを検索エンジン ボットに通知し、それを正規 URL として定義する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c20b1-116">A marketing manager needs to inform search engine bots which URL is the most representative URL for the page and define it as the canonical URL.</span></span> <span data-ttu-id="c20b1-117">正規 URL を定義することにより、類似または重複するページのリンク シグナルを統合して、eコマース ページまたは Web サイトが検索エンジンによって不適切にランク付けされないようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="c20b1-117">By defining a canonical URL, the link signals for similar or duplicate pages can be consolidated to prevent an e-commerce page or website from being ranked poorly by search engines.</span></span> 

- <span data-ttu-id="c20b1-118">contoso.com/womenswear/dresses/pid=9999</span><span class="sxs-lookup"><span data-stu-id="c20b1-118">contoso.com/womenswear/dresses/pid=9999</span></span>

- <span data-ttu-id="c20b1-119">contoso.com/sale/clearance/dresses/pid=9999</span><span class="sxs-lookup"><span data-stu-id="c20b1-119">contoso.com/sale/clearance/dresses/pid=9999</span></span> 

<span data-ttu-id="c20b1-120">マーケティング マネージャーは、どの URL がページの最も代表的な URL であるかを検索エンジン ボットに通知し、それを正規 URL として定義する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c20b1-120">The marketing manager needs to inform the search engine bots which URL is the most representative URL for the page and define it as the canonical URL.</span></span> <span data-ttu-id="c20b1-121">正規 URL を定義することにより、類似または重複するページのリンク シグナルを統合して、eコマース ページまたは Web サイトが検索エンジンによって不適切にランク付けされないようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="c20b1-121">By defining the canonical URL, the link signals for similar or duplicate pages can be consolidated to prevent an e-commerce page or website from being ranked poorly by search engines.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c20b1-122">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c20b1-122">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c20b1-123">すっきりした一貫性のある HTML エクスペリエンスを保証するテンプレートとモジュールを使用して、検索エンジン フレンドリなページを簡単に作成および管理できます。</span><span class="sxs-lookup"><span data-stu-id="c20b1-123">Easily create and maintain pages that are friendly to search engines using templates and modules that ensure clutter-free and consistent HTML experiences.</span></span> <span data-ttu-id="c20b1-124">ページ タイトル、説明、およびネイティブ メタ タグを含めるか、カスタム データ アクションを使用してサード パーティのタグ付けシステムを使用することができます。</span><span class="sxs-lookup"><span data-stu-id="c20b1-124">You can include page titles, descriptions, and native meta tags, or use third-party tagging systems using custom data actions.</span></span> 

<span data-ttu-id="c20b1-125">URL 管理はページから完全に独立して行われます。</span><span class="sxs-lookup"><span data-stu-id="c20b1-125">URL management is done completely independently from pages.</span></span> <span data-ttu-id="c20b1-126">フォルダー構造はなく、サイト内の任意のページで任意の URL をポイントできます。</span><span class="sxs-lookup"><span data-stu-id="c20b1-126">There’s no folder structure, and any URL can be pointed at any page in your site.</span></span> <span data-ttu-id="c20b1-127">URL リダイレクトは、編集ツール セット内でも簡単に管理できます。</span><span class="sxs-lookup"><span data-stu-id="c20b1-127">URL redirects are also simple to manage within the editorial tool set.</span></span> <span data-ttu-id="c20b1-128">URL 管理の柔軟性と使いやすさにより、バニティ URL、サイト構造、SEO の考慮事項の適応と移行が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="c20b1-128">The flexibility and ease of URL management makes vanity URLs, site structures, and SEO considerations simple to adapt and migrate.</span></span>

<span data-ttu-id="c20b1-129">![SEO URL 管理](media/seo_urlmanagement.png "SEO URL 管理")</span><span class="sxs-lookup"><span data-stu-id="c20b1-129">![SEO URL management](media/seo_urlmanagement.png "SEO URL management")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="c20b1-130">関連項目</span><span class="sxs-lookup"><span data-stu-id="c20b1-130">See also</span></span>

<span data-ttu-id="c20b1-131">[SEO メタデータの管理](https://docs.microsoft.com/dynamics365/commerce/manage-seo-metadata) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c20b1-131">[Manage SEO metadata](https://docs.microsoft.com/dynamics365/commerce/manage-seo-metadata) (docs)</span></span>
