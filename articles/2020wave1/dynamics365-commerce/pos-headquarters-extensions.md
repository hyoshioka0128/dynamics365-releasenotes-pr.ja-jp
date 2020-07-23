---
title: POS および本社の拡張機能
description: POS および本社の拡張機能
author: mugunthanm
ms.reviewer: josaw
ms.date: 05/26/2020
ms.assetid: 2c9e2005-f5f6-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 5abf4ad84e9abec2ab15bc3e116d3979277ed9c1
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3415822"
---
# <a name="pos-and-headquarters-extensions"></a><span data-ttu-id="140ed-103">POS および本社の拡張機能</span><span class="sxs-lookup"><span data-stu-id="140ed-103">POS and headquarters extensions</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="140ed-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="140ed-104">Enabled for</span></span>    |  <span data-ttu-id="140ed-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="140ed-105">Public preview</span></span> | <span data-ttu-id="140ed-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="140ed-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="140ed-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="140ed-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="140ed-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="140ed-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="140ed-109">2020 年 5 月 18 日</span><span class="sxs-lookup"><span data-stu-id="140ed-109">May 18, 2020</span></span>| <span data-ttu-id="140ed-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="140ed-110">Jul 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="140ed-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="140ed-111">Feature details</span></span>
<!--feature detail start -->
### <a name="framework-enhancements"></a><span data-ttu-id="140ed-112">フレームワークの機能強化</span><span class="sxs-lookup"><span data-stu-id="140ed-112">Framework enhancements</span></span>
<span data-ttu-id="140ed-113">バイナリ ベースの拡張モデルに移行した後、簡単にロジックを使用およびオーバーライドできるように、すべてのコア POS ロジックとユーザー インターフェイス (UI) コントロールをラップし、SDK (API) として公開しています。</span><span class="sxs-lookup"><span data-stu-id="140ed-113">After moving toward the binary-based extension model, we are wrapping and exposing all our core point of sale (POS) logic and user interface (UI) controls as SDK (APIs) to help the extension easily consume and override our logic.</span></span> <span data-ttu-id="140ed-114">これらの API がないと、拡張機能でカスタム ロジックを実装するのは困難です。</span><span class="sxs-lookup"><span data-stu-id="140ed-114">Without these APIs, it is difficult for the extension to implement custom logic.</span></span> <span data-ttu-id="140ed-115">場合によっては、拡張機能で既存のコードの一部を書き換えたり、単純なシナリオを実行するには多すぎるコード行を書いたりする必要があります。</span><span class="sxs-lookup"><span data-stu-id="140ed-115">In some cases, the extension has to rewrite some of the existing code or write too many lines of code to do a simple scenario.</span></span> <span data-ttu-id="140ed-116">これを回避し、コード行数を減らすために、より高度な API と構成主導の開発を導入して、開発プロセス全体を簡素化しています。</span><span class="sxs-lookup"><span data-stu-id="140ed-116">To avoid this and to reduce the number of lines of code, we are introducing more advanced APIs and configuration-driven development to simplify the overall development process.</span></span>    

### <a name="pos-ui-and-api-extension"></a><span data-ttu-id="140ed-117">POS UI と API 拡張機能</span><span class="sxs-lookup"><span data-stu-id="140ed-117">POS UI and API extension</span></span>
<span data-ttu-id="140ed-118">拡張機能でロジックを使用するための POS API と、コア POS ビューにカスタム列、アプリ バー ボタン、カスタム コントロールを追加するための UI 拡張ポイントを追加することにより、POS フレームワークを拡張しました。</span><span class="sxs-lookup"><span data-stu-id="140ed-118">We have enhanced the POS framework by adding more POS APIs to consume our logic in extensions, and UI extension points to add custom columns, app bar buttons, and custom controls in core POS views.</span></span>

### <a name="pos-overridable-requests-and-triggers"></a><span data-ttu-id="140ed-119">POS オーバーライド可能な要求とトリガー</span><span class="sxs-lookup"><span data-stu-id="140ed-119">POS overridable requests and triggers</span></span>
<span data-ttu-id="140ed-120">POS ワークフローまたは POS ビジネス ロジックをオーバーライドし、カスタム ロジックまたは検証を追加するために、新しいオーバーライド可能な要求が POS に追加されました。</span><span class="sxs-lookup"><span data-stu-id="140ed-120">We added new overridable requests in POS to override the POS workflow or POS business logic, and to add custom logic or validation.</span></span> <span data-ttu-id="140ed-121">POS トリガー フレームワークは、コア POS ロジックの前後でカスタム ロジックを実行するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="140ed-121">The POS trigger framework helps you to run custom logic before or after core POS logic.</span></span> <span data-ttu-id="140ed-122">この新しいパターンにより、開発者は POS のワークフローを簡単にカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="140ed-122">With this new pattern, developers can more easily customize any workflow in POS.</span></span>
<!--feature detail end -->









