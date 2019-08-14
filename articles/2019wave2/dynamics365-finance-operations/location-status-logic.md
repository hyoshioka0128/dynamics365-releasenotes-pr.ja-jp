---
title: 場所ステータス ロジック
description: この機能では、より柔軟に場所ステータスを処理および維持し、クエリでフィルターを使用できるよう、場所テーブルにいくつかの新しいフィールドが導入されます。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: 7062278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 62e6b209d02031492fbf76e64f8de3435e5a9b1b
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1855177"
---
# <a name="location-status-logic"></a><span data-ttu-id="b558d-103">場所ステータス ロジック</span><span class="sxs-lookup"><span data-stu-id="b558d-103">Location status logic</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="b558d-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b558d-104">Enabled for</span></span>    |  <span data-ttu-id="b558d-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b558d-105">Public preview</span></span> | <span data-ttu-id="b558d-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b558d-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="b558d-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="b558d-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="b558d-108">2019 年 8 月</span><span class="sxs-lookup"><span data-stu-id="b558d-108">August 2019</span></span>| <span data-ttu-id="b558d-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="b558d-109">October 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="b558d-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b558d-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b558d-111">この機能では、より柔軟に場所を処理および維持できるよう、場所テーブルにいくつかの新しいフィールドが導入されます。</span><span class="sxs-lookup"><span data-stu-id="b558d-111">This functionality introduces several new fields on the locations table for more flexibility in working with and maintaining locations.</span></span> <span data-ttu-id="b558d-112">倉庫フロー管理を改善するため、場所ステータス (空、保管、ピッキング、凍結) を場所指示クエリに含めることができます。</span><span class="sxs-lookup"><span data-stu-id="b558d-112">Location statuses (empty, storage, picking, or frozen) can be included in the location directives query for better warehouse flow control.</span></span> <span data-ttu-id="b558d-113">ブロックの原因を設定し、後で任意の場所に割り当てて、そのような場所に対する入庫または出庫のトランザクションをブロックすることができます。</span><span class="sxs-lookup"><span data-stu-id="b558d-113">Blocking causes can be set up and can later be assigned to any location to either block inbound or outbound transactions against such a location.</span></span> <span data-ttu-id="b558d-114">場所ブロックでは予約の場所は除外されません。</span><span class="sxs-lookup"><span data-stu-id="b558d-114">Location blocking does not exclude locations for reservations.</span></span> <span data-ttu-id="b558d-115">一時的な運用上のブロックのみを意味します。</span><span class="sxs-lookup"><span data-stu-id="b558d-115">It is meant only as a temporary operational blocking.</span></span>
<!--feature detail end -->











