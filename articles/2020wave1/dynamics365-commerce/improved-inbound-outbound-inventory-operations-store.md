---
title: 店舗における在庫の入庫/出庫の操作の改善
description: この機能は、店舗の在庫入荷プロセスと出庫される移動オーダー出荷プロセスに新しいユーザー インターフェイスと機能強化を提供します。
author: hhainesms
ms.reviewer: josaw
ms.date: 05/04/2020
ms.assetid: 02d60471-0300-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: bf6e2efbd6ed6ca0ce609cee985ebd06a074bcd2
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3349558"
---
# <a name="improved-inbound-and-outbound-inventory-operations-in-store"></a><span data-ttu-id="96c93-103">店舗における在庫の入庫/出庫の操作の改善</span><span class="sxs-lookup"><span data-stu-id="96c93-103">Improved inbound and outbound inventory operations in store</span></span>


| <span data-ttu-id="96c93-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="96c93-104">Enabled for</span></span>    |  <span data-ttu-id="96c93-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="96c93-105">Public preview</span></span> | <span data-ttu-id="96c93-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="96c93-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="96c93-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="96c93-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="96c93-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="96c93-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="96c93-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="96c93-109">Feb 3, 2020</span></span>| <span data-ttu-id="96c93-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="96c93-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="96c93-111">2020 年 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="96c93-111">May 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="96c93-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="96c93-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="96c93-113">この機能は、ユーザーによる在庫の入荷や移動オーダーの作成または履行を可能にするために、新しい操作を追加することによって販売時点管理 (POS) アプリケーションを改善します。</span><span class="sxs-lookup"><span data-stu-id="96c93-113">This feature will improve the point of sale (POS) application by adding new operations to allow the user to receive inventory and create or fulfill transfer orders.</span></span> <span data-ttu-id="96c93-114">これらの新しい操作は、ユーザーの生産性とデータ処理の信頼性を向上させるように設計されています。</span><span class="sxs-lookup"><span data-stu-id="96c93-114">These new operations are designed to improve user productivity and data processing reliability.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="96c93-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="96c93-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="96c93-116">この機能では、店舗在庫の入荷および移動オーダー作成と移動オーダー履行のシナリオに共通のワークフローをサポートする、販売時点管理 (POS) の新しいユーザー インターフェイスが作成されます。</span><span class="sxs-lookup"><span data-stu-id="96c93-116">This feature will create new user interfaces in point of sale (POS) to support workflows common to store inventory receiving and transfer order creation and transfer order fulfillment scenarios.</span></span>  <span data-ttu-id="96c93-117">新しい**入庫操作**および新しい**出庫操作**を画面レイアウトに追加できるようになります。</span><span class="sxs-lookup"><span data-stu-id="96c93-117">A new **Inbound operation** and a new  **Outbound operation** will be available to add to screen layouts.</span></span> <span data-ttu-id="96c93-118">これらにより既存の**ピッキング/入荷** POS 操作を置き換える必要があります。</span><span class="sxs-lookup"><span data-stu-id="96c93-118">They should replace the existing **Picking/receiving** POS operation.</span></span>

<span data-ttu-id="96c93-119">新しい操作には、関連する入庫/出庫ドキュメント上の品目を表示する簡単な方法を提供する、バーコード スキャン用に最適化されたユーザー インターフェイスがあります。</span><span class="sxs-lookup"><span data-stu-id="96c93-119">The new operations will have optimized user interfaces for bar code scanning that will provide an easier way to view items on the related inbound/outbound documents.</span></span> <span data-ttu-id="96c93-120">POS から Commerce Headquarters (HQ) に領収書または出荷を転記するときの円滑な処理とエラー処理を保証するために入力データを強化および検証するための機能も追加されます。</span><span class="sxs-lookup"><span data-stu-id="96c93-120">Additional features will also be added to enhance and validate data being entered to ensure smooth processing and error handling when posting receipts or shipments from POS back to Commerce Headquarters (HQ).</span></span>  

<span data-ttu-id="96c93-121">非同期ドキュメント フレームワークも追加されました。</span><span class="sxs-lookup"><span data-stu-id="96c93-121">An asynchronous document framework was also added.</span></span> <span data-ttu-id="96c93-122">このフレームワークにより、ユーザーは領収書または出庫する移動出荷を HQ に転記して効率的に処理できるようになります。</span><span class="sxs-lookup"><span data-stu-id="96c93-122">This framework allows users to post receipts or outbound transfer shipments to HQ for efficient processing.</span></span> <span data-ttu-id="96c93-123">この機能により、ユーザーが大きなドキュメントを HQ に転記しようとしたときにピッキング/入荷操作で以前に発生していたタイムアウトの問題や処理エラーが解消されます。</span><span class="sxs-lookup"><span data-stu-id="96c93-123">This functionality eliminates previous time-out issues and processing errors that occurred in the legacy picking/receiving operation when users attempted to post large documents to HQ.</span></span>

<span data-ttu-id="96c93-124">この機能は Commerce バージョン 10.0.9 のサンドボックス/トレーニング環境でプレビューおよび使用できます。</span><span class="sxs-lookup"><span data-stu-id="96c93-124">This feature is available for preview and use in sandbox/training environments in  Commerce version 10.0.9.</span></span> <span data-ttu-id="96c93-125">Commerce バージョン 10.0.10 ではさらに安定化されます。</span><span class="sxs-lookup"><span data-stu-id="96c93-125">It will be further stabilized in  Commerce version 10.0.10.</span></span> <span data-ttu-id="96c93-126">バージョン 10.0.10 より後の運用環境では、これらの新しい操作を POS レイアウトに追加することを検討することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="96c93-126">We recommend you consider adding these new operations to your POS layout in a production environment after version 10.0.10.</span></span>  <span data-ttu-id="96c93-127">従来の**ピッキング/入荷**操作は製品の投資分野ではなくなるため、**ピッキング/入荷**操作から**入庫**および**出庫**操作に移行することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="96c93-127">The legacy **Picking/receiving** operation will no longer be an investment area for the product; therefore, we recommend a transition from the **Picking/receiving** operation to the **Inbound** and **Outbound** operation.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="96c93-128">関連項目</span><span class="sxs-lookup"><span data-stu-id="96c93-128">See also</span></span>

<!--docs start-->
<span data-ttu-id="96c93-129">[Commerce のドキュメント](https://docs.microsoft.com/dynamics365/commerce/) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="96c93-129">[Commerce documentation](https://docs.microsoft.com/dynamics365/commerce/) (docs)</span></span>
<!--docs end-->
