---
title: 仕入先請求書に配賦されていない費用がある場合は、ワークフローへの送信を禁止する
description: ''
author: relnotes
ms.reviewer: sericks
ms.date: 12/09/2019
ms.assetid: 40f67ec2-cce3-e911-a814-000d3a4f1244
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: 8df0fef6c6ec6eb7ea33c3705600838657fca606
ms.sourcegitcommit: 50510b41ebc81897993a45f689651d9eda6c4247
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/20/2019
ms.locfileid: "2910228"
---
# <a name="prohibit-submission-to-workflow-when-there-are-unallocated-charges-on-a-vendor-invoice"></a><span data-ttu-id="9d3fd-102">仕入先請求書に配賦されていない費用がある場合は、ワークフローへの送信を禁止する</span><span class="sxs-lookup"><span data-stu-id="9d3fd-102">Prohibit submission to workflow when there are unallocated charges on a vendor invoice</span></span>


| <span data-ttu-id="9d3fd-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="9d3fd-103">Enabled for</span></span>    |  <span data-ttu-id="9d3fd-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9d3fd-104">Public preview</span></span> | <span data-ttu-id="9d3fd-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="9d3fd-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="9d3fd-106">エンド ユーザー、管理者/作成者による有効化、またはアナリスト</span><span class="sxs-lookup"><span data-stu-id="9d3fd-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="9d3fd-107">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9d3fd-107">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9d3fd-108">2019 年 10 月 25 日</span><span class="sxs-lookup"><span data-stu-id="9d3fd-108">Oct 25, 2019</span></span>| <span data-ttu-id="9d3fd-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9d3fd-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9d3fd-110">2019 年 11 月 26 日</span><span class="sxs-lookup"><span data-stu-id="9d3fd-110">Nov 26, 2019</span></span>|


## <a name="business-value"></a><span data-ttu-id="9d3fd-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="9d3fd-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="9d3fd-112">請求書がワークフローに送信される前に問題を見つけることは、転記を中止し仕入先請求書をワークフローに再送信する必要が生じるエラーを防ぐのに役立ち、結果的に送信者と承認者の時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="9d3fd-112">Finding issues before invoices are submitted to workflow helps prevent errors that might stop posting and require resubmitting the vendor invoice to workflow, thereby saving submitters and approvers time in the long run.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="9d3fd-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9d3fd-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9d3fd-114">この機能により、配賦されていない費用が仕入先請求書に含まれている場合に、仕入先請求書がワークフロー プロセスに送信されるのを防ぐことができます。</span><span class="sxs-lookup"><span data-stu-id="9d3fd-114">This feature lets you prevent a vendor invoice from being submitted to the workflow process when it contains unallocated charges.</span></span> <span data-ttu-id="9d3fd-115">代わりに、請求書の送信者は、配賦されていない費用が請求書に含まれているという通知を受け取り、ワークフローに送信する前に修正するよう求められます。</span><span class="sxs-lookup"><span data-stu-id="9d3fd-115">Instead, the person who submitted the invoice receives an alert that it has unallocated charges and lets them correct it before submitting it to workflow.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="9d3fd-116">関連項目</span><span class="sxs-lookup"><span data-stu-id="9d3fd-116">See also</span></span>

<span data-ttu-id="9d3fd-117">[10.0.5 での買掛金勘定の変更](https://community.dynamics.com/365/financeandoperations/b/financials/posts/accounts-payable-changes-in-10-0-5) (ブログ)</span><span class="sxs-lookup"><span data-stu-id="9d3fd-117">[Accounts Payable changes in 10.0.5](https://community.dynamics.com/365/financeandoperations/b/financials/posts/accounts-payable-changes-in-10-0-5) (blog)</span></span>


