---
title: データベース エクスポート用の RESTful API
description: データベースのエクスポートをトリガーする新しい API がドキュメントと共に提供されます。 これにより、運用環境からサンドボックスへの、さらにサンドボックスから資産ライブラリへの、エンドツーエンドの完全な自動化が可能になります。 そこから、既存の API を使用して BACPAC ファイルを開発者マシンにダウンロードすることもできます。
author: relnotes
ms.reviewer: sericks
ms.date: 06/05/2020
ms.assetid: 487df01a-8e74-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: 163ffc45c4c35b31ba446a95fc8d9599135ce84f
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3441592"
---
# <a name="restful-apis-for-database-export"></a><span data-ttu-id="dd3cc-105">データベース エクスポート用の RESTful API</span><span class="sxs-lookup"><span data-stu-id="dd3cc-105">RESTful APIs for database export</span></span>


| <span data-ttu-id="dd3cc-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="dd3cc-106">Enabled for</span></span>    |  <span data-ttu-id="dd3cc-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="dd3cc-107">Public preview</span></span> | <span data-ttu-id="dd3cc-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="dd3cc-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="dd3cc-109">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="dd3cc-109">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="dd3cc-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="dd3cc-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="dd3cc-111">2020 年 5 月 30 日</span><span class="sxs-lookup"><span data-stu-id="dd3cc-111">May 30, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="dd3cc-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="dd3cc-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="dd3cc-113">当社のデータによると、データベースの更新を実行するお客様の 90% 以上が、そのデータベースをユーザー受け入れテスト (UAT) 環境から資産ライブラリにエクスポートしています。</span><span class="sxs-lookup"><span data-stu-id="dd3cc-113">Our data tells us that more than 90 percent of customers who perform a database refresh later export that database from the user acceptance testing (UAT) environment to the asset library.</span></span> <span data-ttu-id="dd3cc-114">現在、お客様はセルフサービス アクションを使用してエクスポートをトリガーする必要があります。これには営業時間中の作業を必要とします。</span><span class="sxs-lookup"><span data-stu-id="dd3cc-114">Today, customers must use the self-service action to trigger the export, which requires work during business hours.</span></span> <span data-ttu-id="dd3cc-115">RESTful API を使用すると、営業時間外または繰り返しのアクティビティを実装できます。</span><span class="sxs-lookup"><span data-stu-id="dd3cc-115">RESTful APIs will allow customers to implement the activity during off hours or on recurrence.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="dd3cc-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="dd3cc-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="dd3cc-117">データベースのエクスポートをトリガーする新しい API がドキュメントと共に提供されます。</span><span class="sxs-lookup"><span data-stu-id="dd3cc-117">A new API, along with documentation, will be provided to trigger database export.</span></span> <span data-ttu-id="dd3cc-118">これにより、運用環境からサンドボックスへの、さらにサンドボックスから資産ライブラリへの、エンドツーエンドの完全な自動化が可能になります。</span><span class="sxs-lookup"><span data-stu-id="dd3cc-118">This will allow full end-to-end automation from production to sandbox, and then from sandbox to the asset library.</span></span> <span data-ttu-id="dd3cc-119">そこから、既存の API を使用して BACPAC ファイルを開発者マシンにダウンロードすることもできます。</span><span class="sxs-lookup"><span data-stu-id="dd3cc-119">From there, customers can also use our existing APIs to download the BACPAC files to their developer machines.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="dd3cc-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="dd3cc-120">See also</span></span>

<!--docs start-->
<span data-ttu-id="dd3cc-121">[データベース エクスポートの作成](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/database/api/v1/reference-create-export) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="dd3cc-121">[Create a database export](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/database/api/v1/reference-create-export) (docs)</span></span>
<!--docs end-->
