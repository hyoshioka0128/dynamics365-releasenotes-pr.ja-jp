---
title: ジョブ カード デバイスの機能向上
description: 現在はジョブ カード ターミナルでのみ利用可能な機能を追加することで、ジョブ カード デバイスを強化しています。 これは、製造現場の作業員に、生産ジョブを管理する際のより直感的でタッチ操作しやすいエクスペリエンスを提供します。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/17/2020
ms.assetid: eb239434-82e3-e911-a812-000d3a4f13c0
ms.topic: article
ms.service: business-applications
ms.author: johanho
dynamics365pdf: true
ms.openlocfilehash: 55ed1039f94f595dee4e5a3134d2ec17e3fdce23
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294789"
---
# <a name="improved-job-card-device"></a><span data-ttu-id="8f150-104">ジョブ カード デバイスの機能向上</span><span class="sxs-lookup"><span data-stu-id="8f150-104">Improved job card device</span></span>


| <span data-ttu-id="8f150-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="8f150-105">Enabled for</span></span>    |  <span data-ttu-id="8f150-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8f150-106">Public preview</span></span> | <span data-ttu-id="8f150-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="8f150-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8f150-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="8f150-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="8f150-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8f150-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8f150-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="8f150-110">Feb 3, 2020</span></span>| <span data-ttu-id="8f150-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8f150-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8f150-112">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="8f150-112">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="8f150-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8f150-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8f150-114">製造現場の作業員が生産ジョブを効果的に管理できる単一の統合されたユーザー エクスペリエンスを提供することは、効果と効率性を高め、エラー率を減らすのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="8f150-114">Providing a single integrated user experience where shop floor workers can effectively manage production jobs can help to improve effectiveness and efficiency and help reduce error rates.</span></span> <span data-ttu-id="8f150-115">生産活動に関する正確なデータを取得することにより、製造業者は生産性を向上させ、スクラップと欠陥の比率を下げ、仕掛品を減らして、スループットを高めることができます。</span><span class="sxs-lookup"><span data-stu-id="8f150-115">Capturing accurate data about production activities also enables manufacturers to increase productivity, decrease scrap and defect ratios, reduce work-in-progress, and improve throughput.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8f150-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8f150-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8f150-117">これまでジョブ カード ターミナルでのみ利用可能であった機能を追加することで、ジョブ カード デバイスを強化しています。</span><span class="sxs-lookup"><span data-stu-id="8f150-117">We are enhancing the job card device by adding capabilities that have so far been available only on the job card terminal.</span></span> <span data-ttu-id="8f150-118">これは、製造現場の作業員に、生産ジョブの管理に向けて、より直感的でタッチ操作しやすいエクスペリエンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="8f150-118">This will provide shop floor workers with a more intuitive and touch-friendly experience toward managing production jobs.</span></span> <span data-ttu-id="8f150-119">機能強化は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="8f150-119">Enhancements include:</span></span>

- <span data-ttu-id="8f150-120">**進捗状況のレポート** ダイアログ ボックスのユーザー インターフェイスが強化され、より直感的でタッチ操作しやすい、ワークフロー駆動型のエクスペリエンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="8f150-120">Improvements to the user interface of the **Report progress** dialog box, which will provide a more intuitive, touch-friendly, and workflow-driven experience.</span></span>
- <span data-ttu-id="8f150-121">モバイル デバイスを使用して完了を報告するときに、ライセンス プレートのラベルを印刷する機能。</span><span class="sxs-lookup"><span data-stu-id="8f150-121">The ability to print labels for license plates when using a mobile device to report as finished.</span></span>

<span data-ttu-id="8f150-122">ジョブ カード デバイスに対するこれらの機能強化は、製造実行機能を更新するための最初のステップを表し、勤怠管理とジョブ管理を統合する、単一の統合されたタッチ操作しやすいエクスペリエンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="8f150-122">These enhancements to the job card device represent the first steps toward renewing the manufacturing execution capabilities and delivering a single, integrated, touch-friendly experience that integrates time, attendance, and job management.</span></span> <span data-ttu-id="8f150-123">また、最終的には モノのインターネット (IoT) データとセンサー データ、作業指示、品質管理、資産メンテナンス ジョブが統合されます。</span><span class="sxs-lookup"><span data-stu-id="8f150-123">It will also eventually bring together internet of things (IoT) and sensor data, work instructions, quality management, and asset maintenance jobs.</span></span>
<!--feature detail end -->









## <a name="thank-you-for-your-idea"></a><span data-ttu-id="8f150-124">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="8f150-124">Thank you for your idea</span></span>
<span data-ttu-id="8f150-125">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=f3073926-7219-e711-80c0-00155d460d59)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="8f150-125">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=f3073926-7219-e711-80c0-00155d460d59).</span></span> <span data-ttu-id="8f150-126">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="8f150-126">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>
