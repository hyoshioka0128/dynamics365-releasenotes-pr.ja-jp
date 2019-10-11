---
title: Cloud Async Client による CDX のスケーラビリティの向上
description: Cloud Async Client による CDX のスケーラビリティの向上
author: relnotes
ms.reviewer: josaw
ms.date: 08/06/2019
ms.assetid: 7c9dc757-73aa-e911-a964-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: jashanno
dynamics365pdf: true
ms.openlocfilehash: c6e924fa9b9fe71fc039d19f470241b42e58e243
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141967"
---
# <a name="improved-cdx-scalability-through-cloud-async-client"></a><span data-ttu-id="33649-103">Cloud Async Client による CDX のスケーラビリティの向上</span><span class="sxs-lookup"><span data-stu-id="33649-103">Improved CDX scalability through Cloud Async Client</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="33649-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="33649-104">Enabled for</span></span>    |  <span data-ttu-id="33649-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="33649-105">Public preview</span></span> | <span data-ttu-id="33649-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="33649-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="33649-107">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="33649-107">Users, automatically</span></span>|<span data-ttu-id="33649-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="33649-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="33649-109">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="33649-109">Aug 2, 2019</span></span>| <span data-ttu-id="33649-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="33649-110">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="33649-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="33649-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="33649-112">Commerce Data Exchange (CDX) は、チャネル データベースとオフライン データベースに対して重要なビジネス データを生成、提供、ダウンロード、適用する重要なプロセスです。</span><span class="sxs-lookup"><span data-stu-id="33649-112">Commerce Data Exchange (CDX) is the critical process of generating, making available, downloading, and applying crucial business data to Channel databases and Offline databases.</span></span> <span data-ttu-id="33649-113">この目に見えないコア アーキテクチャは不可欠であり、高速かつ効率的に機能する必要があります。</span><span class="sxs-lookup"><span data-stu-id="33649-113">This unseen core architecture is vital and must function with speed and efficiency.</span></span> <span data-ttu-id="33649-114">この機能では、Async Client を本社から移行して、Azure の能力を最大限に活用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="33649-114">This feature migrates the Async Client out of headquarters to better use the full complement of Azure capacity.</span></span> <span data-ttu-id="33649-115">この機能は、CDX アーキテクチャのスケーラビリティ、パフォーマンス、可用性を向上して、データをより迅速に生成し、より効率的に提供し、オフライン データベース用の Modern POS 内の Async Clients またはチャネル データベースへの帯域幅を強化します。</span><span class="sxs-lookup"><span data-stu-id="33649-115">This feature enhances the scalability, performance, and availability of the CDX architecture to more quickly generate data, more efficiently make it available, and enhance bandwidth to Async Clients within Modern POS for the offline database or to the Channel database.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="33649-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="33649-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="33649-117">CDX は、直接には本部の一部ではなくなります。</span><span class="sxs-lookup"><span data-stu-id="33649-117">CDX is no longer directly a part of headquarters.</span></span> <span data-ttu-id="33649-118">これを独自の Azure サービスに拡張することで、競合するリソースがなくなります。</span><span class="sxs-lookup"><span data-stu-id="33649-118">By enhancing this into its own Azure service, there are no resources to compete with.</span></span> <span data-ttu-id="33649-119">代わりに、背後で Azure の完全なスケーラビリティとメリットが発揮され、現在および将来の最大限の改善が可能になります。</span><span class="sxs-lookup"><span data-stu-id="33649-119">Instead, the full scalability and strength of Azure is behind it to give the fullest complement of current and future improvements possible.</span></span>
<!--feature detail end -->



