---
title: コードを書かずにユーザー プロファイルをカスタマイズする
description: ユーザー プロファイルを追加およびカスタマイズします。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 09/14/2019
ms.assetid: 846c8f04-e86b-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 1467c9aba60d8038705013809c9c4785a4e1aa15
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140713"
---
# <a name="customize-user-profiles-without-writing-code"></a><span data-ttu-id="70a46-103">コードを書かずにユーザー プロファイルをカスタマイズする</span><span class="sxs-lookup"><span data-stu-id="70a46-103">Customize user profiles without writing code</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="70a46-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="70a46-104">Enabled for</span></span>    |  <span data-ttu-id="70a46-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="70a46-105">Public preview</span></span> | <span data-ttu-id="70a46-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="70a46-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="70a46-107">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="70a46-107">Users, automatically</span></span>|<span data-ttu-id="70a46-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="70a46-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="70a46-109">2019 年 9 月 1 日</span><span class="sxs-lookup"><span data-stu-id="70a46-109">Sep 1, 2019</span></span>| <span data-ttu-id="70a46-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="70a46-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="70a46-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="70a46-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="70a46-112">組織は通常、明確に定義されたユーザー ロールで構成され、その一部はそのビジネス、部署、または業界に固有である可能性があります。</span><span class="sxs-lookup"><span data-stu-id="70a46-112">Organizations are typically composed of well-defined user roles, some of which might be unique to that business, department, or industry.</span></span> <span data-ttu-id="70a46-113">ユーザーは複数の部署にまたがって作業したり、必要に応じてさまざまなロールを果たすこともあります。</span><span class="sxs-lookup"><span data-stu-id="70a46-113">Users might work across multiple departments and occasionally stretch to fill a variety of roles as needed.</span></span> <span data-ttu-id="70a46-114">1 つのサイズではすべてに対応できない場合でも、Business Central は変化する固有のニーズに簡単に適応できます。</span><span class="sxs-lookup"><span data-stu-id="70a46-114">Where one size does not fit all, Business Central is ready to adapt to unique and changing needs.</span></span> <span data-ttu-id="70a46-115">パワー ユーザー、部署の所有者、およびコンサルタントは、どのタスクがどのロールに関連するかを制御する必要があり、コードのカスタマイズを必要とせずにロールの調整を管理できます。</span><span class="sxs-lookup"><span data-stu-id="70a46-115">Power users, department owners, and consultants need control over which tasks are relevant for any role, and are able to manage role-tailoring without the need for code customization.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="70a46-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="70a46-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="70a46-117">Business Central では、プロファイルを使用して、組織のロールとその基本的な設定 (そのロールに関連するコンテンツを表示する開始ホーム画面など) を定義および区別します。</span><span class="sxs-lookup"><span data-stu-id="70a46-117">In Business Central, profiles are used to define and distinguish organizational roles along with their basic settings, such as the starting home screen that displays content relevant to that role.</span></span> <span data-ttu-id="70a46-118">Business Central にはさまざまな専門的なロールや部署のニーズをカバーする一連のプロファイルが用意されており、管理者はそれをユーザーがパーソナライズするときと同様のツールを使用して完全にカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="70a46-118">Business Central provides a set of profiles covering a variety of specialized roles or departmental needs, which administrators can fully customize using tools similar to when users personalize.</span></span>

### <a name="administration-of-profiles-roles"></a><span data-ttu-id="70a46-119">プロファイル (ロール) の管理</span><span class="sxs-lookup"><span data-stu-id="70a46-119">Administration of profiles (roles)</span></span>
<span data-ttu-id="70a46-120">**プロファイル (ロール)** ページは、Business Central オンラインおよびオンプレミスでさまざまなタスクを実行するために使用します。</span><span class="sxs-lookup"><span data-stu-id="70a46-120">The **Profiles (Roles)** page is used to perform a variety of tasks in Business Central online and on-premises:</span></span>

 - <span data-ttu-id="70a46-121">利用可能なプロファイルの概要を取得します。これには、そのプロファイルの発生元である拡張機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="70a46-121">Get an overview of available profiles, including which extensions they might originate from.</span></span>
 - <span data-ttu-id="70a46-122">組織に関係のないプロファイルを削除するか、無効にします。</span><span class="sxs-lookup"><span data-stu-id="70a46-122">Remove or disable profiles that are not relevant to your organization.</span></span>
 - <span data-ttu-id="70a46-123">どのプロファイルがロール エクスプローラーに適しているかを決定して、すべてのユーザーが複数のロールや部署にわたって新しいコンテンツをナビゲートして見つけられるようにします。</span><span class="sxs-lookup"><span data-stu-id="70a46-123">Determine which profiles are fit for the Role Explorer so that any user can navigate and find new content across roles or departments.</span></span>
 - <span data-ttu-id="70a46-124">一意のロールを表す新しいプロファイルを追加するか、プロファイル (拡張機能から発生したものを含む) を編集します。</span><span class="sxs-lookup"><span data-stu-id="70a46-124">Add new profiles to represent unique roles or edit any profile, including those originating from extensions.</span></span>
 - <span data-ttu-id="70a46-125">プロファイル URL パラメーターを使用して、任意のプロファイルに直接リンクする URL を作成および共有します。</span><span class="sxs-lookup"><span data-stu-id="70a46-125">Create and share URLs that link directly to any profile using the profile URL parameter.</span></span>

