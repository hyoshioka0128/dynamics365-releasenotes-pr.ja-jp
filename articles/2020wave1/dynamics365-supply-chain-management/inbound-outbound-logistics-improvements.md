---
title: インバウンドおよびアウトバウンドのロジスティクスの改善
description: この機能は、倉庫管理システムを強化するさまざまな機能を集約します。 ほとんどは 2019 年ウェーブ 2 の間にテスト機能として徐々にリリースされました。
author: relnotes
ms.reviewer: kamaybac
ms.date: 12/16/2019
ms.assetid: 6214e28b-8bcb-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: 9af082cc872729e7963d93719a900590fb74d612
ms.sourcegitcommit: 1e222f5d9816ce7157d63f308aea14d853628226
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/10/2020
ms.locfileid: "3035852"
---
# <a name="inbound-and-outbound-logistics-improvements"></a><span data-ttu-id="dd6dc-104">インバウンドおよびアウトバウンドのロジスティクスの改善</span><span class="sxs-lookup"><span data-stu-id="dd6dc-104">Inbound and outbound logistics improvements</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="dd6dc-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="dd6dc-105">Enabled for</span></span>    |  <span data-ttu-id="dd6dc-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="dd6dc-106">Public preview</span></span> | <span data-ttu-id="dd6dc-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="dd6dc-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="dd6dc-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="dd6dc-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="dd6dc-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="dd6dc-109">Feb 2020</span></span>| <span data-ttu-id="dd6dc-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="dd6dc-110">Apr 2020</span></span>|




## <a name="feature-details"></a><span data-ttu-id="dd6dc-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="dd6dc-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="dd6dc-112">これらの機能のほとんどは 2019 年ウェーブ 2 の期間中にテスト機能としてリリースされました。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-112">Most of these features have been released as flighted during 2019 wave 2 timeframe.</span></span> <span data-ttu-id="dd6dc-113">これらは現在パブリック プレビューとしてリリースされています。顧客は Dynamics 365 Supply Chain Management バージョン 10.0.9 の **機能管理** を介して、これらの機能を運用環境に含めることができます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-113">They are now released as public preview and customers have the ability to include these features in production environment through **Feature management** from Dynamics 365 Supply Chain Management version 10.0.9.</span></span>

<span data-ttu-id="dd6dc-114">入庫:</span><span class="sxs-lookup"><span data-stu-id="dd6dc-114">Inbound:</span></span>

- <span data-ttu-id="dd6dc-115">**品質チェック**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-115">**Quality check**.</span></span> <span data-ttu-id="dd6dc-116">この機能を使用すると、入庫ドック エリアへの入庫時にその場で迅速な品質チェックを実行できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-116">With this functionality, you can perform rapid quality checks on the spot at the time of receiving to the inbound dock area.</span></span>

- <span data-ttu-id="dd6dc-117">**プット アウェイ クラスター**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-117">**Put away clusters**.</span></span> <span data-ttu-id="dd6dc-118">これは、一度に複数のライセンス プレートを選択して、それらを別の場所に在庫受入する方法です。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-118">This is a way to pick multiple license plates at once and take them for a putaway to different locations.</span></span> <span data-ttu-id="dd6dc-119">多くのライセンス プレートが在庫の完全なパレットではない小売企業に非常に便利です。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-119">It is very useful for retail where many license plates are not full pallets of inventory.</span></span>

<span data-ttu-id="dd6dc-120">倉庫オペレーション:</span><span class="sxs-lookup"><span data-stu-id="dd6dc-120">Warehouse operations:</span></span>

- <span data-ttu-id="dd6dc-121">**梱包製品分析コード**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-121">**Packaging product dimensions**.</span></span> <span data-ttu-id="dd6dc-122">これによりユーザーは、品目が倉庫 (ストレージ) に保管されているとき、梱包用の箱に梱包されているとき、複数の箱に梱包されているとき (入れ子の梱包) に対して、一連の異なる分析コードを使用できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-122">This allows users to have different sets of dimensions for when an item is being stored in the warehouse (storage), being packed into a box for packing, and being packed into a box with more of itself (nested packing).</span></span> 

- <span data-ttu-id="dd6dc-123">**品目の連結場所の使用率**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-123">**Item consolidation – location utilization**.</span></span> <span data-ttu-id="dd6dc-124">新しい場所利用率フォームは、倉庫管理者が倉庫全体の場所の容積利用率を簡単に表示してフィルターするツールとして機能します。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-124">The new location utilization form serves as a tool to warehouse managers to easily view and filter the volumetric utilization of location across the warehouse.</span></span>

