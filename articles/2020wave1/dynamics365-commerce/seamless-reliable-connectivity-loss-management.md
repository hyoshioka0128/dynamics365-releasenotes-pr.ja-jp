---
title: シームレスで信頼性の高い接続損失管理
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 01/11/2020
ms.assetid: 833937ea-c8fa-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: 63a25409c992905f134f6ec7178450cfb7202c45
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986637"
---
# <a name="seamless-and-reliable-connectivity-loss-management"></a><span data-ttu-id="a4b35-102">シームレスで信頼性の高い接続損失管理</span><span class="sxs-lookup"><span data-stu-id="a4b35-102">Seamless and reliable connectivity loss management</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="a4b35-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="a4b35-103">Enabled for</span></span>    |  <span data-ttu-id="a4b35-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a4b35-104">Public preview</span></span> | <span data-ttu-id="a4b35-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="a4b35-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a4b35-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a4b35-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="a4b35-107">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="a4b35-107">May 2020</span></span>| <span data-ttu-id="a4b35-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="a4b35-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a4b35-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a4b35-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a4b35-110">Microsoft のリアルタイム トランザクション サービス (RTS) コンポーネントは、さまざまなチャネル (POS (Point of Sale) や 電子商取引など) にサービスを提供する Commerce Server (旧 Retail サーバー) と Commerce Headquarters 間の主要な接続ポイントです。</span><span class="sxs-lookup"><span data-stu-id="a4b35-110">Our Real-time Transaction Service (RTS) component is the main connection point between Commerce Server (formerly Retail Server) serving various channels (for example, point of sale (POS) and e-commerce) and the Commerce headquarters.</span></span>

<span data-ttu-id="a4b35-111">いくつかのパフォーマンスと信頼性のシナリオでは、信頼性を最大化するための追加ロジックにより改善が可能です。</span><span class="sxs-lookup"><span data-stu-id="a4b35-111">There are multiple performance and reliability scenarios that could be improved with additional logic to maximize reliability.</span></span> <span data-ttu-id="a4b35-112">焦点となるのは、必要なときに有意義なメッセージを提供し、可能な限りシームレスに機能することです。</span><span class="sxs-lookup"><span data-stu-id="a4b35-112">The focus is to provide meaningful messages where necessary and to function seamlessly whenever possible.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a4b35-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a4b35-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a4b35-114">この機能には、次の領域でのいくつかの独立した改善が含まれます。</span><span class="sxs-lookup"><span data-stu-id="a4b35-114">This feature will contain several independent improvements in the following areas:</span></span>

- <span data-ttu-id="a4b35-115">Commerce Server (旧 Retail サーバー) にシステム上の問題がある場合は、シームレスな Modern POS (MPOS) オフラインをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="a4b35-115">Ensure seamless Modern POS (MPOS) offline is triggered when there are systemic issues on the Commerce Server (formerly Retail Server).</span></span> <span data-ttu-id="a4b35-116">たとえば、チャネル DB がダウンした場合にオフライン機能をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="a4b35-116">For example, trigger offline functionality if the channel DB is down.</span></span>

- <span data-ttu-id="a4b35-117">シームレスなオフラインの可用性の設計を改善し、信頼性を高めます。</span><span class="sxs-lookup"><span data-stu-id="a4b35-117">Improve design for seamless offline availability so that it is more reliable.</span></span>

- <span data-ttu-id="a4b35-118">デバイスの現在のステータスの詳細を示すダッシュボードの詳細を Headquarters に追加します。</span><span class="sxs-lookup"><span data-stu-id="a4b35-118">Add dashboard details in headquarters that show the current status for devices.</span></span>
<!--feature detail end -->









