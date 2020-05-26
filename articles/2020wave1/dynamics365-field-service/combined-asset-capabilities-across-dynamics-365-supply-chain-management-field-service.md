---
title: Dynamics 365 Supply Chain Management と Field Service 全体にわたる資産機能の統合
description: Supply Chain Management と連携するように Dynamics 365 Field Service の資産管理機能を強化しました。
author: relnotes
ms.reviewer: krbjoran
ms.date: 04/20/2020
ms.assetid: bc8c9d11-0f1e-ea11-a811-000d3a8f022a
ms.topic: article
ms.service: business-applications
ms.author: jacoh
dynamics365pdf: true
ms.openlocfilehash: bcd7f513c474d5e1b369b6be4dbc2f38c7784198
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294107"
---
# <a name="combined-asset-capabilities-across-dynamics-365-supply-chain-management-and-field-service"></a><span data-ttu-id="1ce3c-103">Dynamics 365 Supply Chain Management と Field Service 全体にわたる資産機能の統合</span><span class="sxs-lookup"><span data-stu-id="1ce3c-103">Combined asset capabilities across Dynamics 365 Supply Chain Management and Field Service</span></span>


| <span data-ttu-id="1ce3c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1ce3c-104">Enabled for</span></span>    |  <span data-ttu-id="1ce3c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1ce3c-105">Public preview</span></span> | <span data-ttu-id="1ce3c-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="1ce3c-106">Early access</span></span> | <span data-ttu-id="1ce3c-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="1ce3c-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="1ce3c-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="1ce3c-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1ce3c-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1ce3c-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1ce3c-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="1ce3c-110">Feb 3, 2020</span></span>|-| <span data-ttu-id="1ce3c-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1ce3c-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1ce3c-112">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="1ce3c-112">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1ce3c-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1ce3c-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1ce3c-114">多くのお客様は、貴重な資産をモデル化し、追跡し、提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1ce3c-114">Many customers need to model, track, and service valuable assets.</span></span> <span data-ttu-id="1ce3c-115">Dynamics 365 Supply Chain Management に追加された豊富なエンタープライズ資産管理機能は、Dynamics 365 Field Service での包括的な資産サービス機能と連携するようになりました。</span><span class="sxs-lookup"><span data-stu-id="1ce3c-115">Dynamics 365 Supply Chain Management has added rich enterprise asset management capabilities, which are now aligned with the comprehensive asset service capabilities in Dynamics 365 Field Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1ce3c-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1ce3c-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1ce3c-117">この機能は、Field Service と Supply Chain Management の間で資産エンティティ モデルを調整して、技術者が Field Service を使用しながら資産管理関連のタスクを完了できるようにします。</span><span class="sxs-lookup"><span data-stu-id="1ce3c-117">This feature aligns the asset entity models between Field Service and Supply Chain Management to enable technicians to complete asset management-related tasks while using Field Service.</span></span> <span data-ttu-id="1ce3c-118">Common Data Model と Common Data Service を利用して、これらの資産管理機能を統合し、さまざまな資産中心のシナリオをサポートできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="1ce3c-118">Leveraging the Common Data Model and Common Data Service, these asset management capabilities have now been brought together to support a variety of asset-centric scenarios.</span></span> 

<span data-ttu-id="1ce3c-119">Field Service と Supply Chain Management の資産管理ソリューションの両方で顧客資産エンティティを調整することにより、資産管理のユーザーが Field Service シナリオの完全な機能を、Field Service のユーザーが資産管理の機能を制限なく利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="1ce3c-119">Aligning the customer asset entity across both Field Service and Supply Chain Management's Asset Management solution helps in unlocking the full capability of Field Service scenarios for Asset Management customers and the capabilities of Asset Management for Field Service customers.</span></span> <span data-ttu-id="1ce3c-120">これは、製造で始まり、インストール、メンテナンス、修理を経て除却で終わる重要な資産ライフサイクルをサポートします。</span><span class="sxs-lookup"><span data-stu-id="1ce3c-120">This supports the critical asset lifecycle that begins in manufacturing, continues through installation, maintenance, and repair, and ends in retirement.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="1ce3c-121">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="1ce3c-121">This feature is available in the Unified Interface only.</span></span>







## <a name="see-also"></a><span data-ttu-id="1ce3c-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="1ce3c-122">See also</span></span>

<!--docs start-->
<span data-ttu-id="1ce3c-123">[Dynamics 365 Field Service および Supply Chain Management を統合する](https://docs.microsoft.com/dynamics365/field-service/supply-chain-field-service-integration) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="1ce3c-123">[Integrate Dynamics 365 Field Service and Supply Chain Management](https://docs.microsoft.com/dynamics365/field-service/supply-chain-field-service-integration) (docs)</span></span>
<!--docs end-->
