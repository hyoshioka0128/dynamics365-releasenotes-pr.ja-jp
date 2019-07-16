---
title: ウェーブ ラベル印刷の機能強化
description: この機能では、ピッキング前のラベル作成の柔軟性が向上します。 ラベルはウェーブ プロセス中に作成されます。 ラベルとレイアウトの定義によって機能が拡充されます。
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 7c62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: 918455611b03db41e228c14cafadc81646cc01c6
ms.sourcegitcommit: d6ff62c145bfdd7742034a67a29bf75938823eb0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/24/2019
ms.locfileid: "1702250"
---
# <a name="wave-label-printing-enhancements"></a><span data-ttu-id="c51cf-105">ウェーブ ラベル印刷の機能強化</span><span class="sxs-lookup"><span data-stu-id="c51cf-105">Wave label printing enhancements</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="c51cf-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="c51cf-106">Enabled for</span></span>    |  <span data-ttu-id="c51cf-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c51cf-107">Public preview</span></span> | <span data-ttu-id="c51cf-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="c51cf-108">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="c51cf-109">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="c51cf-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c51cf-110">2019 年 4 月</span><span class="sxs-lookup"><span data-stu-id="c51cf-110">April 2019</span></span>| <span data-ttu-id="c51cf-111">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="c51cf-111">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="c51cf-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c51cf-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c51cf-113">これらの変更により、パレット化前のカートンのラベル付けのサポートがより効率的になります。</span><span class="sxs-lookup"><span data-stu-id="c51cf-113">These changes will make it more efficient to support the labeling of cartons prior to palletizing.</span></span> <span data-ttu-id="c51cf-114">コンプライアンスが問題となる一部のお客様は、各カートンのラベルのレイアウトと内容を義務付ける大規模小売業者に対する仕入先です。</span><span class="sxs-lookup"><span data-stu-id="c51cf-114">Some customers for whom compliance is an issue are vendors to large retailers that mandate the layout and content of labels for each carton.</span></span> <span data-ttu-id="c51cf-115">これらの大規模顧客の "ラベル受け入れプロセス" では、受け入れ中にカートンがコンベア上に置かれ、バーコードが自動的に読み取られて、プット アウェイを自動的に作成できます。</span><span class="sxs-lookup"><span data-stu-id="c51cf-115">These large customers have a “label receiving process” where the cartons, while in receiving, are placed on conveyors, and the bar code is read automatically, allowing for automated creation of put-away.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c51cf-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c51cf-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c51cf-117">ウェーブ ラベル印刷機能は、Dynamics 365 for Finance and Operations バージョン 10.0.0 で組み込まれました。</span><span class="sxs-lookup"><span data-stu-id="c51cf-117">Wave label printing functionality was included in Dynamics 365 for Finance and Operations version 10.0.0.</span></span> <span data-ttu-id="c51cf-118">この機能は次のように強化されます。</span><span class="sxs-lookup"><span data-stu-id="c51cf-118">The functionality is enhanced with the following:</span></span>

-  <span data-ttu-id="c51cf-119">単一の作業明細行でのカートン数に従ってラベルを印刷できます。</span><span class="sxs-lookup"><span data-stu-id="c51cf-119">Allow for labels to be printed according to number of cartons on a single work line.</span></span> <span data-ttu-id="c51cf-120">コンテナー詰め機能を使用しないと、100 個のカートンに対して、100 個のラベルが印刷されることを意味します。</span><span class="sxs-lookup"><span data-stu-id="c51cf-120">Without using the containerization feature, this would mean that for a quantity of 100 cartons, the feature will print out 100 labels.</span></span>

- <span data-ttu-id="c51cf-121">ラベルの列挙が含まれます (1/124、2/124…124/124)。</span><span class="sxs-lookup"><span data-stu-id="c51cf-121">Include an enumeration of the labels (1/124, 2/124…124/124).</span></span>

- <span data-ttu-id="c51cf-122">船荷証券 (BOL) を作成してラベルに印刷することができます。</span><span class="sxs-lookup"><span data-stu-id="c51cf-122">Allow for a bill of lading (BOL) to be created and printed on the label.</span></span>

- <span data-ttu-id="c51cf-123">カートンごとに固有のシリアル配送コンテナー コード (SSCC) を作成して、ラベルに含めることができます。</span><span class="sxs-lookup"><span data-stu-id="c51cf-123">Allow a unique Serial Shipping Container Code (SSCC) to be created per carton and included on the label.</span></span>

- <span data-ttu-id="c51cf-124">BOL および SSCC 番号に対して GS1 準拠の番号シーケンスを作成できます。</span><span class="sxs-lookup"><span data-stu-id="c51cf-124">Allow for the creation of a GS1-compliant number sequence for BOL and SSCC numbers.</span></span>

- <span data-ttu-id="c51cf-125">HAZMAT コードをラベルに含めることができます (該当する場合)。</span><span class="sxs-lookup"><span data-stu-id="c51cf-125">Allow for a HAZMAT code to be included (if relevant) on the label.</span></span>

- <span data-ttu-id="c51cf-126">ラベルの再印刷がサポートされます (リッチ クライアントからのようにハンドヘルド デバイスから) 。</span><span class="sxs-lookup"><span data-stu-id="c51cf-126">Support reprint of labels (from hand-held devices, as from a rich client).</span></span>

- <span data-ttu-id="c51cf-127">ラベル (たとえば、短いピッキング シナリオの場合) と再印刷の無効化がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="c51cf-127">Support for voiding of labels (for example, for short pick scenarios) and reprint.</span></span>

- <span data-ttu-id="c51cf-128">ウェーブ ラベル履歴のクリーンアップがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="c51cf-128">Support for clean-up of wave label history.</span></span> 

<span data-ttu-id="c51cf-129">これらの変更により、パレット化前のカートンのラベル付けのサポートがより効率的になります。</span><span class="sxs-lookup"><span data-stu-id="c51cf-129">These changes will make it more efficient to support labeling of cartons prior to palletizing.</span></span> <span data-ttu-id="c51cf-130">特に、個々のカートンのスキャンを使用して自動的に注文受領確認を実行する大規模小売業者に出荷する会社に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="c51cf-130">It is especially helpful to companies shipping to large retailers that perform order receipt confirmation automatically by scanning each individual carton.</span></span>
<!--feature detail end -->










