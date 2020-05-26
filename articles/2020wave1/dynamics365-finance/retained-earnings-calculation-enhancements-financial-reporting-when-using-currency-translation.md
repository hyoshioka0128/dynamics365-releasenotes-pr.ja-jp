---
title: 通貨換算を使用する場合の財務レポートの利益剰余金計算の機能強化
description: 通貨換算を含む財務レポートを生成する場合、利益剰余金の計算には、勘定科目の履歴全体からのレートと残高が含まれるようになりました。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/09/2020
ms.assetid: 0b6beafb-5f3d-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: c02baccab1c13293b18b39dc9a774d0a801154ce
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3272941"
---
# <a name="retained-earnings-calculation-enhancements-for-financial-reporting-when-using-currency-translation"></a><span data-ttu-id="476e2-103">通貨換算を使用する場合の財務レポートの利益剰余金計算の機能強化</span><span class="sxs-lookup"><span data-stu-id="476e2-103">Retained earnings calculation enhancements for financial reporting when using currency translation</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="476e2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="476e2-104">Enabled for</span></span>    |  <span data-ttu-id="476e2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="476e2-105">Public preview</span></span> | <span data-ttu-id="476e2-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="476e2-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="476e2-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="476e2-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="476e2-108">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="476e2-108">Aug 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="476e2-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="476e2-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="476e2-110">外貨換算を含む財務レポートを生成する場合、利益剰余金の計算には、年とレートだけでなく、勘定科目の履歴全体からのレートと残高が含まれるようになりました。</span><span class="sxs-lookup"><span data-stu-id="476e2-110">When generating financial reports that include currency translation, the retained earnings calculations now include rates and balances from the account's entire history, rather than only the year and rate.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="476e2-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="476e2-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="476e2-112">この機能を有効にすると、**為替換算タイプ**が**取引日付**に設定された利益剰余金勘定科目では、年とレートだけでなく、履歴全体のレートと残高を使用して、勘定科目の換算残高が計算されます。</span><span class="sxs-lookup"><span data-stu-id="476e2-112">When you enable this feature, any retained earnings account that has the **Currency translation type** set to **Transaction date** will calculate the translated balance of the account using rates and balances from its entire history, rather than only the year and rate.</span></span>
<!--feature detail end -->









