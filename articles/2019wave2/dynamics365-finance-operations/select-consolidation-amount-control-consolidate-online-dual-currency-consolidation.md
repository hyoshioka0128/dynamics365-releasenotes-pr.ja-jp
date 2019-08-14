---
title: 二重通貨連結のためのオンライン連結の [連結勘定の選択元] コントロール
description: ''
author: relnotes
ms.reviewer: roschlom
ms.date: 07/31/2019
ms.assetid: 45ee7f88-b0a9-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: f50c3a8f587e661d1f6321e1869c20f9ccc97937
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854880"
---
# <a name="select-consolidation-amount-from-control-on-the-consolidate-online-for-dual-currency-consolidation"></a><span data-ttu-id="ba5c0-102">二重通貨連結のためのオンライン連結の [連結勘定の選択元] コントロール</span><span class="sxs-lookup"><span data-stu-id="ba5c0-102">“Select consolidation amount from” control on the consolidate online for dual currency consolidation</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="ba5c0-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="ba5c0-103">Enabled for</span></span>    |  <span data-ttu-id="ba5c0-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ba5c0-104">Public preview</span></span> | <span data-ttu-id="ba5c0-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="ba5c0-105">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="ba5c0-106">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="ba5c0-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ba5c0-107">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="ba5c0-107">August 2019</span></span>| <span data-ttu-id="ba5c0-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="ba5c0-108">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="ba5c0-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ba5c0-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ba5c0-110">この機能を使用すると、連結会社の取引通貨として使用される通貨 (会計通貨またはレポート通貨) を制御でき、通貨が同じ場合は、ソースの会社から連結会社に金額を自動的にコピーできます。</span><span class="sxs-lookup"><span data-stu-id="ba5c0-110">This features helps you control the currency (either the accounting or reporting currency) that's used as the transaction currency in the consolidation company and can automatically copy amounts from the source company to the consolidation company if the currencies are the same.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ba5c0-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ba5c0-111">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="ba5c0-112">**オンライン連結フォームへの [連結勘定の選択元] コントロールの追加。**</span><span class="sxs-lookup"><span data-stu-id="ba5c0-112">**Add the “Select consolidation amount from” control on the consolidate online form.**</span></span>

  <span data-ttu-id="ba5c0-113">この機能が有効になっている場合、ユーザーはソース会社の会計通貨とレポート通貨のどちらを連結会社の取引通貨として使用するかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="ba5c0-113">When the feature is enabled, the user can choose whether the accounting currency or the reporting currency from the source company will be used as the transaction currency in the consolidation company.</span></span>

- <span data-ttu-id="ba5c0-114">**通貨が同じ場合は、ソースの会社から連結会社に金額を直接コピー。**</span><span class="sxs-lookup"><span data-stu-id="ba5c0-114">**Directly copy amounts from the source company to the consolidation company if the currencies are the same.**</span></span>

  <span data-ttu-id="ba5c0-115">この機能が有効になっている場合、ソース会社の会計通貨またはレポート通貨の金額は、どちらかの通貨が同じ場合には、連結会社の会計通貨またはレポート通貨の金額に直接コピーされます。</span><span class="sxs-lookup"><span data-stu-id="ba5c0-115">When the feature is enabled, the accounting or reporting currency amounts from the source company will be copied directly to the accounting or reporting currency amounts in the consolidation company if either of the currencies are the same.</span></span> <span data-ttu-id="ba5c0-116">どちらの通貨も同じでない場合、連結会社の会計通貨およびレポート通貨の金額は為替レートを使用して計算されます。</span><span class="sxs-lookup"><span data-stu-id="ba5c0-116">The accounting and reporting currency amounts in the consolidation company are calculated using the exchange rate if neither of the currencies is the same.</span></span>
<!--feature detail end -->











