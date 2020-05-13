---
title: 柔軟な倉庫レベルの分析コード引当
description: この機能強化により、在庫引当ポリシーが柔軟になり、バッチ管理される製品を販売し WMS 対応オペレーションとしてロジスティクスを実行する企業は、製品に関連付けられた在庫引当階層で禁じられている ("batch-below" と呼ばれるタイプになっている) 場合でも、顧客からの特定のバッチの要求を販売注文に登録できます。
author: relnotes
ms.reviewer: kamaybac
ms.date: 04/07/2020
ms.assetid: a3cd03d8-93cd-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: c92beee735b8a875e5e613edaf1861628ab1ce48
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320151"
---
# <a name="flexible-warehouse-level-dimension-reservation"></a><span data-ttu-id="61df0-103">柔軟な倉庫レベルの分析コード引当</span><span class="sxs-lookup"><span data-stu-id="61df0-103">Flexible warehouse-level dimension reservation</span></span>


| <span data-ttu-id="61df0-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="61df0-104">Enabled for</span></span>    |  <span data-ttu-id="61df0-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="61df0-105">Public preview</span></span> | <span data-ttu-id="61df0-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="61df0-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="61df0-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="61df0-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="61df0-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="61df0-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="61df0-109">2020 年 1 月 27 日</span><span class="sxs-lookup"><span data-stu-id="61df0-109">Jan 27, 2020</span></span>| <span data-ttu-id="61df0-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="61df0-110">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="61df0-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="61df0-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="61df0-112">顧客の要件に基づいてオーバーライドを設定できるようにしつつ、定型業務でのバッチ管理製品のピッキングに対する最適化に焦点を当てたアプローチを維持します。</span><span class="sxs-lookup"><span data-stu-id="61df0-112">Maintain the optimization-focused approach to picking batch-tracked products for routine operations while still being able to set overrides based on customer requirements.</span></span> <span data-ttu-id="61df0-113">製品の既定の引当ポリシーで、倉庫のピッキング工程が開始されるまでピッキングするバッチとその場所の決定を延期すると規定されている場合 (たとえば、在庫ストック戦略に対する最適化に焦点を当てたアプローチ) でも、その製品のバッチ番号を顧客の注文に対して事前に引き当てることができます。</span><span class="sxs-lookup"><span data-stu-id="61df0-113">Even when a product’s default reservation policy prescribes that decisions on which batches to pick and where to locate them within the warehouse are postponed until the warehouse picking operations start (for example, an optimization-focused approach to inventory stocking strategy), batch numbers for the same product can also be reserved up front for the customer’s order.</span></span> <span data-ttu-id="61df0-114">この機能により、バッチ番号の選択の大部分が倉庫で行われる製品に関して、在庫と倉庫の効率を妥協する必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="61df0-114">This functionality removes the need to compromise on inventory and warehouse efficiency for products whose batch number selection for the most part takes place in the warehouse.</span></span>

<span data-ttu-id="61df0-115">販売注文を受ける作業者は、顧客の要望に応えて特定のバッチ番号を再指定できます。</span><span class="sxs-lookup"><span data-stu-id="61df0-115">Allow workers who take sales orders to respect their customer’s request to reorder a specific batch number.</span></span> <span data-ttu-id="61df0-116">販売注文担当者は受注時にバッチ番号の記録と引当を行うことができます。そのバッチ番号が倉庫オペレーションで変更されたり別の需要に充てられたりすることはありません。</span><span class="sxs-lookup"><span data-stu-id="61df0-116">A batch number can be recorded and reserved at the order-taking time by the sales order processor, with no possibility of it changing during warehouse operations or it being committed to another demand.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="61df0-117">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="61df0-117">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="61df0-118">柔軟な倉庫レベルの分析コード引当には、次の機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="61df0-118">Flexible warehouse-level dimension reservation includes the following capabilities:</span></span>

- <span data-ttu-id="61df0-119">注文の製品数量に対して、それらの分析コードが製品の引当階層内で倉庫の場所の下にある場合に、特定の追跡用分析コードまたは倉庫保管分析コード値を引き当てることができます。(2019 年リリース ウェーブ 2 では、販売注文に対するバッチ番号の引当のみがサポートされます)。</span><span class="sxs-lookup"><span data-stu-id="61df0-119">Allow reservation of a specific tracking or warehouse storage dimension value for the product quantity on the demand order, when those dimensions are placed below warehouse location in the product’s reservation hierarchy (only batch number reservation on sales orders is supported in the 2019 release wave 2).</span></span>

- <span data-ttu-id="61df0-120">販売注文に対して引き当てられたバッチ番号は既存の WMS プロセスによって処理され、指定されたバッチがピッキングされて顧客に出荷されます。</span><span class="sxs-lookup"><span data-stu-id="61df0-120">Batch numbers as reserved for the sales order are handled by the existing WMS processes so that the committed batch is picked and shipped to the customer.</span></span>

- <span data-ttu-id="61df0-121">手持数量に対する販売注文からのバッチ引当のサポート。</span><span class="sxs-lookup"><span data-stu-id="61df0-121">Support for batch reservation from a sales order against on-hand quantities.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="61df0-122">関連項目</span><span class="sxs-lookup"><span data-stu-id="61df0-122">See also</span></span>

<!--docs start-->
<span data-ttu-id="61df0-123">[柔軟な倉庫レベル分析コードの引当ポリシー](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/flexible-warehouse-level-dimension-reservation) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="61df0-123">[Flexible warehouse-level dimension reservation policy](https://docs.microsoft.com/dynamics365/supply-chain/warehousing/flexible-warehouse-level-dimension-reservation) (docs)</span></span>
<!--docs end-->
