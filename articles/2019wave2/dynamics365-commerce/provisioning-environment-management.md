---
title: プロビジョニングと環境管理
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 02/11/2020
ms.assetid: b263278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: brshoo
dynamics365pdf: true
ms.openlocfilehash: 9dc784afa0070fdf7cc03f599d778e8ebe0851d1
ms.sourcegitcommit: bfe05af05f11f2c318a77bb3138c3df0796c7187
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/27/2020
ms.locfileid: "3088781"
---
# <a name="provisioning-and-environment-management"></a><span data-ttu-id="51e3c-102">プロビジョニングと環境管理</span><span class="sxs-lookup"><span data-stu-id="51e3c-102">Provisioning and environment management</span></span>


| <span data-ttu-id="51e3c-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="51e3c-103">Enabled for</span></span>    |  <span data-ttu-id="51e3c-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="51e3c-104">Public preview</span></span> | <span data-ttu-id="51e3c-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="51e3c-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="51e3c-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="51e3c-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="51e3c-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="51e3c-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="51e3c-108">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="51e3c-108">Oct 1, 2019</span></span>| <span data-ttu-id="51e3c-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="51e3c-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="51e3c-110">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="51e3c-110">Feb 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="51e3c-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="51e3c-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="51e3c-112">IT エンジニアまたはシステム インテグレーター (SI) には、eコマース機能セットを有効にしてプロビジョニングする方法が必要です。</span><span class="sxs-lookup"><span data-stu-id="51e3c-112">IT engineers or system integrators (SIs) need a way to enable and provision the e-commerce feature set.</span></span> <span data-ttu-id="51e3c-113">プロビジョニング機能により、IT エンジニアと SI は Dynamics Lifecycle Services (LCS) でこの作業を完了し、完全に機能する CMS、編集、レンダリング環境をプロビジョニングできます。</span><span class="sxs-lookup"><span data-stu-id="51e3c-113">The provisioning feature will allow IT engineers and SIs to complete this work in Dynamics Lifecycle Services (LCS) and provision a fully functional CMS, editing, and rendering environment.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="51e3c-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="51e3c-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="51e3c-115">現在のペースの速いビジネス環境では、市場投入までの時間と、刻々と変化する市場に迅速に対応する能力が重要です。</span><span class="sxs-lookup"><span data-stu-id="51e3c-115">In today’s fast-paced business environment, the time to market and the ability to react quickly to an ever-changing marketplace are essential.</span></span> <span data-ttu-id="51e3c-116">これらの企業と連携する管理者は、環境を自由にプロビジョニングおよびデコミッションできる必要があります。</span><span class="sxs-lookup"><span data-stu-id="51e3c-116">Administrators working with these companies need the ability to provision and decommission environments at will.</span></span> <span data-ttu-id="51e3c-117">Dynamics 365 Commerce は Dynamics 365 Lifecycle Services (LCS) ポータルとシームレスに統合されます。</span><span class="sxs-lookup"><span data-stu-id="51e3c-117">Dynamics 365 Commerce will have seamless integration with the Dynamics 365 Lifecycle Services (LCS) portal.</span></span> <span data-ttu-id="51e3c-118">これにより、小売業者の管理者は、新しい eコマース環境をオンデマンドでプロビジョニングできるようになります。これは、自動化されたプロビジョニング サービスを通じて行われます。</span><span class="sxs-lookup"><span data-stu-id="51e3c-118">With this, administrators for a retailer will be able to provision a new e-commerce environment on demand that will be completed through the automated provisioning services.</span></span> <span data-ttu-id="51e3c-119">プロビジョニングが完了すると、管理者はカスタマイズを管理し、さまざまな環境に展開できるようになります。</span><span class="sxs-lookup"><span data-stu-id="51e3c-119">Once provisioned, the administrator will be able to manage and deploy customizations to the different environments.</span></span> 

<span data-ttu-id="51e3c-120">環境のプロビジョニングと管理に対するこの自動化されたアプローチは、小売業者にとって大幅なコスト削減になります。これによって、新しい環境を稼働させる時間を短縮し、環境を維持するために必要な人員を削減できるからです。</span><span class="sxs-lookup"><span data-stu-id="51e3c-120">This automated approach to environment provisioning and management will represent significant cost savings to a retailer because it means reduced time to have a new environment up and running, which reduces the personnel necessary to maintain the environments.</span></span> <span data-ttu-id="51e3c-121">開発作業と運用作業を安全に分離するために、さまざまな環境をプロビジョニングできます。</span><span class="sxs-lookup"><span data-stu-id="51e3c-121">Different environments can be provisioned to separate development and production efforts safely.</span></span> <span data-ttu-id="51e3c-122">エンジニアは LCS に移動して、サンドボックス環境または運用環境をデプロイできます。</span><span class="sxs-lookup"><span data-stu-id="51e3c-122">Engineers can navigate to LCS to deploy a Sandbox environment or Production environment.</span></span> <span data-ttu-id="51e3c-123">各環境タイプは別々の Azure データ クラスターによって完全に分離されているため、一方の作業中に他方に影響を与えるリスクはありません。</span><span class="sxs-lookup"><span data-stu-id="51e3c-123">Each environment type is completely separated by different Azure data clusters, ensuring there is no risk of affecting the other while working on one.</span></span> <span data-ttu-id="51e3c-124">開発、テスト、レビューをサンドボックスで行います。</span><span class="sxs-lookup"><span data-stu-id="51e3c-124">Develop, test, and review in Sandbox.</span></span> <span data-ttu-id="51e3c-125">準備ができたら、エンジニアはサンドボックスの Commerce コンテンツを運用環境にレベル上げできます。</span><span class="sxs-lookup"><span data-stu-id="51e3c-125">When ready, engineers can promote their Sandbox Commerce content to a Production environment.</span></span> <span data-ttu-id="51e3c-126">これにより、テスト済みの、完全に機能するコンテンツを顧客に提供するための安全な展開プロセスが可能になります。</span><span class="sxs-lookup"><span data-stu-id="51e3c-126">This allows for a safe-deployment process to provide customers tested, fully functioning content.</span></span> 

<span data-ttu-id="51e3c-127">また、Dynamics 365 Commerce では、エンジニアは現実世界の環境で Microsoft のオファリングを探索するための評価環境をプロビジョニングできます。</span><span class="sxs-lookup"><span data-stu-id="51e3c-127">Dynamics 365 Commerce also offers engineers the ability to provision an Evaluation environment to explore our offering in a real-world environment.</span></span> <span data-ttu-id="51e3c-128">評価環境を使用して製品オファリングのすべての機能を調べ、テストし、理解することができます。</span><span class="sxs-lookup"><span data-stu-id="51e3c-128">Use the Evaluation environment to examine, test, and understand all abilities of the product offering.</span></span>

<span data-ttu-id="51e3c-129">![環境のプロビジョニング](media/environment_provisioning.png "環境のプロビジョニング")</span><span class="sxs-lookup"><span data-stu-id="51e3c-129">![Environment provisioning](media/environment_provisioning.png "Environment provisioning")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="51e3c-130">関連項目</span><span class="sxs-lookup"><span data-stu-id="51e3c-130">See also</span></span>

<span data-ttu-id="51e3c-131">[Dynamics 365 Commerce プレビュー環境のプロビジョニング](https://docs.microsoft.com/dynamics365/commerce/provisioning-guide) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="51e3c-131">[Provision a Dynamics 365 Commerce preview environment](https://docs.microsoft.com/dynamics365/commerce/provisioning-guide) (docs)</span></span>
