---
title: 請求書の合計と登録済みの請求書の合計が等しくない場合、ワークフローへの送信を禁止します
description: この機能は、仕入先請求書をワークフロー プロセスに送信する前にエラーを特定して修正するのに役立ちます。
author: relnotes
ms.reviewer: roschlom
ms.date: 04/06/2020
ms.assetid: c2003594-f11e-ea11-a810-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: f4d92c36a44ef72d21ab41ab5a9208462bb0c3ec
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255411"
---
# <a name="prohibit-submission-to-workflow-when-the-invoice-total-and-registered-invoice-total-are-not-equal"></a><span data-ttu-id="bb05f-103">請求書の合計と登録済みの請求書の合計が等しくない場合、ワークフローへの送信を禁止します</span><span class="sxs-lookup"><span data-stu-id="bb05f-103">Prohibit submission to workflow when the invoice total and registered invoice total are not equal</span></span>


| <span data-ttu-id="bb05f-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="bb05f-104">Enabled for</span></span>    |  <span data-ttu-id="bb05f-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="bb05f-105">Public preview</span></span> | <span data-ttu-id="bb05f-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="bb05f-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="bb05f-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="bb05f-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="bb05f-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="bb05f-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="bb05f-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="bb05f-109">Feb 3, 2020</span></span>| <span data-ttu-id="bb05f-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="bb05f-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="bb05f-111">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="bb05f-111">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="bb05f-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="bb05f-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="bb05f-113">請求書がワークフローに送信される前に問題を見つけることは、転記が中止されたり、仕入先請求書をワークフローに再送信する必要が生じたりするエラーを防ぐのに役立ち、結果的に送信者と承認者の時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="bb05f-113">Finding an issue before an invoice is submitted to workflow helps prevent errors that might stop posting and require resubmitting the vendor invoice to workflow later, saving submitters and approvers time in the long run.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="bb05f-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="bb05f-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="bb05f-115">この機能を使用すると、請求書の合計と登録済みの請求書の合計が等しくない場合に、仕入先請求書がワークフロー プロセスに送信されないようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="bb05f-115">This feature lets you prevent a vendor invoice from being submitted to the workflow process when the invoice total and registered invoice total are not equal.</span></span> <span data-ttu-id="bb05f-116">代わりに、請求書の送信者は、合計が一致しないという通知を受け取り、ワークフローに送信する前に修正するよう求められます。</span><span class="sxs-lookup"><span data-stu-id="bb05f-116">Instead, the person who submitted the invoice receives an alert that the totals aren’t equal, letting them correct it before submitting it to workflow.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="bb05f-117">関連項目</span><span class="sxs-lookup"><span data-stu-id="bb05f-117">See also</span></span>

<!--docs start-->
<span data-ttu-id="bb05f-118">[確認用の仕入先請求書の送信](https://docs.microsoft.com/dynamics365/finance/accounts-payable/vendor-invoices-overview#submitting-a-vendor-invoice-for-review) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="bb05f-118">[Submitting a vendor invoice for review](https://docs.microsoft.com/dynamics365/finance/accounts-payable/vendor-invoices-overview#submitting-a-vendor-invoice-for-review) (docs)</span></span>
<!--docs end-->
