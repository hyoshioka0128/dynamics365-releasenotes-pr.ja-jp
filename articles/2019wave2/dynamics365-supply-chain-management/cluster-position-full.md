---
title: クラスター位置フル
description: この機能により、クラスター内のいずれかの作業単位で "フル" オプションを処理し、クラスター位置をフルとして宣言できるようになります。
author: relnotes
ms.reviewer: kamaybac
ms.date: 01/06/2020
ms.assetid: 7e62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 042746ad3c48350376def462a6218c1fa0378c75
ms.sourcegitcommit: 7d5d14ac84333ba166265755f410f7e16035a64e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/10/2020
ms.locfileid: "2948376"
---
# <a name="cluster-position-full"></a><span data-ttu-id="957d3-103">クラスター位置フル</span><span class="sxs-lookup"><span data-stu-id="957d3-103">Cluster position full</span></span>


| <span data-ttu-id="957d3-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="957d3-104">Enabled for</span></span>    |  <span data-ttu-id="957d3-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="957d3-105">Public preview</span></span> | <span data-ttu-id="957d3-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="957d3-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="957d3-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="957d3-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="957d3-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="957d3-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="957d3-109">2019 年 4 月 8 日</span><span class="sxs-lookup"><span data-stu-id="957d3-109">Apr 8, 2019</span></span>| <span data-ttu-id="957d3-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="957d3-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="957d3-111">2019 年 12 月 19 日</span><span class="sxs-lookup"><span data-stu-id="957d3-111">Dec 19, 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="957d3-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="957d3-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="957d3-113">クラスター ピッキングで使用される場合、この機能では、ピッキング作業を柔軟に中断する方法が提供され、コンテナーまたはトートの容積制約により大きな余裕が必要であることが認識されます。</span><span class="sxs-lookup"><span data-stu-id="957d3-113">When used with cluster picking, this feature offers a flexible manner of breaking the pick work and acknowledges the need for a larger margin of error in volumetric constraints of containers or totes.</span></span> <span data-ttu-id="957d3-114">この機能により、クラスター内のいずれかの作業単位で "フル" オプションを実行する機能が導入されます。</span><span class="sxs-lookup"><span data-stu-id="957d3-114">The functionality introduces the ability to execute the “full” option on one of the work units within a cluster.</span></span> <span data-ttu-id="957d3-115">その機能は、残りの作業をキャンセルする標準の "フル" ボタン フローとは異なります。</span><span class="sxs-lookup"><span data-stu-id="957d3-115">The feature differs from the standard “full” button flow in that it cancels the remaining work.</span></span> <span data-ttu-id="957d3-116">また、新しい作業は自動的に作成されないため、同じクラスターへの別のビンの追加は提示されません。</span><span class="sxs-lookup"><span data-stu-id="957d3-116">Additionally, it does not suggest adding another bin to the same cluster because it does not create new work automatically.</span></span>
<!--feature detail end -->




