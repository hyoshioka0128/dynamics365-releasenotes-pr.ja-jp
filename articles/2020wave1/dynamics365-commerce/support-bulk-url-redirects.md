---
title: 一括 URL リダイレクトのサポート
description: 小売業者は、簡単な方法でサイトの Web リダイレクトを一括で制御できるようになりました。 単純な CSV 形式を利用して必要なリダイレクトのタイプを指定することで、URL リダイレクトを制御できます。 これにより、ドメイン所有者は古い URL にランディングしたユーザーを前のサイトの SEO ランキングを維持しながら目的の Web エクスペリエンスにランディングさせて、目的のエクスペリエンスをエンド ユーザーに提供することができます。
author: relnotes
ms.reviewer: josaw
ms.date: 04/07/2020
ms.assetid: d254d58e-631d-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: brshoo
dynamics365pdf: true
ms.openlocfilehash: fe564094173dc32b4030774d95e261c9a48bda57
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3272633"
---
# <a name="support-for-bulk-url-redirects"></a><span data-ttu-id="1ff61-105">一括 URL リダイレクトのサポート</span><span class="sxs-lookup"><span data-stu-id="1ff61-105">Support for bulk URL redirects</span></span>


| <span data-ttu-id="1ff61-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="1ff61-106">Enabled for</span></span>    |  <span data-ttu-id="1ff61-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1ff61-107">Public preview</span></span> | <span data-ttu-id="1ff61-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="1ff61-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1ff61-109">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="1ff61-109">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="1ff61-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1ff61-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1ff61-111">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="1ff61-111">Feb 3, 2020</span></span>| <span data-ttu-id="1ff61-112">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1ff61-112">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1ff61-113">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="1ff61-113">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1ff61-114">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1ff61-114">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1ff61-115">Dynamics 365 Commerce でサイトを構築している小売業者は、そのページに対するドメイン リダイレクトを一括形式で管理できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="1ff61-115">Retailers building their site in Dynamics 365 Commerce can now manage their domain redirects for their pages in bulk format.</span></span> <span data-ttu-id="1ff61-116">Commerce では、Site Builder を介した CSV マッピング ファイルのアップロードとダウンロードがサポートされ、リダイレクトの大きなリストを管理できます。</span><span class="sxs-lookup"><span data-stu-id="1ff61-116">Through Site Builder, Commerce will support the upload and download of a CSV mapping file to manage a large list of redirects.</span></span> <span data-ttu-id="1ff61-117">この機能により、顧客のドメインが Commerce のホスト ページを参照するように切り替えることで、時間と労力が軽減され、以前の URL で新しいホスト コンテンツが提供されるようになり、こうした URL にアクセスする可能性のあるユーザーのエラーを回避できます。</span><span class="sxs-lookup"><span data-stu-id="1ff61-117">When the customer’s domain switches to point to Commerce-hosted pages, this feature saves time and effort to ensure the previous URLs will now serve the new hosted content and prevents errors for users who might be hitting those URLs.</span></span> <span data-ttu-id="1ff61-118">再マッピングでは、以前に確立された SEO も保持されます。</span><span class="sxs-lookup"><span data-stu-id="1ff61-118">Remapping also preserves the previously established SEO.</span></span> <span data-ttu-id="1ff61-119">マッピング ファイルにより、Commerce ユーザーはドメイン マッピングを簡単な CSV 形式で効率的に管理できるため、時間を節約できます。</span><span class="sxs-lookup"><span data-stu-id="1ff61-119">The mapping file will save Commerce users time by enabling the efficient managing of their domain mappings in an easy CSV format.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1ff61-120">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1ff61-120">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1ff61-121">特定のサイトに対する Site Builder で、CSV 形式の URL リダイレクト マッピング ファイルをアップロードまたはダウンロードできるメニュー オプションが用意されています。</span><span class="sxs-lookup"><span data-stu-id="1ff61-121">Within Site Builder for a given site, a menu option will be available to allow a URL redirect mapping file in CSV format to be uploaded or downloaded.</span></span> <span data-ttu-id="1ff61-122">CSV ファイルでは、"ソース" URL と "ターゲット" URL を参照すること、そのリダイレクション タイプ (301/302)、ソース URL で大文字と小文字を区別するかどうか (既定値は false) を指定できます。</span><span class="sxs-lookup"><span data-stu-id="1ff61-122">The CSV file allows for referencing "source" and "Target" URLs, the redirection type (301/302), and if the source URL is case-sensitive (the default is false).</span></span> <span data-ttu-id="1ff61-123">このアップロード後に、Commerce レンダリング プラットフォームはユーザー トラフィックを管理し、ユーザーをターゲット URL に誘導します。</span><span class="sxs-lookup"><span data-stu-id="1ff61-123">Once uploaded, the Commerce rendering platform will manage user traffic to direct users to the target URL.</span></span> <span data-ttu-id="1ff61-124">この CSV は Site Builder ツールからダウンロードし、ユーザーが取り込んで編集できます (この機能では Site Builder 内での編集はサポートされていません)。</span><span class="sxs-lookup"><span data-stu-id="1ff61-124">The CSV can be downloaded from the Site Builder tool to capture and edit by the user (editing within Site Builder is not supported with this feature).</span></span> <span data-ttu-id="1ff61-125">編集後、ユーザーは CSV ファイルを再アップロードして、提供された以前のマッピング CSV を上書きできます。</span><span class="sxs-lookup"><span data-stu-id="1ff61-125">Once edited, the user can re-upload the CSV file to override the previous mapping CSV supplied.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="1ff61-126">関連項目</span><span class="sxs-lookup"><span data-stu-id="1ff61-126">See also</span></span>

<!--docs start-->
<span data-ttu-id="1ff61-127">[URL リダイレクトの一括アップロード](https://docs.microsoft.com/dynamics365/commerce/upload-bulk-redirects) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="1ff61-127">[Upload URL redirects in bulk](https://docs.microsoft.com/dynamics365/commerce/upload-bulk-redirects) (docs)</span></span>
<!--docs end-->
