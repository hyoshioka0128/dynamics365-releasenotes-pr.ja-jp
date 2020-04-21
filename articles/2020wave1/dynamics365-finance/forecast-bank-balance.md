---
title: 銀行残高の予測
description: 顧客からの支払と仕入先への支払の予測に基づいて、銀行口座の残高を予測できます。
author: relnotes
ms.reviewer: roschlom
ms.date: 03/14/2020
ms.assetid: a8cc82bd-4ccb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: eeee726791586f09d6255caf748b918ba7b43ef5
ms.sourcegitcommit: 773ea4a9be0440714ed67e25d1ba572a6a25072e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/21/2020
ms.locfileid: "3152106"
---
# <a name="forecast-bank-balance"></a><span data-ttu-id="afd5b-103">銀行残高の予測</span><span class="sxs-lookup"><span data-stu-id="afd5b-103">Forecast bank balance</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="afd5b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="afd5b-104">Enabled for</span></span>    |  <span data-ttu-id="afd5b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="afd5b-105">Public preview</span></span> | <span data-ttu-id="afd5b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="afd5b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="afd5b-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="afd5b-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="afd5b-108">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="afd5b-108">May 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="afd5b-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="afd5b-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="afd5b-110">組織は複数の銀行口座を持ち、それらの口座の残高は資金の流入と流出を発生させる取引によって影響を受けます。</span><span class="sxs-lookup"><span data-stu-id="afd5b-110">Organizations have multiple bank accounts and the balances of those accounts are affected by transactions that cause funds to flow in and out of them.</span></span> <span data-ttu-id="afd5b-111">銀行残高の予測機能は、組織がビジネス上のコミットメントを満たすために使用できる現金を予測し、必要に応じてそれを満たすための追加のアクションを実行するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="afd5b-111">The Forecast bank balance feature helps organizations predict the cash that will be available to meet business commitments and if necessary, take additional action to meet them.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="afd5b-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="afd5b-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="afd5b-113">銀行残高の予測は、顧客支払の分析情報と仕入先支払からの情報だけでなく、定期的な活動にも基づいて行われます。</span><span class="sxs-lookup"><span data-stu-id="afd5b-113">Forecasts of bank balances will be based on recurring activities, as well as information from customer payment insights and vendor payments.</span></span> <span data-ttu-id="afd5b-114">銀行残高予測は、会計担当者が特定の時点での資金の利用可能性をより正確に把握するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="afd5b-114">The bank balance forecasts help treasurers more accurately understand the availability of funds at specific times.</span></span>
<!--feature detail end -->









