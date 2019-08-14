---
title: 高度な輸送計画
description: 輸送計画の目的で、複数の積荷を 1 つのトリップにグループ化できる新しいトリップの概念が導入されました。
author: relnotes
ms.reviewer: josaw
ms.date: 07/31/2019
ms.assetid: bc62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: dc83c521ab20f1a8656700923977e12779af7b37
ms.sourcegitcommit: 2fe3cfa4d291dfe6492f1095c2f01a4fd8b7719a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/02/2019
ms.locfileid: "1854121"
---
# <a name="advanced-transportation-planning"></a><span data-ttu-id="598a0-103">高度な輸送計画</span><span class="sxs-lookup"><span data-stu-id="598a0-103">Advanced transportation planning</span></span>
[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

| <span data-ttu-id="598a0-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="598a0-104">Enabled for</span></span>    |  <span data-ttu-id="598a0-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="598a0-105">Public preview</span></span> | <span data-ttu-id="598a0-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="598a0-106">General availability</span></span> | 
| ---------- | ---------- |---------- |
|<span data-ttu-id="598a0-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="598a0-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="598a0-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="598a0-108">October 2019</span></span>| <span data-ttu-id="598a0-109">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="598a0-109">November 2019</span></span>|






## <a name="feature-details"></a><span data-ttu-id="598a0-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="598a0-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="598a0-111">出荷が物流施設に届くまでに複数の輸送区間を通る場合があります。</span><span class="sxs-lookup"><span data-stu-id="598a0-111">Sometimes shipments take multiple legs of transport to arrive at the distribution facility.</span></span> <span data-ttu-id="598a0-112">輸送計画の目的で、複数の積荷を 1 つのトリップにグループ化できる新しい "トリップ" の概念が導入されました。</span><span class="sxs-lookup"><span data-stu-id="598a0-112">A new concept of “trip” is introduced that allows multiple loads to be grouped together into a single trip for transportation planning purposes.</span></span> <span data-ttu-id="598a0-113">仕入先で発生した輸送に複数の区間が必要な場合 (たとえば、港まではトラック、海上は船舶、続いて物流施設へは別のトラックなど)、この輸送をモデル化するために 3 つの積荷を含む 1 つのトリップを作成できます。</span><span class="sxs-lookup"><span data-stu-id="598a0-113">If transport from the vendor origin requires multiple legs—for example, a truck to the port, then a ship across the ocean, followed by another truck to the distribution facility—one trip can be created containing three loads to model this transport.</span></span> <span data-ttu-id="598a0-114">個々の積荷はそれぞれ個別に評価し追跡できますが、行程に関するすべての情報が 1 つのトリップ レコードで統合されます。</span><span class="sxs-lookup"><span data-stu-id="598a0-114">Each individual load can be rated and tracked individually, while the single trip record consolidates all of the information about the journey.</span></span>
<!--feature detail end -->











