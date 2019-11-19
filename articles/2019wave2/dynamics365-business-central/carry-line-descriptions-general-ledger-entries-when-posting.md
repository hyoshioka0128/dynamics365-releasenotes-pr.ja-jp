---
title: 転記時に明細行の説明を G/L エントリに繰り越す
description: 伝票明細行タイプ別に伝票明細行から総勘定元帳エントリに説明をコピーすることができます。
author: relnotes
ms.reviewer: sgroespe
ms.date: 10/01/2019
ms.assetid: 54915d1e-4f75-e911-a960-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 101b1d46634572ef379cdb3b8a0d4f0aac52c319
ms.sourcegitcommit: 4605a04f6f017d024aded928fa875b9328e2c904
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/28/2019
ms.locfileid: "2667160"
---
# <a name="carry-line-descriptions-to-gl-entries-when-posting"></a><span data-ttu-id="e6e57-103">転記時に明細行の説明を G/L エントリに繰り越す</span><span class="sxs-lookup"><span data-stu-id="e6e57-103">Carry line descriptions to G/L entries when posting</span></span>


| <span data-ttu-id="e6e57-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="e6e57-104">Enabled for</span></span>    |  <span data-ttu-id="e6e57-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e6e57-105">Public preview</span></span> | <span data-ttu-id="e6e57-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="e6e57-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="e6e57-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="e6e57-107">End users, automatically</span></span>|<span data-ttu-id="e6e57-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e6e57-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e6e57-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="e6e57-109">Aug 1, 2019</span></span>| <span data-ttu-id="e6e57-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e6e57-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e6e57-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="e6e57-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="e6e57-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e6e57-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e6e57-113">経費などのデータを調整または監査するときに、総勘定元帳エントリで元伝票明細行の説明を見ることができれば便利です。</span><span class="sxs-lookup"><span data-stu-id="e6e57-113">When reconciling or auditing data, such as expenses, it is useful to see the source document line description in the general ledger entries.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e6e57-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e6e57-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e6e57-115">**販売および売掛金設定**ページ、**購買および買掛金設定**ページ、**サービス管理設定**ページで、**明細行の説明を G/L エントリにコピーする**チェック ボックスをオンにして、タイプが G/L 勘定である明細行の説明テキストを結果の総勘定元帳エントリに繰り越すことができます。</span><span class="sxs-lookup"><span data-stu-id="e6e57-115">On the **Sales & Receivables Setup**, **Purchases & Payables Setup**, and **Service Management Setup** pages, you can choose the **Copy Line Description to G/L Entry** check box to define for sales, purchase, and service documents that the description text on lines of type G/L Account is carried to the resulting general ledger entries.</span></span>  
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="e6e57-116">フィードバック</span><span class="sxs-lookup"><span data-stu-id="e6e57-116">Tell us what you think</span></span>
<span data-ttu-id="e6e57-117">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="e6e57-117">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="e6e57-118">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="e6e57-118">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="e6e57-119">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="e6e57-119">Thank you for your idea</span></span>
<span data-ttu-id="e6e57-120">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=1935a4ff-b040-e811-a822-0003ff68bbc0)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="e6e57-120">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=1935a4ff-b040-e811-a822-0003ff68bbc0).</span></span> <span data-ttu-id="e6e57-121">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="e6e57-121">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="e6e57-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="e6e57-122">See also</span></span>
<span data-ttu-id="e6e57-123">[機能の探索](https://aka.ms/ROGBC19RW2ROV2) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="e6e57-123">[Feature exploration](https://aka.ms/ROGBC19RW2ROV2) (video)</span></span>
