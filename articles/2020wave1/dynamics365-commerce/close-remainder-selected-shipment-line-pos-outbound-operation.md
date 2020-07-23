---
title: POS 出庫操作で選択した出荷の残余をクローズする
description: この機能は、出庫操作を通じて販売時点管理 (POS) アプリケーションで移動オーダー在庫を出荷するときに、残余をクローズするオプションをユーザーに提供します。
author: hhainesms
ms.reviewer: josaw
ms.date: 05/26/2020
ms.assetid: a7b16c91-9c6f-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: e6fd1018295ba9c76b0fe65d1c935c8cb5fa616d
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3416421"
---
# <a name="close-remainder-of-a-selected-shipment-line-in-pos-outbound-operation"></a><span data-ttu-id="912b3-103">POS 出庫操作で選択した出荷の残余をクローズする</span><span class="sxs-lookup"><span data-stu-id="912b3-103">Close remainder of a selected shipment line in POS outbound operation</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="912b3-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="912b3-104">Enabled for</span></span>    |  <span data-ttu-id="912b3-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="912b3-105">Public preview</span></span> | <span data-ttu-id="912b3-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="912b3-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="912b3-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="912b3-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="912b3-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="912b3-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="912b3-109">2020 年 5 月 18 日</span><span class="sxs-lookup"><span data-stu-id="912b3-109">May 18, 2020</span></span>| <span data-ttu-id="912b3-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="912b3-110">Jul 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="912b3-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="912b3-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="912b3-112">販売時点管理 (POS) アプリケーションを通じて出庫移動オーダーの在庫を出荷する際、店舗マネージャーは、出荷できるのは要求された数量の一部のみで、入庫を要求している倉庫に要求数量全体を提供することはできないと判断する場合があります。</span><span class="sxs-lookup"><span data-stu-id="912b3-112">While shipping inventory on an outbound transfer order through the point of sale (POS) application, store managers might determine that they are able to ship only a portion of the requested quantity and will never be able to provide the inbound requesting warehouse with the full requested quantity.</span></span> 

<span data-ttu-id="912b3-113">全量が出荷されていなくても、移動オーダー明細が適切にクローズされるようにするために、ユーザーは選択した移動オーダー明細に対して "残余のクローズ" 機能を使用することができます。</span><span class="sxs-lookup"><span data-stu-id="912b3-113">To ensure the transfer order line is properly closed even though the full quantity has not been shipped, users will have the ability to use a "close remainder" function for selected transfer orders lines.</span></span> <span data-ttu-id="912b3-114">このオプションを選択すると、POS からの移動オーダーが処理されるときに部分的な出荷数量がコマース本部に転記され、未処理の出荷残数量はキャンセルされたと見なされます。</span><span class="sxs-lookup"><span data-stu-id="912b3-114">When this option is selected, the partial shipped quantity will be posted to Commerce headquarters when the transfer order is processed from POS, and any open ship remaining quantity will be considered canceled.</span></span> <span data-ttu-id="912b3-115">これにより、将来の出荷のために明細をクローズすることができ、入庫倉庫または店舗は、要求残数量が別途出荷されることを期待できないと明確に理解できるようになります。</span><span class="sxs-lookup"><span data-stu-id="912b3-115">This will allow the line to be closed for future shipment and will ensure the inbound warehouse or store can clearly understand that they should not expect the remaining requested quantity on another shipment.</span></span> 

<span data-ttu-id="912b3-116">この機能は、会社が移動オーダーの "過少配送を許可する" パラメーターを構成し、残余/キャンセル済み数量のクローズが移動オーダー明細に構成された過少配送割合の許容範囲内にある場合にのみ機能します。</span><span class="sxs-lookup"><span data-stu-id="912b3-116">This functionality will work only if the company has configured "allow under delivery" parameters for transfer orders and if the close remainder/canceled quantity is within tolerance of the under-delivery percentage configured for the transfer order line.</span></span>
<!--feature detail end -->









