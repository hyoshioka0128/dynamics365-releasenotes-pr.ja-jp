---
title: 口座調整の改善
description: 口座調整と支払い処理の機能強化
author: relnotes
ms.reviewer: sgroespe
ms.date: 12/12/2019
ms.assetid: 685f0acb-13cb-e911-a996-000d3a4f3343
ms.topic: article
ms.service: business-applications
ms.author: jobulsin
dynamics365pdf: true
ms.openlocfilehash: 3d3e4b7dcfc0eb93242689142a68602b2b0dd5af
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986831"
---
# <a name="bank-reconciliation-improvements"></a><span data-ttu-id="3b60e-103">口座調整の改善</span><span class="sxs-lookup"><span data-stu-id="3b60e-103">Bank reconciliation improvements</span></span>
[!include[dynamics365-business-central banner](../includes/dynamics365-business-central.md)]

| <span data-ttu-id="3b60e-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3b60e-104">Enabled for</span></span>    |  <span data-ttu-id="3b60e-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3b60e-105">Public preview</span></span> | <span data-ttu-id="3b60e-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="3b60e-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3b60e-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="3b60e-107">End users, automatically</span></span>|<span data-ttu-id="3b60e-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="3b60e-108">Feb 2020</span></span>| <span data-ttu-id="3b60e-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="3b60e-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3b60e-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3b60e-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3b60e-111">銀行口座明細書を内部銀行口座および顧客または支払元帳と調整することにより、エラーが原因となっている可能性がある支払いの欠落や異常な取引を識別し、財務管理を向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="3b60e-111">By reconciling your bank account statements with your internal bank accounts and customer or payment ledgers, you can identify missing payments or unusual transactions that might be caused by errors and thereby improve your financial management.</span></span> <span data-ttu-id="3b60e-112">これらのプロセスの強化により、調整タスクを効率的かつ迅速に実行できるようになります。</span><span class="sxs-lookup"><span data-stu-id="3b60e-112">Enhancements of these processes will ensure that reconciliation tasks can be done efficiently and quickly.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3b60e-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3b60e-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3b60e-114">**銀行口座調整**ページのデータ用のスペースが増え、口座取引明細書行および関連する銀行口座元帳エントリの概要と理解が向上します。</span><span class="sxs-lookup"><span data-stu-id="3b60e-114">The **Bank Acc. Reconciliation** page will have more space for data and allow better overview and understanding of the bank statement lines and the related bank account ledger entries.</span></span> <span data-ttu-id="3b60e-115">進行中と転記済み両方の調整と明細書で、レポートに使用できる口座調整レポートが提供されます。</span><span class="sxs-lookup"><span data-stu-id="3b60e-115">A Bank Reconciliation report that can be used to report on both ongoing and posted bank reconciliations and statements is provided.</span></span> 

<span data-ttu-id="3b60e-116">**銀行口座調整**ページと**支払調整仕訳**ページの両方が、関連する照合およびアプリケーション ルールの説明にリンクし、ユーザーがルールを有効または無効にすることができます。</span><span class="sxs-lookup"><span data-stu-id="3b60e-116">Both the **Bank Acc. Reconciliation** and the **Payment Reconciliation Journal** pages will link to explanations of the involved matching and application rules, and rules can be enabled or disabled by the user.</span></span> <span data-ttu-id="3b60e-117">転記のプレビューは両方のページでサポートされます。</span><span class="sxs-lookup"><span data-stu-id="3b60e-117">Posting preview will be supported on both pages.</span></span> <span data-ttu-id="3b60e-118">差異の振替機能が改善され、差異のある複数のレコードを一般仕訳帳に振り替えられるようになります。</span><span class="sxs-lookup"><span data-stu-id="3b60e-118">The Transfer Difference function will be improved to allow transferring multiple records with differences to the general journal.</span></span> <span data-ttu-id="3b60e-119">従業員元帳のエントリは、口座調整でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="3b60e-119">Employee ledger entries will be supported in bank reconciliation.</span></span> <span data-ttu-id="3b60e-120">**支払調整仕訳**ページに表示される番号シリーズとドキュメント番号の管理が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="3b60e-120">It will be easier to control number series and document numbers that appear on the **Payment Reconciliation Journal** page.</span></span>
<!--feature detail end -->






## <a name="tell-us-what-you-think"></a><span data-ttu-id="3b60e-121">フィードバック</span><span class="sxs-lookup"><span data-stu-id="3b60e-121">Tell us what you think</span></span>
<span data-ttu-id="3b60e-122">Dynamics 365 Business Central の機能向上のためのアイデア、提案、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="3b60e-122">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="3b60e-123">フォーラム (https://aka.ms/bcideas) をご利用ください。</span><span class="sxs-lookup"><span data-stu-id="3b60e-123">Use the forum at https://aka.ms/bcideas.</span></span>



