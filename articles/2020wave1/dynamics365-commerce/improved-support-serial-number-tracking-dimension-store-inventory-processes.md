---
title: 店舗在庫プロセスでのシリアル番号追跡用分析コードのサポートの改善
description: この機能により、POS の入庫操作でシリアル化された品目を処理できます。
author: relnotes
ms.reviewer: josaw
ms.date: 04/29/2020
ms.assetid: 87274ed9-f20c-ea11-a811-000d3a4f1cdd
ms.topic: article
ms.service: business-applications
ms.author: boycez
dynamics365pdf: true
ms.openlocfilehash: a375c51d0f470bb66565553b04705b3f311b6324
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3349547"
---
# <a name="improved-support-for-serial-number-tracking-dimension-in-store-inventory-processes"></a><span data-ttu-id="1ac1d-103">店舗在庫プロセスでのシリアル番号追跡用分析コードのサポートの改善</span><span class="sxs-lookup"><span data-stu-id="1ac1d-103">Improved support for serial number tracking dimension in store inventory processes</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="1ac1d-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1ac1d-104">Enabled for</span></span>    |  <span data-ttu-id="1ac1d-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1ac1d-105">Public preview</span></span> | <span data-ttu-id="1ac1d-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="1ac1d-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1ac1d-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="1ac1d-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1ac1d-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1ac1d-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1ac1d-109">2020 年 4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="1ac1d-109">Apr 13, 2020</span></span>| <span data-ttu-id="1ac1d-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="1ac1d-110">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1ac1d-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1ac1d-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1ac1d-112">顧客ベースが増えるにつれて、シリアル管理が必要な製品を販売する小売業者が多いことが判明してきました。</span><span class="sxs-lookup"><span data-stu-id="1ac1d-112">As we increase our customer base, we are finding more retailers that sell products that require serial control.</span></span> <span data-ttu-id="1ac1d-113">現在提供中の販売時点管理 (POS) アプリケーションでは、限られた在庫分析コードのセットだけが使用されています。</span><span class="sxs-lookup"><span data-stu-id="1ac1d-113">Our current in-market point of sale (POS) application only uses a limited set of inventory dimensions.</span></span> <span data-ttu-id="1ac1d-114">追跡用分析コード (シリアル番号、バッチ ID など) は完全にはサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="1ac1d-114">The tracking dimensions (serial number, batch ID, and so on) are not fully supported.</span></span> <span data-ttu-id="1ac1d-115">この機能により、POS の入庫在庫操作が強化され、店舗の在庫入荷プロセスでのシリアル番号追跡用分析コードがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="1ac1d-115">This feature will improve upon the POS inbound inventory operation to support the serial number tracking dimension in store inventory receiving processes.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1ac1d-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1ac1d-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1ac1d-117">この機能を使用すると、POS ユーザーは発注書または移動オーダーの受信時にシリアル番号を登録できます。</span><span class="sxs-lookup"><span data-stu-id="1ac1d-117">This feature provides POS users with the ability to register serial numbers during receiving of purchase or transfer orders.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="1ac1d-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="1ac1d-118">See also</span></span>

<!--docs start-->
<span data-ttu-id="1ac1d-119">[POS でシリアル化された品目を処理する](https://docs.microsoft.com/dynamics365/commerce/pos-serialized-items) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="1ac1d-119">[Work with serialized items in the POS](https://docs.microsoft.com/dynamics365/commerce/pos-serialized-items) (docs)</span></span>
<!--docs end-->
