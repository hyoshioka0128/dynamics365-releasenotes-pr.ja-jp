---
title: パートナー向け Application Insights のサインイン試行テレメトリ
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーはサインイン試行に関するテレメトリ (成功または失敗) を Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 03/02/2020
ms.assetid: 2ad1dfcd-4446-ea11-a812-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: d29e7c1f60789b9327572edb219f0153701ae8aa
ms.sourcegitcommit: db53421debc891ea407773d0e9b39feb7a01fef3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/09/2020
ms.locfileid: "3110932"
---
# <a name="sign-in-attempt-telemetry-in-application-insights-for-partners"></a><span data-ttu-id="c75dd-103">パートナー向け Application Insights のサインイン試行テレメトリ</span><span class="sxs-lookup"><span data-stu-id="c75dd-103">Sign-in attempt telemetry in Application Insights for partners</span></span>


| <span data-ttu-id="c75dd-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c75dd-104">Enabled for</span></span>    |  <span data-ttu-id="c75dd-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c75dd-105">Public preview</span></span> | <span data-ttu-id="c75dd-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c75dd-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c75dd-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c75dd-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c75dd-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c75dd-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c75dd-109">2020 年 2 月 26 日</span><span class="sxs-lookup"><span data-stu-id="c75dd-109">Feb 26, 2020</span></span>| <span data-ttu-id="c75dd-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c75dd-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c75dd-111">2020 年 3 月 2 日</span><span class="sxs-lookup"><span data-stu-id="c75dd-111">Mar 2, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c75dd-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c75dd-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c75dd-113">パートナーは Application Insights をセットアップして使用し、(たとえば、アクセス許可がないことによる) ユーザーのサインインの問題の発生を監視して、Microsoft サポートに連絡する必要なしに顧客を積極的に支援できます。</span><span class="sxs-lookup"><span data-stu-id="c75dd-113">Partners can set up and use Application Insights to monitor when users experience sign-in issues (for example, because of missing permissions) and proactively help their customers without the need to contact Microsoft support.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c75dd-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c75dd-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c75dd-115">Business Central Server は、サインイン試行に関するテレメトリ (成功または失敗) を送信します。</span><span class="sxs-lookup"><span data-stu-id="c75dd-115">The Business Central server will emit telemetry about sign-in attempts (successful or failed).</span></span> <span data-ttu-id="c75dd-116">試行が失敗した場合、その理由もメッセージに記録されます。</span><span class="sxs-lookup"><span data-stu-id="c75dd-116">For failed attempts, the reason will be logged in the message as well.</span></span> 

<span data-ttu-id="c75dd-117">Business Central への承認が成功すると、サーバーは Open Company の運用に関するテレメトリー (成功または失敗) も送信します。</span><span class="sxs-lookup"><span data-stu-id="c75dd-117">After a successful authorization to Business Central, the server will also emit telemetry about the Open Company operation (successful or failed).</span></span> <span data-ttu-id="c75dd-118">会社への承認に失敗した場合、理由もメッセージに記録されます。</span><span class="sxs-lookup"><span data-stu-id="c75dd-118">For failed authorization to a company, the reason will also be logged in the message.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="c75dd-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="c75dd-119">See also</span></span>

<span data-ttu-id="c75dd-120">[認可トレース テレメトリの分析](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/telemetry-authorization-trace) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c75dd-120">[Analyzing Authorization Trace Telemetry](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/administration/telemetry-authorization-trace) (docs)</span></span>
