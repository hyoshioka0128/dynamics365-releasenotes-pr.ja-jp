---
title: フル キーボード ショートカットのサポート
description: ショートカットが追加されており、開発者はカスタム アクション用に独自のキーボード ショートカットを追加できます。
author: kotelko
ms.reviewer: sgroespe
ms.date: 09/10/2019
ms.assetid: b663278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: ce98521ddd6372396c584f4c2947c599c6b10ac5
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140603"
---
# <a name="full-keyboard-shortcut-support"></a><span data-ttu-id="4ccb7-103">フル キーボード ショートカットのサポート</span><span class="sxs-lookup"><span data-stu-id="4ccb7-103">Full keyboard shortcut support</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="4ccb7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="4ccb7-104">Enabled for</span></span>    |  <span data-ttu-id="4ccb7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="4ccb7-105">Public preview</span></span> | <span data-ttu-id="4ccb7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="4ccb7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="4ccb7-107">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="4ccb7-107">Users, automatically</span></span>|<span data-ttu-id="4ccb7-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="4ccb7-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="4ccb7-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="4ccb7-109">Aug 1, 2019</span></span>| <span data-ttu-id="4ccb7-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="4ccb7-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="4ccb7-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="4ccb7-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="4ccb7-112">熟練したユーザーは、それぞれの機能を見つけるためにアクション バーを探すのではなく、キーボードを使用してよく使う機能にアクセスできると、より生産的になります。</span><span class="sxs-lookup"><span data-stu-id="4ccb7-112">Proficient users are more productive when they can access commonly used features with their keyboard without having to explore the action bar to find each one.</span></span> <span data-ttu-id="4ccb7-113">開発者は、ソリューションにキーボード ショートカットを追加することによって、エンド ユーザーのフィードバックに対応することもできます。</span><span class="sxs-lookup"><span data-stu-id="4ccb7-113">Developers now also get the possibility to respond to end-user feedback by adding keyboard shortcuts to their solutions.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="4ccb7-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="4ccb7-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="4ccb7-115">Business Central 用の拡張機能を作成する開発者は、AL プロパティによってほとんどのアクションや操作にキーボード ショートカットを追加できます。</span><span class="sxs-lookup"><span data-stu-id="4ccb7-115">Developers creating extensions for Business Central can now add keyboard shortcuts to most actions and operations via an AL property.</span></span> <span data-ttu-id="4ccb7-116">つまり、アプリケーション開発者は、基本アプリケーションのアクションや、拡張機能の独自のオブジェクトに対して、キーボード ショートカットを指定できます。</span><span class="sxs-lookup"><span data-stu-id="4ccb7-116">This means that application developers can specify keyboard shortcuts for actions in the base application and their own objects in their extensions.</span></span> <span data-ttu-id="4ccb7-117">そのためには、開発者は AL (Business Central 拡張機能用のプログラミング言語) の [ShortCutKey プロパティ](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/properties/devenv-shortcutkey-property "ShortCutKey プロパティ")を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4ccb7-117">To do this, the developer must use the [ShortCutKey property](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/properties/devenv-shortcutkey-property "ShortCutKey Property") in AL (the programming language for Business Central extensions).</span></span>

<span data-ttu-id="4ccb7-118">この機能により、Business Central のキーボード ショートカットの定義済みリストが補完され、パートナーはいっそう柔軟に開発できるようになります。</span><span class="sxs-lookup"><span data-stu-id="4ccb7-118">This feature complements the predefined list of keyboard shortcuts in Business Central and enables more flexible development for partners.</span></span>

<span data-ttu-id="4ccb7-119">追加のキーボード ショートカットは 2019 年リリース ウェーブ 2 で追加されます。</span><span class="sxs-lookup"><span data-stu-id="4ccb7-119">Additional keyboard shortcuts are added in the 2019 wave 2 release.</span></span> <span data-ttu-id="4ccb7-120">これらのほとんどはビジネス アプリケーション領域で定義されたショートカットに基づいており、今後、柔軟性向上のために変更される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4ccb7-120">Most of these come from shortcuts defined in the business application area and might be changed in the future to be more flexible.</span></span>


<span data-ttu-id="4ccb7-121">更新されたキーボード ショートカットの完全な一覧は、常に「[キーボード ショートカット](https://go.microsoft.com/fwlink/?LinkId=2064754)」で公開されます。</span><span class="sxs-lookup"><span data-stu-id="4ccb7-121">A full list of updated keyboard shortcuts is always published on [Keyboard Shortcuts](https://go.microsoft.com/fwlink/?LinkId=2064754).</span></span> <span data-ttu-id="4ccb7-122">たとえば、新しく追加されたキーボード ショートカットの 1 つとして、ドキュメントを転記するための *F9* があります。</span><span class="sxs-lookup"><span data-stu-id="4ccb7-122">For instance, one newly added keyboard shortcut is *F9* for posting a document.</span></span>

<span data-ttu-id="4ccb7-123">![キーボード ショートカットを使用した請求書の転記](media/posting.png "キーボード ショートカットを使用した請求書の転記")</span><span class="sxs-lookup"><span data-stu-id="4ccb7-123">![Posting an invoice using a keyboard shortcut](media/posting.png "Posting an invoice using a keyboard shortcut")</span></span>
<!--feature detail end -->











