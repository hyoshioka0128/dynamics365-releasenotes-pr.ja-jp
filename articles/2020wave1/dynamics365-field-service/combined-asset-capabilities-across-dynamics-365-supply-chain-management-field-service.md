---
title: Dynamics 365 Supply Chain Management と Field Service 全体にわたる資産機能の統合
description: Supply Chain Management と連携するように Dynamics 365 Field Service の資産管理機能を強化しました。
author: relnotes
ms.reviewer: krbjoran
ms.date: 02/25/2020
ms.assetid: bc8c9d11-0f1e-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: jacoh
dynamics365pdf: true
ms.openlocfilehash: 9c52442a4244f35414bb88f5533b81d356853652
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232123"
---
# <a name="combined-asset-capabilities-across-dynamics-365-supply-chain-management-and-field-service"></a><span data-ttu-id="37a07-103">Dynamics 365 Supply Chain Management と Field Service 全体にわたる資産機能の統合</span><span class="sxs-lookup"><span data-stu-id="37a07-103">Combined asset capabilities across Dynamics 365 Supply Chain Management and Field Service</span></span>
[!include[dynamics365-field-service banner](../includes/dynamics365-field-service.md)]

| <span data-ttu-id="37a07-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="37a07-104">Enabled for</span></span>    |  <span data-ttu-id="37a07-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="37a07-105">Public preview</span></span> | <span data-ttu-id="37a07-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="37a07-106">Early access</span></span> | <span data-ttu-id="37a07-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="37a07-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="37a07-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="37a07-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="37a07-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="37a07-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="37a07-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="37a07-110">Feb 3, 2020</span></span>|-| <span data-ttu-id="37a07-111">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="37a07-111">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="37a07-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="37a07-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="37a07-113">多くのお客様は、貴重な資産をモデル化し、追跡し、提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="37a07-113">Many customers need to model, track, and service valuable assets.</span></span> <span data-ttu-id="37a07-114">Dynamics 365 Supply Chain Management に追加された豊富なエンタープライズ資産管理機能は、Dynamics 365 Field Service での包括的な資産サービス機能と連携するようになりました。</span><span class="sxs-lookup"><span data-stu-id="37a07-114">Dynamics 365 Supply Chain Management has added rich enterprise asset management capabilities, which are now aligned with the comprehensive asset service capabilities in Dynamics 365 Field Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="37a07-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="37a07-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="37a07-116">この機能は、Field Service と Supply Chain Management の間で資産エンティティ モデルを調整して、技術者が Field Service を使用しながら資産管理関連のタスクを完了できるようにします。</span><span class="sxs-lookup"><span data-stu-id="37a07-116">This feature aligns the asset entity models between Field Service and Supply Chain Management to enable technicians to complete asset management-related tasks while using Field Service.</span></span> <span data-ttu-id="37a07-117">Common Data Model と Common Data Service を利用して、これらの資産管理機能を統合し、さまざまな資産中心のシナリオをサポートできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="37a07-117">Leveraging the Common Data Model and Common Data Service, these asset management capabilities have now been brought together to support a variety of asset-centric scenarios.</span></span> 

<span data-ttu-id="37a07-118">Field Service と Supply Chain Management の資産管理ソリューションの両方で顧客資産エンティティを調整することにより、資産管理のユーザーが Field Service シナリオの完全な機能を、Field Service のユーザーが資産管理の機能を制限なく利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="37a07-118">Aligning the customer asset entity across both Field Service and Supply Chain Management's Asset Management solution helps in unlocking the full capability of Field Service scenarios for Asset Management customers and the capabilities of Asset Management for Field Service customers.</span></span> <span data-ttu-id="37a07-119">これは、製造で始まり、インストール、メンテナンス、修理を経て除却で終わる重要な資産ライフサイクルをサポートします。</span><span class="sxs-lookup"><span data-stu-id="37a07-119">This supports the critical asset lifecycle that begins in manufacturing, continues through installation, maintenance, and repair, and ends in retirement.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="37a07-120">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="37a07-120">This feature is available in the Unified Interface only.</span></span>







## <a name="see-also"></a><span data-ttu-id="37a07-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="37a07-121">See also</span></span>


<!--docs start-->
<span data-ttu-id="37a07-122">[Dynamics 365 Field Service と Supply Chain Management を統合する](https://docs.microsoft.com/dynamics365/field-service/supply-chain-field-service-integration) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="37a07-122">[Integrate Dynamics 365 Field Service and Supply Chain Management](https://docs.microsoft.com/dynamics365/field-service/supply-chain-field-service-integration) (docs)</span></span>
<!--docs end-->

