---
title: cXML による発注書の配信
description: cXML による発注書の配信
author: relnotes
ms.reviewer: josaw
ms.date: 08/02/2019
ms.assetid: 3e62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: lcash
dynamics365pdf: true
ms.openlocfilehash: 90334ac841ab675dbb39985479329f6676521dac
ms.sourcegitcommit: 5d6e90743e29603bfc5d06566a6966de05931982
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/29/2019
ms.locfileid: "2669127"
---
# <a name="purchase-order-delivery-via-cxml"></a><span data-ttu-id="eeace-103">cXML による発注書の配信</span><span class="sxs-lookup"><span data-stu-id="eeace-103">Purchase-order delivery via cXML</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="eeace-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="eeace-104">Enabled for</span></span>    |  <span data-ttu-id="eeace-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="eeace-105">Public preview</span></span> | <span data-ttu-id="eeace-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="eeace-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="eeace-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="eeace-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="eeace-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="eeace-108">Sep 2019</span></span>| <span data-ttu-id="eeace-109">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="eeace-109">Nov 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="eeace-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="eeace-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="eeace-111">調達組織は、外部カタログを有効にし、従業員がサプライヤーの eコマース サイトから直接購入できるようにすることで、運用効率を高め、組織に付加価値サービスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="eeace-111">Procurement organizations can gain operational efficiencies and provide value-added service to their organization by enabling external catalogs and allowing employees to purchase directly from suppliers’ e-commerce sites.</span></span> <span data-ttu-id="eeace-112">要求が返され、承認されて、発注書に変換されるとき、ベンダーに発注書を返送する通信は手動で行われます。</span><span class="sxs-lookup"><span data-stu-id="eeace-112">When the requisition is returned, approved, and converted to a purchase order, the communication of the purchase order back to the vendor is manual.</span></span> <span data-ttu-id="eeace-113">この機能拡張により、cXML 発注書要求メッセージのサポートが追加されました。</span><span class="sxs-lookup"><span data-stu-id="eeace-113">With this enhancement, we have added support for the cXML Purchase Order Request message.</span></span> <span data-ttu-id="eeace-114">サプライヤーが発注書の受け取りをサポートしている場合、この機能に対してベンダーを有効にできます。</span><span class="sxs-lookup"><span data-stu-id="eeace-114">Vendors can be enabled for this feature if your supplier supports receiving the purchase order.</span></span> <span data-ttu-id="eeace-115">追加の設定とパラメーターは、外部カタログの構成によって有効になります。</span><span class="sxs-lookup"><span data-stu-id="eeace-115">Additional setup and parameters are enabled through the external catalog configuration.</span></span> 

<span data-ttu-id="eeace-116">![発注書の既定値](media/purchase-order-delivery-via-cxml-1.png "発注書の既定値")</span><span class="sxs-lookup"><span data-stu-id="eeace-116">![Purchase order defaults](media/purchase-order-delivery-via-cxml-1.png "Purchase order defaults")</span></span> 

<span data-ttu-id="eeace-117">購買された注文は確認済みの発注書を使用して送信されます。</span><span class="sxs-lookup"><span data-stu-id="eeace-117">Purchased orders are sent using confirmed purchase orders.</span></span> <span data-ttu-id="eeace-118">調達チームは、注文を送信する発注書のバックグラウンド処理を有効化し、発注書の確認を監視することができます。</span><span class="sxs-lookup"><span data-stu-id="eeace-118">The procurement team can enable background processing for the purchase order sending the order, and they can monitor the acknowledgment of purchase orders.</span></span> 


<!--feature detail end -->




