---
title: エンティティ レコードの統合ルーティング
description: 統合ルーティングとキュー
author: relnotes
ms.reviewer: kabala
ms.date: 09/12/2019
ms.assetid: 1062278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: karthig
dynamics365pdf: true
ms.openlocfilehash: ec6f2b30f80cf150363a23a48c713547af4c829d
ms.sourcegitcommit: b0fef00d4f04f2507056a10ecce699767c669119
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2662089"
---
# <a name="unified-routing-for-entity-records"></a><span data-ttu-id="0b9f3-103">エンティティ レコードの統合ルーティング</span><span class="sxs-lookup"><span data-stu-id="0b9f3-103">Unified routing for entity records</span></span>
[!include[dynamics365-customer-service banner](../includes/dynamics365-customer-service.md)]

| <span data-ttu-id="0b9f3-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="0b9f3-104">Enabled for</span></span>    |  <span data-ttu-id="0b9f3-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="0b9f3-105">Public preview</span></span> | <span data-ttu-id="0b9f3-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="0b9f3-106">Early access</span></span> | <span data-ttu-id="0b9f3-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="0b9f3-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="0b9f3-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="0b9f3-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="0b9f3-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="0b9f3-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="0b9f3-110">2019 年 8 月 31 日</span><span class="sxs-lookup"><span data-stu-id="0b9f3-110">Aug 31, 2019</span></span>|-| <span data-ttu-id="0b9f3-111">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="0b9f3-111">Oct 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="0b9f3-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="0b9f3-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="0b9f3-113">現在、Dynamics 365 の顧客サービス サポート案件ルーティングにより、組織は静的なキューにサポート案件をルーティングできます。</span><span class="sxs-lookup"><span data-stu-id="0b9f3-113">Today, customer service case routing in Dynamics 365 enables organizations to route cases to static queues.</span></span> <span data-ttu-id="0b9f3-114">これらのサポート案件は、スーパーバイザーが手動で配分するか、エージェントが手動で選択します。</span><span class="sxs-lookup"><span data-stu-id="0b9f3-114">These cases are either manually distributed by supervisors or manually picked by agents.</span></span> <span data-ttu-id="0b9f3-115">統合ルーティングを使用することで、チャットや SMS などの他のチャネルから発信された作業項目とともに、オムニチャネル対応キューにサポート案件をルーティングできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0b9f3-115">With unified routing, now cases can be routed to omnichannel enabled queues along with work items that originate from other channels such as Chat and SMS.</span></span> 
 
> [!NOTE]
> <span data-ttu-id="0b9f3-116">オムニチャネルは既存の CDS キュー エンティティを活用します。サポート案件または他のエンティティ用のキューを既に設定している場合は、オムニチャネル作業配分でそのキューを引き続き使用できます。</span><span class="sxs-lookup"><span data-stu-id="0b9f3-116">Omnichannel leverages the existing CDS queue entity, and if you have already setup queues for cases or other entities, you can continue to use the same with omnichannel work distribution.</span></span>
 
<span data-ttu-id="0b9f3-117">これにより、組織はエージェントが対処する作業プロファイルを厳密に定義でき、チャネルにまたがるワークフローの割り当てを自動化し、エージェントの能力、空き時間、スキルに基づいて作業項目を割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="0b9f3-117">This allows organizations to tightly define the work profile that their agents are supposed to handle, and organizations can automate the work flow assignment across channels and assign the work items based on agents capacity, availability, and skill.</span></span>
 
<span data-ttu-id="0b9f3-118">この統合された顧客サービス ルーティングは、カスタム エンティティやその他のすぐに使えるエンティティなど、任意のアクティビティ対応の CDS エンティティ レコードに対しても適用されます。</span><span class="sxs-lookup"><span data-stu-id="0b9f3-118">This unified customer service routing will also be opened up for any activity enabled CDS entity records like custom entities or other out of the box entities.</span></span>
 
<span data-ttu-id="0b9f3-119">エージェントは、同じマルチセッション エクスペリエンスである顧客サービス用のオムニチャネル アプリを使用して、これらのエンティティ レコード作業項目を、チャットや SMS などの他のチャネルから発信された作業項目と一緒に処理できます。</span><span class="sxs-lookup"><span data-stu-id="0b9f3-119">Agents can use the Omnichannel for Customer Service app, which is the same multi-session experience, to handle these entity record work items alongside work items coming from other channels, such as Chat and SMS.</span></span>
 
> [!NOTE]
> <span data-ttu-id="0b9f3-120">現在、Dynamics 365 ポータルを使用することで、サポート案件を作成してサポートを要求できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0b9f3-120">Today, it's possible for customers to request support using Dynamics 365 Portal.</span></span> <span data-ttu-id="0b9f3-121">統合ルーティングを使用すると、ポータルから発信されるこれらのサポート作業項目を、空いている最適なエージェントにルーティングし、自動的に割り当てることができます。</span><span class="sxs-lookup"><span data-stu-id="0b9f3-121">With unified routing, these support work items originating from Portal can be routed and automatically assigned to best available agents.</span></span>

> [!NOTE]
> <span data-ttu-id="0b9f3-122">サポート案件エンティティ レコードのルーティングは、パブリック プレビュー リリースで利用できます。</span><span class="sxs-lookup"><span data-stu-id="0b9f3-122">Routing for case entity records is available in public preview release.</span></span> <span data-ttu-id="0b9f3-123">他のエンティティ レコードのルーティングは、GA (一般提供) リリースで利用可能になります。</span><span class="sxs-lookup"><span data-stu-id="0b9f3-123">Routing for other entity records will be available with GA release.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="0b9f3-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="0b9f3-124">See also</span></span>

<span data-ttu-id="0b9f3-125">[エンティティ レコードのルーティング](https://docs.microsoft.com/dynamics365/customer-engagement/omnichannel/administrator/entity-channel) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="0b9f3-125">[Entity Records Routing](https://docs.microsoft.com/dynamics365/customer-engagement/omnichannel/administrator/entity-channel) (docs)</span></span>
