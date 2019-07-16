---
title: POS および本社の拡張機能
description: POS および本社の拡張機能
author: mugunthanm
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 5e63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: f995664f8fa82affe723a94177c0b500ca46fa00
ms.sourcegitcommit: 4620697dc1f4fc6903504a55406f3d22af75e361
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1694135"
---
# <a name="pos-and-headquarters-extensions"></a><span data-ttu-id="19876-103">POS および本社の拡張機能</span><span class="sxs-lookup"><span data-stu-id="19876-103">POS and Headquarters extensions</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="19876-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="19876-104">Enabled for</span></span>    |  <span data-ttu-id="19876-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="19876-105">Public preview</span></span> | <span data-ttu-id="19876-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="19876-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="19876-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="19876-107">Admins, makers, or analysts, automatically</span></span>|| <span data-ttu-id="19876-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="19876-108">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="19876-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="19876-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="19876-110">ほぼすべての小売業者が、ビジネス目標を達成するために、Dynamics 365 for Retail を拡張して、既存のビジネス ロジックを変更したり、製品に新しい機能を追加したりする、必要性または選択肢を持っています。</span><span class="sxs-lookup"><span data-stu-id="19876-110">Nearly all retailers have the need or choose to extend Dynamics 365 for Retail to modify the existing business logic or add some new feature to the product to meet their business goals.</span></span> <span data-ttu-id="19876-111">販売時点管理 (POS)、Commerce Runtime (CRT)、および本社 (HQ) では、カスタム ビジネス シナリオをサポートするための拡張ポイントを追加しています。</span><span class="sxs-lookup"><span data-stu-id="19876-111">In the point of sale (POS), commerce runtime (CRT), and Headquarters (HQ) we are adding more extension points to support custom business scenarios.</span></span> <span data-ttu-id="19876-112">この機能の目標は、拡張シナリオをサポートするために製品に必要なコア拡張ポイントを追加することです。</span><span class="sxs-lookup"><span data-stu-id="19876-112">The goal of this feature is to add the necessary core extension points in the product to support extension scenarios.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="19876-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="19876-113">Feature details</span></span>
<!--feature detail start -->
### <a name="framework-enhancements"></a><span data-ttu-id="19876-114">フレームワークの機能強化</span><span class="sxs-lookup"><span data-stu-id="19876-114">Framework enhancements</span></span>
<span data-ttu-id="19876-115">バイナリ ベースの拡張モデルに移行した後、簡単にロジックを使用およびオーバーライドできるように、すべてのコア POS ロジックとユーザー インターフェイス (UI) コントロールをラップし、SDK (API) として公開しています。</span><span class="sxs-lookup"><span data-stu-id="19876-115">After moving toward the binary based extension model, we are wrapping and exposing all our core POS logic and user interface (UI) controls as SDK (APIs) to help the extension to easily consume and override our logic.</span></span> <span data-ttu-id="19876-116">これらの API がないと、拡張機能でカスタム ロジックを記述するのは困難です。</span><span class="sxs-lookup"><span data-stu-id="19876-116">Without these APIs it will be difficult for the extension to write some custom logic.</span></span> <span data-ttu-id="19876-117">場合によっては、拡張機能で既存のコードの一部を書き換えたり、単純なシナリオを実行するには多すぎるコード行を書いたりする必要があります。</span><span class="sxs-lookup"><span data-stu-id="19876-117">In some cases, the extension has to rewrite some of the existing code or write too many lines of code to do a simple scenario.</span></span> <span data-ttu-id="19876-118">これを回避し、コード行数を減らすために、より高度な API と構成主導の開発を導入して、開発プロセス全体を簡素化しています。</span><span class="sxs-lookup"><span data-stu-id="19876-118">To avoid this and to reduce the number of lines of code, we’re introducing more advanced APIs and configuration-driven development to simplify the overall development process.</span></span>    

### <a name="pos-ui-and-api-extension"></a><span data-ttu-id="19876-119">POS UI と API 拡張機能</span><span class="sxs-lookup"><span data-stu-id="19876-119">POS UI and API extension</span></span>
<span data-ttu-id="19876-120">POS フレームワークを継続的に拡張し、拡張機能でロジックを使用するための POS API と、コア POS ビューにカスタム列、アプリ バー ボタン、カスタム コントロールを追加するための UI 拡張ポイントを追加しています。</span><span class="sxs-lookup"><span data-stu-id="19876-120">We are continuously enhancing the POS framework to add more POS APIs to consume our logic in extension and UI extension points to add custom columns, app bar buttons, and custom controls in core POS views.</span></span>

