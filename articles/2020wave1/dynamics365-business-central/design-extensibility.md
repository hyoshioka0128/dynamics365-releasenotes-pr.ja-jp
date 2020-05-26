---
title: 拡張性のデザイン
description: Microsoft では、システム アプリケーションとアプリケーション基盤を形成するシステム ロジックをモジュールに抽出することによって、コア アプリケーションの機能をさらに絞り込み、拡張の可能性を広げ、ローカライズをより簡単にするための取り組みを継続しています。 これらのモジュールでは、*1 機能 = 1 モジュール*の原則に従って、簡潔さに焦点を当てています。 各モジュールでは、複雑さがカプセル化され、実装の詳細がクリーンで文書化されて安定した API に置き換えられています。 これらによって開発サイクルがスピードアップし、セキュリティとパフォーマンスの観点から機能の監視と最適化が容易になります。 モジュールの数は構成によって異なり、各モジュールを個別に拡張することができます。 これは、Microsoft とパートナー コミュニティの両方にとって開発パラダイムの大きな変化であるため、2020 年リリース ウェーブ 1 よりはるかに早く各モジュールのソース コードを利用可能にしています。
author: relnotes
ms.reviewer: bholtorf
ms.date: 04/20/2020
ms.assetid: bc92b8ed-4847-ea11-a812-000d3a579c33
ms.topic: article
ms.service: business-applications
ms.author: andreipa
dynamics365pdf: true
ms.openlocfilehash: ae7340b45d1827d998dc94b091ab5add4c05e0d5
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3293975"
---
# <a name="design-for-extensibility"></a><span data-ttu-id="a77e1-108">拡張性のデザイン</span><span class="sxs-lookup"><span data-stu-id="a77e1-108">Design for extensibility</span></span>


| <span data-ttu-id="a77e1-109">有効対象</span><span class="sxs-lookup"><span data-stu-id="a77e1-109">Enabled for</span></span>    |  <span data-ttu-id="a77e1-110">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a77e1-110">Public preview</span></span> | <span data-ttu-id="a77e1-111">一般提供</span><span class="sxs-lookup"><span data-stu-id="a77e1-111">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a77e1-112">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="a77e1-112">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="a77e1-113">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a77e1-113">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a77e1-114">2020 年 2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="a77e1-114">Feb 7, 2020</span></span>| <span data-ttu-id="a77e1-115">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a77e1-115">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a77e1-116">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a77e1-116">Apr 1, 2020</span></span>|

## <a name="business-value"></a><span data-ttu-id="a77e1-117">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a77e1-117">Business value</span></span>
<span data-ttu-id="a77e1-118">Microsoft では、システム アプリケーションとアプリケーション基盤を形成するシステム ロジックをモジュールに抽出することによって、コア アプリケーションの機能をさらに絞り込み、拡張の可能性を広げ、ローカライズをより簡単にするための取り組みを継続しています。</span><span class="sxs-lookup"><span data-stu-id="a77e1-118">We are continuing our efforts to make the core application leaner, more extensible, and easier to localize by extracting our system logic into modules that form a system application and an application foundation.</span></span> <span data-ttu-id="a77e1-119">これらのモジュールでは、*1 機能 = 1 モジュール*の原則に従って、簡潔さに焦点を当てています。</span><span class="sxs-lookup"><span data-stu-id="a77e1-119">These modules focus on simplicity by following a *one feature = one module* principle.</span></span> <span data-ttu-id="a77e1-120">各モジュールでは、複雑さがカプセル化され、実装の詳細がクリーンで文書化されて安定した API に置き換えられています。</span><span class="sxs-lookup"><span data-stu-id="a77e1-120">Each module encapsulates complexity and replaces implementation details with clean, documented, and stable APIs.</span></span> <span data-ttu-id="a77e1-121">これらによって開発サイクルがスピードアップし、セキュリティとパフォーマンスの観点から機能の監視と最適化が容易になります。</span><span class="sxs-lookup"><span data-stu-id="a77e1-121">They speed up the development cycle and make it easier to monitor and optimize functionality from security and performance perspectives.</span></span> <span data-ttu-id="a77e1-122">モジュールの数は構成によって異なり、各モジュールを個別に拡張することができます。</span><span class="sxs-lookup"><span data-stu-id="a77e1-122">The number of modules can vary depending on the configuration, and you can extend each module individually.</span></span> <span data-ttu-id="a77e1-123">これは、Microsoft とパートナー コミュニティの両方にとって開発パラダイムの大きな変化であるため、2020 年リリース ウェーブ 1 よりはるかに早く各モジュールのソース コードを利用可能にしています。</span><span class="sxs-lookup"><span data-stu-id="a77e1-123">Because this is a major shift in the development paradigm for both Microsoft and our partner community, we’re making the source code for each module available ahead of 2020 release wave 1.</span></span>



## <a name="feature-details"></a><span data-ttu-id="a77e1-124">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a77e1-124">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a77e1-125">モジュールが完成したら、ソース コードを GitHub 上の [ALAppExtensions repo](https://github.com/Microsoft/ALAppExtensions) に公開します。</span><span class="sxs-lookup"><span data-stu-id="a77e1-125">When we finish modules, we publish their source code in the [ALAppExtensions repo](https://github.com/Microsoft/ALAppExtensions) on GitHub.</span></span> <span data-ttu-id="a77e1-126">それを調べ、直接フィードバックを提供し、貢献することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="a77e1-126">We encourage you to explore it and provide direct feedback and make contributions.</span></span> <span data-ttu-id="a77e1-127">現在、次のモジュールを使用できます。</span><span class="sxs-lookup"><span data-stu-id="a77e1-127">The following modules are available now:</span></span>