- <span data-ttu-id="dd6dc-125">**場所ライセンス プレートの配置**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-125">**Location license plate positioning**.</span></span> <span data-ttu-id="dd6dc-126">こにより、ダブル ディープ パレット ラックなど、ユーザーは LP がマルチ パレットの場所のどこに配置されたかを表示できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-126">This allows the user to see where the LP is located in a multi-pallet location, such as double-deep pallet racking.</span></span> <span data-ttu-id="dd6dc-127">この機能は、ロケーションに配置する各ライセンス プレートのライセンス プレートに、順序番号を追加します。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-127">This functionality adds a sequence number to the license plate for each license plate that is put to a location.</span></span> 

- <span data-ttu-id="dd6dc-128">**場所と製品分析コードの混合**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-128">**Location product dimension mixing**.</span></span> <span data-ttu-id="dd6dc-129">この新しいロケーション プロファイル機能により、ファッション業界など、分析コードのある製品や製品バリアントを使用する場合に、場所の管理が改善されます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-129">This new location profile functionality enables better location managing when using product variants or products with dimensions, such as with the fashion industry.</span></span> <span data-ttu-id="dd6dc-130">構成、色、スタイル、サイズを特定の場所 (プロファイル) に混在させることができるかどうか、これらの分析コードの 1 つのみまたはいくつかの組み合わせのみを同じ場所に配置できるかどうかを決定できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-130">It allows you to decide whether configurations, colors, style, and sizes can be mixed on a certain location (profile) or if only one or a combination of some of those dimensions can be put to the same location.</span></span> 

- <span data-ttu-id="dd6dc-131">**柔軟な倉庫レベルの分析コード引当**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-131">**Flexible warehouse-level dimension reservation**.</span></span> <span data-ttu-id="dd6dc-132">バージョン 10.0.7 および 10.0.8 以降で使用可能。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-132">Available since version 10.0.7 and 10.0.8.</span></span> <span data-ttu-id="dd6dc-133">在庫引当ポリシーに柔軟性を提供するこの機能強化によって、バッチ管理される製品を販売し WMS 対応オペレーションとしてロジスティクスを実行する企業は、製品に関連付けられた在庫引当階層で禁じられている (“batch-below” と呼ばれるタイプになっている) 場合でも、顧客からの特定のバッチの要求を販売注文に登録できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-133">This enhancement introduces flexibility in the inventory reservation policy to allow businesses who sell batch-tracked products and run their logistics as WMS-enabled operations, to register their customers’ requests for specific batches on sales orders even though the inventory reservation hierarchy associated with the product prevents this (by being of type that is known as “batch-below”.)</span></span>

<span data-ttu-id="dd6dc-134">出庫:</span><span class="sxs-lookup"><span data-stu-id="dd6dc-134">Outbound:</span></span>

- <span data-ttu-id="dd6dc-135">**小型パッケージ配送**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-135">**Small package shipping**.</span></span> <span data-ttu-id="dd6dc-136">小型パッケージ配送では、配送業者のログイン資格情報の設定、配送業者の Web サービスで取得したラベルの印刷、顧客のサードパーティ アカウントへの運賃の請求、追加の配送条件、追加の付帯サービスの配送タイプの機能が追加されます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-136">Small package shipping adds functionality for setting up carrier login credentials, printing labels received back from carrier web services, charging freight to customer third-party accounts, additional freight terms, and additional accessorial delivery types.</span></span> 

- <span data-ttu-id="dd6dc-137">**システム主導の作業優先順位**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-137">**System-directed work sequencing**.</span></span> <span data-ttu-id="dd6dc-138">これにより、実行するためにシステムがユーザーに提示する作業指示書を、並べ替えおよびフィルターできます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-138">This setup offers the ability to sort and filter which work orders the system will present to the user for execution.</span></span>

- <span data-ttu-id="dd6dc-139">**積荷構築のウェーブ処理**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-139">**Wave load building**.</span></span> <span data-ttu-id="dd6dc-140">高度な積荷構築により、ウェーブでは、条件を満たす積荷が存在する場合は出荷を既存の積荷に割り当てて、必要な場合は新しい積荷を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-140">Advanced load building allows the wave to assign the shipment to an existing load, if one exists that meets the criteria, or create a new load if required.</span></span>

- <span data-ttu-id="dd6dc-141">**倉庫のスロッティング**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-141">**Warehouse slotting**.</span></span> <span data-ttu-id="dd6dc-142">ピッキング場所は、倉庫に注文をリリースする前に補充できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-142">Picking locations can be replenished before releasing orders to the warehouse.</span></span> <span data-ttu-id="dd6dc-143">倉庫のスロッティングを使用すると、注文の需要に基づいていつでも補充作業を作成できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-143">Warehouse slotting allows you to create replenishment work at any time based on order demand.</span></span>

