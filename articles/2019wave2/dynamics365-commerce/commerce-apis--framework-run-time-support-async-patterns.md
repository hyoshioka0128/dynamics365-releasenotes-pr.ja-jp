---
title: Commerce API - 非同期パターンのフレームワークとランタイムのサポート
description: Commerce API フレームワークは、Commerce が要求する拡張機能の非同期実行をサポートするように強化されました。 このフレームワークの機能強化の前は、要求は同期的にのみ実行できました。 長時間の操作 (I/O 操作、データベース クエリ、ネットワーク要求など) は、実行スレッドをブロックします。 Commerce Runtime に非同期モデルのサポートを追加すると、このような操作の非同期バージョンを使用できるようになるため、実行スレッドのブロックが解除されます。 Commerce API フレームワークでは、拡張要求が非同期で実行されるように非同期/待機モデルがサポートされるため、一部の作業を並列に実行する必要がある場合のビジネス ロジックを簡素化できます。
author: mugunthanm
ms.reviewer: rhaertle
ms.date: 04/14/2020
ms.assetid: 98bace36-044d-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 1d7da74c4db4af2b42d31462607dcb17c0a8b894
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320470"
---
# <a name="commerce-apis--framework-and-run-time-support-for-async-patterns"></a><span data-ttu-id="652f1-107">Commerce API - 非同期パターンのフレームワークとランタイムのサポート</span><span class="sxs-lookup"><span data-stu-id="652f1-107">Commerce APIs – Framework and run-time support for Async patterns</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="652f1-108">有効対象</span><span class="sxs-lookup"><span data-stu-id="652f1-108">Enabled for</span></span>    |  <span data-ttu-id="652f1-109">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="652f1-109">Public preview</span></span> | <span data-ttu-id="652f1-110">一般提供</span><span class="sxs-lookup"><span data-stu-id="652f1-110">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="652f1-111">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="652f1-111">End users, automatically</span></span>|<span data-ttu-id="652f1-112">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="652f1-112">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="652f1-113">2020 年 3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="652f1-113">Mar 31, 2020</span></span>| <span data-ttu-id="652f1-114">近日発表</span><span class="sxs-lookup"><span data-stu-id="652f1-114">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="652f1-115">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="652f1-115">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="652f1-116">この機能により、Commerce Runtime フレームワーク、Retail サーバー コントローラー、およびデータベース アクセスの非同期/待機プログラミング モデルがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="652f1-116">This feature provides support for an async/await programming model for the Commerce Runtime framework, Retail Server controllers, and Database access.</span></span> <span data-ttu-id="652f1-117">これにより、開発者は、高負荷時のパフォーマンス結果の向上を実現し、ビジネス ロジックの一部を並列に実行できる場合に実行時間を短縮できます。</span><span class="sxs-lookup"><span data-stu-id="652f1-117">This will allow developers to achieve higher performance results during high loads, and faster execution time when parts of the business logic can be executed in parallel.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="652f1-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="652f1-118">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="652f1-119">Commerce API フレームワークは、拡張機能の非同期実行をサポートするように強化されました。</span><span class="sxs-lookup"><span data-stu-id="652f1-119">The Commerce API framework has been enhanced to support asynchronous execution of extensions.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="652f1-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="652f1-120">See also</span></span>

<!--docs start-->
<span data-ttu-id="652f1-121">[ビジネス ロジックでの非同期 Commerce CRT API の作成](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/async-commerce-extension) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="652f1-121">[Create asynchronous Commerce CRT APIs in your business logic](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/async-commerce-extension) (docs)</span></span>
<!--docs end-->
