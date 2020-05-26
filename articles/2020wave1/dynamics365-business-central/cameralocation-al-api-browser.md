---
title: ブラウザーで利用可能なカメラ/位置 AL API
description: ブラウザーで利用可能なカメラ/位置 AL API。
author: mikebcMSFT
ms.reviewer: solsen
ms.date: 04/07/2020
ms.assetid: 64e0ad63-3c36-ea11-a813-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 66b0d79f3220a8241e4c0515b5307965854d7e70
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255147"
---
# <a name="cameralocation-al-api-available-in-the-browser"></a><span data-ttu-id="90886-103">ブラウザーで利用可能なカメラ/位置 AL API</span><span class="sxs-lookup"><span data-stu-id="90886-103">Camera/location AL API available in the browser</span></span>


| <span data-ttu-id="90886-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="90886-104">Enabled for</span></span>    |  <span data-ttu-id="90886-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="90886-105">Public preview</span></span> | <span data-ttu-id="90886-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="90886-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="90886-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="90886-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="90886-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="90886-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="90886-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="90886-109">Feb 1, 2020</span></span>| <span data-ttu-id="90886-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="90886-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="90886-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="90886-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="90886-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="90886-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="90886-113">ユーザーは、カメラで写真を撮るなど、デバイス ハードウェアを最大限に活用することを最新のアプリに期待しています。</span><span class="sxs-lookup"><span data-stu-id="90886-113">Users expect modern apps to take full advantage of their device hardware, such as taking pictures with their camera.</span></span> <span data-ttu-id="90886-114">これにより、エクスペリエンスが刷新されるだけでなく、適切なシナリオに適用されると、データ入力の時間と労力も削減され、ソースにより近い情報を取得することができます。</span><span class="sxs-lookup"><span data-stu-id="90886-114">Not only does this modernize the experience, but when applied to the right scenarios, it can also reduce time and effort of data entry and help capture information closer to the source.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="90886-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="90886-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="90886-116">開発者は、ブラウザーを介して Business Central にアクセスするときに、プログラムでカメラをアクティブにしたり、AL ベースの API を通じて現在位置の座標を取得したりできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="90886-116">Developers can now programmatically activate the camera or get the current location coordinates through an AL-based API when Business Central is accessed through the browser.</span></span> <span data-ttu-id="90886-117">ブラウザーとアプリの両方がサポートされるので、ユーザーのデバイスとブラウザーがこれらの機能をサポートしている限り、開発者はあらゆるフォーム ファクターでシナリオを確実に強化できます。</span><span class="sxs-lookup"><span data-stu-id="90886-117">With support for both browser and apps, developers can rest assured that their scenarios light up on any form factor, as long as the user's device and browser support those capabilities.</span></span>

<span data-ttu-id="90886-118">![カメラはブラウザーで Business Central によってアクティブ化され、写真を撮る準備ができている](media/camera-snaps-incoming-document.png "カメラはブラウザーで Business Central によってアクティブ化され、写真を撮る準備ができている")</span><span class="sxs-lookup"><span data-stu-id="90886-118">![The camera is activated by Business Central in the browser and ready to snap a photo](media/camera-snaps-incoming-document.png "The camera is activated by Business Central in the browser and ready to snap a photo")</span></span>

### <a name="additional-details"></a><span data-ttu-id="90886-119">追加情報</span><span class="sxs-lookup"><span data-stu-id="90886-119">Additional details</span></span>
- <span data-ttu-id="90886-120">ユーザーはプライバシー設定を引き続き管理し、他の Web サイトと同様にカメラと位置情報へのアクセスを許可または拒否することができます。</span><span class="sxs-lookup"><span data-stu-id="90886-120">Users remain in control of their privacy settings and can choose to grant or deny access to camera and location similar to other websites.</span></span>
- <span data-ttu-id="90886-121">**CameraProvider.IsAvailable** および **LocationProvider.IsAvailable** は、ブラウザーとデバイスで機能がサポートされている場合に、True を返すようになりました。</span><span class="sxs-lookup"><span data-stu-id="90886-121">**CameraProvider.IsAvailable** and **LocationProvider.IsAvailable** now return True if the browser and device support the capability.</span></span>
- <span data-ttu-id="90886-122">カメラには、ビューポートと**使用**および**撮り直し**ボタンが用意されています。</span><span class="sxs-lookup"><span data-stu-id="90886-122">The camera provides a viewport as well as **Use** and **Retake** buttons.</span></span>
- <span data-ttu-id="90886-123">場所は経度と緯度の座標として返されます。</span><span class="sxs-lookup"><span data-stu-id="90886-123">The location is returned as longitude and latitude coordinates.</span></span>

### <a name="try-it-now"></a><span data-ttu-id="90886-124">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="90886-124">Try it now</span></span>
<span data-ttu-id="90886-125">[https://businesscentral.dynamics-tie.com/?page=30](https://businesscentral.dynamics.com/?page=30&mode=edit) でオンライン環境にログインして、写真を撮影してアイテム カードを更新してください。</span><span class="sxs-lookup"><span data-stu-id="90886-125">Experience snapping a photo to update an Item Card, by signing in to your online environment at [https://businesscentral.dynamics-tie.com/?page=30](https://businesscentral.dynamics.com/?page=30&mode=edit).</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="90886-126">フィードバック</span><span class="sxs-lookup"><span data-stu-id="90886-126">Tell us what you think</span></span>
<span data-ttu-id="90886-127">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="90886-127">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="90886-128">フォーラム (https://aka.ms/bcIdeas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="90886-128">Use the forum at https://aka.ms/bcIdeas.</span></span>




## <a name="see-also"></a><span data-ttu-id="90886-129">関連項目</span><span class="sxs-lookup"><span data-stu-id="90886-129">See also</span></span>

<!--docs start-->
<span data-ttu-id="90886-130">[AL でのカメラの実装](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-implement-camera-al) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="90886-130">[Implementing the Camera in AL](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-implement-camera-al) (docs)</span></span>
<!--docs end-->
