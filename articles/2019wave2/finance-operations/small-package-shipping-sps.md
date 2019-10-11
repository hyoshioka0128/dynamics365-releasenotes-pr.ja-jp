---
title: 小型パッケージ配送 (SPS)
description: 小型パッケージ配送 (SPS)
author: relnotes
ms.reviewer: josaw
ms.date: 08/30/2019
ms.assetid: a862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 5479d24ca50b4784d4d4f7e4c6d6eb77669526fe
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2142814"
---
# <a name="small-package-shipping-sps"></a><span data-ttu-id="a6efc-103">小型パッケージ配送 (SPS)</span><span class="sxs-lookup"><span data-stu-id="a6efc-103">Small package shipping (SPS)</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="a6efc-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a6efc-104">Enabled for</span></span>    |  <span data-ttu-id="a6efc-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a6efc-105">Public preview</span></span> | <span data-ttu-id="a6efc-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="a6efc-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a6efc-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a6efc-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="a6efc-108">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="a6efc-108">Nov 2019</span></span>| <span data-ttu-id="a6efc-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="a6efc-109">Feb 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a6efc-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a6efc-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a6efc-111">小型パッケージ配送機能を使用すると、梱包されたコンテナーを評価し、カスタム配送業者評価エンジンから追跡番号を割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="a6efc-111">The small package shipping feature allows packed containers to be rated and have tracking numbers assigned from custom carrier rating engines.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a6efc-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a6efc-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a6efc-113">小型パッケージ配送機能 (SPS) を使用すると、梱包されたコンテナーを評価し、カスタム配送業者評価エンジンから追跡番号を割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="a6efc-113">Small package shipping (SPS) allows packed containers to be rated and have tracking numbers assigned from custom carrier rating engines.</span></span> <span data-ttu-id="a6efc-114">SPS は、手動倉庫管理梱包、ウェーブ コンテナー詰め、または小売店舗の梱包と出荷のいずれかと連携して、梱包されたコンテナーに関する詳細を配送業者に送信し、評価と追跡番号を受け取ります。</span><span class="sxs-lookup"><span data-stu-id="a6efc-114">SPS works in conjunction with either manual warehouse management packing, wave containerization, or retail store pack-and-ship to send details about a packed container to a shipping carrier and receive back a rate and tracking number.</span></span> <span data-ttu-id="a6efc-115">返品料は、雑費として関連する販売注文に追加されます。</span><span class="sxs-lookup"><span data-stu-id="a6efc-115">The returned rate will be added to the associated sales order as a miscellaneous charge.</span></span> <span data-ttu-id="a6efc-116">必要に応じて、返品ラベルを自動的に ZPL プリンターに印刷することができます。</span><span class="sxs-lookup"><span data-stu-id="a6efc-116">The returned label can optionally be printed to a ZPL printer automatically.</span></span> <span data-ttu-id="a6efc-117">ユーザーは、使用される各配送業者のアカウント情報を指定します。コンテナー情報が関連付けられたサービスに送信され、サービスは料金、追跡番号、およびラベル情報を返します。</span><span class="sxs-lookup"><span data-stu-id="a6efc-117">Users specify their account information for each carrier that will be used, and the container information is sent to the associated service, which will return a rate, tracking number, and label information.</span></span> <span data-ttu-id="a6efc-118">さらに、必要に応じて、各顧客にサードパーティのアカウント番号を指定できます。</span><span class="sxs-lookup"><span data-stu-id="a6efc-118">Additionally, a third-party account number can be specified for each customer, as desired.</span></span> <span data-ttu-id="a6efc-119">特定の配送業者評価エンジンは含まれていないため、別途取得する必要があることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="a6efc-119">Note that specific carrier rating engines are not included and must be acquired separately.</span></span>
<!--feature detail end -->











