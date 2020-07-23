---
title: インバウンドおよびアウトバウンドのロジスティクスの改善
description: この機能は、倉庫管理システムを強化するさまざまな機能を集約します。 ほとんどは 2019 年リリース ウェーブ 2 の間にテスト機能として徐々にリリースされました。
author: relnotes
ms.reviewer: kamaybac
ms.date: 06/25/2020
ms.assetid: 6214e28b-8bcb-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: f3f9fc0c29d9a4a2614c32cd5e779296bc8d7ea4
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3522655"
---
# <a name="inbound-and-outbound-logistics-improvements"></a><span data-ttu-id="446f0-104">インバウンドおよびアウトバウンドのロジスティクスの改善</span><span class="sxs-lookup"><span data-stu-id="446f0-104">Inbound and outbound logistics improvements</span></span>


| <span data-ttu-id="446f0-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="446f0-105">Enabled for</span></span>    |  <span data-ttu-id="446f0-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="446f0-106">Public preview</span></span> | <span data-ttu-id="446f0-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="446f0-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="446f0-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="446f0-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="446f0-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="446f0-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="446f0-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="446f0-110">Feb 3, 2020</span></span>| <span data-ttu-id="446f0-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="446f0-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="446f0-112">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="446f0-112">Apr 3, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="446f0-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="446f0-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="446f0-114">これらの機能のほとんどは 2019 年ウェーブ 2 の期間中にテスト機能としてリリースされました。</span><span class="sxs-lookup"><span data-stu-id="446f0-114">Most of these features have been released as flighted during 2019 wave 2 timeframe.</span></span> <span data-ttu-id="446f0-115">これらは現在パブリック プレビューとしてリリースされています。顧客は Dynamics 365 Supply Chain Management バージョン 10.0.9 の **機能管理** を介して、これらの機能を運用環境に含めることができます。</span><span class="sxs-lookup"><span data-stu-id="446f0-115">They are now released as public preview and customers have the ability to include these features in production environment through **Feature management** from Dynamics 365 Supply Chain Management version 10.0.9.</span></span>

<span data-ttu-id="446f0-116">入庫:</span><span class="sxs-lookup"><span data-stu-id="446f0-116">Inbound:</span></span>

- <span data-ttu-id="446f0-117">**品質チェック**。</span><span class="sxs-lookup"><span data-stu-id="446f0-117">**Quality check**.</span></span> <span data-ttu-id="446f0-118">この機能を使用すると、入庫ドック エリアへの入庫時にその場で迅速な品質チェックを実行できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-118">With this functionality, you can perform rapid quality checks on the spot at the time of receiving to the inbound dock area.</span></span>

- <span data-ttu-id="446f0-119">**プット アウェイ クラスター**。</span><span class="sxs-lookup"><span data-stu-id="446f0-119">**Put away clusters**.</span></span> <span data-ttu-id="446f0-120">これは、一度に複数のライセンス プレートを選択して、それらを別の場所に在庫受入する方法です。</span><span class="sxs-lookup"><span data-stu-id="446f0-120">This is a way to pick multiple license plates at once and take them for a putaway to different locations.</span></span> <span data-ttu-id="446f0-121">多くのライセンス プレートが在庫の完全なパレットではない小売企業に非常に便利です。</span><span class="sxs-lookup"><span data-stu-id="446f0-121">It is very useful for retail where many license plates are not full pallets of inventory.</span></span>

<span data-ttu-id="446f0-122">倉庫オペレーション:</span><span class="sxs-lookup"><span data-stu-id="446f0-122">Warehouse operations:</span></span>

- <span data-ttu-id="446f0-123">**梱包製品分析コード**。</span><span class="sxs-lookup"><span data-stu-id="446f0-123">**Packaging product dimensions**.</span></span> <span data-ttu-id="446f0-124">これによりユーザーは、品目が倉庫 (ストレージ) に保管されているとき、梱包用の箱に梱包されているとき、複数の箱に梱包されているとき (入れ子の梱包) に対して、一連の異なる分析コードを使用できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-124">This allows users to have different sets of dimensions for when an item is being stored in the warehouse (storage), being packed into a box for packing, and being packed into a box with more of itself (nested packing).</span></span> 

