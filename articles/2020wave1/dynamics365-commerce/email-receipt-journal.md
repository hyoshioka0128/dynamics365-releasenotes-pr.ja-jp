---
title: 仕訳帳から領収書をメールで送信する
description: レジ担当者は領収書の印刷に加えて、仕訳帳から過去のトランザクションの領収書をメールで送信できるようになります。
author: relnotes
ms.reviewer: josaw
ms.date: 01/10/2020
ms.assetid: 9d6e0bf6-0b1d-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: stuharg
dynamics365pdf: true
ms.openlocfilehash: 0045845bcef9308f48559b7cd4065f7b5adf1bf4
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986809"
---
# <a name="email-a-receipt-from-the-journal"></a><span data-ttu-id="45a0d-103">仕訳帳から領収書をメールで送信する</span><span class="sxs-lookup"><span data-stu-id="45a0d-103">Email a receipt from the journal</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="45a0d-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="45a0d-104">Enabled for</span></span>    |  <span data-ttu-id="45a0d-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="45a0d-105">Public preview</span></span> | <span data-ttu-id="45a0d-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="45a0d-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="45a0d-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="45a0d-107">End users, automatically</span></span>|<span data-ttu-id="45a0d-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="45a0d-108">Feb 2020</span></span>| <span data-ttu-id="45a0d-109">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="45a0d-109">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="45a0d-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="45a0d-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="45a0d-111">デジタル領収書には、紙のドキュメントを使用せずに購買を追跡できたり、他のユーザーにメールで領収書を転送できるなど、顧客にとって多くの利点があります。</span><span class="sxs-lookup"><span data-stu-id="45a0d-111">Digital receipts offer a number of advantages and benefits to customers, such as the ability to keep track of purchases without relying on paper documents, and the ability to forward a receipt by email to someone.</span></span> <span data-ttu-id="45a0d-112">Dynamics 365 Commerce で、印刷された領収書に対するのと同じ機能が、メールで送信される領収書に対しても提供されます。</span><span class="sxs-lookup"><span data-stu-id="45a0d-112">Dynamics 365 Commerce now offers the same features for emailed receipts as it provides for printed receipts.</span></span> <span data-ttu-id="45a0d-113">具体的には、顧客は以前の取引の領収書をメールで送信 (または再送信) するよう要求できます。</span><span class="sxs-lookup"><span data-stu-id="45a0d-113">Specifically, customers can request a receipt for a previous transaction to be sent (or resent) to them by email.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="45a0d-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="45a0d-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="45a0d-115">レジ担当者は、仕訳帳にアクセスしてトランザクションを選択し、**領収書の表示**を選択することにより、Modern POS (販売時点管理) またはクラウド POS から顧客に以前のトランザクションの領収書をメールで送信できます。</span><span class="sxs-lookup"><span data-stu-id="45a0d-115">Cashiers can email a receipt for a previous transaction to a customer from Modern or Cloud point of sale (POS) by going into the journal, selecting a transaction, and selecting **Show receipt**.</span></span> <span data-ttu-id="45a0d-116">レジ担当者が新しい**メール** アイコンを選択すると、ダイアログ ボックスが開き、Commerce Headquarters 内の顧客のレコードに領収書メール プロパティの値が表示されます。</span><span class="sxs-lookup"><span data-stu-id="45a0d-116">When the cashier selects the new **Email** icon, a dialog box will open that displays the value of the receipt email property in the customer's record in Commerce headquarters.</span></span> <span data-ttu-id="45a0d-117">レジ担当者は次のことができます。</span><span class="sxs-lookup"><span data-stu-id="45a0d-117">The cashier can:</span></span>

- <span data-ttu-id="45a0d-118">この領収書を送信する宛先メール アドレスを変更する。</span><span class="sxs-lookup"><span data-stu-id="45a0d-118">Change the destination email address for sending this receipt.</span></span>
- <span data-ttu-id="45a0d-119">**顧客の変更を保存します**を選択して顧客の領収書メール アドレスを更新する。</span><span class="sxs-lookup"><span data-stu-id="45a0d-119">Update the customer's receipt email address by selecting **Save changes for the customer**.</span></span> 
<!--feature detail end -->









