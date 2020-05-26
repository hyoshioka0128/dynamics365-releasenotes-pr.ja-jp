---
title: パートナー向け Application Insights のエラー テレメトリの更新
description: 環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは更新 codeunit で例外によって発生した更新エラーに関するテレメトリを Application Insights に送信します。
author: relnotes
ms.reviewer: jswymer
ms.date: 04/24/2020
ms.assetid: ffafb82d-8f84-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: kepontop
dynamics365pdf: true
ms.openlocfilehash: fe0ac03ead20f0e306e86b893fc497697b1fb6cb
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350931"
---
# <a name="update-error-telemetry-in-application-insights-for-partners"></a><span data-ttu-id="c7ea0-103">パートナー向け Application Insights のエラー テレメトリの更新</span><span class="sxs-lookup"><span data-stu-id="c7ea0-103">Update error telemetry in Application Insights for partners</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="c7ea0-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c7ea0-104">Enabled for</span></span>    |  <span data-ttu-id="c7ea0-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c7ea0-105">Public preview</span></span> | <span data-ttu-id="c7ea0-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c7ea0-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c7ea0-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c7ea0-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c7ea0-108">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="c7ea0-108">Jun 2020</span></span>| <span data-ttu-id="c7ea0-109">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="c7ea0-109">Jun 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c7ea0-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c7ea0-110">Business value</span></span>
<span data-ttu-id="c7ea0-111">環境のテレメトリ キーが Business Central 管理センターで指定されている場合、サーバーは更新 codeunit で例外によって発生した更新エラーに関するテレメトリを Application Insights に送信します。</span><span class="sxs-lookup"><span data-stu-id="c7ea0-111">If a telemetry key for an environment has been specified in the Business Central administration center, the server will emit telemetry to Application Insights about update errors caused by exceptions in update codeunits.</span></span>

## <a name="feature-details"></a><span data-ttu-id="c7ea0-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c7ea0-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c7ea0-113">Business Central Server は、企業ライフサイクル イベントに関するテレメトリ (成功または失敗) を送信します。</span><span class="sxs-lookup"><span data-stu-id="c7ea0-113">The Business Central server will emit telemetry about company lifecycle events (successful or failed).</span></span> 

<span data-ttu-id="c7ea0-114">更新 codeunit の例外によって発生した更新エラーは、以下に関する情報と共に送信されます。</span><span class="sxs-lookup"><span data-stu-id="c7ea0-114">Update errors caused by exceptions in update codeunits will emitted with information about:</span></span>

- <span data-ttu-id="c7ea0-115">例外がスローされた codeunit。</span><span class="sxs-lookup"><span data-stu-id="c7ea0-115">The codeunit where the exception is thrown.</span></span>
- <span data-ttu-id="c7ea0-116">AL スタック トレース。</span><span class="sxs-lookup"><span data-stu-id="c7ea0-116">AL stack trace.</span></span>
- <span data-ttu-id="c7ea0-117">例外メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c7ea0-117">Exception message.</span></span>

<span data-ttu-id="c7ea0-118">これによりパートナーは、テナントごとの拡張機能の更新エラーをすばやく修正できます。</span><span class="sxs-lookup"><span data-stu-id="c7ea0-118">This will enable partners to quickly fix update errors in per-tenant extensions.</span></span>
<!--feature detail end -->









