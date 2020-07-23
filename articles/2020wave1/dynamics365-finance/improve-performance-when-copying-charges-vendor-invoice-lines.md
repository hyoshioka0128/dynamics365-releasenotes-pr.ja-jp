---
title: 仕入先請求書明細行に請求金額をコピーする場合のパフォーマンスを向上させる
description: この機能により、発注書明細行から仕入先請求書明細行への請求金額のコピーが高速になります。
author: relnotes
ms.reviewer: roschlom
ms.date: 05/11/2020
ms.assetid: 0a2ba767-ab4d-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 5f4f5dc54f719b6c73add265a135c306b0ee0537
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3381257"
---
# <a name="improve-performance-when-copying-charges-to-vendor-invoice-lines"></a><span data-ttu-id="5398b-103">仕入先請求書明細行に請求金額をコピーする場合のパフォーマンスを向上させる</span><span class="sxs-lookup"><span data-stu-id="5398b-103">Improve performance when copying charges to vendor invoice lines</span></span>


| <span data-ttu-id="5398b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="5398b-104">Enabled for</span></span>    |  <span data-ttu-id="5398b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5398b-105">Public preview</span></span> | <span data-ttu-id="5398b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="5398b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5398b-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="5398b-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="5398b-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="5398b-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="5398b-109">2020 年 5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="5398b-109">May 8, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="5398b-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5398b-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5398b-111">パフォーマンスの向上により、請求書を承認し、請求書に含まれる情報の正確性に責任を持つ事務職やスタッフが請求書を迅速に利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="5398b-111">Improving the performance makes the invoice readily available to clerks and staff who approve invoices and who have responsibility for the accuracy of the information the invoices contain.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5398b-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5398b-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5398b-113">ほとんどの場合、請求書を作成するとき、または請求書ドキュメントの明細オプションの既定の数量を変更するときに、この機能強化に気付きます。</span><span class="sxs-lookup"><span data-stu-id="5398b-113">You’ll most likely notice this enhancement when creating an invoice or changing the Default quantity for lines option on an invoice document.</span></span> <span data-ttu-id="5398b-114">パフォーマンスの向上により、請求書情報の正確性に責任を持つ事務職や承認者が請求書を迅速に利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="5398b-114">Improving the performance makes the invoice readily available to clerks and approvers who have responsibility for the accuracy of the invoice information.</span></span>
<!--feature detail end -->









