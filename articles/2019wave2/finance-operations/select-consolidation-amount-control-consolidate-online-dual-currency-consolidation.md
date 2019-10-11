---
title: 二重通貨連結のためのオンライン連結の [連結勘定の選択元] コントロール
description: ''
author: relnotes
ms.reviewer: roschlom
ms.date: 08/09/2019
ms.assetid: 45ee7f88-b0a9-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: b4b641cdb06f1777587e37a224010f656acc79ba
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141197"
---
# <a name="select-consolidation-amount-from-control-on-the-consolidate-online-for-dual-currency-consolidation"></a><span data-ttu-id="b396c-102">二重通貨連結のためのオンライン連結の [連結勘定の選択元] コントロール</span><span class="sxs-lookup"><span data-stu-id="b396c-102">“Select consolidation amount from” control on the consolidate online for dual currency consolidation</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="b396c-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="b396c-103">Enabled for</span></span>    |  <span data-ttu-id="b396c-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b396c-104">Public preview</span></span> | <span data-ttu-id="b396c-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="b396c-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b396c-106">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="b396c-106">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="b396c-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b396c-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b396c-108">2019 年 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="b396c-108">Aug 5, 2019</span></span>| <span data-ttu-id="b396c-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="b396c-109">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="b396c-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b396c-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b396c-111">この機能を使用すると、連結会社の取引通貨として使用される通貨 (会計通貨またはレポート通貨) を制御でき、通貨が同じ場合は、ソースの会社から連結会社に金額を自動的にコピーできます。</span><span class="sxs-lookup"><span data-stu-id="b396c-111">This features helps you control the currency (either the accounting or reporting currency) that's used as the transaction currency in the consolidation company and can automatically copy amounts from the source company to the consolidation company if the currencies are the same.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b396c-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b396c-112">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="b396c-113">**オンライン連結フォームへの [連結勘定の選択元] コントロールの追加。**</span><span class="sxs-lookup"><span data-stu-id="b396c-113">**Add the “Select consolidation amount from” control on the consolidate online form.**</span></span>

  <span data-ttu-id="b396c-114">この機能が有効になっている場合、ユーザーはソース会社の会計通貨とレポート通貨のどちらを連結会社の取引通貨として使用するかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="b396c-114">When the feature is enabled, the user can choose whether the accounting currency or the reporting currency from the source company will be used as the transaction currency in the consolidation company.</span></span>

- <span data-ttu-id="b396c-115">**通貨が同じ場合は、ソースの会社から連結会社に金額を直接コピー。**</span><span class="sxs-lookup"><span data-stu-id="b396c-115">**Directly copy amounts from the source company to the consolidation company if the currencies are the same.**</span></span>

  <span data-ttu-id="b396c-116">この機能が有効になっている場合、ソース会社の会計通貨またはレポート通貨の金額は、どちらかの通貨が同じ場合には、連結会社の会計通貨またはレポート通貨の金額に直接コピーされます。</span><span class="sxs-lookup"><span data-stu-id="b396c-116">When the feature is enabled, the accounting or reporting currency amounts from the source company will be copied directly to the accounting or reporting currency amounts in the consolidation company if either of the currencies are the same.</span></span> <span data-ttu-id="b396c-117">どちらの通貨も同じでない場合、連結会社の会計通貨およびレポート通貨の金額は為替レートを使用して計算されます。</span><span class="sxs-lookup"><span data-stu-id="b396c-117">The accounting and reporting currency amounts in the consolidation company are calculated using the exchange rate if neither of the currencies is the same.</span></span>
<!--feature detail end -->












## <a name="see-also"></a><span data-ttu-id="b396c-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="b396c-118">See also</span></span>

<span data-ttu-id="b396c-119">[オンライン連結での [連結勘定の選択元]](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-finance-operations/select-consolidation-amount-control-consolidate-online-dual-currency-consolidation) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b396c-119">[Select consolidation amount from in Consolidate Online](https://docs.microsoft.com/dynamics365-release-plan/2019wave2/dynamics365-finance-operations/select-consolidation-amount-control-consolidate-online-dual-currency-consolidation) (docs)</span></span>
