---
title: 転記時に明細行の説明を総勘定元帳エントリに繰り越す
description: 伝票明細行タイプ別に伝票明細行から総勘定元帳エントリに説明をコピーすることができます。
author: relnotes
ms.reviewer: edupont
ms.date: 07/22/2019
ms.assetid: 54915d1e-4f75-e911-a960-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: ivkoleti
dynamics365pdf: true
ms.openlocfilehash: 379cb127f0f768d93acc0300bafe944aaab5c1df
ms.sourcegitcommit: f28876e2cf349523ecec57dd71f4cb6db56e6695
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2019
ms.locfileid: "1795837"
---
# <a name="carry-line-descriptions-to-general-ledger-entries-when-posting"></a><span data-ttu-id="f450a-103">転記時に明細行の説明を総勘定元帳エントリに繰り越す</span><span class="sxs-lookup"><span data-stu-id="f450a-103">Carry line descriptions to general ledger entries when posting</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="f450a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f450a-104">Enabled for</span></span>    |  <span data-ttu-id="f450a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f450a-105">Public preview</span></span> | <span data-ttu-id="f450a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f450a-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="f450a-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="f450a-107">End users, automatically</span></span>|<span data-ttu-id="f450a-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="f450a-108">August 2019</span></span>| <span data-ttu-id="f450a-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="f450a-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="f450a-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f450a-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f450a-111">経費などのデータを調整または監査するときに、総勘定元帳エントリで元伝票明細行の説明を見ることができれば便利です。</span><span class="sxs-lookup"><span data-stu-id="f450a-111">When reconciling or auditing data such as expenses, it is useful to see the source document line description in the general ledger entries.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f450a-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f450a-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f450a-113">**総勘定元帳の設定**ページから、**ソース説明転記設定**アクションを選択し、販売、購買、およびサービス ドキュメントについて、明細行タイプに応じて、明細説明テキストを結果の明細元帳エントリに引き継ぐかどうかを定義できます。</span><span class="sxs-lookup"><span data-stu-id="f450a-113">From the **General Ledger Setup** page, you can choose the **Source Description Posting Setup** action to define for sales, purchase, and service documents whether the line description text is carried to the resulting item ledger entries depending on the line type.</span></span> <span data-ttu-id="f450a-114">ソース明細行の説明を結果のエントリにコピーすることを選択した場合、そのような G/L エントリもドキュメント明細行ごとにグループ化されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f450a-114">Note that when you select to copy source line descriptions to the resulting entries, such G/L entries will also be grouped per document line.</span></span>
<!--feature detail end -->








## <a name="tell-us-what-you-think"></a><span data-ttu-id="f450a-115">フィードバック</span><span class="sxs-lookup"><span data-stu-id="f450a-115">Tell us what you think</span></span>
<span data-ttu-id="f450a-116">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="f450a-116">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="f450a-117">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="f450a-117">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="f450a-118">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="f450a-118">Thank you for your idea</span></span>
<span data-ttu-id="f450a-119">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=1935a4ff-b040-e811-a822-0003ff68bbc0)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="f450a-119">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=1935a4ff-b040-e811-a822-0003ff68bbc0).</span></span> <span data-ttu-id="f450a-120">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="f450a-120">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>
