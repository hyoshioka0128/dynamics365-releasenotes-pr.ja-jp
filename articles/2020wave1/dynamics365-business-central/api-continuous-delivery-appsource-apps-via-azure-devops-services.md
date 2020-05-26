---
title: Azure DevOps サービスを介して Business Central アプリを継続的に配信するための API
description: Business Central アプリを構築するパートナーが、Business Central Online の顧客にアプリを継続的に配信できるようにします。 パートナーは新しい API と Azure DevOps サービスを使用して、アプリを管理し、リリースのステップを調整します。
author: relnotes
ms.reviewer: jswymer
ms.date: 05/01/2020
ms.assetid: 3d625248-2ccb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: dmitrych
dynamics365pdf: true
ms.openlocfilehash: a8072ab57c8be827adf79a4d9d92d583fbc5e012
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350097"
---
# <a name="api-for-continuous-delivery-of-the-business-central-apps-via-azure-devops-services"></a><span data-ttu-id="816f6-104">Azure DevOps サービスを介して Business Central アプリを継続的に配信するための API</span><span class="sxs-lookup"><span data-stu-id="816f6-104">API for continuous delivery of the Business Central apps via Azure DevOps services</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="816f6-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="816f6-105">Enabled for</span></span>    |  <span data-ttu-id="816f6-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="816f6-106">Public preview</span></span> | <span data-ttu-id="816f6-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="816f6-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="816f6-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="816f6-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="816f6-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="816f6-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="816f6-110">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="816f6-110">Apr 1, 2020</span></span>| <span data-ttu-id="816f6-111">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="816f6-111">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="816f6-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="816f6-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="816f6-113">Business Central のパートナーは、Azure DevOps を使用して、ビルド プロセスと Business Central online へのデプロイを調整できます。</span><span class="sxs-lookup"><span data-stu-id="816f6-113">Partners of Business Central can use Azure DevOps to orchestrate their build processes and deployments to Business Central online.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="816f6-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="816f6-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="816f6-115">グローバル パートナー コミュニティと Business Central パートナー コミュニティでは、特に、継続的インテグレーション/継続的配信と DevOps の原則に対する熱意が高まっています。</span><span class="sxs-lookup"><span data-stu-id="816f6-115">The global partner community and Business Central partner community, in particular, have a growing passion for continuous integration/continuous delivery and DevOps principles.</span></span>

<span data-ttu-id="816f6-116">Azure DevOps サービスでは継続的インテグレーションのプラクティスに従ってコードを管理するための豊富な機能が開発者に既に提供されています。</span><span class="sxs-lookup"><span data-stu-id="816f6-116">Azure DevOps services already provide a wealth of functionality for developers to manage their code following continuous integration practice:</span></span>

- <span data-ttu-id="816f6-117">コードは Visual Studio Code で作成されます。</span><span class="sxs-lookup"><span data-stu-id="816f6-117">Code is written in Visual Studio Code.</span></span>
- <span data-ttu-id="816f6-118">その後、コードはソース管理リポジトリに格納され、レビュー、分岐、マージされます。</span><span class="sxs-lookup"><span data-stu-id="816f6-118">Then, code is stored, reviewed, branched, and merged in a source control repository.</span></span>
- <span data-ttu-id="816f6-119">最後に、コードは、Business Central Docker コンテナーを対象としたビルド パイプラインを使用してビルドおよびテストされます。</span><span class="sxs-lookup"><span data-stu-id="816f6-119">Finally, code is built and tested using build pipelines, targeting Business Central Docker containers.</span></span>

<span data-ttu-id="816f6-120">次のステップは、Business Central Online サービスの顧客へのアプリの継続的配信をパートナーが実装できるようにすることです。</span><span class="sxs-lookup"><span data-stu-id="816f6-120">The next step is to enable partners with the ability to implement continuous delivery of their apps to Business Central online service customers.</span></span>  <span data-ttu-id="816f6-121">ソリューションは、新しい固定アプリ管理エンドポイント API です。</span><span class="sxs-lookup"><span data-stu-id="816f6-121">The solution is the new Fixed App Management Endpoint API.</span></span>

<span data-ttu-id="816f6-122">固定アプリ管理エンドポイント (または FAME) API は REST ベースの API です。</span><span class="sxs-lookup"><span data-stu-id="816f6-122">The Fixed App Management Endpoint (or FAME) API is a REST-based API.</span></span> <span data-ttu-id="816f6-123">これは、認定 ISV であることと、アプリが Microsoft によって登録されていることを必要とします。</span><span class="sxs-lookup"><span data-stu-id="816f6-123">It requires that you're an authorized ISV and your apps have been registered by Microsoft.</span></span> <span data-ttu-id="816f6-124">登録したら、グローバル エンドポイント (https://apps.businesscentral.dynamics.com) を使用して FAME API にアクセスします。</span><span class="sxs-lookup"><span data-stu-id="816f6-124">Once registered, you access the FAME API by using this global endpoint: https://apps.businesscentral.dynamics.com.</span></span>

