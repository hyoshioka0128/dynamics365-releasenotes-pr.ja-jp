---
title: データをより簡単に入力する
description: データ入力の改善
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: 537b596a-851a-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 3cc07904d0325ee835daeccf480c01531cf58dd5
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232189"
---
# <a name="enter-data-more-easily"></a><span data-ttu-id="a8b12-103">データをより簡単に入力する</span><span class="sxs-lookup"><span data-stu-id="a8b12-103">Enter data more easily</span></span>


| <span data-ttu-id="a8b12-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a8b12-104">Enabled for</span></span>    |  <span data-ttu-id="a8b12-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a8b12-105">Public preview</span></span> | <span data-ttu-id="a8b12-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="a8b12-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a8b12-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="a8b12-107">End users, automatically</span></span>|<span data-ttu-id="a8b12-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a8b12-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a8b12-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a8b12-109">Feb 1, 2020</span></span>| <span data-ttu-id="a8b12-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="a8b12-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="a8b12-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a8b12-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a8b12-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a8b12-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a8b12-113">バックオフィス ワーカーは、情報の取り込みや紙の資料のデジタル化を高速で行わなければならないことがよくあります。</span><span class="sxs-lookup"><span data-stu-id="a8b12-113">Back-office workers often need to capture information or digitize paper material at high speed.</span></span> <span data-ttu-id="a8b12-114">一部のユーザーにとって、これは終日の主活動です。</span><span class="sxs-lookup"><span data-stu-id="a8b12-114">For some users, this is their main activity for the whole workday.</span></span> <span data-ttu-id="a8b12-115">OCR や AI などの手段でこれを自動化できない場合、すばやいデータ入力の邪魔にならない効率的なインターフェイスが必要です。</span><span class="sxs-lookup"><span data-stu-id="a8b12-115">When this can't be automated through means like OCR and AI, users require an efficient interface that doesn't get in the way of quickly typing in data.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a8b12-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a8b12-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a8b12-117">リスト内のフィールドの入力またはナビゲートを強化するさまざまな調整には、以下が含まれます。</span><span class="sxs-lookup"><span data-stu-id="a8b12-117">Various adjustments that enhance typing or navigating fields in a list include:</span></span>

 - <span data-ttu-id="a8b12-118">Microsoft Excel と同様に、**F2** キーを導入しました。</span><span class="sxs-lookup"><span data-stu-id="a8b12-118">Similar to Microsoft Excel, we've introduced the **F2** key.</span></span> <span data-ttu-id="a8b12-119">このキーは、フィールド全体の値の選択と値の末尾への移動を切り替えます。</span><span class="sxs-lookup"><span data-stu-id="a8b12-119">This key toggles between selecting the field's entire value and moving to end of the value.</span></span> <span data-ttu-id="a8b12-120">これにより、ユーザーは値をすばやく置き換えたり、値に追加したりできます。</span><span class="sxs-lookup"><span data-stu-id="a8b12-120">This allows users to quickly replace the value or add to it.</span></span> <span data-ttu-id="a8b12-121">キーにより、ユーザーは値をすばやく置き換えたり、値に追加したりできます。</span><span class="sxs-lookup"><span data-stu-id="a8b12-121">The key allows users to quickly replace the value or add to it.</span></span> <span data-ttu-id="a8b12-122">**F2** キーは、リスト内の編集可能フィールドと編集可能セルに使用できます。</span><span class="sxs-lookup"><span data-stu-id="a8b12-122">The **F2** key is available for editable fields and editable cells in lists.</span></span>
 
 - <span data-ttu-id="a8b12-123">データの行に入力するときに、Tab キーでは行のコンテキストを表示する省略記号にフォーカスが設定されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="a8b12-123">When typing to fill in a row of data, the Tab key no longer sets focus to the ellipses that bring up the context for the row.</span></span> <span data-ttu-id="a8b12-124">この変更により、データをすばやく入力するときの効率が向上し、Tab キーの押下が予測可能になります。</span><span class="sxs-lookup"><span data-stu-id="a8b12-124">This change improves efficiency when rapidly entering data and ensures that Tab key presses are predictable.</span></span> <span data-ttu-id="a8b12-125">コンテキスト メニューには、引き続き左右の方向キーを使用してアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="a8b12-125">The context menu remains reachable by using the left or right arrow keys.</span></span> <span data-ttu-id="a8b12-126">スペース バーまたは Enter キーを使用してアクティブ化できます。</span><span class="sxs-lookup"><span data-stu-id="a8b12-126">It can be activated using the space bar or Enter key.</span></span>
 
 - <span data-ttu-id="a8b12-127">編集可能リストでは、ユーザーは左右の方向キーを使用して、行の前または次のセルに移動できます。</span><span class="sxs-lookup"><span data-stu-id="a8b12-127">In editable lists, users can use the left and right arrow keys to navigate to the previous or next cell in a row.</span></span> <span data-ttu-id="a8b12-128">この機能により、編集可能リストと編集不可リストの間で一貫したエクスペリエンスが提供され、リストまたはワークシート内のデータを探索する速度と俊敏性が向上します。</span><span class="sxs-lookup"><span data-stu-id="a8b12-128">This capability provides a consistent experience between editable and non-editable lists and increases the speed and agility of exploring data in a list or worksheet.</span></span> <span data-ttu-id="a8b12-129">同様に、セル内の最初の文字の前にカーソルを置いて、左の方向キーを押すと、セルから抜け出し、フォーカスが前のセルに設定されます。</span><span class="sxs-lookup"><span data-stu-id="a8b12-129">Similarly, when you place the cursor before the first character in cell, pressing the left arrow key will exit the cell and set focus to the previous cell.</span></span> <span data-ttu-id="a8b12-130">また、カーソルが最後の文字の後にある場合は、逆に機能します。</span><span class="sxs-lookup"><span data-stu-id="a8b12-130">The reverse also works when the cursor is placed after the last character.</span></span>

### <a name="try-it-now"></a><span data-ttu-id="a8b12-131">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="a8b12-131">Try it now</span></span>
<span data-ttu-id="a8b12-132">[こちら](https://businesscentral.dynamics.com/?page=41&mode=create)でオンライン環境にログインして、新しい販売見積などでセルの探索と編集の俊敏性を体験してください。</span><span class="sxs-lookup"><span data-stu-id="a8b12-132">Experience the agility of exploring and editing cells, such as in a new Sales Quote, by signing into your online environment [here](https://businesscentral.dynamics.com/?page=41&mode=create).</span></span>  

<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="a8b12-133">フィードバック</span><span class="sxs-lookup"><span data-stu-id="a8b12-133">Tell us what you think</span></span>
<span data-ttu-id="a8b12-134">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="a8b12-134">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="a8b12-135">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="a8b12-135">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="a8b12-136">関連項目</span><span class="sxs-lookup"><span data-stu-id="a8b12-136">See also</span></span>


<!--docs start-->
<span data-ttu-id="a8b12-137">[データを入力する](https://docs.microsoft.com/dynamics365/business-central/ui-enter-data) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="a8b12-137">[Entering Data](https://docs.microsoft.com/dynamics365/business-central/ui-enter-data) (docs)</span></span>
<!--docs end-->

