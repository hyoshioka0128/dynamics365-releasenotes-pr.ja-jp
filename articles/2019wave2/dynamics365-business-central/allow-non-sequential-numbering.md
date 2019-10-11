---
title: 連続しない番号を許容する
description: 事前定義された番号シリーズからレコードに割り当てられる番号のギャップを許容できるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 08/29/2019
ms.assetid: d07f6b3c-fec7-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: bnielse
dynamics365pdf: true
ms.openlocfilehash: 3d4e77d8d82c9b37504f723c910fff23842a8af0
ms.sourcegitcommit: de6f7e8aa90101a730c0109e3578b9131cd3c6cc
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2019
ms.locfileid: "2140746"
---
# <a name="allow-non-sequential-numbering"></a><span data-ttu-id="18bc2-103">連続しない番号を許容する</span><span class="sxs-lookup"><span data-stu-id="18bc2-103">Allow non-sequential numbering</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="18bc2-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="18bc2-104">Enabled for</span></span>    |  <span data-ttu-id="18bc2-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="18bc2-105">Public preview</span></span> | <span data-ttu-id="18bc2-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="18bc2-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="18bc2-107">ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="18bc2-107">Users, automatically</span></span>|-| <span data-ttu-id="18bc2-108">2019 年 10 月</span><span class="sxs-lookup"><span data-stu-id="18bc2-108">Oct 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="18bc2-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="18bc2-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="18bc2-110">顧客カードや倉庫内での活動など、多くのタイプのレコードでは、割り当てられた番号が順番どおりであることは法的要件ではありません。</span><span class="sxs-lookup"><span data-stu-id="18bc2-110">For many types of records, such as customer cards and warehouse activities, it is not a legal requirement that the assigned numbers are in sequence.</span></span> <span data-ttu-id="18bc2-111">システムのパフォーマンスを改善し、ユーザーがレコードを柔軟に削除できるように、連続しない番号が割り当てられることを許容するように番号シリーズを設定できます。</span><span class="sxs-lookup"><span data-stu-id="18bc2-111">To improve system performance and to give users flexibility to delete records, you can set up a number series to allow the assigned numbers to not be in sequence.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="18bc2-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="18bc2-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="18bc2-113">番号シリーズの**番号シリーズ明細行**ページでは、**番号のギャップを許可する**チェック ボックスを選択すると、番号の自動または手動割り当ての際に連続しない番号が割り当てられることを許容します。</span><span class="sxs-lookup"><span data-stu-id="18bc2-113">On the **No. Series Lines** page for a number series, you can select the **Allow Gaps in Nos.** check box to enable automatic or manual assignment of numbers without requiring sequential numbers.</span></span> <span data-ttu-id="18bc2-114">これにより、システムが番号シリーズから新しい番号を作成して使用する間、**番号シリーズ明細行**テーブルがロックされているときに発生する、潜在的なパフォーマンスの問題を回避できます。</span><span class="sxs-lookup"><span data-stu-id="18bc2-114">This avoids potential performance issues that occur when the **No. Series Line** table is locked while the system creates and consumes a new number from a number series.</span></span> <span data-ttu-id="18bc2-115">さらに、使われなくなった銀行口座のカードなどのレコードをユーザーが柔軟に削除できるようになるため、レコードの番号付きリストにギャップが生じます。</span><span class="sxs-lookup"><span data-stu-id="18bc2-115">In addition, it gives users flexibility to delete records, such as an obsolete bank account card, and thereby causing gaps in the numbered list of records.</span></span> 

> [!NOTE]
> <span data-ttu-id="18bc2-116">特定の番号シリーズでギャップを許容する場合は、まず監査人または会計マネージャーに相談して、その国または地域の法的要件を遵守していることを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="18bc2-116">If you want to allow gaps in certain number series, you should first consult with your auditor or accounting manager to ensure that you adhere to the legal requirements in your country or region.</span></span>

<span data-ttu-id="18bc2-117">連続しない番号の割り当てには、SQL サーバーの優先順位ロジックを活用します。</span><span class="sxs-lookup"><span data-stu-id="18bc2-117">The non-sequential assignment of numbers leverages the sequencing logic of the SQL server.</span></span> <span data-ttu-id="18bc2-118">詳細については、「[ロックフリー番号シリーズ](lock-free-number-series.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="18bc2-118">For more information, see [Lock-free number series](lock-free-number-series.md).</span></span>

<span data-ttu-id="18bc2-119">![番号付けのギャップを許容する](media/allow_gaps_in_no_series_lines.png "番号付けのギャップを許容する")</span><span class="sxs-lookup"><span data-stu-id="18bc2-119">![Allow gaps in numbering](media/allow_gaps_in_no_series_lines.png "Allow gaps in numbering")</span></span>

<!--feature detail end -->





