---
title: トランザクション メール用の新しいイベントとプレースホルダー
description: この機能では、オンラインで購入する顧客に対するトランザクション メールをトリガーするための新しいイベントと拡張機能が提供されます。
author: relnotes
ms.reviewer: josaw
ms.date: 03/17/2020
ms.assetid: 232005e9-451d-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: stuharg
dynamics365pdf: true
ms.openlocfilehash: 55c4e7737b0d44366c532e1b1b3391aabb232f07
ms.sourcegitcommit: 773ea4a9be0440714ed67e25d1ba572a6a25072e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2020
ms.locfileid: "3153884"
---
# <a name="new-events-and-placeholders-for-transactional-emails"></a><span data-ttu-id="c4746-103">トランザクション メール用の新しいイベントとプレースホルダー</span><span class="sxs-lookup"><span data-stu-id="c4746-103">New events and placeholders for transactional emails</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="c4746-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c4746-104">Enabled for</span></span>    |  <span data-ttu-id="c4746-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c4746-105">Public preview</span></span> | <span data-ttu-id="c4746-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c4746-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c4746-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="c4746-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="c4746-108">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="c4746-108">Apr 2020</span></span>| <span data-ttu-id="c4746-109">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="c4746-109">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c4746-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c4746-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c4746-111">オンラインや店舗受け取りで購入する顧客は、トランザクション中の重要なイベントに関するメール通知を受け取ることを期待しています。</span><span class="sxs-lookup"><span data-stu-id="c4746-111">Customers who make online and in-store purchases expect to receive email notifications for key events during the transaction.</span></span> <span data-ttu-id="c4746-112">これらのイベントには、注文の確認、注文の店舗受け取り準備の完了を知らせる通知、出荷の確認などが含まれます。</span><span class="sxs-lookup"><span data-stu-id="c4746-112">These events include confirmation of the order, notification that the order is ready for in-store pickup, and shipping confirmation.</span></span> <span data-ttu-id="c4746-113">また、トランザクション通知は、注文に関するタイムリーで有用なフィードバックを送信して顧客に働きかける機会を小売業者に提供します。</span><span class="sxs-lookup"><span data-stu-id="c4746-113">Transactional notifications also offer the retailer an opportunity to engage with the customer, providing timely and useful feedback about their order.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c4746-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c4746-114">Feature details</span></span>
<!--feature detail start -->
### <a name="transactional-events"></a><span data-ttu-id="c4746-115">トランザクション イベント</span><span class="sxs-lookup"><span data-stu-id="c4746-115">Transactional events</span></span>

<span data-ttu-id="c4746-116">このリリースでは、小売業者は、注文の店舗受け取り準備が完了したときと注文が出荷されたときに顧客にメールを自動送信できます。</span><span class="sxs-lookup"><span data-stu-id="c4746-116">With this release, retailers can automatically send an email to customers when an order is ready for in-store pickup, and when an order ships.</span></span>

| <span data-ttu-id="c4746-117">**イベント**</span><span class="sxs-lookup"><span data-stu-id="c4746-117">**Event**</span></span>                        | <span data-ttu-id="c4746-118">**説明**</span><span class="sxs-lookup"><span data-stu-id="c4746-118">**Description**</span></span>                                              |
| -------------------------------- | ------------------------------------------------------------ |
| <span data-ttu-id="c4746-119">注文の店舗受け取り準備完了</span><span class="sxs-lookup"><span data-stu-id="c4746-119">Order ready for  in-store pickup</span></span> | <span data-ttu-id="c4746-120">modeofdelivery が "顧客による受け取り" に設定されている注文が梱包済としてマークされたときにトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="c4746-120">Triggered when an order with modeofdelivery set to "Customer pickup" is marked as  packed.</span></span> |
| <span data-ttu-id="c4746-121">注文出荷済</span><span class="sxs-lookup"><span data-stu-id="c4746-121">Order shipped</span></span>                    | <span data-ttu-id="c4746-122">modeofdelivery が "標準" の注文が請求されたときにトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="c4746-122">Triggered when an order whose modeofdelivery is "Standard" is invoiced.</span></span> |


### <a name="new-placeholders"></a><span data-ttu-id="c4746-123">新しいプレースホルダー</span><span class="sxs-lookup"><span data-stu-id="c4746-123">New placeholders</span></span>

<span data-ttu-id="c4746-124">より充実した情報量の多い顧客向けメールを作成するために、追加のプレースホルダーも HTML メール テンプレートで利用可能になります。</span><span class="sxs-lookup"><span data-stu-id="c4746-124">Additional placeholders will also be made available for use by HTML email templates for creating a richer and more informative email for the customer.</span></span> 

 
<span data-ttu-id="c4746-125">**ヘッダー**</span><span class="sxs-lookup"><span data-stu-id="c4746-125">**Header**</span></span>

