---
title: Power BI ソリューションを分析ワークスペースに直接埋め込む
description: Power BI でホストされている会社のソリューションを、アプリケーション ワークスペースに直接埋め込みます
author: relnotes
ms.reviewer: kfend
ms.date: 07/31/2019
ms.assetid: f862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: tjvass
dynamics365pdf: true
ms.openlocfilehash: 1651d5ad730505117234f7d2c6cb7b52d2010cb9
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854275"
---
# <a name="embed-power-bi-solutions-directly-into-analytical-workspaces"></a><span data-ttu-id="ca9ed-103">Power BI ソリューションを分析ワークスペースに直接埋め込む</span><span class="sxs-lookup"><span data-stu-id="ca9ed-103">Embed Power BI solutions directly into analytical workspaces</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="ca9ed-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ca9ed-104">Enabled for</span></span>    |  <span data-ttu-id="ca9ed-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ca9ed-105">Public preview</span></span> | <span data-ttu-id="ca9ed-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="ca9ed-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="ca9ed-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="ca9ed-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ca9ed-108">2019 年 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="ca9ed-108">May 01, 2019</span></span>| <span data-ttu-id="ca9ed-109">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="ca9ed-109">October 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="ca9ed-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ca9ed-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ca9ed-111">Dynamics 365 for Finance and Operations のパワー ユーザーは、Microsoft Power BI のレポートをアプリケーション ワークスペースに直接埋め込むことができます。</span><span class="sxs-lookup"><span data-stu-id="ca9ed-111">Power users of Dynamics 365 for Finance and Operations are able to embed Microsoft Power BI reports directly in application workspaces.</span></span> <span data-ttu-id="ca9ed-112">お客様は Power BI サービスを使用してグラフィックが豊富な分析ソリューションを作成し、そのソリューションを組織のメンバーと共有することで、大きな成功を収めています。</span><span class="sxs-lookup"><span data-stu-id="ca9ed-112">Customers are finding amazing success using the Power BI service to author graphically rich analytical solutions and then share the solutions with members of their organization.</span></span> <span data-ttu-id="ca9ed-113">最新のプラットフォームの機能強化により、お客様は外部データ システムからのビューを含む可能性のある既存の Power BI ソリューションを統合することができます。</span><span class="sxs-lookup"><span data-stu-id="ca9ed-113">The latest platform enhancement allows customers to integrate existing Power BI solutions that can include views sourced from external data systems.</span></span> <span data-ttu-id="ca9ed-114">とりわけ、更新を配布するためにサービスを中断する必要がなく、お客様には Power BI でホストされている分析ソリューションの機能強化を自分のペースで公開できる柔軟性が提供されます。</span><span class="sxs-lookup"><span data-stu-id="ca9ed-114">Best of all, there are no service interruptions required to distribute updates, giving customers greater flexibility to publish, at their own pace, enhancements to analytical solutions hosted on Power BI.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ca9ed-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ca9ed-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ca9ed-116">ユーザーは、業務運営のコンテキストで表示されるリッチな視覚化を含む Dynamics 365 for Finance and Operations の分析ワークスペースを気に入っています。</span><span class="sxs-lookup"><span data-stu-id="ca9ed-116">Users love analytical workspaces in Dynamics 365 for Finance and Operations, with rich visualizations shown in the context of business operations.</span></span> <span data-ttu-id="ca9ed-117">Microsoft から提供される分析ワークスペースに加えて、ISV やパートナーも特別な分析用ワークスペースを構築しています。</span><span class="sxs-lookup"><span data-stu-id="ca9ed-117">In addition to the analytical workspaces shipped by Microsoft, ISVs and partners have also built specialized analytical workspaces.</span></span> <span data-ttu-id="ca9ed-118">ガイダンスとツールを使用して、パワー ユーザーは、エンティティ ストアで作成された分析ワークスペースを、データ フローに基づく Power BI テンプレート アプリに移行できます。</span><span class="sxs-lookup"><span data-stu-id="ca9ed-118">Using guidance and tools, power users can transition analytical workspaces authored with entity store into Power BI template apps based on data flows.</span></span> <span data-ttu-id="ca9ed-119">アプリを Microsoft AppSource マーケットプレースに送信することもできます。</span><span class="sxs-lookup"><span data-stu-id="ca9ed-119">They can also submit apps to the Microsoft AppSource marketplace.</span></span> 

<span data-ttu-id="ca9ed-120">強化されたアプリケーション ライフサイクル管理の恩恵を受けられる一方、ユーザーが期待する分析ワークスペース エクスペリエンスは影響を受けずに残っています。</span><span class="sxs-lookup"><span data-stu-id="ca9ed-120">The analytical workspace experience that your users expect will remain unaffected while you get the benefit of better application lifecycle management.</span></span> <span data-ttu-id="ca9ed-121">分析ワークスペースを構築している ISV およびパートナーは、AppSource を通して Dynamics 365 の顧客にソリューションを販売できます。</span><span class="sxs-lookup"><span data-stu-id="ca9ed-121">ISVs and partners who build analytical workspaces can now market their solutions to Dynamics 365 customers through AppSource.</span></span>
<!--feature detail end -->












## <a name="see-also"></a><span data-ttu-id="ca9ed-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="ca9ed-122">See also</span></span>

[<span data-ttu-id="ca9ed-123">Power BI ソリューションを分析ワークスペースに直接埋め込む</span><span class="sxs-lookup"><span data-stu-id="ca9ed-123">Embed Power BI solutions directly into analytical workspaces</span></span>](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/analytics/select-analytical-workspace)
