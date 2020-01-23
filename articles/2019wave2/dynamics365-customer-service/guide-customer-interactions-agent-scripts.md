---
title: 顧客とエージェントの対話ガイドのスクリプト
description: 顧客とエージェントの対話ガイドのスクリプト
author: relnotes
ms.reviewer: kabala
ms.date: 01/09/2020
ms.assetid: 0462278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: askuma
dynamics365pdf: true
ms.openlocfilehash: 60b99e7240eaf126b73a2b752b51450b8dd75010
ms.sourcegitcommit: 7d5d14ac84333ba166265755f410f7e16035a64e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2948464"
---
# <a name="guide-customer-interactions-with-agent-scripts"></a><span data-ttu-id="1a303-103">顧客とエージェントの対話ガイドのスクリプト</span><span class="sxs-lookup"><span data-stu-id="1a303-103">Guide customer interactions with agent scripts</span></span>
[!include[dynamics365-customer-service banner](../includes/dynamics365-customer-service.md)]

| <span data-ttu-id="1a303-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="1a303-104">Enabled for</span></span>    |  <span data-ttu-id="1a303-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="1a303-105">Public preview</span></span> | <span data-ttu-id="1a303-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="1a303-106">Early access</span></span> | <span data-ttu-id="1a303-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="1a303-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="1a303-108">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="1a303-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="1a303-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="1a303-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="1a303-110">2019 年 10 月 24 日</span><span class="sxs-lookup"><span data-stu-id="1a303-110">Oct 24, 2019</span></span>|-| <span data-ttu-id="1a303-111">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="1a303-111">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="1a303-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="1a303-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="1a303-113">エージェント スクリプトは、企業がエージェントをすばやく一貫性のある方法でトレーニングし、エージェントが同様の種類のサポートの問題に対して一貫性のある方法ですべての顧客をサポートできるようにします。</span><span class="sxs-lookup"><span data-stu-id="1a303-113">Agent scripts help businesses quickly and consistently train agents and ensure they are helping all customers in a consistent way for similar types of support issues.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="1a303-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="1a303-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="1a303-115">人、製品、プロセスが頻繁に入れ替わるため、企業は最新のプロセスおよび製品についてエージェントを継続的にトレーニングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="1a303-115">Businesses have a critical need to continuously train agents on the latest processes and products due to a high degree of churn in people, products, and processes.</span></span> <span data-ttu-id="1a303-116">定期的なトレーニングにもかかわらず、サービス提供のエラーや遅延が繰り返し発生することがよくあり、顧客の不満につながります。</span><span class="sxs-lookup"><span data-stu-id="1a303-116">Despite regular trainings, recurrent errors and delays in service delivery are common, resulting in customer dissatisfaction.</span></span> <span data-ttu-id="1a303-117">必要なレベルの規制順守を確実にし、常によいカスタマー エクスペリエンスを提供するためには、プロセスの遵守が重要です。</span><span class="sxs-lookup"><span data-stu-id="1a303-117">To ensure the required levels of regulatory compliance and offer a consistently positive customer experience, process adherence is critical.</span></span> <span data-ttu-id="1a303-118">この機能では、エージェントにステップバイステップのガイダンスを提供するスクリプトを構成する手段が組織に提供されます。</span><span class="sxs-lookup"><span data-stu-id="1a303-118">This feature provides organizations a means to configure scripts that provide step-by-step guidance to agents.</span></span> <span data-ttu-id="1a303-119">セッションの種類 (チャットや電話など) に基づいてこれらの手順を構成および自動化し、適切なプロセスを確実に順守することができます。</span><span class="sxs-lookup"><span data-stu-id="1a303-119">These steps can be configured and automated based on session types (such as chat or phone calls) to ensure adherence to the appropriate processes.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="1a303-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="1a303-120">See also</span></span>

<span data-ttu-id="1a303-121">[スクリプトでエージェントをガイドする](https://docs.microsoft.com/dynamics365/omnichannel/administrator/agent-scripts) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="1a303-121">[Guide agents with scripts](https://docs.microsoft.com/dynamics365/omnichannel/administrator/agent-scripts) (docs)</span></span>
