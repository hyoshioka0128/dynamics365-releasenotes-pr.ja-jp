---
title: 請求書の合計と登録済みの請求書の合計が等しくない場合、ワークフローへの送信を禁止します
description: この機能は、仕入先請求書をワークフロー プロセスに送信する前にエラーを特定して修正するのに役立ちます。
author: relnotes
ms.reviewer: roschlom
ms.date: 01/08/2020
ms.assetid: c2003594-f11e-ea11-a810-000d3a8f0f1e
ms.topic: article
ms.service: business-applications
ms.author: aolson
dynamics365pdf: true
ms.openlocfilehash: f4361ea545f1ef7b828b4352bbe9897053112d7e
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986601"
---
# <a name="prohibit-submission-to-workflow-when-the-invoice-total-and-registered-invoice-total-are-not-equal"></a><span data-ttu-id="7bc7c-103">請求書の合計と登録済みの請求書の合計が等しくない場合、ワークフローへの送信を禁止します</span><span class="sxs-lookup"><span data-stu-id="7bc7c-103">Prohibit submission to workflow when the invoice total and registered invoice total are not equal</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="7bc7c-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7bc7c-104">Enabled for</span></span>    |  <span data-ttu-id="7bc7c-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7bc7c-105">Public preview</span></span> | <span data-ttu-id="7bc7c-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7bc7c-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7bc7c-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="7bc7c-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="7bc7c-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="7bc7c-108">Feb 2020</span></span>| <span data-ttu-id="7bc7c-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="7bc7c-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="7bc7c-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7bc7c-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7bc7c-111">請求書がワークフローに送信される前に問題を見つけることは、転記が中止されたり、仕入先請求書をワークフローに再送信する必要が生じたりするエラーを防ぐのに役立ち、結果的に送信者と承認者の時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="7bc7c-111">Finding an issue before an invoice is submitted to workflow helps prevent errors that might stop posting and require resubmitting the vendor invoice to workflow later, saving submitters and approvers time in the long run.</span></span> 
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7bc7c-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7bc7c-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7bc7c-113">この機能を使用すると、請求書の合計と登録済みの請求書の合計が等しくない場合に、仕入先請求書がワークフロー プロセスに送信されないようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="7bc7c-113">This feature lets you prevent a vendor invoice from being submitted to the workflow process when the invoice total and registered invoice total are not equal.</span></span> <span data-ttu-id="7bc7c-114">代わりに、請求書の送信者は、合計が一致しないという通知を受け取り、ワークフローに送信する前に修正するよう求められます。</span><span class="sxs-lookup"><span data-stu-id="7bc7c-114">Instead, the person who submitted the invoice receives an alert that the totals aren’t equal, letting them correct it before submitting it to workflow.</span></span>  
<!--feature detail end -->









