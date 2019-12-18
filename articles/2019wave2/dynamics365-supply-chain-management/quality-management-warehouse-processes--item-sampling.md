---
title: 倉庫プロセスの品質管理 - 品目サンプリング
description: この機能は、モバイル デバイスを使って品質チェックの場所の間で在庫を移動する作業指示書を作成する機能を導入することによって、既存の品質指示機能を拡張します。
author: relnotes
ms.reviewer: josaw
ms.date: 12/02/2019
ms.assetid: df491424-14cb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 82d592cc7626dc6665c5ecc70a75d48cf4bf42d7
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2889632"
---
# <a name="quality-management-for-warehouse-processes--item-sampling"></a><span data-ttu-id="9b19c-103">倉庫プロセスの品質管理 - 品目サンプリング</span><span class="sxs-lookup"><span data-stu-id="9b19c-103">Quality management for warehouse processes – item sampling</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="9b19c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9b19c-104">Enabled for</span></span>    |  <span data-ttu-id="9b19c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9b19c-105">Public preview</span></span> | <span data-ttu-id="9b19c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="9b19c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="9b19c-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="9b19c-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="9b19c-108">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="9b19c-108">Jan 2020</span></span>| <span data-ttu-id="9b19c-109">近日発表</span><span class="sxs-lookup"><span data-stu-id="9b19c-109">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="9b19c-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9b19c-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9b19c-111">入庫在庫を受け取ったら、品質の関連付けを使用して品質指示を作成できます。</span><span class="sxs-lookup"><span data-stu-id="9b19c-111">Upon the receipt of inbound inventory, a quality order can be created using quality associations.</span></span> <span data-ttu-id="9b19c-112">注文は、既存の品質管理プロセスを使用して処理されます。</span><span class="sxs-lookup"><span data-stu-id="9b19c-112">The order is processed using existing quality management processes.</span></span> 

<span data-ttu-id="9b19c-113">この機能は、倉庫への入庫在庫のセット サンプルを品質目的で調べる必要があるときに使用されます。</span><span class="sxs-lookup"><span data-stu-id="9b19c-113">This functionality is used when a set sample of inventory coming into the warehouse needs to be examined for quality purposes.</span></span> <span data-ttu-id="9b19c-114">ビジネス標準に従う必要のある新しい仕入先や、または過去に問題が発生して、より詳細な調査を必要とする仕入先のような場合です。</span><span class="sxs-lookup"><span data-stu-id="9b19c-114">It could be a new vendor where they need to be kept to business standards, or a vendor who has had issues in the past and needs closer examination.</span></span> 

<span data-ttu-id="9b19c-115">注文の作成方法は、品質関連と品目サンプリングの設定方法の基準によって異なります。</span><span class="sxs-lookup"><span data-stu-id="9b19c-115">The way orders are created depends on the criteria in how the quality associations and item sampling are set up.</span></span> <span data-ttu-id="9b19c-116">それらは、積荷ごと、出荷ごと、注文ごとのいずれかです。</span><span class="sxs-lookup"><span data-stu-id="9b19c-116">They can either be per load, shipment, or order.</span></span> <span data-ttu-id="9b19c-117">ここでは、検査するライセンス プレートの数に加えて、完全なライセンス プレートとその一部のどちらを検査するのかと、各品目 ID を個別に検査するかどうかも決定されます。</span><span class="sxs-lookup"><span data-stu-id="9b19c-117">The number of  license plates to be examined is also determined here, as well as whether the complete license plate should be examined or a part of it and whether each item ID should be examined separately or not.</span></span>

<span data-ttu-id="9b19c-118">在庫を受け取ったら、品質の関連付けを使用して品質指示を作成できます。</span><span class="sxs-lookup"><span data-stu-id="9b19c-118">Upon the receipt of inventory, a quality order can be created using quality associations.</span></span> <span data-ttu-id="9b19c-119">この方法で品質指示が作成された場合、品質サンプリング作業トランザクション タイプの品質を使用して、オーダーの在庫を移動する作業が作成されます。</span><span class="sxs-lookup"><span data-stu-id="9b19c-119">If a quality order is created in this manner, the work to move the inventory for the order is created using the quality in quality sampling work trans type.</span></span> <span data-ttu-id="9b19c-120">必要な在庫を入庫ドック (または開始場所) から品質場所に移動する作業が作成されます。</span><span class="sxs-lookup"><span data-stu-id="9b19c-120">Work is created to move the needed inventory from the receive dock (or start location) to the quality location.</span></span> <span data-ttu-id="9b19c-121">在庫は、品質管理によって品質指示が処理されて完了するまでその場所に残ります。</span><span class="sxs-lookup"><span data-stu-id="9b19c-121">The inventory will stay in the location until the quality order is processed and completed via quality management.</span></span> <span data-ttu-id="9b19c-122">品質指示が完了すると、新しい作業指示書を作成して在庫を保管場所に移動できます。</span><span class="sxs-lookup"><span data-stu-id="9b19c-122">Once the quality order is complete, a new work order can be created to move the inventory to the storage location.</span></span>
<!--feature detail end -->