<span data-ttu-id="816f6-125">API は次の操作に使用できます。</span><span class="sxs-lookup"><span data-stu-id="816f6-125">The API can be used for the following operations:</span></span>

- <span data-ttu-id="816f6-126">メジャー、マイナー、および修正プログラムのアプリ更新プログラムを、顧客が Business Central 管理センターからインストールできるようにします。</span><span class="sxs-lookup"><span data-stu-id="816f6-126">Make major, minor, and hotfix app updates available to customers for installation from the Business Central administration center.</span></span> <span data-ttu-id="816f6-127">更新プログラムを FAME アプリ リポジトリにアップロードすることにより、更新を利用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="816f6-127">You make the updates available by uploading them to the FAME App Repository.</span></span> <span data-ttu-id="816f6-128">新しいアプリのバージョンは、Business Central 管理センターの [アプリの管理] ページで利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="816f6-128">The new app versions will then be available on the Manage Apps page of the Business Central administration center.</span></span>
- <span data-ttu-id="816f6-129">アプリがインストールされている顧客の環境の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="816f6-129">Retrieve the list of the customers' environments that have your app installed.</span></span>
- <span data-ttu-id="816f6-130">顧客の環境に合わせてアプリの修正プログラムの自動展開をスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="816f6-130">Schedule the automatic deployment of the app hotfixes for their customers' environments.</span></span>

<span data-ttu-id="816f6-131">FAME API を使用すると、最新の継続的インテグレーション (CI)、継続的配置 (CD)、および DevOps のプラクティスを作業に適用できます。次に例を示します。</span><span class="sxs-lookup"><span data-stu-id="816f6-131">FAME API lets you apply modern continuous integration (CI), continuous deployment (CD), and DevOps practices to your work; for example:</span></span>

- <span data-ttu-id="816f6-132">Microsoft Azure DevOps Services またはその他の利用可能なプロセス自動化ツールを使用して操作を自動化します。</span><span class="sxs-lookup"><span data-stu-id="816f6-132">Automate operations by using Microsoft Azure DevOps Services or other available process automation tools.</span></span>
- <span data-ttu-id="816f6-133">ロールベースのアクセス制御を整理します。</span><span class="sxs-lookup"><span data-stu-id="816f6-133">Organize role-based access control.</span></span>
- <span data-ttu-id="816f6-134">高度で適切に管理されたビルド、テスト、リリースのフローによってサポートされるアプリを複数の地理的な場所で大規模に管理します。</span><span class="sxs-lookup"><span data-stu-id="816f6-134">Manage your apps at scale, in multiple geo locations, supported by advanced and well-controlled build, test, and release flows.</span></span>

<span data-ttu-id="816f6-135">Business Central 2020 年リリース ウェーブ 1 では、FAME API への直接アクセスを利用できるのは、埋め込みアプリを使用する ISV だけです。</span><span class="sxs-lookup"><span data-stu-id="816f6-135">In Business Central 2020 release wave 1, direct access to the FAME API is only available for the ISVs working with the Embed apps.</span></span> <span data-ttu-id="816f6-136">アドオンと Connect Apps では利用できません。</span><span class="sxs-lookup"><span data-stu-id="816f6-136">It isn't available for Add-on and Connect apps.</span></span> <span data-ttu-id="816f6-137">アドオンと Connect Apps を管理するには、パートナー センターを使用して、新しいアプリ バージョンを Business Central オファーにアップロードします。</span><span class="sxs-lookup"><span data-stu-id="816f6-137">To manage Add-on and Connect apps, you use Partner Center to upload the new app versions to Business Central offers.</span></span> <span data-ttu-id="816f6-138">次に、アプリは技術およびマーケティングの検証を受けてから、AppSource で使用可能になります。</span><span class="sxs-lookup"><span data-stu-id="816f6-138">The apps will then undergo a technical and marketing validation before becoming available on AppSource.</span></span> <span data-ttu-id="816f6-139">検証に合格すると、これらのアプリをインストールしている顧客が Business Central 管理センターで新しいバージョンを利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="816f6-139">After passing validation, the new versions are made available in Business Central administration center to the customers who have these apps installed.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="816f6-140">フィードバック</span><span class="sxs-lookup"><span data-stu-id="816f6-140">Tell us what you think</span></span>
<span data-ttu-id="816f6-141">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="816f6-141">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="816f6-142">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="816f6-142">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="816f6-143">関連項目</span><span class="sxs-lookup"><span data-stu-id="816f6-143">See also</span></span>

<!--docs start-->
<span data-ttu-id="816f6-144">[アプリ管理 API](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/appmanagement/app-management-api) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="816f6-144">[App Management API](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/appmanagement/app-management-api) (docs)</span></span>
<!--docs end-->
