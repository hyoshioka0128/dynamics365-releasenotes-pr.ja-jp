---
title: 複数の値によるオプション フィールドのフィルター処理
description: 複数のオプション値でのフィルター処理は、リストやレポートでの強力なフィルター処理機能を補完します。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 07/01/2019
ms.assetid: 823f20c6-e26b-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: ba35b04cfeabb0ef1cefa6f1ed6604700cbc18d6
ms.sourcegitcommit: e5523d6228bfee2d93355b170028731509aed19a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/02/2019
ms.locfileid: "1722622"
---
# <a name="filtering-option-fields-by-multiple-values"></a><span data-ttu-id="e7dc9-103">複数の値によるオプション フィールドのフィルター処理</span><span class="sxs-lookup"><span data-stu-id="e7dc9-103">Filtering option fields by multiple values</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="e7dc9-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="e7dc9-104">Enabled for</span></span>    |  <span data-ttu-id="e7dc9-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e7dc9-105">Public preview</span></span> | <span data-ttu-id="e7dc9-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="e7dc9-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="e7dc9-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="e7dc9-107">End users, automatically</span></span>|<span data-ttu-id="e7dc9-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="e7dc9-108">September 2019</span></span>| <span data-ttu-id="e7dc9-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="e7dc9-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="e7dc9-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e7dc9-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e7dc9-111">バックオフィスのインフォメーション ワーカーは、リストやレポートを処理し、フィルターを適用してデータを関連するレコードに絞り込む作業に、多くの時間を費やします。</span><span class="sxs-lookup"><span data-stu-id="e7dc9-111">Back-office information workers spend significant amounts of time working with lists and reports and applying filters to narrow down their data to the relevant records.</span></span> <span data-ttu-id="e7dc9-112">ビジネス データベースのサイズが大きくなるにつれて、ユーザーはより高度な制御を必要とすることが多くなります。</span><span class="sxs-lookup"><span data-stu-id="e7dc9-112">Users often need a higher degree of control as the size of the business database grows.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e7dc9-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e7dc9-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e7dc9-114">オプション フィールドは基本的に定義済みの値を持つ列挙です。</span><span class="sxs-lookup"><span data-stu-id="e7dc9-114">Option fields are essentially enumerations with predefined values.</span></span> <span data-ttu-id="e7dc9-115">これまで、ユーザーはオプション フィールドでフィルターを設定するときに 1 つの値しか選択できませんでした。</span><span class="sxs-lookup"><span data-stu-id="e7dc9-115">Until now, users have been able to choose only a single value when they set a filter in option fields.</span></span> <span data-ttu-id="e7dc9-116">このウェーブでは、ユーザーが複数の値でフィルター処理できるように、新しい複数選択コントロールが導入されました。</span><span class="sxs-lookup"><span data-stu-id="e7dc9-116">With this wave, we introduce a new multi-selection control so that users can filter by multiple values.</span></span> <span data-ttu-id="e7dc9-117">これは OR 演算として扱われます。</span><span class="sxs-lookup"><span data-stu-id="e7dc9-117">This is treated as an OR operation.</span></span> <span data-ttu-id="e7dc9-118">たとえば、**色**フィールドを赤、緑、または青でフィルター処理できます。</span><span class="sxs-lookup"><span data-stu-id="e7dc9-118">For example, you can filter the **Color** field by red, green, or blue.</span></span> <span data-ttu-id="e7dc9-119">値の複数選択を使用できるのはフィルター処理のときだけであり、レコードでフィールド値を指定するときは使用できません。</span><span class="sxs-lookup"><span data-stu-id="e7dc9-119">Multi-selection of values is available only when filtering, not when specifying the field value on the record.</span></span>
<!--feature detail end -->









