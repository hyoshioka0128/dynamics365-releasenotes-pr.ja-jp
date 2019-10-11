---
title: 配送業者割り当て/ルート指定ウェーブ ステップ
description: AssignCarrierRate ステップが選択されているウェーブ テンプレートを使用して出荷がウェーブ処理されると、システムは関連する販売注文のレート ショップを自動的に行い、最も安いレートを適用します。
author: relnotes
ms.reviewer: josaw
ms.date: 08/30/2019
ms.assetid: b862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 563ad74c7a9ce96ae6f5627e916765e0f5368bab
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2143265"
---
# <a name="carrier-assignmentrouting-wave-step"></a><span data-ttu-id="402bd-103">配送業者割り当て/ルート指定ウェーブ ステップ</span><span class="sxs-lookup"><span data-stu-id="402bd-103">Carrier assignment/routing wave step</span></span>
[!include[finance-operations banner](../includes/finance-operations.md)]

| <span data-ttu-id="402bd-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="402bd-104">Enabled for</span></span>    |  <span data-ttu-id="402bd-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="402bd-105">Public preview</span></span> | <span data-ttu-id="402bd-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="402bd-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="402bd-107">ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="402bd-107">Users by admins, makers, or analysts</span></span>|<span data-ttu-id="402bd-108">2019 年 11 月</span><span class="sxs-lookup"><span data-stu-id="402bd-108">Nov 2019</span></span>| <span data-ttu-id="402bd-109">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="402bd-109">Jan 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="402bd-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="402bd-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="402bd-111">一部の流通業者は、注文が倉庫で処理されるときに輸送業者を割り当てる必要がありますが、このプロセスを手動で行うことを望んでいません。</span><span class="sxs-lookup"><span data-stu-id="402bd-111">Some distributors need to assign transport carriers to orders as they are processed through the warehouse but don’t want to do this process manually.</span></span> <span data-ttu-id="402bd-112">ウェーブ プロセス中に注文を自動的に評価できるようにする新しいウェーブ ステップが導入されました。</span><span class="sxs-lookup"><span data-stu-id="402bd-112">A new wave step is introduced that allows an order to rate automatically during the waving process.</span></span> <span data-ttu-id="402bd-113">AssignCarrierRate ステップが選択されているウェーブ テンプレートを使用して出荷がウェーブ処理されると、システムは関連する販売注文のレート ショップを自動的に行い、最も安いレートを適用します。</span><span class="sxs-lookup"><span data-stu-id="402bd-113">When a shipment is waved using a wave template that has the AssignCarrierRate step selected, the system will automatically rate shop the associated sales order and apply the cheapest rate.</span></span> <span data-ttu-id="402bd-114">注文が評価されると、残りの倉庫処理では割り当てられた配送業者/サービスを考慮して、注文を正しいドック ドアに送ったり、ラベルを印刷したりすることができます。</span><span class="sxs-lookup"><span data-stu-id="402bd-114">Once the order has been rated, the rest of the warehouse processing can take the assigned carrier/service into account to direct the order to the correct dock door, to print labels, and so on.</span></span>
<!--feature detail end -->











