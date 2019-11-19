---
title: フル キーボード ショートカットのサポート
description: ショートカットが追加されており、開発者はカスタム アクション用に独自のキーボード ショートカットを追加できます。
author: kotelko
ms.reviewer: sgroespe
ms.date: 10/01/2019
ms.assetid: b663278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: 8af2b0666ff6ce43755578ace418b9bd6e9f6257
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2667303"
---
# <a name="full-keyboard-shortcut-support"></a><span data-ttu-id="595d4-103">フル キーボード ショートカットのサポート</span><span class="sxs-lookup"><span data-stu-id="595d4-103">Full keyboard shortcut support</span></span>


| <span data-ttu-id="595d4-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="595d4-104">Enabled for</span></span>    |  <span data-ttu-id="595d4-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="595d4-105">Public preview</span></span> | <span data-ttu-id="595d4-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="595d4-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="595d4-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="595d4-107">End users, automatically</span></span>|<span data-ttu-id="595d4-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="595d4-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="595d4-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="595d4-109">Aug 1, 2019</span></span>| <span data-ttu-id="595d4-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="595d4-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="595d4-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="595d4-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="595d4-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="595d4-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="595d4-113">熟練したユーザーは、それぞれの機能を見つけるためにアクション バーを探すのではなく、キーボードを使用してよく使う機能にアクセスできると、より生産的になります。</span><span class="sxs-lookup"><span data-stu-id="595d4-113">Proficient users are more productive when they can access commonly used features with their keyboard without having to explore the action bar to find each one.</span></span> <span data-ttu-id="595d4-114">開発者は、ソリューションにキーボード ショートカットを追加することによって、エンド ユーザーのフィードバックに対応することもできます。</span><span class="sxs-lookup"><span data-stu-id="595d4-114">Developers now also get the possibility to respond to end-user feedback by adding keyboard shortcuts to their solutions.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="595d4-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="595d4-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="595d4-116">Business Central 用の拡張機能を作成する開発者は、AL プロパティによってほとんどのアクションや操作にキーボード ショートカットを追加できます。</span><span class="sxs-lookup"><span data-stu-id="595d4-116">Developers creating extensions for Business Central can now add keyboard shortcuts to most actions and operations via an AL property.</span></span> <span data-ttu-id="595d4-117">つまり、アプリケーション開発者は、基本アプリケーションのアクションや、拡張機能の独自のオブジェクトに対して、キーボード ショートカットを指定できます。</span><span class="sxs-lookup"><span data-stu-id="595d4-117">This means that application developers can specify keyboard shortcuts for actions in the base application and their own objects in their extensions.</span></span> <span data-ttu-id="595d4-118">そのためには、開発者は AL (Business Central 拡張機能用のプログラミング言語) の [ShortCutKey プロパティ](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/properties/devenv-shortcutkey-property "ShortCutKey プロパティ")を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="595d4-118">To do this, the developer must use the [ShortCutKey property](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/properties/devenv-shortcutkey-property "ShortCutKey Property") in AL (the programming language for Business Central extensions).</span></span>

<span data-ttu-id="595d4-119">この機能により、Business Central のキーボード ショートカットの定義済みリストが補完され、パートナーはいっそう柔軟に開発できるようになります。</span><span class="sxs-lookup"><span data-stu-id="595d4-119">This feature complements the predefined list of keyboard shortcuts in Business Central and enables more flexible development for partners.</span></span>

<span data-ttu-id="595d4-120">追加のキーボード ショートカットは 2019 年リリース ウェーブ 2 で追加されます。</span><span class="sxs-lookup"><span data-stu-id="595d4-120">Additional keyboard shortcuts are added in the 2019 release wave 2.</span></span> <span data-ttu-id="595d4-121">これらのほとんどはビジネス アプリケーション領域で定義されたショートカットに基づいており、今後、柔軟性向上のために変更される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="595d4-121">Most of these come from shortcuts defined in the business application area and might be changed in the future to be more flexible.</span></span>


<span data-ttu-id="595d4-122">更新されたキーボード ショートカットの完全な一覧は、常に「[キーボード ショートカット](https://go.microsoft.com/fwlink/?LinkId=2064754)」で公開されます。</span><span class="sxs-lookup"><span data-stu-id="595d4-122">A full list of updated keyboard shortcuts is always published on [Keyboard Shortcuts](https://go.microsoft.com/fwlink/?LinkId=2064754).</span></span> <span data-ttu-id="595d4-123">たとえば、新しく追加されたキーボード ショートカットの 1 つとして、ドキュメントを転記するための *F9* があります。</span><span class="sxs-lookup"><span data-stu-id="595d4-123">For instance, one newly added keyboard shortcut is *F9* for posting a document.</span></span>

<span data-ttu-id="595d4-124">![キーボード ショートカットを使用した請求書の転記](media/posting.png "キーボード ショートカットを使用した請求書の転記")</span><span class="sxs-lookup"><span data-stu-id="595d4-124">![Posting an invoice using a keyboard shortcut](media/posting.png "Posting an invoice using a keyboard shortcut")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="595d4-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="595d4-125">See also</span></span>

<span data-ttu-id="595d4-126">[キーボード ショートカット](https://docs.microsoft.com/dynamics365/business-central/keyboard-shortcuts) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="595d4-126">[Keyboard Shortcuts](https://docs.microsoft.com/dynamics365/business-central/keyboard-shortcuts) (docs)</span></span>
