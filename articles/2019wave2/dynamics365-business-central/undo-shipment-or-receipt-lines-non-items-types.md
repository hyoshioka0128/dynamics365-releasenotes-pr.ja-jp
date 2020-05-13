---
title: 非品目タイプの出荷明細行または受領明細行を元に戻す
description: 販売出荷および購買受領書で、非品目タイプの出荷明細行または受領明細行を元に戻します。
author: relnotes
ms.reviewer: sgroespe
ms.date: 01/24/2020
ms.assetid: 425d9148-4aca-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 499080b0314102f42d04a582d87ea51b3a1f63f5
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3058334"
---
# <a name="undo-shipment-or-receipt-lines-for-non-item-types"></a><span data-ttu-id="3e74c-103">非品目タイプの出荷明細行または受領明細行を元に戻す</span><span class="sxs-lookup"><span data-stu-id="3e74c-103">Undo shipment or receipt lines for non-item types</span></span>


| <span data-ttu-id="3e74c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3e74c-104">Enabled for</span></span>    |  <span data-ttu-id="3e74c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3e74c-105">Public preview</span></span> | <span data-ttu-id="3e74c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="3e74c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3e74c-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="3e74c-107">End users, automatically</span></span>|<span data-ttu-id="3e74c-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3e74c-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3e74c-109">2019 年 10 月 22 日</span><span class="sxs-lookup"><span data-stu-id="3e74c-109">Oct 22, 2019</span></span>| <span data-ttu-id="3e74c-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3e74c-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3e74c-111">2019 年 11 月 1 日</span><span class="sxs-lookup"><span data-stu-id="3e74c-111">Nov 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="3e74c-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3e74c-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3e74c-113">販売出荷および購買受領書に、サービス作業、配送業者手数料、その他の料金などの品目以外の明細行が含まれることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="3e74c-113">Sales shipments and purchase receipts frequently contain non-item lines, such as service work, shipping agent fees, or other charges.</span></span> <span data-ttu-id="3e74c-114">そのような行を迅速かつ一貫した方法で取り消すことで、企業は変化する顧客ニーズに迅速に対応できます。</span><span class="sxs-lookup"><span data-stu-id="3e74c-114">Undoing such lines in a quick and consistent way allows businesses to be agile in responding to changing customer needs.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3e74c-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3e74c-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3e74c-116">**出荷を元に戻す**および**受領を元に戻す**アクションを使用して、販売出荷と購買受領書の非品目明細行を修正または取り消しできます。</span><span class="sxs-lookup"><span data-stu-id="3e74c-116">With the **Undo Shipment** and **Undo Receipt** actions, you can now correct or undo non-item lines on sales shipments and purchase receipts.</span></span>
<!--feature detail end -->

<span data-ttu-id="3e74c-117">![リソースなどの非品目の出荷または受領転記を元に戻す](media/undo-shipment.png "リソースなどの非品目の出荷または受領転記を元に戻す")</span><span class="sxs-lookup"><span data-stu-id="3e74c-117">![Undo shipment or receipt posting of non-items, such as resources](media/undo-shipment.png "Undo shipment or receipt posting of non-items, such as resources")</span></span>
<!-- Picture 1 -->





## <a name="tell-us-what-you-think"></a><span data-ttu-id="3e74c-118">フィードバック</span><span class="sxs-lookup"><span data-stu-id="3e74c-118">Tell us what you think</span></span>
<span data-ttu-id="3e74c-119">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="3e74c-119">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="3e74c-120">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="3e74c-120">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="3e74c-121">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="3e74c-121">Thank you for your idea</span></span>
<span data-ttu-id="3e74c-122">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=e1029365-931d-e911-9461-0003ff68bc11)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="3e74c-122">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=e1029365-931d-e911-9461-0003ff68bc11).</span></span> <span data-ttu-id="3e74c-123">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="3e74c-123">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="3e74c-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="3e74c-124">See also</span></span>

<span data-ttu-id="3e74c-125">[仕訳帳転記の取消と受領/出荷を元に戻す](https://docs.microsoft.com/dynamics365/business-central/finance-how-reverse-journal-posting) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="3e74c-125">[Reverse Journal Postings and Undo Receipts/Shipments](https://docs.microsoft.com/dynamics365/business-central/finance-how-reverse-journal-posting) (docs)</span></span>
