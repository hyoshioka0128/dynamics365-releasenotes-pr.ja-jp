---
title: 顧客データ レイクでの Finance and Operations エンティティ
description: Finance and Operations アプリのエンティティを、独自のデータ レイクで使用できるようになりました。 お客様は、システムがほぼリアルタイムでデータを更新している間に、必要なテーブル エンティティを選択できます。
author: relnotes
ms.reviewer: kfend
ms.date: 04/14/2020
ms.assetid: 5861c499-2fcc-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: milindav
dynamics365pdf: true
ms.openlocfilehash: 38101355b4c2ac757f63d12eed27188d7cf23e8b
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3293392"
---
# <a name="finance-and-operations-entities-in-a-customers-data-lake"></a><span data-ttu-id="1c02e-104">顧客データ レイクでの Finance and Operations エンティティ</span><span class="sxs-lookup"><span data-stu-id="1c02e-104">Finance and Operations entities in a customer's data lake</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="1c02e-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="1c02e-105">Enabled for</span></span>    |  <span data-ttu-id="1c02e-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1c02e-106">Public preview</span></span> | <span data-ttu-id="1c02e-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="1c02e-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="1c02e-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="1c02e-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1c02e-109">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="1c02e-109">Aug 2020</span></span>| <span data-ttu-id="1c02e-110">2020 年 9 月</span><span class="sxs-lookup"><span data-stu-id="1c02e-110">Sep 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1c02e-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1c02e-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1c02e-112">この機能により、お客様は自分のデータベースの持ち込み (BYOD) への依存を減らし、最終的に BYOD の使用を廃止できます。</span><span class="sxs-lookup"><span data-stu-id="1c02e-112">This feature enables customers to reduce their reliance and eventually retire the use of Bring your own database (BYOD).</span></span> <span data-ttu-id="1c02e-113">Azure Data Lake 内のデータ エンティティ定義へのアクセスにより、お客様はダウンストリーム統合を変更せずに BYOD サービスを廃止できます。</span><span class="sxs-lookup"><span data-stu-id="1c02e-113">Access to Data Entity definitions in Azure Data Lake enables customers to retire BYOD service without changing their downstream integrations.</span></span>

<span data-ttu-id="1c02e-114">既存のデータ ウェアハウスを運用データベースに統合していて、Microsoft Dynamics AX 2009 および Dynamics AX 2012 からアップグレードするお客様は、テーブル レベル データへのアクセスとの既存の統合への影響を最小限に抑えながら、Finance and Operations アプリにアップグレードできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="1c02e-114">Customers upgrading from Microsoft Dynamics AX 2009 and Dynamics AX 2012 who have their existing data warehouses integrated into operational databases can now upgrade to Finance and Operations apps with minimal disruptions to their existing integrations with access to Table level data.</span></span> <span data-ttu-id="1c02e-115">エンティティ形式の追加により、ビジネス ユーザーは、基になっているテーブルの定義とリレーションシップを理解しなくても、データを簡単に使用できます。</span><span class="sxs-lookup"><span data-stu-id="1c02e-115">With the addition of Entity shapes, business users can easily consume the data without having to understand underlying table definitions and relationships.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1c02e-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1c02e-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1c02e-117">Dynamics 365 Finance and Operations アプリ内のエンティティは、独自の Azure データ レイク内で利用できるようになり、必要なエンティティを選択できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="1c02e-117">Entities in the Dynamics 365 Finance and Operations apps are now available within your own Azure data lake, allowing you to choose the required entities.</span></span> <span data-ttu-id="1c02e-118">システムにより、基になっているテーブルが識別されて、対応するデータがほぼリアルタイムで更新され続けます。</span><span class="sxs-lookup"><span data-stu-id="1c02e-118">The system identifies the underlying tables and keeps the corresponding data refreshed on a near real-time basis.</span></span> <span data-ttu-id="1c02e-119">データ レイクで利用可能なエンティティ定義メタデータを使用することにより、お客様は Azure Synapse を使用してエンティティ シェイプのクエリを実行できます。</span><span class="sxs-lookup"><span data-stu-id="1c02e-119">By using the Entity definition metadata available in the data lake, customers can query the Entity shape using Azure synapse.</span></span> <span data-ttu-id="1c02e-120">オプションで、お客様はデータ レイク内でエンティティをステージングすることもできます。</span><span class="sxs-lookup"><span data-stu-id="1c02e-120">Optionally, customers can also stage the Entity within the data lake.</span></span>

<span data-ttu-id="1c02e-121">エクスポート ジョブやスケジュールを監視したり、管理したりする必要はなくなりました。</span><span class="sxs-lookup"><span data-stu-id="1c02e-121">There is no need to monitor and manage export jobs or schedules.</span></span> <span data-ttu-id="1c02e-122">パワー ユーザーと開発者は、さまざまなツールと言語を使用して、データフロー、Spark、SQL など、独自のデータ レイク内のデータにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="1c02e-122">Power users and developers can use a variety of tools and languages to access data within their own data lake, including DataFlows, Spark, and SQL.</span></span> <span data-ttu-id="1c02e-123">Azure Synapse を使用することで、SQL ビュー定義としてエンティティ データにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="1c02e-123">By using Azure Synapse, you can get access to entity data as SQL view definitions.</span></span>

> [!NOTE]
> <span data-ttu-id="1c02e-124">この機能は、一部の Azure リージョンおよび環境では上記の日付までに利用可能にならない場合があります。</span><span class="sxs-lookup"><span data-stu-id="1c02e-124">This feature might not be available in all Azure regions and environments by the dates indicated above.</span></span>
<!--feature detail end -->









