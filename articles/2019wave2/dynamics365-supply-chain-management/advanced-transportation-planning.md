---
title: 高度な輸送計画
description: 輸送計画の目的で、複数の積荷を 1 つのトリップにグループ化できる新しいトリップの概念が導入されました。
author: relnotes
ms.reviewer: josaw
ms.date: 10/04/2019
ms.assetid: bc62278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: b1951b76fc841a7cf7ed19f48374201ae03bd2e4
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660549"
---
# <a name="advanced-transportation-planning"></a><span data-ttu-id="409eb-103">高度な輸送計画</span><span class="sxs-lookup"><span data-stu-id="409eb-103">Advanced transportation planning</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="409eb-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="409eb-104">Enabled for</span></span>    |  <span data-ttu-id="409eb-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="409eb-105">Public preview</span></span> | <span data-ttu-id="409eb-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="409eb-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="409eb-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="409eb-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="409eb-108">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="409eb-108">Jan 2020</span></span>| <span data-ttu-id="409eb-109">2020 年 3 月</span><span class="sxs-lookup"><span data-stu-id="409eb-109">Mar 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="409eb-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="409eb-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="409eb-111">出荷が物流施設に届くまでに複数の輸送区間を通る場合があります。</span><span class="sxs-lookup"><span data-stu-id="409eb-111">Sometimes shipments take multiple legs of transport to arrive at the distribution facility.</span></span> <span data-ttu-id="409eb-112">輸送計画の目的で、複数の積荷を 1 つのトリップにグループ化できる新しい*トリップ*の概念が導入されました。</span><span class="sxs-lookup"><span data-stu-id="409eb-112">A new concept of *trip* is introduced that allows multiple loads to be grouped together into a single trip for transportation planning purposes.</span></span> <span data-ttu-id="409eb-113">仕入先で発生した輸送に複数の区間が必要な場合 (たとえば、港まではトラック、海上は船舶、続いて物流施設へは別のトラックなど)、この輸送をモデル化するために 3 つの積荷を含む 1 つのトリップを作成できます。</span><span class="sxs-lookup"><span data-stu-id="409eb-113">If transport from the vendor origin requires multiple legs—for example, a truck to the port, then a ship across the ocean, followed by another truck to the distribution facility—one trip can be created containing three loads to model this transport.</span></span> <span data-ttu-id="409eb-114">個々の積荷はそれぞれ評価し追跡できますが、行程に関するすべての情報が 1 つのトリップ レコードで統合されます。</span><span class="sxs-lookup"><span data-stu-id="409eb-114">Each individual load can be rated and tracked, while the single trip record consolidates all of the information about the journey.</span></span>
<!--feature detail end -->









