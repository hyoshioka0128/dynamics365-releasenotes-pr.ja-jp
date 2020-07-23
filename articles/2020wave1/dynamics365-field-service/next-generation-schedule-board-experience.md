---
title: 次世代スケジュール ボード エクスペリエンス
description: スケジュール ボードのエクスペリエンスを刷新して、パフォーマンスと使いやすさを改善しました。
author: relnotes
ms.reviewer: krbjoran
ms.date: 04/22/2020
ms.assetid: 916e88cf-0d1e-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: sampatn
dynamics365pdf: true
ms.openlocfilehash: cd297a27ff2d780382d70c0cb5b46f93a612e8b5
ms.sourcegitcommit: 299e7ae952585bc5f8dbe620de3a9d5ef778990a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2020
ms.locfileid: "3548198"
---
# <a name="next-generation-schedule-board-experience"></a><span data-ttu-id="2ca17-103">次世代スケジュール ボード エクスペリエンス</span><span class="sxs-lookup"><span data-stu-id="2ca17-103">Next generation schedule board experience</span></span>


| <span data-ttu-id="2ca17-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="2ca17-104">Enabled for</span></span>    |  <span data-ttu-id="2ca17-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2ca17-105">Public preview</span></span> | <span data-ttu-id="2ca17-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="2ca17-106">Early access</span></span> | <span data-ttu-id="2ca17-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="2ca17-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="2ca17-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="2ca17-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="2ca17-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="2ca17-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="2ca17-110">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2ca17-110">Apr 1, 2020</span></span>|-| -|


## <a name="business-value"></a><span data-ttu-id="2ca17-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2ca17-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="2ca17-112">再設計されたスケジュール ボード エクスペリエンスにより、ディスパッチャーはスケジュールをより迅速かつ簡単に管理し、貴重なリソースを効果的に使用できます。</span><span class="sxs-lookup"><span data-stu-id="2ca17-112">The reimagined schedule board experience makes it faster and easier for dispatchers to manage scheduling and better ensure effective use of valuable resources.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="2ca17-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2ca17-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="2ca17-114">スケジュール ボードは、派遣担当者が技術者のスケジュールを設定するための一元化されたスケジューリング機能を提供する強力なツールです。</span><span class="sxs-lookup"><span data-stu-id="2ca17-114">The schedule board is a powerful tool that provides centralized scheduling capabilities for dispatchers to schedule technicians.</span></span> <span data-ttu-id="2ca17-115">また、営業担当者やエンジニアなど、さまざまなリソースの作業を計画するために、他の作業ストリームでも使用されます。</span><span class="sxs-lookup"><span data-stu-id="2ca17-115">It is also used by other workstreams to plan work for various types of resources, such as sales reps and engineers.</span></span>  <span data-ttu-id="2ca17-116">パフォーマンス、スケール、セキュリティ、ユーザー エクスペリエンスなど、重要な原則を網羅するすべてのウェーブについて、スケジュール ボードに対する投資が行われています。</span><span class="sxs-lookup"><span data-stu-id="2ca17-116">There is investment in the schedule board in every wave across critical tenets, including performance, scale, security, and user experience.</span></span>

<span data-ttu-id="2ca17-117">これは、スケジュール ボードの完全に新しいバージョンであり、時間単位ビューでのユーザー エクスペリエンスとパフォーマンスの両方が強化されています。</span><span class="sxs-lookup"><span data-stu-id="2ca17-117">This is a completely new version of the schedule board, enhancing both the user experience and performance on the hourly view.</span></span> <span data-ttu-id="2ca17-118">予約の作成にかかる時間と、ボードの初期スケジュールの読み込み時間が、かなり改善されています。</span><span class="sxs-lookup"><span data-stu-id="2ca17-118">The time it takes to create bookings, along with the initial schedule board load time, is measurably improved.</span></span> <span data-ttu-id="2ca17-119">1 日のスケジュール設定エクスペリエンスも簡素化されます。</span><span class="sxs-lookup"><span data-stu-id="2ca17-119">The intraday scheduling experience is also simplified.</span></span> 

<span data-ttu-id="2ca17-120">2020 年リリース ウェーブ 1 のプレビューでは、スケジュール ボードの時間単位ビューでの個々の要件に対するドラッグ アンド ドロップのスケジュール設定シナリオがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="2ca17-120">The 2020 release wave 1 preview will support drag-and-drop scheduling scenarios for individual requirements in the hourly view of the schedule board.</span></span> <span data-ttu-id="2ca17-121">その後、ウェーブ 1 を通して定期的に追加機能で更新されます。</span><span class="sxs-lookup"><span data-stu-id="2ca17-121">It will be followed by regular updates with additional functionality throughout wave 1.</span></span>
<!--feature detail end -->

<span data-ttu-id="2ca17-122">![次世代スケジュール ボード エクスペリエンス](media/next-generation-schedule-board-experience.png "次世代スケジュール ボード エクスペリエンス")</span><span class="sxs-lookup"><span data-stu-id="2ca17-122">![Next generation schedule board experience](media/next-generation-schedule-board-experience.png "Next generation schedule board experience")</span></span>
<!-- Picture 1 -->

> [!NOTE]
> <span data-ttu-id="2ca17-123">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="2ca17-123">This feature is available in Unified Interface only.</span></span> <span data-ttu-id="2ca17-124">新しいスケジュール ボード エクスペリエンスのための新しいソリューションがインストールされます。</span><span class="sxs-lookup"><span data-stu-id="2ca17-124">A new solution will be installed for the new schedule board experience.</span></span>







## <a name="see-also"></a><span data-ttu-id="2ca17-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="2ca17-125">See also</span></span>

<!--docs start-->
<span data-ttu-id="2ca17-126">[Dynamics 365 Field Service で新しい、改良されたスケジュール ボードをプレビューする](https://docs.microsoft.com/dynamics365/field-service/preview-schedule-board) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="2ca17-126">[Preview the new and improved schedule board in Dynamics 365 Field Service](https://docs.microsoft.com/dynamics365/field-service/preview-schedule-board) (docs)</span></span>
<!--docs end-->
