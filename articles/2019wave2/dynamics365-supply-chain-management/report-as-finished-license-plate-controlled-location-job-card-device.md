---
title: ジョブ カード デバイスからライセンス プレートで管理されている場所への完了レポート
description: 生産への原材料のピッキングや完成品のプット アウェイの完了などの倉庫プロセスは、生産管理プロセスに密接に統合されています。 ジョブ カード デバイスは、製造現場の作業員が製造オーダーの進捗を報告するために使用する Dynamics 365 Supply Chain Management ユーザー エクスペリエンスです。 この機能強化により、ジョブ カード デバイスからライセンス プレートで追跡されている場所に、完了としてレポートできます。
author: relnotes
ms.reviewer: josaw
ms.date: 11/15/2019
ms.assetid: dfb827a2-7bca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: sorenand
dynamics365pdf: true
ms.openlocfilehash: a6f7d7ca3d3033cc745767ab4d51c4d685597063
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889807"
---
# <a name="report-as-finished-to-a-license-plate-controlled-location-from-the-job-card-device"></a><span data-ttu-id="5169a-105">ジョブ カード デバイスからライセンス プレートで管理されている場所への完了レポート</span><span class="sxs-lookup"><span data-stu-id="5169a-105">Report as finished to a license plate-controlled location from the job card device</span></span>


| <span data-ttu-id="5169a-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="5169a-106">Enabled for</span></span>    |  <span data-ttu-id="5169a-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5169a-107">Public preview</span></span> | <span data-ttu-id="5169a-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="5169a-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5169a-109">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="5169a-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="5169a-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5169a-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5169a-111">2019 年 9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="5169a-111">Sep 6, 2019</span></span>| <span data-ttu-id="5169a-112">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5169a-112">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5169a-113">2019 年 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="5169a-113">Oct 8, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="5169a-114">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5169a-114">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5169a-115">この機能強化により、生産からの完成品の出力が生産と倉庫の両方でライセンス プレートによって追跡されるシナリオでジョブ カード デバイスを使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="5169a-115">This enhancement enables the use of the job card device in scenarios where the finished goods output from the production are tracked by license plates throughout both production and the warehouse.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5169a-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5169a-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5169a-117">ジョブ カード デバイスの**進捗状況のレポート** ダイアログが強化され、ライセンス プレートを登録できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5169a-117">The **Report progress** dialog in the job card device has been enhanced to allow registration of a license plate.</span></span> <span data-ttu-id="5169a-118">この機能は次の場合に使用可能です。</span><span class="sxs-lookup"><span data-stu-id="5169a-118">This capability is available when:</span></span> 

- <span data-ttu-id="5169a-119">完成品が高度な倉庫プロセスに対応している。</span><span class="sxs-lookup"><span data-stu-id="5169a-119">The finished good is enabled for the advanced warehouse processes.</span></span>
- <span data-ttu-id="5169a-120">完成品が、ライセンス プレートで在庫を追跡するように設定された場所にレポートされている。</span><span class="sxs-lookup"><span data-stu-id="5169a-120">The finished good is reported to a location that is set up to track inventory by license plate.</span></span>
- <span data-ttu-id="5169a-121">完成品が既存のライセンス プレートにレポートされている。</span><span class="sxs-lookup"><span data-stu-id="5169a-121">The finished good is reported to an existing license plate.</span></span>


<!--feature detail end -->









## <a name="thank-you-for-your-idea"></a><span data-ttu-id="5169a-122">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="5169a-122">Thank you for your idea</span></span>
<span data-ttu-id="5169a-123">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=be62c3ff-2c76-e911-80e7-0003ff689b0e)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="5169a-123">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=be62c3ff-2c76-e911-80e7-0003ff689b0e).</span></span> <span data-ttu-id="5169a-124">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="5169a-124">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="5169a-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="5169a-125">See also</span></span>

<span data-ttu-id="5169a-126">[ジョブ カード デバイスからライセンス プレートで管理されている場所への完了レポート](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/production-control/report-finished-job-device) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="5169a-126">[Report as finished to a license plate controlled location from the Job card device](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/production-control/report-finished-job-device) (docs)</span></span>
