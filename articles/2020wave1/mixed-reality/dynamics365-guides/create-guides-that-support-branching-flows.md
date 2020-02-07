---
title: 分岐フローをサポートするガイドの作成
description: 分岐ロジックを使用して非線形のガイドを作成します。
author: relnotes
ms.reviewer: v-brycho
ms.date: 01/10/2020
ms.assetid: 9464278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: algodin
dynamics365pdf: true
ms.openlocfilehash: a452fe59f3fb9e48d0489765899d667cd315ca0a
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986704"
---
# <a name="create-guides-that-support-branching-flows"></a><span data-ttu-id="c51a3-103">分岐フローをサポートするガイドの作成</span><span class="sxs-lookup"><span data-stu-id="c51a3-103">Create guides that support branching flows</span></span>
[!include[mixed-reality/dynamics365-guides banner](../includes/mixed-reality/dynamics365-guides.md)]

| <span data-ttu-id="c51a3-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c51a3-104">Enabled for</span></span>    |  <span data-ttu-id="c51a3-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c51a3-105">Public preview</span></span> | <span data-ttu-id="c51a3-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c51a3-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c51a3-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="c51a3-107">End users, automatically</span></span>|-| <span data-ttu-id="c51a3-108">2020 年 9 月</span><span class="sxs-lookup"><span data-stu-id="c51a3-108">Sep 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c51a3-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c51a3-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c51a3-110">トレーニングおよびメンテナンス タスクは、多くの場合、複雑すぎて線形ワークフローでは対処できません。</span><span class="sxs-lookup"><span data-stu-id="c51a3-110">Training and maintenance tasks are often too complicated for linear workflows.</span></span> <span data-ttu-id="c51a3-111">分岐ロジックを使用すると、Dynamics 365 Guides の柔軟性が高まり、対応可能なユース ケースの数が増え、ソリューションが事業のニーズに適合します。</span><span class="sxs-lookup"><span data-stu-id="c51a3-111">Using branching logic makes Dynamics 365 Guides more flexible, increases the number of addressable use cases, and ensures the solution fits industrial needs.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c51a3-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c51a3-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c51a3-113">作成者は、ガイドの作成時に、入力に基づいて異なる一連のステップにオペレーターを導く分岐イベントを設定できます。</span><span class="sxs-lookup"><span data-stu-id="c51a3-113">When an author creates a guide, they'll have the option to set up branching events which will move the operator to a different set of steps based on their input.</span></span> <span data-ttu-id="c51a3-114">たとえば、作成者は、ステップ 2 の質問に対するオペレーターの回答に応じて、タスク 2 からタスク 5 にオペレーターを自動的に進める分岐を作成できます。</span><span class="sxs-lookup"><span data-stu-id="c51a3-114">For example, an author can create a branch that automatically advances operators from task 2 to task 5 depending on the operator’s answer to a question in step 2.</span></span>
<!--feature detail end -->









