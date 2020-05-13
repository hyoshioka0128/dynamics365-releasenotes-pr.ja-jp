---
title: Lifecycle Services のデータベース移動 RESTful API
description: 診断やデバッグの目的で、データベースが繰り返し更新されるよう設定できます。
author: relnotes
ms.reviewer: sericks
ms.date: 02/06/2020
ms.assetid: a7c806d6-d5c9-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: d394fcc5b7b7c1517304e266909cb0db9c4d4965
ms.sourcegitcommit: 2928661abcc468748ffc7c33516ebc8e3cd5d653
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/04/2020
ms.locfileid: "3098451"
---
# <a name="database-movement-restful-apis-in-lifecycle-services"></a><span data-ttu-id="c0e7c-103">Lifecycle Services のデータベース移動 RESTful API</span><span class="sxs-lookup"><span data-stu-id="c0e7c-103">Database movement RESTful APIs in Lifecycle Services</span></span>


| <span data-ttu-id="c0e7c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="c0e7c-104">Enabled for</span></span>    |  <span data-ttu-id="c0e7c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="c0e7c-105">Public preview</span></span> | <span data-ttu-id="c0e7c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="c0e7c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="c0e7c-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="c0e7c-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="c0e7c-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c0e7c-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c0e7c-109">2019 年 9 月 30 日</span><span class="sxs-lookup"><span data-stu-id="c0e7c-109">Sep 30, 2019</span></span>| <span data-ttu-id="c0e7c-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="c0e7c-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="c0e7c-111">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="c0e7c-111">Feb 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="c0e7c-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="c0e7c-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="c0e7c-113">平均して、顧客は少なくとも週に 1 回データベース更新のコピー プロセスを使用します。</span><span class="sxs-lookup"><span data-stu-id="c0e7c-113">On average, customers use the database refresh copy process  at least once a week.</span></span>  <span data-ttu-id="c0e7c-114">現在、顧客はセルフサービス アクションを使用して更新をトリガーする必要があります。これは、営業時間中のスタンダード承認テスト環境の可用性に影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="c0e7c-114">Today, customers must use the self-service action to trigger the refresh, which impacts the Standard Acceptance Test environment availability during business hours.</span></span>  <span data-ttu-id="c0e7c-115">RESTful API を使用すると、営業時間外または夜間のビルド プロセスの一部としてアクティビティを実装できます。</span><span class="sxs-lookup"><span data-stu-id="c0e7c-115">RESTful APIs will allow customers to implement the activity during off hours or as part of their nightly build process.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="c0e7c-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="c0e7c-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="c0e7c-117">Lifecycle Services (LCS) は RESTful API エンドポイントを公開します。</span><span class="sxs-lookup"><span data-stu-id="c0e7c-117">Lifecycle Services (LCS) will expose RESTful API endpoints.</span></span> <span data-ttu-id="c0e7c-118">更新をトリガーするための認証方法と適切な呼び出し方法について説明するドキュメントが提供されます。</span><span class="sxs-lookup"><span data-stu-id="c0e7c-118">Documentation that covers how to authenticate and make the appropriate calls to trigger refresh will be provided.</span></span>  <span data-ttu-id="c0e7c-119">Azure Logic Apps またはその他の繰り返しエンジンを使用してこの機能を実行すると、スケジューリングと自動化を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="c0e7c-119">This functionality can be exercised by using Azure Logic Apps or other recurrence engines to provide scheduling and automation.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="c0e7c-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="c0e7c-120">See also</span></span>

<span data-ttu-id="c0e7c-121">[データベース移動 API ](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/database/dbmovement-operations#database-movement-api) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="c0e7c-121">[Database Movement API](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/database/dbmovement-operations#database-movement-api) (docs)</span></span>