<span data-ttu-id="70a46-126">![プロファイル一覧ページに表示されたさまざまなプロファイル](media/profiles-list.png "プロファイル一覧ページに表示されたさまざまなプロファイル")</span><span class="sxs-lookup"><span data-stu-id="70a46-126">![A variety of profiles shown in the profiles list page](media/profiles-list.png "A variety of profiles shown in the profiles list page")</span></span>

### <a name="customizing-pages-for-a-specific-role"></a><span data-ttu-id="70a46-127">特定のロールのページのカスタマイズ</span><span class="sxs-lookup"><span data-stu-id="70a46-127">Customizing pages for a specific role</span></span>
<span data-ttu-id="70a46-128">Dynamics NAV のプロファイル構成モードと同様に、Business Central のデスクトップ エクスペリエンスでは、同じプロファイルを共有するユーザーに対して軽量の UI カスタマイズが可能です。</span><span class="sxs-lookup"><span data-stu-id="70a46-128">Similar to profile configuration mode in Dynamics NAV, the Business Central desktop experience allows lightweight UI customizations for users who share the same profile.</span></span> <span data-ttu-id="70a46-129">これは、すべての運用環境またはサンドボックス環境で、Visual Studio Code と AL を使用しないで行うことができます。</span><span class="sxs-lookup"><span data-stu-id="70a46-129">This can be done on any production or sandbox environment without the use of Visual Studio Code and AL.</span></span>

  - <span data-ttu-id="70a46-130">パーソナル化ツールのすべての豊富な機能を活用して、そのプロファイルの軽量の UI カスタマイズを行い、設計の間にカスタマイズをテストします。</span><span class="sxs-lookup"><span data-stu-id="70a46-130">Leverage all the rich capabilities of the personalization tool to make lightweight UI customization of that profile and test your customization while you design.</span></span> <span data-ttu-id="70a46-131">このようなカスタマイズの例として、ロール固有のリスト ビューの作成、ナビゲーション メニューの定義、ページ上のフィールドの非表示などがあります。</span><span class="sxs-lookup"><span data-stu-id="70a46-131">Examples of such customization include creating a role-specific list view, defining a navigation menu, or hiding fields on a page.</span></span>
 - <span data-ttu-id="70a46-132">プロファイルごとにカスタマイズされたページのセットを表示し、ページごとのカスタマイズをクリアします。</span><span class="sxs-lookup"><span data-stu-id="70a46-132">View the set of pages that have been customized per profile and clear customizations per page.</span></span>
 - <span data-ttu-id="70a46-133">すべてのプロファイル カスタマイズのコピーを AL 形式でエクスポートします。これは、たとえば拡張機能に含めるために開発者にすぐに渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="70a46-133">Export a copy of all profile customizations in AL format that is ready to hand off to developers to include in an extension, for example.</span></span>

<span data-ttu-id="70a46-134">![営業およびリレーションシップ マネージャーのプロファイルを UI で直接カスタマイズする](media/customize-profile.png "営業およびリレーションシップ マネージャーのプロファイルを UI で直接カスタマイズする")</span><span class="sxs-lookup"><span data-stu-id="70a46-134">![Customizing the sales and relationship manager profile directly in the UI](media/customize-profile.png "Customizing the sales and relationship manager profile directly in the UI")</span></span>

<span data-ttu-id="70a46-135">ユーザー プロファイルのカスタマイズでは、オブジェクトやデータへのアクセスがセキュリティで保護されないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="70a46-135">Note that customization of user profiles does not secure access to objects or data.</span></span> <span data-ttu-id="70a46-136">管理者は、関連するユーザー グループまたはアクセス許可セットを依然として適用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="70a46-136">Administrators are still required to apply the relevant user groups or permissions sets.</span></span>

### <a name="more-profiles-in-the-box"></a><span data-ttu-id="70a46-137">ボックス内のプロファイルの追加</span><span class="sxs-lookup"><span data-stu-id="70a46-137">More profiles in the box</span></span>
<span data-ttu-id="70a46-138">Business Central オンラインに、以前はサンドボックス環境でしか使用できなかったプロファイルが含まれるようになりました。</span><span class="sxs-lookup"><span data-stu-id="70a46-138">Business Central online now includes profiles previously available only to sandbox environments.</span></span> <span data-ttu-id="70a46-139">さらに、一部の国または地域で、幅広い部署機能をカバーする 10 個のまったく新しいプロファイルを使用できます。</span><span class="sxs-lookup"><span data-stu-id="70a46-139">In addition, 10 entirely new profiles covering the breadth of departmental functionality are available in select countries or regions.</span></span>

