---
title: 空間トリガーを使用してガイド内を前後に移動する
description: 空間トリガーは、作成者が他のホログラムと同じように配置する 3D ホログラムです。 空間トリガーには 2 つの種類があります。 ボリューム トリガーは、作成者には半透明ですが、オペレーターには見えません。 オペレーターの手がこのタイプのトリガーに当たると、トリガーのタイプに応じて、ガイドが次の手順または前の手順に自動的に進みます。 ユーザーにはフィードバックが提供されます。 2 番目のタイプは、事前構築された [次へ] および [戻る] ホログラフィック ボタンです。 オペレーターはこれらのホログラフィック ボタンを押して、ガイドの次または前の手順に移動できます。 どちらのタイプのトリガーでも、オペレーターは指示カードの [次へ] または [戻る] ボタンを見つめる必要なくガイド内を移動できます。 作成者はそれらをワークフローのコンテキストに配置して、ワークフローを合理化し、オペレーターのアクションの効率を高めることができます。
author: relnotes
ms.reviewer: v-brycho
ms.date: 06/23/2020
ms.assetid: 16091b82-e568-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: ced0b72de69f45f4be8659189c8fb9d1makamat
dynamics365pdf: true
ms.openlocfilehash: 605749e350a926b4dad4ed2422380c93bc1910be
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3522259"
---
# <a name="use-spatial-triggers-to-go-forward-or-backward-in-a-guide"></a><span data-ttu-id="56560-111">空間トリガーを使用してガイド内を前後に移動する</span><span class="sxs-lookup"><span data-stu-id="56560-111">Use spatial triggers to go forward or backward in a guide</span></span>
[!include[mixed-reality/dynamics365-guides banner](../includes/mixed-reality/dynamics365-guides.md)]

| <span data-ttu-id="56560-112">有効対象</span><span class="sxs-lookup"><span data-stu-id="56560-112">Enabled for</span></span>    |  <span data-ttu-id="56560-113">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="56560-113">Public preview</span></span> | <span data-ttu-id="56560-114">一般提供</span><span class="sxs-lookup"><span data-stu-id="56560-114">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="56560-115">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="56560-115">End users, automatically</span></span>|-| <span data-ttu-id="56560-116">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="56560-116">Aug 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="56560-117">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="56560-117">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="56560-118">この機能を使用すると、オペレーターは手順の間に指示カードの**次へ**または**戻る**ボタンを見つめる必要がなくなるため、ガイドをより迅速に完了できます。</span><span class="sxs-lookup"><span data-stu-id="56560-118">This feature enables operators to complete guides faster since they don’t have to gaze at the **Next** or **Back** buttons on the instruction card in between steps.</span></span> <span data-ttu-id="56560-119">オペレーターのタスクのフローに空間トリガーを配置すると、作成者は、注意をそらす (指示カードのボタンを見つめるなど) ことを避けつつ正しい動きを使用するようにオペレーターをトレーニングできます。</span><span class="sxs-lookup"><span data-stu-id="56560-119">Placing spatial triggers in the flow of operator tasks also enables authors to train operators to use correct movements while avoiding distractions (such as gazing at instruction card buttons).</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="56560-120">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="56560-120">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="56560-121">**空間トリガー**は、Dynamics 365 Guides に付属する 3D ツールキットで利用可能な新しいカテゴリの 3D モデルです。</span><span class="sxs-lookup"><span data-stu-id="56560-121">**Spatial triggers** is a new category of 3D models available in the 3D toolkit that comes with Dynamics 365 Guides.</span></span> <span data-ttu-id="56560-122">たとえば、作成者は、オペレーターがノブを回したりボタンを押したりするときに手を置くと想定される場所に**次へ**空間トリガーを配置できます。</span><span class="sxs-lookup"><span data-stu-id="56560-122">For example, authors can place a **Next** spatial trigger where they expect operators to place their hand when turning a knob or pressing a button.</span></span> <span data-ttu-id="56560-123">このトリガーにオペレーターの手が当たると、ガイドが次の手順に自動的に移動します。</span><span class="sxs-lookup"><span data-stu-id="56560-123">When an operator’s hand collides with the trigger, the guide automatically moves to the next step.</span></span> 
 
<span data-ttu-id="56560-124">オペレーターには見えない汎用の空間トリガーに加えて、作成者は、事前構築された**次へ**および**戻る**ホログラフィック ボタンを他のすべてのホログラムと同じように空間に配置できます。</span><span class="sxs-lookup"><span data-stu-id="56560-124">In addition to generic spatial triggers that are invisible to operators, authors can place prebuilt **Next** and **Back** holographic buttons in the world like any other hologram.</span></span>

> [!NOTE]
> <span data-ttu-id="56560-125">オペレーターは空間トリガーのオンとオフを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="56560-125">Operators can turn spatial triggers on or off.</span></span>
<!--feature detail end -->