- <span data-ttu-id="dd6dc-144">**ウェーブ ラベル印刷の機能強化 (バージョン 10.0.2 およびバージョン 10.0.4 以降で使用可能)**:</span><span class="sxs-lookup"><span data-stu-id="dd6dc-144">**Wave label printing enhancements (available since version 10.0.2 and version 10.0.4)**:</span></span>

  - <span data-ttu-id="dd6dc-145">コンテナー詰め機能を使用せずに、単一の作業明細行でのカートン数に従ってラベルを印刷できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-145">Allow for labels to be printed according to number of cartons on a single work line, without using the containerization feature.</span></span>

  - <span data-ttu-id="dd6dc-146">ラベルの列挙が含まれます (1/124、2/124…124/124)。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-146">Include an enumeration of the labels (1/124, 2/124…124/124).</span></span>

  - <span data-ttu-id="dd6dc-147">BOL (船荷証券) を作成してラベルに印刷することができます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-147">Allow for BOL (bill of lading) to be created and printed on label.</span></span>

  - <span data-ttu-id="dd6dc-148">カートンごとに固有のシリアル配送コンテナー コード (SSCC) を作成して、ラベルに含めることができます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-148">Allow a unique Serial Shipping Container Code (SSCC) to be created per carton and included on a label.</span></span> 

  - <span data-ttu-id="dd6dc-149">BOL および SSCC 番号に対して GS1 準拠の番号シーケンスを作成できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-149">Allow for creation of GS1-compliant number sequence for BOL and SSCC numbers.</span></span>

  - <span data-ttu-id="dd6dc-150">HAZMAT コードをラベルに含めることができます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-150">Allow for HAZMAT code to be included on a label.</span></span>

  - <span data-ttu-id="dd6dc-151">ラベルの再印刷のサポート (ハンドヘルド デバイスから)。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-151">Support for reprint of labels (from handheld devices).</span></span>

  - <span data-ttu-id="dd6dc-152">ラベル (短いピッキング シナリオの場合) と再印刷の無効化がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-152">Support for voiding of labels (for short pick scenarios) and reprint.</span></span>

  - <span data-ttu-id="dd6dc-153">ウェーブ ラベル履歴のクリーンアップがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-153">Support for clean-up of wave label history.</span></span>

  <span data-ttu-id="dd6dc-154">これらの修正により、パレット化前のカートンのラベル付けのサポートがより効率的になります。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-154">These amendments will make it more efficient to support labeling of cartons prior to palletizing.</span></span> <span data-ttu-id="dd6dc-155">個々のカートンのスキャンを使用して自動的に注文受領確認を実行する大規模小売業者に出荷する会社をサポートします。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-155">It supports companies shipping to large retailers that perform order receipt confirmation automatically using scanning of each individual carton.</span></span>

- <span data-ttu-id="dd6dc-156">**ウェーブ ステップ コード**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-156">**Wave step code**.</span></span> <span data-ttu-id="dd6dc-157">この機能を使用して、ウェーブ ステップ コードとして使用できるコードを事前に定義できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-157">With this functionality, you can pre-define codes that can be used as wave step codes.</span></span> <span data-ttu-id="dd6dc-158">この機能により不正なステップ コードを入力するリスクがなくなります。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-158">This functionality removes the risk of entering the wrong step code.</span></span> 

- <span data-ttu-id="dd6dc-159">**出荷連結ポリシー:**</span><span class="sxs-lookup"><span data-stu-id="dd6dc-159">**Shipment consolidation policies:**</span></span>
  - <span data-ttu-id="dd6dc-160">**倉庫へのバッチ リリース (出荷連結の強化)**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-160">**Batch release to warehouse (consolidate shipment enhancements)**.</span></span> <span data-ttu-id="dd6dc-161">バージョン 10.0.3 以降で使用可能。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-161">Available since version 10.0.3.</span></span>
  - <span data-ttu-id="dd6dc-162">**積荷計画ワークベンチ**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-162">**Load planning workbench**.</span></span> <span data-ttu-id="dd6dc-163">バージョン 10.0.5 以降で使用可能。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-163">Available since version 10.0.5.</span></span>
  - <span data-ttu-id="dd6dc-164">**出荷連結ワークベンチおよび手動連結**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-164">**Shipment consolidation workbench and manual consolidation**.</span></span> <span data-ttu-id="dd6dc-165">バージョン 10.0.7 以降で使用可能。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-165">Available since version 10.0.7.</span></span> <span data-ttu-id="dd6dc-166">この出荷連結ポリシー機能により、バッチの販売や移動オーダーのリリース時に、出荷の自動連結が可能になります。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-166">This consolidate shipment policies feature allows for automated consolidation of a shipment at the time of batch releasing sales or transfer orders.</span></span> <span data-ttu-id="dd6dc-167">出荷連結ポリシーを設定できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-167">Shipment consolidation policies can be set up.</span></span> <span data-ttu-id="dd6dc-168">ポリシーには、適用できるかを定義するクエリと、倉庫へのリリース時に出荷レベルで積荷明細行を自動的にグループ化する決定を促す修正可能な一連のフィールドがあります。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-168">The policies have queries to define their applicability and a modifiable set of fields driving the decision for grouping load lines on shipment level automatically at release to warehouse.</span></span> <span data-ttu-id="dd6dc-169">手動で倉庫にリリースする場合、未処理の出荷に追加すると同じロジックをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-169">When releasing to warehouse manually, the same logic is triggered when added to open shipments.</span></span> <span data-ttu-id="dd6dc-170">この機能は、倉庫への 5 つのリリースに含まれます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-170">The feature is included at the five release to warehouse places.</span></span> <span data-ttu-id="dd6dc-171">連結ワークベンチを使用すると、手動で連結の詳細な概要を確認し、調整することが可能になります。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-171">The consolidation workbench allows for further manual overview of consolidation and for adjustments.</span></span>

