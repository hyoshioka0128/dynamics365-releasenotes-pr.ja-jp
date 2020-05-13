---
title: データベース エクスポート用の RESTful API
description: ''
author: relnotes
ms.reviewer: sericks
ms.date: 03/16/2020
ms.assetid: 85c8ade0-7548-ea11-a812-000d3a563be2
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: e155ac34ef9f2fc1ede99ee94db5a7fdbcbf1732
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178441"
---
# <a name="restful-apis-for-database-export"></a><span data-ttu-id="52921-102">データベース エクスポート用の RESTful API</span><span class="sxs-lookup"><span data-stu-id="52921-102">RESTful APIs for database export</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="52921-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="52921-103">Enabled for</span></span>    |  <span data-ttu-id="52921-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="52921-104">Public preview</span></span> | <span data-ttu-id="52921-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="52921-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="52921-106">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="52921-106">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="52921-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="52921-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="52921-108">2020 年 3 月 16 日</span><span class="sxs-lookup"><span data-stu-id="52921-108">Mar 16, 2020</span></span>| <span data-ttu-id="52921-109">近日発表</span><span class="sxs-lookup"><span data-stu-id="52921-109">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="52921-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="52921-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="52921-111">当社のデータによると、データベースの更新を実行するお客様の 90% 以上が、そのデータベースをユーザー受け入れテスト (UAT) 環境から資産ライブラリにエクスポートしています。</span><span class="sxs-lookup"><span data-stu-id="52921-111">Our data tells us that more than 90% of customers who perform a database refresh later export that database from the user acceptance testing (UAT) environment to the asset library.</span></span> <span data-ttu-id="52921-112">現在、お客様はセルフサービス アクションを使用してエクスポートをトリガーする必要があります。これには営業時間中の作業を必要とします。</span><span class="sxs-lookup"><span data-stu-id="52921-112">Today, customers must use the self-service action to trigger the export, which requires work during business hours.</span></span> <span data-ttu-id="52921-113">RESTful API を使用すると、営業時間外または繰り返しのアクティビティを実装できます。</span><span class="sxs-lookup"><span data-stu-id="52921-113">RESTful APIs will allow customers to implement the activity during off hours or on recurrence.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="52921-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="52921-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="52921-115">データベースのエクスポートをトリガーする新しい API がドキュメントと共に提供されます。</span><span class="sxs-lookup"><span data-stu-id="52921-115">A new API, along with documentation, will be provided to trigger database export.</span></span> <span data-ttu-id="52921-116">これにより、運用環境からサンドボックスへの、さらにサンドボックスから資産ライブラリへの、エンドツーエンドの完全な自動化が可能になります。</span><span class="sxs-lookup"><span data-stu-id="52921-116">This will allow full end-to-end automation from production to sandbox, and then from sandbox to the asset library.</span></span> <span data-ttu-id="52921-117">そこから、既存の API を使用して BACPAC ファイルを開発者マシンにダウンロードすることもできます。</span><span class="sxs-lookup"><span data-stu-id="52921-117">From there, customers can also use our existing APIs to download the BACPAC files to their developer machines.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="52921-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="52921-118">See also</span></span>

<span data-ttu-id="52921-119">[データベース エクスポートの作成 v1](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/database/api/v1/reference-create-export) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="52921-119">[Create database export v1](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/database/api/v1/reference-create-export) (docs)</span></span>
