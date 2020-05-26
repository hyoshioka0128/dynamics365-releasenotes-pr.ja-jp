---
title: Service Management で口座引落の回収を管理する
description: Service Management で作成した請求書に対する口座引落回収機能を使用して、顧客未収金を回収します。
author: relnotes
ms.reviewer: sgroespe
ms.date: 04/06/2020
ms.assetid: 71a02882-4aca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 762ed2f9b30bb30855895254d7fee9c793e74e25
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255543"
---
# <a name="manage-direct-debit-collections-in-service-management"></a><span data-ttu-id="b68ee-103">Service Management で口座引落の回収を管理する</span><span class="sxs-lookup"><span data-stu-id="b68ee-103">Manage direct-debit collections in Service Management</span></span>


| <span data-ttu-id="b68ee-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b68ee-104">Enabled for</span></span>    |  <span data-ttu-id="b68ee-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b68ee-105">Public preview</span></span> | <span data-ttu-id="b68ee-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b68ee-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b68ee-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="b68ee-107">End users, automatically</span></span>|<span data-ttu-id="b68ee-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b68ee-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b68ee-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b68ee-109">Feb 1, 2020</span></span>| <span data-ttu-id="b68ee-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b68ee-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b68ee-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b68ee-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="b68ee-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b68ee-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b68ee-113">企業とサービスの関連はますます強くなっています。</span><span class="sxs-lookup"><span data-stu-id="b68ee-113">More and more, business is related to services.</span></span> <span data-ttu-id="b68ee-114">お客様はそのような業務、特に定期的なサービス業務に対する便利な支払方法を求めています。</span><span class="sxs-lookup"><span data-stu-id="b68ee-114">Customers want a convenient way of paying for such work, especially recurring service work.</span></span> <span data-ttu-id="b68ee-115">これには Service Management モジュールと統合した口座引落回収機能を使用するのが最適な方法です。</span><span class="sxs-lookup"><span data-stu-id="b68ee-115">The best way to do this is by using the Direct Debit Collection functionality in integration with the Service Management modules.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b68ee-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b68ee-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b68ee-117">サービス注文、請求書、契約に関する口座引落回収の情報を表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="b68ee-117">You can now view direct-debit collection information on service orders, invoices, and contracts.</span></span> <span data-ttu-id="b68ee-118">サービスの請求書を転記する場合は、口座引落の情報を関連する顧客元帳のエントリに保存して、回収プロセスで関連する支払仕訳帳に振り替えます。</span><span class="sxs-lookup"><span data-stu-id="b68ee-118">When posting service invoices, direct-debit information is stored in the related customer ledger entries and then transferred to the relevant payment journal during the collection process.</span></span>
<!--feature detail end -->

<span data-ttu-id="b68ee-119">![請求書に口座引落回収の情報を表示する](media/serv-order-direct-debit-mandate.png "請求書に口座引落回収の情報を表示する")</span><span class="sxs-lookup"><span data-stu-id="b68ee-119">![View direct-debit collection information in an invoice](media/serv-order-direct-debit-mandate.png "View direct-debit collection information in an invoice")</span></span>
<!-- Picture 1 -->





## <a name="tell-us-what-you-think"></a><span data-ttu-id="b68ee-120">フィードバック</span><span class="sxs-lookup"><span data-stu-id="b68ee-120">Tell us what you think</span></span>
<span data-ttu-id="b68ee-121">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="b68ee-121">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="b68ee-122">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="b68ee-122">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="b68ee-123">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="b68ee-123">Thank you for your idea</span></span>
<span data-ttu-id="b68ee-124">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=ca99ab18-3231-e911-9461-0003ff68b049)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="b68ee-124">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=ca99ab18-3231-e911-9461-0003ff68b049).</span></span> <span data-ttu-id="b68ee-125">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="b68ee-125">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="b68ee-126">関連項目</span><span class="sxs-lookup"><span data-stu-id="b68ee-126">See also</span></span>

<!--docs start-->
<span data-ttu-id="b68ee-127">[SEPA 口座引落で支払を回収する](https://docs.microsoft.com/dynamics365/business-central/finance-collect-payments-with-sepa-direct-debit) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b68ee-127">[Collect Payments with SEPA Direct Debit](https://docs.microsoft.com/dynamics365/business-central/finance-collect-payments-with-sepa-direct-debit) (docs)</span></span>
<!--docs end-->
