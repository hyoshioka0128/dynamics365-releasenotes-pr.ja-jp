---
title: サンドボックス環境の AX 2012 のお客様向けのデータ アップグレード パッケージを適用する
description: 現在、AX 2012 のお客様は、リモート デスクトップを使用してデータ アップグレード パッケージを適用する必要があります。 この機能を使用すると、お客様は Lifecycle Services からそれらを適用できるようになります。
author: relnotes
ms.reviewer: sericks
ms.date: 03/16/2020
ms.assetid: c2e36cdb-5b53-ea11-a812-000d3a579c35
ms.topic: article
ms.service: business-applications
ms.author: laswenka
dynamics365pdf: true
ms.openlocfilehash: cd70dd12c4eb2c388589738d22b9f97e59b3d3ba
ms.sourcegitcommit: 32be8c144e80ce07a534527d80aba9db93795efe
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/01/2020
ms.locfileid: "3178771"
---
# <a name="apply-data-upgrade-packages-for-ax-2012-customers-on-sandbox-environments"></a><span data-ttu-id="66886-104">サンドボックス環境の AX 2012 のお客様向けのデータ アップグレード パッケージを適用する</span><span class="sxs-lookup"><span data-stu-id="66886-104">Apply data upgrade packages for AX 2012 customers on sandbox environments</span></span>


| <span data-ttu-id="66886-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="66886-105">Enabled for</span></span>    |  <span data-ttu-id="66886-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="66886-106">Public preview</span></span> | <span data-ttu-id="66886-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="66886-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="66886-108">管理者、作成者、またはアナリスト、自動的</span><span class="sxs-lookup"><span data-stu-id="66886-108">Admins, makers, or analysts, automatically</span></span>|-| <span data-ttu-id="66886-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="66886-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="66886-110">2020 年 3 月 16 日</span><span class="sxs-lookup"><span data-stu-id="66886-110">Mar 16, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="66886-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="66886-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="66886-112">お客様は、リモート デスクトップを使用してデータ アップグレード パッケージを適用する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="66886-112">Customers will no longer be required to use Remote Desktop to apply data upgrade packages.</span></span> <span data-ttu-id="66886-113">マイクロソフトではサンドボックス環境のリモート デスクトップ アクセスからの撤退を開始するため、これは重要です。</span><span class="sxs-lookup"><span data-stu-id="66886-113">This is important as we begin to move away from Remote Desktop access for sandbox environments.</span></span> <span data-ttu-id="66886-114">AX 2012 のアップグレード プロセスは、Lifecycle Services 内で直接行うと、より完全に有効になります。</span><span class="sxs-lookup"><span data-stu-id="66886-114">The AX 2012 upgrade process will become more fully enabled directly within Lifecycle Services.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="66886-115">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="66886-115">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="66886-116">お客様の新しい実装プロジェクトのオンボーディング中に、**レガシー システム** フィールドがあります。お客様は、このフィールドを使用して、プロジェクトを「AX 2012 アップグレード」タイプのプロジェクトとして識別できます。</span><span class="sxs-lookup"><span data-stu-id="66886-116">During customer onboarding for new implementation projects, there is a **Legacy System** field that customers can use to identify their project as an "AX 2012 upgrade" type project.</span></span> <span data-ttu-id="66886-117">そこから、現在 Lifecycle Services を介して利用可能な他のパッケージと同様に、お客様は Tier 2-5 サンドボックス環境で直接 **AX2012DataUpgrade** パッケージを表示して適用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="66886-117">From there, customers will have the ability to see and apply **AX2012DataUpgrade** packages directly on their Tier 2-5 sandbox environments, just like they would any other package available today via Lifecycle Services.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="66886-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="66886-118">See also</span></span>

<span data-ttu-id="66886-119">[AX 2012 からのアップグレード - サンドボックス環境でのデータ アップグレード](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/migration-upgrade/upgrade-data-sandbox) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="66886-119">[Upgrade from AX 2012 - Data upgrade in sandbox environments](https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/migration-upgrade/upgrade-data-sandbox) (docs)</span></span>
