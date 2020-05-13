---
title: 仕訳帳の遅延税計算の有効化
description: ユーザーが仕訳帳を作成または変更するときに税計算を遅らせることができます
author: RichardLuan
ms.reviewer: kfend
ms.date: 01/16/2020
ms.assetid: 52767a22-d51f-ea11-a810-000d3a8f004f
ms.topic: article
ms.service: business-applications
ms.author: riluan
dynamics365pdf: true
ms.openlocfilehash: 5857ddd05dadea53027b3257f18763fd26be20c4
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3058598"
---
# <a name="enable-delayed-tax-calculation-on-journals"></a><span data-ttu-id="c6b42-103">仕訳帳の遅延税計算の有効化</span><span class="sxs-lookup"><span data-stu-id="c6b42-103">Enable delayed tax calculation on journals</span></span>


| <span data-ttu-id="c6b42-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c6b42-104">Enabled for</span></span>    |  <span data-ttu-id="c6b42-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c6b42-105">Public preview</span></span> | <span data-ttu-id="c6b42-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c6b42-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c6b42-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="c6b42-107">End users, automatically</span></span>|<span data-ttu-id="c6b42-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c6b42-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c6b42-109">2019 年 10 月 21 日</span><span class="sxs-lookup"><span data-stu-id="c6b42-109">Oct 21, 2019</span></span>| <span data-ttu-id="c6b42-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c6b42-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c6b42-111">2020 年 1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="c6b42-111">Jan 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c6b42-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c6b42-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c6b42-113">この機能により、仕訳帳明細行が複数ある場合の税計算のパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="c6b42-113">This capability improves the performance of tax calculations when there are multiple journal lines.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c6b42-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c6b42-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c6b42-115">既定では、仕訳帳明細行の消費税額は、税関連フィールドが更新されるたびに計算されます。</span><span class="sxs-lookup"><span data-stu-id="c6b42-115">By default, sales tax amounts on journal lines are calculated whenever tax-related fields are updated.</span></span> <span data-ttu-id="c6b42-116">これには、消費税グループと品目消費税グループのフィールドが含まれます。</span><span class="sxs-lookup"><span data-stu-id="c6b42-116">This includes the fields for sales tax groups and item sales tax groups.</span></span> <span data-ttu-id="c6b42-117">仕訳帳明細行を更新すると、すべての使用税の税額が再計算されます。</span><span class="sxs-lookup"><span data-stu-id="c6b42-117">Any update to a journal line causes tax amounts to be recalculated for all journal lines.</span></span> <span data-ttu-id="c6b42-118">この動作により、ユーザーはリアルタイムで計算された税額を確認できますが、仕訳帳明細行の数が非常に多い場合はパフォーマンスにも影響する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="c6b42-118">Although this behavior helps the user see tax amounts calculated in real time, it can also affect performance if the number of journal lines is very large.</span></span>

<span data-ttu-id="c6b42-119">遅延税計算機能を使用すると、仕訳帳の税計算を遅らせることができるため、パフォーマンスの問題を修正できます。</span><span class="sxs-lookup"><span data-stu-id="c6b42-119">The Delayed tax calculation feature lets you delay the tax calculation on journals and therefore helps fix performance issues.</span></span> <span data-ttu-id="c6b42-120">この機能をオンにすると、ユーザーが **消費税** または仕訳帳を選択した場合のみ税額が計算されます。</span><span class="sxs-lookup"><span data-stu-id="c6b42-120">When this feature is turned on, tax amounts are calculated only when a user selects **Sales tax** or posts the journal.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="c6b42-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="c6b42-121">See also</span></span>

<span data-ttu-id="c6b42-122">[仕訳帳の遅延税計算の有効化](https://docs.microsoft.com/dynamics365/finance/general-ledger/enable-delayed-tax-calculation) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c6b42-122">[Enable delayed tax calculation on journals](https://docs.microsoft.com/dynamics365/finance/general-ledger/enable-delayed-tax-calculation) (docs)</span></span>
