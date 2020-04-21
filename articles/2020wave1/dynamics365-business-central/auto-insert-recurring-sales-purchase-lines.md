---
title: 定期的な販売と購買注文明細行の自動挿入
description: 販売および購買ドキュメントに定期的な販売および購買注文明細行を自動的に挿入できるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 02/04/2020
ms.assetid: ebe92848-4dda-e911-a812-000d3a4f1244
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 1ddeb7ec0569b9121114d9b00cff17aed32052dd
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232992"
---
# <a name="auto-insert-recurring-sales-and-purchase-lines"></a><span data-ttu-id="839e6-103">定期的な販売と購買注文明細行の自動挿入</span><span class="sxs-lookup"><span data-stu-id="839e6-103">Auto-insert recurring sales and purchase lines</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="839e6-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="839e6-104">Enabled for</span></span>    |  <span data-ttu-id="839e6-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="839e6-105">Public preview</span></span> | <span data-ttu-id="839e6-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="839e6-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="839e6-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="839e6-107">End users, automatically</span></span>|<span data-ttu-id="839e6-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="839e6-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="839e6-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="839e6-109">Feb 1, 2020</span></span>| <span data-ttu-id="839e6-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="839e6-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="839e6-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="839e6-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="839e6-112">定期的な販売注文と発注書は、ビジネスにおける新たな標準です。</span><span class="sxs-lookup"><span data-stu-id="839e6-112">Recurring sales and purchase orders are the new normal in business.</span></span> <span data-ttu-id="839e6-113">Business Central では、定義済みの定期的な販売および購買注文明細行の自動挿入を使用して、このような定期的な販売と購買を処理できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="839e6-113">Business Central now allows you to handle such recurring sales and purchases by using automatic insert of predefined recurring sales and purchase lines.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="839e6-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="839e6-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="839e6-115">既存の定期的な販売/購買注文明細行機能が拡張され、顧客または仕入先に対して設定された定期的な販売または購買注文明細行がドキュメントに自動的に挿入されます。</span><span class="sxs-lookup"><span data-stu-id="839e6-115">The existing Recurring Sales/Purchase Lines feature is extended to automatically insert on documents the recurring sales or purchase lines that are set up for the customer or vendor.</span></span> 

<span data-ttu-id="839e6-116">顧客または仕入先に対して複数の定期的な販売または購買注文明細行が存在する場合、通知を受け取ってそこから挿入するものを選択できます。</span><span class="sxs-lookup"><span data-stu-id="839e6-116">If multiple recurring sales or purchase lines exist for the customer or vendor, you will get a notification from where you can pick which one to insert.</span></span> <span data-ttu-id="839e6-117">定期的な販売または購買注文明細行が 1 つしかない場合は、自動的に挿入されます。</span><span class="sxs-lookup"><span data-stu-id="839e6-117">If only one recurring sales or purchase line exists, it will be inserted automatically.</span></span>

<span data-ttu-id="839e6-118">これは、たとえば**発注書**ページで**新規**アクションを選択することで、新しいドキュメントがドキュメント リストから作成された場合にのみ機能することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="839e6-118">Note that this works only if the new document was created from a document list—for example, by choosing the **New** action on the **Purchase Orders** page.</span></span> <span data-ttu-id="839e6-119">たとえば、ドキュメントが仕入先カードから作成された場合には機能しません。</span><span class="sxs-lookup"><span data-stu-id="839e6-119">It does not work if the document was created from a vendor card, for example.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="839e6-120">フィードバック</span><span class="sxs-lookup"><span data-stu-id="839e6-120">Tell us what you think</span></span>
<span data-ttu-id="839e6-121">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="839e6-121">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="839e6-122">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="839e6-122">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="839e6-123">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="839e6-123">Thank you for your idea</span></span>
<span data-ttu-id="839e6-124">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=0ca18002-ca4f-e911-867a-0003ff68d4ef)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="839e6-124">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=0ca18002-ca4f-e911-867a-0003ff68d4ef).</span></span> <span data-ttu-id="839e6-125">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="839e6-125">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="839e6-126">関連項目</span><span class="sxs-lookup"><span data-stu-id="839e6-126">See also</span></span>


<!--docs start-->
<span data-ttu-id="839e6-127">[定期的な販売および購買注文明細行の作成](https://docs.microsoft.com/dynamics365/business-central/sales-how-work-standard-lines) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="839e6-127">[Create Recurring Sales and Purchase Lines](https://docs.microsoft.com/dynamics365/business-central/sales-how-work-standard-lines) (docs)</span></span>
<!--docs end-->

