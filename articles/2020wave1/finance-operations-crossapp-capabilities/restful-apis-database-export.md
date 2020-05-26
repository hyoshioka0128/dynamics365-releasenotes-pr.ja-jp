---
title: データベース エクスポート用の RESTful API
description: ''
author: relnotes
ms.reviewer: sericks
ms.date: 04/02/2020
ms.assetid: 487df01a-8e74-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: c5d4768323803a12aa5d9be888aa1e1bf74fccac
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3256795"
---
# <a name="restful-apis-for-database-export"></a><span data-ttu-id="a7d64-102">データベース エクスポート用の RESTful API</span><span class="sxs-lookup"><span data-stu-id="a7d64-102">RESTful APIs for database export</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="a7d64-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="a7d64-103">Enabled for</span></span>    |  <span data-ttu-id="a7d64-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a7d64-104">Public preview</span></span> | <span data-ttu-id="a7d64-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="a7d64-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a7d64-106">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="a7d64-106">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="a7d64-107">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="a7d64-107">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a7d64-108">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a7d64-108">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a7d64-109">当社のデータによると、データベースの更新を実行するお客様の 90% 以上が、そのデータベースをユーザー受け入れテスト (UAT) 環境から資産ライブラリにエクスポートしています。</span><span class="sxs-lookup"><span data-stu-id="a7d64-109">Our data tells us that more than 90 percent of customers who perform a database refresh later export that database from the user acceptance testing (UAT) environment to the asset library.</span></span> <span data-ttu-id="a7d64-110">現在、お客様はセルフサービス アクションを使用してエクスポートをトリガーする必要があります。これには営業時間中の作業を必要とします。</span><span class="sxs-lookup"><span data-stu-id="a7d64-110">Today, customers must use the self-service action to trigger the export, which requires work during business hours.</span></span> <span data-ttu-id="a7d64-111">RESTful API を使用すると、営業時間外または繰り返しのアクティビティを実装できます。</span><span class="sxs-lookup"><span data-stu-id="a7d64-111">RESTful APIs will allow customers to implement the activity during off hours or on recurrence.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a7d64-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a7d64-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a7d64-113">データベースのエクスポートをトリガーする新しい API がドキュメントと共に提供されます。</span><span class="sxs-lookup"><span data-stu-id="a7d64-113">A new API, along with documentation, will be provided to trigger database export.</span></span> <span data-ttu-id="a7d64-114">これにより、運用環境からサンドボックスへの、さらにサンドボックスから資産ライブラリへの、エンドツーエンドの完全な自動化が可能になります。</span><span class="sxs-lookup"><span data-stu-id="a7d64-114">This will allow full end-to-end automation from production to sandbox, and then from sandbox to the asset library.</span></span> <span data-ttu-id="a7d64-115">そこから、既存の API を使用して BACPAC ファイルを開発者マシンにダウンロードすることもできます。</span><span class="sxs-lookup"><span data-stu-id="a7d64-115">From there, customers can also use our existing APIs to download the BACPAC files to their developer machines.</span></span>
<!--feature detail end -->









