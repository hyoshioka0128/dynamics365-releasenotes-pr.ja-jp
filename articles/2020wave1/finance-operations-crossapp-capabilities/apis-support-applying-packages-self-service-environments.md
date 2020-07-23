---
title: セルフサービス環境へのパッケージの適用をサポートする API
description: 現在、以前のインフラストラクチャ アーキテクチャに展開された Tier 1-5 DevTest およびサンドボックスタイプの環境にパッケージを適用するための API が存在しますが、これらの API はセルフサービス インフラストラクチャ環境をサポートしていません。 この機能では、すべてのタイプの Tier 1-5 環境を有効にするサポートを追加します。
author: relnotes
ms.reviewer: sericks
ms.date: 06/04/2020
ms.assetid: 3c6f224b-8e74-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: 799b8f8977452c450741681da5c641c0fc9e1d53
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3440767"
---
# <a name="apis-to-support-applying-packages-for-self-service-environments"></a><span data-ttu-id="0e91f-104">セルフサービス環境へのパッケージの適用をサポートする API</span><span class="sxs-lookup"><span data-stu-id="0e91f-104">APIs to support applying packages for self-service environments</span></span>


| <span data-ttu-id="0e91f-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="0e91f-105">Enabled for</span></span>    |  <span data-ttu-id="0e91f-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0e91f-106">Public preview</span></span> | <span data-ttu-id="0e91f-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="0e91f-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0e91f-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="0e91f-108">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="0e91f-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0e91f-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0e91f-110">2020 年 5 月 30 日</span><span class="sxs-lookup"><span data-stu-id="0e91f-110">May 30, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="0e91f-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0e91f-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0e91f-112">顧客は現在 Azure DevOps タスクを夜間のビルド プロセスと CI/CD パイプラインに使用しています。</span><span class="sxs-lookup"><span data-stu-id="0e91f-112">Customers currently use Azure DevOps tasks for their nightly build processes and CI/CD pipelines.</span></span> <span data-ttu-id="0e91f-113">より多くの顧客をセルフサービス環境に移行すると、それらの顧客は DevOps タスクを使用できなくなります。</span><span class="sxs-lookup"><span data-stu-id="0e91f-113">As we migrate more customers to self-service environments, those customers will no longer be able to use the DevOps tasks.</span></span> <span data-ttu-id="0e91f-114">この機能により、セルフサービス環境のサポートが有効になり、CI/CD の観点からすべての種類の環境に均衡がもたらされます。</span><span class="sxs-lookup"><span data-stu-id="0e91f-114">This feature will enable support for self-service environments to bring parity across all environment types from a CI/CD perspective.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0e91f-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0e91f-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0e91f-116">新しい Lifecycle Services (LCS) RESTful API を導入して、以前のインフラストラクチャ アーキテクチャ上にあるか、セルフサービス インフラストラクチャ上にあるかに関係なく、Tier 1-5 DevTest またはサンドボックスタイプの環境に Azure DevOps から直接アプリケーションをパッケージ化できるようにします。</span><span class="sxs-lookup"><span data-stu-id="0e91f-116">We will introduce new Lifecycle Services (LCS) RESTful APIs to enable package application directly from Azure DevOps to any Tier 1-5 DevTest or sandbox-type environment, whether it is on the previous infrastructure architecture or on self-service infrastructure.</span></span>
<!--feature detail end -->









