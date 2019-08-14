---
title: サード パーティ統合のためのデータ フィード
description: サード パーティ統合のためのデータ フィード
author: relnotes
ms.reviewer: sericks
ms.date: 07/31/2019
ms.assetid: fe62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: sunilg
dynamics365pdf: true
ms.openlocfilehash: bd7b6d96da900b57ba73ccd51973a15b56ae5e98
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1855331"
---
# <a name="data-feeds-for-third-party-integrations"></a><span data-ttu-id="ee70c-103">サード パーティ統合のためのデータ フィード</span><span class="sxs-lookup"><span data-stu-id="ee70c-103">Data feeds for third-party integrations</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="ee70c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ee70c-104">Enabled for</span></span>    |  <span data-ttu-id="ee70c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ee70c-105">Public preview</span></span> | <span data-ttu-id="ee70c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ee70c-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="ee70c-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="ee70c-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ee70c-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="ee70c-108">October 2019</span></span>| <span data-ttu-id="ee70c-109">2020 年 3 月</span><span class="sxs-lookup"><span data-stu-id="ee70c-109">March 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="ee70c-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ee70c-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ee70c-111">データ フィードにより、Dynamics 365 for Finance and Operations データのほぼリアルタイムの増分エクスポートが可能になります。</span><span class="sxs-lookup"><span data-stu-id="ee70c-111">Data feeds will enable near real-time incremental export of Dynamics 365 for Finance and Operations data.</span></span> <span data-ttu-id="ee70c-112">Finance and Operations のデータが変更され、Azure Data Lake や Azure メッセージング サービスなどの汎用コンシューマーに送信されると、増分エクスポートが発生します。</span><span class="sxs-lookup"><span data-stu-id="ee70c-112">The incremental export occurs when data in Finance and Operations changes and is sent to generic consumers, like Azure Data Lake and Azure messaging services.</span></span> <span data-ttu-id="ee70c-113">外部のビジネス アプリケーションとシステムは、Azure メッセージング サービスを使用して、顧客データ フィードや販売注文データ フィードなどの特定のデータ フィードをサブスクライブして、Finance and Operations からほぼリアルタイムでデータの更新を受け取ることができます。</span><span class="sxs-lookup"><span data-stu-id="ee70c-113">External business applications and systems can subscribe to specific data feeds, such as customer data feeds or sales-order data feeds using Azure messaging services to receive close to real-time updates of data from Finance and Operations.</span></span> <span data-ttu-id="ee70c-114">データ フィードは、フル プッシュのユース ケースもサポートし、イベント駆動型アーキテクチャに基づいてメッセージベースのデータ統合を有効にします。</span><span class="sxs-lookup"><span data-stu-id="ee70c-114">Data feeds will also support full push use cases and will be based on event-driven architecture to enable message-based data integration.</span></span> <span data-ttu-id="ee70c-115">これにより、アプリケーション間の高スループットと待ち時間の短縮が実現されます。</span><span class="sxs-lookup"><span data-stu-id="ee70c-115">This will create high throughput and reduced latency between applications.</span></span>
<!--feature detail end -->











