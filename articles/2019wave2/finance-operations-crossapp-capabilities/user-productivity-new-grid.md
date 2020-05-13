---
title: ユーザーの生産性 - 新しいグリッド コントロール - フェーズ 1
description: ''
author: relnotes
ms.reviewer: sericks
ms.date: 03/30/2020
ms.assetid: e662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: 8afe70ac4f49fd2f2b7d461e5dfe8b1976e6a34d
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3319932"
---
# <a name="user-productivity--new-grid-control--phase-1"></a><span data-ttu-id="3e7d8-102">ユーザーの生産性 - 新しいグリッド コントロール - フェーズ 1</span><span class="sxs-lookup"><span data-stu-id="3e7d8-102">User productivity – New grid control – Phase 1</span></span>


| <span data-ttu-id="3e7d8-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="3e7d8-103">Enabled for</span></span>    |  <span data-ttu-id="3e7d8-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3e7d8-104">Public preview</span></span> | <span data-ttu-id="3e7d8-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="3e7d8-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3e7d8-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="3e7d8-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="3e7d8-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3e7d8-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3e7d8-108">2019 年 10 月 3 日</span><span class="sxs-lookup"><span data-stu-id="3e7d8-108">Oct 3, 2019</span></span>| -|






## <a name="feature-details"></a><span data-ttu-id="3e7d8-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3e7d8-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3e7d8-110">2019 年 10 月の Platform update 29 で、新しく改善されたグリッド コントロールのプレビューが利用可能になりました。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-110">A preview of a new and improved grid control was made available in October 2019 with Platform update 29.</span></span> 

<span data-ttu-id="3e7d8-111">新しいグリッドには多くの利点があります。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-111">The new grid provides a number of benefits:</span></span> 

- <span data-ttu-id="3e7d8-112">**パフォーマンス**: 新しいグリッドでは、レンダリング速度が向上し、スクロール エクスペリエンスが速くなっています。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-112">**Performance**: The new grid provides improved rendering speed and a faster scrolling experience.</span></span>
- <span data-ttu-id="3e7d8-113">**特定の位置にスクロール**: ユーザーは Web ブラウザーに読み込まれたデータ内の特定の位置にスクロールできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-113">**Positional scrolling**: Users can now positionally scroll in the data that has been loaded in the web browser.</span></span> <span data-ttu-id="3e7d8-114">たとえば、グリッド内の 10,000 行を参照する場合、スクロール バーの中央を選択するだけで、サーバーからデータを取得する必要なしに、すぐにレコード 5,000 に移動できます。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-114">For example, if you browse through 10,000 rows in a grid, you can just select the middle of the scrollbar to immediately go to record 5,000 without having to retrieve data from the server.</span></span>
- <span data-ttu-id="3e7d8-115">**一般的な改善**: 既存のグリッドでは、ユーザーがデータをスクロールしたり新しいレコードを作成したりするときに、グリッドのヘッダーとデータの位置がずれたり、グリッドがジャンプしたりすることがありました。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-115">**General improvements**: In the existing grid, users may run into situations occasionally where the grid headers and data are misaligned, or the grid jumps while users scroll through data or create new records.</span></span> <span data-ttu-id="3e7d8-116">新しいグリッドではこれらの問題がなくなります。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-116">The new grid eliminates these issues.</span></span>
- <span data-ttu-id="3e7d8-117">**列の並べ替え**: ユーザーは、列をドラッグして並べ替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-117">**Reorder columns**: Users can now reorder columns by dragging them.</span></span> <span data-ttu-id="3e7d8-118">列ヘッダーにマウス ポインターを合わせ、列の左側に表示されるグリッパー コントロールをドラッグします。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-118">Hover the mouse pointer over the column header, and then drag the gripper control that appears on the left side of the column.</span></span>
- <span data-ttu-id="3e7d8-119">**公式**: ユーザーは、グリッドの数値セルに公式を入力できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-119">**Mathematical formulas**: Users can now enter mathematical formulas into numeric cells in a grid.</span></span> <span data-ttu-id="3e7d8-120">たとえば、**=15\*4** と入力できます。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-120">For example, you can enter **=15\*4**.</span></span> <span data-ttu-id="3e7d8-121">システムによって値が式として認識されるようにするには、値を等号 (**=**) から開始します。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-121">To make the system recognize a value as an expression, start the value with an equal sign (**=**).</span></span> 

<span data-ttu-id="3e7d8-122">新しいグリッドでは、より複雑な機能を組み込むこともできます。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-122">The new grid also enables more complex features to be built into it.</span></span> <span data-ttu-id="3e7d8-123">グリッドへのこれらの追加は、以降の月次アップデートで導入および強化されます。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-123">These additions to the grid will be introduced and enhanced in subsequent monthly updates:</span></span>

- <span data-ttu-id="3e7d8-124">**合計**: ビジネス ユーザーは、表形式グリッドの数値列について合計を表示できます。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-124">**Totals**: Business users can see totals for numeric columns in tabular grids.</span></span> <span data-ttu-id="3e7d8-125">たとえば、会計担当のユーザーは、特定の顧客に対するフィルター処理されたトランザクション セットの合計を表示できます。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-125">For example, financial users can view totals for a filtered set of transactions for a specific customer.</span></span> <span data-ttu-id="3e7d8-126">この機能は、Platform update 29 の新しいグリッド コントロール機能の一部として初めて利用可能になり、以降のプラットフォーム バージョンで進化を続けます。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-126">This feature first became available as part of the new grid control feature in Platform update 29, and it will continue to evolve in subsequent platform versions.</span></span>

- <span data-ttu-id="3e7d8-127">**高速データ入力**: この機能を使用すると、ユーザーはサーバーに先行してグリッドにデータを入力できます。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-127">**Fast data entry**: This feature lets users enter data in a grid ahead of the server.</span></span> <span data-ttu-id="3e7d8-128">したがって、ユーザーが別の行に移動する前にサーバーがグリッド内の 1 行を検証するのを待つ必要性が最小限に抑えられます。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-128">Therefore, it minimizes the need for users to wait for the server to validate one row in the grid before they move to another row.</span></span> <span data-ttu-id="3e7d8-129">この機能は、Platform update 31 の新しいグリッド コントロール機能の一部として初めて利用可能になり、以降のプラットフォーム バージョンで進化を続けます。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-129">This feature first became available as part of the new grid control feature in Platform update 31, and it will continue to evolve in subsequent platform versions.</span></span>

<span data-ttu-id="3e7d8-130">新しいグリッドを有効にする方法については、以下の**関連項目**セクションのリンク先を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3e7d8-130">For instructions on how to enable the new grid, follow the link in the **See also** section below.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="3e7d8-131">関連項目</span><span class="sxs-lookup"><span data-stu-id="3e7d8-131">See also</span></span>

<!--docs start-->
<span data-ttu-id="3e7d8-132">[Platform update 31 の新機能](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/get-started/whats-new-platform-update-31) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="3e7d8-132">[What's new for Platform update 31](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/get-started/whats-new-platform-update-31) (docs)</span></span>
<!--docs end-->
