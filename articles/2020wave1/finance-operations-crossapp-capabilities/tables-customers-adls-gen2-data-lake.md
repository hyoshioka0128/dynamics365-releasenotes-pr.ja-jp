---
title: 顧客の Data Lake Storage Gen2 データ レイク内のテーブル
description: Dynamics 365 Finance and Operations アプリのテーブルが、独自の Azure Data Lake で使用できるようになりました。 顧客は、システムがほぼリアルタイムでデータを更新している間に、必要なテーブルを選択できます。
author: relnotes
ms.reviewer: kfend
ms.date: 06/17/2020
ms.assetid: 0c193363-efc9-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: milindav
dynamics365pdf: true
ms.openlocfilehash: 37d33fbdd0892922d8040c31dd8971fb0bc80546
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3488529"
---
# <a name="tables-in-a-customers-data-lake-storage-gen2-data-lake"></a><span data-ttu-id="6b7a1-104">顧客の Data Lake Storage Gen2 データ レイク内のテーブル</span><span class="sxs-lookup"><span data-stu-id="6b7a1-104">Tables in a customer's Data Lake Storage Gen2 data lake</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="6b7a1-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="6b7a1-105">Enabled for</span></span>    |  <span data-ttu-id="6b7a1-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6b7a1-106">Public preview</span></span> | <span data-ttu-id="6b7a1-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="6b7a1-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6b7a1-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="6b7a1-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="6b7a1-109">2020 年 9 月</span><span class="sxs-lookup"><span data-stu-id="6b7a1-109">Sep 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="6b7a1-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="6b7a1-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="6b7a1-111">独自のデータ レイクでデータがすぐに利用できるときは、独自の Azure SQL Database にデータをエクスポートする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="6b7a1-111">Exporting data to your own Azure SQL Database isn't needed when the data is readily available in your own data lake.</span></span> <span data-ttu-id="6b7a1-112">この機能により、お客様は**自分のデータベースの持ち込み (BYOD)** 機能への依存を減らし、最終的に BYOD の使用を廃止できます。</span><span class="sxs-lookup"><span data-stu-id="6b7a1-112">This feature enables customers to reduce their reliance on **Bring your own database (BYOD)** functionality and to eventually retire the use of it.</span></span> 

<span data-ttu-id="6b7a1-113">既存のデータ ウェアハウスを運用データベースに統合している、Dynamics AX 2009 および Dynamics AX 2012 からアップグレードするお客様は、既存の統合への影響を最小限に抑えながら、Finance and Operations アプリにアップグレードできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="6b7a1-113">Customers who upgrade from Dynamics AX 2009 and Dynamics AX 2012 who have their existing data warehouses integrated into an operational database can now upgrade to Finance and Operations apps with minimal disruptions to their existing integrations.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="6b7a1-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6b7a1-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6b7a1-115">Finance and Operations アプリのテーブルが、独自の Azure Data Lake で使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="6b7a1-115">Tables in the Finance and Operations apps are now available in your own Azure Data Lake.</span></span> <span data-ttu-id="6b7a1-116">システムがほぼリアルタイムでデータを更新している間に、必要なテーブルを選択できます。</span><span class="sxs-lookup"><span data-stu-id="6b7a1-116">You can select the required tables while the system keeps the data refreshed on a near real-time basis.</span></span> <span data-ttu-id="6b7a1-117">エクスポート ジョブやスケジュールを監視したり、管理したりする必要はなくなりました。</span><span class="sxs-lookup"><span data-stu-id="6b7a1-117">There is no need to monitor and manage export jobs or schedules.</span></span> <span data-ttu-id="6b7a1-118">パワー ユーザーと開発者は、さまざまなツールと言語を使用して、データフロー、Spark、SQL など、独自のデータ レイク内のデータにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="6b7a1-118">Power users and developers can use a variety of tools and languages to access data within their own Data Lake, including DataFlows, Spark, and SQL.</span></span>

> [!NOTE]
> <span data-ttu-id="6b7a1-119">この機能は、一部の Azure リージョンおよび環境では上記の日付までに利用可能にならない場合があります。</span><span class="sxs-lookup"><span data-stu-id="6b7a1-119">This feature may not be available in all Azure regions and environments by the dates indicated above.</span></span> <span data-ttu-id="6b7a1-120">詳細については、ドキュメントを参照してください。</span><span class="sxs-lookup"><span data-stu-id="6b7a1-120">Please refer to documentation for availability information.</span></span>
<!--feature detail end -->









