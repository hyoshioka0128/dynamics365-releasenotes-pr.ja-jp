---
title: サービス レベル アグリーメントの強化
description: サービス レベル アグリーメントの強化
author: relnotes
ms.reviewer: nenellim
ms.date: 04/27/2020
ms.assetid: ec61278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: deepap
dynamics365pdf: true
ms.openlocfilehash: d29cc43979446472e4482bb1d777714eb1ec8283
ms.sourcegitcommit: 63a61a3764ac12162f3e06ea5d22a05ba22be2a2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2020
ms.locfileid: "3350504"
---
# <a name="enhancements-in-service-level-agreements"></a><span data-ttu-id="9eed2-103">サービス レベル アグリーメントの強化</span><span class="sxs-lookup"><span data-stu-id="9eed2-103">Enhancements in service level agreements</span></span>


| <span data-ttu-id="9eed2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9eed2-104">Enabled for</span></span>    |  <span data-ttu-id="9eed2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9eed2-105">Public preview</span></span> | <span data-ttu-id="9eed2-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="9eed2-106">Early access</span></span> | <span data-ttu-id="9eed2-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="9eed2-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="9eed2-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="9eed2-108">End users, automatically</span></span>|-|<span data-ttu-id="9eed2-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9eed2-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9eed2-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="9eed2-110">Feb 3, 2020</span></span>| <span data-ttu-id="9eed2-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9eed2-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9eed2-112">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="9eed2-112">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="9eed2-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9eed2-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9eed2-114">企業は、顧客が受ける資格のある適切なレベルのサポートを確実に提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9eed2-114">Businesses must ensure that they deliver the right level of support to which their customers are entitled.</span></span> <span data-ttu-id="9eed2-115">管理者はサービス レベル アグリーメント (SLA) を使用して、契約上合意された目標レベルと、SLA のメトリックの成功と失敗を追跡する主要業績評価指標 (KPI) を定義します。</span><span class="sxs-lookup"><span data-stu-id="9eed2-115">Service level agreements (SLAs) help administrators define a contractually agreed-on target level and key performance indicators (KPIs) that track the success and failure of SLA metrics.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9eed2-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9eed2-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9eed2-117">このリリースでは、統一インターフェイス上で新しい SLA 管理エクスペリエンスが有効になり、従来の Web クライアントとの機能パリティが実現します。</span><span class="sxs-lookup"><span data-stu-id="9eed2-117">In this release, a new SLA administration experience has been enabled on the Unified Interface that brings feature parity with the legacy web client.</span></span> <span data-ttu-id="9eed2-118">管理者は、Microsoft Power Automate で提供されるさまざまな既定のアクションを利用して、SLA に関する成功、失敗、警告などのアクションを簡単に構成できます。</span><span class="sxs-lookup"><span data-stu-id="9eed2-118">Administrators can now leverage the various out-of-the-box actions available with Microsoft Power Automate to easily configure actions, such as success, failure, and warning actions for SLAs.</span></span> <span data-ttu-id="9eed2-119">たとえば、管理者は SLA 違反があったときにエージェントに Microsoft Teams メッセージを投稿できます。</span><span class="sxs-lookup"><span data-stu-id="9eed2-119">For example, the administrator can post a Microsoft Teams message to an agent when an SLA is violated.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="9eed2-120">サービス レベル アグリーメントの統合クライアント エクスペリエンスが別のパッケージで有効になっていても、管理者はこの機能を構成する必要があり、それによってエンド ユーザーが自動的に影響を受けることはありません。</span><span class="sxs-lookup"><span data-stu-id="9eed2-120">Even though the Service Level Agreement Unified Client experience is enabled via a separate package, an admin would need to configure the feature and it will not automatically impact the end user.</span></span>



## <a name="see-also"></a><span data-ttu-id="9eed2-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="9eed2-121">See also</span></span>

<!--docs start-->
<span data-ttu-id="9eed2-122">[顧客サービス ハブで SLA を構成する](https://docs.microsoft.com/dynamics365/customer-service/define-service-level-agreements#configure-slas-in-customer-service-hub) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="9eed2-122">[Configure SLAs in Customer Service Hub](https://docs.microsoft.com/dynamics365/customer-service/define-service-level-agreements#configure-slas-in-customer-service-hub) (docs)</span></span>
<!--docs end-->
