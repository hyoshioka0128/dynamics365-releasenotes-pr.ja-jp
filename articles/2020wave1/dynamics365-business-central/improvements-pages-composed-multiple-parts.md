---
title: 複数の部分で構成されるページの改善
description: 複数の部分で構成されるページの改善
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 02/03/2020
ms.assetid: f4392522-13cb-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: c8ec3e19c7343b8b12d989ef726fb1f23eb8b6cc
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3032505"
---
# <a name="improvements-to-pages-composed-of-multiple-parts"></a><span data-ttu-id="88aa3-103">複数の部分で構成されるページの改善</span><span class="sxs-lookup"><span data-stu-id="88aa3-103">Improvements to pages composed of multiple parts</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="88aa3-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="88aa3-104">Enabled for</span></span>    |  <span data-ttu-id="88aa3-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="88aa3-105">Public preview</span></span> | <span data-ttu-id="88aa3-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="88aa3-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="88aa3-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="88aa3-107">End users, automatically</span></span>|<span data-ttu-id="88aa3-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="88aa3-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="88aa3-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="88aa3-109">Feb 1, 2020</span></span>| <span data-ttu-id="88aa3-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="88aa3-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="88aa3-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="88aa3-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="88aa3-112">一部のビジネス タスクには、タスクの性質とタスクに関連したデータの量を反映した高度な画面レイアウトが必要です。</span><span class="sxs-lookup"><span data-stu-id="88aa3-112">Some business tasks require advanced screen layouts that reflect the nature of the task and the volume of data associated with the task.</span></span> <span data-ttu-id="88aa3-113">高度に最適化されたレイアウトを使用することで、ユーザーはデータの最適な概要を取得して迅速な意思決定と行動が可能になり、タスクを完了するためのスクロールやナビゲートの必要性が減少します。</span><span class="sxs-lookup"><span data-stu-id="88aa3-113">By having highly optimized layouts, users get the best overview of their data to quickly make decisions and act, reducing the need to scroll and navigate to get the task done.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="88aa3-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="88aa3-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="88aa3-115">デスクトップ クライアントには、ListParts や CardParts などの複数のパーツで構成されるページ オブジェクトの完全なサポートが追加されます。</span><span class="sxs-lookup"><span data-stu-id="88aa3-115">The desktop client will add full support for page objects that are composed of multiple parts, such as ListParts or CardParts.</span></span> <span data-ttu-id="88aa3-116">現在、これはロール センターまたは情報ボックス ペインで既に可能ですが、他のページ タイプのキャンバスは、他のコンテンツと共にパーツを表示するには最適ではありません。</span><span class="sxs-lookup"><span data-stu-id="88aa3-116">While this is already possible today on a Role Center or FactBox pane, the canvas of other page types is not optimal for displaying parts alongside other content.</span></span>

<span data-ttu-id="88aa3-117">開発者は、予測可能な結果を提供する事前定義されたパターンから選択することで、ページを実装できるようになります。</span><span class="sxs-lookup"><span data-stu-id="88aa3-117">Developers will now be able to implement pages by choosing from predefined patterns that give predictable outcomes.</span></span> <span data-ttu-id="88aa3-118">たとえば、ListPlus ページに 2 つのリストを並べて表示したり、ドキュメント ページに複数の依存リストを重ねて表示したりします。</span><span class="sxs-lookup"><span data-stu-id="88aa3-118">For example, display two lists side by side on a ListPlus page, or have multiple dependent lists shown above each other on a document page.</span></span> <span data-ttu-id="88aa3-119">2020 年 4 月からさまざまなパターンが利用可能になります。</span><span class="sxs-lookup"><span data-stu-id="88aa3-119">Different patterns will be made available starting in April 2020.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="88aa3-120">フィードバック</span><span class="sxs-lookup"><span data-stu-id="88aa3-120">Tell us what you think</span></span>
<span data-ttu-id="88aa3-121">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="88aa3-121">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="88aa3-122">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="88aa3-122">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="88aa3-123">関連項目</span><span class="sxs-lookup"><span data-stu-id="88aa3-123">See also</span></span>

<span data-ttu-id="88aa3-124">[ページ パーツの概要](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-designing-parts) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="88aa3-124">[Page parts overview](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-designing-parts) (docs)</span></span>