- <span data-ttu-id="446f0-125">**品目の連結場所の使用率**。</span><span class="sxs-lookup"><span data-stu-id="446f0-125">**Item consolidation – location utilization**.</span></span> <span data-ttu-id="446f0-126">新しい場所利用率フォームは、倉庫管理者が倉庫全体の場所の容積利用率を簡単に表示してフィルターするツールとして機能します。</span><span class="sxs-lookup"><span data-stu-id="446f0-126">The new location utilization form serves as a tool to warehouse managers to easily view and filter the volumetric utilization of location across the warehouse.</span></span>

- <span data-ttu-id="446f0-127">**場所ライセンス プレートの配置**。</span><span class="sxs-lookup"><span data-stu-id="446f0-127">**Location license plate positioning**.</span></span> <span data-ttu-id="446f0-128">こにより、ダブル ディープ パレット ラックなど、ユーザーは LP がマルチ パレットの場所のどこに配置されたかを表示できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-128">This allows the user to see where the LP is located in a multi-pallet location, such as double-deep pallet racking.</span></span> <span data-ttu-id="446f0-129">この機能は、ロケーションに配置する各ライセンス プレートのライセンス プレートに、順序番号を追加します。</span><span class="sxs-lookup"><span data-stu-id="446f0-129">This functionality adds a sequence number to the license plate for each license plate that is put to a location.</span></span> 

- <span data-ttu-id="446f0-130">**場所と製品分析コードの混合**。</span><span class="sxs-lookup"><span data-stu-id="446f0-130">**Location product dimension mixing**.</span></span> <span data-ttu-id="446f0-131">この新しいロケーション プロファイル機能により、ファッション業界など、分析コードのある製品や製品バリアントを使用する場合に、場所の管理が改善されます。</span><span class="sxs-lookup"><span data-stu-id="446f0-131">This new location profile functionality enables better location managing when using product variants or products with dimensions, such as with the fashion industry.</span></span> <span data-ttu-id="446f0-132">構成、色、スタイル、サイズを特定の場所 (プロファイル) に混在させることができるかどうか、これらの分析コードの 1 つのみまたはいくつかの組み合わせのみを同じ場所に配置できるかどうかを決定できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-132">It allows you to decide whether configurations, colors, style, and sizes can be mixed on a certain location (profile) or if only one or a combination of some of those dimensions can be put to the same location.</span></span> 

- <span data-ttu-id="446f0-133">**柔軟な倉庫レベルの分析コード引当**。</span><span class="sxs-lookup"><span data-stu-id="446f0-133">**Flexible warehouse-level dimension reservation**.</span></span> <span data-ttu-id="446f0-134">バージョン 10.0.7 および 10.0.8 以降で使用可能。</span><span class="sxs-lookup"><span data-stu-id="446f0-134">Available since version 10.0.7 and 10.0.8.</span></span> <span data-ttu-id="446f0-135">在庫引当ポリシーに柔軟性を提供するこの機能強化によって、バッチ管理される製品を販売し WMS 対応オペレーションとしてロジスティクスを実行する企業は、製品に関連付けられた在庫引当階層で禁じられている (“batch-below” と呼ばれるタイプになっている) 場合でも、顧客からの特定のバッチの要求を販売注文に登録できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-135">This enhancement introduces flexibility in the inventory reservation policy to allow businesses who sell batch-tracked products and run their logistics as WMS-enabled operations, to register their customers’ requests for specific batches on sales orders even though the inventory reservation hierarchy associated with the product prevents this (by being of type that is known as “batch-below.”)</span></span>

<span data-ttu-id="446f0-136">出庫:</span><span class="sxs-lookup"><span data-stu-id="446f0-136">Outbound:</span></span>

- <span data-ttu-id="446f0-137">**小型パッケージ配送**。</span><span class="sxs-lookup"><span data-stu-id="446f0-137">**Small package shipping**.</span></span> <span data-ttu-id="446f0-138">小型パッケージ配送では、配送業者のログイン資格情報の設定、配送業者の Web サービスで取得したラベルの印刷、顧客のサードパーティ アカウントへの運賃の請求、追加の配送条件、追加の付帯サービスの配送タイプの機能が追加されます。</span><span class="sxs-lookup"><span data-stu-id="446f0-138">Small package shipping adds functionality for setting up carrier login credentials, printing labels received back from carrier web services, charging freight to customer third-party accounts, additional freight terms, and additional accessorial delivery types.</span></span> 

