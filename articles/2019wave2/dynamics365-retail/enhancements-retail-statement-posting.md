---
title: 小売明細転記の機能強化
description: 小売明細転記の機能強化
author: anpurush
ms.reviewer: josaw
ms.date: 11/15/2019
ms.assetid: 1102a192-f76c-e911-a98c-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: anpurush
dynamics365pdf: true
ms.openlocfilehash: 5c5698e1934dd4d0bcbb26d6b06bf2e8c8f63689
ms.sourcegitcommit: b3c4fcc7b7ea3803a7643417cc415abb10be1182
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/04/2019
ms.locfileid: "2890181"
---
# <a name="enhancements-to-retail-statement-posting"></a><span data-ttu-id="f8a46-103">小売明細転記の機能強化</span><span class="sxs-lookup"><span data-stu-id="f8a46-103">Enhancements to Retail statement posting</span></span>


| <span data-ttu-id="f8a46-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="f8a46-104">Enabled for</span></span>    |  <span data-ttu-id="f8a46-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="f8a46-105">Public preview</span></span> | <span data-ttu-id="f8a46-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="f8a46-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="f8a46-107">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="f8a46-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="f8a46-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="f8a46-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="f8a46-109">2019 年 8 月 2 日</span><span class="sxs-lookup"><span data-stu-id="f8a46-109">Aug 2, 2019</span></span>| <span data-ttu-id="f8a46-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="f8a46-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="f8a46-111">2019 年 10 月 1 日</span><span class="sxs-lookup"><span data-stu-id="f8a46-111">Oct 1, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="f8a46-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="f8a46-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="f8a46-113">Microsoft Dynamics 365 Retail では、クラウド販売時点管理 (POS) または Modern POS (MPOS) で発生するトランザクションの明細を示すために明細書転記プロセスが使用されます。</span><span class="sxs-lookup"><span data-stu-id="f8a46-113">In Microsoft Dynamics 365 Retail, the statement posting process is used to account for the transactions that occur in Cloud point of sale (POS) or Modern POS (MPOS).</span></span> <span data-ttu-id="f8a46-114">店舗での 1 営業日の販売、支払、現金移動などに関するすべてのトランザクションがこのプロセスを通じて本社 (HQ) に反映されるため、このプロセスは実店舗の業務に不可欠な機能です。</span><span class="sxs-lookup"><span data-stu-id="f8a46-114">This process is an integral and vital function of a physical store operation because all the transactions in the store in terms of sales, payments, cash movements, and so on for a business day are reflected back to the headquarters (HQ) through this process.</span></span> <span data-ttu-id="f8a46-115">HQ の担当者が意思決定に使用するすべての重要な日次レポート (1 日の店舗別売上、1 日の店舗別回収、さまざまな商品やカテゴリの在庫移動など) は、明細書転記プロセスを通じて提供されます。</span><span class="sxs-lookup"><span data-stu-id="f8a46-115">All key daily reporting that personnel in the HQ rely on for decision making such as sales by store for a day, collections by store for a day, inventory movements for different products and categories, and so on are made available through the statement posting process.</span></span> 

<span data-ttu-id="f8a46-116">明細書転記プロセスは、小売組織の損失防止機能においても中心的役割を果たします。販売監査担当者が、詐欺と損失の防止に関する問題やパターンを監視および追跡するために明細書転記プロセスからのデータを使用するからです。</span><span class="sxs-lookup"><span data-stu-id="f8a46-116">The statement posting process also plays a pivotal role in the loss prevention function of a retail organization because data from statement posting is used by the sales audit clerks to monitor and track issues and patterns around fraud and loss prevention.</span></span> <span data-ttu-id="f8a46-117">そのため、実店舗を持つすべての小売組織には、信頼性とパフォーマンスの高い明細書転記プロセスが不可欠です。</span><span class="sxs-lookup"><span data-stu-id="f8a46-117">Given that, it is imperative that any retail organization with physical stores has a reliable and performant statement posting process.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="f8a46-118">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="f8a46-118">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="f8a46-119">この機能は、現在の明細書転記プロセスをここで説明する方法で強化します。</span><span class="sxs-lookup"><span data-stu-id="f8a46-119">This feature will enhance the current statement posting process in the ways described here.</span></span>

