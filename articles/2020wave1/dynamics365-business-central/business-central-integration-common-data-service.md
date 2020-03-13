---
title: Business Central と Common Data Service の統合
description: Business Central と Common Data Service の統合。
author: relnotes
ms.reviewer: solsen
ms.date: 02/05/2020
ms.assetid: 2591eb8d-52ca-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: henrikwh
dynamics365pdf: true
ms.openlocfilehash: 325bf1650b90c6f04b374af1d791e67651a479c1
ms.sourcegitcommit: 99df54b08ef3f481b1999c80acfbd71cc3a0e591
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/07/2020
ms.locfileid: "3031937"
---
# <a name="business-central-integration-with-common-data-service"></a><span data-ttu-id="48e87-103">Business Central と Common Data Service の統合</span><span class="sxs-lookup"><span data-stu-id="48e87-103">Business Central integration with Common Data Service</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="48e87-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="48e87-104">Enabled for</span></span>    |  <span data-ttu-id="48e87-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="48e87-105">Public preview</span></span> | <span data-ttu-id="48e87-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="48e87-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="48e87-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="48e87-107">End users, automatically</span></span>|<span data-ttu-id="48e87-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="48e87-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="48e87-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="48e87-109">Feb 1, 2020</span></span>| <span data-ttu-id="48e87-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="48e87-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="48e87-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="48e87-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="48e87-112">新しい Common Data Service オンボード エクスペリエンスが提供されます。ユーザーは Common Data Service 環境に接続して、Business Central の会社を Common Data Service の部署に関連付けることができます。</span><span class="sxs-lookup"><span data-stu-id="48e87-112">A new Common Data Service onboarding experience will be provided, where users will be able to connect to a Common Data Service environment and associate a Business Central company with a Common Data Service business unit.</span></span> <span data-ttu-id="48e87-113">これにより、複数の企業が Common Data Service インスタンスに接続できるようになります。</span><span class="sxs-lookup"><span data-stu-id="48e87-113">This will allow for multiple companies to connect to a Common Data Service instance.</span></span> <span data-ttu-id="48e87-114">セットアップの間に、既定の Common Data Service データベースの Common Data Service 接続エンティティが同期されます。</span><span class="sxs-lookup"><span data-stu-id="48e87-114">During setup, the Common Data Service connection entities from the default Common Data Service database will be synchronized.</span></span> 

<span data-ttu-id="48e87-115">これにより、Common Data Service 向けの統合を開発している開発者に対する拡張性がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="48e87-115">This provides extensibility support for developers developing integrations for Common Data Service.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="48e87-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="48e87-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="48e87-117">Common Data Service は、Dynamics 365 スイートの中心です。</span><span class="sxs-lookup"><span data-stu-id="48e87-117">Common Data Service is at the center of the Dynamics 365 suite.</span></span> <span data-ttu-id="48e87-118">Common Data Service を使用すると、Common Data Service でデータを利用できるため、ユーザーはビジネスをすべての方向から見ることができます。</span><span class="sxs-lookup"><span data-stu-id="48e87-118">Common Data Service enables users to have a 360-degree view of their business as data is available in Common Data Service.</span></span> <span data-ttu-id="48e87-119">データが Common Data Service に取り込まれると、ユーザーは Dynamics 365 ソリューション全体で共有されるデータの一貫したビューを取得できます。</span><span class="sxs-lookup"><span data-stu-id="48e87-119">Once data is in Common Data Service, users will have a shared, consistent view of data across the Dynamics 365 solution.</span></span> <span data-ttu-id="48e87-120">Dynamics 365 Business Central では、他の統合が依存する "Business Central の CDS ベース ソリューション" で提供される既定の Common Data Service データベースのエンティティ セットがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="48e87-120">Dynamics 365 Business Central will support a set of entities in the Common Data Service default database provided in a "Business Central CDS Base Solution," which other integrations will depend on.</span></span> <span data-ttu-id="48e87-121">ベース ソリューションには、会社のエンティティを Common Data Service の部署エンティティにマップする機能があります。</span><span class="sxs-lookup"><span data-stu-id="48e87-121">The base solution will bring the capability to map a Company entity to a Business Unit entity in Common Data Service.</span></span> 

<span data-ttu-id="48e87-122">Common Data Service と統合する拡張機能を開発する場合、Business Central 2020 年リリース ウェーブ 1 では拡張性機能が提供され、Common Data Service テーブルと Common Data Service テーブル拡張機能を作成できます。</span><span class="sxs-lookup"><span data-stu-id="48e87-122">When developing extensions that integrate with Common Data Service, Business Central 2020 release wave 1 will bring extensibility capabilities, where Common Data Service tables and Common Data Service table extensions can be created.</span></span> <span data-ttu-id="48e87-123">これにより、任意のカスタム属性を同期できます。</span><span class="sxs-lookup"><span data-stu-id="48e87-123">This will allow for any custom attribute to be synchronized.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="48e87-124">フィードバック</span><span class="sxs-lookup"><span data-stu-id="48e87-124">Tell us what you think</span></span>
<span data-ttu-id="48e87-125">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="48e87-125">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="48e87-126">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="48e87-126">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="48e87-127">関連項目</span><span class="sxs-lookup"><span data-stu-id="48e87-127">See also</span></span>

<span data-ttu-id="48e87-128">[Dynamics 365 Sales との統合](https://docs.microsoft.com/dynamics365/business-central/admin-prepare-dynamics-365-for-sales-for-integration) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="48e87-128">[Integrating with Dynamics 365 Sales](https://docs.microsoft.com/dynamics365/business-central/admin-prepare-dynamics-365-for-sales-for-integration) (docs)</span></span>
