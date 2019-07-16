---
title: リード タイムと稼働日に基づいて発注書の配送日を計算する (公的機関)
description: 仕入先のリード タイムと組織の稼働日カレンダーに基づいて、発注書明細行の配送日を計算します。 この機能は公的機関の構成にのみ適用されます。
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 543675a1-3772-e911-a960-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: mkirknel
dynamics365pdf: true
ms.openlocfilehash: 5f561a36c06d8f5e57c0d481e7443a6c19ebdaad
ms.sourcegitcommit: d6ff62c145bfdd7742034a67a29bf75938823eb0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/24/2019
ms.locfileid: "1701997"
---
# <a name="calculate-po-delivery-date-based-on-lead-times-and-working-days-public-sector"></a><span data-ttu-id="094ef-104">リード タイムと稼働日に基づいて発注書の配送日を計算する (公的機関)</span><span class="sxs-lookup"><span data-stu-id="094ef-104">Calculate PO delivery date based on lead times and working days (public sector)</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="094ef-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="094ef-105">Enabled for</span></span>    |  <span data-ttu-id="094ef-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="094ef-106">Public preview</span></span> | <span data-ttu-id="094ef-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="094ef-107">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="094ef-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="094ef-108">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="094ef-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="094ef-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="094ef-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="094ef-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="094ef-111">この機能は、仕入先のコンプライアンスを追跡したい組織に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="094ef-111">This feature is helpful for organizations that want to track vendor compliance.</span></span> <span data-ttu-id="094ef-112">仕入先が RFQ でリード タイムを送信すると、結果の発注書では配送日が自動的に計算されます。</span><span class="sxs-lookup"><span data-stu-id="094ef-112">When a vendor submits a lead time on an RFQ, the delivery date is automatically calculated on the resulting purchase order.</span></span> <span data-ttu-id="094ef-113">購入者はレポートを実行し、元の提案とコミットメントに基づいて仕入先のパフォーマンスを確認できます。</span><span class="sxs-lookup"><span data-stu-id="094ef-113">The purchaser can run reports to view vendor performance based on their original proposals and commitments.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="094ef-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="094ef-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="094ef-115">仕入先のリード タイムと組織の稼働日カレンダーに基づいて、明細行の配送日を計算します。</span><span class="sxs-lookup"><span data-stu-id="094ef-115">Calculate a delivery date for a line based on a vendor's lead time and your organization's working-days calendar.</span></span><span data-ttu-id="094ef-116">仕入先は各明細行のリード タイムを入力できます。</span><span class="sxs-lookup"><span data-stu-id="094ef-116"> Vendors can enter a lead time for each line.</span></span><span data-ttu-id="094ef-117">発注書が確認されると、リード タイムと稼働日カレンダーに基づいて、確認日付から明細行の配送日が計算されます。</span><span class="sxs-lookup"><span data-stu-id="094ef-117"> When a purchase order is confirmed, a delivery date for a line is calculated from the confirmation date, based on the lead time and the working-days calendar.</span></span><span data-ttu-id="094ef-118">リード タイムが指定されていない場合、配送日は確認日になります。</span><span class="sxs-lookup"><span data-stu-id="094ef-118"> If no lead time is specified, the delivery date is the confirmation date.</span></span><span data-ttu-id="094ef-119">管理者が機能を有効にした後、調達パラメーターを使用して機能を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="094ef-119"> After the feature is enabled by the admin, it must be enabled by using the procurement and sourcing parameters.</span></span>
<!--feature detail end -->