### <a name="data-fidelity-checker"></a><span data-ttu-id="f8a46-120">データ信頼性チェッカー</span><span class="sxs-lookup"><span data-stu-id="f8a46-120">Data fidelity checker</span></span>

<span data-ttu-id="f8a46-121">明細書転記プロセスの信頼性は、このプロセスに供給されるデータの品質に大きく依存します。</span><span class="sxs-lookup"><span data-stu-id="f8a46-121">The reliability of a statement posting process is highly dependent on the quality of the data that feeds this process.</span></span> <span data-ttu-id="f8a46-122">このデータはファースト パーティまたはサード パーティの POS システムでのトランザクションに基づいて生成され、小売店舗から送信されます。</span><span class="sxs-lookup"><span data-stu-id="f8a46-122">This data is generated and sent over from the retail stores based on transactions in the first-party or third-party POS systems.</span></span> <span data-ttu-id="f8a46-123">整合性のないデータを店舗データベースに書き込む POS クライアントのバグや、統合フレームワークを通じてサード パーティの POS システムから取り込まれたデータなどの要因により、店舗から届くデータの信頼性が疑わしいことはよくあります。</span><span class="sxs-lookup"><span data-stu-id="f8a46-123">It is often seen that the fidelity of the data that comes from the store is questionable due to factors like bugs in the POS client, which writes inconsistent data to the store database or data brought in from a third-party POS system through the integration framework.</span></span> <span data-ttu-id="f8a46-124">これにより、明細書転記の下流プロセスで問題やバグが発生します。</span><span class="sxs-lookup"><span data-stu-id="f8a46-124">This creates issues and bugs in the downstream process of statement postings.</span></span> 

<span data-ttu-id="f8a46-125">これらの課題を克服するため、データ信頼性チェッカーはデータに脱落や異常がないかどうかをチェックし、検証に合格したトランザクションのみが明細書転記プロセスに含まれるようにします。</span><span class="sxs-lookup"><span data-stu-id="f8a46-125">To overcome these challenges, the data fidelity checker will check the data for omissions and anomalies and only those transactions that pass the validation will be included in the statement process.</span></span> <span data-ttu-id="f8a46-126">以下に、データ信頼性チェッカーで実行される検証の種類の一部を示します (これは完全な一覧ではありません)。</span><span class="sxs-lookup"><span data-stu-id="f8a46-126">The following are some of the types of validation that the data fidelity checker will perform (this is not an exhaustive list):</span></span>

- <span data-ttu-id="f8a46-127">ギフト カード品目が返品明細行に関連付けられていないことを検証します。</span><span class="sxs-lookup"><span data-stu-id="f8a46-127">Validate that gift card items are not associated with return lines.</span></span> 

- <span data-ttu-id="f8a46-128">トランザクションごとに、割引テーブルのレコードが小売トランザクション明細行テーブルの割引金額と一致することを検証します。</span><span class="sxs-lookup"><span data-stu-id="f8a46-128">Validate that the records in the discount table match the discount amount in the retail transaction line tables for every transaction.</span></span> 

- <span data-ttu-id="f8a46-129">小売トランザクション支払明細行の金額を合計すると、ヘッダーの小売トランザクション テーブルの支払金額になることを検証します。</span><span class="sxs-lookup"><span data-stu-id="f8a46-129">Validate that the amount on the retail transaction payment lines add up to the payment amount on the header retail transaction table.</span></span>

- <span data-ttu-id="f8a46-130">トランザクションごとに、税テーブルのレコードが小売トランザクション明細行テーブルの税額と一致することを検証します。</span><span class="sxs-lookup"><span data-stu-id="f8a46-130">Validate that the records in the tax table match the tax amount in the retail transaction line tables for every transaction.</span></span>

<span data-ttu-id="f8a46-131">データ信頼性チェッカー機能では、ユーザーがトレーサビリティと調整の目的で監査に設定した期待に反するトランザクションを修正することもできます。</span><span class="sxs-lookup"><span data-stu-id="f8a46-131">The data fidelity checker feature will also allow a user to fix transactions that are not consistent with the expectations set for auditing for traceability and reconciliation purposes.</span></span>

