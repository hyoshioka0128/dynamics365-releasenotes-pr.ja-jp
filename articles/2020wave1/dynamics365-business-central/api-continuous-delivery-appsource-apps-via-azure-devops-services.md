---
title: Azure DevOps サービスを介した AppSourceアプリの継続的な配信のための API
description: パートナーを有効にし、Dynamics 365 Business Central アプリを構築して、顧客へのアプリの継続的な配信を実装し、Business Central online サービスで実行します。 パートナーは新しい API と Azure DevOps サービスを使用して、アプリを管理し、リリースのステップを調整します。
author: relnotes
ms.reviewer: solsen
ms.date: 12/16/2019
ms.assetid: 3d625248-2ccb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: dmitrych
dynamics365pdf: true
ms.openlocfilehash: 23a735d28ae5a56fcec3b55403f982d98b59feb4
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986834"
---
# <a name="api-for-continuous-delivery-of-the-appsource-apps-via-azure-devops-services"></a><span data-ttu-id="99504-104">Azure DevOps サービスを介した AppSourceアプリの継続的な配信のための API</span><span class="sxs-lookup"><span data-stu-id="99504-104">API for continuous delivery of the AppSource apps via Azure DevOps services</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="99504-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="99504-105">Enabled for</span></span>    |  <span data-ttu-id="99504-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="99504-106">Public preview</span></span> | <span data-ttu-id="99504-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="99504-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="99504-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="99504-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="99504-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="99504-109">Apr 2020</span></span>| <span data-ttu-id="99504-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="99504-110">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="99504-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="99504-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="99504-112">Business Central のパートナーは、Azure DevOps を使用して、ビルド プロセスと Business Central online へのデプロイを調整できます。</span><span class="sxs-lookup"><span data-stu-id="99504-112">Partners of Business Central can use Azure DevOps to orchestrate their build processes and deployments to Business Central online.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="99504-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="99504-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="99504-114">一般的なグローバル パートナー コミュニティと特に Business Central パートナー コミュニティでは、継続的な統合/継続的な配信と DevOps の原則に対する熱意が高まっています。</span><span class="sxs-lookup"><span data-stu-id="99504-114">The global partner community in general and Business Central partner community in particular are growing passion for the continuous integration/continuous delivery and DevOps principles.</span></span>

<span data-ttu-id="99504-115">Azure DevOps サービスでは継続的な統合のプラクティスに従ってコードを管理するための豊富な機能が Business Central 開発者に既に提供されています。</span><span class="sxs-lookup"><span data-stu-id="99504-115">Azure DevOps services already provide a wealth of functionality for Business Central developers to manage their code following continuous integration practice.</span></span> <span data-ttu-id="99504-116">コードは Visual Studio コードで記述され、ソース管理リポジトリに保存されて、レビュー、分岐、およびマージされます。その後、ビルド パイプラインを使用してビルドおよびテストされ、Business Central Docker コンテナーにターゲットが設定されます。</span><span class="sxs-lookup"><span data-stu-id="99504-116">The code is written in Visual Studio Code; stored, reviewed, branched, and merged in a source control repository; then built and tested using build pipelines, targeting Business Central Docker containers.</span></span>

<span data-ttu-id="99504-117">次のステップは、パートナーを有効にし、Dynamics 365 Business Central アプリを構築して、顧客へのアプリの継続的な配信を実装し、Business Central online サービスで実行することです。</span><span class="sxs-lookup"><span data-stu-id="99504-117">The next step is to enable partners building Dynamics 365 Business Central apps to implement continuous delivery of their apps to the customers, running in the Business Central online service.</span></span> 

<span data-ttu-id="99504-118">パートナーは新しい API (FAME の固定アプリ管理エンドポイント) と Azure DevOps サービスを使用してアプリを管理し、リリースのステップ (リリース パイプライン) を調整します。</span><span class="sxs-lookup"><span data-stu-id="99504-118">The partners will use a new API (fixed app management endpoint, of FAME) and Azure DevOps services to manage their apps and orchestrate the steps of the release (release pipeline).</span></span>

<span data-ttu-id="99504-119">Business Central 2020 年リリース ウェーブ 1 では、次のフローが有効になる予定です: パートナーは Docker コンテナーでテストされ、自動化された AppSource 検証チェックに合格し、通常どおり、Microsoft パートナー センター ポータルを介して本番対応のアプリが AppSource 自動検証および追加の手動検証に送信されます。</span><span class="sxs-lookup"><span data-stu-id="99504-119">We expect the following flow to be enabled for the Business Central 2020 release wave 1: Once a partner app has been tested in a Docker container and has passed automated AppSource validation checks, the production-ready app will be submitted for the AppSource automatic and additional manual validation via the Microsoft Partner Center portal as usual.</span></span> <span data-ttu-id="99504-120">アプリが承認されると、ISV は、以前のバージョンの ISV アプリを使用して、複数の国にわたるすべての顧客へのアプリの段階的な展開に進みます。</span><span class="sxs-lookup"><span data-stu-id="99504-120">When the app is approved, the ISV will proceed with a phased rollout of the app to all of their customers, using the previous version of the ISV app, across multiple countries.</span></span> 

<span data-ttu-id="99504-121">お客様は、[拡張機能管理] ページでパートナー アプリの新しいバージョンにアップグレードできるようになります。これにより、お客様は適切と思われるときにインストールまたはアップグレードできます。</span><span class="sxs-lookup"><span data-stu-id="99504-121">New versions of the partner apps will be made available to the customers to upgrade to on the Extension Management page, so that customers can install or upgrade to those when they see fit.</span></span> 

<span data-ttu-id="99504-122">Business Central 2020 年リリース ウェーブ 1 では、API の最初のバージョンが AppSource ISVs の限定的な対象ユーザーに対してプライベート プレビューとして利用可能になり、すべての Business Central AppSource ISVs がその後すぐに展開される予定です。</span><span class="sxs-lookup"><span data-stu-id="99504-122">With Business Central 2020 release wave 1, the first version of the API will be made available as a private preview to a limited audience of our AppSource ISVs with a plan to roll out to all Business Central AppSource ISVs soon after that.</span></span>

<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="99504-123">フィードバック</span><span class="sxs-lookup"><span data-stu-id="99504-123">Tell us what you think</span></span>
<span data-ttu-id="99504-124">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="99504-124">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="99504-125">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="99504-125">Use the forum at https://aka.ms/bcideas.</span></span>



