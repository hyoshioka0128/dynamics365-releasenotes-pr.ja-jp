---
title: IoT インテリジェンス コア分析情報
description: ''
author: relnotes
ms.reviewer: kamaybac
ms.date: 03/04/2020
ms.assetid: 4e6de49f-8acb-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: dabourq
dynamics365pdf: true
ms.openlocfilehash: 4104f2b2f3f1cc7012f1a42d85c0d7a9633ba815
ms.sourcegitcommit: 99f8fe366e70064e41204f9ee5c16fe397396d16
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/10/2020
ms.locfileid: "3114866"
---
# <a name="iot-intelligence-core-insights"></a><span data-ttu-id="8b631-102">IoT インテリジェンス コア分析情報</span><span class="sxs-lookup"><span data-stu-id="8b631-102">IoT intelligence core insights</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="8b631-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="8b631-103">Enabled for</span></span>    |  <span data-ttu-id="8b631-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="8b631-104">Public preview</span></span> | <span data-ttu-id="8b631-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="8b631-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="8b631-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="8b631-106">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="8b631-107">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="8b631-107">Apr 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="8b631-108">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="8b631-108">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="8b631-109">モノのインターネット (IoT) インテリジェンスでは、次のコア分析情報とアクション シナリオがサポートされます。</span><span class="sxs-lookup"><span data-stu-id="8b631-109">Internet of things (IoT) intelligence supports the following core insights and action scenarios:</span></span>

 - <span data-ttu-id="8b631-110">**遅延注文**: 遅延している製造オーダーの管理に対する通知サービスとアクションを提供します。</span><span class="sxs-lookup"><span data-stu-id="8b631-110">**Delayed orders**: Provides notification services and actions for managing delayed production orders.</span></span> <span data-ttu-id="8b631-111">影響を受ける操作を表示します。</span><span class="sxs-lookup"><span data-stu-id="8b631-111">Displays impacted operations.</span></span> <span data-ttu-id="8b631-112">リソースと製品の組み合わせに対する注文遅延の指標を定義する機能をユーザーに提供し、こうしたしきい値で例外が発生したときにユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="8b631-112">Provides users with the ability to define order-delay metrics for combinations of resources and products, and notifies users when exceptions to these thresholds occur.</span></span> <span data-ttu-id="8b631-113">ユーザーは、影響の表示やメンテナンス要求の作成など、遅延した注文に関連するビジネス アクションを実行できます。</span><span class="sxs-lookup"><span data-stu-id="8b631-113">Enables users to take relevant business actions for delayed orders, including the ability to view impact or create a maintenance request.</span></span> 
 - <span data-ttu-id="8b631-114">**設備の故障**: 設備の故障の管理シナリオの通知サービスとアクションを提供します。</span><span class="sxs-lookup"><span data-stu-id="8b631-114">**Equipment down**: Provides notification services and actions for managing equipment-down scenarios.</span></span> <span data-ttu-id="8b631-115">影響を受ける操作を表示します。</span><span class="sxs-lookup"><span data-stu-id="8b631-115">Displays impacted operations.</span></span> <span data-ttu-id="8b631-116">機械の故障しきい値に対する指標を定義する機能をユーザーに提供し、こうしたしきい値で例外が発生したときにユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="8b631-116">Provides users with the ability to define metrics for machine-down thresholds and notifies users when an exception to these thresholds occurs.</span></span> <span data-ttu-id="8b631-117">またユーザーは、影響の表示やメンテナンス作業指示書の作成など、遅延した注文に関連するビジネス アクションを実行できます。</span><span class="sxs-lookup"><span data-stu-id="8b631-117">Enables users to take relevant business actions for delayed orders, including the ability to view impact or create a maintenance work order.</span></span> 
 - <span data-ttu-id="8b631-118">**品質異常**: 品質異常の管理のための通知サービスとアクションを提供します。</span><span class="sxs-lookup"><span data-stu-id="8b631-118">**Quality anomaly**: Provides notification services and actions for managing quality anomalies.</span></span> <span data-ttu-id="8b631-119">ユーザーが、製品の品質属性を定義して、こうした属性に例外が発生した場合に通知を受け取る機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="8b631-119">Provides users with the ability to define quality attributes for products and get notified when exceptions to these attributes occur.</span></span> 
 - <span data-ttu-id="8b631-120">**自動在庫更新**: 製造現場の自動在庫更新を提供します。</span><span class="sxs-lookup"><span data-stu-id="8b631-120">**Automated inventory updates**: Provides automated inventory updates from the shop floor.</span></span> <span data-ttu-id="8b631-121">IoT Hub から受信したパーツ出力シグナルに基づく、自動在庫更新仕訳帳と完了レポート (RAF) 作成のバッチ処理/グループ化ルールを定義する機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="8b631-121">Provides the ability to define batching/grouping rules for automatic inventory update journals and report as finished (RAF) creation based on part-out signals received from the IoT Hub.</span></span>

<span data-ttu-id="8b631-122">シームレスなオンボード エクスペリエンス:</span><span class="sxs-lookup"><span data-stu-id="8b631-122">Seamless onboarding experience:</span></span>

 - <span data-ttu-id="8b631-123">**コード不要の機能**: 機器を IoT インテリジェンス サービスに接続するコード不要の高速なメソッドをユーザーに提供して、実用的な分析情報を利用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="8b631-123">**No-code capability**: Provides a fast, code-free method for users to connect their machines to IoT intelligence service and get started with actionable insights.</span></span>

<!--feature detail end -->









