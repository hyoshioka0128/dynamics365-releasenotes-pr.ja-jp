---
title: 入庫品質チェック
description: この機能を使用すると、入庫ドック エリアへの入庫時にその場で迅速な品質チェックを実行できます。
author: relnotes
ms.reviewer: josaw
ms.date: 12/02/2019
ms.assetid: b462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: a0591ea1e2b15a5efef377fb00e31c75f1e51b16
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889675"
---
# <a name="inbound-quality-check"></a><span data-ttu-id="4dd82-103">入庫品質チェック</span><span class="sxs-lookup"><span data-stu-id="4dd82-103">Inbound quality check</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="4dd82-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="4dd82-104">Enabled for</span></span>    |  <span data-ttu-id="4dd82-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="4dd82-105">Public preview</span></span> | <span data-ttu-id="4dd82-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="4dd82-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="4dd82-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="4dd82-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="4dd82-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="4dd82-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="4dd82-109">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="4dd82-109">Aug 2, 2019</span></span>| <span data-ttu-id="4dd82-110">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="4dd82-110">Jan 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="4dd82-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="4dd82-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="4dd82-112">この機能を使用すると、入庫ドック エリアへの入庫時にその場で迅速な品質チェックを実行できます。</span><span class="sxs-lookup"><span data-stu-id="4dd82-112">With this functionality, you can perform rapid quality checks on the spot at the time of receiving to the inbound dock area.</span></span> <span data-ttu-id="4dd82-113">これらのスポット チェックは、梱包またはその他の容易に認識できる品目の一部が検査されるときに有益です。</span><span class="sxs-lookup"><span data-stu-id="4dd82-113">These spot checks are beneficial when packaging or any other easily recognizable part of the item is being inspected.</span></span> <span data-ttu-id="4dd82-114">在庫を所定の場所にストックする前に、明らかに不良として目に付くものを簡単に確認するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="4dd82-114">They serve as quick looks to see if anything is standing out as faulty before stocking the inventory to its location.</span></span> 

<span data-ttu-id="4dd82-115">この機能では、より高い柔軟性とより速い処理で、既存の品質チェック プロセスに代わる機能が提供されます。</span><span class="sxs-lookup"><span data-stu-id="4dd82-115">This function offers an alternative to existing quality-check processes, with more flexibility and faster processing.</span></span> <span data-ttu-id="4dd82-116">ここで品質指示を作成する必要はなく、代わりにライセンス プレートが最初の検査で却下された後で品質指示を作成します。</span><span class="sxs-lookup"><span data-stu-id="4dd82-116">It does not require any quality orders to be created but instead creates one after a license plate is rejected on initial inspection.</span></span> <span data-ttu-id="4dd82-117">入庫時に、作業者は所定の品質チェックを行う必要があり、スキャンした各ライセンス プレートを受け入れるか拒否するかを決定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4dd82-117">At the time of receiving, the worker is required to perform a desired quality check and must decide whether to accept or reject each license plate scanned.</span></span> <span data-ttu-id="4dd82-118">承認されたライセンス プレートは通常通り保管場所に誘導され、却下されたライセンス プレートは追加検査のために品質チェックに送られます。</span><span class="sxs-lookup"><span data-stu-id="4dd82-118">Accepted license plates will be guided to the storage location as normal, while rejected license plates will be diverted to a quality check location for further inspection.</span></span> 

<span data-ttu-id="4dd82-119">既存のプット アウェイ作業は取り消され、新しい "品質チェックでの品質" 作業指示書が作成され、ユーザーは自動的にプット ステップを続行します。</span><span class="sxs-lookup"><span data-stu-id="4dd82-119">Existing put-away work will be canceled, a new “Quality In Quality Check” work order will be created, and the user will automatically continue with the put step.</span></span> <span data-ttu-id="4dd82-120">このプロセスを自動化し、スキャンしたすべてのライセンス プレートを直ちに品質チェックに送ることもできます。</span><span class="sxs-lookup"><span data-stu-id="4dd82-120">This process can also be automated to divert all scanned license plates to the quality check location immediately.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="4dd82-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="4dd82-121">See also</span></span>
<span data-ttu-id="4dd82-122">[機能の探索](https://www.microsoft.com/en-us/videoplayer/embed/RE4ffzr) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="4dd82-122">[Feature exploration](https://www.microsoft.com/en-us/videoplayer/embed/RE4ffzr) (video)</span></span>