- <span data-ttu-id="446f0-139">**システム主導の作業優先順位**。</span><span class="sxs-lookup"><span data-stu-id="446f0-139">**System-directed work sequencing**.</span></span> <span data-ttu-id="446f0-140">これにより、実行するためにシステムがユーザーに提示する作業指示書を、並べ替えおよびフィルターできます。</span><span class="sxs-lookup"><span data-stu-id="446f0-140">This setup offers the ability to sort and filter which work orders the system will present to the user for execution.</span></span>

- <span data-ttu-id="446f0-141">**積荷構築のウェーブ処理**。</span><span class="sxs-lookup"><span data-stu-id="446f0-141">**Wave load building**.</span></span> <span data-ttu-id="446f0-142">高度な積荷構築により、ウェーブでは、条件を満たす積荷が存在する場合は出荷を既存の積荷に割り当てて、必要な場合は新しい積荷を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="446f0-142">Advanced load building allows the wave to assign the shipment to an existing load, if one exists that meets the criteria, or create a new load if required.</span></span>

- <span data-ttu-id="446f0-143">**倉庫のスロッティング**。</span><span class="sxs-lookup"><span data-stu-id="446f0-143">**Warehouse slotting**.</span></span> <span data-ttu-id="446f0-144">ピッキング場所は、倉庫に注文をリリースする前に補充できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-144">Picking locations can be replenished before releasing orders to the warehouse.</span></span> <span data-ttu-id="446f0-145">倉庫のスロッティングを使用すると、注文の需要に基づいていつでも補充作業を作成できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-145">Warehouse slotting allows you to create replenishment work at any time based on order demand.</span></span>

- <span data-ttu-id="446f0-146">**ウェーブ ラベル印刷の機能強化 (バージョン 10.0.2 およびバージョン 10.0.4 以降で使用可能)**:</span><span class="sxs-lookup"><span data-stu-id="446f0-146">**Wave label printing enhancements (available since version 10.0.2 and version 10.0.4)**:</span></span>

  - <span data-ttu-id="446f0-147">コンテナー詰め機能を使用せずに、単一の作業明細行でのカートン数に従ってラベルを印刷できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-147">Allow for labels to be printed according to number of cartons on a single work line, without using the containerization feature.</span></span>

  - <span data-ttu-id="446f0-148">ラベルの列挙が含まれます (1/124、2/124…124/124)。</span><span class="sxs-lookup"><span data-stu-id="446f0-148">Include an enumeration of the labels (1/124, 2/124…124/124).</span></span>

  - <span data-ttu-id="446f0-149">BOL (船荷証券) を作成してラベルに印刷することができます。</span><span class="sxs-lookup"><span data-stu-id="446f0-149">Allow for BOL (bill of lading) to be created and printed on label.</span></span>

  - <span data-ttu-id="446f0-150">カートンごとに固有のシリアル配送コンテナー コード (SSCC) を作成して、ラベルに含めることができます。</span><span class="sxs-lookup"><span data-stu-id="446f0-150">Allow a unique Serial Shipping Container Code (SSCC) to be created per carton and included on a label.</span></span> 

  - <span data-ttu-id="446f0-151">BOL および SSCC 番号に対して GS1 準拠の番号シーケンスを作成できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-151">Allow for creation of GS1-compliant number sequence for BOL and SSCC numbers.</span></span>

  - <span data-ttu-id="446f0-152">HAZMAT コードをラベルに含めることができます。</span><span class="sxs-lookup"><span data-stu-id="446f0-152">Allow for HAZMAT code to be included on a label.</span></span>

  - <span data-ttu-id="446f0-153">ラベルの再印刷のサポート (ハンドヘルド デバイスから)。</span><span class="sxs-lookup"><span data-stu-id="446f0-153">Support for reprint of labels (from handheld devices).</span></span>

  - <span data-ttu-id="446f0-154">ラベル (短いピッキング シナリオの場合) と再印刷の無効化がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="446f0-154">Support for voiding of labels (for short pick scenarios) and reprint.</span></span>

  - <span data-ttu-id="446f0-155">ウェーブ ラベル履歴のクリーンアップがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="446f0-155">Support for clean-up of wave label history.</span></span>


<span data-ttu-id="446f0-156">これらの修正により、パレット化前のカートンのラベル付けのサポートがより効率的になります。</span><span class="sxs-lookup"><span data-stu-id="446f0-156">These amendments will make it more efficient to support labeling of cartons prior to palletizing.</span></span> <span data-ttu-id="446f0-157">個々のカートンのスキャンを使用して自動的に注文受領確認を実行する大規模小売業者に出荷する会社をサポートします。</span><span class="sxs-lookup"><span data-stu-id="446f0-157">It supports companies shipping to large retailers that perform order receipt confirmation automatically using scanning of each individual carton.</span></span>

