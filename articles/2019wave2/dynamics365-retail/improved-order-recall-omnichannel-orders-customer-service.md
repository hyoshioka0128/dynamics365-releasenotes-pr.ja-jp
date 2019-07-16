---
title: Customer Service におけるオムニチャネル注文の注文取り消しの改善
description: Customer Service におけるオムニチャネル注文の注文取り消しの改善
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: 7863278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: asharchw
dynamics365pdf: true
ms.openlocfilehash: 363a5ea7f360255fb90f349352cec71d46b721a2
ms.sourcegitcommit: 4620697dc1f4fc6903504a55406f3d22af75e361
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/20/2019
ms.locfileid: "1694212"
---
# <a name="improved-order-recall-for-omnichannel-orders-in-customer-service"></a><span data-ttu-id="d5618-103">Customer Service におけるオムニチャネル注文の注文取り消しの改善</span><span class="sxs-lookup"><span data-stu-id="d5618-103">Improved order recall for omnichannel orders in Customer Service</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="d5618-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="d5618-104">Enabled for</span></span>    |  <span data-ttu-id="d5618-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d5618-105">Public preview</span></span> | <span data-ttu-id="d5618-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="d5618-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="d5618-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="d5618-107">End users by admins, makers, or analysts</span></span>|| <span data-ttu-id="d5618-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="d5618-108">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="d5618-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d5618-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d5618-110">Dynamics 365 for Retail では、複数の販売チャネル (POS、コール センター、eコマースなど) を通じて注文のキャプチャと処理を可能にするソリューションが提供されます。</span><span class="sxs-lookup"><span data-stu-id="d5618-110">Dynamics 365 for Retail provides solutions to allow order capture and processing through multiple sales channels (POS, call center, e-commerce, and so on).</span></span> <span data-ttu-id="d5618-111">複数の注文キャプチャ システムを使用している場合、顧客に注文参照データを提供するために使用される方法はそれぞれ異なります。</span><span class="sxs-lookup"><span data-stu-id="d5618-111">When dealing with multiple order capture systems, the methods used to provide the customer with their order reference data are different.</span></span> <span data-ttu-id="d5618-112">販売時点管理 (POS) トランザクションではレシート ID が使用され、コール センターのオーダーでは本社 (HQ) シーケンスからの注文番号が使用され、eコマースの注文では異なる注文番号シーケンスが使用されます。</span><span class="sxs-lookup"><span data-stu-id="d5618-112">Point of sale (POS) transactions use receipt IDs, call center orders use order numbers from a Headquarters (HQ) sequence, and e-commerce orders use a different order number sequence.</span></span> <span data-ttu-id="d5618-113">最終的に、これらの注文は HQ に集中し、HQ の注文番号が再度割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="d5618-113">Eventually, these orders are centralized in HQ and reassigned an HQ order number.</span></span> <span data-ttu-id="d5618-114">顧客サービスの観点からすると、今日の HQ ユーザーは、トランザクション/注文が "ゲスト チェックアウト" または "顧客不明" のトランザクションとして作成された場合、HQ 内でトランザクションや注文を正しく見つけることが課題となっています。</span><span class="sxs-lookup"><span data-stu-id="d5618-114">From a customer service perspective, today, our HQ users are challenged to properly locate transactions and orders in the HQ if they were created as “guest checkout” or “customer unknown” transactions.</span></span> 

<span data-ttu-id="d5618-115">HQ と POS アプリケーションの両方で、Microsoft の顧客サービスと注文検索機能を使用して、これらのさまざまな注文 ID をより見やすくし、相互参照することで、顧客サービス シナリオで問題のある注文を見つけやすくなります。</span><span class="sxs-lookup"><span data-stu-id="d5618-115">By adding more visibility and cross-referencing all of these various order identifiers through our customer service and order search functionality in both the HQ and POS applications, we can provide users with an easier time of locating the order in question in a customer service scenario.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d5618-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d5618-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d5618-117">この機能は、既存の HQ の Customer Service ページを拡張して、顧客番号または注文番号だけでなく、レシート ID または eコマース トランザクション ID による販売注文の相互参照および簡単な検索を可能にします。</span><span class="sxs-lookup"><span data-stu-id="d5618-117">This feature will enhance the existing HQ Customer Service pages to allow for cross-reference and easier lookup of sales orders by not only customer or order number, but also by receipt ID or e-commerce transaction ID.</span></span>

<span data-ttu-id="d5618-118">POS 注文取り消し機能も改善され、レシート ID、注文番号、または eコマース注文番号による検索が可能になります。</span><span class="sxs-lookup"><span data-stu-id="d5618-118">POS order recall features will also be improved to allow for lookup by receipt ID, order number, or e-commerce order number.</span></span>

<span data-ttu-id="d5618-119">eコマースを改善して、お客様がその注文履歴を表示し、必要に応じてレシート番号、本社の販売注文番号、eコマースの販売注文番号を参照できるようにします。</span><span class="sxs-lookup"><span data-stu-id="d5618-119">E-commerce will be improved to ensure that a customer has the ability to view their order history and see reference to receipt numbers, HQ sales order numbers, and/or e-commerce sales order numbers as applicable.</span></span>
<!--feature detail end -->










