---
title: チャネル別に構成された Retail の自動請求
description: ''
author: hhainesms
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: ea1fc046-1c9c-e911-a962-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 887b917c4c8d311fff6771b862899d9c530a6cc1
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143420"
---
# <a name="retail-auto-charges-configured-by-channel"></a><span data-ttu-id="733dc-102">チャネル別に構成された Retail の自動請求</span><span class="sxs-lookup"><span data-stu-id="733dc-102">Retail auto-charges configured by channel</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="733dc-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="733dc-103">Enabled for</span></span>    |  <span data-ttu-id="733dc-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="733dc-104">Public preview</span></span> | <span data-ttu-id="733dc-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="733dc-105">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="733dc-106">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="733dc-106">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="733dc-107">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="733dc-107">November 2019</span></span>| <span data-ttu-id="733dc-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="733dc-108">February 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="733dc-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="733dc-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="733dc-110">小売業者には、一部の場所、店舗、またはチャネルにおいて、品目または荷渡方法の構成に基づいて追加の料金または手数料を請求するための特定の要件があります。</span><span class="sxs-lookup"><span data-stu-id="733dc-110">Retailers have specific requirements in certain locations, stores, or channels to charge customers additional charges or fees based on the item or mode of delivery configurations.</span></span> <span data-ttu-id="733dc-111">例えば、特定の品目に対して、リサイクル関連の料金や環境に関する料金が必要になることがあります。</span><span class="sxs-lookup"><span data-stu-id="733dc-111">For example, fees relating to recycling or environmental fees may be required for certain items.</span></span> <span data-ttu-id="733dc-112">この新しい機能は、既存の自動請求機能を強化してチャネル別に固有の請求を可能にし、料金の請求が必要な店舗、場所、またはチャネルに対してのみ料金が計算されるようにします。</span><span class="sxs-lookup"><span data-stu-id="733dc-112">This new feature will enhance the existing auto-charges feature to allow specific charges by channel so that only the stores, locations, or channels that are required to charge the fees will have the charges calculated.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="733dc-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="733dc-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="733dc-114">この機能は、小売チャネル別に自動請求を定義するための追加の基準を提供します。</span><span class="sxs-lookup"><span data-stu-id="733dc-114">This feature provides additional criteria to allow auto-charges to be defined by retail channel.</span></span> <span data-ttu-id="733dc-115">機能は、現在の Retail で荷渡方法や品揃えをチャネル別にフィルター処理する方法と似たものになります。</span><span class="sxs-lookup"><span data-stu-id="733dc-115">Functionality will be similar to how Retail currently filters modes of delivery or assortments by channel.</span></span> <span data-ttu-id="733dc-116">この機能は、小売組織のモデル階層を使用して、**高度な自動請求**コンフィギュレーション キーが有効になっている本社ユーザーが自分の自動請求テーブルで小売チャネル別に追加のフィルターを定義できるようにします。</span><span class="sxs-lookup"><span data-stu-id="733dc-116">The feature will use the retail organizational model hierarchy and allow headquarters users who have the **Advanced auto charges** configuration key enabled to be able to define additional filters on their auto-charges table by retail channels.</span></span> <span data-ttu-id="733dc-117">Dynamics 365 for Finance and Operations の非小売ユーザーがこれらの Retail の追加機能の影響を受けないようにするために、この機能はコンフィギュレーション キーに関連付けられます。</span><span class="sxs-lookup"><span data-stu-id="733dc-117">The functionality will be tied to a configuration key to ensure that non-retail users of Dynamics 365 for Finance and Operations are not impacted by these added Retail features.</span></span>
<!--feature detail end -->











