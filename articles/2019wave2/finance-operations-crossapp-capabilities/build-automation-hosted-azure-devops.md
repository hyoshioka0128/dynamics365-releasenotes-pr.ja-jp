---
title: Azure DevOps でホストされるビルド自動化
description: お客様とパートナーは、Azure DevOps によってホストされたビルド エージェントを使用して、Finance and Operations のカスタム コードのビルドを自動化できます。
author: relnotes
ms.reviewer: rhaertle
ms.date: 03/18/2020
ms.assetid: 3c9ec5ba-b0ca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: jorisde
dynamics365pdf: true
ms.openlocfilehash: 22a8b550b43266242013ae4d42df886e04c1cd3a
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178760"
---
# <a name="build-automation-hosted-in-azure-devops"></a><span data-ttu-id="3d428-103">Azure DevOps でホストされるビルド自動化</span><span class="sxs-lookup"><span data-stu-id="3d428-103">Build automation hosted in Azure DevOps</span></span>


| <span data-ttu-id="3d428-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3d428-104">Enabled for</span></span>    |  <span data-ttu-id="3d428-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3d428-105">Public preview</span></span> | <span data-ttu-id="3d428-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="3d428-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3d428-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="3d428-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="3d428-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3d428-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3d428-109">2020 年 1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="3d428-109">Jan 3, 2020</span></span>| <span data-ttu-id="3d428-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3d428-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3d428-111">2020 年 2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="3d428-111">Feb 28, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3d428-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3d428-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3d428-113">これにより、毎日のビルドの自動化を有効にするために、ビルドおよびテスト環境をデプロイする必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="3d428-113">This removes the need for deploying build and test environments to enable daily build automation.</span></span> <span data-ttu-id="3d428-114">Azure DevOps でホストされるビルドは、1 か月あたり最大で 1,800 分間無料です (現在)。</span><span class="sxs-lookup"><span data-stu-id="3d428-114">Builds hosted in Azure DevOps are free for up to 1,800 minutes per month (currently).</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3d428-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3d428-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3d428-116">Finance and Operations のアプリケーション モデルとプラットフォーム バイナリの NuGet パッケージは、Lifecycle Services で利用できます。</span><span class="sxs-lookup"><span data-stu-id="3d428-116">NuGet packages of the Finance and Operations application models and platform binaries will be available in Lifecycle Services.</span></span> <span data-ttu-id="3d428-117">これらの NuGet パッケージを Azure DevOps プロジェクトにアップロードし、ビルド定義を作成します。</span><span class="sxs-lookup"><span data-stu-id="3d428-117">Upload these NuGet packages to your Azure DevOps project and create a build definition.</span></span> <span data-ttu-id="3d428-118">標準の Azure DevOps ビルド パイプライン機能を使用してコードを構築し、デプロイ可能なカスタム パッケージを作成します。</span><span class="sxs-lookup"><span data-stu-id="3d428-118">Use standard Azure DevOps build pipeline functionality to build your code and create custom deployable packages.</span></span> <span data-ttu-id="3d428-119">詳細については、機能の公開時に利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="3d428-119">More details will be available when the feature becomes public.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="3d428-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="3d428-120">See also</span></span>

<span data-ttu-id="3d428-121">[開発とカスタマイズに関するインサイダー向けのヒント](https://community.dynamics.com/365/financeandoperations/b/newdynamicsax) (ブログ)</span><span class="sxs-lookup"><span data-stu-id="3d428-121">[Insider tips on development and customization](https://community.dynamics.com/365/financeandoperations/b/newdynamicsax) (blog)</span></span>
