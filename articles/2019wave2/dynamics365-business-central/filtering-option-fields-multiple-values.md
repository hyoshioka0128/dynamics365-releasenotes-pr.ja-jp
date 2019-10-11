---
title: 複数の値によるオプション フィールドのフィルター処理
description: 複数のオプション値でフィルター処理することで、リストやレポートでの強力なフィルター処理機能を補完します。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 09/02/2019
ms.assetid: 823f20c6-e26b-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: ece46a475405d62addfbb845b74447f81b5ce82c
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140636"
---
# <a name="filter-option-fields-by-multiple-values"></a><span data-ttu-id="d1b6e-103">複数の値によるオプション フィールドのフィルター処理</span><span class="sxs-lookup"><span data-stu-id="d1b6e-103">Filter option fields by multiple values</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="d1b6e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="d1b6e-104">Enabled for</span></span>    |  <span data-ttu-id="d1b6e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d1b6e-105">Public preview</span></span> | <span data-ttu-id="d1b6e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="d1b6e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d1b6e-107">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="d1b6e-107">Users, automatically</span></span>|<span data-ttu-id="d1b6e-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="d1b6e-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="d1b6e-109">2019 年 9 月 1 日</span><span class="sxs-lookup"><span data-stu-id="d1b6e-109">Sep 1, 2019</span></span>| <span data-ttu-id="d1b6e-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="d1b6e-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="d1b6e-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d1b6e-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d1b6e-112">バックオフィスのインフォメーション ワーカーは、リストやレポートを処理し、フィルターを適用してデータを関連するレコードに絞り込む作業に、多くの時間を費やします。</span><span class="sxs-lookup"><span data-stu-id="d1b6e-112">Back-office information workers spend significant amounts of time working with lists and reports and applying filters to narrow down their data to the relevant records.</span></span> <span data-ttu-id="d1b6e-113">ビジネス データベースのサイズが大きくなるにつれて、ユーザーはより高度な制御を必要とすることが多くなります。</span><span class="sxs-lookup"><span data-stu-id="d1b6e-113">Users often need a higher degree of control as the size of the business database grows.</span></span> <span data-ttu-id="d1b6e-114">オプション フィールドは基本的に定義済みの値を持つ列挙型です。</span><span class="sxs-lookup"><span data-stu-id="d1b6e-114">Option fields are essentially enumerations with predefined values.</span></span> <span data-ttu-id="d1b6e-115">これまで、ユーザーはオプション フィールドでフィルターを設定するときに 1 つの値しか選択できませんでした。</span><span class="sxs-lookup"><span data-stu-id="d1b6e-115">Until now, users have been able to choose only a single value when they set a filter in option fields.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d1b6e-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d1b6e-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d1b6e-117">このウェーブでは、ユーザーが複数の値でフィルター処理できるように、タイプが**オプション**のフィールドのフィルターに新しい複数選択コントロールが導入されました。</span><span class="sxs-lookup"><span data-stu-id="d1b6e-117">With this wave, we introduce a new multi-selection control in filters for fields of type **Option** so that users can filter on these by multiple values.</span></span> <span data-ttu-id="d1b6e-118">これは OR 演算として扱われます。</span><span class="sxs-lookup"><span data-stu-id="d1b6e-118">This is treated as an OR operation.</span></span> <span data-ttu-id="d1b6e-119">たとえば、**色**フィールドを赤、緑、または青でフィルター処理できます。</span><span class="sxs-lookup"><span data-stu-id="d1b6e-119">For example, you can filter the **Color** field by red, green, or blue.</span></span>

<span data-ttu-id="d1b6e-120">複数の値によるオプション フィールドのフィルター処理は、リスト ページ、レポート、XmlPorts、および RunRequestPage コマンドや FilterPageBuilder コマンドによって駆動されるフィルター画面でのフィルター操作全体で一貫して使用できます。</span><span class="sxs-lookup"><span data-stu-id="d1b6e-120">Filtering option fields by multiple values is available consistently across filter experiences: On list pages, reports, XmlPorts, and on filter screens driven by the RunRequestPage and FilterPageBuilder commands.</span></span> <span data-ttu-id="d1b6e-121">値の複数選択を使用できるのはフィルター処理のときだけであり、レコードでフィールド値を指定するときは使用できません。</span><span class="sxs-lookup"><span data-stu-id="d1b6e-121">Multi-selection of values is available only when filtering, not when specifying the field value on the record.</span></span>

<span data-ttu-id="d1b6e-122">![複数のオプション値を使用したフィルター処理などが適用された、品目リストのフィルター処理のスクリーンショット](media/filtering-multiple-option-values.png "複数のオプション値を使用したフィルター処理などが適用された、品目リストのフィルター処理のスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="d1b6e-122">![Screenshot of filters on the Items list, including a filter on multiple option values](media/filtering-multiple-option-values.png "Screenshot of filters on the Items list, including a filter on multiple option values")</span></span>
<!--feature detail end -->








## <a name="tell-us-what-you-think"></a><span data-ttu-id="d1b6e-123">フィードバック</span><span class="sxs-lookup"><span data-stu-id="d1b6e-123">Tell us what you think</span></span>
<span data-ttu-id="d1b6e-124">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="d1b6e-124">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="d1b6e-125">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="d1b6e-125">Use the forum at https://aka.ms/bcideas.</span></span>



