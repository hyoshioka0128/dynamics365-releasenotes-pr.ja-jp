---
title: リード タイムと稼働日に基づいて発注書の配送日を計算する (公的機関)
description: 仕入先のリード タイムと組織の稼働日カレンダーに基づいて、発注書明細行の配送日を計算します。 この機能は公的機関の構成にのみ適用されます。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/15/2020
ms.assetid: 002d1922-021e-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: mkirknel
dynamics365pdf: true
ms.openlocfilehash: e61b9def6da16182b51e098132b265976d37520d
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273755"
---
# <a name="calculate-po-delivery-date-based-on-lead-times-and-working-days-public-sector"></a><span data-ttu-id="13c7a-104">リード タイムと稼働日に基づいて発注書の配送日を計算する (公的機関)</span><span class="sxs-lookup"><span data-stu-id="13c7a-104">Calculate PO delivery date based on lead times and working days (public sector)</span></span>


| <span data-ttu-id="13c7a-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="13c7a-105">Enabled for</span></span>    |  <span data-ttu-id="13c7a-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="13c7a-106">Public preview</span></span> | <span data-ttu-id="13c7a-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="13c7a-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="13c7a-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="13c7a-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="13c7a-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="13c7a-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="13c7a-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="13c7a-110">Feb 3, 2020</span></span>| <span data-ttu-id="13c7a-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="13c7a-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="13c7a-112">2020 年 4 月 6 日</span><span class="sxs-lookup"><span data-stu-id="13c7a-112">Apr 6, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="13c7a-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="13c7a-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="13c7a-114">仕入先のリード タイムと組織の稼働日カレンダーに基づいて、明細行の配送日を計算します。</span><span class="sxs-lookup"><span data-stu-id="13c7a-114">Calculate a delivery date for a line based on a vendor's lead time and your organization's working-days calendar.</span></span><span data-ttu-id="13c7a-115">仕入先は各明細行のリード タイムを入力できます。</span><span class="sxs-lookup"><span data-stu-id="13c7a-115"> Vendors can enter a lead time for each line.</span></span><span data-ttu-id="13c7a-116">発注書が確認されると、リード タイムと稼働日カレンダーに基づいて、確認日付から明細行の配送日が計算されます。</span><span class="sxs-lookup"><span data-stu-id="13c7a-116"> When a purchase order is confirmed, a delivery date for a line is calculated from the confirmation date, based on the lead time and the working-days calendar.</span></span><span data-ttu-id="13c7a-117"> リード タイムが指定されていない場合、配送日は確認日になります。</span><span class="sxs-lookup"><span data-stu-id="13c7a-117"> If no lead time is specified, the delivery date is the confirmation date.</span></span><span data-ttu-id="13c7a-118"> 機能を有効にした後、調達パラメーターを使用して機能を有効にする必要もあります。</span><span class="sxs-lookup"><span data-stu-id="13c7a-118"> After enabling the feature, the admin must also enable the functionality using the procurement and sourcing parameters.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="13c7a-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="13c7a-119">See also</span></span>

<!--docs start-->
<span data-ttu-id="13c7a-120">[リード タイムに基づいた明細行配送日の計算](https://docs.microsoft.com/dynamics365/finance/public-sector/po-delivery-date) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="13c7a-120">[Calculate the delivery date for a line, based on the lead time](https://docs.microsoft.com/dynamics365/finance/public-sector/po-delivery-date) (docs)</span></span>
<!--docs end-->
