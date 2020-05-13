---
title: 小型パッケージ配送 (SPS)
description: 小型パッケージ配送 (SPS) では、梱包されたコンテナーに関する詳細を配送業者に送信し、料金と追跡番号を受け取ります。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/15/2020
ms.assetid: a862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: e77bd0404f20dd79fa3f67181dafd9aa06c6529d
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3319916"
---
# <a name="small-parcel-shipping-sps"></a><span data-ttu-id="c7f3f-103">小型パッケージ配送 (SPS)</span><span class="sxs-lookup"><span data-stu-id="c7f3f-103">Small parcel shipping (SPS)</span></span>


| <span data-ttu-id="c7f3f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c7f3f-104">Enabled for</span></span>    |  <span data-ttu-id="c7f3f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c7f3f-105">Public preview</span></span> | <span data-ttu-id="c7f3f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c7f3f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c7f3f-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c7f3f-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c7f3f-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c7f3f-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c7f3f-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="c7f3f-109">Feb 3, 2020</span></span>| <span data-ttu-id="c7f3f-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="c7f3f-110">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="c7f3f-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c7f3f-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c7f3f-112">SPS を使用すると、梱包されたコンテナーを評価し、カスタム配送業者評価エンジンから追跡番号を割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="c7f3f-112">SPS allows packed containers to be rated and have tracking numbers assigned from custom carrier rating engines.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c7f3f-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c7f3f-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c7f3f-114">SPS は、手動倉庫管理梱包、ウェーブ コンテナー詰め、または小売店舗の梱包と出荷のいずれかと連携して、梱包されたコンテナーに関する詳細を配送業者に送信し、料金と追跡番号を受け取ります。</span><span class="sxs-lookup"><span data-stu-id="c7f3f-114">SPS works in conjunction with either manual warehouse management packing, wave containerization, or retail store pack-and-ship to send details about a packed container to a shipping carrier and receive a rate and tracking number.</span></span> <span data-ttu-id="c7f3f-115">返品料は、雑費として関連する販売注文に追加されます。</span><span class="sxs-lookup"><span data-stu-id="c7f3f-115">The returned rate will be added to the associated sales order as a miscellaneous charge.</span></span> <span data-ttu-id="c7f3f-116">必要に応じて、返品ラベルを自動的に ZPL プリンターに印刷することができます。</span><span class="sxs-lookup"><span data-stu-id="c7f3f-116">The returned label can optionally be printed to a ZPL printer automatically.</span></span> <span data-ttu-id="c7f3f-117">ユーザーは、使用する各配送業者のアカウント情報を指定します。</span><span class="sxs-lookup"><span data-stu-id="c7f3f-117">Users specify their account information for each carrier that they use.</span></span> <span data-ttu-id="c7f3f-118">システムではコンテナー情報が関連サービスに送信され、サービスからは料金、追跡番号、およびラベル情報が返されます。</span><span class="sxs-lookup"><span data-stu-id="c7f3f-118">The system sends container information to the associated service, which then returns a rate, tracking number, and label information.</span></span> <span data-ttu-id="c7f3f-119">さらに、各顧客にサードパーティのアカウント番号を指定できます。</span><span class="sxs-lookup"><span data-stu-id="c7f3f-119">Additionally, a third-party account number can be specified for each customer.</span></span> <span data-ttu-id="c7f3f-120">(特定の配送業者評価エンジンは含まれていないため、別途取得する必要があります。)</span><span class="sxs-lookup"><span data-stu-id="c7f3f-120">(The specific carrier rating engines are not included and must be acquired separately.)</span></span>
<!--feature detail end -->









## <a name="see-also"></a><span data-ttu-id="c7f3f-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="c7f3f-121">See also</span></span>

<!--docs start-->
<span data-ttu-id="c7f3f-122">[倉庫管理の概要](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c7f3f-122">[Warehouse management overview](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/warehouse-management-overview) (docs)</span></span>
<!--docs end-->
