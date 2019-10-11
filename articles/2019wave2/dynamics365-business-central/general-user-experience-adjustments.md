---
title: 一般的なユーザー エクスペリエンスの調整
description: Dynamics 365 および Office 365 に対する熟知を維持する一般的なユーザー エクスペリエンスの調整。
author: mikebcMSFT
ms.reviewer: sgroespe
ms.date: 09/02/2019
ms.assetid: 8b58ce5a-6a6c-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: mikebc
dynamics365pdf: true
ms.openlocfilehash: a7b915e04dd943dea93d671721d2fee867d4ddcd
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140592"
---
# <a name="general-user-experience-adjustments"></a><span data-ttu-id="c41c9-103">一般的なユーザー エクスペリエンスの調整</span><span class="sxs-lookup"><span data-stu-id="c41c9-103">General user experience adjustments</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="c41c9-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c41c9-104">Enabled for</span></span>    |  <span data-ttu-id="c41c9-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c41c9-105">Public preview</span></span> | <span data-ttu-id="c41c9-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c41c9-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c41c9-107">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="c41c9-107">Users, automatically</span></span>|<span data-ttu-id="c41c9-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c41c9-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c41c9-109">2019 年 8 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c41c9-109">Aug 1, 2019</span></span>| <span data-ttu-id="c41c9-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="c41c9-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="c41c9-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c41c9-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c41c9-112">ビジネス ユーザーは多くの場合、生産性アプリとビジネス アプリを利用して作業を完了します。</span><span class="sxs-lookup"><span data-stu-id="c41c9-112">Business users often work across productivity and business apps to complete their tasks.</span></span> <span data-ttu-id="c41c9-113">アプリを行き来するとき、ユーザー エクスペリエンスの違いによりストレスが生じ、生産性が低下します。</span><span class="sxs-lookup"><span data-stu-id="c41c9-113">As they transition back and forth, differences in user experiences cause friction and lost productivity.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c41c9-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c41c9-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c41c9-115">このアップデートでは Dynamics 365 と Office 365 で使い慣れたルック アンド フィールを維持しつつ、いっそうわかりやすいデザイン要素の追加と、ボタン、リストのヘッダー、パーツのキャプションに対する微細なスタイルの変更が行われています。</span><span class="sxs-lookup"><span data-stu-id="c41c9-115">Continuing our familiar look and feel across Dynamics 365 and Office 365, this update includes the addition of more fluent design elements and subtle stylistic changes to buttons, list headers, and captions on parts.</span></span>

<span data-ttu-id="c41c9-116">行のスタイルが若干改善され、複数のレコードを選択する際の新しいインジケーターが追加されました。</span><span class="sxs-lookup"><span data-stu-id="c41c9-116">Rows have minor stylistic improvements and a new indicator when selecting multiple records.</span></span>

<span data-ttu-id="c41c9-117">水平方向のスペースを活用し、新しいクリック ターゲットを適用できるようにブロックが拡大され、個々のブロックの選択と関連する情報ボックスの選択が簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c41c9-117">Bricks stretch to fill the available horizontal space and apply new click targets that make it easier to select an individual brick and display related FactBoxes.</span></span> <span data-ttu-id="c41c9-118">また、Ctrl + C キーボード ショートカットで 1 つのブロックをコピーできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c41c9-118">The Ctrl+C keyboard shortcut to copy a single brick has also been enabled.</span></span>

<span data-ttu-id="c41c9-119">ロール センターでは、ルートレベルのアクションがアクション グループから自動的に分離されなくなります。</span><span class="sxs-lookup"><span data-stu-id="c41c9-119">Role Centers no longer automatically separate root-level actions from action groups.</span></span> <span data-ttu-id="c41c9-120">コード内で定義された順序が尊重され、クライアントで各アクション領域に反映されます。</span><span class="sxs-lookup"><span data-stu-id="c41c9-120">The sequence in which they were defined in code is respected and reflected in the client for each action area.</span></span>
<!--feature detail end -->

<span data-ttu-id="c41c9-121">![スタイルが新しくなったブロック レイアウトのスクリーンショット](media/bricks-3000x2000.png "スタイルが新しくなったブロック レイアウトのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="c41c9-121">![A screenshot of the restyled brick layout](media/bricks-3000x2000.png "A screenshot of the restyled brick layout")</span></span>
<!-- Picture 1 -->
<span data-ttu-id="c41c9-122">![新しい行選択インジケーターが示されたリスト ページのスクリーンショット](media/rows-3000x2000.png "新しい行選択インジケーターが示されたリスト ページのスクリーンショット")</span><span class="sxs-lookup"><span data-stu-id="c41c9-122">![A screenshot of a list page demonstrating the new row selection indicators](media/rows-3000x2000.png "A screenshot of a list page demonstrating the new row selection indicators")</span></span>
<!-- Picture 2 -->







## <a name="tell-us-what-you-think"></a><span data-ttu-id="c41c9-123">フィードバック</span><span class="sxs-lookup"><span data-stu-id="c41c9-123">Tell us what you think</span></span>
<span data-ttu-id="c41c9-124">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="c41c9-124">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="c41c9-125">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="c41c9-125">Use the forum at https://aka.ms/bcideas.</span></span>



