---
title: 会計統合フレームワークに基づくスウェーデン向けの制御ユニット統合サンプル
description: スウェーデンでは、キャッシュ レジスターに関する現地の規制に従い、すべての小売販売を、統合型の会計デバイス (制御ユニット) を備えたキャッシュ レジスターに登録する必要があります。 スウェーデン向けの制御ユニット統合サンプルでは、スウェーデンの市場で利用できる一般的な会計デバイス モデルの 1 つがサポートされています。 このサンプルは Retail SDK の一部であり、会計統合フレームワークを拡張するものです。
author: relnotes
ms.reviewer: josaw
ms.date: 10/04/2019
ms.assetid: 6e903f43-01e6-e911-a812-000d3a4f15f1
ms.topic: article
ms.service: business-applications
ms.author: epopov
dynamics365pdf: true
ms.openlocfilehash: 7fe4f83ad329d9589216380e5d9eac1e22692cea
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2659894"
---
# <a name="control-unit-integration-sample-for-sweden-based-on-the-fiscal-integration-framework"></a><span data-ttu-id="81100-105">会計統合フレームワークに基づくスウェーデン向けの制御ユニット統合サンプル</span><span class="sxs-lookup"><span data-stu-id="81100-105">Control unit integration sample for Sweden based on the fiscal integration framework</span></span> 
[!include[dynamics365-retail banner](../includes/dynamics365-retail.md)]

| <span data-ttu-id="81100-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="81100-106">Enabled for</span></span>    |  <span data-ttu-id="81100-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="81100-107">Public preview</span></span> | <span data-ttu-id="81100-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="81100-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="81100-109">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="81100-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="81100-110">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="81100-110">Oct 2019</span></span>| <span data-ttu-id="81100-111">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="81100-111">Jan 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="81100-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="81100-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="81100-113">スウェーデン向けの制御ユニット統合サンプルは、お客様が現地のキャッシュ レジスター規制に準拠した POS ソリューションを構築するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="81100-113">The control unit integration sample for Sweden can be used by customers to build their POS solutions that are compliant with the local cash register regulations.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="81100-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="81100-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="81100-115">スウェーデン向けの制御ユニット統合サンプルでは、[会計統合フレームワーク](https://docs.microsoft.com/dynamics365/retail/localizations/fiscal-integration-for-retail-channel)が使用されています。つまり、このサンプルは組み込みの会計統合機能をすべてサポートしており、ビルド後、そのままの構成で使用できます。</span><span class="sxs-lookup"><span data-stu-id="81100-115">The control unit integration sample for Sweden now takes advantage of the [fiscal integration framework](https://docs.microsoft.com/dynamics365/retail/localizations/fiscal-integration-for-retail-channel), which means that it supports all of the built-in fiscal integration capabilities, and it can be built and configured to be used as-is.</span></span> <span data-ttu-id="81100-116">また、お客様固有のビジネス プロセスや、制御ユニットのさまざまなモデルをサポートするために、カスタマイズや拡張を行うこともできます。</span><span class="sxs-lookup"><span data-stu-id="81100-116">It can also be customized or extended to support customer-specific business processes or different models of control units.</span></span> <span data-ttu-id="81100-117">このサンプルでは、さまざまな現金持ち帰り販売シナリオでの販売について会計統合を行うことができ、基本的なシナリオ (再試行が可能な場合など) や、より高度なシナリオ (それまでに制御ユニットに登録されていない完了取引の登録など) でのエラー処理オプションも用意されています。</span><span class="sxs-lookup"><span data-stu-id="81100-117">The sample enables fiscal registration of sales in various cash-and-carry sales scenarios and provides options for error handling in basic scenarios (such as when retry is possible) as well as more advanced scenarios, such as registering a previously completed transaction that was not previously registered in the control unit.</span></span>

<span data-ttu-id="81100-118">Retail 会計統合フレームワークを使用することで、多国籍の小売業者は、事業を展開する国や地域のさまざまな会計規制に準拠した、共通の POS ソリューションを構築することができます。</span><span class="sxs-lookup"><span data-stu-id="81100-118">The Retail fiscal integration framework provides multinational retailers with the possibility to build common POS solutions that are compliant with different local fiscal regulations in the countries or regions that they operate in.</span></span>
<!--feature detail end -->








