---
title: QC 入庫ドック チェック
description: この機能を使用すると、入庫ドック エリアへの入庫時にその場で迅速な品質チェックを実行できます。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: b462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: c28d59f6ce3825981f04ba1df3d7b51242a41c69
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1855012"
---
# <a name="qc-inbound-dock-check"></a><span data-ttu-id="c13a9-103">QC 入庫ドック チェック</span><span class="sxs-lookup"><span data-stu-id="c13a9-103">QC inbound dock check</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="c13a9-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c13a9-104">Enabled for</span></span>    |  <span data-ttu-id="c13a9-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c13a9-105">Public preview</span></span> | <span data-ttu-id="c13a9-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c13a9-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="c13a9-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="c13a9-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c13a9-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="c13a9-108">August 2019</span></span>| <span data-ttu-id="c13a9-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="c13a9-109">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="c13a9-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c13a9-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c13a9-111">この機能を使用すると、入庫ドック エリアへの入庫時にその場で迅速な品質チェックを実行できます。</span><span class="sxs-lookup"><span data-stu-id="c13a9-111">With this functionality, you can perform rapid quality checks on the spot at the time of receiving to the inbound dock area.</span></span> <span data-ttu-id="c13a9-112">これらのスポット チェックは、梱包またはその他の容易に認識できる品目の一部が検査されるときに有益です。</span><span class="sxs-lookup"><span data-stu-id="c13a9-112">These spot checks are beneficial when packaging or any other easily recognizable part of the item is being inspected.</span></span> <span data-ttu-id="c13a9-113">在庫を所定の場所にストックする前に、明らかに不良として目に付くものを簡単に確認するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="c13a9-113">They serve as quick looks to see if anything is standing out as faulty before stocking the inventory to its location.</span></span> <span data-ttu-id="c13a9-114">この機能では、より高い柔軟性とより速い処理で、既存の品質チェック プロセスに代わる機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="c13a9-114">This function offers an alternative to existing quality-check processes, with more flexibility and faster processing.</span></span> <span data-ttu-id="c13a9-115">ここで品質指示を作成する必要はなく、代わりにライセンス プレートが最初の検査で却下された後で品質指示を作成します。</span><span class="sxs-lookup"><span data-stu-id="c13a9-115">It does not require any quality orders to be created but instead creates one after a license plate is rejected on initial inspection.</span></span> <span data-ttu-id="c13a9-116">入庫時に、作業者は所定の品質チェックを行う必要があり、スキャンした各ライセンス プレートを受け入れるか拒否するかを決定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c13a9-116">At the time of receiving, the worker is required to perform a desired quality check and must decide whether to accept or reject each license plate scanned.</span></span> <span data-ttu-id="c13a9-117">承認されたライセンス プレートは通常通り保管場所に誘導され、拒否されたライセンス プレートはさらなる検査のために品質チェックの場所に送られます。</span><span class="sxs-lookup"><span data-stu-id="c13a9-117">Accepted license plates will be guided to the storage location as normal, while rejected license plates will be diverted to a quality check location for further inspection.</span></span> <span data-ttu-id="c13a9-118">既存のプット アウェイ作業は取り消され、新しい "品質チェックでの品質" 作業指示書が作成され、ユーザーは自動的にプット ステップを続行します。</span><span class="sxs-lookup"><span data-stu-id="c13a9-118">Existing put-away work will be cancelled, a new “Quality In Quality Check” work order will be created, and the user will automatically continue with the put step.</span></span> <span data-ttu-id="c13a9-119">このプロセスを自動化し、スキャンしたすべてのライセンス プレートを直ちに品質チェックの場所に送ることもできます。</span><span class="sxs-lookup"><span data-stu-id="c13a9-119">This process can also be automated to divert all scanned license plates to the quality check location immediately.</span></span>
<!--feature detail end -->











