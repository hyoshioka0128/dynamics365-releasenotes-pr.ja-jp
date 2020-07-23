---
title: インドの在庫移動オーダーでの単価と原価価格の取り扱いの改善
description: インドの在庫移動オーダーでの単価と原価価格の取り扱いの改善。
author: relnotes
ms.reviewer: kfend
ms.date: 06/05/2020
ms.assetid: 878e53e0-639e-ea11-a812-000d3a563be2
ms.topic: article
ms.service: business-applications
ms.author: epopov
dynamics365pdf: true
ms.openlocfilehash: 6c4c1161c816d950a4d43cb0ea820d289737374f
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3441383"
---
# <a name="improvements-in-unit-price-and-cost-price-handling-in-stock-transfer-orders-for-india"></a><span data-ttu-id="0140a-103">インドの在庫移動オーダーでの単価と原価価格の取り扱いの改善</span><span class="sxs-lookup"><span data-stu-id="0140a-103">Improvements in unit price and cost price handling in Stock transfer orders for India</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="0140a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0140a-104">Enabled for</span></span>    |  <span data-ttu-id="0140a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0140a-105">Public preview</span></span> | <span data-ttu-id="0140a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="0140a-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0140a-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="0140a-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="0140a-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0140a-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0140a-109">2020 年 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="0140a-109">May 29, 2020</span></span>| <span data-ttu-id="0140a-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="0140a-110">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="0140a-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0140a-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0140a-112">在庫移動機能は、インドのお客様が現地の税法に準拠するために使用します。</span><span class="sxs-lookup"><span data-stu-id="0140a-112">The Stock transfer functionality is used by customers in India to be compliant with local tax regulations.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0140a-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0140a-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0140a-114">この機能では、インドの在庫移動オーダー機能に以下の改善が加えられています。</span><span class="sxs-lookup"><span data-stu-id="0140a-114">This feature introduces the following improvements in the Stock transfer order functionality for India:</span></span>

- <span data-ttu-id="0140a-115">**移動タイプ**と**価格タイプ**の既定値は、**在庫および倉庫管理パラメーター**で構成できます。</span><span class="sxs-lookup"><span data-stu-id="0140a-115">Default values of **Transfer type** and **Price type** can be configured in **Inventory and warehouse management parameters**.</span></span>
- <span data-ttu-id="0140a-116">在庫移動オーダー明細行の単価は、最初の出荷が明細行に転記されるまで、明細行に指定された在庫分析コードに基づいて正しく再計算されます。</span><span class="sxs-lookup"><span data-stu-id="0140a-116">Unit price on a stock transfer order line is correctly recalculated based on the inventory dimensions specified on the line until the first shipment is posted for the line.</span></span>
- <span data-ttu-id="0140a-117">単価がゼロの在庫移動オーダー明細行の出荷を防ぐことができます。</span><span class="sxs-lookup"><span data-stu-id="0140a-117">Shipment of a stock transfer order line having a unit price of zero can be prevented.</span></span>
- <span data-ttu-id="0140a-118">部分的な出荷または入荷、バッチ管理品目などの場合の在庫移動オーダーには、正しい在庫原価が転記されます。</span><span class="sxs-lookup"><span data-stu-id="0140a-118">Correct inventory costs are posted for stock transfer orders in case of partial shipments or receipts, batch-controlled items, and more.</span></span>
- <span data-ttu-id="0140a-119">単価が品目の在庫原価価格と異なる場合、在庫移動明細行の出荷または入荷時に未実現の利益または損失は転記されません。</span><span class="sxs-lookup"><span data-stu-id="0140a-119">Unrealized profit or loss is not posted upon the  shipment or receipt of a stock transfer line if the unit price differs from the inventory cost price of the item.</span></span>

<span data-ttu-id="0140a-120">この機能では、在庫移動オーダー明細行の測定単位の変更も制限されます。</span><span class="sxs-lookup"><span data-stu-id="0140a-120">The feature also restricts changing unit of measure in stock transfer order lines.</span></span>

<span data-ttu-id="0140a-121">**機能管理**で **(インド) 在庫移動オーダーの単価と原価価格の取り扱いの改善**機能を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="0140a-121">The feature **(India) Improvements in unit price and cost price handling in Stock transfer orders** must be enabled in **Feature management**.</span></span>
<!--feature detail end -->









