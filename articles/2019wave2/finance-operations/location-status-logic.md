---
title: 場所ステータス ロジック
description: この機能では、より柔軟に場所ステータスを処理および維持し、クエリでフィルターを使用できるよう、場所テーブルにいくつかの新しいフィールドが導入されます。
author: relnotes
ms.reviewer: josaw
ms.date: 08/02/2019
ms.assetid: 7062278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: ad4cc121748a445c63b327fed7dca3e4ed9de4b3
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143056"
---
# <a name="location-status-logic"></a><span data-ttu-id="75c09-103">場所ステータス ロジック</span><span class="sxs-lookup"><span data-stu-id="75c09-103">Location status logic</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="75c09-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="75c09-104">Enabled for</span></span>    |  <span data-ttu-id="75c09-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="75c09-105">Public preview</span></span> | <span data-ttu-id="75c09-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="75c09-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="75c09-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="75c09-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="75c09-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="75c09-108">Aug 2019</span></span>| <span data-ttu-id="75c09-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="75c09-109">Oct 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="75c09-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="75c09-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="75c09-111">この機能では、より柔軟に場所を処理および維持できるよう、場所テーブルにいくつかの新しいフィールドが導入されます。</span><span class="sxs-lookup"><span data-stu-id="75c09-111">This functionality introduces several new fields on the locations table for more flexibility in working with and maintaining locations.</span></span> <span data-ttu-id="75c09-112">倉庫フロー管理を改善するため、場所ステータス (空、保管、ピッキング、凍結) を場所指示クエリに含めることができます。</span><span class="sxs-lookup"><span data-stu-id="75c09-112">Location statuses (empty, storage, picking, or frozen) can be included in the location directives query for better warehouse flow control.</span></span> <span data-ttu-id="75c09-113">ブロックの原因を設定し、後で任意の場所に割り当てて、そのような場所に対する入庫または出庫のトランザクションをブロックすることができます。</span><span class="sxs-lookup"><span data-stu-id="75c09-113">Blocking causes can be set up and can later be assigned to any location to either block inbound or outbound transactions against such a location.</span></span> <span data-ttu-id="75c09-114">場所ブロックでは予約の場所は除外されません。</span><span class="sxs-lookup"><span data-stu-id="75c09-114">Location blocking does not exclude locations for reservations.</span></span> <span data-ttu-id="75c09-115">一時的な運用上のブロックのみを意味します。</span><span class="sxs-lookup"><span data-stu-id="75c09-115">It is meant only as a temporary operational blocking.</span></span>
<!--feature detail end -->











