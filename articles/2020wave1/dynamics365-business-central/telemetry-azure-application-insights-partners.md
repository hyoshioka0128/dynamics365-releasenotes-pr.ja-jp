---
title: Application Insights でのパートナー向けテレメトリ
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーはサインイン試行に関するテレメトリ (成功または失敗) を送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 12/11/2019
ms.assetid: 9cadefe1-eb1b-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: 955e47e8e50de07ebe087a5d877b4fb6e6e90943
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986651"
---
# <a name="telemetry-in-application-insights-for-partners"></a><span data-ttu-id="c2343-103">Application Insights でのパートナー向けテレメトリ</span><span class="sxs-lookup"><span data-stu-id="c2343-103">Telemetry in Application Insights for partners</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="c2343-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c2343-104">Enabled for</span></span>    |  <span data-ttu-id="c2343-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c2343-105">Public preview</span></span> | <span data-ttu-id="c2343-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c2343-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c2343-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c2343-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c2343-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="c2343-108">Feb 2020</span></span>| <span data-ttu-id="c2343-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="c2343-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c2343-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c2343-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c2343-111">パートナーは、Microsoft サポートに連絡することなく、サインインの問題について顧客を積極的に支援できます。</span><span class="sxs-lookup"><span data-stu-id="c2343-111">Partners can proactively help their customers with sign-in issues without the need to contact Microsoft support.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c2343-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c2343-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c2343-113">Business Central Server は、サインイン試行に関するテレメトリ (成功または失敗) を送信します。</span><span class="sxs-lookup"><span data-stu-id="c2343-113">The Business Central server will emit telemetry about sign-in attempts (successful or failed).</span></span> <span data-ttu-id="c2343-114">試行が失敗した場合、その理由もメッセージに記録されます。</span><span class="sxs-lookup"><span data-stu-id="c2343-114">For failed attempts, the reason will be logged in the message as well.</span></span> 

<span data-ttu-id="c2343-115">Business Central への承認が成功すると、サーバーは Open Company の運用に関するテレメトリー (成功または失敗) も送信します。</span><span class="sxs-lookup"><span data-stu-id="c2343-115">After a successful authorization to Business Central, the server will also emit telemetry about the Open Company operation (successful or failed).</span></span> <span data-ttu-id="c2343-116">会社への承認に失敗した場合、理由もメッセージに記録されます。</span><span class="sxs-lookup"><span data-stu-id="c2343-116">For failed authorization to a company, the reason will also be logged in the message.</span></span>
<!--feature detail end -->