| <span data-ttu-id="c4746-126">**プレースホルダー名**</span><span class="sxs-lookup"><span data-stu-id="c4746-126">**Placeholder name**</span></span> | <span data-ttu-id="c4746-127">**プレースホルダーの説明**</span><span class="sxs-lookup"><span data-stu-id="c4746-127">**Placeholder description**</span></span>                                  |
| -------------------- | ------------------------------------------------------------ |
| <span data-ttu-id="c4746-128">%ordernetamount%</span><span class="sxs-lookup"><span data-stu-id="c4746-128">%ordernetamount%</span></span>     | <span data-ttu-id="c4746-129">割引、課税前金額、送料、またはギフト カード控除の適用を含めた注文の小計。</span><span class="sxs-lookup"><span data-stu-id="c4746-129">Order subtotal including discounts, before tax, shipping, or gift card deductions are applied.</span></span> |
| <span data-ttu-id="c4746-130">%storename%</span><span class="sxs-lookup"><span data-stu-id="c4746-130">%storename%</span></span>          | <span data-ttu-id="c4746-131">店舗受け取り用の小売店の名前。</span><span class="sxs-lookup"><span data-stu-id="c4746-131">Name of the retail store for in-store pickup.</span></span>               |

 
<span data-ttu-id="c4746-132">**明細行**</span><span class="sxs-lookup"><span data-stu-id="c4746-132">**Line**</span></span>

| <span data-ttu-id="c4746-133">**プレースホルダー名**</span><span class="sxs-lookup"><span data-stu-id="c4746-133">**Placeholder name**</span></span>              | <span data-ttu-id="c4746-134">**プレースホルダーの説明**</span><span class="sxs-lookup"><span data-stu-id="c4746-134">**Placeholder description**</span></span>                                  |
| --------------------------------- | ------------------------------------------------------------ |
| <span data-ttu-id="c4746-135">%productid%</span><span class="sxs-lookup"><span data-stu-id="c4746-135">%productid%</span></span>                       | <span data-ttu-id="c4746-136">製品の ID。</span><span class="sxs-lookup"><span data-stu-id="c4746-136">ID of the product.</span></span> <span data-ttu-id="c4746-137">この ID を使用して、eコマース サイトの製品説明ページを開く URL を構築することができます。</span><span class="sxs-lookup"><span data-stu-id="c4746-137">The ID can be used to assemble a URL that opens the product description page on your e-commerce site.</span></span> |
| <span data-ttu-id="c4746-138">%linequantity_withoutunit%</span><span class="sxs-lookup"><span data-stu-id="c4746-138">%linequantity_withoutunit%</span></span>        | <span data-ttu-id="c4746-139">測定単位 (UOM) が追加されていない製品の数量。</span><span class="sxs-lookup"><span data-stu-id="c4746-139">Quantity of product without the unit of measure (UOM) appended.</span></span> |
| <span data-ttu-id="c4746-140">%linequantitypicked_withoutunit%</span><span class="sxs-lookup"><span data-stu-id="c4746-140">%linequantitypicked_withoutunit%</span></span>  | <span data-ttu-id="c4746-141">UOM なしの受け取り製品の数量。</span><span class="sxs-lookup"><span data-stu-id="c4746-141">Quantity of product picked without UOM.</span></span>                    |
| <span data-ttu-id="c4746-142">%linequantitypacked_withoutunit%</span><span class="sxs-lookup"><span data-stu-id="c4746-142">%linequantitypacked_withoutunit%</span></span>  | <span data-ttu-id="c4746-143">UOM が追加されていない梱包済製品の数量。</span><span class="sxs-lookup"><span data-stu-id="c4746-143">Quantity of  product packed without UOM.</span></span> <span data-ttu-id="c4746-144">このプレースホルダーを ‘注文の受け取り準備完了’ イベントと共に使用して、受け取り準備が完了した数量 (注文された数量と異なる場合があります) を示します。</span><span class="sxs-lookup"><span data-stu-id="c4746-144">Use this placeholder with the ‘Order Ready For Pickup’ event to indicate the quantity that is ready for pickup (which might differ from the quantity ordered).</span></span> |
| <span data-ttu-id="c4746-145">%linequantityshipped_withoutunit%</span><span class="sxs-lookup"><span data-stu-id="c4746-145">%linequantityshipped_withoutunit%</span></span> | <span data-ttu-id="c4746-146">UOM なしの出荷済数量。</span><span class="sxs-lookup"><span data-stu-id="c4746-146">Quantity shipped for the line without UOM.</span></span> <span data-ttu-id="c4746-147">このプレースホルダーを ‘注文出荷済’ イベントと共に使用して、実際に出荷された数量 (注文された数量と異なる場合があります) を示します。</span><span class="sxs-lookup"><span data-stu-id="c4746-147">Use this placeholder with the ‘Order Shipped’ event to indicate the quantity that was actually shipped (which might differ from the quantity ordered).</span></span> |
<!--feature detail end -->









