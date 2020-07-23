---
title: 類似する顧客を見つける
description: 人工知能で類似する顧客セグメントを見つけます。
author: relnotes
ms.reviewer: mhart
ms.date: 06/03/2020
ms.assetid: 2e415913-c988-ea11-a812-000d3a8faea9
ms.topic: article
ms.service: business-applications
ms.author: midevane
dynamics365pdf: true
ms.openlocfilehash: 03dbc9e401ee035afb903de88caad9e10d762814
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3440602"
---
# <a name="find-similar-customers"></a><span data-ttu-id="352f2-103">類似する顧客を見つける</span><span class="sxs-lookup"><span data-stu-id="352f2-103">Find similar customers</span></span>
[!include[artificial-intelligence/dynamics365-customer-insights banner](../includes/artificial-intelligence/dynamics365-customer-insights.md)]

| <span data-ttu-id="352f2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="352f2-104">Enabled for</span></span>    |  <span data-ttu-id="352f2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="352f2-105">Public preview</span></span> | <span data-ttu-id="352f2-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="352f2-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="352f2-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="352f2-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="352f2-108">2020 年 6 月</span><span class="sxs-lookup"><span data-stu-id="352f2-108">Jun 2020</span></span>| <span data-ttu-id="352f2-109">近日発表</span><span class="sxs-lookup"><span data-stu-id="352f2-109">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="352f2-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="352f2-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="352f2-111">セグメントの拡張により、人工知能を使用して顧客ベース内の類似する顧客を見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="352f2-111">Segment expansion lets you find similar customers in your customer base using artificial intelligence.</span></span> <span data-ttu-id="352f2-112">二項分類機械学習モデルでは、拡張されたセグメント内の顧客に類似性スコアが割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="352f2-112">A binary classification machine learning model assigns a similarity score to customers in the expanded segment.</span></span> <span data-ttu-id="352f2-113">スコアは、ソース セグメントの顧客との類似性に基づきます。</span><span class="sxs-lookup"><span data-stu-id="352f2-113">The score is based on the similarity to customers in the source segment.</span></span> <span data-ttu-id="352f2-114">類似性スコアに応じて、新しく作成されたセグメントに顧客プロファイルが追加されます。</span><span class="sxs-lookup"><span data-stu-id="352f2-114">Depending on the similarity score, customer profiles are added to a newly created segment.</span></span>

<span data-ttu-id="352f2-115">これはデジタル マーケティングで類似モデリングと呼ばれることもあり、AI モデルを使用して、追加の属性を考慮することで顧客の別のセグメントに類似する顧客を見つけるのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="352f2-115">Sometimes referred to as lookalike modeling in digital marketing, it uses an AI model to help find customers who are similar to another segment of your customers by factoring in additional attributes.</span></span> <span data-ttu-id="352f2-116">これにより、属性を選択できるだけでなく、この新しいセグメントに含まれる顧客の最大数を指定することもできます。</span><span class="sxs-lookup"><span data-stu-id="352f2-116">It not only allows you to pick the attributes but also allows you to specify the maximum number of customers who should be in this new segment.</span></span> <span data-ttu-id="352f2-117">AI モデルは、選択した属性に基づいて各顧客の類似スコアを計算し、平均類似スコアが高い顧客を探します。</span><span class="sxs-lookup"><span data-stu-id="352f2-117">The AI model will then compute similarity scores for each customer based on your selected attributes and find customers with the higher average similarity score.</span></span> <span data-ttu-id="352f2-118">結果のセグメントには、元のセグメント内の顧客に似ている顧客が含まれます。</span><span class="sxs-lookup"><span data-stu-id="352f2-118">The resulting segment will include customers who look similar to the customer in your original segment.</span></span>
<!--feature detail end -->









