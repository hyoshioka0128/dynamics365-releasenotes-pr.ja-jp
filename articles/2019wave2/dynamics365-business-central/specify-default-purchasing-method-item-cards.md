---
title: 品目カードで既定の購買方法を指定する
description: 品目カードで、**直送**、**特別注文**などの既定の購買コードを購買方法として追加できるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 10/15/2019
ms.assetid: fe738702-57e3-e911-a812-000d3a4f13c0
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 450b9b66fd0633c3f202a59f571c1354ef6ca150
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2667422"
---
# <a name="specify-default-purchasing-method-on-item-cards"></a><span data-ttu-id="16c6a-103">品目カードで既定の購買方法を指定する</span><span class="sxs-lookup"><span data-stu-id="16c6a-103">Specify default purchasing method on item cards</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="16c6a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="16c6a-104">Enabled for</span></span>    |  <span data-ttu-id="16c6a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="16c6a-105">Public preview</span></span> | <span data-ttu-id="16c6a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="16c6a-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="16c6a-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="16c6a-107">End users, automatically</span></span>|<span data-ttu-id="16c6a-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="16c6a-108">Oct 2019</span></span>| <span data-ttu-id="16c6a-109">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="16c6a-109">Nov 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="16c6a-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="16c6a-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="16c6a-111">直送機能または特別注文機能を使用していずれかの仕入れ先から顧客に品目を直接出荷する場合に、営業担当者はどの品目がこの方法で発送可能かを覚えておく必要がなくなり、それらの品目を Business Central で自動的に処理できます。</span><span class="sxs-lookup"><span data-stu-id="16c6a-111">When shipping items from one of your vendors directly to your customer by using the Drop Shipment or Special Order features, your salespeople no longer need to remember which items can be sent this way but can have Business Central handle that for them.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="16c6a-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="16c6a-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="16c6a-113">品目カードの**購買コード** フィールドに入力することで、その品目が仕入先から顧客に直接出荷可能であることを定義できます。</span><span class="sxs-lookup"><span data-stu-id="16c6a-113">You can now define for an item that it can be sent from your vendor to your customer directly by filling in the **Purchasing Code** field on the item card.</span></span> <span data-ttu-id="16c6a-114">その後は、品目の販売ドキュメント明細行の**購買コード** フィールドに選択した方法 (たとえば**直送**) が入力されます。</span><span class="sxs-lookup"><span data-stu-id="16c6a-114">The **Purchasing Code** field on sales document lines for the item is then filled in with the selected method, for example **DROP SHIPMENT**.</span></span> 


<span data-ttu-id="16c6a-115">![購買コード フィールドに直送を入力](media/default-purchasing-code-item.png "[購買コード] フィールドに [直送] を入力")</span><span class="sxs-lookup"><span data-stu-id="16c6a-115">![Entering Drop Shipment in the Purchasing Code field](media/default-purchasing-code-item.png "Entering Drop Shipment in the Purchasing Code field")</span></span>

<!--feature detail end -->



## <a name="tell-us-what-you-think"></a><span data-ttu-id="16c6a-116">フィードバック</span><span class="sxs-lookup"><span data-stu-id="16c6a-116">Tell us what you think</span></span>
<span data-ttu-id="16c6a-117">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="16c6a-117">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="16c6a-118">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="16c6a-118">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="16c6a-119">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="16c6a-119">Thank you for your idea</span></span>
<span data-ttu-id="16c6a-120">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=c468c8b1-ba12-e811-80c0-00155d7cb38d)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="16c6a-120">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=c468c8b1-ba12-e811-80c0-00155d7cb38d).</span></span> <span data-ttu-id="16c6a-121">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="16c6a-121">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>
