---
title: ユーザーの生産性 - 新しいグリッド コントロール - フェーズ 2
description: 新しく改善されたグリッド コントロールは、10.0.9 / Platform update 33 でパブリック プレビューに移行しました。 この機能の継続的な進化は、この機能が一般公開されるまで、毎月の更新の一部として引き続き導入されます。
author: relnotes
ms.reviewer: sericks
ms.date: 04/10/2020
ms.assetid: ebd342bc-d91d-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: bfaa1c4132dcbd81a03a79d2add5d5d9830f0a50
ms.sourcegitcommit: 06f1a393c9fed93ed9b16e6615a8bf50c98c816f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/21/2020
ms.locfileid: "3273018"
---
# <a name="user-productivity--new-grid-control--phase-2"></a><span data-ttu-id="169f8-104">ユーザーの生産性 - 新しいグリッド コントロール - フェーズ 2</span><span class="sxs-lookup"><span data-stu-id="169f8-104">User productivity – new grid control – phase 2</span></span>


| <span data-ttu-id="169f8-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="169f8-105">Enabled for</span></span>    |  <span data-ttu-id="169f8-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="169f8-106">Public preview</span></span> | <span data-ttu-id="169f8-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="169f8-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="169f8-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="169f8-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="169f8-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="169f8-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="169f8-110">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="169f8-110">Apr 3, 2020</span></span>| -|






## <a name="feature-details"></a><span data-ttu-id="169f8-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="169f8-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="169f8-112">新しいグリッドには多くの利点があります。</span><span class="sxs-lookup"><span data-stu-id="169f8-112">The new grid provides a number of benefits:</span></span> 

- <span data-ttu-id="169f8-113">**パフォーマンス**: 新しいグリッドでは、レンダリング速度が向上し、スクロール エクスペリエンスが速くなっています。</span><span class="sxs-lookup"><span data-stu-id="169f8-113">**Performance**: The new grid provides improved rendering speed and a faster scrolling experience.</span></span>
- <span data-ttu-id="169f8-114">**特定の位置にスクロール**: ユーザーは Web ブラウザーに読み込まれたデータ内の特定の位置にスクロールできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="169f8-114">**Positional scrolling**: Users can now positionally scroll in the data that has been loaded in the web browser.</span></span> <span data-ttu-id="169f8-115">たとえば、グリッド内の 10,000 行を参照する場合、スクロール バーの中央をクリックするだけで、サーバーからデータを取得する必要なしに、すぐにレコード 5,000 に移動できます。</span><span class="sxs-lookup"><span data-stu-id="169f8-115">For example, if you have browsed through 10,000 rows in a grid, you can click the middle of the scrollbar to immediately go to record 5,000 without having to retrieve data from the server.</span></span>
- <span data-ttu-id="169f8-116">**全般的改善**: グリッドの使いやすさを改善するために、さまざまな機能が強化されています。</span><span class="sxs-lookup"><span data-stu-id="169f8-116">**General improvements**: Various enhancements have been made to improve the usability of the grid.</span></span> <span data-ttu-id="169f8-117">たとえば、既存のグリッドでは、ユーザーがデータをスクロールしたり新しいレコードを作成したりするときに、グリッドのヘッダーとデータの位置がずれたり、グリッドがジャンプしたりすることがありました。</span><span class="sxs-lookup"><span data-stu-id="169f8-117">For example, in the existing grid, users might run into situations occasionally where the grid headers and data are misaligned, or the grid jumps while users scroll through data or create new records.</span></span> 
- <span data-ttu-id="169f8-118">**列の並べ替え**: ユーザーは、列をドラッグして並べ替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="169f8-118">**Reorder columns**: Users can now reorder columns by dragging them.</span></span> <span data-ttu-id="169f8-119">列ヘッダーにマウス ポインターを合わせ、列の左側に表示されるグリッパー コントロールをドラッグします。</span><span class="sxs-lookup"><span data-stu-id="169f8-119">Hover the mouse pointer over the column header, and then drag the gripper control that appears on the left side of the column.</span></span>
- <span data-ttu-id="169f8-120">**公式**: ユーザーは、グリッドの数値セルに公式を入力できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="169f8-120">**Mathematical formulas**: Users can now enter mathematical formulas into numeric cells in a grid.</span></span> <span data-ttu-id="169f8-121">たとえば、**=15\*4** と入力できます。</span><span class="sxs-lookup"><span data-stu-id="169f8-121">For example, you can enter **=15\*4**.</span></span> <span data-ttu-id="169f8-122">システムによって値が式として認識されるようにするには、値を等号 (**=**) から開始します。</span><span class="sxs-lookup"><span data-stu-id="169f8-122">To make the system recognize a value as an expression, start the value with an equal sign (**=**).</span></span> 

