---
title: Finance and Operations アプリのデータを Common Data Model で記述する
description: テーブルやエンティティを含む Finance and Operations アプリのすべてのデータが、Common Data Model で記述されます。
author: relnotes
ms.reviewer: kfend
ms.date: 05/11/2020
ms.assetid: 1b434b83-30cc-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: milindav
dynamics365pdf: true
ms.openlocfilehash: 7c065cac2565d02b5df9d22aaab605c89074c73a
ms.sourcegitcommit: 299e7ae952585bc5f8dbe620de3a9d5ef778990a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/09/2020
ms.locfileid: "3548306"
---
# <a name="finance-and-operations-apps-data-is-described-in-common-data-model"></a><span data-ttu-id="f62cb-103">Finance and Operations アプリのデータを Common Data Model で記述する</span><span class="sxs-lookup"><span data-stu-id="f62cb-103">Finance and Operations apps data is described in Common Data Model</span></span>


| <span data-ttu-id="f62cb-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f62cb-104">Enabled for</span></span>    |  <span data-ttu-id="f62cb-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f62cb-105">Public preview</span></span> | <span data-ttu-id="f62cb-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f62cb-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f62cb-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="f62cb-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="f62cb-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="f62cb-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="f62cb-109">2020 年 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="f62cb-109">May 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="f62cb-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f62cb-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f62cb-111">Common Data Model とは、Dynamics 365 Finance and Operations アプリなどの Microsoft サービスで利用可能なすべてのデータを記述するデータ スキーマです。</span><span class="sxs-lookup"><span data-stu-id="f62cb-111">Common Data Model is the data schema that describes all of the data available in Microsoft services including Dynamics 365 Finance and Operations apps.</span></span> <span data-ttu-id="f62cb-112">お客様やパートナーは、アプリケーションが Microsoft サービスと緊密に統合できることを理解したうえで、Common Data Model で記述されているデータ モデルを使用してダウンストリーム アプリケーションや拡張機能を構築できます。</span><span class="sxs-lookup"><span data-stu-id="f62cb-112">Customers and partners can build downstream applications and extensions using the data model described in Common Data Model knowing that their applications can integrate tightly with Microsoft services.</span></span> <span data-ttu-id="f62cb-113">パートナー、プロバイダー、業界グループは、業界や業種に固有の拡張機能を使用して、ERP のコア スキーマを進化させることができます。</span><span class="sxs-lookup"><span data-stu-id="f62cb-113">Partners, providers, and industry groups can evolve the core ERP schemas with extensions that are specific to industries and verticals.</span></span>

<span data-ttu-id="f62cb-114">Power BI などの AI ツールや分析ツールでは、Common Data Model スキーマがネイティブに理解されます。</span><span class="sxs-lookup"><span data-stu-id="f62cb-114">AI and analytics tools such as Power BI natively understand the Common Data Model schema.</span></span> <span data-ttu-id="f62cb-115">たとえば、Power BI コネクタを使用して外部データを取り込むとき、ユーザーは発注書、在庫、元帳などの Common Data Model エンティティを使用して宛先にデータを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="f62cb-115">For example, when ingesting external data using Power BI connectors, users can easily store the data in the destination using Common Data Model entities such as Purchase Orders, Inventory, and Ledger.</span></span> <span data-ttu-id="f62cb-116">これにより、ユーザーは、あるエンティティ形式から別の形式へのデータの変換と処理に時間を費やすことなく、複数のソースからのデータを結合するリッチ アプリケーションを作成できます。</span><span class="sxs-lookup"><span data-stu-id="f62cb-116">This enables users to create rich applications that combine data from multiple sources without spending too much time transforming and wrangling data from one entity shape to another.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f62cb-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f62cb-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f62cb-118">テーブルやエンティティを含む Finance and Operations アプリのすべてのデータは、Common Data Model (CDM) で記述されます。</span><span class="sxs-lookup"><span data-stu-id="f62cb-118">All of the data in Finance and Operations apps, including tables and entities, are described in Common Data Model.</span></span> <span data-ttu-id="f62cb-119">これにより、幅広く受け入れられているエンティティの標準セットに宛先データが保存されるため、複数のアプリケーションからのデータを簡単に結合できます。</span><span class="sxs-lookup"><span data-stu-id="f62cb-119">This makes combining data from multiple applications easy because the destination data is stored in a broadly accepted standard set of entities.</span></span>
<!--feature detail end -->









