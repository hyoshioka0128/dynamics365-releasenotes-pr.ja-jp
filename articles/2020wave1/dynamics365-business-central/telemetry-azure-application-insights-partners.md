---
title: パートナー向けの Application Insights テレメトリに追加された Web サービス要求とレポートのパフォーマンス
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは Web サービス要求の実行時刻とレポート実行時刻に関するテレメトリを発行します。
author: relnotes
ms.reviewer: jswymer
ms.date: 03/25/2020
ms.assetid: 9cadefe1-eb1b-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: af0f47b0d107e8786df2058461bb3dfd0477440b
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232618"
---
# <a name="performance-of-web-service-requests-and-reports-added-to-application-insights-telemetry-for-partners"></a><span data-ttu-id="c8c50-103">パートナー向けの Application Insights テレメトリに追加された Web サービス要求とレポートのパフォーマンス</span><span class="sxs-lookup"><span data-stu-id="c8c50-103">Performance of web service requests and reports added to Application Insights telemetry for partners</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="c8c50-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c8c50-104">Enabled for</span></span>    |  <span data-ttu-id="c8c50-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c8c50-105">Public preview</span></span> | <span data-ttu-id="c8c50-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c8c50-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c8c50-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c8c50-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c8c50-108">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="c8c50-108">Apr 2020</span></span>| <span data-ttu-id="c8c50-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="c8c50-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c8c50-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c8c50-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c8c50-111">パートナーは Web サービス要求とレポートのパフォーマンスを監視できます。</span><span class="sxs-lookup"><span data-stu-id="c8c50-111">Partners can monitor performance of web service requests and reports.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c8c50-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c8c50-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c8c50-113">Business Central Server は、Web サービス要求とレポートの実行時刻とタイムアウトに関するテレメトリを発行します。</span><span class="sxs-lookup"><span data-stu-id="c8c50-113">The Business Central server will emit telemetry about the execution time and timeouts of web service requests and reports.</span></span> 

<span data-ttu-id="c8c50-114">パートナーとお客様はこのデータ使用して、Web サービス要求とレポートによって引き起こされるパフォーマンスの問題について環境を監視し、これらの問題の発生をよりプロアクティブに防ぐことができます。</span><span class="sxs-lookup"><span data-stu-id="c8c50-114">Partners and customers can use this data to monitor their environments for performance issues caused by web service requests and reports and be more proactive in preventing these issues from occurring.</span></span>

<span data-ttu-id="c8c50-115">[サンプル クエリ](https://github.com/microsoft/BCTech/tree/master/samples/AppInsights/KQL)と[サンプル ダッシュボード](https://github.com/microsoft/BCTech/tree/master/samples/AppInsights/Dashboard)にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="c8c50-115">You can access [sample queries](https://github.com/microsoft/BCTech/tree/master/samples/AppInsights/KQL) and [sample dashboards](https://github.com/microsoft/BCTech/tree/master/samples/AppInsights/Dashboard).</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="c8c50-116">関連項目</span><span class="sxs-lookup"><span data-stu-id="c8c50-116">See also</span></span>


<!--docs start-->
<span data-ttu-id="c8c50-117">[テレメトリの監視と分析](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/telemetry-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c8c50-117">[Monitoring and Analyzing Telemetry](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/telemetry-overview) (docs)</span></span>
<!--docs end-->

