---
title: オペレーターは HoloLens で以前に開いたガイドをオフライン時に使用できる
description: オペレーターは、接続が断続的な環境で HoloLens アプリのガイドを使用できるようになります。 オペレーターがガイドを開くと、デバイスにガイドが自動的にダウンロードされます。
author: relnotes
ms.reviewer: v-brycho
ms.date: 06/24/2020
ms.assetid: df27ee0f-f869-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: algodin
dynamics365pdf: true
ms.openlocfilehash: edb8802ae6977de8ffc00a16d89ad2d8cf188560
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3522667"
---
# <a name="operators-can-use-any-previously-opened-guides-on-hololens-when-offline"></a><span data-ttu-id="b8b87-104">オペレーターは HoloLens で以前に開いたガイドをオフライン時に使用できる</span><span class="sxs-lookup"><span data-stu-id="b8b87-104">Operators can use any previously opened guides on HoloLens when offline</span></span>
[!include[mixed-reality/dynamics365-guides banner](../includes/mixed-reality/dynamics365-guides.md)]

| <span data-ttu-id="b8b87-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="b8b87-105">Enabled for</span></span>    |  <span data-ttu-id="b8b87-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b8b87-106">Public preview</span></span> | <span data-ttu-id="b8b87-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="b8b87-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b8b87-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="b8b87-108">End users, automatically</span></span>|-| <span data-ttu-id="b8b87-109">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="b8b87-109">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="b8b87-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b8b87-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b8b87-111">この機能を使用すると、オペレーターは工場のフロアにいるときやフィールド サービス通話中など、インターネット接続が遅いか利用できない環境で作業を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="b8b87-111">This feature enables operators to do their work in low- or no-internet environments, such as a factory floor or when on field service calls.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b8b87-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b8b87-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b8b87-113">オペレーターが HoloLens でガイドを開くと、デバイスにガイドが自動的にダウンロードされます。</span><span class="sxs-lookup"><span data-stu-id="b8b87-113">When an operator opens a guide on HoloLens, the guide will be downloaded to the device automatically.</span></span> <span data-ttu-id="b8b87-114">オペレーターのインターネット接続が失われるか接続状態が悪くなると、HoloLens アプリが自動的に**オフライン** モードに切り替わり、オフラインであることが指示カードの上部にあるバナーでオペレーターに通知されます。</span><span class="sxs-lookup"><span data-stu-id="b8b87-114">If the operator loses their internet connection or if they have a poor connection, the HoloLens app will automatically switch to **Offline** mode, and a banner at the top of the instruction card will inform the operator that they’re offline.</span></span> 

<span data-ttu-id="b8b87-115">オフライン時には、オフラインで利用できるすべてのガイドが**すべて**タブの下に表示されます。ここには、そのデバイスとユーザーが以前に開いたガイドが表示されます。</span><span class="sxs-lookup"><span data-stu-id="b8b87-115">When offline, any guide that’s available for offline use will appear under the **All** tab, which shows previously opened guides for that device and user.</span></span>

<span data-ttu-id="b8b87-116">また、デバイスがオンライン/オフラインのときに作成されたデータが含まれるように Power BI ダッシュボードが更新されました。</span><span class="sxs-lookup"><span data-stu-id="b8b87-116">Power BI dashboards have also been updated to include data created when a device is online and offline.</span></span> <span data-ttu-id="b8b87-117">オフライン データは、デバイスがオンラインに戻るとすぐに表示されます。</span><span class="sxs-lookup"><span data-stu-id="b8b87-117">The offline data appears as soon as a device is back online.</span></span>
<!--feature detail end -->









