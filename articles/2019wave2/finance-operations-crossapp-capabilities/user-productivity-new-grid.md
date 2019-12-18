---
title: ユーザーの生産性 - 新しいグリッド
description: ユーザーの生産性 - 新しいグリッド
author: relnotes
ms.reviewer: sericks
ms.date: 12/02/2019
ms.assetid: e662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: jasongre
dynamics365pdf: true
ms.openlocfilehash: f7884d6057dabfd7308a0dd473518c981b441afa
ms.sourcegitcommit: b18d8ef2595c1298c94fe6a6fd1fceaa16bd9561
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/06/2019
ms.locfileid: "2893822"
---
# <a name="user-productivity--new-grid"></a><span data-ttu-id="61fc8-103">ユーザーの生産性 - 新しいグリッド</span><span class="sxs-lookup"><span data-stu-id="61fc8-103">User productivity – New grid</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="61fc8-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="61fc8-104">Enabled for</span></span>    |  <span data-ttu-id="61fc8-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="61fc8-105">Public preview</span></span> | <span data-ttu-id="61fc8-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="61fc8-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="61fc8-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="61fc8-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="61fc8-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="61fc8-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="61fc8-109">2019 年 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="61fc8-109">Aug 5, 2019</span></span>| <span data-ttu-id="61fc8-110">2020 年 3 月</span><span class="sxs-lookup"><span data-stu-id="61fc8-110">Mar 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="61fc8-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="61fc8-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="61fc8-112">2019 年 10 月の Platform update 29 で、新しく改善されたグリッド コントロールのプレビューが利用可能になります。</span><span class="sxs-lookup"><span data-stu-id="61fc8-112">A preview of a new and improved grid control is available in October 2019 with Platform update 29.</span></span> 

<span data-ttu-id="61fc8-113">新しいグリッドには多くの利点があります。</span><span class="sxs-lookup"><span data-stu-id="61fc8-113">The new grid provides a number of benefits:</span></span> 

- <span data-ttu-id="61fc8-114">**パフォーマンス**: 新しいグリッドでは、レンダリング速度が向上し、スクロール エクスペリエンスが速くなっています。</span><span class="sxs-lookup"><span data-stu-id="61fc8-114">**Performance**: The new grid provides improved rendering speed and a faster scrolling experience.</span></span>
- <span data-ttu-id="61fc8-115">**特定の位置にスクロール**: ユーザーは Web ブラウザーに読み込まれたデータ内の特定の位置にスクロールできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="61fc8-115">**Positionally scroll**: Users can now positionally scroll in the data that has been loaded in the web browser.</span></span> <span data-ttu-id="61fc8-116">たとえば、グリッド内の 10,000 行をスクロールするには、スクロール バーの中央を選択すると、サーバーからデータを取得する必要なしに、すぐにレコード 5,000 に移動します。</span><span class="sxs-lookup"><span data-stu-id="61fc8-116">For example, to scroll through 10,000 rows in a grid, select the middle of the scrollbar to immediately go to record 5,000 without having to retrieve data from the server.</span></span>
- <span data-ttu-id="61fc8-117">**一般的な改善**: 既存のグリッドでは、グリッド ヘッダーとデータの位置がずれており、スクロールまたは新しいレコードの作成中にグリッドがジャンプします。</span><span class="sxs-lookup"><span data-stu-id="61fc8-117">**General improvements**: In the existing grid, grid headers and data are misaligned, and the grid jumps while you scroll or create new records.</span></span> <span data-ttu-id="61fc8-118">新しいグリッドではこれらの問題がなくなります。</span><span class="sxs-lookup"><span data-stu-id="61fc8-118">The new grid eliminates these issues.</span></span>
- <span data-ttu-id="61fc8-119">**列の並べ替え**: ユーザーは、列をドラッグして並べ替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="61fc8-119">**Reorder columns**: Users can now reorder columns by dragging them.</span></span> <span data-ttu-id="61fc8-120">列ヘッダーにマウス ポインターを合わせ、列の左側に表示されるグリッパー コントロールをドラッグします。</span><span class="sxs-lookup"><span data-stu-id="61fc8-120">Hover the mouse pointer over the column header, and then drag the gripper control that appears on the left side of the column.</span></span>
- <span data-ttu-id="61fc8-121">**公式**: ユーザーは、グリッドの数値セルに公式を入力できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="61fc8-121">**Mathematical formulas**: Users can now enter mathematical formulas into numeric cells in a grid.</span></span> <span data-ttu-id="61fc8-122">たとえば、**=15\*4** と入力できます。</span><span class="sxs-lookup"><span data-stu-id="61fc8-122">For example, you can enter **=15\*4**.</span></span> <span data-ttu-id="61fc8-123">システムによって値が式として認識されるようにするには、値を等号 (**=**) から開始します。</span><span class="sxs-lookup"><span data-stu-id="61fc8-123">To make the system recognize a value as an expression, start the value with an equal sign (**=**).</span></span> 

