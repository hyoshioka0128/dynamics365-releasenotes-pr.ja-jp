---
title: 高度なプリンター選択で非対話型印刷を有効にする
description: ユーザーはオンラインとオンプレミスの両方で、各レポートのプリンター選択を定義し、あらかじめ定義したプリンターを使用してレポートを印刷することができます。
author: kotelko
ms.reviewer: sgroespe
ms.date: 12/10/2019
ms.assetid: 5f638301-24cb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: ddc90642fa9ed7ada973160acdc71f287b491d6f
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986670"
---
# <a name="enable-non-interactive-printing-with-advanced-printer-selection"></a><span data-ttu-id="fd5b3-103">高度なプリンター選択で非対話型印刷を有効にする</span><span class="sxs-lookup"><span data-stu-id="fd5b3-103">Enable non-interactive printing with advanced printer selection</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="fd5b3-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="fd5b3-104">Enabled for</span></span>    |  <span data-ttu-id="fd5b3-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="fd5b3-105">Public preview</span></span> | <span data-ttu-id="fd5b3-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="fd5b3-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="fd5b3-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="fd5b3-107">End users, automatically</span></span>|<span data-ttu-id="fd5b3-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="fd5b3-108">Feb 2020</span></span>| <span data-ttu-id="fd5b3-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="fd5b3-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="fd5b3-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="fd5b3-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="fd5b3-111">ユーザーは、**プリンターの選択**ページで構成された定義済みのプリンターを使用して、デスクトップから直接レポートを印刷できます。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-111">Users can print reports directly from the desktop using the predefined printers configured on the **Printer Selection** page.</span></span> <span data-ttu-id="fd5b3-112">プリンターが選択され、適切に設定されている場合、ファイルのダウンロードやプレビューのナビゲートなどの追加手順は不要です。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-112">If the printers are selected and set up properly, then no additional steps, such as downloading files or navigating through previews, are necessary.</span></span> <span data-ttu-id="fd5b3-113">さらに、管理者は特定のタスク、ユーザー、またはより複雑なプリンター設定用に印刷ジョブを構成できるようになります。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-113">In addition, administrators get the power to configure print jobs for specific tasks, users, or for more complex printer setups.</span></span> 

<span data-ttu-id="fd5b3-114">ラベルと梱包明細を別々のプリンターに送信する必要がある複雑な印刷シナリオは、多くの企業で一般的です。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-114">Complex printing scenarios where labels must be sent to one printer and a packing slip to another are common in many businesses.</span></span> <span data-ttu-id="fd5b3-115">ユーザーは、そのようなフローを記述する特定のプロパティを構成、保存、保持できる機能と、各レポートをあらかじめ定義したプリンターに直接印刷できる機能を求めています。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-115">Users expect to be able configure, save, and retain certain properties describing such flows, and they expect to print each report directly to a predefined printer.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="fd5b3-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="fd5b3-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="fd5b3-117">最新のデスクトップ クライアントからプリンターへの直接印刷が可能になりました。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-117">Printing directly to a printer is now possible from the modern desktop clients.</span></span> <span data-ttu-id="fd5b3-118">**プリンターの選択**ページでの設定により、拡張機能で定義されているクラウド プリンターも含めてどのデバイスで印刷を行うかを制御できます。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-118">The setup that you make on the **Printer Selection** page allows you to control which device to print to, including to cloud printers as defined by extensions.</span></span> <span data-ttu-id="fd5b3-119">Business Central の最新のクライアントを使用している場合、ブラウザーで作業しているユーザーは、各レポートに対してプリンター選択を設定して、ドキュメント、ラベル、その他のコンテンツが選択したプリンターで自動的に印刷されるようにできます。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-119">Using the Business Central modern clients, users who work in the browser can set up a printer selection for each report so that documents, labels, and other content are printed automatically on the selected printer.</span></span> <span data-ttu-id="fd5b3-120">管理者は、たとえば各プリンターに対してフレンドリ名を作成し、既定値を設定して、プリンター (クラウド プリンターを含む) のリストを管理できます。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-120">Administrators can manage a list of printers (including cloud printers)—for example, creating a friendly name for each and setting defaults.</span></span> <span data-ttu-id="fd5b3-121">さらに、オンプレミスのインストールの場合は、サーバーがアクセスできるすべてのネットワーク プリンターをプリンターの選択ページで利用できます。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-121">Additionally, for on-premises installations, any network printer that the server has access to would be available in the printer selection page.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="fd5b3-122">フィードバック</span><span class="sxs-lookup"><span data-stu-id="fd5b3-122">Tell us what you think</span></span>
<span data-ttu-id="fd5b3-123">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-123">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="fd5b3-124">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-124">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="fd5b3-125">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="fd5b3-125">Thank you for your idea</span></span>
<span data-ttu-id="fd5b3-126">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=445a8a96-1cb3-e911-b083-0003ff6889b9)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-126">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=445a8a96-1cb3-e911-b083-0003ff6889b9).</span></span> <span data-ttu-id="fd5b3-127">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="fd5b3-127">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>
