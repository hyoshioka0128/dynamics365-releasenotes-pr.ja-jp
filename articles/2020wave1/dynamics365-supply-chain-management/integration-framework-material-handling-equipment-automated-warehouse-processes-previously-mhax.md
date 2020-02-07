---
title: 自動倉庫プロセス用の材料取り扱い機器の統合フレームワーク (以前の MHAX)
description: 自動倉庫用の材料取り扱い機器の統合フレームワークにより、完全または部分的に自動化された倉庫を持つ顧客企業は、Dynamics 365 と統合して倉庫モジュールで生成された作業を処理できます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 12/13/2019
ms.assetid: 277b7ab1-d1e3-e911-a812-000d3a4f13c0
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 43063851936029c4074b8951b3f31e6530400b83
ms.sourcegitcommit: 9ede92eba84a02579fc8fc63e6a9673b034ce30c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/23/2020
ms.locfileid: "2976542"
---
# <a name="integration-framework-for-material-handling-equipment-for-automated-warehouse-processes-previously-mhax"></a><span data-ttu-id="95bb8-103">自動倉庫プロセス用の材料取り扱い機器の統合フレームワーク (以前の MHAX)</span><span class="sxs-lookup"><span data-stu-id="95bb8-103">Integration framework for material handling equipment for automated warehouse processes (previously MHAX)</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="95bb8-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="95bb8-104">Enabled for</span></span>    |  <span data-ttu-id="95bb8-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="95bb8-105">Public preview</span></span> | <span data-ttu-id="95bb8-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="95bb8-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="95bb8-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="95bb8-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="95bb8-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="95bb8-108">Feb 2020</span></span>| <span data-ttu-id="95bb8-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="95bb8-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="95bb8-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="95bb8-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="95bb8-111">材料取り扱い機器 (MHE) の統合フレームワークは、WMS によって作成された倉庫作業と、基本的な倉庫処理操作を実行できる材料取り扱い機器との間のインターフェイスとして機能します。</span><span class="sxs-lookup"><span data-stu-id="95bb8-111">The integration framework for material handling equipment (MHE) serves as an interface between the warehouse work created by the WMS and the material handling equipment that can perform basic warehouse handling operations.</span></span> <span data-ttu-id="95bb8-112">この機能は柔軟で、機器が Web サービスを介して統合できる限り、すべてのタイプの機器と統合できます。</span><span class="sxs-lookup"><span data-stu-id="95bb8-112">The functionality is flexible and integrates with all types of equipment, as long as the equipment can integrate through web services.</span></span>

<span data-ttu-id="95bb8-113">コンベア、縦型カルーセル、ハイベイ - ASRS (自動化ストレージおよび取り出しシステム)、梱包装置など、さまざまな MHE に対して行われた資本投資に統合できる WMS システムを顧客が持つことが不可欠です。</span><span class="sxs-lookup"><span data-stu-id="95bb8-113">It’s essential for customers to have a WMS system that can integrate to the capital investment made into a variety of MHE, such as conveyor, vertical carousel,  High bay - ASRS (Automated Storage and Retrieving Systems), and packing equipment.</span></span> <span data-ttu-id="95bb8-114">多くの顧客は、単純な材料取り扱い機器との統合を整理する追加のプロバイダーに投資することを避けたいと考えます。</span><span class="sxs-lookup"><span data-stu-id="95bb8-114">Many customers would prefer to avoid investing in an additional provider to organize the integration with simple material handling equipment.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="95bb8-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="95bb8-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="95bb8-116">ユーザーは、作業の作成、完了、キャンセルなどの倉庫イベントで、アウトバウンド サブスクリプションを設定できます。</span><span class="sxs-lookup"><span data-stu-id="95bb8-116">Users can set up outbound subscriptions on warehouse events such as work creation, completion, and cancellation.</span></span> <span data-ttu-id="95bb8-117">これらのイベントは、関連付けられたデータとともに、キューで追跡され、外部の機器から Web サービス経由でアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="95bb8-117">These events, along with associated data will be tracked in a queue, which external equipment can access by web service.</span></span> <span data-ttu-id="95bb8-118">各トランザクションに関連付けられたデータは、完全にユーザー構成可能です。</span><span class="sxs-lookup"><span data-stu-id="95bb8-118">The data associated with each transaction is completely user configurable.</span></span> <span data-ttu-id="95bb8-119">各キュー レコードを追加するために、最大 10 個のフィールドを指定できます。</span><span class="sxs-lookup"><span data-stu-id="95bb8-119">Up to 10 fields can be specified to accompany each queue record.</span></span> <span data-ttu-id="95bb8-120">各レコードのステータスは、ブロック済みから送信済みまで追跡されます。</span><span class="sxs-lookup"><span data-stu-id="95bb8-120">The status of each record will be tracked from blocked through sent.</span></span>

<span data-ttu-id="95bb8-121">同様に、インバウンド キューが存在し、外部機器は Web サービス経由でこれを設定できます。</span><span class="sxs-lookup"><span data-stu-id="95bb8-121">Similarly, an inbound queue exists that external equipment can populate via web service.</span></span> <span data-ttu-id="95bb8-122">インバウンド キュー レコードが消費されると、作業の完了やライセンス プレートの受取などの倉庫アクションがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="95bb8-122">When the inbound queue records are consumed, warehouse actions such as work completion and license plate receiving will be triggered.</span></span>  <span data-ttu-id="95bb8-123">作業は一度に 1 つずつ実行するか、またはピック/プットのペアを単一のトランザクションで実行することができます。</span><span class="sxs-lookup"><span data-stu-id="95bb8-123">Work can be executed one work line at a time, or a pick/put pair can be executed in a single transaction.</span></span> <span data-ttu-id="95bb8-124">未処理ピッキングと場所の上書きもサポートされています。</span><span class="sxs-lookup"><span data-stu-id="95bb8-124">Short pick and location override is also supported.</span></span>

<span data-ttu-id="95bb8-125">この新しい機能は、既存顧客の一部向けにプライベート プレビューでリリースされたライセンス ソリューションである MHAX と比較して、パフォーマンスとスケール、新しいデータ モデル、その他の必要な設計強化に対応するリファクタリングにも対応します。</span><span class="sxs-lookup"><span data-stu-id="95bb8-125">This new functionality will also address some refactoring to cater for performance and scale, new data model, and other needed design enhancements compared to the licensed solution MHAX that has been released as a private preview for selected existing customers.</span></span>

<!--feature detail end -->









