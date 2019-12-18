---
title: 作業ラインの詳細
description: 新しい作業ライン機能は、すべての作業ヘッダーにわたる作業ラインの追加の概要を提供します。
author: relnotes
ms.reviewer: josaw
ms.date: 12/03/2019
ms.assetid: 7cfa0122-b415-ea11-a811-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 2d45a6ce8714cbfa3cf70084664bce7cf1baed0d
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2890446"
---
# <a name="work-line-details"></a><span data-ttu-id="33d24-103">作業ラインの詳細</span><span class="sxs-lookup"><span data-stu-id="33d24-103">Work line details</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="33d24-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="33d24-104">Enabled for</span></span>    |  <span data-ttu-id="33d24-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="33d24-105">Public preview</span></span> | <span data-ttu-id="33d24-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="33d24-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="33d24-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="33d24-107">End users, automatically</span></span>|<span data-ttu-id="33d24-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="33d24-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="33d24-109">2019 年 4 月 8 日</span><span class="sxs-lookup"><span data-stu-id="33d24-109">Apr 8, 2019</span></span>| <span data-ttu-id="33d24-110">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="33d24-110">Dec 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="33d24-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="33d24-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="33d24-112">この機能を使用すると、ユーザーは特定の会社のすべての作業ラインを表示するか、開いている作業ラインのみを表示するかを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="33d24-112">With this functionality, a user can switch between displaying all work lines or only open work lines for a specific company.</span></span> <span data-ttu-id="33d24-113">ページには、管理者が倉庫内のワークフローを正常に管理および調整するために必要な重要な詳細 (作業状態、品目番号、場所、作業数量、積荷 ID、出荷 ID など) がすべて表示されます。</span><span class="sxs-lookup"><span data-stu-id="33d24-113">The page shows all important details that a supervisor would require to successfully manage and adjust workflow within the warehouse, namely work status, item number, location, work quantity, load ID, shipment ID, and others.</span></span> <span data-ttu-id="33d24-114">ユーザーは、場所ディレクティブの設定を上書きして開いている作業ラインの場所を変更し、作業ラインをページから直接キャンセルしたり、数量を調整したりできます。</span><span class="sxs-lookup"><span data-stu-id="33d24-114">The user can change the location of any opened work line, overriding location directive setup,  to cancel any work line straight from the page or to adjust quantities.</span></span> <span data-ttu-id="33d24-115">ユーザーは、各作業ラインの背後にあるトランザクションをページから直接表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="33d24-115">The user can also view transactions behind each work line straight from the page.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="33d24-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="33d24-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="33d24-117">特定の会社のすべての作業ラインと開いている作業ラインだけの間で表示を切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="33d24-117">You can switch between showing all work lines or only open work lines for a specific company.</span></span> <span data-ttu-id="33d24-118">管理者が倉庫内のワークフローを正常に管理および調整するために必要な重要な詳細 (作業状態、品目番号、場所、作業数量、積荷 ID、出荷 ID など) をすべて表示できます。</span><span class="sxs-lookup"><span data-stu-id="33d24-118">You can view all important details that a supervisor would require to successfully manage and adjust workflow within the warehouse, namely work status, item number, location, work quantity, load ID, shipment ID, and others.</span></span> <span data-ttu-id="33d24-119">場所ディレクティブの設定を上書きして開いている作業ラインの場所を変更し、作業ラインをページから直接キャンセルしたり、数量を調整したりできます。</span><span class="sxs-lookup"><span data-stu-id="33d24-119">You can change the location of any opened work line, overriding location directive setup, to cancel any work line straight from the page or to adjust quantities.</span></span> <span data-ttu-id="33d24-120">各作業ラインの背後にあるトランザクションをページから直接表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="33d24-120">There is also the ability to view transactions behind each work line straight from the page.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="33d24-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="33d24-121">See also</span></span>
<span data-ttu-id="33d24-122">[機能の探索](https://www.microsoft.com/videoplayer/embed/RE4fcYN) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="33d24-122">[Feature exploration](https://www.microsoft.com/videoplayer/embed/RE4fcYN) (video)</span></span>


