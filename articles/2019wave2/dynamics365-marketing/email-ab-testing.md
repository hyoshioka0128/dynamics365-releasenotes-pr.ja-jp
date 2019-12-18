---
title: メールの A/B テスト
description: メールの A/B テスト
author: jain-shailesh
ms.reviewer: kamaybac
ms.date: 11/15/2019
ms.assetid: b861278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: shjain
dynamics365pdf: true
ms.openlocfilehash: 7c5f589e98ed341f7840543421f8c545a593148e
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2891824"
---
# <a name="email-ab-testing"></a><span data-ttu-id="b8dbf-103">メールの A/B テスト</span><span class="sxs-lookup"><span data-stu-id="b8dbf-103">Email A/B testing</span></span>


| <span data-ttu-id="b8dbf-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b8dbf-104">Enabled for</span></span>    |  <span data-ttu-id="b8dbf-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b8dbf-105">Public preview</span></span> | <span data-ttu-id="b8dbf-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="b8dbf-106">Early access</span></span> | <span data-ttu-id="b8dbf-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="b8dbf-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="b8dbf-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="b8dbf-108">End users, automatically</span></span>|-|<span data-ttu-id="b8dbf-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b8dbf-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b8dbf-110">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="b8dbf-110">Aug 2, 2019</span></span>| <span data-ttu-id="b8dbf-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b8dbf-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b8dbf-112">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b8dbf-112">Oct 1, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="b8dbf-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b8dbf-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b8dbf-114">複数存在するメール デザインから最善の結果が得られるものを見つけるための最良の方法の 1 つは、対象ユーザーの異なるサブセットで各デザインを試し、対話レコードを分析して各デザインがどのように受け取られたかを調べることです。</span><span class="sxs-lookup"><span data-stu-id="b8dbf-114">One of the best ways to find out which of several possible email designs will produce the best results is to try each design on a different subset of your audience and then analyze interaction records to see how each design was received.</span></span> <span data-ttu-id="b8dbf-115">マーケティング担当者はこれを _A/B テスト_と呼びます。</span><span class="sxs-lookup"><span data-stu-id="b8dbf-115">Marketers call this _A/B testing_.</span></span> 

<span data-ttu-id="b8dbf-116">マーケティング担当者が代替バージョンのメッセージを作成し、それに対するビジネス目標を定義できるようにすることで、この機能が Marketing 製品に組み込まれました。</span><span class="sxs-lookup"><span data-stu-id="b8dbf-116">We've now built this capability right into the Marketing product by allowing marketers to create alternative versions of a message and define their business goals for it.</span></span> <span data-ttu-id="b8dbf-117">システムでは、ターゲット セグメント内にいくつかの小さなテスト グループが確立され、各グループに異なるバージョンのメッセージが送信された後、統計的分析が行われて、示されたビジネス目標に基づいて優れている方のデザインが自動的に特定されます。</span><span class="sxs-lookup"><span data-stu-id="b8dbf-117">The system establishes a few small test groups within the target segment and sends a different version of the message to each group, followed by statistical analysis that automatically identifies the winning design based on the stated business goal.</span></span> <span data-ttu-id="b8dbf-118">その後、優れている方が残りのセグメントに配布されます。</span><span class="sxs-lookup"><span data-stu-id="b8dbf-118">The winner is then delivered to the rest of the segment.</span></span>
<!--feature detail end -->

<span data-ttu-id="b8dbf-119">![A/B テスト プロセスの概要図](media/a-b-testing.png "A/B テスト プロセスの概要図")</span><span class="sxs-lookup"><span data-stu-id="b8dbf-119">![A/B testing process overview diagram](media/a-b-testing.png "A/B testing process overview diagram")</span></span>
<!-- Picture 1 -->









## <a name="see-also"></a><span data-ttu-id="b8dbf-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="b8dbf-120">See also</span></span>
<span data-ttu-id="b8dbf-121">[機能の探索](https://aka.ms/rogm19RW2ROV2) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="b8dbf-121">[Feature exploration](https://aka.ms/rogm19RW2ROV2) (video)</span></span>

<span data-ttu-id="b8dbf-122">[8 月の更新プログラムと早期アクセス](https://cloudblogs.microsoft.com/dynamics365/it/2019/08/03/dynamics-365-for-marketing-august-update-and-early-access-are-rolling-out-now/) (ブログ)</span><span class="sxs-lookup"><span data-stu-id="b8dbf-122">[August update and early access](https://cloudblogs.microsoft.com/dynamics365/it/2019/08/03/dynamics-365-for-marketing-august-update-and-early-access-are-rolling-out-now/) (blog)</span></span>

<span data-ttu-id="b8dbf-123">[メール デザインの A/B テストを設計して実行する](https://docs.microsoft.com/dynamics365/customer-engagement/marketing/email-a-b-testing) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b8dbf-123">[Design and run A/B test on your email designs](https://docs.microsoft.com/dynamics365/customer-engagement/marketing/email-a-b-testing) (docs)</span></span>
