---
title: POS 周辺機器の店内正常性チェック
description: この機能は接続された周辺機器の販売時点情報管理 (POS) から実行する正常性チェックを導入します。 今後 POS のユーザーは、接続されたデバイスの現在の状態を表示したり、デバイスとの通信実行に起因するエラーを確認したりすることができます。 さらに正常性チェック機能を拡張して、POS が依存するサービスの正常性チェックをサポートしたり、追加の周辺機器やそれに関連するシナリオをテストしたりすることもできます。
author: relnotes
ms.reviewer: josaw
ms.date: 03/30/2020
ms.assetid: 51b64564-a4ca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: 3e6d37cf974e9a817e72216202325f92941e03be
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219460"
---
# <a name="in-store-health-check-for-pos-peripherals"></a><span data-ttu-id="d04a3-105">POS 周辺機器の店内正常性チェック</span><span class="sxs-lookup"><span data-stu-id="d04a3-105">In-store health check for POS peripherals</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="d04a3-106">有効対象</span><span class="sxs-lookup"><span data-stu-id="d04a3-106">Enabled for</span></span>    |  <span data-ttu-id="d04a3-107">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="d04a3-107">Public preview</span></span> | <span data-ttu-id="d04a3-108">一般提供</span><span class="sxs-lookup"><span data-stu-id="d04a3-108">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="d04a3-109">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="d04a3-109">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="d04a3-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="d04a3-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="d04a3-111">2020 年 2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="d04a3-111">Feb 28, 2020</span></span>| <span data-ttu-id="d04a3-112">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="d04a3-112">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="d04a3-113">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="d04a3-113">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="d04a3-114">この機能を使用すると、小売周辺機器に対してすぐに使用できる基本的な検証が有効になり、小売業者はデバイスがトランザクション フロー外で適切に動作していることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="d04a3-114">This feature enables basic out-of-the-box validation for retail peripherals to allow retailers to ensure that devices are working properly outside of transactional flows.</span></span> <span data-ttu-id="d04a3-115">問題を事前に検出する機能は、販売時の顧客と小売店スタッフの混乱を回避するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d04a3-115">The ability to proactively detect issues helps to avoid customer and retail associate confusion at the time of sale.</span></span> <span data-ttu-id="d04a3-116">正常性チェックを拡張して特定の周辺サービスまたはカスタム デバイスをチェックすることもできるため、小売業者は個々のニーズに合わせて正常性チェックを調整できます。</span><span class="sxs-lookup"><span data-stu-id="d04a3-116">The health check can also be extended to check specific peripheral services or custom devices so that retailers can tailor the health check to meet their individual needs.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="d04a3-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="d04a3-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="d04a3-118">正常性チェックは、販売時点管理の新しい操作であり、アドホックで実行したり、開店のシフトなどの特定のフローの一部として実行するようにカスタマイズしたりできます。</span><span class="sxs-lookup"><span data-stu-id="d04a3-118">The health check is a new operation for the point of sale that can be run ad hoc or customized to run as part of certain flows such as shift opening.</span></span> <span data-ttu-id="d04a3-119">特定のエラーをカスタマイズして、レジ係や店員に問題を自分で解決する方法に関する具体的な情報や、問題を報告する方法に関する詳細情報を提供できます。</span><span class="sxs-lookup"><span data-stu-id="d04a3-119">Specific errors can be customized to provide the cashier or store associate specific information for how to resolve the issue on their own or to provide detailed information on how to report the issue.</span></span>
<!--feature detail end -->









