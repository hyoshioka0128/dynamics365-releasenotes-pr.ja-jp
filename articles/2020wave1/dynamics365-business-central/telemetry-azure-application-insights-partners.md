---
title: パートナー向けの Application Insights テレメトリに追加された Web サービス要求とレポートのパフォーマンス
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは Web サービス要求の実行時刻とレポート実行時刻に関するテレメトリを発行します。
author: relnotes
ms.reviewer: jswymer
ms.date: 04/15/2020
ms.assetid: 9cadefe1-eb1b-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 6ece8fe1bae3fc4bfba9d1a9f01994a81d9b226c
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273777"
---
# <a name="performance-of-web-service-requests-and-reports-added-to-application-insights-telemetry-for-partners"></a><span data-ttu-id="2816e-103">パートナー向けの Application Insights テレメトリに追加された Web サービス要求とレポートのパフォーマンス</span><span class="sxs-lookup"><span data-stu-id="2816e-103">Performance of web service requests and reports added to Application Insights telemetry for partners</span></span>


| <span data-ttu-id="2816e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="2816e-104">Enabled for</span></span>    |  <span data-ttu-id="2816e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2816e-105">Public preview</span></span> | <span data-ttu-id="2816e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="2816e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="2816e-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="2816e-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="2816e-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2816e-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2816e-109">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2816e-109">Apr 1, 2020</span></span>| <span data-ttu-id="2816e-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2816e-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2816e-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2816e-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="2816e-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2816e-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="2816e-113">パートナーは Web サービス要求とレポートのパフォーマンスを監視できます。</span><span class="sxs-lookup"><span data-stu-id="2816e-113">Partners can monitor performance of web service requests and reports.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="2816e-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2816e-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="2816e-115">Business Central Server は、Web サービス要求とレポートの実行時刻とタイムアウトに関するテレメトリを発行します。</span><span class="sxs-lookup"><span data-stu-id="2816e-115">The Business Central server will emit telemetry about the execution time and timeouts of web service requests and reports.</span></span> 

<span data-ttu-id="2816e-116">パートナーとお客様はこのデータ使用して、Web サービス要求とレポートによって引き起こされるパフォーマンスの問題について環境を監視し、これらの問題の発生をよりプロアクティブに防ぐことができます。</span><span class="sxs-lookup"><span data-stu-id="2816e-116">Partners and customers can use this data to monitor their environments for performance issues caused by web service requests and reports and be more proactive in preventing these issues from occurring.</span></span>

<span data-ttu-id="2816e-117">[サンプル クエリ](https://github.com/microsoft/BCTech/tree/master/samples/AppInsights/KQL)と[サンプル ダッシュボード](https://github.com/microsoft/BCTech/tree/master/samples/AppInsights/Dashboard)にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="2816e-117">You can access [sample queries](https://github.com/microsoft/BCTech/tree/master/samples/AppInsights/KQL) and [sample dashboards](https://github.com/microsoft/BCTech/tree/master/samples/AppInsights/Dashboard).</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="2816e-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="2816e-118">See also</span></span>

<!--docs start-->
<span data-ttu-id="2816e-119">[テレメトリの監視と分析](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/telemetry-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="2816e-119">[Monitoring and Analyzing Telemetry](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/telemetry-overview) (docs)</span></span>
<!--docs end-->
