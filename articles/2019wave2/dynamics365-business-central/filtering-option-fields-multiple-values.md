---
title: 複数の値によるオプション フィールドのフィルター処理
description: 複数のオプション値でフィルター処理することで、リストやレポートでの強力なフィルター処理機能を補完します。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 11/15/2019
ms.assetid: 823f20c6-e26b-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 07c37e7c0dcce1f9d6a3ef998a13bb78b5c40a7e
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892176"
---
# <a name="filter-option-fields-by-multiple-values"></a><span data-ttu-id="b0731-103">複数の値によるオプション フィールドのフィルター処理</span><span class="sxs-lookup"><span data-stu-id="b0731-103">Filter option fields by multiple values</span></span>


| <span data-ttu-id="b0731-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b0731-104">Enabled for</span></span>    |  <span data-ttu-id="b0731-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b0731-105">Public preview</span></span> | <span data-ttu-id="b0731-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b0731-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b0731-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="b0731-107">End users, automatically</span></span>|<span data-ttu-id="b0731-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b0731-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b0731-109">2019 年 9 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b0731-109">Sep 1, 2019</span></span>| <span data-ttu-id="b0731-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b0731-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b0731-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="b0731-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="b0731-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b0731-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b0731-113">バックオフィスのインフォメーション ワーカーは、リストやレポートを処理し、フィルターを適用してデータを関連するレコードに絞り込む作業に、多くの時間を費やします。</span><span class="sxs-lookup"><span data-stu-id="b0731-113">Back-office information workers spend significant amounts of time working with lists and reports and applying filters to narrow down their data to the relevant records.</span></span> <span data-ttu-id="b0731-114">ビジネス データベースのサイズが大きくなるにつれて、ユーザーはより高度な制御を必要とすることが多くなります。</span><span class="sxs-lookup"><span data-stu-id="b0731-114">Users often need a higher degree of control as the size of the business database grows.</span></span> <span data-ttu-id="b0731-115">オプション フィールドは基本的に定義済みの値を持つ列挙型です。</span><span class="sxs-lookup"><span data-stu-id="b0731-115">Option fields are essentially enumerations with predefined values.</span></span> <span data-ttu-id="b0731-116">これまで、ユーザーはオプション フィールドでフィルターを設定するときに 1 つの値しか選択できませんでした。</span><span class="sxs-lookup"><span data-stu-id="b0731-116">Until now, users have been able to choose only a single value when they set a filter in option fields.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b0731-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b0731-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b0731-118">このウェーブでは、ユーザーが複数の値でフィルター処理できるように、タイプが**オプション**のフィールドのフィルターに新しい複数選択コントロールが導入されました。</span><span class="sxs-lookup"><span data-stu-id="b0731-118">With this wave, we introduce a new multi-selection control in filters for fields of type **Option** so that users can filter on these by multiple values.</span></span> <span data-ttu-id="b0731-119">これは OR 演算として扱われます。</span><span class="sxs-lookup"><span data-stu-id="b0731-119">This is treated as an OR operation.</span></span> <span data-ttu-id="b0731-120">たとえば、**色**フィールドを赤、緑、または青でフィルター処理できます。</span><span class="sxs-lookup"><span data-stu-id="b0731-120">For example, you can filter the **Color** field by red, green, or blue.</span></span>

<span data-ttu-id="b0731-121">複数の値によるオプション フィールドのフィルター処理は、リスト ページ、レポート、XmlPorts、および RunRequestPage コマンドや FilterPageBuilder コマンドによって駆動されるフィルター画面でのフィルター操作全体で一貫して使用できます。</span><span class="sxs-lookup"><span data-stu-id="b0731-121">Filtering option fields by multiple values is available consistently across filter experiences: On list pages, reports, XmlPorts, and on filter screens driven by the RunRequestPage and FilterPageBuilder commands.</span></span> <span data-ttu-id="b0731-122">値の複数選択を使用できるのはフィルター処理のときだけであり、レコードでフィールド値を指定するときは使用できません。</span><span class="sxs-lookup"><span data-stu-id="b0731-122">Multi-selection of values is available only when filtering, not when specifying the field value on the record.</span></span>

<span data-ttu-id="b0731-123">![複数のオプション値によるフィルターを含む、アイテム リストのフィルターのスクリーンショット](media/filtering-multiple-option-values.png "複数のオプション値によるフィルターを含む、アイテム リストのフィルターのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="b0731-123">![Screenshot of filters on the Items list, including a filter on multiple option values](media/filtering-multiple-option-values.png "Screenshot of filters on the Items list, including a filter on multiple option values")</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="b0731-124">フィードバック</span><span class="sxs-lookup"><span data-stu-id="b0731-124">Tell us what you think</span></span>
<span data-ttu-id="b0731-125">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="b0731-125">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="b0731-126">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="b0731-126">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="b0731-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="b0731-127">See also</span></span>
<span data-ttu-id="b0731-128">[機能の探索](https://aka.ms/ROGBC19RW2ROV6) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="b0731-128">[Feature exploration](https://aka.ms/ROGBC19RW2ROV6) (video)</span></span>

<span data-ttu-id="b0731-129">[オプション フィールドを使用したフィルター処理](https://docs.microsoft.com/dynamics365/business-central/ui-enter-criteria-filters#filtering-with-option-fields) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="b0731-129">[Filtering with Option Fields](https://docs.microsoft.com/dynamics365/business-central/ui-enter-criteria-filters#filtering-with-option-fields) (docs)</span></span>
