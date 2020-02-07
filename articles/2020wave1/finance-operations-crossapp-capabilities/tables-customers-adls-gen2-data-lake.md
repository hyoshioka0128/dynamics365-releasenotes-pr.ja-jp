---
title: 顧客の Data Lake Storage Gen2 データ レイク内のテーブル
description: Finance and Operations アプリのテーブルが、独自の Azure データ レイクで使用できるようになりました。 顧客は、システムがほぼリアルタイムでデータを更新している間に、必要なテーブルを選択できます。
author: relnotes
ms.reviewer: kfend
ms.date: 12/16/2019
ms.assetid: 0c193363-efc9-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: milindav
dynamics365pdf: true
ms.openlocfilehash: d774e776577c3e6d587bb74f447e8045dc6dc832
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986715"
---
# <a name="tables-in-a-customers-data-lake-storage-gen2-data-lake"></a><span data-ttu-id="c9977-104">顧客の Data Lake Storage Gen2 データ レイク内のテーブル</span><span class="sxs-lookup"><span data-stu-id="c9977-104">Tables in a customer's Data Lake Storage Gen2 data lake</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="c9977-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="c9977-105">Enabled for</span></span>    |  <span data-ttu-id="c9977-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c9977-106">Public preview</span></span> | <span data-ttu-id="c9977-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="c9977-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c9977-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c9977-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c9977-109">2020 年 3 月</span><span class="sxs-lookup"><span data-stu-id="c9977-109">Mar 2020</span></span>| <span data-ttu-id="c9977-110">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="c9977-110">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c9977-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c9977-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c9977-112">独自のデータ レイクでデータがすぐに利用できるときは、独自の Azure SQL Database にデータをエクスポートする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="c9977-112">Exporting data to your own Azure SQL Database isn't needed when the data is readily available in your own data lake.</span></span> <span data-ttu-id="c9977-113">この機能により、顧客は自分のデータベースの持ち込み (BYOD) への依存を減らし、最終的に BYOD の使用を廃止できます。</span><span class="sxs-lookup"><span data-stu-id="c9977-113">This feature enables customers to reduce their reliance on Bring your own database (BYOD) and to eventually retire the use of BYOD.</span></span> 

<span data-ttu-id="c9977-114">既存のデータ ウェアハウスを運用データベースに統合している、Dynamics AX 2009 および Dynamics AX 2012 からアップグレードするお客様は、既存の統合への影響を最小限に抑えながら、Finance and Operations アプリにアップグレードできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c9977-114">Customers upgrading from Dynamics AX 2009 and Dynamics AX 2012 who have their existing data warehouses integrated into an operational database can now upgrade to Finance and Operations apps with minimal disruptions to their existing integrations.</span></span>

<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c9977-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c9977-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c9977-116">Finance and Operations アプリのテーブルが、独自の Azure データ レイクで使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c9977-116">Tables in the Finance and Operations apps are now available within your own Azure data lake.</span></span> <span data-ttu-id="c9977-117">顧客は、システムがほぼリアルタイムでデータを更新している間に、必要なテーブルを選択できます。</span><span class="sxs-lookup"><span data-stu-id="c9977-117">Customers can choose the required tables while the system keeps the data refreshed on a near real-time basis.</span></span> <span data-ttu-id="c9977-118">エクスポート ジョブやスケジュールを監視したり、管理したりする必要はなくなりました。</span><span class="sxs-lookup"><span data-stu-id="c9977-118">There is no need to monitor and manage export jobs or schedules.</span></span> <span data-ttu-id="c9977-119">パワー ユーザーと開発者は、さまざまなツールと言語を使用して、データフロー、Spark、SQL など、独自のデータ レイク内のデータにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="c9977-119">Power users and developers can use a variety of tools and languages to access data within their own data lake, including DataFlows, Spark, and SQL.</span></span>
<!--feature detail end -->









