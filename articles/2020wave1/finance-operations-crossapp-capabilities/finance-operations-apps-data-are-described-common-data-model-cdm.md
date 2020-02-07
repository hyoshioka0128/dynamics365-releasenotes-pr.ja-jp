---
title: Finance and Operations アプリのデータを Common Data Model で記述する
description: テーブルやエンティティを含む Finance and Operations アプリのすべてのデータが、Common Data Model で記述されます
author: relnotes
ms.reviewer: kfend
ms.date: 01/14/2020
ms.assetid: 1b434b83-30cc-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: milindav
dynamics365pdf: true
ms.openlocfilehash: da9b00b3697c4a2b82e711a902f54764cd24ff22
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986719"
---
# <a name="finance-and-operations-apps-data-is-described-in-the-common-data-model"></a><span data-ttu-id="a8be9-103">Finance and Operations アプリのデータを Common Data Model で記述する</span><span class="sxs-lookup"><span data-stu-id="a8be9-103">Finance and Operations apps data is described in the Common Data Model</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="a8be9-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="a8be9-104">Enabled for</span></span>    |  <span data-ttu-id="a8be9-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a8be9-105">Public preview</span></span> | <span data-ttu-id="a8be9-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="a8be9-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a8be9-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a8be9-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="a8be9-108">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="a8be9-108">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a8be9-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a8be9-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a8be9-110">Common Data Model とは、Dynamics 365 Finance and Operations アプリなどの Microsoft サービスで利用可能なすべてのデータを記述するデータ スキーマです。</span><span class="sxs-lookup"><span data-stu-id="a8be9-110">The Common Data Model is the data schema that describes all of the data available in Microsoft services including Dynamics 365 Finance and Operations apps.</span></span> <span data-ttu-id="a8be9-111">お客様やパートナーは、アプリケーションが Microsoft サービスと緊密に統合できることを理解したうえで、Common Data Model で記述されているデータ モデルを使用してダウンストリーム アプリケーションや拡張機能を構築できます。</span><span class="sxs-lookup"><span data-stu-id="a8be9-111">Customers and partners can build downstream applications and extensions using the data model described in the Common Data Model knowing that their applications can integrate tightly with Microsoft services.</span></span> <span data-ttu-id="a8be9-112">パートナー、プロバイダー、業界グループは、業界や業種に固有の拡張機能を使用して、ERP のコア スキーマを進化させることができます。</span><span class="sxs-lookup"><span data-stu-id="a8be9-112">Partners, providers, and industry groups can evolve the core ERP schemas with extensions that are specific to industries and verticals.</span></span>

<span data-ttu-id="a8be9-113">Power BI などの AI ツールや分析ツールでは、Common Data Model スキーマがネイティブに理解されます。</span><span class="sxs-lookup"><span data-stu-id="a8be9-113">AI and analytics tools such as Power BI natively understand the Common Data Model schema.</span></span> <span data-ttu-id="a8be9-114">たとえば、Power BI コネクタを使用して外部データを取り込むとき、ユーザーは発注書、在庫、元帳などの Common Data Model エンティティを使用して宛先にデータを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="a8be9-114">For example, when ingesting external data using Power BI connectors, users can easily store the data in the destination using the Common Data Model entities such as Purchase Orders, Inventory, and Ledger.</span></span> <span data-ttu-id="a8be9-115">これにより、ユーザーは、あるエンティティ形式から別の形式へのデータの変換と処理に時間を費やすことなく、複数のソースからのデータを結合するリッチ アプリケーションを作成できます。</span><span class="sxs-lookup"><span data-stu-id="a8be9-115">This enables users to create rich applications that combine data from multiple sources without spending too much time transforming and wrangling data from one entity shape to another.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a8be9-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a8be9-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a8be9-117">テーブルやエンティティを含む Finance and Operations アプリのすべてのデータは、Common Data Model (CDM) で記述されます。</span><span class="sxs-lookup"><span data-stu-id="a8be9-117">All of the data in Finance and Operations apps, including tables and entities, are described in the Common Data Model.</span></span> <span data-ttu-id="a8be9-118">これにより、幅広く受け入れられているエンティティの標準セットに宛先データが保存されるため、複数のアプリケーションからのデータを簡単に結合できます。</span><span class="sxs-lookup"><span data-stu-id="a8be9-118">This makes combining data from multiple applications easy because the destination data is stored in a broadly accepted standard set of entities.</span></span>
<!--feature detail end -->









