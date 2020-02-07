---
title: 仕訳帳別転記済みトランザクション レポートのデータ範囲
description: 仕訳帳別転記済みトランザクション レポートで、レポートの生成時に日付範囲の指定が必須となりました。  既定では、この機能は無効になっています。
author: relnotes
ms.reviewer: roschlom
ms.date: 01/08/2020
ms.assetid: b7cd1474-eb21-ea11-a810-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 1fe10a6d1ec88e2020cc5014e763a6f5e68d7cf1
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986610"
---
# <a name="date-range-for-posted-transactions-by-journals-report"></a><span data-ttu-id="840f1-104">仕訳帳別転記済みトランザクション レポートのデータ範囲</span><span class="sxs-lookup"><span data-stu-id="840f1-104">Date range for Posted transactions by journals report</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="840f1-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="840f1-105">Enabled for</span></span>    |  <span data-ttu-id="840f1-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="840f1-106">Public preview</span></span> | <span data-ttu-id="840f1-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="840f1-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="840f1-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="840f1-108">End users, automatically</span></span>|<span data-ttu-id="840f1-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="840f1-109">Feb 2020</span></span>| <span data-ttu-id="840f1-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="840f1-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="840f1-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="840f1-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="840f1-112">仕訳帳別転記済みトランザクション レポートで、日付範囲の指定が必須となりました。これにより、レポートの生成が迅速化されます。</span><span class="sxs-lookup"><span data-stu-id="840f1-112">The Posted transactions by journals report now requires a date range, which allows it to be generated faster.</span></span>  <span data-ttu-id="840f1-113">日付範囲を指定することで、仕訳帳別転記済みトランザクション レポートで処理されるデータの量が制限されます。</span><span class="sxs-lookup"><span data-stu-id="840f1-113">Specifying a date range limits the amount of data that’s processed for the Posted transactions by journals report.</span></span> <span data-ttu-id="840f1-114">制限がないと、処理されるデータの量が膨大になり、システムのパフォーマンスが大幅に低下する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="840f1-114">Without any restriction, the amount of data that’s processed can be huge, and can significantly degrade system performance.</span></span>  
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="840f1-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="840f1-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="840f1-116">既定では、この機能は無効になっています。</span><span class="sxs-lookup"><span data-stu-id="840f1-116">This feature is enabled by default.</span></span> <span data-ttu-id="840f1-117">この変更により、ユーザー インターフェイスに 2 つのフィールドが追加されます。**開始日**フィールドと**終了日**フィールドです (仕訳帳別転記済みトランザクション レポートのレポート ダイアログに表示されます)。</span><span class="sxs-lookup"><span data-stu-id="840f1-117">This change adds two fields to the user interface, a **From date** field and a **To date** field, on the report dialog for the Posted transactions by journals report.</span></span>
<!--feature detail end -->









