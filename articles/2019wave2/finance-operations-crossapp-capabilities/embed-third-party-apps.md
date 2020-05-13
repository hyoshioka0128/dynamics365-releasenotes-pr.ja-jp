---
title: サード パーティのアプリを埋め込む
description: サード パーティのアプリを埋め込む
author: relnotes
ms.reviewer: sericks
ms.date: 02/18/2020
ms.assetid: 6c1ed69c-73ef-e911-a812-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: a153a3e8f6be7f02e7b343c49434917edb6b3678
ms.sourcegitcommit: bfe05af05f11f2c318a77bb3138c3df0796c7187
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/27/2020
ms.locfileid: "3089045"
---
# <a name="embed-third-party-apps"></a><span data-ttu-id="6c0a7-103">サード パーティのアプリを埋め込む</span><span class="sxs-lookup"><span data-stu-id="6c0a7-103">Embed third-party apps</span></span>


| <span data-ttu-id="6c0a7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="6c0a7-104">Enabled for</span></span>    |  <span data-ttu-id="6c0a7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6c0a7-105">Public preview</span></span> | <span data-ttu-id="6c0a7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="6c0a7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6c0a7-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="6c0a7-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="6c0a7-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6c0a7-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6c0a7-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="6c0a7-109">Feb 3, 2020</span></span>| -|






## <a name="feature-details"></a><span data-ttu-id="6c0a7-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6c0a7-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6c0a7-111">場合によっては、自社やパートナーによって構築された Finance and Operations アプリケーションを、サードパーティ アプリと連携させて使用することもあります。</span><span class="sxs-lookup"><span data-stu-id="6c0a7-111">You might have third-party apps that work in conjunction with Finance and Operations applications that are either built in-house or by a partner.</span></span> <span data-ttu-id="6c0a7-112">この機能は、Finance and Operations アプリケーション ページ内に Power Apps を埋め込むのと同様に、個人用設定を使用して Finance and Operations アプリケーション内にサード パーティ アプリを埋め込めるようにすることで、シームレスな統合を実現できるようにするためのものです。</span><span class="sxs-lookup"><span data-stu-id="6c0a7-112">This feature aims to provide seamless integration by allowing you to embed third-party apps within Finance and Operations applications via personalization, similar to how you can embed Power Apps inside of Finance and Operations application pages.</span></span> <span data-ttu-id="6c0a7-113">既存のフォーム内のタブ ページ内にサード パーティ アプリを埋め込むことも、新しいフルページ エクスペリエンスを作成して、サード パーティ アプリを表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="6c0a7-113">You'll have the option to embed third-party apps inside tab pages within existing forms, or create new full-page experiences that showcase your third-party app.</span></span>

<span data-ttu-id="6c0a7-114">**Platform update 31**</span><span class="sxs-lookup"><span data-stu-id="6c0a7-114">**Platform update 31**</span></span>

<span data-ttu-id="6c0a7-115">新しい Web サイト ホスト コントロールが追加され、開発者がサードパーティのアプリを Finance and Operations ページに直接埋め込めるようになりました。</span><span class="sxs-lookup"><span data-stu-id="6c0a7-115">A new Website Host control has been added to allow developers to embed third-party apps directly into Finance and Operations pages.</span></span> 

<span data-ttu-id="6c0a7-116">**Platform update 32**</span><span class="sxs-lookup"><span data-stu-id="6c0a7-116">**Platform update 32**</span></span>

<span data-ttu-id="6c0a7-117">ユーザーがタブ ページ内に Power App を追加できるのと同じ場所で、特権ユーザーが個人用設定を使用して既存のフォームのタブ ページ内にサードパーティ アプリを埋め込むことができます。</span><span class="sxs-lookup"><span data-stu-id="6c0a7-117">Third-party apps can be embedded inside tab pages in existing forms via personalization by privileged users in the same places where users can add a Power App inside a tab page.</span></span> <span data-ttu-id="6c0a7-118">これを容易にするために、個人用設定ツール バーの [Power App の追加] オプションが [アプリの追加] オプションに置き換えられました。</span><span class="sxs-lookup"><span data-stu-id="6c0a7-118">To facilitate this, the "Add a Power App" option in the personalization toolbar has been replaced with an "Add an app" option.</span></span> <span data-ttu-id="6c0a7-119">このオプションを選択すると、ユーザーが埋め込むアプリの種類 (Power App または Web サイト) を決定できるギャラリー ページが開きます。</span><span class="sxs-lookup"><span data-stu-id="6c0a7-119">Selecting this option opens a gallery page where the user can decide which kind of app they want to embed, Power App or Website.</span></span> <span data-ttu-id="6c0a7-120">標準ではシステム管理者、セキュリティ管理者、および IT マネージャーのみがこの機能にアクセスできることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="6c0a7-120">Note that only system administrators, security administrators, and IT managers have access to this capability out of the box.</span></span>  

<span data-ttu-id="6c0a7-121">この機能は、保存されているビュー機能が有効になっていることに依存します。</span><span class="sxs-lookup"><span data-stu-id="6c0a7-121">This functionality is dependent on the Saved views feature being enabled.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="6c0a7-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="6c0a7-122">See also</span></span>

<span data-ttu-id="6c0a7-123">[ユーザー エクスペリエンスのパーソナライズ](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/personalize-user-experience) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="6c0a7-123">[Personalize the user experience](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/personalize-user-experience) (docs)</span></span>
