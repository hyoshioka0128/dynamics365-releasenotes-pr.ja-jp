---
title: 通貨換算を使用する場合の財務レポートの利益剰余金計算の機能強化
description: ''
author: relnotes
ms.reviewer: roschlom
ms.date: 09/13/2019
ms.assetid: 7b036487-2abe-e911-a963-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: dcca5a85fe136c6ea054b86063132ca56e6e0949
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2142858"
---
# <a name="retained-earnings-calculation-enhancements-for-financial-reporting-when-using-currency-translation"></a><span data-ttu-id="37e89-102">通貨換算を使用する場合の財務レポートの利益剰余金計算の機能強化</span><span class="sxs-lookup"><span data-stu-id="37e89-102">Retained earnings calculation enhancements for financial reporting when using currency translation</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="37e89-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="37e89-103">Enabled for</span></span>    |  <span data-ttu-id="37e89-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="37e89-104">Public preview</span></span> | <span data-ttu-id="37e89-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="37e89-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="37e89-106">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="37e89-106">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="37e89-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="37e89-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="37e89-108">2019 年 9 月 3 日</span><span class="sxs-lookup"><span data-stu-id="37e89-108">Sep 3, 2019</span></span>| <span data-ttu-id="37e89-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="37e89-109">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="37e89-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="37e89-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="37e89-111">この機能は、通貨換算を使用して所得が複数年にわたって計算される場合に、利益剰余金の計算の精度を向上させます。</span><span class="sxs-lookup"><span data-stu-id="37e89-111">This feature improves the precision of calculations of retained earnings when earnings are calculated across multiple years using currency translation.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="37e89-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="37e89-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="37e89-113">この機能を有効にすると、**為替換算タイプ**が**取引日付**に設定された利益剰余金勘定科目では、年とレートだけでなく、履歴全体のレートと残高を使用して、勘定科目の換算残高が計算されます。</span><span class="sxs-lookup"><span data-stu-id="37e89-113">When you enable this feature, any retained earnings account that has the **Currency translation type** set to **Transaction date** will calculate the translated balance of the account using rates and balances from its entire history, rather than only the year and rate.</span></span>
<!--feature detail end -->

