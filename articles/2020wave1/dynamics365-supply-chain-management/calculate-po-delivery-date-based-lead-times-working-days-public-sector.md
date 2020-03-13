---
title: リード タイムと稼働日に基づいて発注書の配送日を計算する (公的機関)
description: 仕入先のリード タイムと組織の稼働日カレンダーに基づいて、発注書明細行の配送日を計算します。 この機能は公的機関の構成にのみ適用されます。
author: relnotes
ms.reviewer: roschlom
ms.date: 02/13/2020
ms.assetid: 002d1922-021e-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: lcash
dynamics365pdf: true
ms.openlocfilehash: a714025dfbed9b49c751da44c6fa9b81c9828d0e
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3079436"
---
# <a name="calculate-po-delivery-date-based-on-lead-times-and-working-days-public-sector"></a><span data-ttu-id="9bcd9-104">リード タイムと稼働日に基づいて発注書の配送日を計算する (公的機関)</span><span class="sxs-lookup"><span data-stu-id="9bcd9-104">Calculate PO delivery date based on lead times and working days (public sector)</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="9bcd9-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="9bcd9-105">Enabled for</span></span>    |  <span data-ttu-id="9bcd9-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9bcd9-106">Public preview</span></span> | <span data-ttu-id="9bcd9-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="9bcd9-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="9bcd9-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="9bcd9-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="9bcd9-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="9bcd9-109">Feb 2020</span></span>| <span data-ttu-id="9bcd9-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="9bcd9-110">Apr 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="9bcd9-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9bcd9-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9bcd9-112">仕入先のリード タイムと組織の稼働日カレンダーに基づいて、明細行の配送日を計算します。</span><span class="sxs-lookup"><span data-stu-id="9bcd9-112">Calculate a delivery date for a line based on a vendor's lead time and your organization's working-days calendar.</span></span><span data-ttu-id="9bcd9-113">仕入先は各明細行のリード タイムを入力できます。</span><span class="sxs-lookup"><span data-stu-id="9bcd9-113"> Vendors can enter a lead time for each line.</span></span><span data-ttu-id="9bcd9-114">発注書が確認されると、リード タイムと稼働日カレンダーに基づいて、確認日付から明細行の配送日が計算されます。</span><span class="sxs-lookup"><span data-stu-id="9bcd9-114"> When a purchase order is confirmed, a delivery date for a line is calculated from the confirmation date, based on the lead time and the working-days calendar.</span></span><span data-ttu-id="9bcd9-115">リード タイムが指定されていない場合、配送日は確認日になります。</span><span class="sxs-lookup"><span data-stu-id="9bcd9-115"> If no lead time is specified, the delivery date is the confirmation date.</span></span><span data-ttu-id="9bcd9-116">管理者は、機能を有効にした後、調達パラメーターを使用して機能を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="9bcd9-116"> After the admin enables the feature, the admin must enable the functionality using the procurement and sourcing parameters.</span></span>
<!--feature detail end -->









