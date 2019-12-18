---
title: 連続しない番号を許容する
description: 事前定義された番号シリーズからレコードに割り当てられる番号のギャップを許容できるようになりました。
author: relnotes
ms.reviewer: sgroespe
ms.date: 11/15/2019
ms.assetid: d07f6b3c-fec7-e911-a96f-000d3a4f33c1
ms.topic: article
ms.service: business-applications
ms.author: bnielse
dynamics365pdf: true
ms.openlocfilehash: 0a9b189a14dc912436f8709732be56b9ead008a4
ms.sourcegitcommit: 8576a2025aaee545bbfc7d3c91de5bec2054639c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/05/2019
ms.locfileid: "2892297"
---
# <a name="allow-non-sequential-numbering"></a><span data-ttu-id="6e6e1-103">連続しない番号を許容する</span><span class="sxs-lookup"><span data-stu-id="6e6e1-103">Allow non-sequential numbering</span></span>


| <span data-ttu-id="6e6e1-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="6e6e1-104">Enabled for</span></span>    |  <span data-ttu-id="6e6e1-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="6e6e1-105">Public preview</span></span> | <span data-ttu-id="6e6e1-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="6e6e1-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="6e6e1-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="6e6e1-107">End users, automatically</span></span>|-| <span data-ttu-id="6e6e1-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="6e6e1-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="6e6e1-109">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="6e6e1-109">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="6e6e1-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="6e6e1-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="6e6e1-111">顧客カードや倉庫内での活動など、多くのタイプのレコードでは、割り当てられた番号が順番どおりであることは法的要件ではありません。</span><span class="sxs-lookup"><span data-stu-id="6e6e1-111">For many types of records, such as customer cards and warehouse activities, it is not a legal requirement that the assigned numbers are in sequence.</span></span> <span data-ttu-id="6e6e1-112">システムのパフォーマンスを改善し、ユーザーがレコードを柔軟に削除できるように、連続しない番号が割り当てられることを許容するように番号シリーズを設定できます。</span><span class="sxs-lookup"><span data-stu-id="6e6e1-112">To improve system performance and to give users flexibility to delete records, you can set up a number series to allow the assigned numbers to not be in sequence.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="6e6e1-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="6e6e1-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="6e6e1-114">番号シリーズの**番号シリーズ明細行**ページでは、**番号のギャップを許可する**チェック ボックスを選択すると、番号の自動または手動割り当ての際に連続しない番号が割り当てられることを許容します。</span><span class="sxs-lookup"><span data-stu-id="6e6e1-114">On the **No. Series Lines** page for a number series, you can select the **Allow Gaps in Nos.** check box to enable automatic or manual assignment of numbers without requiring sequential numbers.</span></span> <span data-ttu-id="6e6e1-115">これにより、システムが番号シリーズから新しい番号を作成して使用する間、**番号シリーズ明細行**テーブルがロックされているときに発生する、潜在的なパフォーマンスの問題を回避できます。</span><span class="sxs-lookup"><span data-stu-id="6e6e1-115">This avoids potential performance issues that occur when the **No. Series Line** table is locked while the system creates and consumes a new number from a number series.</span></span> <span data-ttu-id="6e6e1-116">さらに、使われなくなった銀行口座のカードなどのレコードをユーザーが柔軟に削除できるようになるため、レコードの番号付きリストにギャップが生じます。</span><span class="sxs-lookup"><span data-stu-id="6e6e1-116">In addition, it gives users flexibility to delete records, such as an obsolete bank account card, and thereby causing gaps in the numbered list of records.</span></span> 

> [!NOTE]
> <span data-ttu-id="6e6e1-117">特定の番号シリーズでギャップを許容する場合は、まず監査人または会計マネージャーに相談して、その国または地域の法的要件を遵守していることを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6e6e1-117">If you want to allow gaps in certain number series, you should first consult with your auditor or accounting manager to ensure that you adhere to the legal requirements in your country or region.</span></span>

<span data-ttu-id="6e6e1-118">連続しない番号の割り当てには、SQL サーバーの優先順位ロジックを活用します。</span><span class="sxs-lookup"><span data-stu-id="6e6e1-118">The non-sequential assignment of numbers leverages the sequencing logic of the SQL server.</span></span> <span data-ttu-id="6e6e1-119">詳細については、「[ロックフリー番号シリーズ](lock-free-number-series.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="6e6e1-119">For more information, see [Lock-free number series](lock-free-number-series.md).</span></span>

<span data-ttu-id="6e6e1-120">![番号付けのギャップを許可する](media/allow_gaps_in_no_series_lines.png "番号付けのギャップを許可する")</span><span class="sxs-lookup"><span data-stu-id="6e6e1-120">![Allow gaps in numbering](media/allow_gaps_in_no_series_lines.png "Allow gaps in numbering")</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="6e6e1-121">関連項目</span><span class="sxs-lookup"><span data-stu-id="6e6e1-121">See also</span></span>

<span data-ttu-id="6e6e1-122">[番号付けのギャップを許可する](https://docs.microsoft.com/dynamics365/business-central/ui-create-number-series#gaps-in-number-series) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="6e6e1-122">[Allow Gaps in Numbers](https://docs.microsoft.com/dynamics365/business-central/ui-create-number-series#gaps-in-number-series) (docs)</span></span>
