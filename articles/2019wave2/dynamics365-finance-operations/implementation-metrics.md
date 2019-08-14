---
title: 実装メトリック
description: 実装メトリック
author: relnotes
ms.reviewer: kfend
ms.date: 07/31/2019
ms.assetid: 0c63278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: meeram
dynamics365pdf: true
ms.openlocfilehash: a93e3a6f88e206ea733a1e4284728073832c7b10
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1855243"
---
# <a name="implementation-metrics"></a><span data-ttu-id="59156-103">実装メトリック</span><span class="sxs-lookup"><span data-stu-id="59156-103">Implementation metrics</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="59156-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="59156-104">Enabled for</span></span>    |  <span data-ttu-id="59156-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="59156-105">Public preview</span></span> | <span data-ttu-id="59156-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="59156-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="59156-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="59156-107">Admins, makers, or analysts, automatically</span></span>|| <span data-ttu-id="59156-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="59156-108">February 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="59156-109">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="59156-109">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="59156-110">Dynamics 365 Finance and Operations では、パートナー、お客様、ISV による柔軟で広範なカスタマイズがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="59156-110">Dynamics 365 Finance and Operations supports flexible and extensive customizations from our partners, customers, and ISVs.</span></span> <span data-ttu-id="59156-111">多くの場合、お客様はプロジェクトで複数の ISV のコードを使用します。</span><span class="sxs-lookup"><span data-stu-id="59156-111">Often, customers have code from multiple ISVs in their project.</span></span> <span data-ttu-id="59156-112">これにより、高い可用性と信頼性を備えたサービスの品質を維持するには、実稼働インスタンス内のすべてのコードに厳密な品質水準が必要となります。</span><span class="sxs-lookup"><span data-stu-id="59156-112">This calls for rigorous quality gates across all code in a production instance to ensure that we maintain quality of service with high availability and reliability.</span></span> <span data-ttu-id="59156-113">実装を評価するための新しい必須フェーズが、パートナーとシステム インテグレーターのライフサイクルに導入されます。</span><span class="sxs-lookup"><span data-stu-id="59156-113">We are introducing a new mandatory phase in the lifecycle for our partners and system integrators to evaluate their implementation.</span></span> <span data-ttu-id="59156-114">パートナーは、サンドボックスおよび運用環境における静的分析と実行時分析の両方に基づいたメトリックを、Lifecycle Services 内から使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="59156-114">Metrics, based on both static and runtime analysis in sandbox and production environments, will be made available to partners from within Lifecycle Services.</span></span> <span data-ttu-id="59156-115">分析と詳細ログにはエラーと警告が含まれます。</span><span class="sxs-lookup"><span data-stu-id="59156-115">The analysis and detailed logs will include errors and warnings.</span></span> <span data-ttu-id="59156-116">未解決のエラーがあると、コードを運用環境に移動してデプロイすることはできません。</span><span class="sxs-lookup"><span data-stu-id="59156-116">Unresolved errors will prevent the code from being moved and deployed to production.</span></span> <span data-ttu-id="59156-117">カスタマイズによって一般的に使用されるシナリオの生産性がどのように妨げられたかを示すために、特定のパフォーマンス ベンチマークも利用できます。</span><span class="sxs-lookup"><span data-stu-id="59156-117">Specific performance benchmarking will also be available to indicate how customizations have deterred productivity for commonly used scenarios.</span></span>
<!--feature detail end -->