### <a name="trickle-feed-order-creation-public-preview"></a><span data-ttu-id="f8a46-132">トリクル フィード命令の作成 (パブリック プレビュー)</span><span class="sxs-lookup"><span data-stu-id="f8a46-132">Trickle feed order creation (Public Preview)</span></span>

<span data-ttu-id="f8a46-133">現在の明細書転記プロセスは、主に 2 つの部分で管理されます。</span><span class="sxs-lookup"><span data-stu-id="f8a46-133">The current statement posting process is managed in two major parts:</span></span>

- <span data-ttu-id="f8a46-134">HQ に同期されたデータに基づいて、"在庫ジョブ" が、定義された定期的なスケジュールで製品の在庫を引き当てます。</span><span class="sxs-lookup"><span data-stu-id="f8a46-134">Based on the data synchronized to the HQ, an “inventory job” reserves the inventory for products at a defined recurring schedule.</span></span>

- <span data-ttu-id="f8a46-135">1 日の終わりに、閉店して店舗で営業終了操作が実行されると、残りのデータが HQ に同期されます。</span><span class="sxs-lookup"><span data-stu-id="f8a46-135">At the end of the day, when the stores are closed and the end-of-day operations are performed in the store, the remaining data is synchronized to the HQ.</span></span> <span data-ttu-id="f8a46-136">定義されたスケジュールに基づいて、システムは各店舗の明細書ドキュメントを作成します。この明細書ドキュメントが転記されると、システムは作成された在庫の引当を削除し、販売注文、支払仕訳帳、仕訳元帳をシステム内に作成します。</span><span class="sxs-lookup"><span data-stu-id="f8a46-136">Based on a defined schedule, the system creates a statement document for every store and, when this statement document is posted, the system removes the reservation for inventory created and then creates sales orders, payment journals, and ledger journals in the system.</span></span>

<span data-ttu-id="f8a46-137">上記の点から明らかなように、日中は一時的な在庫引当のみが作成されます。</span><span class="sxs-lookup"><span data-stu-id="f8a46-137">As evident from the above points, only temporary inventory reservations are created during the day.</span></span> <span data-ttu-id="f8a46-138">これらの在庫引当は 1 日の終わりに削除され、すべてのトランザクションが販売注文として処理され、新しい在庫トランザクションが 1 日の終わりに他のトランザクションと共に作成されます。</span><span class="sxs-lookup"><span data-stu-id="f8a46-138">These inventory reservations are then removed at the end of the day and all transactions are processed as sales orders; new inventory transactions are created along with other transactions at the end of the day.</span></span> <span data-ttu-id="f8a46-139">日中はこれらのトランザクションの処理は行われず、すべてのトランザクションの処理が 1 日の終わりまで持ち越されます。</span><span class="sxs-lookup"><span data-stu-id="f8a46-139">There is no processing of these transactions happening during the day and all of them are back-loaded to the end of the day.</span></span> <span data-ttu-id="f8a46-140">そのため、大規模なトランザクションを限られた時間枠内で処理しなければならなくなり、大量の負荷とロックが発生して明細書の転記が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="f8a46-140">This creates a situation where large transactions have to be processed in a limited time window and results in phenomenal load and locks, which can result in statement posting failures.</span></span>

<span data-ttu-id="f8a46-141">このような問題に対処するために、明細書転記プロセスが次のように改善されます。</span><span class="sxs-lookup"><span data-stu-id="f8a46-141">To address these issues, the following improvements will be made to the statement posting process:</span></span>

- <span data-ttu-id="f8a46-142">一時的な引当を作成する "在庫ジョブ" を廃止します。</span><span class="sxs-lookup"><span data-stu-id="f8a46-142">Deprecate the “inventory job” that creates temporary reservations.</span></span>

- <span data-ttu-id="f8a46-143">事前に定義されたスケジュールで販売注文を作成し、請求書を発行し、その時点で HQ と同期されるすべてのトランザクションの支払を作成、転記、適用する、新しいジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="f8a46-143">Create a new job that will, at a predefined schedule, create sales orders, invoice them, and create, post, and apply payments for all the transactions that are synchronized to the HQ at that point of time.</span></span> <span data-ttu-id="f8a46-144">さらに、このジョブは割引やギフト カードなどのために作成する必要がある元帳仕訳帳も作成します。</span><span class="sxs-lookup"><span data-stu-id="f8a46-144">In addition, it will also create any ledger journals that need to be created for discounts, gift cards, and so on.</span></span>