### <a name="pos-overridable-requests-and-triggers"></a><span data-ttu-id="19876-121">POS オーバーライド可能な要求とトリガー</span><span class="sxs-lookup"><span data-stu-id="19876-121">POS overridable requests and triggers</span></span>
<span data-ttu-id="19876-122">POS ワークフローまたは POS ビジネス ロジックをオーバーライドし、カスタム ロジックまたは検証を追加するために、新しいオーバーライド可能な要求が POS に追加されています。</span><span class="sxs-lookup"><span data-stu-id="19876-122">New overridable requests are added in POS to override the POS workflow or POS business logic and to add custom logic or validation.</span></span> <span data-ttu-id="19876-123">POS トリガー フレームワークは、コア POS ロジックの前後でカスタム ロジックを実行するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="19876-123">POS trigger framework helps you to run custom logic before or after core POS logic.</span></span> <span data-ttu-id="19876-124">この新しいパターンにより、開発者は POS のワークフローを簡単にカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="19876-124">With this new pattern, developers can easily customize any workflow in POS.</span></span>

### <a name="dev-infrastructure-and-tools-improvements"></a><span data-ttu-id="19876-125">開発インフラストラクチャとツールの改善</span><span class="sxs-lookup"><span data-stu-id="19876-125">Dev infrastructure and tools improvements</span></span>

<span data-ttu-id="19876-126">**NuGet への参照**: Commerce Runtime を含む Retail SDK 参照および Retail サーバー参照が、拡張機能で使用するために Retail SDK に同梱されていますが、現在は、拡張プロジェクトで簡単に参照を使用できるよう、NuGet パッケージ マネージャーにすべての参照を公開することが計画されています。</span><span class="sxs-lookup"><span data-stu-id="19876-126">**Reference to NuGet**: Retail SDK references, including commerce runtime and Retail server references, are shipped in the Retail SDK for extensions to consume, but now we are planning to publish all the reference to NuGet package manager for the extension project to easily consume our references.</span></span> <span data-ttu-id="19876-127">このアプローチを使用すると、拡張プロジェクトでは、Lifecycle Services (LCS) 更新フローを経由するのではなく、数回クリックするだけで参照ライブラリの最新の更新を取得できます。</span><span class="sxs-lookup"><span data-stu-id="19876-127">With this approach, the extension project can get the latest updates for the reference library with a few clicks instead of going through the Lifecycle Services (LCS) update flow.</span></span>

<span data-ttu-id="19876-128">**GitHub へのサンプル**: 現在、Retail 拡張機能の開発サンプルはすべて SDK に含まれていますが、すべてのサンプルを GitHub に移動することが計画されています。</span><span class="sxs-lookup"><span data-stu-id="19876-128">**Samples to GitHub**: Currently all the development samples for Retail extensions are included in the SDK but we are planning to move all the samples to GitHub.</span></span> <span data-ttu-id="19876-129">それにより、簡単に使用および更新できるようになります。</span><span class="sxs-lookup"><span data-stu-id="19876-129">That way they can be easily consumed and updated.</span></span>

<span data-ttu-id="19876-130">**Commerce Runtime アナライザー**: Commerce Runtime アナライザー ツールは、POS の操作またはワークフロー用に CRT で使用されている要求と応答を特定するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="19876-130">**Commerce runtime analyzer**: The commerce runtime analyzer tool helps to identify which request and response is used in CRT for any POS operation or workflow.</span></span> <span data-ttu-id="19876-131">たとえば、開発者が CRT で正しい要求を変更するのに必要な追加情報を取得するために検索ワークフローをカスタマイズしたい場合、このツールはそのシナリオで使用されている正確な要求を識別するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="19876-131">For example, if a developer wants to customize a search workflow to get some additional information needed to modify the right request in CRT, this tool helps to identify the exact request used in that scenario.</span></span>  

<span data-ttu-id="19876-132">**コード サンプルとドキュメント**: あらゆる開発シナリオに役立つように、多くの新しいコード サンプルとドキュメントが公開されます。</span><span class="sxs-lookup"><span data-stu-id="19876-132">**Code samples and documentation**: Many new code samples and documentation will be published to help with any development scenarios.</span></span> <span data-ttu-id="19876-133">これらの新しいサンプルを使用すると、開発者は実質的に、コードをコピーして貼り付け、いくつか変更を行うだけで、拡張機能を完成させることができます。</span><span class="sxs-lookup"><span data-stu-id="19876-133">With these new samples, developers can virtually copy and paste the code, and only make a few changes to complete their extensions.</span></span>
<!--feature detail end -->










