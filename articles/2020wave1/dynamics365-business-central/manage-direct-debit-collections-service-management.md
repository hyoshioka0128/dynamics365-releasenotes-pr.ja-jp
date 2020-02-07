---
title: Service Management で口座引落の回収を管理する
description: Service Management で作成した請求書に対する口座引落回収機能を使用して、顧客未収金を回収します。
author: relnotes
ms.reviewer: sgroespe
ms.date: 12/10/2019
ms.assetid: 71a02882-4aca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 11a6c37099610cd6b39b9be7ee02192e95ca05f1
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986823"
---
# <a name="manage-direct-debit-collections-in-service-management"></a><span data-ttu-id="46f05-103">Service Management で口座引落の回収を管理する</span><span class="sxs-lookup"><span data-stu-id="46f05-103">Manage direct-debit collections in Service Management</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="46f05-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="46f05-104">Enabled for</span></span>    |  <span data-ttu-id="46f05-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="46f05-105">Public preview</span></span> | <span data-ttu-id="46f05-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="46f05-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="46f05-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="46f05-107">End users, automatically</span></span>|<span data-ttu-id="46f05-108">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="46f05-108">Jan 2020</span></span>| <span data-ttu-id="46f05-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="46f05-109">Apr 2020</span></span>|

## <a name="business-value"></a><span data-ttu-id="46f05-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="46f05-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="46f05-111">企業とサービスの関連はますます強くなっています。</span><span class="sxs-lookup"><span data-stu-id="46f05-111">More and more, business is related to services.</span></span> <span data-ttu-id="46f05-112">お客様はそのような業務、特に定期的なサービス業務に対する便利な支払方法を求めています。</span><span class="sxs-lookup"><span data-stu-id="46f05-112">Customers want a convenient way of paying for such work, especially recurring service work.</span></span> <span data-ttu-id="46f05-113">これには Service Management モジュールと統合した口座引落回収機能を使用するのが最適な方法です。</span><span class="sxs-lookup"><span data-stu-id="46f05-113">The best way to do this is by using the Direct Debit Collection functionality in integration with the Service Management modules.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="46f05-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="46f05-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="46f05-115">サービス注文、請求書、契約に関する口座引落回収の情報を表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="46f05-115">You can now view direct-debit collection information on service orders, invoices, and contracts.</span></span> <span data-ttu-id="46f05-116">サービスの請求書を転記する場合は、口座引落の情報を関連する顧客元帳のエントリに保存して、回収プロセスで関連する支払仕訳帳に振り替えます。</span><span class="sxs-lookup"><span data-stu-id="46f05-116">When posting service invoices, direct-debit information is stored in the related customer ledger entries and then transferred to the relevant payment journal during the collection process.</span></span>
<!--feature detail end -->

<span data-ttu-id="46f05-117">![請求書に口座引落回収の情報を表示する](media/serv-order-direct-debit-mandate.png "請求書に口座引落回収の情報を表示する")</span><span class="sxs-lookup"><span data-stu-id="46f05-117">![View direct-debit collection information in an invoice](media/serv-order-direct-debit-mandate.png "View direct-debit collection information in an invoice")</span></span>
<!-- Picture 1 -->





## <a name="tell-us-what-you-think"></a><span data-ttu-id="46f05-118">フィードバック</span><span class="sxs-lookup"><span data-stu-id="46f05-118">Tell us what you think</span></span>
<span data-ttu-id="46f05-119">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="46f05-119">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="46f05-120">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="46f05-120">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="46f05-121">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="46f05-121">Thank you for your idea</span></span>
<span data-ttu-id="46f05-122">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=ca99ab18-3231-e911-9461-0003ff68b049)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="46f05-122">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=ca99ab18-3231-e911-9461-0003ff68b049).</span></span> <span data-ttu-id="46f05-123">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="46f05-123">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>
