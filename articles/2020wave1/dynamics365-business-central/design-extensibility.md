---
title: 拡張性のデザイン
description: ''
author: relnotes
ms.reviewer: bholtorf
ms.date: 03/19/2020
ms.assetid: bc92b8ed-4847-ea11-a812-000d3a579c33
ms.topic: article
ms.service: business-applications
ms.author: andreipa
dynamics365pdf: true
ms.openlocfilehash: 8dc39a46f487ad9c07b839d20b53194045d618ea
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232937"
---
# <a name="design-for-extensibility"></a><span data-ttu-id="2dacc-102">拡張性のデザイン</span><span class="sxs-lookup"><span data-stu-id="2dacc-102">Design for extensibility</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="2dacc-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="2dacc-103">Enabled for</span></span>    |  <span data-ttu-id="2dacc-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2dacc-104">Public preview</span></span> | <span data-ttu-id="2dacc-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="2dacc-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="2dacc-106">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="2dacc-106">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="2dacc-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2dacc-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2dacc-108">2020 年 2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="2dacc-108">Feb 7, 2020</span></span>| <span data-ttu-id="2dacc-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="2dacc-109">Apr 2020</span></span>|




## <a name="business-value"></a><span data-ttu-id="2dacc-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2dacc-110">Business value</span></span>
<span data-ttu-id="2dacc-111">マイクロソフトでは、システム アプリケーションとアプリケーション基盤を形成するシステム ロジックをモジュールに抽出することによって、コア アプリケーションの機能をさらに絞り込み、拡張の可能性を広げ、ローカライズをより簡単にするための取り組みを継続しています。</span><span class="sxs-lookup"><span data-stu-id="2dacc-111">We are continuing our efforts to make the core application leaner, more extensible, and easier to localize by extracting our system logic into modules that form a system application and an application foundation.</span></span> <span data-ttu-id="2dacc-112">これらのモジュールでは、*1 機能 = 1 モジュール*の原則に従って、簡潔さに焦点を当てています。</span><span class="sxs-lookup"><span data-stu-id="2dacc-112">These modules focus on simplicity by following a *one feature = one module* principle.</span></span> <span data-ttu-id="2dacc-113">各モジュールでは、複雑さがカプセル化され、実装の詳細がクリーンで文書化されて安定した API に置き換えられています。</span><span class="sxs-lookup"><span data-stu-id="2dacc-113">Each module encapsulates complexity and replaces implementation details with clean, documented, and stable APIs.</span></span> <span data-ttu-id="2dacc-114">これらによって開発サイクルがスピードアップし、セキュリティとパフォーマンスの観点から機能の監視と最適化が容易になります。</span><span class="sxs-lookup"><span data-stu-id="2dacc-114">They speed up the development cycle and make it easier to monitor and optimize functionality from security and performance perspectives.</span></span> <span data-ttu-id="2dacc-115">モジュールの数は構成によって異なり、各モジュールを個別に拡張することができます。</span><span class="sxs-lookup"><span data-stu-id="2dacc-115">The number of modules can vary depending on the configuration, and you can extend each module individually.</span></span> <span data-ttu-id="2dacc-116">これは、マイクロソフトとパートナー コミュニティの両方にとって開発パラダイムの大きな変化であるため、2020 年リリース ウェーブ 1 よりはるかに早く各モジュールのソース コードを利用可能にしています。</span><span class="sxs-lookup"><span data-stu-id="2dacc-116">Because this is a major shift in the development paradigm for both Microsoft and our partner community, we’re making the source code for each module available ahead of 2020 release wave 1.</span></span>

