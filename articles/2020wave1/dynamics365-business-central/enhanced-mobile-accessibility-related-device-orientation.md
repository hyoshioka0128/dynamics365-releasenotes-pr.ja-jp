---
title: デバイスの向きに関連するモバイル アクセシビリティの強化
description: タブレットと携帯電話でのアクセシビリティが強化され、ユーザーはデバイスの向きに関係なくすべての関連情報にアクセスできるようになります。
author: kotelko
ms.reviewer: sgroespe
ms.date: 12/09/2019
ms.assetid: 47172681-b016-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: 0bc46a1d16e4852b36712ba4fed97a6c139c6fed
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986668"
---
# <a name="enhanced-mobile-accessibility-related-to-device-orientation"></a><span data-ttu-id="f2125-103">デバイスの向きに関連するモバイル アクセシビリティの強化</span><span class="sxs-lookup"><span data-stu-id="f2125-103">Enhanced mobile accessibility related to device orientation</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="f2125-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f2125-104">Enabled for</span></span>    |  <span data-ttu-id="f2125-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f2125-105">Public preview</span></span> | <span data-ttu-id="f2125-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f2125-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f2125-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="f2125-107">End users, automatically</span></span>|<span data-ttu-id="f2125-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="f2125-108">Feb 2020</span></span>| <span data-ttu-id="f2125-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="f2125-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="f2125-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f2125-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f2125-111">外出中のユーザーは、デバイスを操作したり大きくスクロールしたりせずにすべての関連情報にすばやくアクセスできる必要があります。</span><span class="sxs-lookup"><span data-stu-id="f2125-111">Users on the road must have quick access to all relevant information without having to manipulate the device or scroll extensively.</span></span> <span data-ttu-id="f2125-112">タブレットや携帯電話のユーザーが FactBox 内の関連情報やロール センターの追加のキューに簡単かつ迅速にアクセスでき、ロール センターからページに簡単に移動できるようになると、生産性と利便性が向上します。</span><span class="sxs-lookup"><span data-stu-id="f2125-112">Users on tablets and phones are more productive and feel more empowered when they have easy and fast access to related information in FactBoxes or to additional cues on Role Centers and when they can easily navigate to pages from the Role Center.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f2125-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f2125-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f2125-114">この機能強化では、(ページの横または上部に) 小さなシェブロンを表示して、デバイスの向きに関係なく FactBoxes 内の情報にアクセスできるようにします。これによりユーザーは関連情報を画面上に "プル" できます。</span><span class="sxs-lookup"><span data-stu-id="f2125-114">This enhancement makes access to information in FactBoxes reachable regardless of the device orientation by displaying a small chevron (either on the side or at the top of the page), allowing the user to "pull” the related information onto the screen.</span></span> <span data-ttu-id="f2125-115">以前のリリースでは、このアクションは特定の画面の向きでのみ利用可能でした。</span><span class="sxs-lookup"><span data-stu-id="f2125-115">In previous releases, this action was only available with certain screen orientations.</span></span> <span data-ttu-id="f2125-116">今後は、どのデバイスでも、どこでも利用可能になります。</span><span class="sxs-lookup"><span data-stu-id="f2125-116">Now, it is available everywhere on any device.</span></span> <span data-ttu-id="f2125-117">携帯電話が車内のホルダーに装着されている (運転中ではない) 一般的なシナリオで、オペレーターが電話をホルダーに入れたままで顧客に関する関連情報にすばやくアクセスできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2125-117">In the common scenario where a mobile phone is mounted on a holder in a vehicle (not driving), it is now possible for the operator to quickly access related information about a customer while the phone is in the holder.</span></span>

<span data-ttu-id="f2125-118">この機能強化に関連するもう 1 つの変更は、タブレットの横モードでのロール センター ビューの再設計です。</span><span class="sxs-lookup"><span data-stu-id="f2125-118">Another change related to this enhancement is the redesigned Role Center view in Landscape mode on tablets.</span></span> <span data-ttu-id="f2125-119">ナビゲーション コントロールが左側のウィンドウに移動され、ユーザーは別のページにすばやくジャンプしてタスクを開始できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2125-119">The navigation controls have been moved to the left pane, allowing users to quickly jump to a different page and get started with tasks.</span></span> <span data-ttu-id="f2125-120">以前のリリースでは、これはメニューの下に隠れていました。</span><span class="sxs-lookup"><span data-stu-id="f2125-120">In previous releases, this was hidden under a menu.</span></span> <span data-ttu-id="f2125-121">また、この変更により、ユーザーと管理者はホーム グループに (ブックマークなどによって) さらに要素を追加して、より充実したナビゲーションでロール センターをパーソナライズできるようになります。</span><span class="sxs-lookup"><span data-stu-id="f2125-121">The change also allows users and administrators to personalize a Role Center with richer navigation by adding more elements to the Home group (for example, by bookmarking them).</span></span> <span data-ttu-id="f2125-122">その結果、キューが右側のウィンドウに移動され、ユーザーはロール センターのコンテンツ全体をスクロールできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2125-122">As a result, the cues have been moved to the right pane, allowing users to scroll the entire Role Center content.</span></span> 
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="f2125-123">フィードバック</span><span class="sxs-lookup"><span data-stu-id="f2125-123">Tell us what you think</span></span>
<span data-ttu-id="f2125-124">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="f2125-124">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="f2125-125">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="f2125-125">Use the forum at https://aka.ms/bcideas.</span></span>



