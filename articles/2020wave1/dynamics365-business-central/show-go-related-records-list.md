---
title: リストから関連レコードを表示してそのレコードに移動する
description: リストから関連エントリに簡単に移動できます。
author: kotelko
ms.reviewer: jswymer
ms.date: 04/07/2020
ms.assetid: 6150b591-13cb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: blazkote
dynamics365pdf: true
ms.openlocfilehash: 389c55a4e5aea4de2d560adcc331f47f6c52d28e
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255829"
---
# <a name="show-and-go-to-related-records-from-a-list"></a><span data-ttu-id="c8ea7-103">リストから関連レコードを表示してそのレコードに移動する</span><span class="sxs-lookup"><span data-stu-id="c8ea7-103">Show and go to related records from a list</span></span>


| <span data-ttu-id="c8ea7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c8ea7-104">Enabled for</span></span>    |  <span data-ttu-id="c8ea7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c8ea7-105">Public preview</span></span> | <span data-ttu-id="c8ea7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c8ea7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c8ea7-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="c8ea7-107">End users, automatically</span></span>|<span data-ttu-id="c8ea7-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c8ea7-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c8ea7-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c8ea7-109">Feb 1, 2020</span></span>| <span data-ttu-id="c8ea7-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c8ea7-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c8ea7-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c8ea7-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c8ea7-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c8ea7-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c8ea7-113">ビジネス データ内を移動したり、あるコンテキストから別のコンテキストにジャンプしたり、単純にデータをドリル スルーしたりすることは、忙しいプロフェッショナルにとって不可欠です。</span><span class="sxs-lookup"><span data-stu-id="c8ea7-113">Navigating through your business data, jumping from one context to the other, or simply drilling through data is essential for a busy professional.</span></span> <span data-ttu-id="c8ea7-114">テーブル間の関係は Business Central 全体の多くのページで定義されているため、ページ間をジャンプできるリンクが自動的に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c8ea7-114">Since relation between tables is defined in many pages across Business Central, the links allowing you to jump between pages would show up automatically as a consequence.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c8ea7-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c8ea7-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c8ea7-116">ユーザーが関連エントリやその他の多くの場所へリンクを介してナビゲートするための機能がいくつか追加されました。</span><span class="sxs-lookup"><span data-stu-id="c8ea7-116">We have added some capabilities for users to navigate via links to related entries or even more places.</span></span> <span data-ttu-id="c8ea7-117">Business Central Web クライアントに、ユーザーがリストから別のエンティティに移動するためのリンクが導入されます。</span><span class="sxs-lookup"><span data-stu-id="c8ea7-117">Business Central web client introduces links allowing users to traverse to different entities from a list.</span></span> <span data-ttu-id="c8ea7-118">これにより、たとえば販売注文から顧客カードや品目カードを開くなど、リストから関連カードを開くことができます (これを機能させるには、ドキュメント カード ページがビュー モードになっている必要があります)。</span><span class="sxs-lookup"><span data-stu-id="c8ea7-118">This allows you to open a related card from a list, such as a customer or item card from a sales order (note that the document card page needs to be in view mode for this to work).</span></span>

<span data-ttu-id="c8ea7-119">パートナーは、既存のテーブル関係を再利用するか新しいテーブル関係を作成し (「[TableRelation プロパティ](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/properties/devenv-tablerelation-property)」を参照してください)、アプリに新しいエクスペリエンスを導入できます。</span><span class="sxs-lookup"><span data-stu-id="c8ea7-119">Partners can reuse existing or create new table relations (see [TableRelation Property](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/properties/devenv-tablerelation-property)) and light up new experiences in their apps.</span></span>
<!--feature detail end -->

<span data-ttu-id="c8ea7-120">![リストから開いている関連エントリへの簡単な移動](media/related-link.png "リストから開いている関連エントリへの簡単な移動")</span><span class="sxs-lookup"><span data-stu-id="c8ea7-120">![Easy navigation to open related entries from lists](media/related-link.png "Easy navigation to open related entries from lists")</span></span>
<!-- Picture 1 -->





## <a name="tell-us-what-you-think"></a><span data-ttu-id="c8ea7-121">フィードバック</span><span class="sxs-lookup"><span data-stu-id="c8ea7-121">Tell us what you think</span></span>
<span data-ttu-id="c8ea7-122">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="c8ea7-122">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="c8ea7-123">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="c8ea7-123">Use the forum at https://aka.ms/bcideas.</span></span>



## <a name="thank-you-for-your-idea"></a><span data-ttu-id="c8ea7-124">アイデアをありがとうございます</span><span class="sxs-lookup"><span data-stu-id="c8ea7-124">Thank you for your idea</span></span>
<span data-ttu-id="c8ea7-125">[このアイデア](https://experience.dynamics.com/ideas/idea/?ideaid=4075b3be-5ba8-e811-b96f-0003ff68a2af)をお送りいただき、ありがとうございました。</span><span class="sxs-lookup"><span data-stu-id="c8ea7-125">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=4075b3be-5ba8-e811-b96f-0003ff68a2af).</span></span> <span data-ttu-id="c8ea7-126">アイデア、コメント、投票を参考に、製品のロードマップに追加するものを決定しています。</span><span class="sxs-lookup"><span data-stu-id="c8ea7-126">We listened to your idea, along with comments and votes, to help us decide what to add to our product roadmap.</span></span>

## <a name="see-also"></a><span data-ttu-id="c8ea7-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="c8ea7-127">See also</span></span>

<!--docs start-->
<span data-ttu-id="c8ea7-128">[Business Central のドキュメント](https://docs.microsoft.com/dynamics365/business-central/) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c8ea7-128">[Business Central documentation](https://docs.microsoft.com/dynamics365/business-central/) (docs)</span></span>
<!--docs end-->
