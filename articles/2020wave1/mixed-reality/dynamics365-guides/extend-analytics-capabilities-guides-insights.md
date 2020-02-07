---
title: Guides Insights で分析機能を拡張する
description: Guides Insights により、顧客とパートナーは製品の利用状況分析を柔軟に活用できるようになり、Dynamics 365 Guides のデータが大規模なエンタープライズ エコシステムの重要な部分にすることができます。
author: relnotes
ms.reviewer: v-brycho
ms.date: 01/10/2020
ms.assetid: 8664278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: algodin
dynamics365pdf: true
ms.openlocfilehash: 6a100b1ef308f8dd12575197fb8622cf254de1ba
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986703"
---
# <a name="extend-analytics-capabilities-with-guides-insights"></a><span data-ttu-id="3b148-103">Guides Insights で分析機能を拡張する</span><span class="sxs-lookup"><span data-stu-id="3b148-103">Extend analytics capabilities with Guides Insights</span></span>
[!include[mixed-reality/dynamics365-guides banner](../includes/mixed-reality/dynamics365-guides.md)]

| <span data-ttu-id="3b148-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3b148-104">Enabled for</span></span>    |  <span data-ttu-id="3b148-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3b148-105">Public preview</span></span> | <span data-ttu-id="3b148-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="3b148-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3b148-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="3b148-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="3b148-108">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="3b148-108">Aug 2020</span></span>| -|


## <a name="business-value"></a><span data-ttu-id="3b148-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3b148-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3b148-110">Guides Insights を使用すると、製品の利用状況分析に簡単にアクセスできるようになり、Dynamics 365 Guides を大規模なエンタープライズ エコシステムの一部にすることができます。</span><span class="sxs-lookup"><span data-stu-id="3b148-110">Guides Insights provide easy access to product usage analytics that enables Dynamics 365 Guides to be part of the larger enterprise ecosystem.</span></span>  
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3b148-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3b148-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3b148-112">Guides Insights を使用すると、顧客とパートナーは、現在の時間追跡用の Power BI テンプレートの範囲を超えるユース ケースで製品の利用状況情報を簡単に活用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="3b148-112">Guides Insights allows partners and customers to easily leverage product usage information in use cases that extend beyond the current Power BI template for time-tracking.</span></span> <span data-ttu-id="3b148-113">低レベルの使用状況データから計算された分析情報を含む事前定義された Common Data Service エンティティに簡単にアクセスできるようになることで、幅広い用途が可能になります。</span><span class="sxs-lookup"><span data-stu-id="3b148-113">Easy access to pre-defined Common Data Service entities that contain insights computed from low-level usage data will enable a wide variety of applications.</span></span> <span data-ttu-id="3b148-114">たとえば、Microsoft Power Automate を使用して、ガイドが完了したときに通知を送信できます。</span><span class="sxs-lookup"><span data-stu-id="3b148-114">For example, you can use Microsoft Power Automate to send a notification when a guide is completed.</span></span> <span data-ttu-id="3b148-115">より複雑なアプリケーションで、ガイドの完了時間の傾向を分析することもできます。</span><span class="sxs-lookup"><span data-stu-id="3b148-115">A more complex application could provide a guide-completion-time-trend analysis.</span></span> 

<span data-ttu-id="3b148-116">Guides Insights の使用により、顧客とパートナーは Dynamics 365 Guides 内の次のようなデータに簡単にアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="3b148-116">Using Guides Insights, customers and partners will be able to easily access data in Dynamics 365 Guides, including:</span></span>

-   <span data-ttu-id="3b148-117">オペレーター ランスルー中に収集された生データ</span><span class="sxs-lookup"><span data-stu-id="3b148-117">Raw data collected during operator run-throughs</span></span>
-   <span data-ttu-id="3b148-118">統計情報の集計 (例: 平均時間、分布、異常)</span><span class="sxs-lookup"><span data-stu-id="3b148-118">Statistical summaries (for example: average times, distributions, and anomalies)</span></span>

<span data-ttu-id="3b148-119">Guides Insights は、パートナーと顧客のフィードバックに基づいて、製品チームによって設計されて開発されます。</span><span class="sxs-lookup"><span data-stu-id="3b148-119">Guides Insights will be designed and developed by the product team based on partner and customer feedback.</span></span> 
<!--feature detail end -->









