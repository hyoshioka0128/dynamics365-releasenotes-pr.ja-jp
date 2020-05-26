---
title: '拡張されたローカライズ (フランス): 国際支払および送金用 ISO 20022 フォーマット'
description: Dynamics 365 Finance が、ISO 20022 国際支払用フランス版フォーマットに対応するよう拡張されました。
author: relnotes
ms.reviewer: kfend
ms.date: 04/07/2020
ms.assetid: 50fc678d-f2db-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
dynamics365pdf: true
ms.openlocfilehash: 93e0dc9610fc2ca0176f8f573527f789e6c94e3f
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255477"
---
# <a name="extended-french-localization-iso-20022-format-for-international-payment-and-treasury-transfer"></a><span data-ttu-id="8bc64-103">拡張されたローカライズ (フランス): 国際支払および送金用 ISO 20022 フォーマット</span><span class="sxs-lookup"><span data-stu-id="8bc64-103">Extended French localization: ISO 20022 format for international payment and treasury transfer</span></span>


| <span data-ttu-id="8bc64-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8bc64-104">Enabled for</span></span>    |  <span data-ttu-id="8bc64-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8bc64-105">Public preview</span></span> | <span data-ttu-id="8bc64-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8bc64-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8bc64-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="8bc64-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="8bc64-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8bc64-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8bc64-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="8bc64-109">Feb 3, 2020</span></span>| <span data-ttu-id="8bc64-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8bc64-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8bc64-111">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="8bc64-111">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="8bc64-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8bc64-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8bc64-113">国際送金の多いフランスの企業は、このソリューションを使用して、国固有の要件を満たす電子支払ファイルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="8bc64-113">With more and more international money transfers, French businesses can use the solution to create an electronic payment file that meets the country-specific requirements.</span></span> <span data-ttu-id="8bc64-114">このフォーマットは完全に構成可能であるため、パワー ユーザーは銀行固有の要件をより簡単に取り入れることできます。</span><span class="sxs-lookup"><span data-stu-id="8bc64-114">Because the format is fully configurable, it's easier to adapt it to bank-specific requirements by a power user.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8bc64-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8bc64-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8bc64-116">支払が許可される 1 つ以上の国際支払および送金用の支払フォーマットに求められるフランス版ローカライズは、次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="8bc64-116">France localization required at least one payment format for international payment and treasury transfer where the payment would be allowed:</span></span> 

- <span data-ttu-id="8bc64-117">外貨/EUR 以外の通貨表記</span><span class="sxs-lookup"><span data-stu-id="8bc64-117">In foreign/non-EUR currency</span></span>
- <span data-ttu-id="8bc64-118">SEPA 地域外では EUR 表記</span><span class="sxs-lookup"><span data-stu-id="8bc64-118">In EUR outside of the SEPA area</span></span>
- <span data-ttu-id="8bc64-119">選択された費用の配賦は EUR 表記</span><span class="sxs-lookup"><span data-stu-id="8bc64-119">In EUR with selected fees allocation</span></span>
- <span data-ttu-id="8bc64-120">BIC/IBAN なしの EUR 表記</span><span class="sxs-lookup"><span data-stu-id="8bc64-120">In EUR without BIC or IBAN</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="8bc64-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="8bc64-121">See also</span></span>

<!--docs start-->
<span data-ttu-id="8bc64-122">[ISO 20022 口座振替形式の前提条件](https://docs.microsoft.com/dynamics365/finance/localizations/emea-fra-ISO20022-international) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="8bc64-122">[Prerequisites for ISO 20022 credit transfer format](https://docs.microsoft.com/dynamics365/finance/localizations/emea-fra-ISO20022-international) (docs)</span></span>
<!--docs end-->

<!--kb start-->
<span data-ttu-id="8bc64-123">[フランス向けの国固有の更新: ISO 20022 クレジット転送形式 (国際支払および財務振替)](https://support.microsoft.com/en-us/help/4537038) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="8bc64-123">[Country-specific update for France: ISO 20022 Credit transfer format for international payment and treasury transfer](https://support.microsoft.com/en-us/help/4537038) (docs)</span></span>
<!--kb end-->
