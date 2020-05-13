---
title: CW 統合の強化 10.0.2
description: CW 統合の強化 10.0.2
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/07/2020
ms.assetid: 9462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: 81a0c122b674cec1a8fb0c0a2b3708c0b1a4e321
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320140"
---
# <a name="further-catch-weight-integration-1002"></a><span data-ttu-id="fd7e8-103">CW 統合の強化 10.0.2</span><span class="sxs-lookup"><span data-stu-id="fd7e8-103">Further catch weight integration 10.0.2</span></span>


| <span data-ttu-id="fd7e8-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="fd7e8-104">Enabled for</span></span>    |  <span data-ttu-id="fd7e8-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="fd7e8-105">Public preview</span></span> | <span data-ttu-id="fd7e8-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="fd7e8-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="fd7e8-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="fd7e8-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="fd7e8-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="fd7e8-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="fd7e8-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="fd7e8-109">Feb 3, 2020</span></span>| <span data-ttu-id="fd7e8-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="fd7e8-110">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="fd7e8-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="fd7e8-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="fd7e8-112">この機能により、倉庫管理プロセス内の CW 製品処理に関連するさまざまな機能が強化されます。</span><span class="sxs-lookup"><span data-stu-id="fd7e8-112">This feature provides various enhancements on catch weight product processing within warehouse management processes.</span></span> <span data-ttu-id="fd7e8-113">Fullscope ISV ソリューションでサポートされる以下の追加統合作業を提供しています。</span><span class="sxs-lookup"><span data-stu-id="fd7e8-113">We are providing the following additional integration work supported in the Fullscope ISV solution:</span></span>

- <span data-ttu-id="fd7e8-114">混合ライセンス プレートの受取 (販売注文の転送と返品): 販売注文の転送と返品に混合ライセンス プレートの受取を使用するために CW 製品の倉庫アプリ処理を有効にします。</span><span class="sxs-lookup"><span data-stu-id="fd7e8-114">Mixed license plate receiving (transfer and return sales orders): enables warehouse app processing for catch weight products to use mixed license plate receiving for transfer and return sales orders.</span></span>
 
- <span data-ttu-id="fd7e8-115">重量調整の制限: 以下の倉庫アプリ処理に対して CW 損益調整が行われる、重量キャプチャからの倉庫管理ピッキング プロセスを制限できるようにします。</span><span class="sxs-lookup"><span data-stu-id="fd7e8-115">Restrict weight adjustments: enables the possibility of restricting the warehouse management picking processes from capturing weights resulting in catch weight profit/loss adjustments for the following warehouse app processes:</span></span>

  - <span data-ttu-id="fd7e8-116">販売注文</span><span class="sxs-lookup"><span data-stu-id="fd7e8-116">Sales order</span></span>

  - <span data-ttu-id="fd7e8-117">移動オーダー</span><span class="sxs-lookup"><span data-stu-id="fd7e8-117">Transfer order</span></span>

  - <span data-ttu-id="fd7e8-118">製造オーダー</span><span class="sxs-lookup"><span data-stu-id="fd7e8-118">Production order</span></span>

  - <span data-ttu-id="fd7e8-119">振替</span><span class="sxs-lookup"><span data-stu-id="fd7e8-119">Movement</span></span>

  - <span data-ttu-id="fd7e8-120">テンプレートによる移動</span><span class="sxs-lookup"><span data-stu-id="fd7e8-120">Movement by templates</span></span>

  - <span data-ttu-id="fd7e8-121">調整外</span><span class="sxs-lookup"><span data-stu-id="fd7e8-121">Adjustment out</span></span>
 
- <span data-ttu-id="fd7e8-122">移動中の重量キャプチャ: 内部在庫移動中に重量をキャプチャできるようにします。</span><span class="sxs-lookup"><span data-stu-id="fd7e8-122">Weight capturing during movements: enables the possibility of capturing weight during internal inventory movements.</span></span>
 
- <span data-ttu-id="fd7e8-123">CW タグのメンテナンスの強化: CW タグ フォームで直接アクションを作成および修正できます。</span><span class="sxs-lookup"><span data-stu-id="fd7e8-123">Catch weight tag maintenance enhancements: enables creation and correction actions directly in the catch weight tag form.</span></span>
     
- <span data-ttu-id="fd7e8-124">CW タグに対するデータ エンティティのサポート: パブリック OData 対応のデータ エンティティを有効にして、CW タグの作成と維持をサポートします。</span><span class="sxs-lookup"><span data-stu-id="fd7e8-124">Data entity support for catch weight tags: enables a public OData-enabled data entity, supporting creation and maintenance of the catch weight tags.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="fd7e8-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="fd7e8-125">See also</span></span>
<span data-ttu-id="fd7e8-126">[機能の探索](https://www.microsoft.com/videoplayer/embed/RE4jzx8) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="fd7e8-126">[Feature exploration](https://www.microsoft.com/videoplayer/embed/RE4jzx8) (video)</span></span>

<!--docs start-->
<span data-ttu-id="fd7e8-127">[倉庫管理での CW 製品処理](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="fd7e8-127">[Catch weight product processing with warehouse management](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (docs)</span></span>
<!--docs end-->
