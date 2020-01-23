---
title: 小型パッケージ配送 (SPS)
description: 小型パッケージ配送 (SPS)
author: relnotes
ms.reviewer: kamaybac
ms.date: 12/13/2019
ms.assetid: a862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 3cf2d32229daf623239f145b4e7d0256b441fa4b
ms.sourcegitcommit: 50510b41ebc81897993a45f689651d9eda6c4247
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/20/2019
ms.locfileid: "2909678"
---
# <a name="small-package-shipping-sps"></a><span data-ttu-id="af0bf-103">小型パッケージ配送 (SPS)</span><span class="sxs-lookup"><span data-stu-id="af0bf-103">Small package shipping (SPS)</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="af0bf-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="af0bf-104">Enabled for</span></span>    |  <span data-ttu-id="af0bf-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="af0bf-105">Public preview</span></span> | <span data-ttu-id="af0bf-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="af0bf-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="af0bf-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="af0bf-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="af0bf-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="af0bf-108">Feb 2020</span></span>| <span data-ttu-id="af0bf-109">近日発表</span><span class="sxs-lookup"><span data-stu-id="af0bf-109">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="af0bf-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="af0bf-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="af0bf-111">小型パッケージ配送機能を使用すると、梱包されたコンテナーを評価し、カスタム配送業者評価エンジンから追跡番号を割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="af0bf-111">The small package shipping feature allows packed containers to be rated and have tracking numbers assigned from custom carrier rating engines.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="af0bf-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="af0bf-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="af0bf-113">小型パッケージ配送は、手動倉庫管理梱包、ウェーブ コンテナー詰め、または小売店舗の梱包と出荷のいずれかと連携して、梱包されたコンテナーに関する詳細を配送業者に送信し、評価と追跡番号を受け取ります。</span><span class="sxs-lookup"><span data-stu-id="af0bf-113">Small package shipping works in conjunction with either manual warehouse management packing, wave containerization, or retail store pack-and-ship to send details about a packed container to a shipping carrier and receive a rate and tracking number.</span></span> <span data-ttu-id="af0bf-114">返品料は、雑費として関連する販売注文に追加されます。</span><span class="sxs-lookup"><span data-stu-id="af0bf-114">The returned rate will be added to the associated sales order as a miscellaneous charge.</span></span> <span data-ttu-id="af0bf-115">必要に応じて、返品ラベルを自動的に ZPL プリンターに印刷することができます。</span><span class="sxs-lookup"><span data-stu-id="af0bf-115">The returned label can optionally be printed to a ZPL printer automatically.</span></span> <span data-ttu-id="af0bf-116">ユーザーは、使用される各配送業者のアカウント情報を指定します。コンテナー情報が関連付けられたサービスに送信され、サービスは料金、追跡番号、およびラベル情報を返します。</span><span class="sxs-lookup"><span data-stu-id="af0bf-116">Users specify their account information for each carrier that will be used, and the container information is sent to the associated service, which will return a rate, tracking number, and label information.</span></span> <span data-ttu-id="af0bf-117">さらに、必要に応じて、各顧客にサードパーティのアカウント番号を指定できます。</span><span class="sxs-lookup"><span data-stu-id="af0bf-117">Additionally, a third-party account number can be specified for each customer, as desired.</span></span> <span data-ttu-id="af0bf-118">特定の配送業者評価エンジンは含まれていないため、別途取得する必要があることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="af0bf-118">Note that specific carrier rating engines are not included and must be acquired separately.</span></span>
<!--feature detail end -->









