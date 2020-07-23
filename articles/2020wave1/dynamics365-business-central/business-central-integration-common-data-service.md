---
title: Business Central と Common Data Service の統合
description: Business Central と Common Data Service の統合。
author: relnotes
ms.reviewer: solsen
ms.date: 04/20/2020
ms.assetid: 2591eb8d-52ca-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: henrikwh
dynamics365pdf: true
ms.openlocfilehash: 21c66306f12dce6eba76ab2148e3b2956e356357
ms.sourcegitcommit: 299e7ae952585bc5f8dbe620de3a9d5ef778990a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2020
ms.locfileid: "3548138"
---
# <a name="business-central-integration-with-common-data-service"></a><span data-ttu-id="64419-103">Business Central と Common Data Service の統合</span><span class="sxs-lookup"><span data-stu-id="64419-103">Business Central integration with Common Data Service</span></span>


| <span data-ttu-id="64419-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="64419-104">Enabled for</span></span>    |  <span data-ttu-id="64419-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="64419-105">Public preview</span></span> | <span data-ttu-id="64419-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="64419-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="64419-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="64419-107">End users, automatically</span></span>|<span data-ttu-id="64419-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="64419-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="64419-109">2020 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="64419-109">Feb 1, 2020</span></span>| <span data-ttu-id="64419-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="64419-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="64419-111">2020 年 4 月 2 日</span><span class="sxs-lookup"><span data-stu-id="64419-111">Apr 2, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="64419-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="64419-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="64419-113">新しい Common Data Service オンボード エクスペリエンスが提供されます。ユーザーは Common Data Service 環境に接続して、Business Central の会社を Common Data Service の部署に関連付けることができます。</span><span class="sxs-lookup"><span data-stu-id="64419-113">A new Common Data Service onboarding experience will be provided, where users will be able to connect to a Common Data Service environment and associate a Business Central company with a Common Data Service business unit.</span></span> <span data-ttu-id="64419-114">これにより、複数の企業が Common Data Service 環境に接続できるようになります。</span><span class="sxs-lookup"><span data-stu-id="64419-114">This will allow for multiple companies to connect to a Common Data Service environment.</span></span> <span data-ttu-id="64419-115">セットアップの間に、既定の Common Data Service データベースの Common Data Service 接続エンティティが同期されます。</span><span class="sxs-lookup"><span data-stu-id="64419-115">During setup, Common Data Service connection entities from the default Common Data Service database will be synchronized.</span></span> 

<span data-ttu-id="64419-116">Common Data Service 向けの Business Central 統合を開発している開発者に対する拡張性がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="64419-116">Extensibility support for developers developing Business Central integrations for Common Data Service is provided.</span></span> <span data-ttu-id="64419-117">拡張性のサポートにより、Business Central Extensions を記述して、フィールドとテーブルを同期プロセスに追加し、既存のテーブルも拡張できます。</span><span class="sxs-lookup"><span data-stu-id="64419-117">With the extensibility support, Business Central Extensions can be written to add fields and tables to the synchronization process, also extending existing tables.</span></span> <span data-ttu-id="64419-118">さらに、変換を作成し、値を変換およびマッピングできます。</span><span class="sxs-lookup"><span data-stu-id="64419-118">In addition, transformation can be created, transforming and mapping values.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="64419-119">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="64419-119">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="64419-120">Common Data Service は、Dynamics 365 スイートの中心です。</span><span class="sxs-lookup"><span data-stu-id="64419-120">Common Data Service is at the center of the Dynamics 365 suite.</span></span> <span data-ttu-id="64419-121">ユーザーはビジネスをすべての方向から見ることができます。</span><span class="sxs-lookup"><span data-stu-id="64419-121">It enables users to have a 360-degree view of their business.</span></span> <span data-ttu-id="64419-122">Common Data Service 内のデータにより、ユーザーとソリューションに Dynamics 365 ソリューション全体で共有されるデータの一貫したビューが与えられます。</span><span class="sxs-lookup"><span data-stu-id="64419-122">Data in Common Data Service gives users and solutions a shared, consistent view of data across Dynamics 365 solutions.</span></span> <span data-ttu-id="64419-123">Dynamics 365 Business Central では Common Data Service の既定のデータベース内のエンティティのセットがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="64419-123">Dynamics 365 Business Central will support a set of entities in the Common Data Service default database.</span></span> <span data-ttu-id="64419-124">Business Central Common Data Service のベース ソリューションは、他の統合が依存するものです。</span><span class="sxs-lookup"><span data-stu-id="64419-124">Business Central Common Data Service Base Solution is what other integrations will depend on.</span></span> <span data-ttu-id="64419-125">ベース ソリューションにより、ユーザーは会社のエンティティを Common Data Service の部署エンティティにマップできます。</span><span class="sxs-lookup"><span data-stu-id="64419-125">The base solution will allow users to map a Company entity to a Business Unit entity in Common Data Service.</span></span> 

<span data-ttu-id="64419-126">Common Data Service と統合する拡張機能を開発する場合、2020 年リリース ウェーブ 1 では拡張性機能が提供され、そこで Common Data Service テーブルへのプロキシを Business Central に作成でき、これらは拡張可能になります。</span><span class="sxs-lookup"><span data-stu-id="64419-126">For developing extensions that integrate with Common Data Service, 2020 release wave 1 will bring extensibility capabilities where proxies to Common Data Service tables can be created in Business Central, and these will be made extensible.</span></span> <span data-ttu-id="64419-127">これにより、カスタム属性を同期したり、同期プロセスに追加のテーブルを追加したりできます。</span><span class="sxs-lookup"><span data-stu-id="64419-127">This will allow for custom attributes to be synchronized and for additional tables to be added to the synchronization process.</span></span> <span data-ttu-id="64419-128">同期プロセスでのフィールド値のマッピングと変換のサポートが利用可能になりました。</span><span class="sxs-lookup"><span data-stu-id="64419-128">Support for mapping and transforming field values in the synchronization process are now available.</span></span> 

<span data-ttu-id="64419-129">CRM Sales 統合の新規インストールは、新しい Business Central Common Data Service ベース ソリューションの上にインストールされ、このソリューションに前述の機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="64419-129">New installations of the CRM Sales integration will install on top of the new Business Central Common Data Service Base Solution, providing the capabilities described above to this solution.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="64419-130">フィードバック</span><span class="sxs-lookup"><span data-stu-id="64419-130">Tell us what you think</span></span>
<span data-ttu-id="64419-131">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="64419-131">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="64419-132">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="64419-132">Use the forum at https://aka.ms/bcideas.</span></span>




## <a name="see-also"></a><span data-ttu-id="64419-133">関連項目</span><span class="sxs-lookup"><span data-stu-id="64419-133">See also</span></span>

<!--docs start-->
<span data-ttu-id="64419-134">[Common Data Service との統合 ](https://docs.microsoft.com/dynamics365/business-central/admin-common-data-service) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="64419-134">[Integrating with Common Data Service](https://docs.microsoft.com/dynamics365/business-central/admin-common-data-service) (docs)</span></span>
<!--docs end-->
