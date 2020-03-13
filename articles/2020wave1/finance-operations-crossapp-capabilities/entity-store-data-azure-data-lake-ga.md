---
title: Azure Data Lake でエンティティ格納が利用可能に
description: 顧客は、Finance and Operations アプリの分析データとトランザクション データ (エンティティ格納で集計の測定として定義される) を独自の Azure Data Lake で使用して、ほぼリアルタイムの AI と分析を実現できます。
author: relnotes
ms.reviewer: kfend
ms.date: 02/13/2020
ms.assetid: c3876dfc-31cc-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: milindav
dynamics365pdf: true
ms.openlocfilehash: 37cb2f720795e59dc889675c0e212efbd5a155f1
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3080140"
---
# <a name="entity-store-data-is-available-in-azure-data-lake"></a><span data-ttu-id="371da-103">Azure Data Lake でエンティティ格納が利用可能に</span><span class="sxs-lookup"><span data-stu-id="371da-103">Entity store data is available in Azure Data Lake</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="371da-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="371da-104">Enabled for</span></span>    |  <span data-ttu-id="371da-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="371da-105">Public preview</span></span> | <span data-ttu-id="371da-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="371da-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="371da-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="371da-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="371da-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="371da-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="371da-109">2019 年 6 月 1 日</span><span class="sxs-lookup"><span data-stu-id="371da-109">Jun 1, 2019</span></span>| <span data-ttu-id="371da-110">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="371da-110">Aug 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="371da-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="371da-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="371da-112">Finance and Operations アプリと顧客独自の Azure Data Lake に含まれるその他のデータ全体で、高度な分析と AI (データに基づく推論など) が可能になります。</span><span class="sxs-lookup"><span data-stu-id="371da-112">Enable advanced analytics and AI (such as reasoning over data) across Finance and Operations apps and other data in a customer's own Azure Data Lake.</span></span> <span data-ttu-id="371da-113">Finance and Operations アプリでは、非正規化トランザクション データにほぼリアルタイムで簡単にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="371da-113">Finance and Operations apps provide easy access to denormalized transnational data in a near real-time basis.</span></span>

<span data-ttu-id="371da-114">分析ワークスペースに供給される同じデータセットが、独自のレポートとデータ マッシュアップ シナリオで利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="371da-114">The same dataset that powers analytical workspaces is now available for your own reports and data mash-up scenarios.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="371da-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="371da-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="371da-116">集計の測定は、Dynamics 365 Finance and Operations アプリ内で定義されている非正規化スター スキーマです。</span><span class="sxs-lookup"><span data-stu-id="371da-116">Aggregate measurements are denormalized star schemas defined within Dynamics 365 Finance and Operations apps.</span></span> <span data-ttu-id="371da-117">集計の測定を使用すると、ユーザーは複雑なデータ スキーマを理解する必要なく運用データをナビゲートできます。</span><span class="sxs-lookup"><span data-stu-id="371da-117">Aggregate measurements enable users to navigate operational data without having to understand complex data schemas.</span></span> <span data-ttu-id="371da-118">集計の測定はエンティティ格納にステージングされ、運用データ ウェアハウスが含まれます。</span><span class="sxs-lookup"><span data-stu-id="371da-118">Aggregate measurements are staged in Entity store, and the operational data warehouse is included.</span></span>

<span data-ttu-id="371da-119">Azure Data Lake でのエンティティ格納スキーマの一般提供に伴い、顧客はレポート作成と分析のために非正規化データに直接アクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="371da-119">With the general availability of Entity store schemas in Azure Data Lake, customers can directly access denormalized data for reporting and analytics.</span></span> <span data-ttu-id="371da-120">集計の測定は Data Lake Storage Common Data Model フォルダーとして格納されるため、リッチなデータ マッシュアップ シナリオや分析シナリオが可能になります。</span><span class="sxs-lookup"><span data-stu-id="371da-120">Aggregate measurements are stored in Data Lake Storage as Common Data Model folders enabling rich data mash-up and analytical scenarios.</span></span> <span data-ttu-id="371da-121">たとえば、集計の測定データを Power BI 参照データ フローとして Power BI に添付し、レポート作成に使用できます。</span><span class="sxs-lookup"><span data-stu-id="371da-121">For example, aggregate measurement data can be attached as Power BI reference data flows with and used for reporting with Power BI.</span></span> <span data-ttu-id="371da-122">パワー ユーザーは、Power BI Desktop で新しいデータ マッシュアップとレポートを簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="371da-122">Power users can easily create new data mashups and reports in Power BI Desktop.</span></span> 

<span data-ttu-id="371da-123">開発者と BI のプロフェッショナルは Azure Synapse や Azure Data Factory などのツールを使用してデータを操作し、エンタープライズ データ ウェアハウスを作成できます。</span><span class="sxs-lookup"><span data-stu-id="371da-123">Developers and BI professionals can use tools such as Azure Synapse and Azure Data Factory to work with data and create enterprise data warehouses.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="371da-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="371da-124">See also</span></span>

<span data-ttu-id="371da-125">[エンティティ格納を Data Lake として使用可能にする](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/data-entities/entity-store-data-lake) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="371da-125">[Make Entity store available as a Data Lake](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/data-entities/entity-store-data-lake) (docs)</span></span>
