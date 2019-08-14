---
title: 最新 POS 用の独立したパッケージ化
description: 最新 POS 用の独立したパッケージ化
author: mugunthanm
ms.reviewer: josaw
ms.date: 07/22/2019
ms.assetid: 6063278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 1eb2588db30c6bb0e44f03be7639016a7dd8dd49
ms.sourcegitcommit: 4101748c25acf79b22e31a01b73969500926ff91
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1793411"
---
# <a name="independent-packaging-for-modern-pos"></a><span data-ttu-id="cf25f-103">最新 POS 用の独立したパッケージ化</span><span class="sxs-lookup"><span data-stu-id="cf25f-103">Independent packaging for Modern POS</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="cf25f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cf25f-104">Enabled for</span></span>    |  <span data-ttu-id="cf25f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cf25f-105">Public preview</span></span> | <span data-ttu-id="cf25f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="cf25f-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="cf25f-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="cf25f-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="cf25f-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="cf25f-108">September 2019</span></span>| <span data-ttu-id="cf25f-109">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="cf25f-109">November 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="cf25f-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="cf25f-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="cf25f-111">現在の拡張機能パッケージ モデルでは、小売業者またはパートナーは常に、修正プログラムの適用またはアップグレードのために、コア製品でチャネル拡張機能を再パッケージ化する必要があります。</span><span class="sxs-lookup"><span data-stu-id="cf25f-111">With the current extension packaging model, retailers or partners always need to repackage the channel extension with the core product to apply a hotfix or to upgrade.</span></span> <span data-ttu-id="cf25f-112">再パッケージ化を行うたびにテストとビルドが必要となり、すべての修正プログラムに対して同じプロセスが何度も何度も発生するため、これには手間がかかります。</span><span class="sxs-lookup"><span data-stu-id="cf25f-112">This requires more effort because every time repackaging is done, test and build is required and for every hotfix, the same process happens again and again.</span></span> <span data-ttu-id="cf25f-113">再パッケージ化と検証が常に必要であり、これは開発者によってのみ実行できるので、これにより小売業者と Microsoft の両方が変更のロールアウトを制限されます。</span><span class="sxs-lookup"><span data-stu-id="cf25f-113">This limits both the retailer and Microsoft to roll out the changes because repackaging and validation is always required, and this can be done only by a developer.</span></span> <span data-ttu-id="cf25f-114">たとえば、Microsoft がいくつかの重要な修正プログラムや大きな機能拡張をロールアウトしたい場合、拡張機能を使用している小売業者は、開発者を手配してビルド、再パッケージ化、テストなどを行う必要があるため、簡単には対応できません。</span><span class="sxs-lookup"><span data-stu-id="cf25f-114">For example, if Microsoft wants to roll out some critical fixes or some major functional enhancement, the retailer who has extensions will not be able to easily uptake it because they have to involve a developer and then build, repackage, test, and so on.</span></span> <span data-ttu-id="cf25f-115">小売業者の多くの実装には、パートナーの拡張機能、ISV のソリューション、そして場合によっては社内カスタマイズが含まれます。この場合、修正プログラムを適用するには、すべての当事者が小売業者またはパートナーとコードを共有し、コア製品を含む 1 つの結合パッケージを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="cf25f-115">Many retail implementations will have partner extensions, ISV solutions, and in some cases in-house customizations—in this case, to apply any hotfix, all the parties need to share the code with the retailer or partner to create one combined package with the core product.</span></span> <span data-ttu-id="cf25f-116">新しい独立パッケージ拡張機能モデルにより、この問題が最小限に抑えられます。</span><span class="sxs-lookup"><span data-stu-id="cf25f-116">We are minimizing this problem with the new independent package extension model.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="cf25f-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cf25f-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cf25f-118">独立パッケージ化モデルと呼ばれる新しい機能が開発されています。これは、コアから拡張機能を分離し、独立してサービスを提供するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="cf25f-118">We are developing a new feature called independent packaging model, which helps to separate extensions from the core and provide service independently.</span></span> <span data-ttu-id="cf25f-119">また、将来的には、拡張機能ごとの個別パッケージもサポートする予定です。</span><span class="sxs-lookup"><span data-stu-id="cf25f-119">We will also support separate packages by extensions in the future.</span></span> <span data-ttu-id="cf25f-120">最新の販売時点管理 (MPOS) でこの新しいパッケージ化モデルをサポートするため、Windows のオプションのパッケージ拡張機能モデル、デスクトップ ブリッジ、および MSIX をサポートするように POS フレームワークを変更しています。</span><span class="sxs-lookup"><span data-stu-id="cf25f-120">For Modern point of sale (MPOS) to support this new packaging model, we are changing the POS framework to support Windows optional package extension model, Desktop Bridge, and MSIX.</span></span> <span data-ttu-id="cf25f-121">拡張機能の開発方法には多少の変更がありますが、変更は主に拡張機能テンプレート、パッケージ化、および展開において行われます。</span><span class="sxs-lookup"><span data-stu-id="cf25f-121">There will be some change to how extensions are developed, but changes will be done mostly in the extension template, packaging, and deployment.</span></span> 

<span data-ttu-id="cf25f-122">この新しいモデルでは、すべての MPOS 拡張機能は別の appx ファイルとして作成され、コア POS はこれらの appx ファイルをアドインとして読み込み、コア MPOS アプリ ID の下で実行します。</span><span class="sxs-lookup"><span data-stu-id="cf25f-122">With this new model, all MPOS extensions will be created as separate appx files and core POS will load these appx files as add-ins and will run under the core MPOS app identity.</span></span> <span data-ttu-id="cf25f-123">以前は、コア POS と拡張機能は 1 つの appx としてパッケージ化されていましたが、開発者が独自に拡張機能 appx を処理できるように、コア appx と拡張機能アドインになる予定です。</span><span class="sxs-lookup"><span data-stu-id="cf25f-123">Previously, the core POS and extensions were packaged as one appx, but now there will be core appx and extension add-ins appx so that developers can independently service their extension appx.</span></span> <span data-ttu-id="cf25f-124">拡張機能 appx シナリオをサポートするためのテンプレート ファイルが出荷されます。</span><span class="sxs-lookup"><span data-stu-id="cf25f-124">We will ship template files to support the extension appx scenarios.</span></span> <span data-ttu-id="cf25f-125">開発された拡張機能は、クラウド POS と MPOS の両方で機能します。</span><span class="sxs-lookup"><span data-stu-id="cf25f-125">The extensions developed will work for both Cloud POS and MPOS.</span></span> <span data-ttu-id="cf25f-126">テンプレートは異なる場合がありますが、コードは両方で共有されます。</span><span class="sxs-lookup"><span data-stu-id="cf25f-126">The template may be different, but the code is shared between both.</span></span>
<!--feature detail end -->











