---
title: 小売チャネル間での支払管理の一貫性
description: オムニチャネルの小売では、注文の支払いを管理するときに一貫性が必要です。 チャネル間での払戻の処理、支払いの変更、ポリシーの有効化では、一貫性が必要です。
author: relnotes
ms.reviewer: josaw
ms.date: 01/10/2020
ms.assetid: ce1a4e4d-426c-e911-a95f-000d3a4f36ce
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: a5a7354531844bc00211e7035e46e75ed3108982
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986647"
---
# <a name="consistency-in-payments-management-across-retail-channels"></a><span data-ttu-id="f02d8-104">小売チャネル間での支払管理の一貫性</span><span class="sxs-lookup"><span data-stu-id="f02d8-104">Consistency in payments management across retail channels</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="f02d8-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="f02d8-105">Enabled for</span></span>    |  <span data-ttu-id="f02d8-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f02d8-106">Public preview</span></span> | <span data-ttu-id="f02d8-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="f02d8-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f02d8-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="f02d8-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="f02d8-109">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="f02d8-109">May 2020</span></span>| <span data-ttu-id="f02d8-110">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="f02d8-110">Aug 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="f02d8-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f02d8-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f02d8-112">小売業者は、すべてのチャネルにわたって同じレベルの顧客サービスを提供すると同時に、バック オフィスの従業員がこれらの小売注文を管理するときのエクスペリエンスが一貫するようにしたいと考えています。</span><span class="sxs-lookup"><span data-stu-id="f02d8-112">Retailers want to provide the same level of customer service across all channels, while at the same time ensure that back office employees have a consistent experience when managing retail orders.</span></span> <span data-ttu-id="f02d8-113">小売注文処理インターフェイスのどこかで、一貫した方法で、販売注文に関連する支払い取引を表示、変更、または処理できることが不可欠です。</span><span class="sxs-lookup"><span data-stu-id="f02d8-113">It is imperative that payment transactions related to sales orders can be viewed, modified, or processed by any of our retail order processing interfaces in a consistent way.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f02d8-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f02d8-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f02d8-115">この機能では、以前はコール センター チャネルによってのみ使用されていた既存の MCRCustPaym\* テーブルを使用した、POS (販売時点管理) および eコマースの注文支払いのバックオフィス管理が可能になります。</span><span class="sxs-lookup"><span data-stu-id="f02d8-115">This feature will enable back office management of point of sale (POS) and e-commerce order payments using the existing MCRCustPaym\* tables previously only used by the call center channel.</span></span> <span data-ttu-id="f02d8-116">小売販売注文の支払いデータを一貫した方法で管理することにより、コール センターのユーザーは真のオムニチャネル小売注文支払い管理が可能になります。</span><span class="sxs-lookup"><span data-stu-id="f02d8-116">By managing our retail sales order payment data in a consistent way, we will allow for true omnichannel retail order payment management for call center users.</span></span>
<!--feature detail end -->









