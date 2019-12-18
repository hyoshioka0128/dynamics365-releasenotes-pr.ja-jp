---
title: セグメント化のエクスペリエンスの改善
description: セグメント化のエクスペリエンスの改善
author: jain-shailesh
ms.reviewer: kamaybac
ms.date: 11/19/2019
ms.assetid: b261278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: shjain
dynamics365pdf: true
ms.openlocfilehash: 7d3f66a78aee40419692b10ee459b68a6d4a74df
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2891813"
---
# <a name="improved-segmentation-experience"></a><span data-ttu-id="c2897-103">セグメント化のエクスペリエンスの改善</span><span class="sxs-lookup"><span data-stu-id="c2897-103">Improved segmentation experience</span></span>


| <span data-ttu-id="c2897-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c2897-104">Enabled for</span></span>    |  <span data-ttu-id="c2897-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c2897-105">Public preview</span></span> | <span data-ttu-id="c2897-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="c2897-106">Early access</span></span> | <span data-ttu-id="c2897-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="c2897-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="c2897-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="c2897-108">End users, automatically</span></span>|-|<span data-ttu-id="c2897-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c2897-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c2897-110">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="c2897-110">Aug 2, 2019</span></span>| <span data-ttu-id="c2897-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c2897-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c2897-112">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="c2897-112">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="c2897-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c2897-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c2897-114">需要創出のための的を絞った対象ユーザーを簡単に構築できます。</span><span class="sxs-lookup"><span data-stu-id="c2897-114">Build targeted audiences for demand generation easily.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c2897-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c2897-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c2897-116">適切な対象ユーザーを選択することがキャンペーンを成功させるための鍵であるため、Dynamics 365 Marketing のセグメント化デザイナーのデザインとパフォーマンスを改善する作業が続けられています。</span><span class="sxs-lookup"><span data-stu-id="c2897-116">Choosing the right target audience is key for running a successful campaign, so we’re continuing to improve the design and performance of the segmentation designer in Dynamics 365 Marketing.</span></span> <span data-ttu-id="c2897-117">今回のリリースでは、以前のデザインの使いやすさの問題点の多くに対処する新鮮で直観的なセグメント ビルダーが提供されます。</span><span class="sxs-lookup"><span data-stu-id="c2897-117">This release brings a fresh, intuitive segment builder that addresses many of the usability pain points of the previous design.</span></span> <span data-ttu-id="c2897-118">改善点は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="c2897-118">Improvements include:</span></span>

- <span data-ttu-id="c2897-119">対話ベースのセグメント、人口統計ベースのセグメント、複合セグメントなど、最もよく使用される種類のセグメントを作成するときにすばやく作業を開始できる、新しいセグメント化ハブ。</span><span class="sxs-lookup"><span data-stu-id="c2897-119">A new segmentation hub that helps you get started quickly when creating the most-used types of segments, such as interaction-based, demographics-based, and compound segments.</span></span>
- <span data-ttu-id="c2897-120">連絡先から始めてボトムアップでクエリを設計でき、より直感的で "高度な検索" 機能に似たエクスペリエンスを提供する、再設計されたクエリ ビルダー。</span><span class="sxs-lookup"><span data-stu-id="c2897-120">A redesigned query builder that lets you design queries from the bottom up, starting from contacts, which provides an experience that's more intuitive and similar to the "advanced find" feature.</span></span>
- <span data-ttu-id="c2897-121">ライブ移行前に、セグメントの構築中にいつでも要求して最新の情報に更新できる、正確なセグメント サイズの見積もり。</span><span class="sxs-lookup"><span data-stu-id="c2897-121">Accurate segment-size estimates, which you can request and refresh at any time while building a segment, prior to going live.</span></span>
- <span data-ttu-id="c2897-122">セグメント メンバーの閲覧中に連絡先リストをフィルター処理できる、新しいビュー セレクター。</span><span class="sxs-lookup"><span data-stu-id="c2897-122">A new views selector that lets you filter the contacts list while browsing segment members.</span></span>

<span data-ttu-id="c2897-123">![新しいセグメント化ハブ](media/segment-hero.jpg "新しいセグメント化ハブ")</span><span class="sxs-lookup"><span data-stu-id="c2897-123">![The new segmentation hub](media/segment-hero.jpg "The new segmentation hub")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="c2897-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="c2897-124">See also</span></span>
<span data-ttu-id="c2897-125">[機能の探索](https://youtu.be/c8YOVbo4hhw?t=152) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="c2897-125">[Feature exploration](https://youtu.be/c8YOVbo4hhw?t=152) (video)</span></span>

<span data-ttu-id="c2897-126">[8 月の更新プログラムと早期アクセス](https://cloudblogs.microsoft.com/dynamics365/it/2019/08/03/dynamics-365-for-marketing-august-update-and-early-access-are-rolling-out-now/) (ブログ)</span><span class="sxs-lookup"><span data-stu-id="c2897-126">[August update and early access](https://cloudblogs.microsoft.com/dynamics365/it/2019/08/03/dynamics-365-for-marketing-august-update-and-early-access-are-rolling-out-now/) (blog)</span></span>

<span data-ttu-id="c2897-127">[セグメントに関する作業](https://docs.microsoft.com/dynamics365/customer-engagement/marketing/new-segment-designer) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c2897-127">[Working with segments](https://docs.microsoft.com/dynamics365/customer-engagement/marketing/new-segment-designer) (docs)</span></span>
