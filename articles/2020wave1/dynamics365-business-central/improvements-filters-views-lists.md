---
title: リストでのフィルターとビューの改善
description: リストでのフィルターとビューの改善
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 01/14/2020
ms.assetid: 9f86de01-4236-ea11-a813-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 433bf0b6fe0fd5a1288e1f53f7336dc56ba0f10b
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986824"
---
# <a name="improvements-to-filters-and-views-on-lists"></a><span data-ttu-id="ef34b-103">リストでのフィルターとビューの改善</span><span class="sxs-lookup"><span data-stu-id="ef34b-103">Improvements to filters and views on lists</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="ef34b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ef34b-104">Enabled for</span></span>    |  <span data-ttu-id="ef34b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ef34b-105">Public preview</span></span> | <span data-ttu-id="ef34b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ef34b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ef34b-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="ef34b-107">End users, automatically</span></span>|<span data-ttu-id="ef34b-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="ef34b-108">Feb 2020</span></span>| <span data-ttu-id="ef34b-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="ef34b-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ef34b-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ef34b-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ef34b-111">ビジネスが成長するにつれて、データベース内のテーブル データも増加し、適切なツールがないとデータの分析やレコードの検索を迅速に行うことが困難になります。</span><span class="sxs-lookup"><span data-stu-id="ef34b-111">As the business grows, so does table data in the database, making quick analysis of the data or even finding records more challenging without the right tools.</span></span> <span data-ttu-id="ef34b-112">完全なフィルターのセットを定義することは、時間がかかる反復的なプロセスである場合があります。フィルターを維持することができれば、次に必要なときにそれらを作り直さなければならない時間を節約できます。</span><span class="sxs-lookup"><span data-stu-id="ef34b-112">Defining the perfect set of filters can be a time-consuming, iterative process where the ability to persist filters will save having to recreate them the next time they are needed.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ef34b-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ef34b-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ef34b-114">2019 年リリース ウェーブ 2 では、ユーザーがフィルターをビューとして永続的に保存できるようにすることで、よく使用されるフィルターを作り直す必要がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="ef34b-114">The 2019 release wave 2 eliminated the need to recreate commonly used filters by allowing users to permanently save filters as a view.</span></span> <span data-ttu-id="ef34b-115">コミュニティのフィードバックに基づいて、現在はフィルターのエクスペリエンスをさらに改善しています。</span><span class="sxs-lookup"><span data-stu-id="ef34b-115">Based on community feedback, we're now improving the filter experience further:</span></span>

- <span data-ttu-id="ef34b-116">日付範囲やフィルター トークンなどの式を使用するフィルターを作成するときに、フィルター フィールドを切り替えて、式または対応する値を表示できます。</span><span class="sxs-lookup"><span data-stu-id="ef34b-116">When authoring filters that use expressions such as date ranges or filter tokens, you can toggle the filter field to display either the expression or the corresponding value.</span></span> <span data-ttu-id="ef34b-117">式を表示するには、キーボードまたはマウスを使用してフィルター フィールドにフォーカスを設定するだけです。</span><span class="sxs-lookup"><span data-stu-id="ef34b-117">To view the expression, simply set the focus to the filter field using a keyboard or mouse.</span></span> <span data-ttu-id="ef34b-118">これは、リスト ビューを保存するときに特に便利であり、日付や時間に依存する式を必要に応じて簡単に変更できます。</span><span class="sxs-lookup"><span data-stu-id="ef34b-118">This is particularly useful when saving list views so that date- or time-sensitive expressions can easily be modified when needed.</span></span>

- <span data-ttu-id="ef34b-119">リスト ページにいる間に、URL をブラウザーのお気に入りとして保存すると、現在のビューが含まれるので、そのお気に入りに移動すると、ビューに直接リンクできます。</span><span class="sxs-lookup"><span data-stu-id="ef34b-119">While on a list page, saving the URL as a browser favorite will include the current view, allowing you to link directly to the view when you navigate to that favorite.</span></span>

- <span data-ttu-id="ef34b-120">Business Central でリストを使用するときは、切断された場合、または最後にアクセスしたビューに戻ろうとして Web ページをリロードした場合に、中断したところから再開できます。</span><span class="sxs-lookup"><span data-stu-id="ef34b-120">When working with lists, Business Central will help you pick up where you left off if you are disconnected or you reload the web page by trying to return to the last view you visited.</span></span>
<!--feature detail end -->