- <span data-ttu-id="f8a46-145">1 日の終わりに作成される明細書ドキュメントは、数量の差異を計算および転記する目的でのみ使用されるようになります。</span><span class="sxs-lookup"><span data-stu-id="f8a46-145">The statement document that gets created at the end of the day will only be used to calculate and post any counting variances.</span></span>

### <a name="handling-of-return-lines"></a><span data-ttu-id="f8a46-146">返品明細行の処理</span><span class="sxs-lookup"><span data-stu-id="f8a46-146">Handling of return lines</span></span>

<span data-ttu-id="f8a46-147">返品明細行が正しい返品原価で転記されるようにするために、現在の小売明細書転記プロセスでは、返品を転記する前に元の販売が転記されている必要があります。しかし、元の販売が転記されていないシナリオでは、返品トランザクションに関連する明細書も転記できません。</span><span class="sxs-lookup"><span data-stu-id="f8a46-147">To ensure that the return lines are posted with the correct return cost, the current retail statement posting process requires the original sale to be posted before allowing the return posting; however, in scenarios where a statement for the original sale is not posted, then the statement associated with the return transaction also cannot be posted.</span></span> <span data-ttu-id="f8a46-148">その結果、明細書がバックアップされ、ユーザーは明細書を正しい順序で手動で転記する前に依存関係を見つけなければならなくなります。</span><span class="sxs-lookup"><span data-stu-id="f8a46-148">This results in statements getting backed up and involves users trying to figure out the dependency before posting them manually in the correct sequence.</span></span> <span data-ttu-id="f8a46-149">これを解決し、明細書間に時間的な依存関係が適用されることを避けるために、今後は返品が元の販売の営業日からの在庫原価を利用して転記されるようになります。</span><span class="sxs-lookup"><span data-stu-id="f8a46-149">To resolve this and not enforce chronological dependency between the statements, the returns will be posted leveraging the inventory costs from the business date of the original sale.</span></span>

### <a name="handling-of-batch-controlled-items"></a><span data-ttu-id="f8a46-150">バッチ管理される品目の処理</span><span class="sxs-lookup"><span data-stu-id="f8a46-150">Handling of batch-controlled items</span></span>

<span data-ttu-id="f8a46-151">バッチ管理される品目に対しては、Retail POS で販売時点のバッチ番号の取得がサポートされません。しかし、これらの製品の販売を HQ で転記する際にはバッチ番号が必要です。</span><span class="sxs-lookup"><span data-stu-id="f8a46-151">For batch-tracked items, Retail POS does not support the capture of batch numbers at the time of sale; however, batch numbers are required while posting the sales of these products in the HQ.</span></span> <span data-ttu-id="f8a46-152">現在の明細書転記フレームワークでは、明細の転記時点で既存のバッチ番号を取得します。しかし、これらの製品に対してバッチ番号を持つ数量が存在しないシナリオでは、製品でマイナス在庫が有効になっている場合でも明細書転記プロセスが失敗します。</span><span class="sxs-lookup"><span data-stu-id="f8a46-152">The current statement posting framework picks an already existing batch number at the time of statement posting; however, in scenarios where quantity with batch numbers does not exist for these products, the statement posting process fails even when negative inventory is turned on for these products.</span></span> <span data-ttu-id="f8a46-153">この機能により、バッチ管理される品目でマイナス在庫が有効になっている場合は、品目の在庫がゼロであるかバッチ番号を利用できないときでも明細書の転記がブロックされなくなります。</span><span class="sxs-lookup"><span data-stu-id="f8a46-153">This feature will ensure that statement posting is not blocked for batch-tracked items if the inventory is zero or the batch number is not available if negative inventory is turned on for these items.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="f8a46-154">関連項目</span><span class="sxs-lookup"><span data-stu-id="f8a46-154">See also</span></span>
<span data-ttu-id="f8a46-155">[小売トランザクションの整合性チェック](https://docs.microsoft.com/dynamics365/retail/valid-checker) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="f8a46-155">[Retail transaction consistency checker](https://docs.microsoft.com/dynamics365/retail/valid-checker) (docs)</span></span>