- <span data-ttu-id="446f0-158">**ウェーブ ステップ コード**。</span><span class="sxs-lookup"><span data-stu-id="446f0-158">**Wave step code**.</span></span> <span data-ttu-id="446f0-159">この機能を使用して、ウェーブ ステップ コードとして使用できるコードを事前に定義できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-159">With this functionality, you can pre-define codes that can be used as wave step codes.</span></span> <span data-ttu-id="446f0-160">この機能により不正なステップ コードを入力するリスクがなくなります。</span><span class="sxs-lookup"><span data-stu-id="446f0-160">This functionality removes the risk of entering the wrong step code.</span></span> 

- <span data-ttu-id="446f0-161">**出荷連結ポリシー:**</span><span class="sxs-lookup"><span data-stu-id="446f0-161">**Shipment consolidation policies:**</span></span>
  - <span data-ttu-id="446f0-162">**倉庫へのバッチ リリース (出荷連結の強化)**。</span><span class="sxs-lookup"><span data-stu-id="446f0-162">**Batch release to warehouse (consolidate shipment enhancements)**.</span></span> <span data-ttu-id="446f0-163">バージョン 10.0.3 以降で使用可能。</span><span class="sxs-lookup"><span data-stu-id="446f0-163">Available since version 10.0.3.</span></span>
  - <span data-ttu-id="446f0-164">**積荷計画ワークベンチ**。</span><span class="sxs-lookup"><span data-stu-id="446f0-164">**Load planning workbench**.</span></span> <span data-ttu-id="446f0-165">バージョン 10.0.5 以降で使用可能。</span><span class="sxs-lookup"><span data-stu-id="446f0-165">Available since version 10.0.5.</span></span>
  - <span data-ttu-id="446f0-166">**出荷連結ワークベンチおよび手動連結**。</span><span class="sxs-lookup"><span data-stu-id="446f0-166">**Shipment consolidation workbench and manual consolidation**.</span></span> <span data-ttu-id="446f0-167">バージョン 10.0.7 以降で使用可能。</span><span class="sxs-lookup"><span data-stu-id="446f0-167">Available since version 10.0.7.</span></span> <span data-ttu-id="446f0-168">この出荷連結ポリシー機能により、バッチの販売や移動オーダーのリリース時に、出荷の自動連結が可能になります。</span><span class="sxs-lookup"><span data-stu-id="446f0-168">This consolidate shipment policies feature allows for automated consolidation of a shipment at the time of batch releasing sales or transfer orders.</span></span> <span data-ttu-id="446f0-169">出荷連結ポリシーを設定できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-169">Shipment consolidation policies can be set up.</span></span> <span data-ttu-id="446f0-170">ポリシーには、適用できるかを定義するクエリと、倉庫へのリリース時に出荷レベルで積荷明細行を自動的にグループ化する決定を促す修正可能な一連のフィールドがあります。</span><span class="sxs-lookup"><span data-stu-id="446f0-170">The policies have queries to define their applicability and a modifiable set of fields driving the decision for grouping load lines on shipment level automatically at release to warehouse.</span></span> <span data-ttu-id="446f0-171">手動で倉庫にリリースする場合、未処理の出荷に追加すると同じロジックをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="446f0-171">When releasing to warehouse manually, the same logic is triggered when added to open shipments.</span></span> <span data-ttu-id="446f0-172">この機能は、倉庫への 5 つのリリースに含まれます。</span><span class="sxs-lookup"><span data-stu-id="446f0-172">The feature is included at the five release to warehouse places.</span></span> <span data-ttu-id="446f0-173">連結ワークベンチを使用すると、手動で連結の詳細な概要を確認し、調整することが可能になります。</span><span class="sxs-lookup"><span data-stu-id="446f0-173">The consolidation workbench allows for further manual overview of consolidation and for adjustments.</span></span>

