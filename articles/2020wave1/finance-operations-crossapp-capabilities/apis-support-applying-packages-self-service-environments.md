---
title: セルフサービス環境へのパッケージの適用をサポートする API
description: 現在、以前のインフラストラクチャ アーキテクチャに展開された Tier 1-5 DevTest およびサンドボックスタイプの環境にパッケージを適用するための API が存在しますが、これらの API はセルフサービス インフラストラクチャ環境をサポートしていません。 この機能では、すべてのタイプの Tier 1-5 環境を有効にするサポートを追加します。
author: relnotes
ms.reviewer: sericks
ms.date: 04/02/2020
ms.assetid: 3c6f224b-8e74-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: adbae459eebfab370391d6241f206c0f2559309b
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219705"
---
# <a name="apis-to-support-applying-packages-for-self-service-environments"></a><span data-ttu-id="871e5-104">セルフサービス環境へのパッケージの適用をサポートする API</span><span class="sxs-lookup"><span data-stu-id="871e5-104">APIs to support applying packages for self-service environments</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="871e5-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="871e5-105">Enabled for</span></span>    |  <span data-ttu-id="871e5-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="871e5-106">Public preview</span></span> | <span data-ttu-id="871e5-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="871e5-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="871e5-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="871e5-108">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="871e5-109">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="871e5-109">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="871e5-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="871e5-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="871e5-111">顧客は現在 Azure DevOps タスクを夜間のビルド プロセスと CI/CD パイプラインに使用しています。</span><span class="sxs-lookup"><span data-stu-id="871e5-111">Customers currently use Azure DevOps tasks for their nightly build processes and CI/CD pipelines.</span></span> <span data-ttu-id="871e5-112">より多くの顧客をセルフサービス環境に移行すると、それらの顧客は DevOps タスクを使用できなくなります。</span><span class="sxs-lookup"><span data-stu-id="871e5-112">As we migrate more customers to self-service environments, those customers will no longer be able to use the DevOps tasks.</span></span> <span data-ttu-id="871e5-113">この機能により、セルフサービス環境のサポートが有効になり、CI/CD の観点からすべての種類の環境に均衡がもたらされます。</span><span class="sxs-lookup"><span data-stu-id="871e5-113">This feature will enable support for self-service environments to bring parity across all environment types from a CI/CD perspective.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="871e5-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="871e5-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="871e5-115">新しい Lifecycle Services (LCS) RESTful API を導入して、以前のインフラストラクチャ アーキテクチャ上にあるか、セルフサービス インフラストラクチャ上にあるかに関係なく、Tier 1-5 DevTest またはサンドボックスタイプの環境に Azure DevOps から直接アプリケーションをパッケージ化できるようにします。</span><span class="sxs-lookup"><span data-stu-id="871e5-115">We will introduce new Lifecycle Services (LCS) RESTful APIs to enable package application directly from Azure DevOps to any Tier 1-5 DevTest or sandbox-type environment, whether it is on the previous infrastructure architecture or on self-service infrastructure.</span></span>
<!--feature detail end -->









