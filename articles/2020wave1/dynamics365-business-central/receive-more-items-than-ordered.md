---
title: 注文量よりも多くの商品を受け取る
description: 注文数量に対する入庫数量について指定された許容範囲に基づいて、発注書と倉庫の超過入庫を許可します。
author: relnotes
ms.reviewer: sgroespe
ms.date: 02/04/2020
ms.assetid: 7c144f9f-4aca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 4a5a05bfa18e20be19ab0bd01a27845259b62e03
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3032432"
---
# <a name="receive-more-items-than-ordered"></a><span data-ttu-id="baa80-103">注文量よりも多くの商品を受け取る</span><span class="sxs-lookup"><span data-stu-id="baa80-103">Receive more items than ordered</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="baa80-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="baa80-104">Enabled for</span></span>    |  <span data-ttu-id="baa80-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="baa80-105">Public preview</span></span> | <span data-ttu-id="baa80-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="baa80-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="baa80-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="baa80-107">End users, automatically</span></span>|<span data-ttu-id="baa80-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="baa80-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="baa80-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="baa80-109">Feb 1, 2020</span></span>| <span data-ttu-id="baa80-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="baa80-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="baa80-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="baa80-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="baa80-112">注文量よりも多くの商品を受け取り、そのような商品の価格が安く、返品しないか、仕入先が割引サービスを提供する場合、注文処理担当者と倉庫作業者は、新しい発注書の準備と承認を得る長いプロセスを経ることなく、そのような受け入れを処理できることが必要です。</span><span class="sxs-lookup"><span data-stu-id="baa80-112">When you receive more goods than you ordered and it's cheaper not to return such goods or your vendor offers you a discount, order processors and warehouse workers must be able to handle such receipts without going through a lengthy process of preparing and getting approval for a new purchase order.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="baa80-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="baa80-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="baa80-114">**超過入庫コード** ページで設定した超過入庫ポリシーに従って、発注書の注文数量よりも多い数量を受け取ることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="baa80-114">You can now receive a quantity higher than the ordered quantity on purchase orders according to an over-receive policy that you set up on the **Over-Receipt Codes** page.</span></span> <span data-ttu-id="baa80-115">ここで**超過入庫許容率**フィールドに入力し、デフォルトで使用されるポリシーを選択できます。</span><span class="sxs-lookup"><span data-stu-id="baa80-115">Here you can fill in the **Over-Receipt Tolerance %** field and select a policy to be used by default.</span></span> 

<span data-ttu-id="baa80-116">会社で発注書の承認を使用している場合、超過入庫により再承認がトリガーされる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="baa80-116">If your company uses purchase order approval, over-receiving can trigger a reapproval.</span></span> <span data-ttu-id="baa80-117">これは、**超過入庫コード** ページで定義します。</span><span class="sxs-lookup"><span data-stu-id="baa80-117">You define this on the **Over-Receipt Codes** page.</span></span> <span data-ttu-id="baa80-118">**超過入庫の承認**ワークフローの応答は、この目的のためにワークフロー エンジンで使用できます。</span><span class="sxs-lookup"><span data-stu-id="baa80-118">The **Approve Over-Receipt** workflow response is available in the workflow engine for this purpose.</span></span>
 
<span data-ttu-id="baa80-119">商品や仕入先のカードの**超過入庫コード** フィールドで、購入時にデフォルトで使用されるフィールドを選択できます。</span><span class="sxs-lookup"><span data-stu-id="baa80-119">On the cards for items and vendors, you can select in the **Over-Receipt Code** field which policy to use by default on purchases.</span></span>
 
<span data-ttu-id="baa80-120">超過入庫コードを選択したら、リリース済みの発注書と倉庫入庫の**入庫する数量**フィールドに、注文数量よりも多い数量を入力できます。</span><span class="sxs-lookup"><span data-stu-id="baa80-120">When you have selected an over-receipt code, you can enter a higher-than-ordered quantity in the **Quantity to Receive** field on released purchase orders and warehouse receipts.</span></span>
<!--feature detail end -->

<span data-ttu-id="baa80-121">![超過入庫許容率フィールドがハイライトされた超過入庫コード](media/over-receipt-codes.png "[超過入庫許容率] フィールドがハイライトされた超過入庫コード")</span><span class="sxs-lookup"><span data-stu-id="baa80-121">![Over-receipt codes with over-receipt tolerance field highlighted](media/over-receipt-codes.png "Over-receipt codes with over-receipt tolerance field highlighted")</span></span>
<!-- Picture 1 -->

<span data-ttu-id="baa80-122">![発注書明細行の超過入庫](media/over-receipt-purch-order.png "発注書明細行の超過入庫")</span><span class="sxs-lookup"><span data-stu-id="baa80-122">![Over-receipt on purchase order line](media/over-receipt-purch-order.png "Over-receipt on purchase order line")</span></span>
<!-- Picture 2 -->





## <a name="tell-us-what-you-think"></a><span data-ttu-id="baa80-123">フィードバック</span><span class="sxs-lookup"><span data-stu-id="baa80-123">Tell us what you think</span></span>
<span data-ttu-id="baa80-124">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="baa80-124">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="baa80-125">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="baa80-125">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="baa80-126">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="baa80-126">Thank you for your idea</span></span>
<span data-ttu-id="baa80-127">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=7c83f7d7-8763-e911-b047-0003ff68b7ef)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="baa80-127">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=7c83f7d7-8763-e911-b047-0003ff68b7ef).</span></span> <span data-ttu-id="baa80-128">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="baa80-128">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>
