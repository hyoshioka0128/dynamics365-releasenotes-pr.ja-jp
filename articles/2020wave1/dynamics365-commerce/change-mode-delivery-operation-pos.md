---
title: POS の荷渡方法の変更操作
description: この機能では、POS トランザクションの 1 つ以上の明細行の荷渡方法をユーザーが更新できる、新しいオプションの販売時点管理 (POS) 操作が提供されます。
author: hhainesms
ms.reviewer: josaw
ms.date: 02/18/2020
ms.assetid: a56ceb94-4711-ea11-a811-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 5ceadc7fc94165033610e441cdecde96c0b9cdf4
ms.sourcegitcommit: e29512e521c19d5542b7c0425a5b3aa83d4bbfdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/21/2020
ms.locfileid: "3080685"
---
# <a name="change-mode-of-delivery-operation-for-pos"></a><span data-ttu-id="91605-103">POS の荷渡方法の変更操作</span><span class="sxs-lookup"><span data-stu-id="91605-103">Change mode of delivery operation for POS</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="91605-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="91605-104">Enabled for</span></span>    |  <span data-ttu-id="91605-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="91605-105">Public preview</span></span> | <span data-ttu-id="91605-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="91605-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="91605-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="91605-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="91605-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="91605-108">Feb 2020</span></span>| <span data-ttu-id="91605-109">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="91605-109">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="91605-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="91605-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="91605-111">小売業者は、顧客注文明細行の荷渡方法を明細行のフルフィルメントの前にいつでも個別に変更できる柔軟性を求めています。</span><span class="sxs-lookup"><span data-stu-id="91605-111">Retailers need the flexibility to make changes specifically to the mode of delivery on customer order sales lines at any time prior to the fulfillment of the line.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="91605-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="91605-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="91605-113">POS 画面レイアウトに**荷渡方法の変更**を追加できます。</span><span class="sxs-lookup"><span data-stu-id="91605-113">**Change Mode of Delivery** can be added to a POS screen layout.</span></span> <span data-ttu-id="91605-114">これは、POS で以前に "すべて出荷" または "選択された出荷" 注文作成方法を使用して構成された明細行に対してのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="91605-114">It will only be applicable to lines that were previously configured using the "ship all" or "ship selected" order-creation methods in POS.</span></span> <span data-ttu-id="91605-115">トランザクション明細行に対して元の荷渡方法が設定された後に、ユーザーが "すべて出荷" または "選択された出荷" フロー全体を経ずに 1 つ以上の対象明細行の荷渡方法を変更したくなる場合があります。</span><span class="sxs-lookup"><span data-stu-id="91605-115">After the original mode of delivery is set for a transaction line, a user might want to modify the mode of delivery for one or more eligible lines without having to go through the entire "ship all" or "ship selected" flows.</span></span> <span data-ttu-id="91605-116">この荷渡方法操作は、そのような利便性を提供します。</span><span class="sxs-lookup"><span data-stu-id="91605-116">The mode of delivery operation will provide this convenience.</span></span> <span data-ttu-id="91605-117">これは POS 顧客注文の最初の注文作成処理時か、顧客注文の編集時に使用できます。</span><span class="sxs-lookup"><span data-stu-id="91605-117">It can be used during the initial order creation processing of the POS customer order, or during the editing of a customer order.</span></span> <span data-ttu-id="91605-118">出荷明細行として構成されていない明細行には適用できず、フルフィルメントにリリース済みの明細行や請求済みの明細行に対しては機能しません。</span><span class="sxs-lookup"><span data-stu-id="91605-118">It is not applicable to lines that are not configured as shipping lines, and the operation will not work for lines that are released to fulfillment or invoiced.</span></span>  
<!--feature detail end -->









