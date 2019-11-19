---
title: ピッキング明細行のグループ化
description: ピッキング明細行グループ化設定により、ユーザーはモバイル デバイス上で複数のピッキング明細行を動的にグループ化して単一のピッキング実行ステップに集約できます。
author: relnotes
ms.reviewer: josaw
ms.date: 10/04/2019
ms.assetid: 6a62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 165e1e52f231492a58dad066a128e390fd95fd80
ms.sourcegitcommit: 5d6e90743e29603bfc5d06566a6966de05931982
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/29/2019
ms.locfileid: "2668698"
---
# <a name="pick-line-grouping"></a><span data-ttu-id="b91da-103">ピッキング明細行のグループ化</span><span class="sxs-lookup"><span data-stu-id="b91da-103">Pick-line grouping</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="b91da-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b91da-104">Enabled for</span></span>    |  <span data-ttu-id="b91da-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b91da-105">Public preview</span></span> | <span data-ttu-id="b91da-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b91da-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b91da-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="b91da-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="b91da-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b91da-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b91da-109">2019 年 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="b91da-109">Mar 5, 2019</span></span>| <span data-ttu-id="b91da-110">2019 年 12 月</span><span class="sxs-lookup"><span data-stu-id="b91da-110">Dec 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="b91da-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b91da-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b91da-112">ピッキング明細行グループ化設定により、ユーザーはモバイル デバイス上で複数のピッキング明細行を動的にグループ化して単一のピッキング実行ステップに集約できます。</span><span class="sxs-lookup"><span data-stu-id="b91da-112">Pick-line grouping setup allows users to dynamically group together and aggregate multiple pick lines into a single pick execution step on a mobile device.</span></span> <span data-ttu-id="b91da-113">システムは、すべてのピッキング明細行を一致する分析コード セット (つまり、品目 ID と場所 ID) でグループ化します。ユーザーは、複数の一致するピッキング明細行を持つ 1 つの作業指示書に対し、ピッキング場所に 1 回だけアクセスする必要があります。</span><span class="sxs-lookup"><span data-stu-id="b91da-113">The system groups together all pick lines with a matching dimension set, namely item ID and location ID, and the user will only have to visit the pick location once for a single work order with multiple matching pick lines.</span></span> <span data-ttu-id="b91da-114">この機能により、ピッキング作業をすばやく実行でき、特定のシナリオでの作業者のピッキング パスが大幅に短縮されます。</span><span class="sxs-lookup"><span data-stu-id="b91da-114">This feature offers faster execution of picking work and reduces worker pick path significantly in certain scenarios.</span></span> <span data-ttu-id="b91da-115">この機能は、モバイル デバイスの設定を介して自動的に適用されます。</span><span class="sxs-lookup"><span data-stu-id="b91da-115">The functionality is applied automatically via the setup of the mobile device.</span></span> <span data-ttu-id="b91da-116">処理中の作業指示書のすべての一致するピッキング明細行および関連するトランザクションが、システムによって相互に更新されます。</span><span class="sxs-lookup"><span data-stu-id="b91da-116">All matching pick lines and associated transactions of the work order being processed will be updated by the system mutually.</span></span> <span data-ttu-id="b91da-117">作業指示書の構造は最初に作成されたままになり、明細行はクライアント内で集約されません。ただし、この機能を使用するには、ピッキング明細行を品目 ID で並べ替える必要があります。</span><span class="sxs-lookup"><span data-stu-id="b91da-117">The work order structure will remain as initially created, and the lines will not be aggregated within the client; however, the pick lines should be sorted by item ID for this functionality to work.</span></span>
<!--feature detail end -->









