---
title: IoT インテリジェンス コア分析情報
description: IoT インテリジェンス
author: relnotes
ms.reviewer: kamaybac
ms.date: 06/25/2020
ms.assetid: 4e6de49f-8acb-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: dabourq
dynamics365pdf: true
ms.openlocfilehash: 2e8124a98fb680bd5f7784f86bf47655818bc777
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3522607"
---
# <a name="iot-intelligence-core-insights"></a><span data-ttu-id="d0993-103">IoT インテリジェンス コア分析情報</span><span class="sxs-lookup"><span data-stu-id="d0993-103">IoT intelligence core insights</span></span>


| <span data-ttu-id="d0993-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="d0993-104">Enabled for</span></span>    |  <span data-ttu-id="d0993-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d0993-105">Public preview</span></span> | <span data-ttu-id="d0993-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="d0993-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d0993-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="d0993-107">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="d0993-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="d0993-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="d0993-109">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="d0993-109">Apr 15, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="d0993-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d0993-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d0993-111">モノのインターネット (IoT) インテリジェンスでは、次のコア分析情報とアクション シナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="d0993-111">Internet of things (IoT) intelligence supports the following core insights and action scenarios:</span></span>

 - <span data-ttu-id="d0993-112">**遅延注文**: 遅延している製造オーダーの管理に対する通知サービスとアクションを提供します。</span><span class="sxs-lookup"><span data-stu-id="d0993-112">**Delayed orders**: Provides notification services and actions for managing delayed production orders.</span></span> <span data-ttu-id="d0993-113">影響を受ける操作を表示します。</span><span class="sxs-lookup"><span data-stu-id="d0993-113">Displays impacted operations.</span></span> <span data-ttu-id="d0993-114">リソースと製品の組み合わせに対する注文遅延の指標を定義する機能をユーザーに提供し、こうしたしきい値で例外が発生したときにユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="d0993-114">Provides users with the ability to define order-delay metrics for combinations of resources and products, and notifies users when exceptions to these thresholds occur.</span></span> <span data-ttu-id="d0993-115">ユーザーは、影響の表示やメンテナンス要求の作成など、遅延した注文に関連するビジネス アクションを実行できます。</span><span class="sxs-lookup"><span data-stu-id="d0993-115">Enables users to take relevant business actions for delayed orders, including the ability to view impact or create a maintenance request.</span></span> 
 - <span data-ttu-id="d0993-116">**設備の故障**: 設備の故障の管理シナリオの通知サービスとアクションを提供します。</span><span class="sxs-lookup"><span data-stu-id="d0993-116">**Equipment down**: Provides notification services and actions for managing equipment-down scenarios.</span></span> <span data-ttu-id="d0993-117">影響を受ける操作を表示します。</span><span class="sxs-lookup"><span data-stu-id="d0993-117">Displays impacted operations.</span></span> <span data-ttu-id="d0993-118">機械の故障しきい値に対する指標を定義する機能をユーザーに提供し、こうしたしきい値で例外が発生したときにユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="d0993-118">Provides users with the ability to define metrics for machine-down thresholds and notifies users when an exception to these thresholds occurs.</span></span> <span data-ttu-id="d0993-119">またユーザーは、影響の表示やメンテナンス作業指示書の作成など、遅延した注文に関連するビジネス アクションを実行できます。</span><span class="sxs-lookup"><span data-stu-id="d0993-119">Enables users to take relevant business actions for delayed orders, including the ability to view impact or create a maintenance work order.</span></span> 
 - <span data-ttu-id="d0993-120">**品質異常**: 品質異常の管理のための通知サービスとアクションを提供します。</span><span class="sxs-lookup"><span data-stu-id="d0993-120">**Quality anomaly**: Provides notification services and actions for managing quality anomalies.</span></span> <span data-ttu-id="d0993-121">ユーザーが、製品の品質属性を定義して、こうした属性に例外が発生した場合に通知を受け取る機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="d0993-121">Provides users with the ability to define quality attributes for products and get notified when exceptions to these attributes occur.</span></span> 

<span data-ttu-id="d0993-122">シームレスなオンボード エクスペリエンス:</span><span class="sxs-lookup"><span data-stu-id="d0993-122">Seamless onboarding experience:</span></span>

 - <span data-ttu-id="d0993-123">**コード不要の機能**: 機器を IoT インテリジェンス サービスに接続するコード不要の高速なメソッドをユーザーに提供して、実用的な分析情報を利用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="d0993-123">**No-code capability**: Provides a fast, code-free method for users to connect their machines to IoT intelligence service and get started with actionable insights.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="d0993-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="d0993-124">See also</span></span>

<!--docs start-->
<span data-ttu-id="d0993-125">[IoT インテリジェンスのホーム ページ](https://docs.microsoft.com/dynamics365/supply-chain/iot/iot-intelligence-home-page) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="d0993-125">[IoT Intelligence home page](https://docs.microsoft.com/dynamics365/supply-chain/iot/iot-intelligence-home-page) (docs)</span></span>
<!--docs end-->
