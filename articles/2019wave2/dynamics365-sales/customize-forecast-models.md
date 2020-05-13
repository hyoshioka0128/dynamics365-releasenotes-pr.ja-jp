---
title: 予測モデルのカスタマイズ
description: 柔軟な列モデリングを使用し、さまざまな組織構造をサポートして、クォータ管理と高度なフィルタリングの利点を活用しながら、ビジネス ニーズに応じてアクセスを管理できます。
author: relnotes
ms.reviewer: udag
ms.date: 03/21/2020
ms.assetid: bef5c15e-a638-ea11-a813-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: dandalla
dynamics365pdf: true
ms.openlocfilehash: cdcf2576eeb244111ea17e8279e14bf3c8cb9853
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178496"
---
# <a name="customize-forecast-models"></a><span data-ttu-id="3e35f-103">予測モデルのカスタマイズ</span><span class="sxs-lookup"><span data-stu-id="3e35f-103">Customize forecast models</span></span>


| <span data-ttu-id="3e35f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3e35f-104">Enabled for</span></span>    |  <span data-ttu-id="3e35f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3e35f-105">Public preview</span></span> | <span data-ttu-id="3e35f-106">早期アクセス</span><span class="sxs-lookup"><span data-stu-id="3e35f-106">Early access</span></span> | <span data-ttu-id="3e35f-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="3e35f-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |:----------: |
|<span data-ttu-id="3e35f-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="3e35f-108">End users by admins, makers, or analysts</span></span>|-|-| <span data-ttu-id="3e35f-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="3e35f-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="3e35f-110">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="3e35f-110">Feb 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3e35f-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3e35f-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3e35f-112">多くの組織では、販売担当者に対し、最善の収益、最も可能性の高い収益、および最悪の収益を予測させるという、一般的な方法論が採用されていますが、業界、製品、および地域によって、このアプローチにはバリエーションがあります。</span><span class="sxs-lookup"><span data-stu-id="3e35f-112">Although many organizations follow a common methodology of requiring sellers to forecast best, most likely, and worst-case revenue, there are variations to this approach across industries, products, and geographies.</span></span> <span data-ttu-id="3e35f-113">ネイティブの予測機能では、柔軟な構成とフィルタリングが可能で、複数のタイプの予測、ロールアップ カテゴリ、および測定を使用することができます。</span><span class="sxs-lookup"><span data-stu-id="3e35f-113">The native forecast capabilities provide flexible configurations and filtering to support multiple types of forecasting, rollup categories, and measurements.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3e35f-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3e35f-114">Feature details</span></span>
<!--feature detail start -->
- <span data-ttu-id="3e35f-115">**柔軟な列モデリングを使用する**: カスタム ロールアップと計算列を作成できます。</span><span class="sxs-lookup"><span data-stu-id="3e35f-115">**Use flexible column modeling**: Create custom rollup and calculated columns.</span></span>
- <span data-ttu-id="3e35f-116">**さまざまな組織構造をサポートする**: 製品、地域、またはレポート階層に基づいて予測を作成できます。</span><span class="sxs-lookup"><span data-stu-id="3e35f-116">**Support different organizational structures**: Create forecasts based on product, territory, or reporting hierarchy.</span></span>
- <span data-ttu-id="3e35f-117">**クォータ管理を利用する**: Excel テンプレートを使用して、予測グリッド内でクォータを有効にしたり、予測期間全体に対するクォータをアップロードすることができます。</span><span class="sxs-lookup"><span data-stu-id="3e35f-117">**Benefit from quota management**: Enable quotas in the forecast grid or upload quotas for entire forecast time periods using an Excel template.</span></span>
- <span data-ttu-id="3e35f-118">**高度なフィルタリングを利用する**: 制限を使用して、新しいクエリ ビルダーでの予測に含まれる、特定の営業案件を除外することができます。</span><span class="sxs-lookup"><span data-stu-id="3e35f-118">**Benefit from advanced filtering**: Use limits to filter out specific opportunities included in the forecast with the new query builder.</span></span>
- <span data-ttu-id="3e35f-119">**ビジネス ニーズに応じてセキュリティ モデリングを調整する**: 特定の予測モデルや予測フィールドにアクセスできるユーザーを選択できます。</span><span class="sxs-lookup"><span data-stu-id="3e35f-119">**Adapt security modeling to meet business needs**: Select who has access to specific forecast models and fields.</span></span>
<!--feature detail end -->


> [!NOTE]
> <span data-ttu-id="3e35f-120">この機能は、統一インターフェイスでのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="3e35f-120">This feature is available in the Unified Interface only.</span></span> <span data-ttu-id="3e35f-121">この機能は、Dynamics 365 Sales Enterprise のみを対象としています。</span><span class="sxs-lookup"><span data-stu-id="3e35f-121">This capability is intended only for Dynamics 365 Sales Enterprise.</span></span>







## <a name="see-also"></a><span data-ttu-id="3e35f-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="3e35f-122">See also</span></span>

<span data-ttu-id="3e35f-123">[レイアウトと列の選択](https://docs.microsoft.com/dynamics365/sales-enterprise/choose-layout-and-columns-forecast) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="3e35f-123">[Choose layout and columns](https://docs.microsoft.com/dynamics365/sales-enterprise/choose-layout-and-columns-forecast) (docs)</span></span>
