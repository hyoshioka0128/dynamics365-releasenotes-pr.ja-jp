---
title: コマース データのサイズ変更の向上
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 01/11/2020
ms.assetid: 94b93c03-bff6-e911-a813-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: 37ed6fa2b7978ae0441b0d427450bbccfd486476
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986648"
---
# <a name="commerce-data-sizing-improvements"></a><span data-ttu-id="ba830-102">コマース データのサイズ変更の向上</span><span class="sxs-lookup"><span data-stu-id="ba830-102">Commerce data sizing improvements</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="ba830-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="ba830-103">Enabled for</span></span>    |  <span data-ttu-id="ba830-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ba830-104">Public preview</span></span> | <span data-ttu-id="ba830-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="ba830-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ba830-106">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="ba830-106">End users, automatically</span></span>|<span data-ttu-id="ba830-107">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="ba830-107">May 2020</span></span>| <span data-ttu-id="ba830-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="ba830-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ba830-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ba830-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ba830-110">最新の販売時点管理 (MPOS) オフラインや Retail Store Scale Unit (RSSU) など、Retail のオンプレミス コンポーネントは、計画された利用不可、クラウド コンポーネントの停止、ネットワーク接続が不十分なリージョンといった不測の事態のシナリオに不可欠です。</span><span class="sxs-lookup"><span data-stu-id="ba830-110">Our Retail on-premises components, such as Modern point of sale (MPOS) offline and Retail Store Scale Unit (RSSU), are critical for our contingency story for scenarios of planned unavailability, for outage of cloud components, and for regions with poor network connectivity.</span></span>  <span data-ttu-id="ba830-111">この機能として、データの同期の効率、回復性、速度を最大化することが重要です。</span><span class="sxs-lookup"><span data-stu-id="ba830-111">As a function of this, it is crucial to maximize the efficiency, resiliency, and speed with which data is synchronized.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ba830-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ba830-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ba830-113">この機能は、次のスコープを対象としています: チャネル データベースで必要なものとオフライン データベース内で必要なものをより適切に区別するための同期関連データを構成する機能。</span><span class="sxs-lookup"><span data-stu-id="ba830-113">This features targets the following scope: The ability to configure synchronization-related data to better differentiate between what is required at the channel database and what is required within the offline database.</span></span> <span data-ttu-id="ba830-114">オフライン データベース内のデータの分離とデータの最小化を可能にするために、少なくともジョブ レベルとサブジョブ レベルで機能します。</span><span class="sxs-lookup"><span data-stu-id="ba830-114">It will function at a job level and at a subjob level, at least, to allow separation of data and minimization of data in the offline database.</span></span>

<span data-ttu-id="ba830-115">**この機能の対象ユーザー**</span><span class="sxs-lookup"><span data-stu-id="ba830-115">**Who uses this feature**</span></span>

<span data-ttu-id="ba830-116">これは、小売業者の IT 部門または小売チャネルのセットアップを管理する運用ロールで使用されます。</span><span class="sxs-lookup"><span data-stu-id="ba830-116">This will be used by Retail IT or operations roles that manage the Retail Channel Setup.</span></span>

<span data-ttu-id="ba830-117">**必要なライセンス**</span><span class="sxs-lookup"><span data-stu-id="ba830-117">**License required**</span></span>

<span data-ttu-id="ba830-118">なし</span><span class="sxs-lookup"><span data-stu-id="ba830-118">No</span></span>

<span data-ttu-id="ba830-119">**必要なセットアップ**</span><span class="sxs-lookup"><span data-stu-id="ba830-119">**Setup required**</span></span>

<span data-ttu-id="ba830-120">なし</span><span class="sxs-lookup"><span data-stu-id="ba830-120">No</span></span>
<!--feature detail end -->









