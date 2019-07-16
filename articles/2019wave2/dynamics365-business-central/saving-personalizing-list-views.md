---
title: リスト ビューの保存とパーソナライズ
description: リスト ビューの保存とパーソナライズ
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 07/01/2019
ms.assetid: 386fe1f3-5f76-e911-a960-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: ede80c22b615969d99432b8110789a85531435e2
ms.sourcegitcommit: e5523d6228bfee2d93355b170028731509aed19a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/02/2019
ms.locfileid: "1722754"
---
# <a name="saving-and-personalizing-list-views"></a><span data-ttu-id="28957-103">リスト ビューの保存とパーソナライズ</span><span class="sxs-lookup"><span data-stu-id="28957-103">Saving and personalizing list views</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="28957-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="28957-104">Enabled for</span></span>    |  <span data-ttu-id="28957-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="28957-105">Public preview</span></span> | <span data-ttu-id="28957-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="28957-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="28957-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="28957-107">End users, automatically</span></span>|<span data-ttu-id="28957-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="28957-108">August 2019</span></span>| <span data-ttu-id="28957-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="28957-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="28957-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="28957-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="28957-111">ビジネスが成長するにつれて、データベース内のテーブル データも増加し、適切なツールがないと迅速な分析やレコードの検索が困難になります。</span><span class="sxs-lookup"><span data-stu-id="28957-111">As the business grows, so does table data in the database, making quick analysis or finding records more challenging without the right tools.</span></span> <span data-ttu-id="28957-112">完璧なフィルターのセットを定義することは、時間がかかる反復的なプロセスである場合があります。フィルターを維持することができれば、次に必要なときにそれらを作り直さなければならない時間を節約できます。</span><span class="sxs-lookup"><span data-stu-id="28957-112">Defining the perfect set of filters can be a time-consuming, iterative process where the ability to persist filters will save having to recreate them the next time they are needed.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="28957-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="28957-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="28957-114">ユーザーは、自分のリスト フィルターや同様の個人用設定を保存して、異なるデータ スライス方法を作成できるようになります。</span><span class="sxs-lookup"><span data-stu-id="28957-114">Users will be able to save their list filters and similar personalizations to create different ways of slicing their data.</span></span> <span data-ttu-id="28957-115">リスト ビューには名前が付けられ ("販売している商品" など)、次のような内容になります。</span><span class="sxs-lookup"><span data-stu-id="28957-115">List views are given a name, such as "Items I sell", and might include:</span></span>

- <span data-ttu-id="28957-116">合計と分析コードについてのフィルター。</span><span class="sxs-lookup"><span data-stu-id="28957-116">Filters on totals and dimensions.</span></span>
- <span data-ttu-id="28957-117">正しいデータに動的にフィルター処理するためのフィルター トークン (%MyCustomers など)。</span><span class="sxs-lookup"><span data-stu-id="28957-117">Filter tokens (such as %MyCustomers) to dynamically filter to the right data.</span></span>
- <span data-ttu-id="28957-118">リストのより複雑で調整されたビューを可能にするさまざまなソート。</span><span class="sxs-lookup"><span data-stu-id="28957-118">Different sorting to allow more complex and tailored views of a list.</span></span>

<span data-ttu-id="28957-119">ユーザーはリストの異なるビューをすばやく切り替えることができます。これには、独自の個人的なビューや、ビジネス アプリケーション、アプリ、ロールに標準で付属するビューが含まれます。</span><span class="sxs-lookup"><span data-stu-id="28957-119">Users can quickly switch between different views of a list, which includes their own personal views or views that come as standard in their business application, in apps, or for their role.</span></span>

<span data-ttu-id="28957-120">他の個人用設定と同様に、リスト ビューは、ユーザーがサインインしているデバイスやブラウザーに関係なく、ユーザーと一緒に移動します。</span><span class="sxs-lookup"><span data-stu-id="28957-120">Similar to other personalizations, list views roam with the user no matter which device or browser they sign in to.</span></span>
<!--feature detail end -->

<span data-ttu-id="28957-121">![リスト ビューへの変更保存の概念設計](media/list-views.png "リスト ビューへの変更保存の概念設計")</span><span class="sxs-lookup"><span data-stu-id="28957-121">![Concept design for saving changes to a list view](media/list-views.png "Concept design for saving changes to a list view")</span></span>
<!-- Picture 1 -->









