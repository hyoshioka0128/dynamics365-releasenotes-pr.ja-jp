---
title: フィルター式の向上
description: フィルター式の向上
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: 9f86de01-4236-ea11-a813-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 4dc0584a9888d2f3c66127269209d92bfe50ba93
ms.sourcegitcommit: 299e7ae952585bc5f8dbe620de3a9d5ef778990a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2020
ms.locfileid: "3547946"
---
# <a name="improvements-to-filter-expressions"></a><span data-ttu-id="0c5ed-103">フィルター式の向上</span><span class="sxs-lookup"><span data-stu-id="0c5ed-103">Improvements to filter expressions</span></span>


| <span data-ttu-id="0c5ed-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0c5ed-104">Enabled for</span></span>    |  <span data-ttu-id="0c5ed-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0c5ed-105">Public preview</span></span> | <span data-ttu-id="0c5ed-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="0c5ed-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0c5ed-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="0c5ed-107">End users, automatically</span></span>|<span data-ttu-id="0c5ed-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0c5ed-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0c5ed-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="0c5ed-109">Feb 1, 2020</span></span>| <span data-ttu-id="0c5ed-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0c5ed-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0c5ed-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="0c5ed-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="0c5ed-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="0c5ed-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="0c5ed-113">ビジネスが成長するにつれて、データベース内のテーブル データも増加し、適切なツールがないとデータの分析やレコードの検索を迅速に行うことが困難になります。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-113">As the business grows, so does table data in the database, making quick analysis of the data or even finding records more challenging without the right tools.</span></span> <span data-ttu-id="0c5ed-114">完全なフィルターのセットを定義することは、時間がかかる反復的なプロセスである場合があります。フィルターを維持することができれば、次に必要なときにそれらを作り直さなければならない時間を節約できます。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-114">Defining the perfect set of filters can be a time-consuming, iterative process where the ability to persist filters will save having to recreate them the next time they are needed.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="0c5ed-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0c5ed-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0c5ed-116">Business Central の 2019 年リリース ウェーブ 2 では、ユーザーがレガシ Web クライアントでフィルターをビューとして永続的に保存できるようにすることで、よく使用されるフィルターを作り直す必要がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-116">Business Central 2019 release wave 2 eliminated the need to recreate commonly used filters by allowing users to permanently save filters as a view in the legacy web client.</span></span> <span data-ttu-id="0c5ed-117">コミュニティのフィードバックに基づいて、現在はフィルターのエクスペリエンスをさらに改善しています。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-117">Based on community feedback, we're now improving the filter experience further.</span></span>

<span data-ttu-id="0c5ed-118">日付範囲やフィルター トークンなどの式を使用するフィルターを作成するときに、フィルター フィールドを切り替えて、式または対応する値を表示できます。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-118">When authoring filters that use expressions, such as date ranges or filter tokens, you can toggle the filter field to display either the expression or the corresponding value.</span></span> <span data-ttu-id="0c5ed-119">式をもう一度表示するには、キーボードまたはマウスを使用してフィルター フィールドにフォーカスを設定するだけです。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-119">To view the expression again, just set the focus to the filter field by using the keyboard or mouse.</span></span> <span data-ttu-id="0c5ed-120">この機能は以下に適用されます。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-120">This feature applies to:</span></span>

- <span data-ttu-id="0c5ed-121">リストに対するフィルター。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-121">Filters on lists.</span></span> <span data-ttu-id="0c5ed-122">これは、リスト ビューを保存するときに特に便利であり、日付や時間に依存する式を必要に応じて簡単に変更できます。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-122">Here, it is particularly useful when saving list views so that date- or time-sensitive expressions can easily be modified when needed.</span></span>
- <span data-ttu-id="0c5ed-123">レポート要求ページ、XMLPort 要求ページ、および類似のフィルター画面上のフィルターに対するフィルター。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-123">Filters to filters on report request pages, XmlPort request pages, and similar filter screens.</span></span>

<span data-ttu-id="0c5ed-124">![値としての 1 つのフィルター式と編集中の別の式を表示するフィルター処理されたリスト](media/filter-expression.png "値としての 1 つのフィルター式と編集中の別の式を表示するフィルター処理されたリスト")</span><span class="sxs-lookup"><span data-stu-id="0c5ed-124">![A filtered list showing one filter expression as values and another expression that is being edited](media/filter-expression.png "A filtered list showing one filter expression as values and another expression that is being edited")</span></span>

### <a name="try-it-now"></a><span data-ttu-id="0c5ed-125">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="0c5ed-125">Try it now</span></span>
<span data-ttu-id="0c5ed-126">[こちら](https://businesscentral.dynamics.com/?page=31)でオンライン環境にログインして、アイテム リストなどのフィルター式の設定と編集を体験してください。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-126">Experience setting and editing a filter expression, such as on the Items list, by signing into your online environment [here](https://businesscentral.dynamics.com/?page=31).</span></span>  

<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="0c5ed-127">フィードバック</span><span class="sxs-lookup"><span data-stu-id="0c5ed-127">Tell us what you think</span></span>
<span data-ttu-id="0c5ed-128">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-128">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="0c5ed-129">フォーラム (https://aka.ms/bcIdeas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="0c5ed-129">Use the forum at https://aka.ms/bcIdeas.</span></span>




## <a name="see-also"></a><span data-ttu-id="0c5ed-130">関連項目</span><span class="sxs-lookup"><span data-stu-id="0c5ed-130">See also</span></span>


<!--docs start-->
<span data-ttu-id="0c5ed-131">[リスト ビューの保存とパーソナライズ](https://docs.microsoft.com/dynamics365/business-central/ui-views) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="0c5ed-131">[Save and Personalize List Views](https://docs.microsoft.com/dynamics365/business-central/ui-views) (docs)</span></span>
<!--docs end-->

