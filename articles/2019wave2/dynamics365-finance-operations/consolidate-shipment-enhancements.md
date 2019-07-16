---
title: 出荷の連結の機能強化
description: この機能では、バッチで、または元伝票ごとに手動で倉庫にリリースするときに、出荷の連結のクエリ ベースの設定が可能です。
author: ''
ms.reviewer: josaw
ms.date: 06/18/2019
ms.assetid: a462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: pjacobse
dynamics365pdf: true
ms.openlocfilehash: 95df02db13782e40a826c74bcb71404e1cf1795d
ms.sourcegitcommit: d6ff62c145bfdd7742034a67a29bf75938823eb0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/24/2019
ms.locfileid: "1702140"
---
# <a name="consolidate-shipment-enhancements"></a><span data-ttu-id="9ebaa-103">出荷の連結の機能強化</span><span class="sxs-lookup"><span data-stu-id="9ebaa-103">Consolidate shipment enhancements</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="9ebaa-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9ebaa-104">Enabled for</span></span>    |  <span data-ttu-id="9ebaa-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9ebaa-105">Public preview</span></span> | <span data-ttu-id="9ebaa-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="9ebaa-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="9ebaa-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="9ebaa-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="9ebaa-108">2019 年 5 月</span><span class="sxs-lookup"><span data-stu-id="9ebaa-108">May 2019</span></span>| <span data-ttu-id="9ebaa-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="9ebaa-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="9ebaa-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9ebaa-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9ebaa-111">このシステムでは、顧客ごと、倉庫ごと、配送ごと、および顧客または品目で定義されているすべてのタイプの特性ごとに、出荷の連結に対応する柔軟な設定が可能です。</span><span class="sxs-lookup"><span data-stu-id="9ebaa-111">The system allows for a flexible setup accommodating consolidated shipments per customer, warehouse, mode of delivery, and all types of characteristics defined for the customer or item.</span></span> <span data-ttu-id="9ebaa-112">これにより、最終的に倉庫の効率化と顧客サービスの向上が可能になります。</span><span class="sxs-lookup"><span data-stu-id="9ebaa-112">This ultimately allows for higher efficiency at the warehouse and better customer service.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9ebaa-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9ebaa-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9ebaa-114">この機能では、倉庫に対して送信元伝票をリリースするときに行われる出荷の連結をより柔軟に構成できます。</span><span class="sxs-lookup"><span data-stu-id="9ebaa-114">This feature will allow for a more flexible configuration of the consolidated shipment that takes place when releasing the outbound source document to the warehouse.</span></span> <span data-ttu-id="9ebaa-115">出荷連結ポリシーと共に出荷連結テンプレートが導入されます。</span><span class="sxs-lookup"><span data-stu-id="9ebaa-115">A consolidate shipment policy is introduced as well as a shipment consolidation template.</span></span> <span data-ttu-id="9ebaa-116">これらの新しいエンティティにより、ユーザーは出荷のリリース時のポリシーの適用方法および出荷連結時のテンプレートの適用方法をクエリごとに定義できます。</span><span class="sxs-lookup"><span data-stu-id="9ebaa-116">These new entities will allow the user to define, per query, how to apply the policy when releasing the shipments and how to apply the template when consolidating the shipments.</span></span> <span data-ttu-id="9ebaa-117">現在の機能は倉庫レベルでの切り替えに限定されているため、連結する必要がある顧客または注文の選択または選択解除が困難です。</span><span class="sxs-lookup"><span data-stu-id="9ebaa-117">The current functionality is limited to a toggle at the warehouse level, making it difficult to select or deselect which customer or orders should be consolidated.</span></span>
<!--feature detail end -->










