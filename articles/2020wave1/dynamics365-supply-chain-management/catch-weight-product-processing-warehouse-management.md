---
title: 倉庫管理での CW 製品処理
description: 農業、食品、鉱業、金属などの一部の産業では、ビジネス プロセス フローで複数の測定単位を使用して製品を追跡する必要があります。
author: relnotes
ms.reviewer: kamaybac
ms.date: 12/16/2019
ms.assetid: 80e7006d-1f1c-ea11-a811-000d3a8f0752
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: f695247b406980087c7872cc5e0f050c9ca31c61
ms.sourcegitcommit: 1e222f5d9816ce7157d63f308aea14d853628226
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/10/2020
ms.locfileid: "3035797"
---
# <a name="catch-weight-product-processing-with-warehouse-management"></a><span data-ttu-id="5da2b-103">倉庫管理での CW 製品処理</span><span class="sxs-lookup"><span data-stu-id="5da2b-103">Catch weight product processing with warehouse management</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="5da2b-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="5da2b-104">Enabled for</span></span>    |  <span data-ttu-id="5da2b-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="5da2b-105">Public preview</span></span> | <span data-ttu-id="5da2b-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="5da2b-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="5da2b-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="5da2b-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="5da2b-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="5da2b-108">Feb 2020</span></span>| <span data-ttu-id="5da2b-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="5da2b-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="5da2b-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="5da2b-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="5da2b-111">CW 製品で、倉庫管理プロセスに関連するビジネス シナリオを処理できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5da2b-111">With catch weight products, you can now handle business scenarios related to warehouse management processes.</span></span>

<span data-ttu-id="5da2b-112">この機能では、割り当てられた CW 単位ごとにキャプチャされた重量を取得する CW タグが提供されます。</span><span class="sxs-lookup"><span data-stu-id="5da2b-112">This feature provides a catch weight tag that fetches the captured weight per catch weight unit assigned.</span></span> <span data-ttu-id="5da2b-113">このアプローチの目的は、製品を受領時に 1 回のみ計量することです。</span><span class="sxs-lookup"><span data-stu-id="5da2b-113">The goal of this approach is to weigh the product only once—at the time of receipt.</span></span> <span data-ttu-id="5da2b-114">これは、時間がたっても重量が変化しない製品 (冷凍エビなど)、および出荷可能な材料取り扱い測定単位 (エビの箱など) がある製品に有効です。</span><span class="sxs-lookup"><span data-stu-id="5da2b-114">This works for products that don't change weight over time (such as frozen shrimp) and products that have a handling unit of measure that is shippable (such as a box of shrimp).</span></span> <span data-ttu-id="5da2b-115">このアプローチでは、ユーザーは、CW タグをスキャンし、製品の構成に基づいてピッキング時または梱包時に重量を識別します。</span><span class="sxs-lookup"><span data-stu-id="5da2b-115">With this approach, the user scans the catch weight tag to identify the weight at the time of picking or packing based on the product configuration.</span></span> <span data-ttu-id="5da2b-116">その後、キャプチャされた CW タグに関連付けられている重量に基づいて請求します。</span><span class="sxs-lookup"><span data-stu-id="5da2b-116">Then invoicing is based on the weight that is associated with the captured catch weight tag.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="5da2b-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="5da2b-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="5da2b-118">この機能は、**機能管理**インターフェイスで有効になります。</span><span class="sxs-lookup"><span data-stu-id="5da2b-118">The feature is enabled in the **Feature management** interface.</span></span> <span data-ttu-id="5da2b-119">新機能には、未処理の在庫トランザクションを持つ既存の CW 品目のアップグレード機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="5da2b-119">The new functionality includes upgrade capabilities for existing catch weight items that have open inventory transactions.</span></span> <span data-ttu-id="5da2b-120">品目は、**品目の分析コード グループの変更**オプションを通じて倉庫管理プロセスに対して有効にすることができます。</span><span class="sxs-lookup"><span data-stu-id="5da2b-120">The items can be enabled for warehouse management processes by means of the **Change storage dimension group for items** option.</span></span>
<!--feature detail end -->













## <a name="see-also"></a><span data-ttu-id="5da2b-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="5da2b-121">See also</span></span>
<span data-ttu-id="5da2b-122">[機能の探索](https://www.microsoft.com/en-us/videoplayer/embed/RE4jzx8) (ビデオ)</span><span class="sxs-lookup"><span data-stu-id="5da2b-122">[Feature exploration](https://www.microsoft.com/en-us/videoplayer/embed/RE4jzx8) (video)</span></span>

<span data-ttu-id="5da2b-123">[倉庫管理での CW 製品処理](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="5da2b-123">[Catch weight product processing with warehouse management](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/catch-weight-processing) (docs)</span></span>
