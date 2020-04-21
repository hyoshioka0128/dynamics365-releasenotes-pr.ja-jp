---
title: 価格計算の拡張
description: インターフェイス オブジェクトを使用して、価格計算を簡単に拡張できるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 04/02/2020
ms.assetid: 741c5608-5272-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 97c8a961292624445342abb8d2a099782b0411b5
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232860"
---
# <a name="extend-price-calculation"></a><span data-ttu-id="53809-103">価格計算の拡張</span><span class="sxs-lookup"><span data-stu-id="53809-103">Extend price calculation</span></span>


| <span data-ttu-id="53809-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="53809-104">Enabled for</span></span>    |  <span data-ttu-id="53809-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="53809-105">Public preview</span></span> | <span data-ttu-id="53809-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="53809-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="53809-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="53809-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="53809-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="53809-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="53809-109">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="53809-109">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="53809-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="53809-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="53809-111">販売と購入の特別価格と明細割引を記録すると、Business Central は販売ドキュメントと購買ドキュメント、およびジョブと品目の仕訳帳明細行の価格を自動的に計算できます。</span><span class="sxs-lookup"><span data-stu-id="53809-111">If you record special prices and line discounts for sales and purchases, Business Central can automatically calculate prices on sales and purchase documents, and on job and item journal lines.</span></span> <span data-ttu-id="53809-112">価格は、指定された日付の最大許容明細割引での最低許容価格です。</span><span class="sxs-lookup"><span data-stu-id="53809-112">The price is the lowest permissible price with the highest permissible line discount on a given date.</span></span> <span data-ttu-id="53809-113">Business Central での価格計算は多くのビジネスに適合しますが、業界またはビジネス固有の価格設定ニーズを持つ企業も多くあります。</span><span class="sxs-lookup"><span data-stu-id="53809-113">Price calculation in Business Central can fit many businesses, but there are also many that have industry- or business-specific pricing needs.</span></span> <span data-ttu-id="53809-114">この改善により、ビジネス ニーズに合わせて価格計算を簡単に拡張できるようにすることで、このようなニーズに対応します。</span><span class="sxs-lookup"><span data-stu-id="53809-114">This improvement addresses such needs by making price calculation easily extendable to fit business needs.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="53809-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="53809-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="53809-116">このリリース ウェーブでは、2019 年リリース ウェーブ 2 以前のバージョンで利用できた計算の代替として利用できる価格計算の 2 番目の実装が導入されています。</span><span class="sxs-lookup"><span data-stu-id="53809-116">This release wave introduces a second implementation of price calculation that will be available as an alternative to the calculation that was available in 2019 release wave 2 and earlier versions.</span></span> <span data-ttu-id="53809-117">この新しい実装には、たとえば新しい計算を使用して拡張するのがはるかに簡単であるという利点があります。</span><span class="sxs-lookup"><span data-stu-id="53809-117">This new implementation has the advantage that it is much easier to extend, for example, with new calculations.</span></span>

<span data-ttu-id="53809-118">2019 年リリース ウェーブ 2 で利用可能だった価格計算は変更されていません。</span><span class="sxs-lookup"><span data-stu-id="53809-118">The price calculation that was available in 2019 release wave 2 is unchanged.</span></span> <span data-ttu-id="53809-119">2020 年リリース ウェーブ 1 の新しい計算は、拡張可能な追加の実装です。</span><span class="sxs-lookup"><span data-stu-id="53809-119">The new calculation in 2020 release wave 1 is an additional implementation that you can extend.</span></span>

<span data-ttu-id="53809-120">現在、新しい拡張可能な価格計算機能はコードでのみ存在し、ユーザー インターフェイスは含まれていません。</span><span class="sxs-lookup"><span data-stu-id="53809-120">The new extendable price calculation capabilities currently exist in code only and do not include a user interface.</span></span> <span data-ttu-id="53809-121">今後のリリースで提供する予定です。</span><span class="sxs-lookup"><span data-stu-id="53809-121">We will provide that in an upcoming release.</span></span> <span data-ttu-id="53809-122">現時点では、新機能を使用するには独自のページを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="53809-122">For now, you must create your own page to use the new capability.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="53809-123">フィードバック</span><span class="sxs-lookup"><span data-stu-id="53809-123">Tell us what you think</span></span>
<span data-ttu-id="53809-124">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="53809-124">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="53809-125">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="53809-125">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="53809-126">関連項目</span><span class="sxs-lookup"><span data-stu-id="53809-126">See also</span></span>


<!--docs start-->
<span data-ttu-id="53809-127">[価格計算の拡張](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-extending-best-price-calculations) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="53809-127">[Extending Price Calculations](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-extending-best-price-calculations) (docs)</span></span>
<!--docs end-->