<span data-ttu-id="61fc8-124">新しいグリッドでは、より複雑な機能を組み込むこともできます。</span><span class="sxs-lookup"><span data-stu-id="61fc8-124">The new grid also enables more complex features to be built into it.</span></span> <span data-ttu-id="61fc8-125">グリッドへのこれらの追加は、以降の月次アップデートで導入および強化されます。</span><span class="sxs-lookup"><span data-stu-id="61fc8-125">These additions to the grid will be introduced and enhanced in subsequent monthly updates:</span></span>

- <span data-ttu-id="61fc8-126">**合計**: ビジネス ユーザーは、表形式グリッドの数値列について合計を表示できます。</span><span class="sxs-lookup"><span data-stu-id="61fc8-126">**Totals**: Business users can see totals for numeric columns in tabular grids.</span></span> <span data-ttu-id="61fc8-127">たとえば、会計担当のユーザーは、特定の顧客に対するフィルター処理されたトランザクション セットの合計を表示できます。</span><span class="sxs-lookup"><span data-stu-id="61fc8-127">For example, financial users can view totals for a filtered set of transactions for a specific customer.</span></span> <span data-ttu-id="61fc8-128">この機能は、Platform update 29 の新しいグリッド コントロール機能の一部として初めて利用可能になり、以降のプラットフォーム バージョンで進化を続けます。</span><span class="sxs-lookup"><span data-stu-id="61fc8-128">This feature first became available as part of the new grid control feature in Platform update 29, and it will continue to evolve in subsequent platform versions.</span></span>

  <span data-ttu-id="61fc8-129">![金額列に表示された合計](media/user-productivity-new-grid-1.png "金額列に表示された合計")</span><span class="sxs-lookup"><span data-stu-id="61fc8-129">![Total shown for the Amount column](media/user-productivity-new-grid-1.png "Total shown for the Amount column")</span></span>

- <span data-ttu-id="61fc8-130">**高速データ入力**: この機能を使用すると、ユーザーはサーバーに先行してグリッドにデータを入力できます。</span><span class="sxs-lookup"><span data-stu-id="61fc8-130">**Fast data entry**: This feature lets users enter data in a grid ahead of the server.</span></span> <span data-ttu-id="61fc8-131">したがって、ユーザーが別の行に移動する前にサーバーがグリッド内の 1 行を検証するのを待つ必要性が最小限に抑えられます。</span><span class="sxs-lookup"><span data-stu-id="61fc8-131">Therefore, it minimizes the need for users to wait for the server to validate one row in the grid before they move to another row.</span></span> <span data-ttu-id="61fc8-132">この機能は、Platform update 31 の新しいグリッド コントロール機能の一部として初めて利用可能になり、以降のプラットフォーム バージョンで進化を続けます。</span><span class="sxs-lookup"><span data-stu-id="61fc8-132">This feature first became available as part of the new grid control feature in Platform update 31, and it will continue to evolve in subsequent platform versions.</span></span>

<span data-ttu-id="61fc8-133">新しいグリッドを有効にする方法については、この記事の「関連項目」セクションのリンク先を参照してください。</span><span class="sxs-lookup"><span data-stu-id="61fc8-133">For instructions on how to enable the new grid, follow the link in the "See also" section of this article.</span></span>  
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="61fc8-134">関連項目</span><span class="sxs-lookup"><span data-stu-id="61fc8-134">See also</span></span>

<span data-ttu-id="61fc8-135">[Platform update 31 の新機能](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/get-started/whats-new-platform-update-31) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="61fc8-135">[What's new for Platform update 31](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/get-started/whats-new-platform-update-31) (docs)</span></span>
