---
title: 顧客データ レイクでの Finance and Operations エンティティ
description: Finance and Operations アプリのエンティティを、独自のデータ レイクで使用できるようになりました。 お客様は、システムがほぼリアルタイムでデータを更新している間に、必要なテーブル エンティティを選択できます。
author: relnotes
ms.reviewer: kfend
ms.date: 03/31/2020
ms.assetid: 5861c499-2fcc-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: milindav
dynamics365pdf: true
ms.openlocfilehash: e047dea0ca15a86fff2d3bac2ef3f44c7e88dbea
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219383"
---
# <a name="finance-and-operations-entities-in-a-customers-data-lake"></a><span data-ttu-id="c2e3a-104">顧客データ レイクでの Finance and Operations エンティティ</span><span class="sxs-lookup"><span data-stu-id="c2e3a-104">Finance and Operations entities in a customer's data lake</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="c2e3a-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="c2e3a-105">Enabled for</span></span>    |  <span data-ttu-id="c2e3a-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c2e3a-106">Public preview</span></span> | <span data-ttu-id="c2e3a-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="c2e3a-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c2e3a-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c2e3a-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c2e3a-109">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="c2e3a-109">Aug 2020</span></span>| <span data-ttu-id="c2e3a-110">2020 年 9 月</span><span class="sxs-lookup"><span data-stu-id="c2e3a-110">Sep 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c2e3a-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c2e3a-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c2e3a-112">独自のデータ レイクでデータがすぐに利用できるのに、なぜ独自の Azure SQL Database にデータをエクスポートするのでしょうか。</span><span class="sxs-lookup"><span data-stu-id="c2e3a-112">Why export data to your own Azure SQL Database when the data is readily available in your own data lake?</span></span> <span data-ttu-id="c2e3a-113">この機能により、顧客は自分のデータベースの持ち込み (BYOD) への依存を減らし、最終的に BYOD の使用を廃止できます。</span><span class="sxs-lookup"><span data-stu-id="c2e3a-113">This feature enables customers to reduce their reliance on Bring your own database (BYOD) and eventually retire the use of BYOD.</span></span> <span data-ttu-id="c2e3a-114">Azure Data Lake 内のデータ エンティティ定義にアクセスできることにより、お客様はダウンストリーム統合を変更せずに BYOD サービスを廃止できます。</span><span class="sxs-lookup"><span data-stu-id="c2e3a-114">Having access to Data Entity definitions in Azure Data Lake enables customers to retire BYOD service without changing their downstream integrations.</span></span>

<span data-ttu-id="c2e3a-115">既存のデータ ウェアハウスを運用データベースに統合していて、Microsoft Dynamics AX 2009 および Dynamics AX 2012 からアップグレードするお客様は、テーブル レベル データへのアクセスとの既存の統合への影響を最小限に抑えながら、Finance and Operations アプリにアップグレードできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c2e3a-115">Customers upgrading from Microsoft Dynamics AX 2009 and Dynamics AX 2012 who have their existing data warehouses integrated into operational databases can now upgrade to Finance and Operations apps with minimal disruptions to their existing integrations with access to Table level data.</span></span> <span data-ttu-id="c2e3a-116">エンティティ形式の追加により、ビジネス ユーザーは、基になっているテーブルの定義とリレーションシップを理解しなくても、データを簡単に使用できます。</span><span class="sxs-lookup"><span data-stu-id="c2e3a-116">With the addition of Entity shapes, business users can easily consume the data without having to understand underlying table definitions and relationships.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c2e3a-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c2e3a-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c2e3a-118">Finance and Operations アプリのエンティティを、独自の Azure データ レイクで使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c2e3a-118">Entities in the Finance and Operations apps are now available within your own Azure data lake.</span></span> <span data-ttu-id="c2e3a-119">お客様は必要なエンティティを選択できます。</span><span class="sxs-lookup"><span data-stu-id="c2e3a-119">Customer can choose the required entities.</span></span> <span data-ttu-id="c2e3a-120">システムにより、基になっているテーブルが識別されて、対応するデータがほぼリアルタイムで更新され続けます。</span><span class="sxs-lookup"><span data-stu-id="c2e3a-120">The system identifies the underlying tables and keeps the corresponding data refreshed on a near real-time basis.</span></span> <span data-ttu-id="c2e3a-121">エクスポート ジョブやスケジュールを監視したり、管理したりする必要はなくなりました。</span><span class="sxs-lookup"><span data-stu-id="c2e3a-121">There is no need to monitor and manage export jobs or schedules.</span></span> <span data-ttu-id="c2e3a-122">パワー ユーザーと開発者は、さまざまなツールと言語を使用して、データフロー、Spark、SQL など、独自のデータ レイク内のデータにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="c2e3a-122">Power users and developers can use a variety of tools and languages to access data within their own data lake, including DataFlows, Spark, and SQL.</span></span> <span data-ttu-id="c2e3a-123">Azure Synapse を使用することで、SQL ビュー定義としてエンティティ データにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="c2e3a-123">By using Azure Synapse, you can get access to entity data as SQL view definitions.</span></span>
<!--feature detail end -->