## <a name="feature-details"></a><span data-ttu-id="2dacc-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2dacc-117">Feature details</span></span>
<span data-ttu-id="2dacc-118">モジュールが完成したら、ソース コードを GitHub 上の [ALAppExtensions リポジトリ](https://github.com/Microsoft/ALAppExtensions)に公開します。</span><span class="sxs-lookup"><span data-stu-id="2dacc-118">When we finish modules we publish their source code in the [ALAppExtensions repo](https://github.com/Microsoft/ALAppExtensions) on GitHub.</span></span> <span data-ttu-id="2dacc-119">それを調べ、直接フィードバックを提供し、貢献することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="2dacc-119">We encourage you to explore it and provide direct feedback and make contributions.</span></span> <span data-ttu-id="2dacc-120">現在、次のモジュールを使用できます。</span><span class="sxs-lookup"><span data-stu-id="2dacc-120">The following modules are available now:</span></span>

|<span data-ttu-id="2dacc-121">名前</span><span class="sxs-lookup"><span data-stu-id="2dacc-121">Name</span></span>|<span data-ttu-id="2dacc-122">責任</span><span class="sxs-lookup"><span data-stu-id="2dacc-122">Responsibility</span></span>|
|---|---|
|[<span data-ttu-id="2dacc-123">Advanced Setting</span><span class="sxs-lookup"><span data-stu-id="2dacc-123">Advanced Settings</span></span>](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Advanced%20Settings)| <span data-ttu-id="2dacc-124">詳細設定と関連する統合イベントを含むページを公開します。</span><span class="sxs-lookup"><span data-stu-id="2dacc-124">Exposes a page that contains advanced settings and related integration events.</span></span>|
|[<span data-ttu-id="2dacc-125">Navigation Bar Subscribers</span><span class="sxs-lookup"><span data-stu-id="2dacc-125">Navigation Bar Subscribers</span></span>](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Navigation%20Bar%20Subscribers)| <span data-ttu-id="2dacc-126">システム イベントの既定のサブスクライバーとナビゲーション バーの対応するオーバーライド可能な統合イベントを公開します。</span><span class="sxs-lookup"><span data-stu-id="2dacc-126">Exposes default subscribers to system events and corresponding overridable integration events for the Navigation Bar.</span></span>|
|[<span data-ttu-id="2dacc-127">Camera and Media Interaction</span><span class="sxs-lookup"><span data-stu-id="2dacc-127">Camera and Media Interaction</span></span>](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Camera%20and%20Media%20Interaction)| <span data-ttu-id="2dacc-128">カメラとクライアント デバイスに保存されたメディアへのアクセスを提供します。</span><span class="sxs-lookup"><span data-stu-id="2dacc-128">Provides access to the camera and saved media on the client device.</span></span> <span data-ttu-id="2dacc-129">[カメラ] ページを呼び出してカメラ ビューを開き、クライアント デバイスで写真を撮ります。</span><span class="sxs-lookup"><span data-stu-id="2dacc-129">Invoke the Camera page to open the camera view and take a picture on your client device.</span></span> <span data-ttu-id="2dacc-130">このページには、カメラの可用性と写真の保存の進行状況が表示されます。</span><span class="sxs-lookup"><span data-stu-id="2dacc-130">The page shows the availability of the camera and progress in saving the picture.</span></span> <span data-ttu-id="2dacc-131">[メディア アップロード] ページを呼び出して、クライアント デバイスから保存されたメディアをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="2dacc-131">Invoke the Media Upload page to upload saved media from your client device.</span></span>|
|<span data-ttu-id="2dacc-132">Feature Key</span><span class="sxs-lookup"><span data-stu-id="2dacc-132">Feature Key</span></span>| <span data-ttu-id="2dacc-133">テナントに対して有効にする機能を選択するための機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="2dacc-133">Provides functionality for selecting the features to enable for a tenant.</span></span>|
|[<span data-ttu-id="2dacc-134">OAuth</span><span class="sxs-lookup"><span data-stu-id="2dacc-134">OAuth</span></span>](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/OAuth)| <span data-ttu-id="2dacc-135">Oauth 1.0 認証プロトコルに関して、認証キーとシークレット、または認証ヘッダーを取得するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="2dacc-135">Provides helper methods for obtaining the authentication key and secret, or the authorization header in respect to the OAuth 1.0 authorization protocol.</span></span>|
|<span data-ttu-id="2dacc-136">OAuth2</span><span class="sxs-lookup"><span data-stu-id="2dacc-136">OAuth2</span></span>| <span data-ttu-id="2dacc-137">Oauth 2.0 認証プロトコルの認証キーとシークレット、または認証ヘッダーを取得するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="2dacc-137">Provides helper methods for getting the authentication key and secret, or the authorization header for the OAuth 2.0 authorization protocol.</span></span>|
|[<span data-ttu-id="2dacc-138">OAuthClientAddIn</span><span class="sxs-lookup"><span data-stu-id="2dacc-138">OAuthClientAddIn</span></span>](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/OAuthClientAddIn)| <span data-ttu-id="2dacc-139">コントロール アドインと、リソースを承認するための特定のメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="2dacc-139">Provides the Control add-in and specific methods for authorizing a resource.</span></span>|
|<span data-ttu-id="2dacc-140">Printer Management</span><span class="sxs-lookup"><span data-stu-id="2dacc-140">Printer Management</span></span>|<span data-ttu-id="2dacc-141">テナントで使用可能なプリンターを管理するための機能が含まれています。</span><span class="sxs-lookup"><span data-stu-id="2dacc-141">Contains functionality for managing the printers that are available for a tenant.</span></span>|
|[<span data-ttu-id="2dacc-142">Table Information</span><span class="sxs-lookup"><span data-stu-id="2dacc-142">Table Information</span></span>](https://github.com/microsoft/ALAppExtensions/tree/master/Modules/System/Table%20Information)| <span data-ttu-id="2dacc-143">テーブルに関する情報を表示します。</span><span class="sxs-lookup"><span data-stu-id="2dacc-143">Displays information about tables.</span></span>|

<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="2dacc-144">関連項目</span><span class="sxs-lookup"><span data-stu-id="2dacc-144">See also</span></span>


<!--docs start-->
<span data-ttu-id="2dacc-145">[システム アプリケーションの概要](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-system-application-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="2dacc-145">[Overview of the System Application](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-system-application-overview) (docs)</span></span>
<!--docs end-->

