---
title: セルフサービス展開でサポートされているサブレポート項目
description: セルフサービス展開でホストされているアプリケーション ソリューションで、サブレポート項目がサポートされるようになりました。
author: relnotes
ms.reviewer: kfend
ms.date: 05/21/2020
ms.assetid: 877a8a73-f69a-ea11-a811-000d3a579c34
ms.topic: article
ms.service: business-applications
ms.author: tjvass
dynamics365pdf: true
ms.openlocfilehash: 18f4f5935913a693773cb797d9960357a4ddbcba
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3416426"
---
# <a name="subreport-items-supported-in-self-service-deployments"></a><span data-ttu-id="d5780-103">セルフサービス展開でサポートされているサブレポート項目</span><span class="sxs-lookup"><span data-stu-id="d5780-103">Subreport items supported in self-service deployments</span></span>
[!include[finance-operations-crossapp-capabilities banner](../includes/finance-operations-crossapp-capabilities.md)]

| <span data-ttu-id="d5780-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="d5780-104">Enabled for</span></span>    |  <span data-ttu-id="d5780-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d5780-105">Public preview</span></span> | <span data-ttu-id="d5780-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="d5780-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d5780-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="d5780-107">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="d5780-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="d5780-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="d5780-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d5780-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d5780-110">サブレポート項目は、ドキュメントにヘッダーと本文の両方を含む、顧客支払提案レポートなどのソリューションにとって効果的なツールです。</span><span class="sxs-lookup"><span data-stu-id="d5780-110">Subreport items are an effective tool for solutions like the Customer payment proposals report that includes both a header and body in the document.</span></span><span data-ttu-id="d5780-111">サブレポートを使用すると、アプリケーション ソリューションでは、レポート パラメーターの評価に応じて、実行時にドキュメント ヘッダーを効率的に除外または追加できます。</span><span class="sxs-lookup"><span data-stu-id="d5780-111"> Using a subreport, the application solution is able to efficiently exclude or include the document header at runtime depending on an evaluation of the report parameters.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d5780-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d5780-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d5780-113">パートナーのフィードバックに応えて、セルフサービス展開にサブレポート項目を含むアプリケーション ソリューションのサポートを追加しました。</span><span class="sxs-lookup"><span data-stu-id="d5780-113">In response to partner feedback, we have added support for application solutions that include subreport items to self-service deployments.</span></span>  <span data-ttu-id="d5780-114">[サブレポート](https://docs.microsoft.com/sql/reporting-services/report-design/subreports-report-builder-and-ssrs?view=sql-server-ver15)項目を使用すると、設計者はレポート全体を別のレポートの本体に埋め込むことができます。</span><span class="sxs-lookup"><span data-stu-id="d5780-114">A [subreport](https://docs.microsoft.com/sql/reporting-services/report-design/subreports-report-builder-and-ssrs?view=sql-server-ver15) item allows the designer to embed an entire report inside the main body of another report.</span></span><span data-ttu-id="d5780-115">通常、これらは関連するデータ セットに基づくセクションを含むアプリケーション ソリューションで見られます。</span><span class="sxs-lookup"><span data-stu-id="d5780-115"> These are commonly found in application solutions that include sections based on a related data set.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="d5780-116">アプリケーション ソリューションの場合、Tablix コントロール内でサブレポート項目を使用することは推奨**されません**。</span><span class="sxs-lookup"><span data-stu-id="d5780-116">Using subreport items within a Tablix control is **not** recommended for application solutions.</span></span><span data-ttu-id="d5780-117">Tablix コントロール内にサブレポート項目を含むレポート デザイン定義は推奨されておらず、サービスでランタイム エラーが発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="d5780-117"> Report design definitions that include subreport items within a Tablix control are highly discouraged and may produce runtime errors in the service.</span></span>
<!--feature detail end -->









