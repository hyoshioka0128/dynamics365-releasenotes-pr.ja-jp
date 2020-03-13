---
title: '拡張されたローカライズ (フランス): 国際支払および送金用 ISO 20022 フォーマット'
description: Dynamics 365 Finance が、ISO 20022 国際支払用フランス版フォーマットに対応するよう拡張されました。
author: relnotes
ms.reviewer: kfend
ms.date: 02/14/2020
ms.assetid: 50fc678d-f2db-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
dynamics365pdf: true
ms.openlocfilehash: 07f5e7fc89976688ac78e815994c0782e6c9b137
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3080327"
---
# <a name="extended-french-localization-iso-20022-format-for-international-payment-and-treasury-transfer"></a><span data-ttu-id="63514-103">拡張されたローカライズ (フランス): 国際支払および送金用 ISO 20022 フォーマット</span><span class="sxs-lookup"><span data-stu-id="63514-103">Extended French localization: ISO 20022 format for international payment and treasury transfer</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="63514-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="63514-104">Enabled for</span></span>    |  <span data-ttu-id="63514-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="63514-105">Public preview</span></span> | <span data-ttu-id="63514-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="63514-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="63514-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="63514-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="63514-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="63514-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="63514-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="63514-109">Feb 3, 2020</span></span>| <span data-ttu-id="63514-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="63514-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="63514-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="63514-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="63514-112">国際送金の多いフランスの企業は、このソリューションを使用して、国固有の要件を満たす電子支払ファイルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="63514-112">With more and more international money transfers, French businesses can use the solution to create an electronic payment file that meets the country-specific requirements.</span></span> <span data-ttu-id="63514-113">このフォーマットは完全に構成可能であるため、パワー ユーザーは銀行固有の要件をより簡単に取り入れることできます。</span><span class="sxs-lookup"><span data-stu-id="63514-113">Because the format is fully configurable, it's easier to adapt it to bank-specific requirements by a power user.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="63514-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="63514-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="63514-115">支払が許可される 1 つ以上の国際支払および送金用の支払フォーマットに求められるフランス版ローカライズは、次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="63514-115">France localization required at least one payment format for international payment and treasury transfer where the payment would be allowed:</span></span> 

- <span data-ttu-id="63514-116">外貨/EUR 以外の通貨表記</span><span class="sxs-lookup"><span data-stu-id="63514-116">In foreign/non-EUR currency</span></span>
- <span data-ttu-id="63514-117">SEPA 地域外では EUR 表記</span><span class="sxs-lookup"><span data-stu-id="63514-117">In EUR outside of the SEPA area</span></span>
- <span data-ttu-id="63514-118">選択された費用の配賦は EUR 表記</span><span class="sxs-lookup"><span data-stu-id="63514-118">In EUR with selected fees allocation</span></span>
- <span data-ttu-id="63514-119">BIC/IBAN なしの EUR 表記</span><span class="sxs-lookup"><span data-stu-id="63514-119">In EUR without BIC or IBAN</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="63514-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="63514-120">See also</span></span>

<span data-ttu-id="63514-121">[フランス向けの国固有の更新: ISO 20022 クレジット転送形式 (国際支払および財務振替)](https://support.microsoft.com/help/4537038) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="63514-121">[Country-specific update for France: ISO 20022 Credit transfer format for international payment and treasury transfer](https://support.microsoft.com/help/4537038) (docs)</span></span>
