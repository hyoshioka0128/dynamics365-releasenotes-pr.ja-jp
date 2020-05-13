---
title: 材料取り扱い/倉庫自動化
description: 材料取り扱い機能は、倉庫自動化および材料取り扱い機器とのインターフェイスのためのフレームワークです。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/07/2020
ms.assetid: 9a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 4bdf6f3dab912d27d87dfb0419c09fecdac7b7b8
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320008"
---
# <a name="material-handlingwarehouse-automation"></a><span data-ttu-id="0df9f-103">材料取り扱い/倉庫自動化</span><span class="sxs-lookup"><span data-stu-id="0df9f-103">Material handling/warehouse automation</span></span>


| <span data-ttu-id="0df9f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0df9f-104">Enabled for</span></span>    |  <span data-ttu-id="0df9f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0df9f-105">Public preview</span></span> | <span data-ttu-id="0df9f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="0df9f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="0df9f-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="0df9f-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="0df9f-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0df9f-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0df9f-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="0df9f-109">Feb 3, 2020</span></span>| <span data-ttu-id="0df9f-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="0df9f-110">To be announced</span></span>|






## <a name="feature-details"></a><span data-ttu-id="0df9f-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0df9f-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0df9f-112">材料取り扱い機能は、倉庫自動化および材料取り扱い機器とのインターフェイスのためのフレームワークです。</span><span class="sxs-lookup"><span data-stu-id="0df9f-112">The material handling feature is a framework for interfacing with warehouse automation and material handling equipment.</span></span> <span data-ttu-id="0df9f-113">ユーザーは、作業の作成、完了、キャンセルなどの倉庫イベントで、アウトバウンド サブスクリプションを設定できます。</span><span class="sxs-lookup"><span data-stu-id="0df9f-113">Users can set up outbound subscriptions on warehouse events, such as work creation, completion, and cancellation.</span></span> <span data-ttu-id="0df9f-114">これらのイベントは、関連付けられたデータとともに、キューで追跡され、外部の機器から Web サービス経由でアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="0df9f-114">These events, along with associated data, will be tracked in a queue, which can be accessed via a web service by external equipment.</span></span> <span data-ttu-id="0df9f-115">各トランザクションに関連付けられたデータは、完全にユーザー構成可能です。</span><span class="sxs-lookup"><span data-stu-id="0df9f-115">The data associated with each transaction is completely user configurable.</span></span> <span data-ttu-id="0df9f-116">各キュー レコードを追加するために、最大 10 個のフィールドを指定できます。</span><span class="sxs-lookup"><span data-stu-id="0df9f-116">Up to 10 fields can be specified to accompany each queue record.</span></span> <span data-ttu-id="0df9f-117">各レコードのステータスは、ブロック済みから送信済みまで追跡されます。</span><span class="sxs-lookup"><span data-stu-id="0df9f-117">The status of each record will be tracked from blocked through sent.</span></span> <span data-ttu-id="0df9f-118">同様に、インバウンド キューが存在し、外部機器は Web サービス経由でこれを設定できます。</span><span class="sxs-lookup"><span data-stu-id="0df9f-118">Similarly, an inbound queue exists, which external equipment can populate via a web service.</span></span> <span data-ttu-id="0df9f-119">インバウンド キュー レコードが消費されると、作業の完了やライセンス プレートの受取などの倉庫アクションがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="0df9f-119">When the inbound queue records are consumed, warehouse actions will be triggered, such as work completion and license plate receiving.</span></span> <span data-ttu-id="0df9f-120">作業は一度に 1 つずつ実行するか、またはピック/プットのペアを単一のトランザクションで実行することができます。</span><span class="sxs-lookup"><span data-stu-id="0df9f-120">Work can be executed one work line at a time, or a pick/put pair can be executed in a single transaction.</span></span> <span data-ttu-id="0df9f-121">未処理ピッキングと場所の上書きもサポートされています。</span><span class="sxs-lookup"><span data-stu-id="0df9f-121">Short pick and location override are also supported.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="0df9f-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="0df9f-122">See also</span></span>

<!--docs start-->
<span data-ttu-id="0df9f-123">[倉庫管理の概要](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="0df9f-123">[Warehouse management overview](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (docs)</span></span>
<!--docs end-->
