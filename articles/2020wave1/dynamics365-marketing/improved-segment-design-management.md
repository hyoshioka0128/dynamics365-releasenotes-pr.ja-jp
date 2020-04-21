---
title: セグメントの設計と管理の改善
description: ''
author: relnotes
ms.reviewer: shellyha
ms.date: 02/19/2020
ms.assetid: 3a2ddc32-15ce-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: shsuri
dynamics365pdf: true
ms.openlocfilehash: 2b3ba93044e6d63079d100509ba763bfe3b53818
ms.sourcegitcommit: 2928661abcc468748ffc7c33516ebc8e3cd5d653
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/04/2020
ms.locfileid: "3098738"
---
# <a name="improved-segment-design-and-management"></a><span data-ttu-id="9c35c-102">セグメントの設計と管理の改善</span><span class="sxs-lookup"><span data-stu-id="9c35c-102">Improved segment design and management</span></span>
[!include[dynamics365-marketing banner](../includes/dynamics365-marketing.md)]

| <span data-ttu-id="9c35c-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="9c35c-103">Enabled for</span></span>    |  <span data-ttu-id="9c35c-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9c35c-104">Public preview</span></span> | <span data-ttu-id="9c35c-105">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="9c35c-105">Early access</span></span> | <span data-ttu-id="9c35c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="9c35c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="9c35c-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="9c35c-107">Admins, makers, or analysts, automatically</span></span>|-|-| <span data-ttu-id="9c35c-108">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="9c35c-108">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="9c35c-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9c35c-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9c35c-110">改善されたセグメント管理では、セグメントの作成と編集を簡素化することにより、マーケティング担当者の時間が節約されます。</span><span class="sxs-lookup"><span data-stu-id="9c35c-110">Improved segment management saves marketers time by simplifying segment creation and editing.</span></span> <span data-ttu-id="9c35c-111">動的セグメント エディター内で行動データと人口統計データを直接組み合わせることにより、特定の取引先担当者をターゲットとする複雑なセグメントを作成できます。</span><span class="sxs-lookup"><span data-stu-id="9c35c-111">You can create complex segments, targeting specific contacts, by combining behavioral and demographic data directly within the dynamic segment editor.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9c35c-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9c35c-112">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="9c35c-113">**セグメント作成の簡素化**: 動的セグメント エディター内で行動データと人口統計データを直接組み合わせます。</span><span class="sxs-lookup"><span data-stu-id="9c35c-113">**Simplified segment creation**: Combine behavioral and demographic data directly within the dynamic segment editor.</span></span> 
- <span data-ttu-id="9c35c-114">**静的セグメントの再設計**: 静的セグメントは、無制限の数の合計取引先担当者 (一度に最大 10,000) を処理し、ルールに基づいてリスト メンバーに追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="9c35c-114">**Static segments are redesigned**: Static segments now handle an unlimited number of total contacts (up to 10,000 at a time) and allow rule-based addition to list members.</span></span>
- <span data-ttu-id="9c35c-115">**クエリの選択**: クエリとセグメント データに基づいて静的セグメントの取引先担当者を選択できます。</span><span class="sxs-lookup"><span data-stu-id="9c35c-115">**Query selection**: You can select static segment contacts based on query and segment data.</span></span>
- <span data-ttu-id="9c35c-116">**タイムゾーン対応セグメント**: セグメントはタイムゾーンに対応しており、顧客体験のタイム ゾーン機能を反映しています。</span><span class="sxs-lookup"><span data-stu-id="9c35c-116">**Time zone-aware segments**: Segments are time zone-aware, mirroring the time zone functionality in customer journeys.</span></span>
- <span data-ttu-id="9c35c-117">**新しい部分日付演算子**: 正確な日付を指定する代わりに部分的な日付を使用して、"今日" などのイベントのセグメントや、月の初日にアクションを実行するユーザーに基づくセグメントを作成できます。</span><span class="sxs-lookup"><span data-stu-id="9c35c-117">**New partial date operator**: Partial dates allow you to create segments for events such as “today” or based on people doing an action on the first day of the month, rather than specifying exact dates.</span></span>
<!--feature detail end -->

<span data-ttu-id="9c35c-118">![セグメント デザイナー](media/segmentation.png "セグメント デザイナー")</span><span class="sxs-lookup"><span data-stu-id="9c35c-118">![The segment designer](media/segmentation.png "The segment designer")</span></span>
<!-- Picture 1 -->








