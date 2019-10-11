---
title: POS 用の Regression Suite Automation Tool
description: POS 用の Regression Suite Automation Tool
author: mugunthanm
ms.reviewer: josaw
ms.date: 09/16/2019
ms.assetid: 6463278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 392d09b53cc7ab83308d2330362c24421373b969
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2141846"
---
# <a name="regression-suite-automation-tool-for-pos"></a><span data-ttu-id="20f24-103">POS 用の Regression Suite Automation Tool</span><span class="sxs-lookup"><span data-stu-id="20f24-103">Regression Suite Automation Tool for POS</span></span>
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="20f24-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="20f24-104">Enabled for</span></span>    |  <span data-ttu-id="20f24-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="20f24-105">Public preview</span></span> | <span data-ttu-id="20f24-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="20f24-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="20f24-107">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="20f24-107">Admins, makers, or analysts, automatically</span></span>|<span data-ttu-id="20f24-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="20f24-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="20f24-109">2019 年 9 月 3 日</span><span class="sxs-lookup"><span data-stu-id="20f24-109">Sep 3, 2019</span></span>| <span data-ttu-id="20f24-110">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="20f24-110">Nov 2019</span></span>|





## <a name="business-value"></a><span data-ttu-id="20f24-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="20f24-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="20f24-112">小売業者またはパートナーは、Lifecycle Services (LCS) のテスト レコーダーとビジネス プロセス モデラー (BPM) を使用して、販売時点管理 (POS) 用のユーザー受け入れテスト ライブラリを作成できます。</span><span class="sxs-lookup"><span data-stu-id="20f24-112">Retailers or partners can use test recorder and business process modeler (BPM) in Lifecycle Services (LCS) to create user acceptance test libraries for point of sale (POS).</span></span> <span data-ttu-id="20f24-113">タスク レコーダーはテスト ケースを記録するための強力なツールです。</span><span class="sxs-lookup"><span data-stu-id="20f24-113">Task recorder is a powerful tool for recording test cases.</span></span> <span data-ttu-id="20f24-114">その後、BPM を使用してビジネス プロセス別にテスト ケースを整理できます。</span><span class="sxs-lookup"><span data-stu-id="20f24-114">The test cases can then be organized by business process using BPM.</span></span> <span data-ttu-id="20f24-115">BPM を Azure DevOps と同期して、Azure DevOps プロジェクトのテスト ケース (テスト ステップを含む) を自動的に作成できます。</span><span class="sxs-lookup"><span data-stu-id="20f24-115">BPM can be synchronized with Azure DevOps to automatically create test cases (including test steps) in an Azure DevOps project.</span></span> <span data-ttu-id="20f24-116">その後、Azure DevOps はテスト構成およびテスト管理ツールとして使用でき、ユーザーはターゲットを絞ったテスト計画やテスト スイートを作成し、テストの実行を管理して、結果を調査することができます。</span><span class="sxs-lookup"><span data-stu-id="20f24-116">Azure DevOps can then serve as a test configuration and test management tool where users can create targeted test plans and test suites, manage the execution of tests, and investigate results.</span></span> <span data-ttu-id="20f24-117">テストでは、オムニチャネルのシナリオをサポートできます。たとえば、Retail で注文を作成し、POS を使って店舗で取得できます。</span><span class="sxs-lookup"><span data-stu-id="20f24-117">The test can support omnichannel scenarios; for example, create an order in Retail and pick up in a store using the POS.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="20f24-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="20f24-118">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="20f24-119">以下は、この機能で利用可能なエンドツーエンドのフローの例です。</span><span class="sxs-lookup"><span data-stu-id="20f24-119">The following is an example of the end-to-end flow that is available with this functionality:</span></span>

- <span data-ttu-id="20f24-120">POS にアクセスできる環境で、Web ブラウザーを使用して、ビジネス サイクル テストを作成して実行します。</span><span class="sxs-lookup"><span data-stu-id="20f24-120">Author and execute business cycle tests on any environment that can access POS and via a web browser.</span></span>

- <span data-ttu-id="20f24-121">運用データベースのコピーを使用して、サンドボックス環境に対してテストを実行します。</span><span class="sxs-lookup"><span data-stu-id="20f24-121">Run tests against sandbox environments with a copy of your production database.</span></span>

- <span data-ttu-id="20f24-122">一度記録し、異なるデータ セットや異なる法人で複数回再生します。</span><span class="sxs-lookup"><span data-stu-id="20f24-122">Record once, play back multiple times with different data sets, different legal entities.</span></span>

- <span data-ttu-id="20f24-123">予想される値に対して検証します。</span><span class="sxs-lookup"><span data-stu-id="20f24-123">Validate against expected values.</span></span> 

- <span data-ttu-id="20f24-124">あるテスト ケースから次のテスト ケースにパラメーターを渡すことで、テスト ケースを連結します (エンドツーエンド テスト)。</span><span class="sxs-lookup"><span data-stu-id="20f24-124">Chain-test cases (end-to-end test) by passing parameters from one test case to the next.</span></span>

- <span data-ttu-id="20f24-125">Azure DevOps を使用して、テスト スイートを管理し、テストを実行し、テスト結果を調査します。</span><span class="sxs-lookup"><span data-stu-id="20f24-125">Use Azure DevOps to manage test suites, test runs, and investigate test results.</span></span>

- <span data-ttu-id="20f24-126">次のようにして作成および配布します。</span><span class="sxs-lookup"><span data-stu-id="20f24-126">Author and distribute by doing the following:</span></span>

  - <span data-ttu-id="20f24-127">テスト計画を構成します。</span><span class="sxs-lookup"><span data-stu-id="20f24-127">Configure the test plan.</span></span>

  - <span data-ttu-id="20f24-128">テストを実行して結果を管理します。</span><span class="sxs-lookup"><span data-stu-id="20f24-128">Execute tests and manage results.</span></span>
<!--feature detail end -->












## <a name="see-also"></a><span data-ttu-id="20f24-129">関連項目</span><span class="sxs-lookup"><span data-stu-id="20f24-129">See also</span></span>

<span data-ttu-id="20f24-130">[Retail Cloud POS 用のテスト レコーダーと Regression Suite Automation Tool](https://docs.microsoft.com/dynamics365/unified-operations/retail/dev-itpro/pos-rsat) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="20f24-130">[Test recorder and Regression suite automation tool for Retail Cloud POS](https://docs.microsoft.com/dynamics365/unified-operations/retail/dev-itpro/pos-rsat) (docs)</span></span>
