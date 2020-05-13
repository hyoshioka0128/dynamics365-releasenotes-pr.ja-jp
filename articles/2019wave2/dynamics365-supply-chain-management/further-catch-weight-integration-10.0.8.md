---
title: CW 統合の強化 10.0.8
description: CW 統合の強化 10.0.8
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/15/2020
ms.assetid: c999ac52-3405-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: d4dc747260dc8272372beb58623e6522d205af86
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320041"
---
# <a name="further-catch-weight-integration-1008"></a><span data-ttu-id="209c2-103">CW 統合の強化 10.0.8</span><span class="sxs-lookup"><span data-stu-id="209c2-103">Further catch weight integration 10.0.8</span></span>


| <span data-ttu-id="209c2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="209c2-104">Enabled for</span></span>    |  <span data-ttu-id="209c2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="209c2-105">Public preview</span></span> | <span data-ttu-id="209c2-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="209c2-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="209c2-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="209c2-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="209c2-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="209c2-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="209c2-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="209c2-109">Feb 3, 2020</span></span>| <span data-ttu-id="209c2-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="209c2-110">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="209c2-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="209c2-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="209c2-112">このリリースでは、倉庫管理の CW 処理機能にいくつかの拡張機能が追加されています。</span><span class="sxs-lookup"><span data-stu-id="209c2-112">This release adds several enhancements to the catch weight processing features for warehouse management.</span></span> <span data-ttu-id="209c2-113">独立系ソフトウェア ベンダー (ISV) である Fullscope によって提供されるシナリオとの統合に対する追加のサポートを提供し、BHS ISV ソリューションに基づいて構築されるいくつかのその他のシナリオのサポートを追加します。</span><span class="sxs-lookup"><span data-stu-id="209c2-113">It provides additional support for integrating with scenarios provided by the independent software vendor (ISV) Fullscope, and adds support for several additional scenarios that build on the BHS ISV solution.</span></span> <span data-ttu-id="209c2-114">機能強化は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="209c2-114">Enhancements include:</span></span>

- <span data-ttu-id="209c2-115">機能管理サポート (非推奨になったメソッドを検証する機能を含む)</span><span class="sxs-lookup"><span data-stu-id="209c2-115">Feature management support, including the ability to validate obsolete methods</span></span>
- <span data-ttu-id="209c2-116">以下を含む、すべての保管分析コードを追跡しながら CW タグを処理するための追加機能:</span><span class="sxs-lookup"><span data-stu-id="209c2-116">Additional capabilities for processing catch weight tags while tracking all storage dimensions, including:</span></span>

    - <span data-ttu-id="209c2-117">倉庫アプリ移動作業 (状態の変更あり)</span><span class="sxs-lookup"><span data-stu-id="209c2-117">Warehouse app movements with status change</span></span>
    - <span data-ttu-id="209c2-118">テンプレートによる倉庫アプリ移動作業 (状態の変更あり)</span><span class="sxs-lookup"><span data-stu-id="209c2-118">Warehouse app movement by templates with status change</span></span>
    - <span data-ttu-id="209c2-119">倉庫間の移動 (状態の変更あり)</span><span class="sxs-lookup"><span data-stu-id="209c2-119">Warehouse transfer with status change</span></span>
    - <span data-ttu-id="209c2-120">倉庫アプリの在庫状態の変更</span><span class="sxs-lookup"><span data-stu-id="209c2-120">Warehouse app inventory status change</span></span>
    - <span data-ttu-id="209c2-121">倉庫アプリの返品販売注文プロセス</span><span class="sxs-lookup"><span data-stu-id="209c2-121">Warehouse app return sales order process</span></span>
    - <span data-ttu-id="209c2-122">手動パック フォーム処理</span><span class="sxs-lookup"><span data-stu-id="209c2-122">Manual pack form processing</span></span>
    - <span data-ttu-id="209c2-123">ピッキングされた数量の削減処理</span><span class="sxs-lookup"><span data-stu-id="209c2-123">Reduced picked quantity processing</span></span>
    - <span data-ttu-id="209c2-124">コンテナーの再オープン処理</span><span class="sxs-lookup"><span data-stu-id="209c2-124">Container reopening process</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="209c2-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="209c2-125">See also</span></span>

<!--docs start-->
<span data-ttu-id="209c2-126">[倉庫管理での CW 製品処理](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="209c2-126">[Catch weight product processing with warehouse management](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (docs)</span></span>
<!--docs end-->