|<span data-ttu-id="a77e1-128">名前</span><span class="sxs-lookup"><span data-stu-id="a77e1-128">Name</span></span>|<span data-ttu-id="a77e1-129">責任</span><span class="sxs-lookup"><span data-stu-id="a77e1-129">Responsibility</span></span>|
|---|---|
|[<span data-ttu-id="a77e1-130">Advanced Setting</span><span class="sxs-lookup"><span data-stu-id="a77e1-130">Advanced Settings</span></span>](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Advanced%20Settings)| <span data-ttu-id="a77e1-131">詳細設定と関連する統合イベントを含むページを公開します。</span><span class="sxs-lookup"><span data-stu-id="a77e1-131">Exposes a page that contains advanced settings and related integration events.</span></span>|
|[<span data-ttu-id="a77e1-132">Navigation Bar Subscribers</span><span class="sxs-lookup"><span data-stu-id="a77e1-132">Navigation Bar Subscribers</span></span>](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Navigation%20Bar%20Subscribers)| <span data-ttu-id="a77e1-133">システム イベントの既定のサブスクライバーとナビゲーション バーの対応するオーバーライド可能な統合イベントを公開します。</span><span class="sxs-lookup"><span data-stu-id="a77e1-133">Exposes default subscribers to system events and corresponding overridable integration events for the Navigation Bar.</span></span>|
|[<span data-ttu-id="a77e1-134">Camera and Media Interaction</span><span class="sxs-lookup"><span data-stu-id="a77e1-134">Camera and Media Interaction</span></span>](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Camera%20and%20Media%20Interaction)| <span data-ttu-id="a77e1-135">カメラとクライアント デバイスに保存されたメディアへのアクセスを提供します。</span><span class="sxs-lookup"><span data-stu-id="a77e1-135">Provides access to the camera and saved media on the client device.</span></span> <span data-ttu-id="a77e1-136">[カメラ] ページを呼び出してカメラ ビューを開き、クライアント デバイスで写真を撮ります。</span><span class="sxs-lookup"><span data-stu-id="a77e1-136">Invoke the Camera page to open the camera view and take a picture on your client device.</span></span> <span data-ttu-id="a77e1-137">このページには、カメラの可用性と写真の保存の進行状況が表示されます。</span><span class="sxs-lookup"><span data-stu-id="a77e1-137">The page shows the availability of the camera and progress in saving the picture.</span></span> <span data-ttu-id="a77e1-138">[メディア アップロード] ページを呼び出して、クライアント デバイスから保存されたメディアをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="a77e1-138">Invoke the Media Upload page to upload saved media from your client device.</span></span>|
|<span data-ttu-id="a77e1-139">Feature Key</span><span class="sxs-lookup"><span data-stu-id="a77e1-139">Feature Key</span></span>| <span data-ttu-id="a77e1-140">テナントに対して有効にする機能を選択するための機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="a77e1-140">Provides functionality for selecting the features to enable for a tenant.</span></span>|
|[<span data-ttu-id="a77e1-141">OAuth</span><span class="sxs-lookup"><span data-stu-id="a77e1-141">OAuth</span></span>](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/OAuth)| <span data-ttu-id="a77e1-142">Oauth 1.0 認証プロトコルに関して、認証キーとシークレット、または認証ヘッダーを取得するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="a77e1-142">Provides helper methods for obtaining the authentication key and secret, or the authorization header in respect to the OAuth 1.0 authorization protocol.</span></span>|
|<span data-ttu-id="a77e1-143">OAuth2</span><span class="sxs-lookup"><span data-stu-id="a77e1-143">OAuth2</span></span>| <span data-ttu-id="a77e1-144">Oauth 2.0 認証プロトコルの認証キーとシークレット、または認証ヘッダーを取得するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="a77e1-144">Provides helper methods for getting the authentication key and secret, or the authorization header for the OAuth 2.0 authorization protocol.</span></span>|
|[<span data-ttu-id="a77e1-145">OAuthClientAddIn</span><span class="sxs-lookup"><span data-stu-id="a77e1-145">OAuthClientAddIn</span></span>](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/OAuthClientAddIn)| <span data-ttu-id="a77e1-146">コントロール アドインと、リソースを承認するための特定のメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="a77e1-146">Provides the Control add-in and specific methods for authorizing a resource.</span></span>|
|<span data-ttu-id="a77e1-147">Printer Management</span><span class="sxs-lookup"><span data-stu-id="a77e1-147">Printer Management</span></span>|<span data-ttu-id="a77e1-148">テナントで使用可能なプリンターを管理するための機能が含まれています。</span><span class="sxs-lookup"><span data-stu-id="a77e1-148">Contains functionality for managing the printers that are available for a tenant.</span></span>|
|[<span data-ttu-id="a77e1-149">Table Information</span><span class="sxs-lookup"><span data-stu-id="a77e1-149">Table Information</span></span>](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Table%20Information)| <span data-ttu-id="a77e1-150">テーブルに関する情報を表示します。</span><span class="sxs-lookup"><span data-stu-id="a77e1-150">Displays information about tables.</span></span>|

<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="a77e1-151">関連項目</span><span class="sxs-lookup"><span data-stu-id="a77e1-151">See also</span></span>

<!--docs start-->
<span data-ttu-id="a77e1-152">[システム アプリケーションの概要](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-system-application-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="a77e1-152">[Overview of the System Application](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-system-application-overview) (docs)</span></span>
<!--docs end-->
