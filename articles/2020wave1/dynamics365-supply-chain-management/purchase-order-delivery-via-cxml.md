---
title: cXML による発注書の配信
description: cXML による発注書の配信
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/07/2020
ms.assetid: a5e38966-f51d-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: lcash
dynamics365pdf: true
ms.openlocfilehash: 3d0ddc223667fdb4c83b6a76e8fe3ecadc7b8ad3
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3272259"
---
# <a name="purchase-order-delivery-via-cxml"></a><span data-ttu-id="822a9-103">cXML による発注書の配信</span><span class="sxs-lookup"><span data-stu-id="822a9-103">Purchase order delivery via cXML</span></span>


| <span data-ttu-id="822a9-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="822a9-104">Enabled for</span></span>    |  <span data-ttu-id="822a9-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="822a9-105">Public preview</span></span> | <span data-ttu-id="822a9-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="822a9-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="822a9-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="822a9-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="822a9-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="822a9-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="822a9-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="822a9-109">Feb 3, 2020</span></span>| <span data-ttu-id="822a9-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="822a9-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="822a9-111">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="822a9-111">Apr 3, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="822a9-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="822a9-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="822a9-113">調達組織は、外部カタログを有効にし、従業員がサプライヤーの eコマース サイトから直接購入できるようにすることで、運用効率を高め、組織に付加価値サービスを提供できます。</span><span class="sxs-lookup"><span data-stu-id="822a9-113">Procurement organizations can gain operational efficiencies and provide value-added service to their organization by enabling external catalogs and allowing employees to purchase directly from suppliers’ e-commerce sites.</span></span> <span data-ttu-id="822a9-114">要求が返され、承認されて、発注書に変換されるとき、ベンダーに発注書を返送する通信は手動で行われます。</span><span class="sxs-lookup"><span data-stu-id="822a9-114">When the requisition is returned, approved, and converted to a purchase order, the communication of the purchase order back to the vendor is manual.</span></span> <span data-ttu-id="822a9-115">この機能拡張により、cXML 発注書要求メッセージのサポートが追加されました。</span><span class="sxs-lookup"><span data-stu-id="822a9-115">With this enhancement, we have added support for the cXML purchase order request message.</span></span> <span data-ttu-id="822a9-116">サプライヤーが発注書の受け取りをサポートしている場合、この機能に対してベンダーを有効にできます。</span><span class="sxs-lookup"><span data-stu-id="822a9-116">You can enable vendors for this feature if your supplier supports receiving the purchase order.</span></span> <span data-ttu-id="822a9-117">追加の設定とパラメーターは、外部カタログの構成によって有効になります。</span><span class="sxs-lookup"><span data-stu-id="822a9-117">Additional setup and parameters are enabled through the external catalog configuration.</span></span> 

<!--![Purchase order defaults](media/purchase-order-delivery-via-cxml-1.png "Purchase order defaults")-->

<span data-ttu-id="822a9-118">購買された注文は確認済みの発注書を使用して送信されます。</span><span class="sxs-lookup"><span data-stu-id="822a9-118">Purchased orders are sent using confirmed purchase orders.</span></span> <span data-ttu-id="822a9-119">調達チームは、注文を送信する発注書のバックグラウンド処理を有効にして、発注書の確認を監視できます。</span><span class="sxs-lookup"><span data-stu-id="822a9-119">The procurement team can enable background processing for the purchase order sending the order, and they can monitor the acknowledgment of purchase orders.</span></span>
<!--feature detail end -->









