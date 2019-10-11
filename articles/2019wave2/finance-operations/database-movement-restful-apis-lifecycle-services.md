---
title: Lifecycle Services のデータベース移動 RESTful API
description: 診断やデバッグの目的で、データベースが繰り返し更新されるよう設定できます。
author: relnotes
ms.reviewer: sericks
ms.date: 09/04/2019
ms.assetid: a7c806d6-d5c9-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: e18a3c3e64b4c02279fb93420efc7cecba7135ef
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143893"
---
# <a name="database-movement-restful-apis-in-lifecycle-services"></a><span data-ttu-id="930e2-103">Lifecycle Services のデータベース移動 RESTful API</span><span class="sxs-lookup"><span data-stu-id="930e2-103">Database movement RESTful APIs in Lifecycle Services</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="930e2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="930e2-104">Enabled for</span></span>    |  <span data-ttu-id="930e2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="930e2-105">Public preview</span></span> | <span data-ttu-id="930e2-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="930e2-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="930e2-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="930e2-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="930e2-108">2019 年 9 月</span><span class="sxs-lookup"><span data-stu-id="930e2-108">Sep 2019</span></span>| <span data-ttu-id="930e2-109">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="930e2-109">Nov 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="930e2-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="930e2-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="930e2-111">平均して、顧客は少なくとも週に 1 回データベース更新のコピー プロセスを使用します。</span><span class="sxs-lookup"><span data-stu-id="930e2-111">On average, customers use the database refresh copy process  at least once a week.</span></span>  <span data-ttu-id="930e2-112">現在、顧客はセルフサービス アクションを使用して更新をトリガーする必要があります。これは、営業時間中のスタンダード承認テスト環境の可用性に影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="930e2-112">Today, customers must use the self-service action to trigger the refresh, which impacts the Standard Acceptance Test environment availability during business hours.</span></span>  <span data-ttu-id="930e2-113">RESTful API を使用すると、営業時間外または夜間のビルド プロセスの一部としてアクティビティを実装できます。</span><span class="sxs-lookup"><span data-stu-id="930e2-113">RESTful APIs will allow customers to implement the activity during off hours or as part of their nightly build process.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="930e2-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="930e2-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="930e2-115">Lifecycle Services (LCS) は RESTful API エンドポイントを公開します。</span><span class="sxs-lookup"><span data-stu-id="930e2-115">Lifecycle Services (LCS) will expose RESTful API endpoints.</span></span> <span data-ttu-id="930e2-116">更新をトリガーするための認証方法と適切な呼び出し方法について説明するドキュメントが提供されます。</span><span class="sxs-lookup"><span data-stu-id="930e2-116">Documentation that covers how to authenticate and make the appropriate calls to trigger refresh will be provided.</span></span>  <span data-ttu-id="930e2-117">この機能は、Azure Logic Apps またはその他の繰り返しエンジンを使用して実行することで、スケジューリングと自動化を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="930e2-117">This functionality can be exercised by using Azure LogicApps or other recurrence engines to provide scheduling and automation.</span></span>
<!--feature detail end -->











