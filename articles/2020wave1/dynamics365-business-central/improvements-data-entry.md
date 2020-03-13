---
title: データをより簡単に入力する
description: データ入力の改善
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 02/03/2020
ms.assetid: 537b596a-851a-ea11-a812-000d3a8f010c
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 3a982d7d94bb70e6b3caff6b469c12b45f5f3260
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3031827"
---
# <a name="enter-data-more-easily"></a><span data-ttu-id="8108a-103">データをより簡単に入力する</span><span class="sxs-lookup"><span data-stu-id="8108a-103">Enter data more easily</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="8108a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="8108a-104">Enabled for</span></span>    |  <span data-ttu-id="8108a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8108a-105">Public preview</span></span> | <span data-ttu-id="8108a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="8108a-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8108a-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="8108a-107">End users, automatically</span></span>|<span data-ttu-id="8108a-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="8108a-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="8108a-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="8108a-109">Feb 1, 2020</span></span>| <span data-ttu-id="8108a-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8108a-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="8108a-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="8108a-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="8108a-112">バックオフィス ワーカーは、情報の取り込みや紙の資料のデジタル化を高速で行わなければならないことがよくあります。</span><span class="sxs-lookup"><span data-stu-id="8108a-112">Back-office workers often need to capture information or digitize paper material at high speed.</span></span> <span data-ttu-id="8108a-113">一部のユーザーにとって、これは終日の主活動です。</span><span class="sxs-lookup"><span data-stu-id="8108a-113">For some users, this is their main activity for the whole work day.</span></span> <span data-ttu-id="8108a-114">OCR や AI などの手段でこれを自動化できない場合、すばやいデータ入力の邪魔にならない効率的なインターフェイスが必要です。</span><span class="sxs-lookup"><span data-stu-id="8108a-114">When this cannot be automated through means like OCR and AI, users require an efficient interface that does not get in the way of quickly typing in data.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="8108a-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8108a-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8108a-116">リスト内のフィールドの入力またはナビゲートを強化するさまざまな調整。</span><span class="sxs-lookup"><span data-stu-id="8108a-116">Various adjustments that enhance typing or navigating fields in a list.</span></span>

 - <span data-ttu-id="8108a-117">編集可能リストでは、ユーザーは左右の方向キーを使用して、行の前または次のセルに移動できます。</span><span class="sxs-lookup"><span data-stu-id="8108a-117">In editable lists, users will be able to use the left and right arrow keys to navigate to the previous or next cell in a row.</span></span> <span data-ttu-id="8108a-118">これにより、編集可能リストと編集不可リストの間で一貫したエクスペリエンスが提供され、リストまたはワークシート内のデータを探索する速度と俊敏性が向上します。</span><span class="sxs-lookup"><span data-stu-id="8108a-118">This provides a consistent experience between editable and non-editable lists, and increases the speed and agility of exploring data in a list or worksheet.</span></span>
 - <span data-ttu-id="8108a-119">Microsoft Excel と同様に、フィールドの値全体を選択するか、値の末尾にカーソルを置くかを切り替える F2 キーを導入しました。</span><span class="sxs-lookup"><span data-stu-id="8108a-119">Similar to Microsoft Excel, we've introduced the F2 key that toggles between selecting the entire value of a field and placing the cursor at the end of the value.</span></span> <span data-ttu-id="8108a-120">これにより、ユーザーは値をすばやく置き換えたり、値に追加したりできます。</span><span class="sxs-lookup"><span data-stu-id="8108a-120">This allows users to quickly replace the value or add to it.</span></span> <span data-ttu-id="8108a-121">F2 キーは、リスト内の編集可能フィールドと編集可能セルに使用できます。</span><span class="sxs-lookup"><span data-stu-id="8108a-121">The F2 key is available for editable fields and editable cells in lists.</span></span>
 - <span data-ttu-id="8108a-122">データの行に入力するときに、Tab キーでは行のコンテキストを表示する省略記号にフォーカスが設定されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="8108a-122">When typing to fill in a row of data, the Tab key no longer sets focus to the ellipses that bring up the context for the row.</span></span> <span data-ttu-id="8108a-123">これにより、データをすばやく入力するときの効率が向上し、Tab キーの押下が予測可能になります。</span><span class="sxs-lookup"><span data-stu-id="8108a-123">This improves efficiency when rapidly entering data and ensures that Tab key presses are predictable.</span></span> <span data-ttu-id="8108a-124">コンテキスト メニューには、引き続き左右の方向キーを使用してアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="8108a-124">The context menu remains reachable using the left or right arrow keys.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="8108a-125">フィードバック</span><span class="sxs-lookup"><span data-stu-id="8108a-125">Tell us what you think</span></span>
<span data-ttu-id="8108a-126">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="8108a-126">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="8108a-127">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="8108a-127">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="8108a-128">関連項目</span><span class="sxs-lookup"><span data-stu-id="8108a-128">See also</span></span>

<span data-ttu-id="8108a-129">[データを入力する](https://docs.microsoft.com/dynamics365/business-central/ui-enter-data) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="8108a-129">[Entering Data](https://docs.microsoft.com/dynamics365/business-central/ui-enter-data) (docs)</span></span>