<span data-ttu-id="169f8-123">新しいグリッドでは、より複雑な機能を組み込むこともできます。</span><span class="sxs-lookup"><span data-stu-id="169f8-123">The new grid also enables more complex features to be built into it.</span></span> <span data-ttu-id="169f8-124">グリッドへのこれらの追加は、以降の月次アップデートで導入および強化されます。</span><span class="sxs-lookup"><span data-stu-id="169f8-124">These additions to the grid will be introduced and enhanced in subsequent monthly updates:</span></span>

- <span data-ttu-id="169f8-125">**合計**: ビジネス ユーザーは、表形式グリッドの数値列について合計を表示できます。</span><span class="sxs-lookup"><span data-stu-id="169f8-125">**Totals**: Business users can see totals for numeric columns in tabular grids.</span></span> <span data-ttu-id="169f8-126">たとえば、会計担当のユーザーは、特定の顧客に対するフィルター処理されたトランザクション セットの合計を表示できます。</span><span class="sxs-lookup"><span data-stu-id="169f8-126">For example, financial users can view totals for a filtered set of transactions for a specific customer.</span></span> <span data-ttu-id="169f8-127">この機能は、10.0.5/Platform update 29 の新しいグリッド コントロール機能の一部として初めて利用可能になり、以降のプラットフォーム バージョンで進化を続けます。</span><span class="sxs-lookup"><span data-stu-id="169f8-127">This feature first became available as part of the new grid control feature in 10.0.5 / Platform update 29, and will continue to evolve in subsequent platform versions.</span></span>

- <span data-ttu-id="169f8-128">**高速データ入力**: この機能を使用すると、ユーザーはサーバーに先行してグリッドにデータを入力できます。</span><span class="sxs-lookup"><span data-stu-id="169f8-128">**Fast data entry**: This feature lets users enter data in a grid ahead of the server.</span></span> <span data-ttu-id="169f8-129">したがって、ユーザーが別の行に移動する前にサーバーがグリッド内の 1 行を検証するのを待つ必要性が最小限に抑えられます。</span><span class="sxs-lookup"><span data-stu-id="169f8-129">Therefore, it minimizes the need for users to wait for the server to validate one row in the grid before they move to another row.</span></span> <span data-ttu-id="169f8-130">この機能は、10.0.7/Platform update 31 の新しいグリッド コントロール機能の一部として初めて利用可能になり、以降のプラットフォーム バージョンで進化を続けます。</span><span class="sxs-lookup"><span data-stu-id="169f8-130">This feature first became available as part of the new grid control feature in 10.0.7 / Platform update 31, and will continue to evolve in subsequent platform versions.</span></span>

<span data-ttu-id="169f8-131">新しいグリッドを有効にする方法については、この記事の**関連項目**セクションのリンク先を参照してください。</span><span class="sxs-lookup"><span data-stu-id="169f8-131">For instructions on how to enable the new grid, follow the link in the **See also** section of this article.</span></span>

## <a name="version-updates"></a><span data-ttu-id="169f8-132">バージョンの更新</span><span class="sxs-lookup"><span data-stu-id="169f8-132">Version updates</span></span>
<span data-ttu-id="169f8-133">**10.0.11**</span><span class="sxs-lookup"><span data-stu-id="169f8-133">**10.0.11**</span></span>
- <span data-ttu-id="169f8-134">他の Dynamics 365 製品に合わせてグリッドのスタイル設定を更新。</span><span class="sxs-lookup"><span data-stu-id="169f8-134">Updated styling of the grid to better align with other Dynamics 365 products.</span></span> <span data-ttu-id="169f8-135">これには特に、マーキング列とさまざまな行の状態の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="169f8-135">This notably includes updates to the marking column and various row states.</span></span>  
- <span data-ttu-id="169f8-136">バグ修正。</span><span class="sxs-lookup"><span data-stu-id="169f8-136">Bug fixes.</span></span>

<span data-ttu-id="169f8-137">**10.0.10**</span><span class="sxs-lookup"><span data-stu-id="169f8-137">**10.0.10**</span></span>
- <span data-ttu-id="169f8-138">バグ修正。</span><span class="sxs-lookup"><span data-stu-id="169f8-138">Bug fixes.</span></span>

<span data-ttu-id="169f8-139">**10.0.9**</span><span class="sxs-lookup"><span data-stu-id="169f8-139">**10.0.9**</span></span>
- <span data-ttu-id="169f8-140">新しいグリッドのパブリック プレビュー開始。</span><span class="sxs-lookup"><span data-stu-id="169f8-140">Public preview of the new grid begins.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="169f8-141">関連項目</span><span class="sxs-lookup"><span data-stu-id="169f8-141">See also</span></span>

<!--docs start-->
<span data-ttu-id="169f8-142">[グリッド機能](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/grid-capabilities) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="169f8-142">[Grid capabilities](https://docs.microsoft.com/dynamics365/fin-ops-core/fin-ops/get-started/grid-capabilities) (docs)</span></span>
<!--docs end-->
