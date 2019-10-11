---
title: Azure DevOps でホストされるビルド自動化
description: お客様とパートナーは、Azure DevOps によってホストされたビルド エージェントを使用して、Finance and Operations のカスタム コードのビルドを自動化できます。
author: relnotes
ms.reviewer: rhaertle
ms.date: 09/03/2019
ms.assetid: 3c9ec5ba-b0ca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: robadawy
dynamics365pdf: true
ms.openlocfilehash: 9aabb8d32b8e13d81648f8587f60fd9c57187509
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143276"
---
# <a name="build-automation-hosted-in-azure-devops"></a><span data-ttu-id="89f35-103">Azure DevOps でホストされるビルド自動化</span><span class="sxs-lookup"><span data-stu-id="89f35-103">Build automation hosted in Azure DevOps</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="89f35-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="89f35-104">Enabled for</span></span>    |  <span data-ttu-id="89f35-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="89f35-105">Public preview</span></span> | <span data-ttu-id="89f35-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="89f35-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="89f35-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="89f35-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="89f35-108">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="89f35-108">Jan 2020</span></span>| <span data-ttu-id="89f35-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="89f35-109">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="89f35-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="89f35-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="89f35-111">これにより、毎日のビルドの自動化を有効にするために、ビルドおよびテスト環境をデプロイする必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="89f35-111">This removes the need for deploying build and test environments to enable daily build automation.</span></span> <span data-ttu-id="89f35-112">Azure DevOps でホストされるビルドは、1 か月あたり最大で 1,800 分間無料です (現在)。</span><span class="sxs-lookup"><span data-stu-id="89f35-112">Builds hosted in Azure DevOps are free for up to 1,800 minutes per month (currently).</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="89f35-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="89f35-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="89f35-114">Finance and Operations のアプリケーション モデルとプラットフォーム バイナリの NuGet パッケージは、Lifecycle Services で利用できます。</span><span class="sxs-lookup"><span data-stu-id="89f35-114">NuGet packages of the Finance and Operations application models and platform binaries will be available in Lifecycle Services.</span></span> <span data-ttu-id="89f35-115">これらの NuGet パッケージを Azure DevOps プロジェクトにアップロードし、ビルド定義を作成します。</span><span class="sxs-lookup"><span data-stu-id="89f35-115">Upload these NuGet packages to your Azure DevOps project and create a build definition.</span></span> <span data-ttu-id="89f35-116">標準の Azure DevOps ビルド パイプライン機能を使用してコードを構築し、デプロイ可能なカスタム パッケージを作成します。</span><span class="sxs-lookup"><span data-stu-id="89f35-116">Use standard Azure DevOps build pipeline functionality to build your code and create custom deployable packages.</span></span> <span data-ttu-id="89f35-117">詳細については、機能の公開時に利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="89f35-117">More details will be available when the feature becomes public.</span></span>
<!--feature detail end -->











