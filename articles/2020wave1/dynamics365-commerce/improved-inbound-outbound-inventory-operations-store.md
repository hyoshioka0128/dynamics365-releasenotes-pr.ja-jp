---
title: 店舗における在庫の入庫/出庫の操作の改善
description: この機能は、店舗の在庫入荷プロセスと出庫される移動オーダー出荷プロセスに新しいユーザー インターフェイスと機能強化を提供します。
author: hhainesms
ms.reviewer: josaw
ms.date: 03/24/2020
ms.assetid: 02d60471-0300-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 1df76105ee2c97c7184a679d1dceaf3195a9a7f0
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3233311"
---
# <a name="improved-inbound-and-outbound-inventory-operations-in-store"></a><span data-ttu-id="7a94d-103">店舗における在庫の入庫/出庫の操作の改善</span><span class="sxs-lookup"><span data-stu-id="7a94d-103">Improved inbound and outbound inventory operations in store</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="7a94d-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7a94d-104">Enabled for</span></span>    |  <span data-ttu-id="7a94d-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7a94d-105">Public preview</span></span> | <span data-ttu-id="7a94d-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7a94d-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7a94d-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="7a94d-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="7a94d-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7a94d-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7a94d-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="7a94d-109">Feb 3, 2020</span></span>| <span data-ttu-id="7a94d-110">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="7a94d-110">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="7a94d-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7a94d-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7a94d-112">この機能は、ユーザーが在庫の入荷および移動オーダーの作成または履行を実行できるようにする新しい操作の追加によって、販売時点管理 (POS) アプリケーションを改善します。</span><span class="sxs-lookup"><span data-stu-id="7a94d-112">This feature will improve the point of sale (POS) application by adding new operations to allow the user to recieve inventory and create or fulfill transfer orders.</span></span> <span data-ttu-id="7a94d-113">これらの新しい操作は、ユーザーの生産性とデータ処理の信頼性を向上させるように設計されています。</span><span class="sxs-lookup"><span data-stu-id="7a94d-113">These new operations are designed to improve user productivity and data processing reliability.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7a94d-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7a94d-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7a94d-115">この機能では、店舗在庫の入荷および移動オーダー作成と移動オーダー履行のシナリオに共通のワークフローをサポートする、販売時点管理 (POS) の新しいユーザー インターフェイスが作成されます。</span><span class="sxs-lookup"><span data-stu-id="7a94d-115">This feature will create new user interfaces in point of sale (POS) to support workflows common to store inventory receiving and transfer order creation and transfer order fulfillment scenarios.</span></span>  <span data-ttu-id="7a94d-116">新しい**入庫操作**および新しい**出庫操作**を画面レイアウトに追加できるようになります。</span><span class="sxs-lookup"><span data-stu-id="7a94d-116">A new **Inbound operation** and a new  **Outbound operation** will be available to add to screen layouts.</span></span> <span data-ttu-id="7a94d-117">これらにより既存の**ピッキング/入荷** POS 操作を置き換える必要があります。</span><span class="sxs-lookup"><span data-stu-id="7a94d-117">They should replace the existing **Picking/receiving** POS operation.</span></span>

<span data-ttu-id="7a94d-118">新しい操作には、関連する入庫/出庫ドキュメント上の品目を表示する簡単な方法を提供する、バーコード スキャン用に最適化されたユーザー インターフェイスがあります。</span><span class="sxs-lookup"><span data-stu-id="7a94d-118">The new operations will have optimized user interfaces for bar code scanning that will provide an easier way to view items on the related inbound/outbound documents.</span></span> <span data-ttu-id="7a94d-119">POS から Commerce Headquarters (HQ) に領収書または出荷を転記するときの円滑な処理とエラー処理を保証するために入力データを強化および検証するための機能も追加されます。</span><span class="sxs-lookup"><span data-stu-id="7a94d-119">Additional features will also be added to enhance and validate data being entered to ensure smooth processing and error handling when posting receipts or shipments from POS back to Commerce Headquarters (HQ).</span></span>  

<span data-ttu-id="7a94d-120">非同期ドキュメント フレームワークも追加されました。</span><span class="sxs-lookup"><span data-stu-id="7a94d-120">An asynchronous document framework was also added.</span></span> <span data-ttu-id="7a94d-121">このフレームワークにより、ユーザーは領収書または出庫する移動出荷を Commerce Headquarters (HQ) に転記して効率的に処理できるようになります。</span><span class="sxs-lookup"><span data-stu-id="7a94d-121">This framework allows users to post receipts or outbound transfer shipments to Commerce Headquarters (HQ) for efficient processing.</span></span> <span data-ttu-id="7a94d-122">この機能により、ユーザーが大きなドキュメントを Commerce Headquarters (HQ) に転記しようとしたときにピッキング/入荷操作で以前に発生していたタイムアウトの問題や処理エラーが解消されます。</span><span class="sxs-lookup"><span data-stu-id="7a94d-122">This functionality eliminates previous time-out issues and processing errors that occurred in the legacy picking/receiving operation when users attempted to post large documents to Commerce Headquarters (HQ).</span></span>

<span data-ttu-id="7a94d-123">この機能は Commerce バージョン 10.0.9 のサンドボックス/トレーニング環境でプレビューおよび使用できます。</span><span class="sxs-lookup"><span data-stu-id="7a94d-123">This feature is available for preview and use in sandbox/training environments in  Commerce version 10.0.9.</span></span> <span data-ttu-id="7a94d-124">Commerce バージョン 10.0.10 ではさらに安定化されます。</span><span class="sxs-lookup"><span data-stu-id="7a94d-124">It will be further stabilized in  Commerce version 10.0.10.</span></span> <span data-ttu-id="7a94d-125">バージョン 10.0.10 より後の運用環境では、これらの新しい操作を POS レイアウトに追加することを検討することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="7a94d-125">We recommend you consider adding these new operations to your POS layout in a production environment after version 10.0.10.</span></span>  <span data-ttu-id="7a94d-126">従来の**ピッキング/入荷**操作は製品の投資分野ではなくなるため、**ピッキング/入荷**操作から**入庫**および**出庫**操作に移行することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="7a94d-126">The legacy **Picking/receiving** operation will no longer be an investment area for the product, therefore we recommend a transition from the **Picking/receiving** operation to the **Inbound** and **Outbound** operation.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="7a94d-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="7a94d-127">See also</span></span>


<!--docs start-->
<span data-ttu-id="7a94d-128">[コマース ホーム ページ](https://docs.microsoft.com/dynamics365/commerce/) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="7a94d-128">[Commerce home page](https://docs.microsoft.com/dynamics365/commerce/) (docs)</span></span>
<!--docs end-->

