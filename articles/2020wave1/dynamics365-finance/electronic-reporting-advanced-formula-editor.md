---
title: 電子申告の高度な数式エディター
description: 電子申告の数式エディターに加えて高度な電子申告の数式エディターを使用して、電子申告 (ER) の式の構成エクスペリエンスを改善できます。 高度なエディターはブラウザー ベースで、Monaco エディターによって強化されています。
author: relnotes
ms.reviewer: kfend
ms.date: 04/06/2020
ms.assetid: 7cb11ece-ef49-ea11-a812-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: filatovm
dynamics365pdf: true
ms.openlocfilehash: 6c94c5696f485d5ce40f7be817c83e5c37e250dd
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255686"
---
# <a name="electronic-reporting-advanced-formula-editor"></a><span data-ttu-id="e00ba-104">電子申告の高度な数式エディター</span><span class="sxs-lookup"><span data-stu-id="e00ba-104">Electronic reporting advanced formula editor</span></span>


| <span data-ttu-id="e00ba-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="e00ba-105">Enabled for</span></span>    |  <span data-ttu-id="e00ba-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e00ba-106">Public preview</span></span> | <span data-ttu-id="e00ba-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="e00ba-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="e00ba-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="e00ba-108">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="e00ba-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e00ba-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e00ba-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="e00ba-110">Feb 3, 2020</span></span>| <span data-ttu-id="e00ba-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e00ba-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e00ba-112">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="e00ba-112">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="e00ba-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e00ba-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e00ba-114">与信管理では、先を見越した与信管理アクティビティ提案により、顧客がプロモーションを利用して必要な購入を行える柔軟性を確保しながら、キャッシュフローを改善し、貸倒損失を減らし、信用リスクの管理に役立つ分析情報とコントロールを提供します。</span><span class="sxs-lookup"><span data-stu-id="e00ba-114">Credit management will proactively suggest credit control activities, thereby improving cashflow, reducing bad debts, and providing insight and controls that help you manage credit risks while ensuring that customers have the flexibility to take advantage of promotions and make the purchases they need.</span></span> <span data-ttu-id="e00ba-115">詳細については、「[売掛金勘定の貸方転記および取立](https://docs.microsoft.com/dynamics365/finance/accounts-receivable/collections-credit-accounts-receivable)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="e00ba-115">To learn more, refer to [Credit and collections in Accounts receivable](https://docs.microsoft.com/dynamics365/finance/accounts-receivable/collections-credit-accounts-receivable).</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e00ba-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e00ba-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e00ba-117">電子申告の数式エディターに加えて高度な電子申告の数式エディターを使用して、電子申告 (ER) の式の構成エクスペリエンスを改善できます。</span><span class="sxs-lookup"><span data-stu-id="e00ba-117">In addition to the Electronic reporting formula editor, you can use the advanced Electronic reporting formula editor to improve the experience of configuring Electronic reporting (ER) expressions.</span></span> <span data-ttu-id="e00ba-118">高度なエディターはブラウザー ベースで、Monaco エディターによって強化されています。</span><span class="sxs-lookup"><span data-stu-id="e00ba-118">The advanced editor is browser-based and powered by the Monaco editor.</span></span> <span data-ttu-id="e00ba-119">これにより、数式エディターで次の新機能を使用できます。</span><span class="sxs-lookup"><span data-stu-id="e00ba-119">It allows the following new features for the formula editor:</span></span>

- <span data-ttu-id="e00ba-120">コードのオートフォーマット</span><span class="sxs-lookup"><span data-stu-id="e00ba-120">Code autoformatting</span></span>
- <span data-ttu-id="e00ba-121">IntelliSense</span><span class="sxs-lookup"><span data-stu-id="e00ba-121">IntelliSense</span></span>
- <span data-ttu-id="e00ba-122">コードの完了</span><span class="sxs-lookup"><span data-stu-id="e00ba-122">Code completion</span></span>
- <span data-ttu-id="e00ba-123">コードのナビゲーション</span><span class="sxs-lookup"><span data-stu-id="e00ba-123">Code navigation</span></span>
- <span data-ttu-id="e00ba-124">コードの構築</span><span class="sxs-lookup"><span data-stu-id="e00ba-124">Code structuring</span></span>
- <span data-ttu-id="e00ba-125">検索と置換</span><span class="sxs-lookup"><span data-stu-id="e00ba-125">Find and replace</span></span>
- <span data-ttu-id="e00ba-126">データの貼り付け</span><span class="sxs-lookup"><span data-stu-id="e00ba-126">Data pasting</span></span>
- <span data-ttu-id="e00ba-127">構文の色付け</span><span class="sxs-lookup"><span data-stu-id="e00ba-127">Syntax colorization</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="e00ba-128">関連項目</span><span class="sxs-lookup"><span data-stu-id="e00ba-128">See also</span></span>

<!--docs start-->
<span data-ttu-id="e00ba-129">[電子申告の高度な数式エディター](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/analytics/er-advanced-formula-editor?toc=/dynamics365/finance/toc.json) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="e00ba-129">[Electronic reporting advanced formula editor](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/analytics/er-advanced-formula-editor?toc=/dynamics365/finance/toc.json) (docs)</span></span>
<!--docs end-->
