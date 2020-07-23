---
title: コマース データのサイズ変更の向上
description: お客様にとって、データ同期がどのように発生するかを正確に制御し、どのデータをどこで同期するかを指定することが重要です。 特にオンプレミスのオフラインの最新の販売時点管理 (MPOS) データベースでは、同期されるデータとデータのサイズを管理することが不可欠です。 この機能セットにより、オフライン データベースと同期するデータを顧客が管理できるようにする機能が追加されます。
author: relnotes
ms.reviewer: josaw
ms.date: 06/03/2020
ms.assetid: 94b93c03-bff6-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: d862264bb0674d4fcba2c772befe076f51cc6178
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3441339"
---
# <a name="commerce-data-sizing-improvements"></a><span data-ttu-id="b0c27-105">コマース データのサイズ変更の向上</span><span class="sxs-lookup"><span data-stu-id="b0c27-105">Commerce data sizing improvements</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="b0c27-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="b0c27-106">Enabled for</span></span>    |  <span data-ttu-id="b0c27-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b0c27-107">Public preview</span></span> | <span data-ttu-id="b0c27-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="b0c27-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b0c27-109">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="b0c27-109">End users, automatically</span></span>|<span data-ttu-id="b0c27-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b0c27-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b0c27-111">2020 年 5 月 18 日</span><span class="sxs-lookup"><span data-stu-id="b0c27-111">May 18, 2020</span></span>| <span data-ttu-id="b0c27-112">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="b0c27-112">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="b0c27-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b0c27-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b0c27-114">最新の販売時点管理 (MPOS) オフラインやオンプレミスの Commerce Scale Unit (以前の Retail Store Scale Unit) など、Commerce のオンプレミス コンポーネントは、計画された利用不可、クラウド コンポーネントの停止、ネットワーク接続が不十分なリージョンといった不測の事態のシナリオに不可欠です。</span><span class="sxs-lookup"><span data-stu-id="b0c27-114">Our Commerce on-premises components, such as Modern point of sale (MPOS) offline and Commerce Scale Unit on-premises (formerly Retail Store Scale Unit), are critical for our contingency story for scenarios of planned unavailability, for outage of cloud components, and for regions with poor network connectivity.</span></span> <span data-ttu-id="b0c27-115">そのため、データの同期の効率、回復性、速度を最大化することが重要です。</span><span class="sxs-lookup"><span data-stu-id="b0c27-115">To this end, it is crucial to maximize the efficiency, resiliency, and speed with which data is synchronized.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b0c27-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b0c27-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b0c27-117">この機能は、チャネル データベースで必要なものとオフライン データベース内で必要なものを区別するための同期関連データを構成する機能を対象としています。</span><span class="sxs-lookup"><span data-stu-id="b0c27-117">This features targets the ability to configure synchronization-related data to differentiate between what is required at the channel database and what is required within the offline database.</span></span> <span data-ttu-id="b0c27-118">オフライン データベース内のデータの分離とデータの最小化は、ジョブ レベルで機能するようになります。</span><span class="sxs-lookup"><span data-stu-id="b0c27-118">Separation of data and minimization of data in the offline database will be allowed at a job level.</span></span>

- <span data-ttu-id="b0c27-119">この機能は、小売業者の IT 部門または小売チャネルのセットアップを管理する運用ロールで使用されます。</span><span class="sxs-lookup"><span data-stu-id="b0c27-119">The functionality will be used by Retail IT or operations roles that manage the Retail channel setup.</span></span>

- <span data-ttu-id="b0c27-120">ライセンス必要はありません。</span><span class="sxs-lookup"><span data-stu-id="b0c27-120">No license is required.</span></span>

- <span data-ttu-id="b0c27-121">セットアップの必要はありません。</span><span class="sxs-lookup"><span data-stu-id="b0c27-121">No setup is required.</span></span>
<!--feature detail end -->









