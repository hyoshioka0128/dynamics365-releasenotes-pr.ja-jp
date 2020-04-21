---
title: ジョブ カード デバイスの機能向上
description: 現在はジョブ カード ターミナルでしか利用できない機能を追加することで、ジョブ カード デバイスを強化しています。 これは、製造現場の作業員に、生産ジョブを管理する際のより直感的でタッチ操作しやすいエクスペリエンスを提供します。
author: relnotes
ms.reviewer: kamaybac
ms.date: 03/18/2020
ms.assetid: eb239434-82e3-e911-a812-000d3a4f13c0
ms.topic: article
ms.service: business-applications
ms.author: johanho
dynamics365pdf: true
ms.openlocfilehash: dcfb6093e1eac3b0807586af63dbfd663a6d74f4
ms.sourcegitcommit: 773ea4a9be0440714ed67e25d1ba572a6a25072e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2020
ms.locfileid: "3152271"
---
# <a name="improved-job-card-device"></a><span data-ttu-id="d7174-104">ジョブ カード デバイスの機能向上</span><span class="sxs-lookup"><span data-stu-id="d7174-104">Improved job card device</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="d7174-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="d7174-105">Enabled for</span></span>    |  <span data-ttu-id="d7174-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d7174-106">Public preview</span></span> | <span data-ttu-id="d7174-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="d7174-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d7174-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="d7174-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="d7174-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="d7174-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="d7174-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="d7174-110">Feb 3, 2020</span></span>| <span data-ttu-id="d7174-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="d7174-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="d7174-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d7174-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d7174-113">製造現場の作業員が生産ジョブを効果的に管理できる単一の統合されたユーザー エクスペリエンスを提供することは、効果と効率性を高め、エラー率を減らすのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d7174-113">Providing a single integrated user experience where shop floor workers can effectively manage production jobs can help to improve effectiveness and efficiency and help reduce error rates.</span></span> <span data-ttu-id="d7174-114">生産活動に関する正確なデータを取得することにより、製造業者は生産性を向上させ、スクラップと欠陥の比率を下げ、仕掛品を減らして、スループットを高めることができます。</span><span class="sxs-lookup"><span data-stu-id="d7174-114">Capturing accurate data about production activities also enables manufacturers to increase productivity, decrease scrap and defect ratios, reduce work-in-progress, and improve throughput.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d7174-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d7174-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d7174-116">これまでジョブ カード ターミナルでしか利用できなかった機能を追加することで、ジョブ カード デバイスを強化しています。</span><span class="sxs-lookup"><span data-stu-id="d7174-116">We are enhancing the job card device by adding capabilities that have so far been available only on the job card terminal.</span></span> <span data-ttu-id="d7174-117">これは、製造現場の作業員に、生産ジョブの管理に向けて、より直感的でタッチ操作しやすいエクスペリエンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="d7174-117">This will provide shop floor workers with a more intuitive and touch-friendly experience toward managing production jobs.</span></span> <span data-ttu-id="d7174-118">機能強化は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="d7174-118">Enhancements include:</span></span>

- <span data-ttu-id="d7174-119">**進捗状況のレポート** ダイアログ ボックスのユーザー インターフェイスが強化され、より直感的でタッチ操作しやすい、ワークフロー駆動型のエクスペリエンスが提供されます。</span><span class="sxs-lookup"><span data-stu-id="d7174-119">Improvements to the user interface of the **Report progress** dialog box, which will provide a more intuitive, touch-friendly, and workflow-driven experience.</span></span>
- <span data-ttu-id="d7174-120">モバイル デバイスを使用して完了を報告するときに、ライセンス プレートのラベルを印刷する機能。</span><span class="sxs-lookup"><span data-stu-id="d7174-120">The ability to print labels for license plates when using a mobile device to report as finished.</span></span>

<span data-ttu-id="d7174-121">ジョブ カード デバイスに対するこれらの機能強化は、製造実行機能を更新するための最初のステップを表し、勤怠管理とジョブ管理を統合する、単一の統合されたタッチ操作しやすいエクスペリエンスを提供します。</span><span class="sxs-lookup"><span data-stu-id="d7174-121">These enhancements to the job card device represent the first steps toward renewing the manufacturing execution capabilities and delivering a single, integrated, touch-friendly experience that integrates time, attendance, and job management.</span></span> <span data-ttu-id="d7174-122">また、最終的には モノのインターネット (IoT) データとセンサー データ、作業指示、品質管理、資産メンテナンス ジョブが統合されます。</span><span class="sxs-lookup"><span data-stu-id="d7174-122">It will also eventually bring together internet of things (IoT) and sensor data, work instructions, quality management, and asset maintenance jobs.</span></span>
<!--feature detail end -->









## <a name="thank-you-for-your-idea"></a><span data-ttu-id="d7174-123">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="d7174-123">Thank you for your idea</span></span>
<span data-ttu-id="d7174-124">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=f3073926-7219-e711-80c0-00155d460d59)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="d7174-124">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=f3073926-7219-e711-80c0-00155d460d59).</span></span> <span data-ttu-id="d7174-125">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="d7174-125">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>
