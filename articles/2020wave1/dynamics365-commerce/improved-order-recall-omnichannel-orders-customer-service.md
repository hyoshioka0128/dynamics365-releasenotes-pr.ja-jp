---
title: Customer Service におけるオムニチャネル注文の注文取り消しの改善
description: Customer Service におけるオムニチャネル注文の注文取り消しの改善
author: relnotes
ms.reviewer: josaw
ms.date: 01/10/2020
ms.assetid: 7863278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: asharchw
dynamics365pdf: true
ms.openlocfilehash: 85fb4da0b708ea42f2419a70e047fbbb4c1b6703
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986804"
---
# <a name="improved-order-recall-for-omnichannel-orders-in-customer-service"></a><span data-ttu-id="8a2d4-103">Customer Service におけるオムニチャネル注文の注文取り消しの改善</span><span class="sxs-lookup"><span data-stu-id="8a2d4-103">Improved order recall for omnichannel orders in Customer Service</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="8a2d4-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8a2d4-104">Enabled for</span></span>    |  <span data-ttu-id="8a2d4-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8a2d4-105">Public preview</span></span> | <span data-ttu-id="8a2d4-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8a2d4-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8a2d4-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="8a2d4-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="8a2d4-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="8a2d4-108">Feb 2020</span></span>| <span data-ttu-id="8a2d4-109">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="8a2d4-109">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="8a2d4-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8a2d4-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8a2d4-111">Dynamics 365 Commerce では、複数のチャネル (販売時点管理 (POS)、コール センター、eコマースなど) を通じて注文のキャプチャと処理を可能にするソリューションが提供されます。</span><span class="sxs-lookup"><span data-stu-id="8a2d4-111">Dynamics 365 Commerce provides solutions to allow order capture and processing through multiple channels (such as point of sale (POS), call center, and e-commerce).</span></span> <span data-ttu-id="8a2d4-112">複数の注文キャプチャ システムを使用している場合、顧客に注文参照データを提供するために使用される方法はそれぞれ異なります。</span><span class="sxs-lookup"><span data-stu-id="8a2d4-112">When dealing with multiple order capture systems, the methods used to provide the customer with their order reference data are different.</span></span> <span data-ttu-id="8a2d4-113">POS トランザクションではレシート ID が使用され、コール センターの注文では本社シーケンスからの注文番号が使用され、eコマースの注文では異なる注文番号シーケンスが使用されます。</span><span class="sxs-lookup"><span data-stu-id="8a2d4-113">POS transactions use receipt IDs, call center orders use order numbers from a headquarters sequence, and e-commerce orders use a different order number sequence.</span></span> <span data-ttu-id="8a2d4-114">最終的に、これらの注文は本社に集中し、本社の注文番号が再度割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="8a2d4-114">Eventually, these orders are centralized in the headquarters and reassigned a headquarters order number.</span></span> <span data-ttu-id="8a2d4-115">顧客サービスの観点からすると、今日の本社 (HQ) ユーザーは、トランザクション/注文が "ゲスト チェックアウト" または "顧客不明" のトランザクションとして作成された場合、本社内でトランザクションや注文を正しく見つけることが課題となっています。</span><span class="sxs-lookup"><span data-stu-id="8a2d4-115">From a customer service perspective, our headquarters (HQ) users are challenged today to properly locate transactions and orders in the headquarters if they were created as “guest checkout” or “customer unknown” transactions.</span></span> 

<span data-ttu-id="8a2d4-116">本社と POS アプリケーションの両方で、Microsoft の顧客サービスと注文検索機能を使用して、これらのさまざまな注文 ID をより見やすくし、相互参照することで、顧客サービス シナリオで問題のある注文を見つけやすくなります。</span><span class="sxs-lookup"><span data-stu-id="8a2d4-116">By adding more visibility and cross-referencing all of these various order identifiers through our customer service and order search functionality in both the headquarters and POS applications, we can provide users with an easier time of locating the order in question in a customer service scenario.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8a2d4-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8a2d4-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8a2d4-118">この機能は、HQ の 既存の顧客サービス ページを拡張して、顧客番号、注文番号、レシート ID、または eコマース トランザクション ID による販売注文の相互参照および簡単な検索を可能にします。</span><span class="sxs-lookup"><span data-stu-id="8a2d4-118">This feature will enhance the existing customer service pages in HQ to allow for cross-referencing and easier lookup of sales orders by customer, order number, receipt ID or e-commerce transaction ID.</span></span>

<span data-ttu-id="8a2d4-119">POS 注文取り消し機能も改善され、レシート ID、注文番号、または eコマース注文番号による検索が可能になります。</span><span class="sxs-lookup"><span data-stu-id="8a2d4-119">POS order recall features will also be improved to allow for lookup by receipt ID, order number, or e-commerce order number.</span></span>

<span data-ttu-id="8a2d4-120">eコマースが改善され、お客様は注文履歴を表示し、必要に応じてレシート番号、本社の販売注文番号、eコマースの販売注文番号を参照できるようになります。</span><span class="sxs-lookup"><span data-stu-id="8a2d4-120">E-commerce will be improved to ensure that a customer has the ability to view their order history and see receipt numbers, HQ sales order numbers, or e-commerce sales order numbers as applicable.</span></span>
<!--feature detail end -->









