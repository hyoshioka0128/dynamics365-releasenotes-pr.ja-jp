---
title: 一般仕訳帳明細行の数を表示する
description: 仕訳帳明細行の数が一般仕訳帳ページの下部のフィールドに表示されるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 01/24/2020
ms.assetid: b35f9776-5ffa-e911-a813-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: b4085e47bd77dfa0fe0f67432ef9a0dc2d177970
ms.sourcegitcommit: 539959f0153f0218e260146bc73a90ac391dfaa2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "3058290"
---
# <a name="view-the-number-of-general-journal-lines"></a><span data-ttu-id="36a8b-103">一般仕訳帳明細行の数を表示する</span><span class="sxs-lookup"><span data-stu-id="36a8b-103">View the number of general journal lines</span></span>


| <span data-ttu-id="36a8b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="36a8b-104">Enabled for</span></span>    |  <span data-ttu-id="36a8b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="36a8b-105">Public preview</span></span> | <span data-ttu-id="36a8b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="36a8b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="36a8b-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="36a8b-107">End users, automatically</span></span>|<span data-ttu-id="36a8b-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="36a8b-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="36a8b-109">2019 年 11 月 29 日</span><span class="sxs-lookup"><span data-stu-id="36a8b-109">Nov 29, 2019</span></span>| <span data-ttu-id="36a8b-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="36a8b-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="36a8b-111">2019 年 12 月 17 日</span><span class="sxs-lookup"><span data-stu-id="36a8b-111">Dec 17, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="36a8b-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="36a8b-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="36a8b-113">一般仕訳帳を使用してデータを Business Central に移行する場合、または数百や数千の仕訳帳明細行を処理する場合、正しい数の仕訳帳明細行がインポートされたことをすばやく確認できるととても便利です。</span><span class="sxs-lookup"><span data-stu-id="36a8b-113">When you use the general journal to migrate data to Business Central or otherwise work with hundreds or thousands of journal lines, being able to quickly verify that the correct number of journal lines were imported is very useful.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="36a8b-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="36a8b-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="36a8b-115">仕訳帳ページの下部にある仕訳帳明細行の数を参照し、すべての仕訳帳明細行がインポートされたことをすばやく確認できます。</span><span class="sxs-lookup"><span data-stu-id="36a8b-115">You can now see the number of journal lines at the bottom of the journal page and quickly verify that all journal lines were imported.</span></span> <span data-ttu-id="36a8b-116">たとえば、期首残高をインポートする場合、残高の隣の仕訳帳明細行の数を確認すると便利です。</span><span class="sxs-lookup"><span data-stu-id="36a8b-116">Checking the number of journal lines next to the balances is useful when you import opening balances, for example.</span></span> <span data-ttu-id="36a8b-117">これは、一部の仕訳帳明細行が残高勘定を使用して既に調整されている可能性があるため、仕訳帳明細行をゼロに調整しても必ずしもすべての仕訳帳明細行がインポートされるとは限らないためです。</span><span class="sxs-lookup"><span data-stu-id="36a8b-117">This is because balancing journal lines to zero doesn't always mean that all journal lines were imported because some journal lines might already have been balanced using balancing accounts.</span></span>



<span data-ttu-id="36a8b-118">![仕訳帳明細行の表示](media/view-gen-journal-no-lines.png "仕訳帳明細行の表示")</span><span class="sxs-lookup"><span data-stu-id="36a8b-118">![View of journal lines](media/view-gen-journal-no-lines.png "View of journal lines")</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="36a8b-119">フィードバック</span><span class="sxs-lookup"><span data-stu-id="36a8b-119">Tell us what you think</span></span>
<span data-ttu-id="36a8b-120">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="36a8b-120">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="36a8b-121">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="36a8b-121">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="36a8b-122">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="36a8b-122">Thank you for your idea</span></span>
<span data-ttu-id="36a8b-123">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=79938649-d048-e911-867a-0003ff68934c)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="36a8b-123">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=79938649-d048-e911-867a-0003ff68934c).</span></span> <span data-ttu-id="36a8b-124">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="36a8b-124">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="36a8b-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="36a8b-125">See also</span></span>

<span data-ttu-id="36a8b-126">[一般仕訳帳の操作](https://docs.microsoft.com/dynamics365/business-central/ui-work-general-journals) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="36a8b-126">[Working with General Journals](https://docs.microsoft.com/dynamics365/business-central/ui-work-general-journals) (docs)</span></span>
