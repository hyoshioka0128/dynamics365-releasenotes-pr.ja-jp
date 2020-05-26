---
title: 実行時間の長い操作を Web クライアントからキャンセルできる
description: 操作とレポートは、完了までに時間がかかりすぎる場合、ブラウザーからキャンセルできます。
author: kotelko
ms.reviewer: sgroespe
ms.date: 04/07/2020
ms.assetid: da142188-f753-ea11-a812-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: 1cf97fd0154281666ad87a69b8f7ef5da417235b
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255037"
---
# <a name="long-running-operations-can-be-canceled-from-the-web-client"></a><span data-ttu-id="f4ae7-103">実行時間の長い操作を Web クライアントからキャンセルできる</span><span class="sxs-lookup"><span data-stu-id="f4ae7-103">Long-running operations can be canceled from the web client</span></span>


| <span data-ttu-id="f4ae7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f4ae7-104">Enabled for</span></span>    |  <span data-ttu-id="f4ae7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f4ae7-105">Public preview</span></span> | <span data-ttu-id="f4ae7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f4ae7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f4ae7-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="f4ae7-107">End users, automatically</span></span>|<span data-ttu-id="f4ae7-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="f4ae7-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="f4ae7-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="f4ae7-109">Feb 1, 2020</span></span>| <span data-ttu-id="f4ae7-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="f4ae7-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="f4ae7-111">2020 年 4 月 2 日</span><span class="sxs-lookup"><span data-stu-id="f4ae7-111">Apr 2, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="f4ae7-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f4ae7-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f4ae7-113">最新のビジネス システムでは、大量のデータを扱う場合でも、実行時間の長い操作 (レポートなど) に関連する柔軟性が不可欠です。</span><span class="sxs-lookup"><span data-stu-id="f4ae7-113">Flexibility related to long-running operations (like reports) is essential in modern business systems, even when you work with large amounts of data.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f4ae7-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f4ae7-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f4ae7-115">実行時間の長い操作またはアプリケーション ジョブをキャンセルできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f4ae7-115">You can now cancel long-running operations or application jobs.</span></span> <span data-ttu-id="f4ae7-116">操作全体をキャンセルするオプションを備えた処理済みの行数を示す進行状況ウィンドウが表示されます。</span><span class="sxs-lookup"><span data-stu-id="f4ae7-116">The user is presented with a progress window that shows the number of processed rows with the option to cancel the entire operation.</span></span> <span data-ttu-id="f4ae7-117">キャンセルされると、システムによって確認を求められ、ジョブのキャンセルが要求されます。</span><span class="sxs-lookup"><span data-stu-id="f4ae7-117">When canceled, the system asks for confirmation and then requests the job to be cancelled.</span></span>

<span data-ttu-id="f4ae7-118">典型的なシナリオは、レポートまたは長時間実行されているバッチ ジョブをキャンセルする機能ですが、この機能は、請求書の一括転記など、他の実行時間の長い操作のキャンセルにまで拡張されます。</span><span class="sxs-lookup"><span data-stu-id="f4ae7-118">A typical scenario is the ability to cancel reports or long-running batch jobs, but this feature extends to canceling other long-running operations, such as bulk posting of invoices.</span></span>
<!--feature detail end -->

<span data-ttu-id="f4ae7-119">![レポートのキャンセル](media/cancel-report.png "レポートのキャンセル")</span><span class="sxs-lookup"><span data-stu-id="f4ae7-119">![Canceling a report](media/cancel-report.png "Canceling a report")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="f4ae7-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="f4ae7-120">See also</span></span>

<!--docs start-->
<span data-ttu-id="f4ae7-121">[レポート、バッチ ジョブ、XMLport の操作](https://docs.microsoft.com/dynamics365/business-central/ui-work-report) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="f4ae7-121">[Working with Reports, Batch Jobs, and XMLports](https://docs.microsoft.com/dynamics365/business-central/ui-work-report) (docs)</span></span>
<!--docs end-->
