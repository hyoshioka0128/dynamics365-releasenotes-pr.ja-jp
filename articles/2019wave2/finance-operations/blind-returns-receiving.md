---
title: ブラインド返品受取
description: この機能は、注文を事前に調整しなくても、元の返品注文には含まれていなかった品目を作業者が受け取れるようにすることで、標準の返品注文処理を拡張します。
author: relnotes
ms.reviewer: josaw
ms.date: 08/30/2019
ms.assetid: b662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 2d5420a2deb377c72a403bcb31e2725e87fca31e
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141648"
---
# <a name="blind-returns-receiving"></a><span data-ttu-id="680cb-103">ブラインド返品受取</span><span class="sxs-lookup"><span data-stu-id="680cb-103">Blind returns receiving</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="680cb-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="680cb-104">Enabled for</span></span>    |  <span data-ttu-id="680cb-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="680cb-105">Public preview</span></span> | <span data-ttu-id="680cb-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="680cb-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="680cb-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="680cb-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="680cb-108">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="680cb-108">Nov 2019</span></span>| <span data-ttu-id="680cb-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="680cb-109">Feb 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="680cb-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="680cb-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="680cb-111">倉庫では、一致する返品注文に追加されていない品目を含む返送品を受け取ることがよくあります。</span><span class="sxs-lookup"><span data-stu-id="680cb-111">Often a warehouse will receive a return shipment with items that were not added on the matching return order.</span></span> <span data-ttu-id="680cb-112">この機能は、注文を事前に調整しなくても、元の返品注文には含まれていなかった品目を作業者が受け取れるようにすることで、標準の返品注文処理を拡張します。</span><span class="sxs-lookup"><span data-stu-id="680cb-112">This feature extends standard return order processing by enabling workers to receive items that were not present on the original return order without having to adjust the order beforehand.</span></span> <span data-ttu-id="680cb-113">そのような返送品が倉庫に届き、見つからない品目が作業者によってスキャンされると、確認メッセージがモバイル デバイスに表示されます。</span><span class="sxs-lookup"><span data-stu-id="680cb-113">When such a return shipment arrives to the warehouse and a missing item is scanned by the worker, a confirmation message is shown on the mobile device.</span></span> <span data-ttu-id="680cb-114">確認された場合、数量が一致する入庫品目の返品注文に新しい明細行が作成されます。</span><span class="sxs-lookup"><span data-stu-id="680cb-114">If confirmed, a new line is created on the return order for the received item with  the matching quantity.</span></span> <span data-ttu-id="680cb-115">この機能はユーザー レベルで管理できます。</span><span class="sxs-lookup"><span data-stu-id="680cb-115">This functionality can be managed on the user level.</span></span>
<!--feature detail end -->











