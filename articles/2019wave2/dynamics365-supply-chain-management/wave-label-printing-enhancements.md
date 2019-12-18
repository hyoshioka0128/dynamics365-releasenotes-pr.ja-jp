---
title: ウェーブ ラベル印刷の機能強化
description: この機能では、ピッキング前のラベル作成の柔軟性が向上します。 ラベルはウェーブ プロセス中に作成されます。 ラベルとレイアウトの定義によって機能が拡充されます。
author: relnotes
ms.reviewer: josaw
ms.date: 11/15/2019
ms.assetid: 7c62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: 02240174998e55df409f4726d3cc7e0e068d620f
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889565"
---
# <a name="wave-label-printing-enhancements"></a><span data-ttu-id="6ec4c-105">ウェーブ ラベル印刷の機能強化</span><span class="sxs-lookup"><span data-stu-id="6ec4c-105">Wave label printing enhancements</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="6ec4c-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="6ec4c-106">Enabled for</span></span>    |  <span data-ttu-id="6ec4c-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6ec4c-107">Public preview</span></span> | <span data-ttu-id="6ec4c-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="6ec4c-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6ec4c-109">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="6ec4c-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="6ec4c-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6ec4c-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6ec4c-111">2019 年 9 月 17 日</span><span class="sxs-lookup"><span data-stu-id="6ec4c-111">Sep 17, 2019</span></span>| <span data-ttu-id="6ec4c-112">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="6ec4c-112">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="6ec4c-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="6ec4c-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="6ec4c-114">これらの変更により、パレット化前のカートンのラベル付けのサポートがより効率的になります。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-114">These changes will make it more efficient to support the labeling of cartons prior to palletizing.</span></span> <span data-ttu-id="6ec4c-115">コンプライアンスが問題となる一部のお客様は、各カートンのラベルのレイアウトと内容を義務付ける大規模小売業者に対する仕入先です。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-115">Some customers for whom compliance is an issue are vendors to large retailers that mandate the layout and content of labels for each carton.</span></span> <span data-ttu-id="6ec4c-116">これらの大規模顧客の "ラベル受け入れプロセス" では、受け入れ中にカートンがコンベア上に置かれ、バーコードが自動的に読み取られて、プット アウェイを自動的に作成できます。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-116">These large customers have a “label receiving process” where the cartons, while in receiving, are placed on conveyors, and the bar code is read automatically, allowing for automated creation of put-away.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="6ec4c-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6ec4c-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6ec4c-118">ウェーブ ラベルの印刷機能が次のように強化されます。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-118">Wave label printing functionality will be enhanced with the following:</span></span>

-  <span data-ttu-id="6ec4c-119">単一の作業明細行でのカートン数に従ってラベルを印刷できます。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-119">Allow for labels to be printed according to number of cartons on a single work line.</span></span> <span data-ttu-id="6ec4c-120">コンテナー詰め機能を使用しないと、100 個のカートンに対して、100 個のラベルが印刷されることを意味します。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-120">Without using the containerization feature, this would mean that for a quantity of 100 cartons, the feature will print out 100 labels.</span></span>

- <span data-ttu-id="6ec4c-121">ラベルの列挙が含まれます (1/124、2/124 …</span><span class="sxs-lookup"><span data-stu-id="6ec4c-121">Include an enumeration of the labels (1/124, 2/124 …</span></span> <span data-ttu-id="6ec4c-122">124/124)。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-122">124/124).</span></span>

- <span data-ttu-id="6ec4c-123">船荷証券 (BOL) を作成してラベルに印刷することができます。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-123">Allow for a bill of lading (BOL) to be created and printed on the label.</span></span>

- <span data-ttu-id="6ec4c-124">カートンごとに固有のシリアル配送コンテナー コード (SSCC) を作成して、ラベルに含めることができます。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-124">Allow a unique Serial Shipping Container Code (SSCC) to be created per carton and included on the label.</span></span>

- <span data-ttu-id="6ec4c-125">BOL および SSCC 番号に対して GS1 準拠の番号シーケンスを作成できます。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-125">Allow for the creation of a GS1-compliant number sequence for BOL and SSCC numbers.</span></span>

- <span data-ttu-id="6ec4c-126">HAZMAT コードをラベルに含めることができます (該当する場合)。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-126">Allow for a HAZMAT code to be included (if relevant) on the label.</span></span>

- <span data-ttu-id="6ec4c-127">ラベルの再印刷がサポートされます (リッチ クライアントからのようにハンドヘルド デバイスから) 。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-127">Support reprint of labels (from hand-held devices, as from a rich client).</span></span>

- <span data-ttu-id="6ec4c-128">ラベル (たとえば、短いピッキング シナリオの場合) と再印刷の無効化がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-128">Support for voiding of labels (for example, for short pick scenarios) and reprint.</span></span>

- <span data-ttu-id="6ec4c-129">ウェーブ ラベル履歴のクリーンアップがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-129">Support for clean-up of wave label history.</span></span> 

<span data-ttu-id="6ec4c-130">これらの変更により、パレット化前のカートンのラベル付けのサポートがより効率的になります。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-130">These changes will make it more efficient to support labeling of cartons prior to palletizing.</span></span> <span data-ttu-id="6ec4c-131">特に、個々のカートンのスキャンを使用して自動的に注文受領確認を実行する大規模小売業者に出荷する会社に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="6ec4c-131">It is especially helpful to companies shipping to large retailers that perform order receipt confirmation automatically by scanning each individual carton.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="6ec4c-132">関連項目</span><span class="sxs-lookup"><span data-stu-id="6ec4c-132">See also</span></span>

<span data-ttu-id="6ec4c-133">[倉庫管理の概要](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/warehousing/warehouse-management-overview) (docs)</span><span class="sxs-lookup"><span data-stu-id="6ec4c-133">[Warehouse management overview](https://docs.microsoft.com/dynamics365/unified-operations/supply-chain/warehousing/warehouse-management-overview) (docs)</span></span>
