---
title: デバイスの向きに関連するモバイル アクセシビリティの強化
description: タブレットと携帯電話でのアクセシビリティが強化され、ユーザーはデバイスの向きに関係なくすべての関連情報にアクセスできるようになります。
author: kotelko
ms.reviewer: jswymer
ms.date: 04/07/2020
ms.assetid: 47172681-b016-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: d27fcd64391cbaa394d1270d918ce99ff98b80f0
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255064"
---
# <a name="enhanced-mobile-accessibility-related-to-device-orientation"></a><span data-ttu-id="5fe04-103">デバイスの向きに関連するモバイル アクセシビリティの強化</span><span class="sxs-lookup"><span data-stu-id="5fe04-103">Enhanced mobile accessibility related to device orientation</span></span>


| <span data-ttu-id="5fe04-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="5fe04-104">Enabled for</span></span>    |  <span data-ttu-id="5fe04-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5fe04-105">Public preview</span></span> | <span data-ttu-id="5fe04-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="5fe04-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5fe04-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="5fe04-107">End users, automatically</span></span>|<span data-ttu-id="5fe04-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5fe04-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5fe04-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5fe04-109">Feb 1, 2020</span></span>| <span data-ttu-id="5fe04-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5fe04-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5fe04-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5fe04-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="5fe04-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5fe04-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5fe04-113">外出中のユーザーは、デバイスを操作したり大きくスクロールしたりせずにすべての関連情報にすばやくアクセスできる必要があります。</span><span class="sxs-lookup"><span data-stu-id="5fe04-113">Users on the road must have quick access to all relevant information without having to manipulate the device or scroll extensively.</span></span> <span data-ttu-id="5fe04-114">タブレットや携帯電話のユーザーが FactBox 内の関連情報やロール センターの追加のキューに簡単かつ迅速にアクセスでき、ロール センターからページに簡単に移動できるようになると、生産性と利便性が向上します。</span><span class="sxs-lookup"><span data-stu-id="5fe04-114">Users on tablets and phones are more productive and feel more empowered when they have easy and fast access to related information in FactBoxes or to additional cues on Role Centers and when they can easily navigate to pages from the Role Center.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5fe04-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5fe04-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5fe04-116">この機能強化では、(ページの横または上部に) 小さなシェブロンを表示して、デバイスの向きに関係なく FactBoxes 内の情報にアクセスできるようにします。これによりユーザーは関連情報を画面上に "プル" できます。</span><span class="sxs-lookup"><span data-stu-id="5fe04-116">This enhancement makes access to information in FactBoxes reachable regardless of the device orientation by displaying a small chevron (either on the side or at the top of the page), allowing the user to "pull" the related information onto the screen.</span></span> <span data-ttu-id="5fe04-117">以前のリリースでは、このアクションは特定の画面の向きでのみ利用可能でした。</span><span class="sxs-lookup"><span data-stu-id="5fe04-117">In previous releases, this action was only available with certain screen orientations.</span></span> <span data-ttu-id="5fe04-118">今後は、どのデバイスでも、どこでも利用可能になります。</span><span class="sxs-lookup"><span data-stu-id="5fe04-118">Now, it is available everywhere on any device.</span></span> <span data-ttu-id="5fe04-119">携帯電話が車内のホルダーに装着されている (運転中ではない) 一般的なシナリオで、オペレーターが電話をホルダーに入れたままで顧客に関する関連情報にすばやくアクセスできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5fe04-119">In the common scenario where a mobile phone is mounted on a holder in a vehicle (not driving), it is now possible for the operator to quickly access related information about a customer while the phone is in the holder.</span></span>

<span data-ttu-id="5fe04-120">この機能強化に関連するもう 1 つの変更は、タブレットの横モードでのロール センター ビューの再設計です。</span><span class="sxs-lookup"><span data-stu-id="5fe04-120">Another change related to this enhancement is the redesigned Role Center view in Landscape mode on tablets.</span></span> <span data-ttu-id="5fe04-121">ナビゲーション コントロールが左側のウィンドウに移動され、ユーザーは別のページにすばやくジャンプしてタスクを開始できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5fe04-121">The navigation controls have been moved to the left pane, allowing users to quickly jump to a different page and get started with tasks.</span></span> <span data-ttu-id="5fe04-122">以前のリリースでは、これはメニューの下に隠れていました。</span><span class="sxs-lookup"><span data-stu-id="5fe04-122">In previous releases, this was hidden under a menu.</span></span> <span data-ttu-id="5fe04-123">また、この変更により、ユーザーと管理者はホーム グループに (ブックマークなどによって) さらに要素を追加して、より充実したナビゲーションでロール センターをパーソナライズできるようになります。</span><span class="sxs-lookup"><span data-stu-id="5fe04-123">The change also allows users and administrators to personalize a Role Center with richer navigation by adding more elements to the Home group (for example, by bookmarking them).</span></span> <span data-ttu-id="5fe04-124">その結果、キューが右側のウィンドウに移動され、ユーザーはロール センターのコンテンツ全体をスクロールできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5fe04-124">As a result, the cues have been moved to the right pane, allowing users to scroll the entire Role Center content.</span></span>
<!--feature detail end -->

<span data-ttu-id="5fe04-125">![横モードのタブレットのロール センター](media/new-tablet-view-ipad-air.png "横モードのタブレットのロール センター")</span><span class="sxs-lookup"><span data-stu-id="5fe04-125">![Role Center on a tablet in landscape mode](media/new-tablet-view-ipad-air.png "Role Center on a tablet in landscape mode")</span></span>
<!-- Picture 1 -->





## <a name="tell-us-what-you-think"></a><span data-ttu-id="5fe04-126">フィードバック</span><span class="sxs-lookup"><span data-stu-id="5fe04-126">Tell us what you think</span></span>
<span data-ttu-id="5fe04-127">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="5fe04-127">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="5fe04-128">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="5fe04-128">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="5fe04-129">関連項目</span><span class="sxs-lookup"><span data-stu-id="5fe04-129">See also</span></span>

<!--docs start-->
<span data-ttu-id="5fe04-130">[Business Central のドキュメント](https://docs.microsoft.com/dynamics365/business-central/) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="5fe04-130">[Business Central documentation](https://docs.microsoft.com/dynamics365/business-central/) (docs)</span></span>
<!--docs end-->
