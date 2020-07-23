---
title: シームレスで信頼性の高い接続損失管理
description: この機能により、ロジックを拡張して信頼性を向上させるためのオフライン機能が強化されます。
author: relnotes
ms.reviewer: josaw
ms.date: 05/26/2020
ms.assetid: 833937ea-c8fa-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: 6449d438d08f837bd0aa80aa7954a7ec51a930e5
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3415723"
---
# <a name="seamless-and-reliable-connectivity-loss-management"></a><span data-ttu-id="47065-103">シームレスで信頼性の高い接続損失管理</span><span class="sxs-lookup"><span data-stu-id="47065-103">Seamless and reliable connectivity loss management</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="47065-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="47065-104">Enabled for</span></span>    |  <span data-ttu-id="47065-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="47065-105">Public preview</span></span> | <span data-ttu-id="47065-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="47065-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="47065-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="47065-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="47065-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="47065-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="47065-109">2020 年 5 月 18 日</span><span class="sxs-lookup"><span data-stu-id="47065-109">May 18, 2020</span></span>| <span data-ttu-id="47065-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="47065-110">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="47065-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="47065-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="47065-112">Microsoft のリアルタイム トランザクション サービス (RTS) コンポーネントは、さまざまなチャネル (販売時点管理や eコマースなど) にサービスを提供する Commerce Server (旧 Retail サーバー) と Commerce Headquarters 間の主要な接続ポイントです。</span><span class="sxs-lookup"><span data-stu-id="47065-112">Our Real-time Transaction Service (RTS) component is the main connection point between Commerce Server (formerly Retail Server), serving various channels (for example, point of sale and e-commerce) and the Commerce headquarters.</span></span>

<span data-ttu-id="47065-113">いくつかのパフォーマンスと信頼性のシナリオでは、信頼性を最大化するための追加ロジックにより改善が可能です。</span><span class="sxs-lookup"><span data-stu-id="47065-113">There are multiple performance and reliability scenarios that could be improved with additional logic to maximize reliability.</span></span> <span data-ttu-id="47065-114">焦点となるのは、必要なときに有意義なメッセージを提供し、可能な限りシームレスに機能することです。</span><span class="sxs-lookup"><span data-stu-id="47065-114">The focus is to provide meaningful messages where necessary and to function seamlessly whenever possible.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="47065-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="47065-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="47065-116">この機能には、次の領域でのいくつかの独立した改善が含まれます。</span><span class="sxs-lookup"><span data-stu-id="47065-116">This feature will contain several independent improvements in the following areas:</span></span>

- <span data-ttu-id="47065-117">Commerce Server にシステム上の問題がある場合は、シームレスな Modern POS (MPOS) オフラインをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="47065-117">Ensure seamless Modern point of sale (MPOS) offline is triggered when there are systemic issues on the Commerce Server.</span></span> <span data-ttu-id="47065-118">たとえば、チャネル DB がダウンした場合にオフライン機能をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="47065-118">For example, trigger offline functionality if the channel DB is down.</span></span>

- <span data-ttu-id="47065-119">シームレスなオフラインの可用性の設計を改善し、信頼性を高めます。</span><span class="sxs-lookup"><span data-stu-id="47065-119">Improve design for seamless offline availability, so that it is more reliable.</span></span>
<!--feature detail end -->