### <a name="upgrading-from-an-earlier-version-of-business-central"></a><span data-ttu-id="70a46-140">以前のバージョンの Business Central からのアップグレード</span><span class="sxs-lookup"><span data-stu-id="70a46-140">Upgrading from an earlier version of Business Central</span></span>
<span data-ttu-id="70a46-141">今回のリリースでは、ユーザー プロファイルの定義、保存、カスタマイズの方法が大幅に見直され、これらの機能がクラウドおよび最新のクライアント向けに提供されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="70a46-141">With this release, the way user profiles are defined, stored, and customized has undergone a major overhaul to unlock these capabilities for the cloud and for the modern clients.</span></span> <span data-ttu-id="70a46-142">Business Central オンラインとオンプレミスの両方で、一貫したエクスペリエンスと豊富な機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="70a46-142">Both Business Central online and on-premises are now consistent in experience and richness of capability.</span></span> <span data-ttu-id="70a46-143">このリリースでの重要な変更点は以下のとおりです。</span><span class="sxs-lookup"><span data-stu-id="70a46-143">Below are important changes in this release:</span></span>

 - <span data-ttu-id="70a46-144">プロファイルおよびページのカスタマイズが開発者によって AL で作成されたか、またはコンサルタントやパワー ユーザーによってクライアント内で直接作成されたかに関係なく、AL 言語がそれらのカスタマイズを一貫して記述するために使用される基本の構文となります。</span><span class="sxs-lookup"><span data-stu-id="70a46-144">The AL language is now the underlying syntax used to consistently describe profiles and page customizations, whether they were authored by a developer in AL or by a consultant or power user directly in the client.</span></span> <span data-ttu-id="70a46-145">従来の XML 形式は廃止されます。</span><span class="sxs-lookup"><span data-stu-id="70a46-145">The legacy XML format is discontinued.</span></span>
 - <span data-ttu-id="70a46-146">Business Central で利用できるプロファイルのセットに、ページのカスタマイズが含まれなくなります。</span><span class="sxs-lookup"><span data-stu-id="70a46-146">The set of profiles available with Business Central no longer includes page customizations.</span></span> <span data-ttu-id="70a46-147">これらのプロファイルのユーザーに対しては、ロールのページのレイアウトが若干変更される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="70a46-147">Users of these profiles might experience slight differences in the layout of pages for their roles.</span></span>
 - <span data-ttu-id="70a46-148">データベースをアップグレードすると、従来のすべてのプロファイルを引き続き利用できますが、それに付随するプロファイル設定は破棄されます。</span><span class="sxs-lookup"><span data-stu-id="70a46-148">When upgrading your database, any legacy profiles remain available but their accompanying profile configuration is discarded.</span></span> <span data-ttu-id="70a46-149">以前のバージョンを使用して作成された従来のプロファイル構成は、Business Central 2019 ウェーブ 2 以降と互換性がありません。</span><span class="sxs-lookup"><span data-stu-id="70a46-149">Legacy profile configuration created using earlier versions is not compatible with Business Central 2019 wave 2 and later.</span></span> <span data-ttu-id="70a46-150">ページのカスタマイズは Business Central クライアントを使用して再作成するか、AL 拡張機能として再作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="70a46-150">Page customizations must be either recreated using the Business Central client or as an AL extension.</span></span>
 - <span data-ttu-id="70a46-151">さまざまなシステム テーブルが、導入、変更、または廃止とマークされています。</span><span class="sxs-lookup"><span data-stu-id="70a46-151">Various system tables have been introduced, have changed, or are marked as obsolete.</span></span> <span data-ttu-id="70a46-152">それらに依存するページ オブジェクトは、新しいプロファイル モデルを反映するようにフィールドと機能が更新されています。</span><span class="sxs-lookup"><span data-stu-id="70a46-152">Page objects that depend on them have been updated with fields and functionality to reflect the new profile model.</span></span>
 - <span data-ttu-id="70a46-153">Business Central でシステム プロファイルとテナント プロファイルの区別がなくなり、管理者はシステム スコープのプロファイルを指定できなくなりました。</span><span class="sxs-lookup"><span data-stu-id="70a46-153">Business Central no longer distinguishes between System and Tenant profiles, and administrators can no longer specify a profile of System scope.</span></span> <span data-ttu-id="70a46-154">ただし、拡張機能を使用してマルチテナント サーバー上のすべての顧客用の開始プロファイル セットを定義することは可能です。</span><span class="sxs-lookup"><span data-stu-id="70a46-154">Defining a starting set of profiles for all customers on a multitenant server can still be achieved using extensions.</span></span>

<!--feature detail end -->








## <a name="tell-us-what-you-think"></a><span data-ttu-id="70a46-155">フィードバック</span><span class="sxs-lookup"><span data-stu-id="70a46-155">Tell us what you think</span></span>
<span data-ttu-id="70a46-156">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="70a46-156">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="70a46-157">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="70a46-157">Use the forum at https://aka.ms/bcideas.</span></span>



