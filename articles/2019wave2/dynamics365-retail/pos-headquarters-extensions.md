---
title: POS および本社の拡張機能
description: POS および本社の拡張機能
author: mugunthanm
ms.reviewer: josaw
ms.date: 11/15/2019
ms.assetid: 5e63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 52ffa75eec4afc9f503aa3be754e8623321761da
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2890005"
---
# <a name="pos-and-headquarters-extensions"></a><span data-ttu-id="2ff2b-103">POS および本社の拡張機能</span><span class="sxs-lookup"><span data-stu-id="2ff2b-103">POS and headquarters extensions</span></span>


| <span data-ttu-id="2ff2b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="2ff2b-104">Enabled for</span></span>    |  <span data-ttu-id="2ff2b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2ff2b-105">Public preview</span></span> | <span data-ttu-id="2ff2b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="2ff2b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="2ff2b-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="2ff2b-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="2ff2b-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2ff2b-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2ff2b-109">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="2ff2b-109">Aug 2, 2019</span></span>| <span data-ttu-id="2ff2b-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2ff2b-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2ff2b-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2ff2b-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="2ff2b-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2ff2b-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="2ff2b-113">多くの小売業者が、ビジネス目標を達成するために、Dynamics 365 Retail を拡張して、既存のビジネス ロジックを変更したり、製品に新しい機能を追加したりすることを必要とするか選択しています。</span><span class="sxs-lookup"><span data-stu-id="2ff2b-113">Many retailers need or choose to extend Dynamics 365 Retail to modify the existing business logic or add some new feature to the product to meet their business goals.</span></span> <span data-ttu-id="2ff2b-114">販売時点管理 (POS)、Commerce Runtime (CRT)、および本社 (HQ) では、カスタム ビジネス シナリオをサポートするための拡張ポイントを追加しています。</span><span class="sxs-lookup"><span data-stu-id="2ff2b-114">In the point of sale (POS), commerce runtime (CRT), and headquarters (HQ), we are adding more extension points to support custom business scenarios.</span></span> <span data-ttu-id="2ff2b-115">この機能の目標は、拡張シナリオをサポートするために製品に必要なコア拡張ポイントを追加することです。</span><span class="sxs-lookup"><span data-stu-id="2ff2b-115">The goal of this feature is to add the necessary core extension points in the product to support extension scenarios.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="2ff2b-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2ff2b-116">Feature details</span></span>
<!--feature detail start -->
### <a name="framework-enhancements"></a><span data-ttu-id="2ff2b-117">フレームワークの機能強化</span><span class="sxs-lookup"><span data-stu-id="2ff2b-117">Framework enhancements</span></span>
<span data-ttu-id="2ff2b-118">バイナリ ベースの拡張モデルに移行した後、簡単にロジックを使用およびオーバーライドできるように、すべてのコア POS ロジックとユーザー インターフェイス (UI) コントロールをラップし、SDK (API) として公開しています。</span><span class="sxs-lookup"><span data-stu-id="2ff2b-118">After moving toward the binary-based extension model, we are wrapping and exposing all our core POS logic and user interface (UI) controls as SDK (APIs) to help the extension to easily consume and override our logic.</span></span> <span data-ttu-id="2ff2b-119">これらの API がないと、拡張機能でカスタム ロジックを記述するのは困難です。</span><span class="sxs-lookup"><span data-stu-id="2ff2b-119">Without these APIs, it will be difficult for the extension to write some custom logic.</span></span> <span data-ttu-id="2ff2b-120">場合によっては、拡張機能で既存のコードの一部を書き換えたり、単純なシナリオを実行するには多すぎるコード行を書いたりする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2ff2b-120">In some cases, the extension has to rewrite some of the existing code or write too many lines of code to do a simple scenario.</span></span> <span data-ttu-id="2ff2b-121">これを回避し、コード行数を減らすために、より高度な API と構成主導の開発を導入して、開発プロセス全体を簡素化しています。</span><span class="sxs-lookup"><span data-stu-id="2ff2b-121">To avoid this and to reduce the number of lines of code, we’re introducing more advanced APIs and configuration-driven development to simplify the overall development process.</span></span>    

### <a name="pos-ui-and-api-extension"></a><span data-ttu-id="2ff2b-122">POS UI と API 拡張機能</span><span class="sxs-lookup"><span data-stu-id="2ff2b-122">POS UI and API extension</span></span>
<span data-ttu-id="2ff2b-123">POS フレームワークを継続的に拡張し、拡張機能でロジックを使用するための POS API と、コア POS ビューにカスタム列、アプリ バー ボタン、カスタム コントロールを追加するための UI 拡張ポイントを追加しています。</span><span class="sxs-lookup"><span data-stu-id="2ff2b-123">We are continuously enhancing the POS framework to add more POS APIs to consume our logic in extension and UI extension points to add custom columns, app bar buttons, and custom controls in core POS views.</span></span>

### <a name="pos-overridable-requests-and-triggers"></a><span data-ttu-id="2ff2b-124">POS オーバーライド可能な要求とトリガー</span><span class="sxs-lookup"><span data-stu-id="2ff2b-124">POS overridable requests and triggers</span></span>
<span data-ttu-id="2ff2b-125">POS ワークフローまたは POS ビジネス ロジックをオーバーライドし、カスタム ロジックまたは検証を追加するために、新しいオーバーライド可能な要求が POS に追加されています。</span><span class="sxs-lookup"><span data-stu-id="2ff2b-125">New overridable requests are added in POS to override the POS workflow or POS business logic and to add custom logic or validation.</span></span> <span data-ttu-id="2ff2b-126">POS トリガー フレームワークは、コア POS ロジックの前後でカスタム ロジックを実行するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="2ff2b-126">POS trigger framework helps you to run custom logic before or after core POS logic.</span></span> <span data-ttu-id="2ff2b-127">この新しいパターンにより、開発者は POS のワークフローを簡単にカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="2ff2b-127">With this new pattern, developers can easily customize any workflow in POS.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="2ff2b-128">関連項目</span><span class="sxs-lookup"><span data-stu-id="2ff2b-128">See also</span></span>

<span data-ttu-id="2ff2b-129">[Retail POS API](https://docs.microsoft.com/dynamics365/unified-operations/retail/dev-itpro/pos-apis) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="2ff2b-129">[Retail POS APIs](https://docs.microsoft.com/dynamics365/unified-operations/retail/dev-itpro/pos-apis) (docs)</span></span>
