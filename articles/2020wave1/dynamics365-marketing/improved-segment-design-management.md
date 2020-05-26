---
title: セグメントの設計と管理の改善
description: 動的セグメント エディター内で行動データと人口統計データを直接組み合わせることにより、特定の取引先担当者をターゲットとする複雑なセグメントを作成できます。
author: relnotes
ms.reviewer: alfergus
ms.date: 04/23/2020
ms.assetid: 3a2ddc32-15ce-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: eosipova
dynamics365pdf: true
ms.openlocfilehash: ebdfc6e88ea7b69b5a380f0d3fc7bf26a61b822f
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3293183"
---
# <a name="improved-segment-design-and-management"></a><span data-ttu-id="1c66a-103">セグメントの設計と管理の改善</span><span class="sxs-lookup"><span data-stu-id="1c66a-103">Improved segment design and management</span></span>


| <span data-ttu-id="1c66a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1c66a-104">Enabled for</span></span>    |  <span data-ttu-id="1c66a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1c66a-105">Public preview</span></span> | <span data-ttu-id="1c66a-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="1c66a-106">Early access</span></span> | <span data-ttu-id="1c66a-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="1c66a-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="1c66a-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="1c66a-108">Admins, makers, or analysts, automatically</span></span>|-|-| <span data-ttu-id="1c66a-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1c66a-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1c66a-110">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="1c66a-110">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1c66a-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1c66a-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1c66a-112">改善されたセグメント管理では、セグメントの作成と編集を簡素化することにより、マーケティング担当者の時間が節約されます。</span><span class="sxs-lookup"><span data-stu-id="1c66a-112">Improved segment management saves marketers time by simplifying segment creation and editing.</span></span> <span data-ttu-id="1c66a-113">動的セグメント エディター内で行動データと人口統計データを直接組み合わせることにより、特定の取引先担当者をターゲットとする複雑なセグメントを作成できます。</span><span class="sxs-lookup"><span data-stu-id="1c66a-113">Create complex segments targeting specific contacts by combining behavioral and demographic data directly within the dynamic segment editor.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1c66a-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1c66a-114">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="1c66a-115">**セグメント作成の簡素化**: 動的セグメント エディター内で行動データと人口統計データを直接組み合わせます。</span><span class="sxs-lookup"><span data-stu-id="1c66a-115">**Simplified segment creation**: Combine behavioral and demographic data directly within the dynamic segment editor.</span></span> 
- <span data-ttu-id="1c66a-116">**静的セグメントの再設計**: 静的セグメントは、無制限の数の合計取引先担当者 (一度に最大 10,000) を処理し、ルールに基づいてリスト メンバーに追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="1c66a-116">**Static segments are redesigned**: Static segments now handle an unlimited number of total contacts (up to 10,000 at a time) and allow rule-based addition to list members.</span></span>
- <span data-ttu-id="1c66a-117">**クエリの選択**: クエリとセグメント データに基づいて静的セグメントの取引先担当者を選択できます。</span><span class="sxs-lookup"><span data-stu-id="1c66a-117">**Query selection**: Select static segment contacts based on query and segment data.</span></span>
- <span data-ttu-id="1c66a-118">**タイムゾーン対応セグメント**: セグメントはタイムゾーンに対応しており、顧客体験のタイム ゾーン機能を反映しています。</span><span class="sxs-lookup"><span data-stu-id="1c66a-118">**Time zone-aware segments**: Segments are time zone-aware, mirroring the time zone functionality in customer journeys.</span></span>
- <span data-ttu-id="1c66a-119">**新しい部分日付演算子**: 正確な日付を指定する代わりに部分的な日付を使用して、"今日" などのイベントのセグメントを作成できます。</span><span class="sxs-lookup"><span data-stu-id="1c66a-119">**New partial date operator**: Partial dates allow you to create segments for events such as “today," rather than specifying exact dates.</span></span>
<!--feature detail end -->

<span data-ttu-id="1c66a-120">![セグメント デザイナー](media/segmentation.png "セグメント デザイナー")</span><span class="sxs-lookup"><span data-stu-id="1c66a-120">![The segment designer](media/segmentation.png "The segment designer")</span></span>
<!-- Picture 1 -->








