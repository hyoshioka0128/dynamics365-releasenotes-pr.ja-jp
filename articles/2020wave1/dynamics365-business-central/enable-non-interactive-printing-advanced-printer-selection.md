---
title: クラウドで非対話型印刷を有効にする
description: ユーザーはオンラインとオンプレミスの両方で、各レポートのプリンター選択を定義し、あらかじめ定義したプリンターを使用してレポートを印刷することができます。
author: kotelko
ms.reviewer: jswymer
ms.date: 04/07/2020
ms.assetid: 5f638301-24cb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: a07d7c6429a0bac064ecba8401eaa7e834a26698
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255125"
---
# <a name="enable-non-interactive-printing-in-the-cloud"></a><span data-ttu-id="fa35f-103">クラウドで非対話型印刷を有効にする</span><span class="sxs-lookup"><span data-stu-id="fa35f-103">Enable non-interactive printing in the cloud</span></span>


| <span data-ttu-id="fa35f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="fa35f-104">Enabled for</span></span>    |  <span data-ttu-id="fa35f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="fa35f-105">Public preview</span></span> | <span data-ttu-id="fa35f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="fa35f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="fa35f-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="fa35f-107">End users, automatically</span></span>|<span data-ttu-id="fa35f-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="fa35f-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="fa35f-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="fa35f-109">Feb 1, 2020</span></span>| <span data-ttu-id="fa35f-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="fa35f-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="fa35f-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="fa35f-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="fa35f-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="fa35f-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="fa35f-113">ユーザーは、**プリンター管理**ページで構成された定義済みのプリンターを使用して、デスクトップから直接レポートを印刷できます。</span><span class="sxs-lookup"><span data-stu-id="fa35f-113">Users can print reports directly from the desktop using the predefined printers configured on the **Printer Management** page.</span></span> <span data-ttu-id="fa35f-114">プリンターが選択され、適切に設定されている場合、ファイルのダウンロードやプレビューのナビゲートなどの追加手順は不要です。</span><span class="sxs-lookup"><span data-stu-id="fa35f-114">If the printers are selected and set up properly, then no additional steps, such as downloading files or navigating through previews, are necessary.</span></span> <span data-ttu-id="fa35f-115">さらに、管理者は特定のタスク、ユーザー、またはより複雑なプリンター設定用に印刷ジョブを構成できます。</span><span class="sxs-lookup"><span data-stu-id="fa35f-115">In addition, administrators have the power to configure print jobs for specific tasks, users, or for more complex printer setups.</span></span> 

<span data-ttu-id="fa35f-116">ラベルと梱包明細を別々のプリンターに送信する必要がある複雑な印刷シナリオは、多くの企業で一般的です。</span><span class="sxs-lookup"><span data-stu-id="fa35f-116">Complex printing scenarios where labels must be sent to one printer and a packing slip to another are common in many businesses.</span></span> <span data-ttu-id="fa35f-117">ユーザーは、そのようなフローを記述する特定のプロパティを構成、保存、保持できる機能と、各レポートをあらかじめ定義したプリンターに直接印刷できる機能を求めています。</span><span class="sxs-lookup"><span data-stu-id="fa35f-117">Users expect to be able to configure, save, and retain certain properties describing such flows, and they expect to print each report directly to a predefined printer.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="fa35f-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="fa35f-118">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="fa35f-119">最新のデスクトップ クライアントからプリンターへの直接印刷が可能になりました。</span><span class="sxs-lookup"><span data-stu-id="fa35f-119">Printing directly to a printer is now possible from the modern desktop clients.</span></span> <span data-ttu-id="fa35f-120">**プリンター管理** ページでの設定により、拡張機能で定義されているクラウド プリンターも含めてどのデバイスで印刷を行うかを制御できます。</span><span class="sxs-lookup"><span data-stu-id="fa35f-120">The setup that you make on the **Printer Management** page allows you to control which device to print to, including to cloud printers as defined by extensions.</span></span> <span data-ttu-id="fa35f-121">Business Central の最新のクライアントを使用している場合、ブラウザーで作業しているユーザーは、各レポートに対してプリンター選択を設定して、ドキュメント、ラベル、その他のコンテンツが選択したプリンターで自動的に印刷されるようにできます。</span><span class="sxs-lookup"><span data-stu-id="fa35f-121">Using the Business Central modern clients, users who work in the browser can set up a printer selection for each report so that documents, labels, and other content are printed automatically on the selected printer.</span></span> <span data-ttu-id="fa35f-122">管理者は、たとえば各プリンターに対してフレンドリ名を作成し、既定値を設定して、プリンター (クラウド プリンターを含む) のリストを管理できます。</span><span class="sxs-lookup"><span data-stu-id="fa35f-122">Administrators can manage a list of printers (including cloud printers), for example, by creating a friendly name for each and setting defaults.</span></span> <span data-ttu-id="fa35f-123">さらに、オンプレミスのインストールの場合は、サーバーがアクセスできるすべてのネットワーク プリンターを **プリンター管理** ページで利用できます。</span><span class="sxs-lookup"><span data-stu-id="fa35f-123">Additionally, for on-premises installations, any network printer that the server has access to will be available on the **Printer Management** page.</span></span>

