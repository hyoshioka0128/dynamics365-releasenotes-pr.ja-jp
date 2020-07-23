---
title: Business Central 管理センターでの AppSource アプリの更新プログラムのインストール
description: Business Central 管理センターでは、[アプリの管理] ページでアプリの更新プログラムを検出してインストールできるようになりました。
author: relnotes
ms.reviewer: jswymer
ms.date: 06/15/2020
ms.assetid: fcd16ef0-cc6d-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: dmitrych
dynamics365pdf: true
ms.openlocfilehash: 0c567ae82c2734235737a64a589acb6c2a9e7a32
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3487977"
---
# <a name="installing-appsource-apps-updates-in-the-business-central-administration-center"></a><span data-ttu-id="febbf-103">Business Central 管理センターでの AppSource アプリの更新プログラムのインストール</span><span class="sxs-lookup"><span data-stu-id="febbf-103">Installing AppSource apps updates in the Business Central administration center</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="febbf-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="febbf-104">Enabled for</span></span>    |  <span data-ttu-id="febbf-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="febbf-105">Public preview</span></span> | <span data-ttu-id="febbf-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="febbf-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="febbf-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="febbf-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="febbf-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="febbf-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="febbf-109">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="febbf-109">Apr 1, 2020</span></span>| <span data-ttu-id="febbf-110">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="febbf-110">Jun 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="febbf-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="febbf-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="febbf-112">ご使用の環境にインストールしたアプリが、AppSource ISV によって提供される最新の変更と修正プログラムで常に最新に保たれるようにしてください。</span><span class="sxs-lookup"><span data-stu-id="febbf-112">Ensure that the apps you have installed for your environments are always up to date with the latest changes and hotfixes provided by the AppSource ISVs.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="febbf-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="febbf-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="febbf-114">AppSource マーケットプレイスで使用可能なアプリの新しいバージョンが ISV によって作成されると、パートナーと顧客の管理者は、管理センターの [アプリの管理] ページを使用して更新プログラムを検出し、インストールできます。</span><span class="sxs-lookup"><span data-stu-id="febbf-114">When ISVs make new versions of their apps available on the AppSource marketplace, the partners and customer admins can discover and install the updates by using the Manage Apps page of the administration center.</span></span>

<span data-ttu-id="febbf-115">[アプリの管理] ページは、管理者にも役立ちます。</span><span class="sxs-lookup"><span data-stu-id="febbf-115">The Manage Apps page can also help admins:</span></span>

- <span data-ttu-id="febbf-116">アプリの更新の要件を解決します。</span><span class="sxs-lookup"><span data-stu-id="febbf-116">Resolve requirements for app updates.</span></span>
- <span data-ttu-id="febbf-117">アプリの依存関係を把握します。</span><span class="sxs-lookup"><span data-stu-id="febbf-117">Understand the apps dependencies.</span></span>
- <span data-ttu-id="febbf-118">インストールと更新の問題を分析します。</span><span class="sxs-lookup"><span data-stu-id="febbf-118">Analyze installation and update issues.</span></span>
- <span data-ttu-id="febbf-119">アプリの更新をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="febbf-119">Trigger app updates.</span></span>

<span data-ttu-id="febbf-120">この機能は、Business Central Administration API からも利用できます。</span><span class="sxs-lookup"><span data-stu-id="febbf-120">The functionality is also available via the Business Central Administration API.</span></span> <span data-ttu-id="febbf-121">API を使用すると、パートナーと顧客の管理者は上記の操作をプログラムで実行できます。</span><span class="sxs-lookup"><span data-stu-id="febbf-121">The API enables partners and customer admins to do the above operations programmatically.</span></span>

<span data-ttu-id="febbf-122">新しい AppSource アプリのインストール、およびテナントごとの拡張機能 (PTE) の更新は、引き続き製品内の [拡張機能管理] ページから管理されるので注意してください。</span><span class="sxs-lookup"><span data-stu-id="febbf-122">Note that installation of the new AppSource apps, as well as updates to per-tenant extensions (PTEs), is still managed from the in-product Extensions Management page.</span></span>
<!--feature detail end -->

<span data-ttu-id="febbf-123">![管理センターでアプリを管理する](media/manage-apps.png "管理センターでアプリを管理する")</span><span class="sxs-lookup"><span data-stu-id="febbf-123">![Manage apps in the administration center](media/manage-apps.png "Manage apps in the administration center")</span></span>
<!-- Picture 1 -->








## <a name="thank-you-for-your-idea"></a><span data-ttu-id="febbf-124">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="febbf-124">Thank you for your idea</span></span>
<span data-ttu-id="febbf-125">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=4a4fbd14-8446-ea11-b698-0003ff68992e)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="febbf-125">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=4a4fbd14-8446-ea11-b698-0003ff68992e).</span></span> <span data-ttu-id="febbf-126">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="febbf-126">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="febbf-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="febbf-127">See also</span></span>

<!--docs start-->
<span data-ttu-id="febbf-128">[アプリの管理](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/tenant-admin-center-manage-apps) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="febbf-128">[Managing Apps](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/tenant-admin-center-manage-apps) (docs)</span></span>
<!--docs end-->
