---
title: ツリーでより簡単に移動する
description: ツリーの移動が改善されました。
author: mikebcMSFT
ms.reviewer: jswymer
ms.date: 04/01/2020
ms.assetid: 78855116-36e1-e911-a812-000d3a4f15f1
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: 14504bae4eaf4016446280fe98e86cf7975d825b
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232772"
---
# <a name="navigate-trees-more-easily"></a><span data-ttu-id="d6dd4-103">ツリーでより簡単に移動する</span><span class="sxs-lookup"><span data-stu-id="d6dd4-103">Navigate trees more easily</span></span>


| <span data-ttu-id="d6dd4-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="d6dd4-104">Enabled for</span></span>    |  <span data-ttu-id="d6dd4-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d6dd4-105">Public preview</span></span> | <span data-ttu-id="d6dd4-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="d6dd4-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d6dd4-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="d6dd4-107">End users, automatically</span></span>|<span data-ttu-id="d6dd4-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="d6dd4-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="d6dd4-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="d6dd4-109">Feb 1, 2020</span></span>| <span data-ttu-id="d6dd4-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="d6dd4-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="d6dd4-111">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="d6dd4-111">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="d6dd4-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d6dd4-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d6dd4-113">ユーザーは、データをカテゴリにグループ化することで、概要を掴みやすくなります。</span><span class="sxs-lookup"><span data-stu-id="d6dd4-113">Users get a better overview of their data when it is grouped into categories.</span></span> <span data-ttu-id="d6dd4-114">一部のデータは、深い階層リストとして最適に表示されます。</span><span class="sxs-lookup"><span data-stu-id="d6dd4-114">Some data is best represented as a deep hierarchical list.</span></span> <span data-ttu-id="d6dd4-115">Business Central は、これらの両方のシナリオのページを開発者が設計することを可能にし、ユーザーが最善の概要を取得して関連するレコードに移動できるようにします。</span><span class="sxs-lookup"><span data-stu-id="d6dd4-115">Business Central empowers developers to design pages for both of these scenarios, so that users can get the best possible overview and navigate to the relevant records.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d6dd4-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d6dd4-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d6dd4-117">リピーター コントロールの **ShowAsTree** プロパティが True に設定されているページ オブジェクトでは、ユーザーはデータ ツリーの操作で最新レベルの効率を体験できます。</span><span class="sxs-lookup"><span data-stu-id="d6dd4-117">On page objects where a repeater control has the **ShowAsTree** property set to True, users will experience a new level of efficiency when working with the data tree.</span></span> <span data-ttu-id="d6dd4-118">ユーザーは、キーボードやマウスを使用して、簡単にドリルダウンしたり再度元に戻したりできます。</span><span class="sxs-lookup"><span data-stu-id="d6dd4-118">Users can easily drill down and back out again, using a keyboard or mouse.</span></span> <span data-ttu-id="d6dd4-119">個別のグループの展開と折りたたみを実行するか、**すべて展開**アクションと**すべて折りたたむ**アクションを使用できます。</span><span class="sxs-lookup"><span data-stu-id="d6dd4-119">They can expand and collapse individual groups or use the **Expand all** and **Collapse all** actions.</span></span> 

<span data-ttu-id="d6dd4-120">![展開ボタンと折りたたみボタンを使用した勘定科目表の探索](media/coa-tree.png "展開ボタンと折りたたみボタンを使用した勘定科目表の探索")</span><span class="sxs-lookup"><span data-stu-id="d6dd4-120">![Exploring the Chart of Accounts Overview using expand and collapse buttons](media/coa-tree.png "Exploring the Chart of Accounts Overview using expand and collapse buttons")</span></span>

<span data-ttu-id="d6dd4-121">また開発者は、リピーター コントロールにある新しいプロパティ **TreeInitialState** を使用して、ツリーを完全に展開された状態と完全に折りたたまれた状態のどちらで開くかを指定できます。</span><span class="sxs-lookup"><span data-stu-id="d6dd4-121">Developers can also specify whether a tree opens fully expanded or fully collapsed by using the new property **TreeInitialState** that is available on repeater controls.</span></span>

### <a name="try-it-now"></a><span data-ttu-id="d6dd4-122">試してみましょう</span><span class="sxs-lookup"><span data-stu-id="d6dd4-122">Try it now</span></span>
<span data-ttu-id="d6dd4-123">[https://businesscentral.dynamics.com/?page=1801](https://businesscentral.dynamics.com/?page=1801) でオンライン環境にサインインして、支援セットアップ ページなどの階層リストのすばやく簡単な探索をお試しください。</span><span class="sxs-lookup"><span data-stu-id="d6dd4-123">Experience the ease and agility of exploring a hierarchical list, such as the Assisted Setup page, by signing into your online environment at [https://businesscentral.dynamics.com/?page=1801](https://businesscentral.dynamics.com/?page=1801).</span></span>  
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="d6dd4-124">フィードバック</span><span class="sxs-lookup"><span data-stu-id="d6dd4-124">Tell us what you think</span></span>
<span data-ttu-id="d6dd4-125">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="d6dd4-125">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="d6dd4-126">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="d6dd4-126">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="d6dd4-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="d6dd4-127">See also</span></span>


<!--docs start-->
<span data-ttu-id="d6dd4-128">[インデントされた階層リストの設計](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-indented-hierarchy-lists) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="d6dd4-128">[Designing Indented Hierarchy Lists](https://docs.microsoft.com/dynamics365/business-central/dev-itpro/developer/devenv-indented-hierarchy-lists) (docs)</span></span>
<!--docs end-->

