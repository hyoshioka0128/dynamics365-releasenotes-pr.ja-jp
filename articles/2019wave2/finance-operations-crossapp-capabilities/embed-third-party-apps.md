---
title: サード パーティのアプリを埋め込む
description: サード パーティのアプリを埋め込む
author: relnotes
ms.reviewer: sericks
ms.date: 12/13/2019
ms.assetid: 6c1ed69c-73ef-e911-a812-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: f516bc667dfc5467d64d3b1c8398f988004df9d8
ms.sourcegitcommit: 50510b41ebc81897993a45f689651d9eda6c4247
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/20/2019
ms.locfileid: "2909656"
---
# <a name="embed-third-party-apps"></a><span data-ttu-id="7bf0c-103">サード パーティのアプリを埋め込む</span><span class="sxs-lookup"><span data-stu-id="7bf0c-103">Embed third-party apps</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="7bf0c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7bf0c-104">Enabled for</span></span>    |  <span data-ttu-id="7bf0c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7bf0c-105">Public preview</span></span> | <span data-ttu-id="7bf0c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7bf0c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7bf0c-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="7bf0c-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="7bf0c-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="7bf0c-108">Feb 2020</span></span>| -|






## <a name="feature-details"></a><span data-ttu-id="7bf0c-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7bf0c-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7bf0c-110">場合によっては、自社やパートナーによって構築された Finance and Operations アプリケーションを、サードパーティ アプリと連携させて使用することもあるでしょう。</span><span class="sxs-lookup"><span data-stu-id="7bf0c-110">You might have third-party apps that work in conjunction with Finance and Operations applications that are either built in-house or by a partner.</span></span> <span data-ttu-id="7bf0c-111">この機能は、Finance and Operations のアプリケーション ページ内に Power Apps を埋め込むのと同様に、個人用設定を使用して Finance and Operations アプリケーション内にサードパーティ アプリを埋め込めるようにすることで、シームレスな統合を実現できるようにするためのものです。</span><span class="sxs-lookup"><span data-stu-id="7bf0c-111">This feature aims to provide seamless integration by allowing you to embed third-party apps within Finance and Operations applications via personalization, similar to how you can embed Power Apps inside of Finance and Operations application pages.</span></span> <span data-ttu-id="7bf0c-112">既存のフォーム内のタブ ページ内にサードパーティ アプリを埋め込むこともできますし、新しいフルページ エクスペリエンスを作成して、サードパーティ アプリを表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="7bf0c-112">You'll have the option to embed third-party apps inside tab pages within existing forms, or create new full-page experiences that showcase your third-party app.</span></span>

<span data-ttu-id="7bf0c-113">**Platform update 31**</span><span class="sxs-lookup"><span data-stu-id="7bf0c-113">**Platform update 31**</span></span>

<span data-ttu-id="7bf0c-114">新しい Web サイト ホスト コントロールが追加され、開発者がサードパーティのアプリを Finance and Operations ページに直接埋め込めるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7bf0c-114">A new Website Host control has been added to allow developers to embed third-party apps directly into Finance and Operations pages.</span></span> 

<span data-ttu-id="7bf0c-115">**Platform update 32**</span><span class="sxs-lookup"><span data-stu-id="7bf0c-115">**Platform update 32**</span></span>

<span data-ttu-id="7bf0c-116">ユーザーがタブ ページ内に Power App を追加できるのと同じ場所で、特権ユーザーが個人用設定を使用して既存のフォームのタブ ページ内にサードパーティ アプリを埋め込むことができます。</span><span class="sxs-lookup"><span data-stu-id="7bf0c-116">Third-party apps can be embedded inside tab pages in existing forms via personalization by privileged users in the same places where users can add a Power App inside a tab page.</span></span> <span data-ttu-id="7bf0c-117">これを容易にするために、個人用設定ツール バーの [Power App の追加] オプションが [アプリの追加] オプションに置き換えられました。</span><span class="sxs-lookup"><span data-stu-id="7bf0c-117">To facilitate this, the "Add a Power App" option in the personalization toolbar has been replaced with an "Add an app" option.</span></span> <span data-ttu-id="7bf0c-118">このオプションを選択すると、ユーザーが埋め込むアプリの種類 (Power App または Web サイト) を決定できるギャラリー ページが開きます。</span><span class="sxs-lookup"><span data-stu-id="7bf0c-118">Selecting this option opens a gallery page where the user can decide which kind of app they want to embed, Power App or Website.</span></span>  <span data-ttu-id="7bf0c-119">標準ではシステム管理者、セキュリティ管理者、および IT マネージャーのみがこの機能にアクセスできることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="7bf0c-119">Note that only system administrators, security administrators, and IT managers have access to this capability out of the box.</span></span>  

<span data-ttu-id="7bf0c-120">この機能は、保存されているビュー機能が有効になっていることに依存することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="7bf0c-120">Note that this functionality is dependent on the Saved views feature being enabled.</span></span>
<!--feature detail end -->









