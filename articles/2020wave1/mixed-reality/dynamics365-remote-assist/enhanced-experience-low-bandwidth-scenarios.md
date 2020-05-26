---
title: 低帯域幅シナリオでのエクスペリエンスの強化
description: Remote Assist ユーザーとリモートの利害関係者は、高品質の静止画像に注釈を付けて OneDrive に保存することにより、低帯域幅のシナリオでシームレスに共同作業を行います。
author: relnotes
ms.reviewer: krbjoran
ms.date: 05/01/2020
ms.assetid: c819bc2d-f388-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: sopsun
dynamics365pdf: true
ms.openlocfilehash: 025ad1d84df392b5d0e3ac09deabec2aa674688a
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350915"
---
# <a name="enhanced-experience-in-low-bandwidth-scenarios"></a><span data-ttu-id="9a0ee-103">低帯域幅シナリオでのエクスペリエンスの強化</span><span class="sxs-lookup"><span data-stu-id="9a0ee-103">Enhanced experience in low bandwidth scenarios</span></span>
[!include[mixed-reality/dynamics365-remote-assist banner](../includes/mixed-reality/dynamics365-remote-assist.md)]

| <span data-ttu-id="9a0ee-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9a0ee-104">Enabled for</span></span>    |  <span data-ttu-id="9a0ee-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9a0ee-105">Public preview</span></span> | <span data-ttu-id="9a0ee-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="9a0ee-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="9a0ee-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="9a0ee-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="9a0ee-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="9a0ee-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="9a0ee-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9a0ee-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9a0ee-110">第一線の作業者は、工場現場や、ネットワーク接続状況の良くないリモート サイトにいることがあります。</span><span class="sxs-lookup"><span data-stu-id="9a0ee-110">First-line workers might work on factory floors or in remote locations with poor network connectivity.</span></span> <span data-ttu-id="9a0ee-111">以前は、これらのシナリオでは、第一線の作業者とリモートの共同作業者がリアルタイムでの問題のトラブルシューティングと解決に問題を抱えていました。</span><span class="sxs-lookup"><span data-stu-id="9a0ee-111">Previously, in these scenarios, first-line workers and remote collaborators would have issues troubleshooting and resolving problems in real time.</span></span> <span data-ttu-id="9a0ee-112">2 月に、このシナリオのモバイル ユーザー向けの初期機能をリリースし、現在は強化されて HoloLens に拡張されています。</span><span class="sxs-lookup"><span data-stu-id="9a0ee-112">In February, we released initial capabilities for mobile users in this scenario that are now enhanced and extended to HoloLens.</span></span> <span data-ttu-id="9a0ee-113">HoloLens の第一線の従業員は、低帯域幅のシナリオでもリモートの共同編集者と問題について話し合い、診断し、解決できます。また、すべてのプラットフォームで将来参照できるように、環境の高品質の画像を保存することもできます。</span><span class="sxs-lookup"><span data-stu-id="9a0ee-113">Now, HoloLens first-line workers can discuss, diagnose, and resolve issues with remote collaborators even in low bandwidth scenarios, and they can also save high-quality images of their environment for future reference in all platforms.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9a0ee-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9a0ee-114">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="9a0ee-115">低帯域幅環境では、Remote Assist ユーザーは、送信ビデオ フィードを凍結するように求められます。</span><span class="sxs-lookup"><span data-stu-id="9a0ee-115">In low bandwidth environments, the Remote Assist user is prompted to freeze their outgoing video feed.</span></span> <span data-ttu-id="9a0ee-116">通話参加者は高品質の画像を表示して注釈を付け、注釈はリアルタイムで表示されます。</span><span class="sxs-lookup"><span data-stu-id="9a0ee-116">Call participants will see and annotate a high-quality image, and the annotations will appear in real time.</span></span> 
- <span data-ttu-id="9a0ee-117">Remote Assist Mobile ユーザーは、2D スナップショット機能を利用して高品質の画像を共有します。</span><span class="sxs-lookup"><span data-stu-id="9a0ee-117">Remote Assist mobile users leverage the 2D snapshot feature to share a high-quality image.</span></span> <span data-ttu-id="9a0ee-118">通話参加者が画像の編集を完了した後、Remote Assist Mobile ユーザーは画像をローカル デバイスまたは OneDrive に保存できます。</span><span class="sxs-lookup"><span data-stu-id="9a0ee-118">After call participants finish editing the image, the Remote Assist mobile user can save it to their local device or OneDrive.</span></span>
- <span data-ttu-id="9a0ee-119">Remote Assist HoloLens ユーザーは、フレームの固定機能を利用して高品質の画像を共有します。</span><span class="sxs-lookup"><span data-stu-id="9a0ee-119">Remote Assist HoloLens users leverage the freeze frame feature to share a high-quality image.</span></span> <span data-ttu-id="9a0ee-120">通話参加者が画像の編集を終了した後、Remote Assist HoloLens ユーザーは注釈のスナップショットを取得して OneDrive に保存できます。</span><span class="sxs-lookup"><span data-stu-id="9a0ee-120">After call participants finish editing the image, the Remote Assist HoloLens user can take a snapshot of the annotations and save it to OneDrive.</span></span>
<!--feature detail end -->









