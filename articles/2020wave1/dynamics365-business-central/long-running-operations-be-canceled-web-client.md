---
title: 実行時間の長い操作を Web クライアントからキャンセルできる
description: 操作とレポートは、完了までに時間がかかりすぎる場合、ブラウザーからキャンセルできます。
author: kotelko
ms.reviewer: sgroespe
ms.date: 04/02/2020
ms.assetid: da142188-f753-ea11-a812-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: 46c743228db2092c5648cc734e6005eae68d59ef
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232849"
---
# <a name="long-running-operations-can-be-canceled-from-the-web-client"></a><span data-ttu-id="55ac6-103">実行時間の長い操作を Web クライアントからキャンセルできる</span><span class="sxs-lookup"><span data-stu-id="55ac6-103">Long-running operations can be canceled from the web client</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="55ac6-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="55ac6-104">Enabled for</span></span>    |  <span data-ttu-id="55ac6-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="55ac6-105">Public preview</span></span> | <span data-ttu-id="55ac6-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="55ac6-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="55ac6-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="55ac6-107">End users, automatically</span></span>|<span data-ttu-id="55ac6-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="55ac6-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="55ac6-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="55ac6-109">Feb 1, 2020</span></span>| <span data-ttu-id="55ac6-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="55ac6-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="55ac6-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="55ac6-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="55ac6-112">最新のビジネス システムでは、大量のデータを扱う場合でも、実行時間の長い操作 (レポートなど) に関連する柔軟性が不可欠です。</span><span class="sxs-lookup"><span data-stu-id="55ac6-112">Flexibility related to long-running operations (like reports) is essential in modern business systems, even when you work with large amounts of data.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="55ac6-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="55ac6-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="55ac6-114">実行時間の長い操作またはアプリケーション ジョブをキャンセルできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="55ac6-114">You can now cancel long-running operations or application jobs.</span></span> <span data-ttu-id="55ac6-115">操作全体をキャンセルするオプションを備えた処理済みの行数を示す進行状況ウィンドウが表示されます。</span><span class="sxs-lookup"><span data-stu-id="55ac6-115">The user is presented with a progress window that shows the number of processed rows with the option to cancel the entire operation.</span></span> <span data-ttu-id="55ac6-116">キャンセルされると、システムによって確認を求められ、ジョブのキャンセルが要求されます。</span><span class="sxs-lookup"><span data-stu-id="55ac6-116">When canceled, the system asks for confirmation and then requests the job to be cancelled.</span></span>

<span data-ttu-id="55ac6-117">典型的なシナリオは、レポートまたは長時間実行されているバッチ ジョブをキャンセルする機能ですが、この機能は、請求書の一括転記など、他の実行時間の長い操作のキャンセルにまで拡張されます。</span><span class="sxs-lookup"><span data-stu-id="55ac6-117">A typical scenario is the ability to cancel reports or long-running batch jobs, but this feature extends to canceling other long-running operations, such as bulk posting of invoices.</span></span>
<!--feature detail end -->

<span data-ttu-id="55ac6-118">![レポートのキャンセル](media/cancel-report.png "レポートのキャンセル")</span><span class="sxs-lookup"><span data-stu-id="55ac6-118">![Canceling a report](media/cancel-report.png "Canceling a report")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="55ac6-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="55ac6-119">See also</span></span>


<!--docs start-->
<span data-ttu-id="55ac6-120">[レポート、バッチ ジョブ、XMLport の操作](https://docs.microsoft.com/dynamics365/business-central/ui-work-report) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="55ac6-120">[Working with Reports, Batch Jobs, and XMLports](https://docs.microsoft.com/dynamics365/business-central/ui-work-report) (docs)</span></span>
<!--docs end-->

