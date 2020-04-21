---
title: 仕訳帳から領収書をメールで送信する
description: レジ担当者は領収書の印刷に加えて、仕訳帳から過去のトランザクションの領収書をメールで送信できるようになります。
author: relnotes
ms.reviewer: josaw
ms.date: 03/06/2020
ms.assetid: 9d6e0bf6-0b1d-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: stuharg
dynamics365pdf: true
ms.openlocfilehash: 046b0c224e903871f841d7d54e3b66fa429960e6
ms.sourcegitcommit: 99f8fe366e70064e41204f9ee5c16fe397396d16
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/10/2020
ms.locfileid: "3115086"
---
# <a name="email-a-receipt-from-the-journal"></a><span data-ttu-id="a56bd-103">仕訳帳から領収書をメールで送信する</span><span class="sxs-lookup"><span data-stu-id="a56bd-103">Email a receipt from the journal</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="a56bd-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a56bd-104">Enabled for</span></span>    |  <span data-ttu-id="a56bd-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a56bd-105">Public preview</span></span> | <span data-ttu-id="a56bd-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="a56bd-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a56bd-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a56bd-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="a56bd-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a56bd-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a56bd-109">2020 年 2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="a56bd-109">Feb 24, 2020</span></span>| <span data-ttu-id="a56bd-110">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="a56bd-110">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a56bd-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a56bd-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a56bd-112">デジタル領収書には、紙のドキュメントを使用せずに購買を追跡できたり、他のユーザーにメールで領収書を転送できるなど、顧客にとって多くの利点があります。</span><span class="sxs-lookup"><span data-stu-id="a56bd-112">Digital receipts offer a number of advantages and benefits to customers, such as the ability to keep track of purchases without relying on paper documents, and the ability to forward a receipt by email to someone.</span></span> <span data-ttu-id="a56bd-113">Dynamics 365 Commerce で、印刷された領収書に対するのと同じ機能が、メールで送信される領収書に対しても提供されます。</span><span class="sxs-lookup"><span data-stu-id="a56bd-113">Dynamics 365 Commerce now offers the same features for emailed receipts as it provides for printed receipts.</span></span> <span data-ttu-id="a56bd-114">具体的には、顧客は以前の取引の領収書をメールで送信 (または再送信) するよう要求できます。</span><span class="sxs-lookup"><span data-stu-id="a56bd-114">Specifically, customers can request a receipt for a previous transaction to be sent (or resent) to them by email.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a56bd-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a56bd-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a56bd-116">レジ担当者は、仕訳帳にアクセスしてトランザクションを選択し、**領収書の表示**を選択することにより、Modern POS (販売時点管理) またはクラウド POS から顧客に以前のトランザクションの領収書をメールで送信できます。</span><span class="sxs-lookup"><span data-stu-id="a56bd-116">Cashiers can email a receipt for a previous transaction to a customer from Modern or Cloud point of sale (POS) by going into the journal, selecting a transaction, and selecting **Show receipt**.</span></span> <span data-ttu-id="a56bd-117">レジ担当者が新しい**メール** アイコンを選択すると、ダイアログ ボックスが開き、Commerce Headquarters 内の顧客のレコードに領収書メール プロパティの値が表示されます。</span><span class="sxs-lookup"><span data-stu-id="a56bd-117">When the cashier selects the new **Email** icon, a dialog box will open that displays the value of the receipt email property in the customer's record in Commerce headquarters.</span></span> <span data-ttu-id="a56bd-118">レジ担当者は次のことができます。</span><span class="sxs-lookup"><span data-stu-id="a56bd-118">The cashier can:</span></span>

- <span data-ttu-id="a56bd-119">テキスト フィールドのメール アドレスに領収書を送信する。</span><span class="sxs-lookup"><span data-stu-id="a56bd-119">Send the receipt to the email address in the text field.</span></span>
- <span data-ttu-id="a56bd-120">領収書を送信する宛先メール アドレスを変更する。</span><span class="sxs-lookup"><span data-stu-id="a56bd-120">Change the destination email address for sending the receipt.</span></span>

> [!NOTE]
> <span data-ttu-id="a56bd-121">既定では、この機能は無効になっています。</span><span class="sxs-lookup"><span data-stu-id="a56bd-121">This capability is disabled by default.</span></span> <span data-ttu-id="a56bd-122">Commerce Headquarters でこれを有効にするには、**機能管理**ワークスペースに移動し、**仕訳帳から領収書をメールで送信する**機能を有効にします。</span><span class="sxs-lookup"><span data-stu-id="a56bd-122">To enable it in Commerce Headquarters, go to the **Feature Management** workspace and enable the **Email receipts from the Journal** feature.</span></span> 
<!--feature detail end -->









