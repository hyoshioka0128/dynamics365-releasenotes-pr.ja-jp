---
title: パートナー向け Application Insights のクライアント ページ ビュー テレメトリ
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、クライアントはページ ビューに関するテレメトリを Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 06/25/2020
ms.assetid: f2e1ac5e-6790-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 4bd2ae1d993956d746ba550f4286d2084868c917
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3524114"
---
# <a name="client-page-view-telemetry-in-application-insights-for-partners"></a><span data-ttu-id="6a462-103">パートナー向け Application Insights のクライアント ページ ビュー テレメトリ</span><span class="sxs-lookup"><span data-stu-id="6a462-103">Client page view telemetry in Application Insights for partners</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="6a462-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="6a462-104">Enabled for</span></span>    |  <span data-ttu-id="6a462-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6a462-105">Public preview</span></span> | <span data-ttu-id="6a462-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="6a462-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6a462-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="6a462-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="6a462-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="6a462-108">Jul 2020</span></span>| <span data-ttu-id="6a462-109">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="6a462-109">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="6a462-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="6a462-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="6a462-111">これにより、パートナーと顧客管理者はシステムの使用状況を追跡できます。</span><span class="sxs-lookup"><span data-stu-id="6a462-111">This will enable partners and customer administrators to track usage of the system.</span></span> 

<span data-ttu-id="6a462-112">また、パートナーはページ ビュー シグナルを使用して、ブラウザーやクライアント設定に起因するパフォーマンスの問題のトラブルシューティングを実行できます。</span><span class="sxs-lookup"><span data-stu-id="6a462-112">Also, using the page view signal, a partner can troubleshoot performance problems due to browsers or client settings.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="6a462-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6a462-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6a462-114">2019 年リリース ウェーブ 2 では、テナント管理者は Azure Application Insights キーを指定して、事前定義されたトレース イベントのロギングを有効にできました。</span><span class="sxs-lookup"><span data-stu-id="6a462-114">With 2019 release wave 2, tenant administrators have been able to specify an Azure Application Insights key to enable logging of predefined trace events.</span></span> <span data-ttu-id="6a462-115">これまでは、[aka.ms/bctelemetry](https://aka.ms/bctelemetry) に示されている例のように、サーバーからのトレースのみが送信されていました。</span><span class="sxs-lookup"><span data-stu-id="6a462-115">Until now, only traces from the server have been emitted, such as the examples listed at [aka.ms/bctelemetry](https://aka.ms/bctelemetry).</span></span>

<span data-ttu-id="6a462-116">この変更により、同じチャネルを通じてクライアント テレメトリを利用できるようにする最初のステップが実現しました。</span><span class="sxs-lookup"><span data-stu-id="6a462-116">With this change, the first step of making client telemetry available through the same channel has been achieved.</span></span> <span data-ttu-id="6a462-117">利用可能になる最初のシグナルはページ ビューです。</span><span class="sxs-lookup"><span data-stu-id="6a462-117">The first signal to be made available is page views.</span></span>
<!--feature detail end -->









