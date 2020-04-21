---
title: 店舗在庫プロセスでのシリアル番号追跡用分析コードのサポートの改善
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 02/20/2020
ms.assetid: 87274ed9-f20c-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: boycez
dynamics365pdf: true
ms.openlocfilehash: 7b6d3fa35355eb9f2409fa36bdae3070922fec09
ms.sourcegitcommit: 2928661abcc468748ffc7c33516ebc8e3cd5d653
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/04/2020
ms.locfileid: "3098189"
---
# <a name="improved-support-for-serial-number-tracking-dimension-in-store-inventory-processes"></a><span data-ttu-id="03d50-102">店舗在庫プロセスでのシリアル番号追跡用分析コードのサポートの改善</span><span class="sxs-lookup"><span data-stu-id="03d50-102">Improved support for serial number tracking dimension in store inventory processes</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="03d50-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="03d50-103">Enabled for</span></span>    |  <span data-ttu-id="03d50-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="03d50-104">Public preview</span></span> | <span data-ttu-id="03d50-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="03d50-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="03d50-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="03d50-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="03d50-107">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="03d50-107">Apr 2020</span></span>| <span data-ttu-id="03d50-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="03d50-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="03d50-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="03d50-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="03d50-110">顧客ベースが増えるにつれて、シリアル管理が必要な製品を販売する小売業者が多いことが判明してきました。</span><span class="sxs-lookup"><span data-stu-id="03d50-110">As we increase our customer base, we are finding more retailers that sell products that require serial control.</span></span> <span data-ttu-id="03d50-111">現在提供中の販売時点管理 (POS) アプリケーションでは、限られた在庫分析コードのセットだけが使用されています。</span><span class="sxs-lookup"><span data-stu-id="03d50-111">Our current in-market point of sale (POS) application only uses a limited set of inventory dimensions.</span></span> <span data-ttu-id="03d50-112">追跡用分析コード (シリアル番号、バッチ ID など) は完全にはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="03d50-112">The tracking dimensions (serial number, batch ID, and so on) are not fully supported.</span></span> <span data-ttu-id="03d50-113">この機能により、POS の入庫在庫操作が強化され、店舗の在庫入荷プロセスでのシリアル番号追跡用分析コードがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="03d50-113">This feature will improve upon the POS inbound inventory operation to support the serial number tracking dimension in store inventory receiving processes.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="03d50-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="03d50-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="03d50-115">この機能を使用すると、POS ユーザーは発注書または移動オーダーの受信時にシリアル番号を登録できます。</span><span class="sxs-lookup"><span data-stu-id="03d50-115">This feature provides POS users with the ability to register serial numbers during receiving of purchase or transfer orders.</span></span>
<!--feature detail end -->









