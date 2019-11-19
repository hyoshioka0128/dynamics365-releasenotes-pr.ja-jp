---
title: Azure DevOps でホストされるビルド自動化
description: お客様とパートナーは、Azure DevOps によってホストされたビルド エージェントを使用して、Finance and Operations のカスタム コードのビルドを自動化できます。
author: relnotes
ms.reviewer: sericks
ms.date: 09/03/2019
ms.assetid: 3c9ec5ba-b0ca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: robadawy
dynamics365pdf: true
ms.openlocfilehash: a9a9ba01d8f44e0792a3d99a08b4288422d65eec
ms.sourcegitcommit: b5be4afdeec589f0490a82495e8206a2b3aee287
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2668128"
---
# <a name="build-automation-hosted-in-azure-devops"></a><span data-ttu-id="de95f-103">Azure DevOps でホストされるビルド自動化</span><span class="sxs-lookup"><span data-stu-id="de95f-103">Build automation hosted in Azure DevOps</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="de95f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="de95f-104">Enabled for</span></span>    |  <span data-ttu-id="de95f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="de95f-105">Public preview</span></span> | <span data-ttu-id="de95f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="de95f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="de95f-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="de95f-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="de95f-108">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="de95f-108">Jan 2020</span></span>| <span data-ttu-id="de95f-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="de95f-109">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="de95f-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="de95f-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="de95f-111">これにより、毎日のビルドの自動化を有効にするために、ビルドおよびテスト環境をデプロイする必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="de95f-111">This removes the need for deploying build and test environments to enable daily build automation.</span></span> <span data-ttu-id="de95f-112">Azure DevOps でホストされるビルドは、1 か月あたり最大で 1,800 分間無料です (現在)。</span><span class="sxs-lookup"><span data-stu-id="de95f-112">Builds hosted in Azure DevOps are free for up to 1,800 minutes per month (currently).</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="de95f-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="de95f-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="de95f-114">Finance and Operations のアプリケーション モデルとプラットフォーム バイナリの NuGet パッケージは、Lifecycle Services で利用できます。</span><span class="sxs-lookup"><span data-stu-id="de95f-114">NuGet packages of the Finance and Operations application models and platform binaries will be available in Lifecycle Services.</span></span> <span data-ttu-id="de95f-115">これらの NuGet パッケージを Azure DevOps プロジェクトにアップロードし、ビルド定義を作成します。</span><span class="sxs-lookup"><span data-stu-id="de95f-115">Upload these NuGet packages to your Azure DevOps project and create a build definition.</span></span> <span data-ttu-id="de95f-116">標準の Azure DevOps ビルド パイプライン機能を使用してコードを構築し、デプロイ可能なカスタム パッケージを作成します。</span><span class="sxs-lookup"><span data-stu-id="de95f-116">Use standard Azure DevOps build pipeline functionality to build your code and create custom deployable packages.</span></span> <span data-ttu-id="de95f-117">詳細については、機能の公開時に利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="de95f-117">More details will be available when the feature becomes public.</span></span>
<!--feature detail end -->









