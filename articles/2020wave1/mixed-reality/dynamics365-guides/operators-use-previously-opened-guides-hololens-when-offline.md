---
title: オペレーターは HoloLens で以前に開いたガイドをオフライン時に使用できる
description: オペレーターは、インターネット接続が遅いか利用できない環境で HoloLens アプリのガイドを使用できるようになります。 オペレーターがガイドを開くと、ガイドが自動的にダウンロードされます。 最近開いた 12 個のガイドがオフラインで利用可能になります。
author: relnotes
ms.reviewer: v-brycho
ms.date: 03/25/2020
ms.assetid: df27ee0f-f869-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: algodin
dynamics365pdf: true
ms.openlocfilehash: f88d028908b94d01819678f68a3e3ec6aa9c022c
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219688"
---
# <a name="operators-can-use-any-previously-opened-guides-on-hololens-when-offline"></a><span data-ttu-id="e9d1a-105">オペレーターは HoloLens で以前に開いたガイドをオフライン時に使用できる</span><span class="sxs-lookup"><span data-stu-id="e9d1a-105">Operators can use any previously opened guides on HoloLens when offline</span></span>
[!include[mixed-reality/dynamics365-guides banner](../includes/mixed-reality/dynamics365-guides.md)]

| <span data-ttu-id="e9d1a-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="e9d1a-106">Enabled for</span></span>    |  <span data-ttu-id="e9d1a-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e9d1a-107">Public preview</span></span> | <span data-ttu-id="e9d1a-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="e9d1a-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="e9d1a-109">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="e9d1a-109">End users, automatically</span></span>|-| <span data-ttu-id="e9d1a-110">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="e9d1a-110">Jun 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="e9d1a-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e9d1a-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e9d1a-112">この機能を使用すると、オペレーターは工場のフロアにいるときやフィールド サービス通話中など、インターネット接続が遅いか利用できない環境で作業を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="e9d1a-112">This feature enables operators to do their work in low- or no-internet environments, such as a factory floor or when on field service calls.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e9d1a-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e9d1a-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e9d1a-114">オペレーターが HoloLens でガイドを開くと、デバイスにガイドが自動的にダウンロードされます。</span><span class="sxs-lookup"><span data-stu-id="e9d1a-114">When an operator opens a guide on HoloLens, the guide will be downloaded to the device automatically.</span></span> <span data-ttu-id="e9d1a-115">オペレーターのインターネット接続が失われるか接続状態が悪くなると、HoloLens アプリが自動的に**オフライン** モードに切り替わり、オフラインであることが指示カードの上部にあるバナーでオペレーターに通知されます。</span><span class="sxs-lookup"><span data-stu-id="e9d1a-115">If the operator loses their internet connection or if they have a poor connection, the HoloLens app will automatically switch to **Offline** mode, and a banner at the top of the instruction card will inform the operator that they’re offline.</span></span> 

<span data-ttu-id="e9d1a-116">オフライン時には、オフラインで利用できるすべてのガイドが**すべて**タブの下に表示されます。ここには、そのデバイスで以前に開いたガイドが表示されます。</span><span class="sxs-lookup"><span data-stu-id="e9d1a-116">When offline, any guide that’s available for offline use will appear under the **All** tab, which shows previously opened guides for that device.</span></span> <span data-ttu-id="e9d1a-117">特定のデバイスで最近開いた 12 個のガイドが、オフラインで利用可能になります。</span><span class="sxs-lookup"><span data-stu-id="e9d1a-117">The 12 most recently opened guides on a specific device will be available offline.</span></span> <span data-ttu-id="e9d1a-118">デバイスが共有されている場合は、そのデバイスの各アカウントについて、最近開いた 12 個のガイドが利用可能になります。</span><span class="sxs-lookup"><span data-stu-id="e9d1a-118">If the device is shared, the 12 most recently opened guides will be available for each account on that device.</span></span>

<!--feature detail end -->