- <span data-ttu-id="dd6dc-172">**遅延プット処理**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-172">**Deferred put processing**.</span></span> <span data-ttu-id="dd6dc-173">バージョン 10.0.4 以降で使用可能。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-173">Available since version 10.0.4.</span></span> <span data-ttu-id="dd6dc-174">これは、倉庫作業者の生産性向上に重点を置いたパフォーマンス関連の機能です。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-174">This is a performance-related feature focused on increasing the productivity of the warehouse worker.</span></span> <span data-ttu-id="dd6dc-175">モバイル デバイスが "フリーズ" する原因になる、プット完了のたびのインベントリ更新のオンライン処理を行う必要がなく、そのプロセスを非同期的に実行できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-175">Instead of requiring online processing of inventory updates each time a put is complete, which “freezes” the mobile device, we will allow for that process to be performed asynchronously.</span></span>

- <span data-ttu-id="dd6dc-176">**出庫の並べ替え**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-176">**Outbound sorting**.</span></span> <span data-ttu-id="dd6dc-177">この機能を使用すると、梱包機能で梱包されたコンテナーからパレットのガイド付き構築が可能です。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-177">This functionality allows for the guided building of pallets from containers packed through the packing functionality.</span></span>

- <span data-ttu-id="dd6dc-178">**場所の容量に対する補充**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-178">**Replenishment over location capacity**.</span></span> <span data-ttu-id="dd6dc-179">これにより、その日に必要なすべての補充作業を作成でき、補充作業の利用可能性が管理されて、ピッキング場所の在庫が不足せず、容量を超えないことが保証されます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-179">This allows all replenishment work to be created that will be needed for the day and manages availability of the replenishment work to ensure that the pick location doesn’t run out of inventory, but also doesn’t go above capacity.</span></span> 

- <span data-ttu-id="dd6dc-180">**計画的クロスドッキング**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-180">**Planned cross docking**.</span></span> <span data-ttu-id="dd6dc-181">この機能により、注文を満たすために必要な在庫数量が、入庫または作成から正しい出荷ドックまたはステージング領域に直接送られる、高度な計画的クロスドッキングが導入されます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-181">This functionality introduces advanced planned cross docking where the inventory quantity required to satisfy an order will be directed to the correct outbound dock or staging area straight from receipt or creation.</span></span> <span data-ttu-id="dd6dc-182">入庫ソースからのすべての残余在庫が、通常のプット アウェイ プロセスを通じて正しい保存場所に送られます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-182">All remaining inventory from the inbound source will be directed to the correct storage location through the regular put away process.</span></span>

- <span data-ttu-id="dd6dc-183">**壁へのプット/ストアへのプット**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-183">**Put to wall/Put to store**.</span></span> <span data-ttu-id="dd6dc-184">この機能では、構成可能な基準に基づいて、パッケージ品目ステージング領域への製品の連結が要求されるシナリオを処理できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-184">With this feature, you can handle scenarios where consolidation of product is required to a prepack staging area based on configurable criteria.</span></span> 

- <span data-ttu-id="dd6dc-185">**クロスドッキングのための自動リリース出荷**。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-185">**Auto release shipment for cross docking**.</span></span> <span data-ttu-id="dd6dc-186">この機能により、完了した製造オーダーからの供給についてクロスドッキングが可能になります。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-186">This feature enables cross docking of supply coming out of a finished production order.</span></span> <span data-ttu-id="dd6dc-187">製造オーダーの供給元でクロスドッキング作業を作成するとき、クロスドック テンプレートを設定してクロスドッキングを有効化できます。</span><span class="sxs-lookup"><span data-stu-id="dd6dc-187">When creating cross-dock work with a supply source of a production order, it’s possible to set the cross-dock template up and enable cross docking.</span></span>



<!--feature detail end -->









