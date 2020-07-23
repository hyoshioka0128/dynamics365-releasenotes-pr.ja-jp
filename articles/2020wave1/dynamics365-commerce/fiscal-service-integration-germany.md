---
title: ドイツ向け会計サービスの統合
description: 2020 年 1 月 1 日より、ドイツで新しいキャッシュ レジスター規制が施行されました。 Dynamics 365 Commerce がこれらの規制の要件に対応するようになりました。
author: relnotes
ms.reviewer: josaw
ms.date: 06/10/2020
ms.assetid: e4963159-3fcb-e911-a96a-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: epopov
dynamics365pdf: true
ms.openlocfilehash: a7d2d6ec9f850e921fc91e9fbe0eaedc5a5fa465
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3487845"
---
# <a name="fiscal-service-integration-for-germany"></a><span data-ttu-id="7ceb3-104">ドイツ向け会計サービスの統合</span><span class="sxs-lookup"><span data-stu-id="7ceb3-104">Fiscal service integration for Germany</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="7ceb3-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="7ceb3-105">Enabled for</span></span>    |  <span data-ttu-id="7ceb3-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7ceb3-106">Public preview</span></span> | <span data-ttu-id="7ceb3-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="7ceb3-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7ceb3-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="7ceb3-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="7ceb3-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7ceb3-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7ceb3-110">2020 年 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="7ceb3-110">May 29, 2020</span></span>| <span data-ttu-id="7ceb3-111">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="7ceb3-111">Aug 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="7ceb3-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7ceb3-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7ceb3-113">この機能により、グローバルとローカルの Dynamics 365 Commerce ユーザーが、ドイツのキャッシュ レジスター規制に順守するようになります。</span><span class="sxs-lookup"><span data-stu-id="7ceb3-113">This functionality enables global and local Dynamics 365 Commerce customers to comply with the local cash register regulations in Germany.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7ceb3-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7ceb3-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7ceb3-115">この機能には、販売時点情報管理 (POS) とサードパーティの会計サービスとの統合のサンプルが含まれており、ドイツのキャッシュ レジスター規制への準拠を保証します。</span><span class="sxs-lookup"><span data-stu-id="7ceb3-115">This functionality includes a sample of the integration of the point of sale (POS) with a third-party fiscal service that ensures compliance with cash register regulations in Germany.</span></span> <span data-ttu-id="7ceb3-116">統合のサンプルは、ドイツの市場で利用できる一般的なサード パーティの会計サービスの 1 つをサポートし、さまざまな現金持ち帰りおよび顧客注文販売シナリオで販売を登録できるようにします。</span><span class="sxs-lookup"><span data-stu-id="7ceb3-116">The integration sample supports one of the popular third-party fiscal services available on the German market and enables registration of sales in various cash-and-carry and customer order sales scenarios.</span></span> 

<span data-ttu-id="7ceb3-117">また、基本的なシナリオ (再試行が可能な場合など)、さらにはより高度なシナリオ (それまでに会計サービスに登録されていない完了取引の登録など) でのエラー処理のオプションも提供されます。</span><span class="sxs-lookup"><span data-stu-id="7ceb3-117">It also provides options for error handling in basic scenarios (such as when retry is possible) as well as more advanced scenarios, such as registering a completed transaction that was not previously registered in the fiscal service.</span></span> <span data-ttu-id="7ceb3-118">サンプルは Retail SDK の一部であり、そのままビルドして使用することができます。</span><span class="sxs-lookup"><span data-stu-id="7ceb3-118">The sample is a part of the Retail SDK and can be built and used as is.</span></span> <span data-ttu-id="7ceb3-119">実装パートナーは、必要な小売シナリオすべてに対応できるように統合機能を拡張したり、サンプルに基づいて他の会計サービスとの統合を作成したりすることもできます。</span><span class="sxs-lookup"><span data-stu-id="7ceb3-119">Implementation partners can also extend the integration functionality to cover all required retail scenarios or build integration with other fiscal services based on the sample.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="7ceb3-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="7ceb3-120">See also</span></span>

<!--docs start-->
<span data-ttu-id="7ceb3-121">[ドイツ向け会計登録サービス統合サンプル](https://docs.microsoft.com/dynamics365/commerce/localizations/emea-deu-fi-sample) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="7ceb3-121">[Fiscal registration service integration sample for Germany](https://docs.microsoft.com/dynamics365/commerce/localizations/emea-deu-fi-sample) (docs)</span></span>
<!--docs end-->
