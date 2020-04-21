---
title: 注文量よりも多くの商品を受け取る
description: 注文数量に対する入庫数量について指定された許容範囲に基づいて、発注書と倉庫の超過入庫を許可します。
author: relnotes
ms.reviewer: sgroespe
ms.date: 03/18/2020
ms.assetid: 7c144f9f-4aca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: ce42adeed6b67ca29c06b0cd229c3d15c5e52e03
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232706"
---
# <a name="receive-more-items-than-ordered"></a><span data-ttu-id="cfc09-103">注文量よりも多くの商品を受け取る</span><span class="sxs-lookup"><span data-stu-id="cfc09-103">Receive more items than ordered</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="cfc09-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cfc09-104">Enabled for</span></span>    |  <span data-ttu-id="cfc09-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cfc09-105">Public preview</span></span> | <span data-ttu-id="cfc09-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="cfc09-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="cfc09-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="cfc09-107">End users, automatically</span></span>|<span data-ttu-id="cfc09-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="cfc09-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="cfc09-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="cfc09-109">Feb 1, 2020</span></span>| <span data-ttu-id="cfc09-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="cfc09-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="cfc09-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="cfc09-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="cfc09-112">注文量よりも多くの商品を受け取り、そのような商品の価格が安く、返品しないか、仕入先が割引サービスを提供する場合、注文処理担当者と倉庫作業者は、新しい発注書の準備と承認を得る長いプロセスを経ることなく、そのような受け入れを処理できることが必要です。</span><span class="sxs-lookup"><span data-stu-id="cfc09-112">When you receive more goods than you ordered and it's cheaper not to return such goods or your vendor offers you a discount, order processors and warehouse workers must be able to handle such receipts without going through a lengthy process of preparing and getting approval for a new purchase order.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="cfc09-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cfc09-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cfc09-114">**超過入庫コード** ページで設定した超過入庫ポリシーに従って、発注書の注文数量よりも多い数量を受け取ることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="cfc09-114">You can now receive a quantity higher than the ordered quantity on purchase orders according to an over-receive policy that you set up on the **Over-Receipt Codes** page.</span></span> <span data-ttu-id="cfc09-115">ここで**超過入庫許容率**フィールドに入力し、デフォルトで使用されるポリシーを選択できます。</span><span class="sxs-lookup"><span data-stu-id="cfc09-115">Here you can fill in the **Over-Receipt Tolerance %** field and select a policy to be used by default.</span></span> 

<span data-ttu-id="cfc09-116">会社で発注書の承認を使用している場合、超過入庫により再承認がトリガーされる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="cfc09-116">If your company uses purchase order approval, over-receiving can trigger a reapproval.</span></span> <span data-ttu-id="cfc09-117">これは、**超過入庫コード** ページで定義します。</span><span class="sxs-lookup"><span data-stu-id="cfc09-117">You define this on the **Over-Receipt Codes** page.</span></span> <span data-ttu-id="cfc09-118">**超過入庫の承認**ワークフローの応答は、この目的のためにワークフロー エンジンで使用できます。</span><span class="sxs-lookup"><span data-stu-id="cfc09-118">The **Approve Over-Receipt** workflow response is available in the workflow engine for this purpose.</span></span>
 
<span data-ttu-id="cfc09-119">商品や仕入先のカードの**超過入庫コード** フィールドで、購入時にデフォルトで使用されるフィールドを選択できます。</span><span class="sxs-lookup"><span data-stu-id="cfc09-119">On the cards for items and vendors, you can select in the **Over-Receipt Code** field which policy to use by default on purchases.</span></span>
 
<span data-ttu-id="cfc09-120">超過入庫コードを選択したら、リリース済みの発注書と倉庫入庫の**入庫する数量**フィールドに、注文数量よりも多い数量を入力できます。</span><span class="sxs-lookup"><span data-stu-id="cfc09-120">When you have selected an over-receipt code, you can enter a higher-than-ordered quantity in the **Quantity to Receive** field on released purchase orders and warehouse receipts.</span></span>
<!--feature detail end -->

<span data-ttu-id="cfc09-121">![超過入庫許容率フィールドがハイライトされた超過入庫コードの表示](media/over-receipt-codes.png "超過入庫許容率フィールドがハイライトされた超過入庫コードの表示")</span><span class="sxs-lookup"><span data-stu-id="cfc09-121">![Shows over-receipt codes with over-receipt tolerance field highlighted](media/over-receipt-codes.png "Shows over-receipt codes with over-receipt tolerance field highlighted")</span></span>
<!-- Picture 1 -->
<span data-ttu-id="cfc09-122">![発注書明細行での超過入庫の表示](media/over-receipt-purch-order.png "発注書明細行での超過入庫の表示")</span><span class="sxs-lookup"><span data-stu-id="cfc09-122">![Shows over-receipt on purchase order line](media/over-receipt-purch-order.png "Shows over-receipt on purchase order line")</span></span>
<!-- Picture 2 -->





## <a name="tell-us-what-you-think"></a><span data-ttu-id="cfc09-123">フィードバック</span><span class="sxs-lookup"><span data-stu-id="cfc09-123">Tell us what you think</span></span>
<span data-ttu-id="cfc09-124">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="cfc09-124">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="cfc09-125">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="cfc09-125">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="cfc09-126">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="cfc09-126">Thank you for your idea</span></span>
<span data-ttu-id="cfc09-127">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=7c83f7d7-8763-e911-b047-0003ff68b7ef)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="cfc09-127">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=7c83f7d7-8763-e911-b047-0003ff68b7ef).</span></span> <span data-ttu-id="cfc09-128">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="cfc09-128">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="cfc09-129">関連項目</span><span class="sxs-lookup"><span data-stu-id="cfc09-129">See also</span></span>


<!--docs start-->
<span data-ttu-id="cfc09-130">[商品の受け取り](https://docs.microsoft.com/dynamics365/business-central/warehouse-how-receive-items) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="cfc09-130">[Receive Items](https://docs.microsoft.com/dynamics365/business-central/warehouse-how-receive-items) (docs)</span></span>
<!--docs end-->

