---
title: 二重通貨連結のためのオンライン連結の 連結勘定の選択元 コントロール
description: ''
author: relnotes
ms.reviewer: roschlom
ms.date: 11/15/2019
ms.assetid: 45ee7f88-b0a9-e911-a962-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: a071b23cbb11478e1ba26b446e559ff96b14d490
ms.sourcegitcommit: cf8b2ba74d2b553c2a721942221c285ffcf184c5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892771"
---
# <a name="select-consolidation-amount-from-control-on-the-consolidate-online-for-dual-currency-consolidation"></a><span data-ttu-id="b07be-102">二重通貨連結のためのオンライン連結の [連結勘定の選択元] コントロール</span><span class="sxs-lookup"><span data-stu-id="b07be-102">'Select consolidation amount from' control on the consolidate online for dual currency consolidation</span></span>


| <span data-ttu-id="b07be-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="b07be-103">Enabled for</span></span>    |  <span data-ttu-id="b07be-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b07be-104">Public preview</span></span> | <span data-ttu-id="b07be-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="b07be-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b07be-106">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="b07be-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="b07be-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b07be-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b07be-108">2019 年 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="b07be-108">Aug 5, 2019</span></span>| <span data-ttu-id="b07be-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b07be-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b07be-110">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b07be-110">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="b07be-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b07be-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b07be-112">この機能を使用すると、連結会社の取引通貨として使用される通貨 (会計通貨またはレポート通貨) を制御でき、通貨が同じ場合は、ソースの会社から連結会社に金額を自動的にコピーできます。</span><span class="sxs-lookup"><span data-stu-id="b07be-112">This features helps you control the currency (either the accounting or reporting currency) that's used as the transaction currency in the consolidation company and can automatically copy amounts from the source company to the consolidation company if the currencies are the same.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b07be-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b07be-113">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="b07be-114">**オンライン連結フォームへの [連結勘定の選択元] コントロールの追加。**</span><span class="sxs-lookup"><span data-stu-id="b07be-114">**Add the “Select consolidation amount from” control on the consolidate online form.**</span></span>

  <span data-ttu-id="b07be-115">この機能が有効になっている場合、ユーザーはソース会社の会計通貨とレポート通貨のどちらを連結会社の取引通貨として使用するかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="b07be-115">When the feature is enabled, the user can choose whether the accounting currency or the reporting currency from the source company will be used as the transaction currency in the consolidation company.</span></span>

- <span data-ttu-id="b07be-116">**通貨が同じ場合は、ソースの会社から連結会社に金額を直接コピー。**</span><span class="sxs-lookup"><span data-stu-id="b07be-116">**Directly copy amounts from the source company to the consolidation company if the currencies are the same.**</span></span>

  <span data-ttu-id="b07be-117">この機能が有効になっている場合、ソース会社の会計通貨またはレポート通貨の金額は、どちらかの通貨が同じ場合には、連結会社の会計通貨またはレポート通貨の金額に直接コピーされます。</span><span class="sxs-lookup"><span data-stu-id="b07be-117">When the feature is enabled, the accounting or reporting currency amounts from the source company will be copied directly to the accounting or reporting currency amounts in the consolidation company if either of the currencies are the same.</span></span> <span data-ttu-id="b07be-118">どちらの通貨も同じでない場合、連結会社の会計通貨およびレポート通貨の金額は為替レートを使用して計算されます。</span><span class="sxs-lookup"><span data-stu-id="b07be-118">The accounting and reporting currency amounts in the consolidation company are calculated using the exchange rate if neither of the currencies is the same.</span></span>
<!--feature detail end -->










