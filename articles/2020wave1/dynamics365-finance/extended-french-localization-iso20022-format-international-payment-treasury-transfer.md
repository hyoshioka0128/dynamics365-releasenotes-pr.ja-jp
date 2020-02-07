---
title: '拡張されたローカライズ (フランス): 国際支払および送金用 ISO 20022 フォーマット'
description: Dynamics 365 Finance が、ISO 20022 国際支払用フランス版フォーマットに対応するよう拡張されました。
author: relnotes
ms.reviewer: kfend
ms.date: 12/14/2019
ms.assetid: 50fc678d-f2db-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
dynamics365pdf: true
ms.openlocfilehash: 5e3e693bf74316eb734cbc0b2dd7e2e11e335b9c
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986762"
---
# <a name="extended-french-localization-iso-20022-format-for-international-payment-and-treasury-transfer"></a><span data-ttu-id="2053c-103">拡張されたローカライズ (フランス): 国際支払および送金用 ISO 20022 フォーマット</span><span class="sxs-lookup"><span data-stu-id="2053c-103">Extended French localization: ISO 20022 format for international payment and treasury transfer</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="2053c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="2053c-104">Enabled for</span></span>    |  <span data-ttu-id="2053c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="2053c-105">Public preview</span></span> | <span data-ttu-id="2053c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="2053c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="2053c-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="2053c-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="2053c-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="2053c-108">Feb 2020</span></span>| <span data-ttu-id="2053c-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="2053c-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="2053c-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="2053c-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="2053c-111">国際送金の多いフランスの企業は、このソリューションを使用して、国固有の要件を満たす電子支払ファイルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="2053c-111">With more and more international money transfers, French businesses can use the solution to create an electronic payment file that meets the country-specific requirements.</span></span> <span data-ttu-id="2053c-112">このフォーマットは完全に構成可能であるため、パワー ユーザーは銀行固有の要件をより簡単に取り入れることできます。</span><span class="sxs-lookup"><span data-stu-id="2053c-112">Because the format is fully configurable, it's easier to adapt it to bank-specific requirements by a power user.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="2053c-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="2053c-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="2053c-114">支払が許可される 1 つ以上の国際支払および送金用の支払フォーマットに求められるフランス版ローカライズは、次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="2053c-114">France localization required at least one payment format for international payment and treasury transfer where the payment would be allowed:</span></span> 

- <span data-ttu-id="2053c-115">外貨/EUR 以外の通貨表記</span><span class="sxs-lookup"><span data-stu-id="2053c-115">In foreign/non-EUR currency</span></span>
- <span data-ttu-id="2053c-116">SEPA 地域外では EUR 表記</span><span class="sxs-lookup"><span data-stu-id="2053c-116">In EUR outside of the SEPA area</span></span>
- <span data-ttu-id="2053c-117">選択された費用の配賦は EUR 表記</span><span class="sxs-lookup"><span data-stu-id="2053c-117">In EUR with selected fees allocation</span></span>
- <span data-ttu-id="2053c-118">BIC/IBAN なしの EUR 表記</span><span class="sxs-lookup"><span data-stu-id="2053c-118">In EUR without BIC or IBAN</span></span>
<!--feature detail end -->









