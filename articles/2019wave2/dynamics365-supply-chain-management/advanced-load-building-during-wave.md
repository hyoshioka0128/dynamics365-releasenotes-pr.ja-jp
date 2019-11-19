---
title: ウェーブの間の高度な積荷構築
description: 高度な積荷構築により、ウェーブでは、条件を満たす積荷が存在する場合は出荷を既存の積荷に割り当てて、必要な場合は新しい積荷を作成することができます。
author: relnotes
ms.reviewer: josaw
ms.date: 10/04/2019
ms.assetid: 6662278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: c707b087329cff65c05e1110b28dd8391bc85787
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660550"
---
# <a name="advanced-load-building-during-a-wave"></a><span data-ttu-id="caa38-103">ウェーブの間の高度な積荷構築</span><span class="sxs-lookup"><span data-stu-id="caa38-103">Advanced load building during a wave</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="caa38-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="caa38-104">Enabled for</span></span>    |  <span data-ttu-id="caa38-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="caa38-105">Public preview</span></span> | <span data-ttu-id="caa38-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="caa38-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="caa38-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="caa38-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="caa38-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="caa38-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="caa38-109">2019 年 3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="caa38-109">Mar 4, 2019</span></span>| <span data-ttu-id="caa38-110">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="caa38-110">Jan 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="caa38-111">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="caa38-111">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="caa38-112">高度な積荷構築により、ウェーブでは、条件を満たす積荷が存在する場合は出荷を既存の積荷に割り当てて、必要な場合は新しい積荷を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="caa38-112">Advanced load building allows the wave to assign the shipment to an existing load, if one exists that meets the criteria, or create a new load if required.</span></span> <span data-ttu-id="caa38-113">この機能を使用すると、システムで、ビジネス ニーズに応じてルート、配送業者、またはその他の概念を表す積荷を自動的に構築することができます。</span><span class="sxs-lookup"><span data-stu-id="caa38-113">This feature allows for the system to automatically build loads to represent a route, carrier, or other concepts as needed by the business.</span></span> <span data-ttu-id="caa38-114">販売注文からの情報、または前のウェーブ ステップで作成されたコンテナーに基づいて、積荷を構築できます。</span><span class="sxs-lookup"><span data-stu-id="caa38-114">Loads can be built based on information from the sales order or containers created in an earlier wave step.</span></span> <span data-ttu-id="caa38-115">ルート計画機能を使用している場合、積荷構築は輸送管理とも統合されます。</span><span class="sxs-lookup"><span data-stu-id="caa38-115">Load building will also integrate with transportation management when using the route plan functionality.</span></span>
<!--feature detail end -->









