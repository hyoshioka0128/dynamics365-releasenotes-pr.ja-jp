---
title: 柔軟な倉庫レベルの分析コード引当
description: この機能強化により、在庫引当ポリシーが柔軟になり、バッチ管理される製品を販売し WMS 対応オペレーションとしてロジスティクスを実行する企業は、製品に関連付けられた在庫引当階層で禁じられている ("batch-below" と呼ばれるタイプになっている) 場合でも、顧客からの特定のバッチの要求を販売注文に登録できます。
author: relnotes
ms.reviewer: josaw
ms.date: 10/15/2019
ms.assetid: a3cd03d8-93cd-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: omulvad
dynamics365pdf: true
ms.openlocfilehash: 8cf087e8ee537e34d26134b0a84c2a1ebde3ab01
ms.sourcegitcommit: 6fd581a9afe3da3ded441e8254d1f30737187afc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/25/2019
ms.locfileid: "2660558"
---
# <a name="flexible-warehouse-level-dimension-reservation"></a><span data-ttu-id="f582f-103">柔軟な倉庫レベルの分析コード引当</span><span class="sxs-lookup"><span data-stu-id="f582f-103">Flexible warehouse-level dimension reservation</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="f582f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f582f-104">Enabled for</span></span>    |  <span data-ttu-id="f582f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f582f-105">Public preview</span></span> | <span data-ttu-id="f582f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f582f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f582f-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="f582f-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="f582f-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="f582f-108">Oct 2019</span></span>| <span data-ttu-id="f582f-109">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="f582f-109">Feb 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="f582f-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f582f-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f582f-111">顧客の要件に基づいてオーバーライドを設定できるようにしつつ、定型業務でのバッチ管理製品のピッキングに対する最適化に焦点を当てたアプローチを維持します。</span><span class="sxs-lookup"><span data-stu-id="f582f-111">Maintain the optimization-focused approach to picking batch-tracked products for routine operations while still being able to set overrides based on customer requirements.</span></span> <span data-ttu-id="f582f-112">製品の既定の引当ポリシーで、倉庫のピッキング工程が開始されるまでピッキングするバッチとその場所の決定を延期すると規定されている場合 (たとえば、在庫ストック戦略に対する最適化に焦点を当てたアプローチ) でも、その製品のバッチ番号を顧客の注文に対して事前に引き当てることができます。</span><span class="sxs-lookup"><span data-stu-id="f582f-112">Even when a product’s default reservation policy prescribes that decisions on which batches to pick and where to locate them within the warehouse are postponed until the warehouse picking operations start (for example, an optimization-focused approach to inventory stocking strategy), batch numbers for the same product can also be reserved up front for the customer’s order.</span></span> <span data-ttu-id="f582f-113">この機能により、バッチ番号の選択の大部分が倉庫で行われる製品に関して、在庫と倉庫の効率を妥協する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="f582f-113">This functionality removes the need to compromise on inventory and warehouse efficiency for products whose batch number selection for the most part takes place in the warehouse.</span></span>

<span data-ttu-id="f582f-114">販売注文を受ける作業者は、顧客の要望に応えて特定のバッチ番号を再指定できます。</span><span class="sxs-lookup"><span data-stu-id="f582f-114">Allow workers who take sales orders to respect their customer’s request to reorder a specific batch number.</span></span> <span data-ttu-id="f582f-115">販売注文担当者は受注時にバッチ番号の記録と引当を行うことができます。そのバッチ番号が倉庫オペレーションで変更されたり別の需要に充てられたりすることはありません。</span><span class="sxs-lookup"><span data-stu-id="f582f-115">A batch number can be recorded and reserved at the order-taking time by the sales order processor, with no possibility of it changing during warehouse operations or it being committed to another demand.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f582f-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f582f-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f582f-117">柔軟な倉庫レベルの分析コード引当には、次の機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="f582f-117">Flexible warehouse-level dimension reservation includes the following capabilities:</span></span>

- <span data-ttu-id="f582f-118">注文の製品数量に対して、それらの分析コードが製品の引当階層内で倉庫の場所の下にある場合に、特定の追跡用分析コードまたは倉庫保管分析コード値を引き当てることができます。(2019 年リリース ウェーブ 2 では、販売注文に対するバッチ番号の引当のみがサポートされます)。</span><span class="sxs-lookup"><span data-stu-id="f582f-118">Allow reservation of a specific tracking or warehouse storage dimension value for the product quantity on the demand order, when those dimensions are placed below warehouse location in the product’s reservation hierarchy (only batch number reservation on sales orders is supported in the 2019 release wave 2).</span></span>

- <span data-ttu-id="f582f-119">販売注文に対して引き当てられたバッチ番号は既存の WMS プロセスによって処理され、指定されたバッチがピッキングされて顧客に出荷されます。</span><span class="sxs-lookup"><span data-stu-id="f582f-119">Batch numbers as reserved for the sales order are handled by the existing WMS processes so that the committed batch is picked and shipped to the customer.</span></span>

- <span data-ttu-id="f582f-120">手持数量に対する販売注文からのバッチ引当のサポート。</span><span class="sxs-lookup"><span data-stu-id="f582f-120">Support for batch reservation from a sales order against on-hand quantities.</span></span>
<!--feature detail end -->









