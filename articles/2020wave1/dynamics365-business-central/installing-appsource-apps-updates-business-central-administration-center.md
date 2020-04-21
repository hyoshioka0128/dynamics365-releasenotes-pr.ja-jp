---
title: Business Central 管理センターでの AppSource アプリの更新プログラムのインストール
description: Business Central 管理センターでは、[アプリの管理] ページでアプリの更新プログラムを検出してインストールできるようになりました。
author: relnotes
ms.reviewer: jswymer
ms.date: 03/24/2020
ms.assetid: fcd16ef0-cc6d-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: dmitrych
dynamics365pdf: true
ms.openlocfilehash: abe13085702dc7f134c23f5f05712656c4f1678f
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232156"
---
# <a name="installing-appsource-apps-updates-in-the-business-central-administration-center"></a><span data-ttu-id="63290-103">Business Central 管理センターでの AppSource アプリの更新プログラムのインストール</span><span class="sxs-lookup"><span data-stu-id="63290-103">Installing AppSource apps updates in the Business Central administration center</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="63290-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="63290-104">Enabled for</span></span>    |  <span data-ttu-id="63290-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="63290-105">Public preview</span></span> | <span data-ttu-id="63290-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="63290-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="63290-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="63290-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="63290-108">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="63290-108">Apr 2020</span></span>| <span data-ttu-id="63290-109">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="63290-109">Jun 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="63290-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="63290-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="63290-111">ご使用の環境にインストールしたアプリが、AppSource ISV によって提供される最新の変更と修正プログラムで常に最新に保たれるようにしてください。</span><span class="sxs-lookup"><span data-stu-id="63290-111">Ensure that the apps you have installed for your environments are always up to date with the latest changes and hotfixes provided by the AppSource ISVs.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="63290-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="63290-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="63290-113">AppSource マーケットプレイスで使用可能なアプリの新しいバージョンが ISV によって作成されると、パートナーと顧客の管理者は、管理センターの [アプリの管理] ページを使用して更新プログラムを検出し、インストールできます。</span><span class="sxs-lookup"><span data-stu-id="63290-113">When ISVs make new versions of their apps available on the AppSource marketplace, the partners and customer admins can discover and install the updates by using the Manage Apps page of the administration center.</span></span>

<span data-ttu-id="63290-114">[アプリの管理] ページは、管理者にも役立ちます。</span><span class="sxs-lookup"><span data-stu-id="63290-114">The Manage Apps page can also help admins:</span></span>

- <span data-ttu-id="63290-115">アプリの更新の要件を解決します。</span><span class="sxs-lookup"><span data-stu-id="63290-115">resolve requirements for app updates.</span></span>
- <span data-ttu-id="63290-116">アプリの依存関係を把握します。</span><span class="sxs-lookup"><span data-stu-id="63290-116">understand the apps dependencies.</span></span>
- <span data-ttu-id="63290-117">インストールと更新の問題を分析します。</span><span class="sxs-lookup"><span data-stu-id="63290-117">analyze installation and update issues.</span></span>
- <span data-ttu-id="63290-118">アプリの更新をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="63290-118">trigger app updates.</span></span>

<span data-ttu-id="63290-119">この機能は、Business Central Administration API からも利用できます。</span><span class="sxs-lookup"><span data-stu-id="63290-119">The functionality is also available via the Business Central Administration API.</span></span> <span data-ttu-id="63290-120">API を使用すると、パートナーと顧客の管理者は上記の操作をプログラムで実行できます。</span><span class="sxs-lookup"><span data-stu-id="63290-120">The API enables partners and customer admins to do the above operations programmatically.</span></span>

<span data-ttu-id="63290-121">新しい AppSource アプリのインストール、およびテナントごとの拡張機能 (PTE) の更新は、引き続き製品内の [拡張機能管理] ページから管理されるので注意してください。</span><span class="sxs-lookup"><span data-stu-id="63290-121">Note that installation of the new AppSource apps, as well as updates to per-tenant extensions (PTEs) is still be managed from the in-product Extensions Management page.</span></span>
<!--feature detail end -->

<span data-ttu-id="63290-122">![管理センターでアプリを管理する](media/manage-apps.png "管理センターでアプリを管理する")</span><span class="sxs-lookup"><span data-stu-id="63290-122">![Manage apps in the administration center](media/manage-apps.png "Manage apps in the administration center")</span></span>
<!-- Picture 1 -->








## <a name="thank-you-for-your-idea"></a><span data-ttu-id="63290-123">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="63290-123">Thank you for your idea</span></span>
<span data-ttu-id="63290-124">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=4a4fbd14-8446-ea11-b698-0003ff68992e)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="63290-124">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=4a4fbd14-8446-ea11-b698-0003ff68992e).</span></span> <span data-ttu-id="63290-125">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="63290-125">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="63290-126">関連項目</span><span class="sxs-lookup"><span data-stu-id="63290-126">See also</span></span>


<!--docs start-->
<span data-ttu-id="63290-127">[アプリの管理](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/tenant-admin-center-manage-apps) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="63290-127">[Managing Apps](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/tenant-admin-center-manage-apps) (docs)</span></span>
<!--docs end-->

