---
title: HoloLens 2 で Mixed Reality キャプチャを行う際のホログラムと現実世界との位置合わせの向上
description: HoloLens からの Mixed Reality キャプチャで、ホログラムの位置合わせが向上し、ユーザーがデバイスで体験している内容が反映されます。
author: relnotes
ms.reviewer: v-brycho
ms.date: 06/23/2020
ms.assetid: 3db1104c-05a1-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: algodin
dynamics365pdf: true
ms.openlocfilehash: ef38353801b35e52a8964f7504c450ce38a971e4
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3522691"
---
# <a name="improved-hologram-alignment-with-real-world-during-mixed-reality-capture-on-hololens-2"></a><span data-ttu-id="166f4-103">HoloLens 2 で Mixed Reality キャプチャを行う際のホログラムと現実世界との位置合わせの向上</span><span class="sxs-lookup"><span data-stu-id="166f4-103">Improved hologram alignment with real world during mixed-reality capture on HoloLens 2</span></span>
[!include[mixed-reality/dynamics365-guides banner](../includes/mixed-reality/dynamics365-guides.md)]

| <span data-ttu-id="166f4-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="166f4-104">Enabled for</span></span>    |  <span data-ttu-id="166f4-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="166f4-105">Public preview</span></span> | <span data-ttu-id="166f4-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="166f4-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="166f4-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="166f4-107">End users, automatically</span></span>|-| <span data-ttu-id="166f4-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="166f4-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="166f4-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="166f4-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="166f4-110">お客様は、HoloLens エクスペリエンスを紹介する、より高品質のビデオを作成できます。</span><span class="sxs-lookup"><span data-stu-id="166f4-110">Customers can make higher-quality videos that showcase the HoloLens experience.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="166f4-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="166f4-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="166f4-112">Mixed Reality キャプチャ (MRC) では、ユーザーが HoloLens 2 を使用しているときに体験している内容への忠実度がより高くなります。</span><span class="sxs-lookup"><span data-stu-id="166f4-112">Mixed-reality capture (MRC) will have higher fidelity to what users are experiencing when using HoloLens 2.</span></span> <span data-ttu-id="166f4-113">作成者がワールド内に配置したホログラムは適切にレンダリングされ、位置合わせされます。</span><span class="sxs-lookup"><span data-stu-id="166f4-113">Holograms placed by authors in-world are properly rendered and aligned.</span></span>

<span data-ttu-id="166f4-114">Mixed Reality キャプチャの詳細については、「[Mixed Reality の写真とビデオを作成する](https://docs.microsoft.com/hololens/holographic-photos-and-videos)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="166f4-114">To learn more about mixed-reality capture, see [Create mixed reality photos and videos](https://docs.microsoft.com/hololens/holographic-photos-and-videos).</span></span>
<!--feature detail end -->









