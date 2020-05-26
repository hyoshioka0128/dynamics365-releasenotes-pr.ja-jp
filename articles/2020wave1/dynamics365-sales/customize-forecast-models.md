---
title: 予測モデルのカスタマイズ
description: 柔軟な列モデリングを使用し、さまざまな組織構造をサポートして、クォータ管理と高度なフィルター処理の利点を活用しながら、ビジネス ニーズに応じてアクセスを管理できます。
author: relnotes
ms.reviewer: udag
ms.date: 04/15/2020
ms.assetid: e6c53181-4ad5-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: dandalla
dynamics365pdf: true
ms.openlocfilehash: 01fc98a30814e79c16904e609d64e90dd01557ae
ms.sourcegitcommit: d891d652909a155016d30391a09acbf4e20a756d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2020
ms.locfileid: "3294745"
---
# <a name="customize-forecast-models"></a><span data-ttu-id="ef251-103">予測モデルのカスタマイズ</span><span class="sxs-lookup"><span data-stu-id="ef251-103">Customize forecast models</span></span>


| <span data-ttu-id="ef251-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="ef251-104">Enabled for</span></span>    |  <span data-ttu-id="ef251-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ef251-105">Public preview</span></span> | <span data-ttu-id="ef251-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="ef251-106">Early access</span></span> | <span data-ttu-id="ef251-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="ef251-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="ef251-108">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="ef251-108">End users, automatically</span></span>|-|<span data-ttu-id="ef251-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ef251-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ef251-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="ef251-110">Feb 3, 2020</span></span>| <span data-ttu-id="ef251-111">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="ef251-111">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="ef251-112">2020 年 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="ef251-112">Apr 1, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ef251-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ef251-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ef251-114">多くの組織では、販売担当者に対し、最善の収益、最も可能性の高い収益、および最悪の収益を予測させるという、一般的な方法論が採用されていますが、業界、製品、および地域によって、このアプローチにはバリエーションがあります。</span><span class="sxs-lookup"><span data-stu-id="ef251-114">Although many organizations follow a common methodology of requiring sellers to forecast best, most likely, and worst-case revenue, there are variations to this approach across industries, products, and geographies.</span></span> <span data-ttu-id="ef251-115">ネイティブの予測機能では、柔軟な構成とフィルタリングが可能で、複数のタイプの予測、ロールアップ カテゴリ、および測定を使用することができます。</span><span class="sxs-lookup"><span data-stu-id="ef251-115">The native forecast capabilities provide flexible configurations and filtering to support multiple types of forecasting, rollup categories, and measurements.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ef251-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ef251-116">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="ef251-117">**柔軟な列モデリングを使用する**: カスタム ロールアップと計算列を作成できます。</span><span class="sxs-lookup"><span data-stu-id="ef251-117">**Use flexible column modeling**: Create custom rollup and calculated columns.</span></span>
- <span data-ttu-id="ef251-118">**さまざまな組織構造をサポートする**: 地域またはレポート階層に基づいて予測を作成できます。</span><span class="sxs-lookup"><span data-stu-id="ef251-118">**Support different organizational structures**: Create forecasts based on territory or reporting hierarchy.</span></span>
- <span data-ttu-id="ef251-119">**クォータ管理を利用する**: Excel テンプレートを使用して、予測グリッド内でクォータを有効にしたり、予測期間全体に対するクォータをアップロードすることができます。</span><span class="sxs-lookup"><span data-stu-id="ef251-119">**Benefit from quota management**: Enable quotas in the forecast grid or upload quotas for entire forecast time periods using an Excel template.</span></span>
- <span data-ttu-id="ef251-120">**高度なフィルタリングを利用する**: 制限を使用して、新しいクエリ ビルダーでの予測に含まれる、特定の営業案件を除外することができます。</span><span class="sxs-lookup"><span data-stu-id="ef251-120">**Benefit from advanced filtering**: Use limits to filter out specific opportunities included in the forecast with the new query builder.</span></span>
- <span data-ttu-id="ef251-121">**ビジネス ニーズに応じてセキュリティ モデリングを調整する**: 特定の予測モデルや予測フィールドにアクセスできるユーザーを選択できます。</span><span class="sxs-lookup"><span data-stu-id="ef251-121">**Adapt security modeling to meet business needs**: Select who has access to specific forecast models and fields.</span></span>
<!--feature detail end -->

<span data-ttu-id="ef251-122">![ビジネス ニーズを満たす予測を構成する](media/forecasting_configuringforecast.png "ビジネス ニーズを満たす予測を構成する")</span><span class="sxs-lookup"><span data-stu-id="ef251-122">![Configure the forecast to meet business needs](media/forecasting_configuringforecast.png "Configure the forecast to meet business needs")</span></span>
<!-- Picture 1 -->

> [!NOTE]
> <span data-ttu-id="ef251-123">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="ef251-123">This feature is available in the Unified Interface only.</span></span> <span data-ttu-id="ef251-124">この機能は、Dynamics 365 Sales Enterprise のみを対象としています。</span><span class="sxs-lookup"><span data-stu-id="ef251-124">This capability is intended only for Dynamics 365 Sales Enterprise.</span></span>







## <a name="see-also"></a><span data-ttu-id="ef251-125">関連項目</span><span class="sxs-lookup"><span data-stu-id="ef251-125">See also</span></span>

<!--blog start-->
<span data-ttu-id="ef251-126">[Dynamics 365 Sales の高度な予測による説明責任の推進](https://aka.ms/forecasting.blog) (ブログ)</span><span class="sxs-lookup"><span data-stu-id="ef251-126">[Driving accountability with advanced forecasting in Dynamics 365 Sales](https://aka.ms/forecasting.blog) (blog)</span></span>
<!--blog end-->

<!--docs start-->
<span data-ttu-id="ef251-127">[自社組織で予測機能を設定する](https://docs.microsoft.com/dynamics365/sales-enterprise/configure-forecast) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="ef251-127">[Configure forecasts in your organization](https://docs.microsoft.com/dynamics365/sales-enterprise/configure-forecast) (docs)</span></span>
<!--docs end-->
