---
title: 配送業者割り当て/ルート指定ウェーブ ステップ
description: AssignCarrierRate ステップが選択されているウェーブ テンプレートを使用して出荷がウェーブ処理されると、システムは関連する販売注文のレートショップを自動的に行い、最も安いレートを適用します。
author: relnotes
ms.reviewer: josaw
ms.date: 10/04/2019
ms.assetid: b862278d-615e-e911-a96c-000d3a1c7bbb
ms.topic: article
ms.service: business-applications
ms.author: mirzaab
dynamics365pdf: true
ms.openlocfilehash: 76af34d36a32fcfd37e2dad2356f38b3efd68d2d
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660561"
---
# <a name="carrier-assignmentrouting-wave-step"></a><span data-ttu-id="370b7-103">配送業者割り当て/ルート指定ウェーブ ステップ</span><span class="sxs-lookup"><span data-stu-id="370b7-103">Carrier assignment/routing wave step</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="370b7-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="370b7-104">Enabled for</span></span>    |  <span data-ttu-id="370b7-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="370b7-105">Public preview</span></span> | <span data-ttu-id="370b7-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="370b7-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="370b7-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="370b7-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="370b7-108">2020 年 1 月</span><span class="sxs-lookup"><span data-stu-id="370b7-108">Jan 2020</span></span>| <span data-ttu-id="370b7-109">2020 年 3 月</span><span class="sxs-lookup"><span data-stu-id="370b7-109">Mar 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="370b7-110">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="370b7-110">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="370b7-111">一部の流通業者は、注文が倉庫で処理されるときに輸送業者を割り当てる必要がありますが、このプロセスを手動で行うことを望んでいません。</span><span class="sxs-lookup"><span data-stu-id="370b7-111">Some distributors need to assign transport carriers to orders as they are processed through the warehouse but don’t want to do this process manually.</span></span> <span data-ttu-id="370b7-112">ウェーブ プロセス中に注文を自動的に評価できるようにする新しいウェーブ ステップが導入されました。</span><span class="sxs-lookup"><span data-stu-id="370b7-112">A new wave step is introduced that allows an order to rate automatically during the waving process.</span></span> <span data-ttu-id="370b7-113">AssignCarrierRate ステップが選択されているウェーブ テンプレートを使用して出荷がウェーブ処理されると、システムは関連する販売注文のレート ショップを自動的に行い、最も安いレートを適用します。</span><span class="sxs-lookup"><span data-stu-id="370b7-113">When a shipment is waved using a wave template that has the AssignCarrierRate step selected, the system will automatically rate shop the associated sales order and apply the cheapest rate.</span></span> <span data-ttu-id="370b7-114">注文が評価されると、残りの倉庫処理では割り当てられた配送業者/サービスを考慮して、注文を正しいドック ドアに送ったり、ラベルを印刷したりすることができます。</span><span class="sxs-lookup"><span data-stu-id="370b7-114">Once the order has been rated, the rest of the warehouse processing can take the assigned carrier/service into account to direct the order to the correct dock door, to print labels, and so on.</span></span>
<!--feature detail end -->