- <span data-ttu-id="446f0-174">**遅延プット処理**。</span><span class="sxs-lookup"><span data-stu-id="446f0-174">**Deferred put processing**.</span></span> <span data-ttu-id="446f0-175">バージョン 10.0.4 以降で使用可能。</span><span class="sxs-lookup"><span data-stu-id="446f0-175">Available since version 10.0.4.</span></span> <span data-ttu-id="446f0-176">これは、倉庫作業者の生産性向上に重点を置いたパフォーマンス関連の機能です。</span><span class="sxs-lookup"><span data-stu-id="446f0-176">This is a performance-related feature focused on increasing the productivity of the warehouse worker.</span></span> <span data-ttu-id="446f0-177">モバイル デバイスが "フリーズ" する原因になる、プット完了のたびのインベントリ更新のオンライン処理を行う必要がなく、そのプロセスを非同期的に実行できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-177">Instead of requiring online processing of inventory updates each time a put is complete, which “freezes” the mobile device, we will allow for that process to be performed asynchronously.</span></span>

- <span data-ttu-id="446f0-178">**出庫の並べ替え**。</span><span class="sxs-lookup"><span data-stu-id="446f0-178">**Outbound sorting**.</span></span> <span data-ttu-id="446f0-179">この機能を使用すると、梱包機能で梱包されたコンテナーからパレットのガイド付き構築が可能です。</span><span class="sxs-lookup"><span data-stu-id="446f0-179">This functionality allows for the guided building of pallets from containers packed through the packing functionality.</span></span>

- <span data-ttu-id="446f0-180">**場所の容量に対する補充**。</span><span class="sxs-lookup"><span data-stu-id="446f0-180">**Replenishment over location capacity**.</span></span> <span data-ttu-id="446f0-181">これにより、その日に必要なすべての補充作業を作成でき、補充作業の利用可能性が管理されて、ピッキング場所の在庫が不足せず、容量を超えないことが保証されます。</span><span class="sxs-lookup"><span data-stu-id="446f0-181">This allows all replenishment work to be created that will be needed for the day and manages availability of the replenishment work to ensure that the pick location doesn’t run out of inventory, but also doesn’t go above capacity.</span></span> 

- <span data-ttu-id="446f0-182">**計画的クロスドッキング**。</span><span class="sxs-lookup"><span data-stu-id="446f0-182">**Planned cross docking**.</span></span> <span data-ttu-id="446f0-183">この機能により、注文を満たすために必要な在庫数量が、入庫または作成から正しい出荷ドックまたはステージング領域に直接送られる、高度な計画的クロスドッキングが導入されます。</span><span class="sxs-lookup"><span data-stu-id="446f0-183">This functionality introduces advanced planned cross docking where the inventory quantity required to satisfy an order will be directed to the correct outbound dock or staging area straight from receipt or creation.</span></span> <span data-ttu-id="446f0-184">入庫ソースからのすべての残余在庫が、通常のプット アウェイ プロセスを通じて正しい保存場所に送られます。</span><span class="sxs-lookup"><span data-stu-id="446f0-184">All remaining inventory from the inbound source will be directed to the correct storage location through the regular put away process.</span></span>

- <span data-ttu-id="446f0-185">**壁へのプット/ストアへのプット**。</span><span class="sxs-lookup"><span data-stu-id="446f0-185">**Put to wall/Put to store**.</span></span> <span data-ttu-id="446f0-186">この機能では、構成可能な基準に基づいて、パッケージ品目ステージング領域への製品の連結が要求されるシナリオを処理できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-186">With this feature, you can handle scenarios where consolidation of product is required to a prepack staging area based on configurable criteria.</span></span> 

- <span data-ttu-id="446f0-187">**クロスドッキングのための自動リリース出荷**。</span><span class="sxs-lookup"><span data-stu-id="446f0-187">**Auto release shipment for cross docking**.</span></span> <span data-ttu-id="446f0-188">この機能により、完了した製造オーダーからの供給についてクロスドッキングが可能になります。</span><span class="sxs-lookup"><span data-stu-id="446f0-188">This feature enables cross docking of supply coming out of a finished production order.</span></span> <span data-ttu-id="446f0-189">製造オーダーの供給元でクロスドッキング作業を作成するとき、クロスドック テンプレートを設定してクロスドッキングを有効化できます。</span><span class="sxs-lookup"><span data-stu-id="446f0-189">When creating cross-dock work with a supply source of a production order, it’s possible to set the cross-dock template up and enable cross docking.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="446f0-190">関連項目</span><span class="sxs-lookup"><span data-stu-id="446f0-190">See also</span></span>

<!--docs start-->
<span data-ttu-id="446f0-191">[倉庫管理の概要](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="446f0-191">[Warehouse management overview](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (docs)</span></span>
<!--docs end-->
