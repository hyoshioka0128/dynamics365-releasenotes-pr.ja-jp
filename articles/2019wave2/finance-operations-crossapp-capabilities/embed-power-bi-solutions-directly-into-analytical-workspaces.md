---
title: Power BI ソリューションを分析ワークスペースに直接埋め込む
description: Power BI でホストされている会社のソリューションを、アプリケーション ワークスペースに直接埋め込みます
author: relnotes
ms.reviewer: kfend
ms.date: 11/15/2019
ms.assetid: f862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: tjvass
dynamics365pdf: true
ms.openlocfilehash: 91bbccb81fbf29756f970f91e3641ccfd6a05cd5
ms.sourcegitcommit: b18d8ef2595c1298c94fe6a6fd1fceaa16bd9561
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/06/2019
ms.locfileid: "2893888"
---
# <a name="embed-power-bi-solutions-directly-into-analytical-workspaces"></a><span data-ttu-id="57394-103">Power BI ソリューションを分析ワークスペースに直接埋め込む</span><span class="sxs-lookup"><span data-stu-id="57394-103">Embed Power BI solutions directly into analytical workspaces</span></span>


| <span data-ttu-id="57394-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="57394-104">Enabled for</span></span>    |  <span data-ttu-id="57394-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="57394-105">Public preview</span></span> | <span data-ttu-id="57394-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="57394-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="57394-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="57394-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="57394-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="57394-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="57394-109">2019 年 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="57394-109">May 1, 2019</span></span>| <span data-ttu-id="57394-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="57394-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="57394-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="57394-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="57394-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="57394-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="57394-113">Finance and Operations アプリのパワー ユーザーは、Microsoft Power BI のレポートをアプリケーション ワークスペースに直接埋め込むことができます。</span><span class="sxs-lookup"><span data-stu-id="57394-113">Power users of Finance and Operations apps are able to embed Microsoft Power BI reports directly in application workspaces.</span></span> <span data-ttu-id="57394-114">お客様は Power BI サービスを使用してグラフィックが豊富な分析ソリューションを作成し、そのソリューションを組織のメンバーと共有することで、大きな成功を収めています。</span><span class="sxs-lookup"><span data-stu-id="57394-114">Customers are finding amazing success using the Power BI service to author graphically rich analytical solutions and then share the solutions with members of their organization.</span></span> <span data-ttu-id="57394-115">最新のプラットフォームの機能強化により、お客様は外部データ システムからのビューを含む可能性のある既存の Power BI ソリューションを統合することができます。</span><span class="sxs-lookup"><span data-stu-id="57394-115">The latest platform enhancement allows customers to integrate existing Power BI solutions that can include views sourced from external data systems.</span></span> <span data-ttu-id="57394-116">とりわけ、更新を配布するためにサービスを中断する必要がなく、お客様には Power BI でホストされている分析ソリューションの機能強化を自分のペースで公開できる柔軟性が提供されます。</span><span class="sxs-lookup"><span data-stu-id="57394-116">Best of all, there are no service interruptions required to distribute updates, giving customers greater flexibility to publish, at their own pace, enhancements to analytical solutions hosted on Power BI.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="57394-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="57394-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="57394-118">Finance and Operations の分析ワークスペースを使用すると、ユーザーはビジネス運営のコンテキストでリッチな視覚化を表示することができます。</span><span class="sxs-lookup"><span data-stu-id="57394-118">With analytical workspaces in Finance and Operations apps, users get rich visualizations shown in the context of business operations.</span></span> <span data-ttu-id="57394-119">Microsoft から提供される分析ワークスペースに加えて、ISV やパートナーも特別な分析用ワークスペースを構築しています。</span><span class="sxs-lookup"><span data-stu-id="57394-119">In addition to the analytical workspaces shipped by Microsoft, ISVs and partners have also built specialized analytical workspaces.</span></span> <span data-ttu-id="57394-120">ガイダンスとツールを使用して、パワー ユーザーは、エンティティ ストアで作成された分析ワークスペースを、データ フローに基づく Power BI テンプレート アプリに移行できます。</span><span class="sxs-lookup"><span data-stu-id="57394-120">Using guidance and tools, power users can transition analytical workspaces authored with entity store into Power BI template apps based on data flows.</span></span> <span data-ttu-id="57394-121">アプリを Microsoft AppSource マーケットプレースに送信することもできます。</span><span class="sxs-lookup"><span data-stu-id="57394-121">They can also submit apps to the Microsoft AppSource marketplace.</span></span> 

<span data-ttu-id="57394-122">強化されたアプリケーション ライフサイクル管理の恩恵を受けられる一方、ユーザーが期待する分析ワークスペース エクスペリエンスは影響を受けずに残っています。</span><span class="sxs-lookup"><span data-stu-id="57394-122">The analytical workspace experience that your users expect will remain unaffected while you get the benefit of better application lifecycle management.</span></span> <span data-ttu-id="57394-123">分析ワークスペースを構築している ISV およびパートナーは、AppSource を通して Dynamics 365 の顧客にソリューションを販売できます。</span><span class="sxs-lookup"><span data-stu-id="57394-123">ISVs and partners who build analytical workspaces can now market their solutions to Dynamics 365 customers through AppSource.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="57394-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="57394-124">See also</span></span>

<span data-ttu-id="57394-125">[PowerBI.com から分析ワークスペースを選択する](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/analytics/select-analytical-workspace) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="57394-125">[Select analytical workspaces from PowerBI.com](https://docs.microsoft.com/dynamics365/unified-operations/dev-itpro/analytics/select-analytical-workspace) (docs)</span></span>
