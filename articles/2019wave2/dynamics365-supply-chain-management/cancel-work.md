---
title: 作業のキャンセル
description: 作業のキャンセル機能を使用すると、管理ユーザーは現在進行中であるがブロックされている特定の倉庫作業をキャンセルできます。 運用上の理由でキャンセルが必要な作業については、ユーザーは作業フォームで利用可能な通常の作業キャンセル操作を引き続き使用する必要があります。
author: relnotes
ms.reviewer: josaw
ms.date: 10/16/2019
ms.assetid: 6062278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: omulvad
dynamics365pdf: true
ms.openlocfilehash: 8b322d48677de8f0756f11cd1f30139ee941f554
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660552"
---
# <a name="cancel-work"></a><span data-ttu-id="d97f7-104">作業のキャンセル</span><span class="sxs-lookup"><span data-stu-id="d97f7-104">Cancel work</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="d97f7-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="d97f7-105">Enabled for</span></span>    |  <span data-ttu-id="d97f7-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d97f7-106">Public preview</span></span> | <span data-ttu-id="d97f7-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="d97f7-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d97f7-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="d97f7-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="d97f7-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="d97f7-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="d97f7-110">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="d97f7-110">Jun 7, 2019</span></span>| <span data-ttu-id="d97f7-111">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="d97f7-111">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="d97f7-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d97f7-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d97f7-113">作業のキャンセル機能は、現在は管理権限を持つ会社のユーザーが使用できる、矛盾するデータを修正するために通常は IcM チケットを通じて要求される SQL 修正スクリプトに代わる、魅力的で安全な方法です。</span><span class="sxs-lookup"><span data-stu-id="d97f7-113">The cancel work feature is an attractive and secure alternative to SQL corrective scripts that are typically requested through IcM tickets to fix inconsistent data that can now be employed by the company’s users with admin rights.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d97f7-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d97f7-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d97f7-115">倉庫作業の強制キャンセルは、現在進行中ではあるがブロックされている (多くの場合はデータ破損のためですが、そうでない場合もあります) 特定の倉庫作業をユーザーがキャンセルできるようにする管理機能です。</span><span class="sxs-lookup"><span data-stu-id="d97f7-115">Warehouse Work Force Cancel is an admin facility available from the user interface that enables the user to cancel specific warehouse work that is currently in progress but is blocked (often, but not necessarily, due to data corruption).</span></span> 

<span data-ttu-id="d97f7-116">標準の**キャンセル** ボタン ([作業] ページから直接使用できるボタン) とは異なり、新しい作業のキャンセル機能には、最後に完了した作業明細のタイプが**プット**でなければならないという前提条件はありません。</span><span class="sxs-lookup"><span data-stu-id="d97f7-116">Unlike the standard **Cancel** button (the one available directly from the Work page), the new cancel work function does not have a precondition for the last completed work line to be of type **Put**.</span></span> <span data-ttu-id="d97f7-117">つまり、作業明細の品目数量がユーザー以外の場所にある必要はありません。</span><span class="sxs-lookup"><span data-stu-id="d97f7-117">In other words, it does not require item quantity on a work line to be on a non-user location.</span></span> 

<span data-ttu-id="d97f7-118">このジョブで取り消すことができるのは、タイプが**販売**、**移動の出庫**、**原材料ピッキング**、または**補充**の作業だけです。</span><span class="sxs-lookup"><span data-stu-id="d97f7-118">Only work of type **Sales**, **Transfer issue**, **Raw material picking**, or **Replenishment** can be canceled by this job.</span></span> <span data-ttu-id="d97f7-119">凍結された原材料のピッキング作業の場合、または通常の取消機能 (前述のとおり) で取り消すことができる作業の場合、キャンセルは実行されません。</span><span class="sxs-lookup"><span data-stu-id="d97f7-119">Cancellation will not be executed for frozen raw material picking work or work that can be canceled by a regular cancel function (as described earlier).</span></span> 

<span data-ttu-id="d97f7-120">作業のブロックを解除するため、残りの作業明細が取り消され、作業 ID に関連付けられている倉庫データが修正されます。</span><span class="sxs-lookup"><span data-stu-id="d97f7-120">To unblock the work, the system will cancel any remaining work lines and fix the warehouse data that is associated with the work ID.</span></span> <span data-ttu-id="d97f7-121">これにより、影響を受ける品目の数量を含む通常の倉庫処理作業を再開できます。</span><span class="sxs-lookup"><span data-stu-id="d97f7-121">This will allow any regular warehouse-handling operations that involve the impacted item quantity to resume.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="d97f7-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="d97f7-122">See also</span></span>

<span data-ttu-id="d97f7-123">[例外処理のために倉庫作業をキャンセル](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/cancel-warehouse-work) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="d97f7-123">[Cancel warehouse work for exception handling](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/cancel-warehouse-work) (docs)</span></span>
