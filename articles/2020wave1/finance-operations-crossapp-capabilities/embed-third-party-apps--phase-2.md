---
title: サード パーティのアプリを埋め込む - フェーズ 2
description: サード パーティのアプリを埋め込む
author: relnotes
ms.reviewer: sericks
ms.date: 01/10/2020
ms.assetid: ec26b6a7-db1d-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: a887bef155e003cd879e50990b0fb26a415a1b6a
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986720"
---
# <a name="embed-third-party-apps--phase-2"></a><span data-ttu-id="2787c-103">サード パーティのアプリを埋め込む - フェーズ 2</span><span class="sxs-lookup"><span data-stu-id="2787c-103">Embed third-party apps – phase 2</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="2787c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="2787c-104">Enabled for</span></span>    |  <span data-ttu-id="2787c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2787c-105">Public preview</span></span> | <span data-ttu-id="2787c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="2787c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="2787c-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="2787c-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="2787c-108">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="2787c-108">Apr 2020</span></span>| -|


## <a name="feature-details"></a><span data-ttu-id="2787c-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2787c-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="2787c-110">場合によっては、自社やパートナーによって構築された Finance and Operations アプリケーションを、サードパーティ アプリと連携させて使用することもあります。</span><span class="sxs-lookup"><span data-stu-id="2787c-110">You might have third-party apps that work in conjunction with Finance and Operations apps that are either built in-house or by a partner.</span></span> <span data-ttu-id="2787c-111">この機能は、Finance and Operations アプリ内に Power Apps を埋め込むのと同様に、個人用設定を使用して Finance and Operations アプリ内にサード パーティ アプリを埋め込めるようにすることで、シームレスな統合を実現できるようにするためのものです。</span><span class="sxs-lookup"><span data-stu-id="2787c-111">This feature aims to provide a seamless integration by allowing you to embed third-party apps within your Finance and Operations apps by using personalization, similar to how you can embed Power Apps inside of Finance and Operations apps.</span></span> <span data-ttu-id="2787c-112">既存のフォーム内のタブ ページ内にサード パーティ アプリを埋め込むこともできますし、新しいフルページ エクスペリエンスを作成して、サード パーティ アプリを表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="2787c-112">You'll have the option to embed third-party apps inside tab pages within existing forms, or create new full-page experiences that showcase your third-party app.</span></span>

<span data-ttu-id="2787c-113">**10.0.8 / Platform update 32** ユーザーがタブ ページ内に Power App を追加できるのと同じ場所で、特権ユーザーが個人用設定を使用して既存のフォームのタブ ページ内にサード パーティ アプリを埋め込むことができます。</span><span class="sxs-lookup"><span data-stu-id="2787c-113">**10.0.8 / Platform update 32** Third-party apps can be embedded inside tab pages in existing forms via personalization by privileged users in the same places where users can add a Power App inside a tab page.</span></span> <span data-ttu-id="2787c-114">これを容易にするために、個人用設定ツール バーの **Power App の追加**オプションが**アプリの追加**オプションに置き換えられました。</span><span class="sxs-lookup"><span data-stu-id="2787c-114">To facilitate this, the **Add a Power App** option in the personalization toolbar has been replaced with an **Add an app** option.</span></span> <span data-ttu-id="2787c-115">このオプションを選択すると、ユーザーが埋め込むアプリの種類 (Power App や Web サイトなど) を決定できるギャラリー ページが開きます。</span><span class="sxs-lookup"><span data-stu-id="2787c-115">Selecting this option opens a gallery page where the user can decide which kind of app they want to embed, such as a Power App or website.</span></span> <span data-ttu-id="2787c-116">標準ではシステム管理者、セキュリティ管理者、および IT マネージャーのみがこの機能にアクセスできることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="2787c-116">Note that only system administrators, security administrators, and IT managers have access to this capability out of the box.</span></span>  

<span data-ttu-id="2787c-117">この機能は、**保存されているビュー**機能が有効になっていることに依存することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="2787c-117">Note that this functionality is dependent on the **Saved views** feature being enabled.</span></span>

<span data-ttu-id="2787c-118">**10.0.7 / Platform update 31** 新しい Web サイト ホスト コントロールが追加され、開発者がサード パーティのアプリを Finance and Operations ページに直接埋め込めるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2787c-118">**10.0.7 / Platform update 31** A new Website Host control has been added to allow developers to embed third-party apps directly into Finance and Operations pages.</span></span> 


<!--feature detail end -->









