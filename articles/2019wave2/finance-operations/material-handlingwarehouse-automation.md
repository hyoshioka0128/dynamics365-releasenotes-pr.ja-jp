---
title: 材料取り扱い/倉庫自動化
description: 材料取り扱い機能は、倉庫自動化および材料取り扱い機器とのインターフェイスのためのフレームワークです。
author: relnotes
ms.reviewer: josaw
ms.date: 09/16/2019
ms.assetid: 9a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 816935c2375fbc8ce930440b6eb1458f80d6fe82
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143034"
---
# <a name="material-handlingwarehouse-automation"></a><span data-ttu-id="ae5ce-103">材料取り扱い/倉庫自動化</span><span class="sxs-lookup"><span data-stu-id="ae5ce-103">Material handling/warehouse automation</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="ae5ce-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ae5ce-104">Enabled for</span></span>    |  <span data-ttu-id="ae5ce-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ae5ce-105">Public preview</span></span> | <span data-ttu-id="ae5ce-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ae5ce-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ae5ce-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="ae5ce-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="ae5ce-108">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="ae5ce-108">Jan 2020</span></span>| <span data-ttu-id="ae5ce-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="ae5ce-109">Feb 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="ae5ce-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ae5ce-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ae5ce-111">材料取り扱い機能は、倉庫自動化および材料取り扱い機器とのインターフェイスのためのフレームワークです。</span><span class="sxs-lookup"><span data-stu-id="ae5ce-111">The material handling feature is a framework for interfacing with warehouse automation and material handling equipment.</span></span> <span data-ttu-id="ae5ce-112">ユーザーは、作業の作成、完了、キャンセルなどの倉庫イベントで、アウトバウンド サブスクリプションを設定できます。</span><span class="sxs-lookup"><span data-stu-id="ae5ce-112">Users can set up outbound subscriptions on warehouse events, such as work creation, completion, and cancellation.</span></span> <span data-ttu-id="ae5ce-113">これらのイベントは、関連付けられたデータとともに、キューで追跡され、外部の機器から Web サービス経由でアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="ae5ce-113">These events, along with associated data, will be tracked in a queue, which can be accessed via a web service by external equipment.</span></span> <span data-ttu-id="ae5ce-114">各トランザクションに関連付けられたデータは、完全にユーザー構成可能です。</span><span class="sxs-lookup"><span data-stu-id="ae5ce-114">The data associated with each transaction is completely user configurable.</span></span> <span data-ttu-id="ae5ce-115">各キュー レコードを追加するために、最大 10 個のフィールドを指定できます。</span><span class="sxs-lookup"><span data-stu-id="ae5ce-115">Up to 10 fields can be specified to accompany each queue record.</span></span> <span data-ttu-id="ae5ce-116">各レコードのステータスは、ブロック済みから送信済みまで追跡されます。</span><span class="sxs-lookup"><span data-stu-id="ae5ce-116">The status of each record will be tracked from blocked through sent.</span></span> <span data-ttu-id="ae5ce-117">同様に、インバウンド キューが存在し、外部機器は Web サービス経由でこれを設定できます。</span><span class="sxs-lookup"><span data-stu-id="ae5ce-117">Similarly, an inbound queue exists, which external equipment can populate via a web service.</span></span> <span data-ttu-id="ae5ce-118">インバウンド キュー レコードが消費されると、作業の完了やライセンス プレートの受取などの倉庫アクションがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="ae5ce-118">When the inbound queue records are consumed, warehouse actions will be triggered, such as work completion and license plate receiving.</span></span> <span data-ttu-id="ae5ce-119">作業は一度に 1 つずつ実行するか、またはピック/プットのペアを単一のトランザクションで実行することができます。</span><span class="sxs-lookup"><span data-stu-id="ae5ce-119">Work can be executed one work line at a time, or a pick/put pair can be executed in a single transaction.</span></span> <span data-ttu-id="ae5ce-120">未処理ピッキングと場所の上書きもサポートされています。</span><span class="sxs-lookup"><span data-stu-id="ae5ce-120">Short pick and location override are also supported.</span></span>
<!--feature detail end -->











