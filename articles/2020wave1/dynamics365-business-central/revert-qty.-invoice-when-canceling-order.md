---
title: 注文をキャンセルする場合、請求書に対して数量を元に戻します
description: 請求書をキャンセルすると、請求された数量が元に戻され、元の注文で請求書の数量がリセットされるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 04/06/2020
ms.assetid: a4becc12-3aef-e911-a812-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 77e5388c2bf2e8202f4e3f8d795f32446c84dd2f
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255851"
---
# <a name="revert-qty-to-invoice-when-canceling-order"></a><span data-ttu-id="613b5-103">注文をキャンセルする場合、請求書に対して数量を元に戻します</span><span class="sxs-lookup"><span data-stu-id="613b5-103">Revert Qty. to Invoice when canceling order</span></span>


| <span data-ttu-id="613b5-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="613b5-104">Enabled for</span></span>    |  <span data-ttu-id="613b5-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="613b5-105">Public preview</span></span> | <span data-ttu-id="613b5-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="613b5-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="613b5-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="613b5-107">End users, automatically</span></span>|<span data-ttu-id="613b5-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="613b5-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="613b5-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="613b5-109">Feb 1, 2020</span></span>| <span data-ttu-id="613b5-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="613b5-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="613b5-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="613b5-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="613b5-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="613b5-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="613b5-113">注文の部分的な出荷/入庫と請求は、今日のビジネスでは一般的な慣行です。</span><span class="sxs-lookup"><span data-stu-id="613b5-113">Partial shipping/receiving and invoicing of orders are common practices in today's business.</span></span> <span data-ttu-id="613b5-114">このコア プロセスで間違いが発生した場合、修正プロセスを追跡する堅牢で簡単な方法が存在することが重要であり、それによって従業員の生産性が維持されます。</span><span class="sxs-lookup"><span data-stu-id="613b5-114">As mistakes happen in these core processes, it is important to have robust and easy ways to follow the correction process, thereby keeping employees productive.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="613b5-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="613b5-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="613b5-116">元の注文から作成された請求書をキャンセルすることで、元の注文の請求済数量を簡単に修正できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="613b5-116">You can now easily correct invoiced quantities on originating orders by canceling invoices created from them.</span></span> <span data-ttu-id="613b5-117">元の注文の **請求書の数量** フィールドは自動的に更新されます。</span><span class="sxs-lookup"><span data-stu-id="613b5-117">The **Qty. to Invoice** field on the originating order is automatically updated.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="613b5-118">フィードバック</span><span class="sxs-lookup"><span data-stu-id="613b5-118">Tell us what you think</span></span>
<span data-ttu-id="613b5-119">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="613b5-119">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="613b5-120">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="613b5-120">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="613b5-121">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="613b5-121">Thank you for your idea</span></span>
<span data-ttu-id="613b5-122">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=e64f533a-783c-e911-867a-0003ff689eb8)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="613b5-122">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=e64f533a-783c-e911-867a-0003ff689eb8).</span></span> <span data-ttu-id="613b5-123">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="613b5-123">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="613b5-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="613b5-124">See also</span></span>

<!--docs start-->
<span data-ttu-id="613b5-125">[転記された売上請求書を取り消すには](https://docs.microsoft.com/dynamics365/business-central/sales-how-correct-cancel-sales-invoice#to-cancel-a-posted-sales-invoice) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="613b5-125">[To cancel a posted sales invoice](https://docs.microsoft.com/dynamics365/business-central/sales-how-correct-cancel-sales-invoice#to-cancel-a-posted-sales-invoice) (docs)</span></span>
<!--docs end-->
