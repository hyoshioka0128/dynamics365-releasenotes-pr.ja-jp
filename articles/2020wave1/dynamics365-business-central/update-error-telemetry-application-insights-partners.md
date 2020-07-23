---
title: パートナー向け Application Insights のエラー テレメトリの更新
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは更新 codeunit で例外によって発生した更新エラーに関するテレメトリを Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 05/11/2020
ms.assetid: ffafb82d-8f84-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: e2bd226590b2ebc9ac51a819b40aaeecb7cf3e62
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3381367"
---
# <a name="update-error-telemetry-in-application-insights-for-partners"></a><span data-ttu-id="f3977-103">パートナー向け Application Insights のエラー テレメトリの更新</span><span class="sxs-lookup"><span data-stu-id="f3977-103">Update error telemetry in Application Insights for partners</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="f3977-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f3977-104">Enabled for</span></span>    |  <span data-ttu-id="f3977-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f3977-105">Public preview</span></span> | <span data-ttu-id="f3977-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f3977-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f3977-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="f3977-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="f3977-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="f3977-108">Jul 2020</span></span>| <span data-ttu-id="f3977-109">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="f3977-109">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="f3977-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f3977-110">Business value</span></span>
<span data-ttu-id="f3977-111">環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは更新 codeunit で例外によって発生した更新エラーに関するテレメトリを Application Insights に送信します。</span><span class="sxs-lookup"><span data-stu-id="f3977-111">If a telemetry key for an environment has been specified in the Business Central administration center, the server will emit telemetry to Application Insights about update errors caused by exceptions in update codeunits.</span></span>



## <a name="feature-details"></a><span data-ttu-id="f3977-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f3977-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f3977-113">更新 codeunit の例外によって発生した更新エラーは、以下に関する情報と共に送信されます。</span><span class="sxs-lookup"><span data-stu-id="f3977-113">Update errors caused by exceptions in update codeunits will emitted with information about:</span></span>

- <span data-ttu-id="f3977-114">例外がスローされた codeunit。</span><span class="sxs-lookup"><span data-stu-id="f3977-114">The codeunit where the exception is thrown.</span></span>
- <span data-ttu-id="f3977-115">AL スタック トレース。</span><span class="sxs-lookup"><span data-stu-id="f3977-115">AL stack trace.</span></span>
- <span data-ttu-id="f3977-116">例外メッセージ。</span><span class="sxs-lookup"><span data-stu-id="f3977-116">Exception message.</span></span>

<span data-ttu-id="f3977-117">これによりパートナーは、テナントごとの拡張機能の更新エラーをすばやく修正できます。</span><span class="sxs-lookup"><span data-stu-id="f3977-117">This will enable partners to quickly fix update errors in per-tenant extensions.</span></span>
<!--feature detail end -->









