---
title: 積荷品目の入庫中に倉庫アプリで製品バリアントと追跡用分析コードをキャプチャする
description: 積荷品目の入庫中に倉庫アプリで製品バリアントと追跡用分析コードをキャプチャする
author: relnotes
ms.reviewer: kamaybac
ms.date: 05/05/2020
ms.assetid: 321a9322-7385-ea11-a812-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: 096c2e59af80337adc42a0e48c9fa9edb2698c00
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350932"
---
# <a name="capture-product-variants-and-tracking-dimensions-in-the-warehousing-app-during-load-item-receiving"></a><span data-ttu-id="56b87-103">積荷品目の入庫中に倉庫アプリで製品バリアントと追跡用分析コードをキャプチャする</span><span class="sxs-lookup"><span data-stu-id="56b87-103">Capture product variants and tracking dimensions in the warehousing app during load item receiving</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="56b87-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="56b87-104">Enabled for</span></span>    |  <span data-ttu-id="56b87-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="56b87-105">Public preview</span></span> | <span data-ttu-id="56b87-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="56b87-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="56b87-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="56b87-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="56b87-108">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="56b87-108">May 2020</span></span>| <span data-ttu-id="56b87-109">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="56b87-109">Jul 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="56b87-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="56b87-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="56b87-111">この機能により、複数の製品バリアントを含む積荷の積荷品目入庫プロセス中に、特定の製品バリアントを (製品バーコードを使用せずに) キャプチャできます。</span><span class="sxs-lookup"><span data-stu-id="56b87-111">This feature makes it possible to capture a specific product variant (without using a product barcode) during the load item receiving process for loads containing multiple product variants.</span></span> <span data-ttu-id="56b87-112">また、注文明細行に事前に定義されていれば、追跡用分析コード値 (バッチやシリアル番号など) をキャプチャすることもできます。</span><span class="sxs-lookup"><span data-stu-id="56b87-112">You can also capture tracking-dimension values (such as batch and serial numbers) provided they are predefined on the order lines.</span></span> <span data-ttu-id="56b87-113">これにより、倉庫入庫担当者は、注文明細行シーケンスに従って特定の各 SKU を見つけるように指示されるのではなく、開梱時に各品目を登録し、そのバリアントと追跡用分析コードをメモできます。</span><span class="sxs-lookup"><span data-stu-id="56b87-113">This enables the warehouse receiving clerk to register each item and note its variant and tracking dimensions as it's unpacked, rather than being instructed to locate each specific SKU following the order-line sequence.</span></span>
<!--feature detail end -->









