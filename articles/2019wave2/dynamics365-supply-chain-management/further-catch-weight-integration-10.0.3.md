---
title: CW 統合の強化 10.0.3
description: CW 統合の強化 10.0.3
author: relnotes
ms.reviewer: kamaybac
ms.date: 12/10/2019
ms.assetid: a662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: aa6aac3bb30023337bc27997442b6c3e4168b88d
ms.sourcegitcommit: 50510b41ebc81897993a45f689651d9eda6c4247
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/20/2019
ms.locfileid: "2909876"
---
# <a name="further-catch-weight-integration-1003"></a><span data-ttu-id="7c143-103">CW 統合の強化 10.0.3</span><span class="sxs-lookup"><span data-stu-id="7c143-103">Further catch weight integration 10.0.3</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="7c143-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7c143-104">Enabled for</span></span>    |  <span data-ttu-id="7c143-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7c143-105">Public preview</span></span> | <span data-ttu-id="7c143-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7c143-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7c143-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="7c143-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="7c143-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="7c143-108">Feb 2020</span></span>| <span data-ttu-id="7c143-109">近日発表</span><span class="sxs-lookup"><span data-stu-id="7c143-109">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="7c143-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7c143-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7c143-111">ここでは、倉庫管理プロセス内の CW 製品処理に関連するさまざまな機能が強化されます。</span><span class="sxs-lookup"><span data-stu-id="7c143-111">This feature provides various enhancements on the catch weight product processing within warehouse management processes.</span></span> <span data-ttu-id="7c143-112">この機能では、Fullscope ISV ソリューションでサポートされる以下の追加統合作業が追加されます。</span><span class="sxs-lookup"><span data-stu-id="7c143-112">The feature adds the following additional integration work supported in the Fullscope ISV solution:</span></span> 

- <span data-ttu-id="7c143-113">重量キャプチャ方法のカウント: 倉庫アプリのカウント処理で、CW 単位ごとに重量をキャプチャできるようにします。</span><span class="sxs-lookup"><span data-stu-id="7c143-113">Counting weight capturing method: enables the warehouse app counting processing to capture the weight per catch weight unit.</span></span>
 
- <span data-ttu-id="7c143-114">倉庫間移動重量キャプチャ方法: 倉庫間移動プロセスの一環として、倉庫アプリで CW 単位ごとに重量をキャプチャできるようにします。</span><span class="sxs-lookup"><span data-stu-id="7c143-114">Warehouse transfer weight capturing method: enables the warehouse app to capture the weight per catch weight unit as part of the warehouse transfer process.</span></span>
 
- <span data-ttu-id="7c143-115">追加プロセスの重量調整の制限: 倉庫アプリの一環として CW 損益調整が行われる、重量キャプチャからのピッキング プロセスを制限できるようにします。</span><span class="sxs-lookup"><span data-stu-id="7c143-115">Restrict weight adjustments for additional processes: enables the possibility to restrict the picking processes from capturing weights resulting in catch weight profit/loss adjustments as part of warehouse app:</span></span>

  - <span data-ttu-id="7c143-116">倉庫間の移動</span><span class="sxs-lookup"><span data-stu-id="7c143-116">Warehouse transfer</span></span>

  - <span data-ttu-id="7c143-117">在庫状態の変更</span><span class="sxs-lookup"><span data-stu-id="7c143-117">Inventory status change</span></span>
 
- <span data-ttu-id="7c143-118">倉庫管理アプリ照会操作の一部としての重量情報: 倉庫アプリ照会プロセスで重量情報と単位を表示できるようにします。</span><span class="sxs-lookup"><span data-stu-id="7c143-118">Weight information as part of warehousing app inquire operations: enables the warehouse app inquire processes to display weight information and units.</span></span>

- <span data-ttu-id="7c143-119">CW 製品の在庫状態の変更 (定期): 非 CW タグ製品に対して在庫状態変更プロセスを有効にします。</span><span class="sxs-lookup"><span data-stu-id="7c143-119">Change inventory status (periodic) for catch weight products: enables the change inventory status process for non–catch weight tag products.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="7c143-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="7c143-120">See also</span></span>
<span data-ttu-id="7c143-121">[機能の探索](https://www.microsoft.com/videoplayer/embed/RE4jzx8) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="7c143-121">[Feature exploration](https://www.microsoft.com/videoplayer/embed/RE4jzx8) (video)</span></span>

<span data-ttu-id="7c143-122">[倉庫管理での CW 製品処理](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="7c143-122">[Catch weight product processing with warehouse management](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (docs)</span></span>
