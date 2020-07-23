---
title: 追加の演算子
description: セグメント用の新しい演算子では、単一の条件で複数の文字列値を選択できます。
author: relnotes
ms.reviewer: mhart
ms.date: 05/12/2020
ms.assetid: 95c9f5bc-8f86-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: midevane
dynamics365pdf: true
ms.openlocfilehash: 625bacf77822fbb9251ac7e4f63c3f79f77aa317
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3382583"
---
# <a name="additional-operator"></a><span data-ttu-id="0acd5-103">追加の演算子</span><span class="sxs-lookup"><span data-stu-id="0acd5-103">Additional operator</span></span>
[!include[artificial-intelligence/dynamics365-customer-insights banner](../includes/artificial-intelligence/dynamics365-customer-insights.md)]

| <span data-ttu-id="0acd5-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0acd5-104">Enabled for</span></span>    |  <span data-ttu-id="0acd5-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0acd5-105">Public preview</span></span> | <span data-ttu-id="0acd5-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="0acd5-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0acd5-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="0acd5-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="0acd5-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0acd5-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0acd5-109">2020 年 4 月 30 日</span><span class="sxs-lookup"><span data-stu-id="0acd5-109">Apr 30, 2020</span></span>| <span data-ttu-id="0acd5-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="0acd5-110">Jul 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="0acd5-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0acd5-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0acd5-112">In-set 演算子を使用すると、いくつかの可能な文字列値で顧客をセグメント化できます。</span><span class="sxs-lookup"><span data-stu-id="0acd5-112">The In-set operator allows segmentation for customers by several possible string values.</span></span> <span data-ttu-id="0acd5-113">この演算子が追加される前は、そのようなセグメントを作成するには複数の OR 条件を使用する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="0acd5-113">Before this operator was added, you had to construct such segments with multiple OR conditions.</span></span> <span data-ttu-id="0acd5-114">In-set 演算子を使用すると、単一の条件でそれを行うことができます。</span><span class="sxs-lookup"><span data-stu-id="0acd5-114">The In-set operator lets you do that with a single condition.</span></span>

<span data-ttu-id="0acd5-115">![セグメント内演算子オプションのビジュアル](media/in-set-segment.png "セグメント内演算子オプションのビジュアル")</span><span class="sxs-lookup"><span data-stu-id="0acd5-115">![Visual of in-segment operator options](media/in-set-segment.png "Visual of in-segment operator options")</span></span>

<span data-ttu-id="0acd5-116">たとえば、次の条件でセグメントを作成できます。</span><span class="sxs-lookup"><span data-stu-id="0acd5-116">For example, you can create segments with the following conditions:</span></span>

- <span data-ttu-id="0acd5-117">メンバーはニューヨークまたはシカゴ出身である。</span><span class="sxs-lookup"><span data-stu-id="0acd5-117">Members are either from New York or Chicago.</span></span>
- <span data-ttu-id="0acd5-118">メンバーは $100 または $200 を消費した。</span><span class="sxs-lookup"><span data-stu-id="0acd5-118">Members spent either $100 or $200.</span></span>
- <span data-ttu-id="0acd5-119">メンバーは日付 X または Y に購入した。</span><span class="sxs-lookup"><span data-stu-id="0acd5-119">Members purchased on date X or Y.</span></span>


<!--feature detail end -->









