---
title: データとプロセスの統合
description: 独自の Azure Data Lake Storage Gen2 データ レイクですべてのデータが利用可能
author: relnotes
ms.reviewer: ''
ms.date: 03/12/2020
ms.assetid: e83944e6-75c8-e911-a968-000d3a4f3883
ms.topic: structure
ms.service: business-applications
ms.author: robadawy
dynamics365pdf: true
ms.openlocfilehash: c5595a26d166f79fc4bd7066c31348dc6725c23c
ms.sourcegitcommit: f7b958b02d7cb7543a3f81414e7b3e62a5b8539d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2020
ms.locfileid: "3158233"
---
# <a name="data-and-process-integration"></a><span data-ttu-id="2397f-103">データとプロセスの統合</span><span class="sxs-lookup"><span data-stu-id="2397f-103">Data and process integration</span></span>

[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

<!--structure start-->
## <a name="finance-and-operations-data-in-azure-data-lake-storage-gen2"></a><span data-ttu-id="2397f-104">Azure Data Lake Storage Gen2 での Finance and Operations データ</span><span class="sxs-lookup"><span data-stu-id="2397f-104">Finance and Operations data in Azure Data Lake Storage Gen2</span></span>

<span data-ttu-id="2397f-105">Dynamics AX 2012 以前を使用しているオンプレミスのお客様は、これまでデータに直接アクセスすることができました。これらのお客様は、データに直接アクセスし、Power BI などのツールでレポートを作成することに慣れている可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2397f-105">On-premises customers in Dynamics AX 2012 and earlier had direct access to data—you might be accustomed to accessing data directly and creating reports with tools such as Power BI.</span></span> <span data-ttu-id="2397f-106">お客様は、Finance and Operations に移行し、クラウドでのデジタル変革を開始するにあたって、少なくともしばらくの間は、レポートやデータ ウェアハウスに関連する既存の資産を維持したいと考える可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2397f-106">As you migrate to Finance and Operations apps and begin your digital transformation journey in the cloud, you might want to keep your existing reports and data warehouse investments, at least for the near future.</span></span> <span data-ttu-id="2397f-107">Microsoft では、すべてのデータにアクセスできるようにすることで、お客様がクラウドに簡単に移行できるようにしたいと考えています。</span><span class="sxs-lookup"><span data-stu-id="2397f-107">We want to enable your transition to the cloud easily by enabling access to all data.</span></span> <span data-ttu-id="2397f-108">Finance and Operations アプリで定義された中核的なテーブル、データ エンティティ、および集計測定は、お客様のデータ レイク (Data Lake Storage Gen2) でも利用可能になります。</span><span class="sxs-lookup"><span data-stu-id="2397f-108">Core tables, data entities as well as aggregate measurements defined in Finance and Operations apps will be available in your own data lake (Data Lake Storage Gen2).</span></span> 

<span data-ttu-id="2397f-109">管理者は、使いやすいインターフェイスを使用して、データ レイクを Finance and Operations アプリで構成できます。</span><span class="sxs-lookup"><span data-stu-id="2397f-109">With an easy-to-use interface, an administrator can configure a data lake with Finance and Operations apps.</span></span> <span data-ttu-id="2397f-110">データの更新は Microsoft によって管理されます。テーブル、エンティティ、および集計測定は、パワー ユーザーが選択できます。</span><span class="sxs-lookup"><span data-stu-id="2397f-110">Microsoft manages data refresh—a power user can choose tables, entities, and aggregate measurements.</span></span> <span data-ttu-id="2397f-111">データは更新され、最新の状態に保たれます。お客様がエクスポート スケジュールを管理する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="2397f-111">The data is refreshed and kept up to date—you don't need to manage export schedules.</span></span> 

<span data-ttu-id="2397f-112">中核的なテーブル、エンティティ、集計測定は、さまざまな属性、定義、リレーションシップとともに Common Data Model で定義されます。</span><span class="sxs-lookup"><span data-stu-id="2397f-112">Core tables, entities, and aggregate measurements are defined in the Common Data Model along with rich attributes, definitions, and relationships.</span></span> <span data-ttu-id="2397f-113">データ レイクにエクスポートされるデータは、Common Data Model で記述されます。</span><span class="sxs-lookup"><span data-stu-id="2397f-113">Data exported to the data lake is described in the Common Data Model.</span></span> <span data-ttu-id="2397f-114">Data Lake Storage Gen2 のデータ構造は、Common Data Model のデータ定義の構成を反映したものとなります。</span><span class="sxs-lookup"><span data-stu-id="2397f-114">The data structure in Data Lake Storage Gen2 mirrors the organization of data definitions in the Common Data Model.</span></span> <span data-ttu-id="2397f-115">Data Lake Storage に格納されるデータは、Common Data Model の言語仕様で定義されたメタデータを使用して記述されます。</span><span class="sxs-lookup"><span data-stu-id="2397f-115">Data stored in Data Lake Storage is described using metadata as defined by the Common Data Model language specification.</span></span> <span data-ttu-id="2397f-116">これにより、既存のツールでデータのセマンティクスとリレーションシップを解釈できるようになり、データ レイクのデータを処理できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2397f-116">This enables existing tools to understand data semantics and relationships—they light up with data in the data lake.</span></span> 

<span data-ttu-id="2397f-117">Data Lake Storage Gen2 のテーブル、エンティティ、および集計測定が一般提供になることで、お客様は Data Lake Storage Gen2 をレポートやダウンストリーム統合のデータソースとして使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2397f-117">With the General Availability of tables, entities, and aggregate measurements in Data Lake Storage Gen2, you can use Data Lake Storage Gen2 as the source of data for reporting and downstream integrations.</span></span> <span data-ttu-id="2397f-118">現在、自分のデータベースの持ち込み (BYOD) を使用して Finance and Operations からデータをエクスポートしている場合は、Data Lake Storage Gen2 に移行することができます。お客様は、自分でデータをエクスポートすることなく、Data Lake Storage Gen2 に既に存在するデータを使用できます。</span><span class="sxs-lookup"><span data-stu-id="2397f-118">If you are currently using Bring your own database (BYOD) to export data from Finance and Operations, you can transition to Data Lake Storage Gen2—no need to export data on your own, you can use data already present in Data Lake Storage Gen2.</span></span>
<!--structure end-->