<span data-ttu-id="fa35f-124">このバージョンでは、事前定義された**メール プリンター**拡張機能がインストールされ、お客様が使用できるようになっています。</span><span class="sxs-lookup"><span data-stu-id="fa35f-124">In this version, a predefined **Email Printer** extension is installed and ready for customers to use.</span></span> <span data-ttu-id="fa35f-125">これは、電子メール印刷シナリオを可能にする主要なプリンター メーカーをサポートします。</span><span class="sxs-lookup"><span data-stu-id="fa35f-125">This supports major printer manufacturers that enable email printing scenarios.</span></span> <span data-ttu-id="fa35f-126">Microsoft とパートナーの両方が、追加のクラウド印刷テクノロジー用の追加の拡張機能を作成しています。</span><span class="sxs-lookup"><span data-stu-id="fa35f-126">Both Microsoft and partners are creating additional extensions for additional cloud printing technologies.</span></span> <span data-ttu-id="fa35f-127">それらは AppSource ですぐに見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="fa35f-127">Those can be found on AppSource soon.</span></span>
<!--feature detail end -->

<span data-ttu-id="fa35f-128">![[プリンター管理] ページ](media/printer-management.png "[プリンター管理] ページ")</span><span class="sxs-lookup"><span data-stu-id="fa35f-128">![Printer Management page](media/printer-management.png "Printer Management page")</span></span>
<!-- Picture 1 -->





## <a name="tell-us-what-you-think"></a><span data-ttu-id="fa35f-129">フィードバック</span><span class="sxs-lookup"><span data-stu-id="fa35f-129">Tell us what you think</span></span>
<span data-ttu-id="fa35f-130">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="fa35f-130">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="fa35f-131">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="fa35f-131">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="fa35f-132">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="fa35f-132">Thank you for your idea</span></span>
<span data-ttu-id="fa35f-133">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=445a8a96-1cb3-e911-b083-0003ff6889b9)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="fa35f-133">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=445a8a96-1cb3-e911-b083-0003ff6889b9).</span></span> <span data-ttu-id="fa35f-134">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="fa35f-134">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="fa35f-135">関連項目</span><span class="sxs-lookup"><span data-stu-id="fa35f-135">See also</span></span>

<!--docs start-->
<span data-ttu-id="fa35f-136">[プリンターの設定](https://docs.microsoft.com/dynamics365/business-central/ui-specify-printer-selection-reports) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="fa35f-136">[Set Up Printers](https://docs.microsoft.com/dynamics365/business-central/ui-specify-printer-selection-reports) (docs)</span></span>
<!--docs end-->
