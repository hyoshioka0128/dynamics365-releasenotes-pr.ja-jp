---
title: POS の荷渡方法の変更操作
description: この機能では、POS トランザクションの 1 つ以上の明細行の荷渡方法をユーザーが更新できる、新しいオプションの販売時点管理 (POS) 操作が提供されます。
author: hhainesms
ms.reviewer: josaw
ms.date: 03/24/2020
ms.assetid: a56ceb94-4711-ea11-a811-000d3a4f1ebb
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: ad0ea827b8c6b3990effcf6455ecffc42084a278
ms.sourcegitcommit: bb7ffd21bd61f24e7174b76465b9a6630c7decb5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/06/2020
ms.locfileid: "3232570"
---
# <a name="change-mode-of-delivery-operation-for-pos"></a><span data-ttu-id="07a41-103">POS の荷渡方法の変更操作</span><span class="sxs-lookup"><span data-stu-id="07a41-103">Change mode of delivery operation for POS</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="07a41-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="07a41-104">Enabled for</span></span>    |  <span data-ttu-id="07a41-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="07a41-105">Public preview</span></span> | <span data-ttu-id="07a41-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="07a41-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="07a41-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="07a41-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="07a41-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="07a41-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="07a41-109">2020 年 2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="07a41-109">Feb 24, 2020</span></span>| <span data-ttu-id="07a41-110">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="07a41-110">May 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="07a41-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="07a41-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="07a41-112">小売業者は、顧客注文明細行の荷渡方法を明細行のフルフィルメントの前にいつでも個別に変更できる柔軟性を求めています。</span><span class="sxs-lookup"><span data-stu-id="07a41-112">Retailers need the flexibility to make changes specifically to the mode of delivery on customer order sales lines at any time prior to the fulfillment of the line.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="07a41-113">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="07a41-113">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="07a41-114">販売時点管理 (POS) 画面レイアウトに**荷渡方法の変更**を追加できます。</span><span class="sxs-lookup"><span data-stu-id="07a41-114">**Change Mode of Delivery** can be added to a point of sale (POS) screen layout.</span></span> <span data-ttu-id="07a41-115">これは、POS での注文作成に "すべて出荷" または "選択された出荷" 方法を使用して以前に構成された明細行に対してのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="07a41-115">It will be applicable only to lines that were previously configured using the "ship all" or "ship selected" methods for creating orders in POS.</span></span> <span data-ttu-id="07a41-116">トランザクション明細行に対して元の荷渡方法が設定された後に、ユーザーが "すべて出荷" または "選択された出荷" フロー全体を経ずに 1 つ以上の対象明細行の荷渡方法を変更したくなる場合があります。</span><span class="sxs-lookup"><span data-stu-id="07a41-116">After the original mode of delivery is set for a transaction line, a user might want to modify the mode of delivery for one or more eligible lines without having to go through the entire "ship all" or "ship selected" flows.</span></span> <span data-ttu-id="07a41-117">この荷渡方法操作は、そのような利便性を提供します。</span><span class="sxs-lookup"><span data-stu-id="07a41-117">The mode of delivery operation will provide this convenience.</span></span> <span data-ttu-id="07a41-118">これは POS 顧客注文の最初の注文作成処理時か、顧客注文の編集時に使用できます。</span><span class="sxs-lookup"><span data-stu-id="07a41-118">It can be used during the initial order creation processing of the POS customer order, or during the editing of a customer order.</span></span> <span data-ttu-id="07a41-119">出荷明細行として構成されていない明細行には適用できず、フルフィルメントに既にリリースされた明細行や請求済みの明細行に対しては機能しません。</span><span class="sxs-lookup"><span data-stu-id="07a41-119">It is not applicable to lines that are not configured as shipping lines, and the operation will not work for lines that are already released to fulfillment or invoiced.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="07a41-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="07a41-120">See also</span></span>


<!--docs start-->
<span data-ttu-id="07a41-121">[POS での荷渡方法の変更](https://docs.microsoft.com/dynamics365/commerce/pos-change-delivery-mode) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="07a41-121">[Change mode of delivery in POS](https://docs.microsoft.com/dynamics365/commerce/pos-change-delivery-mode) (docs)</span></span>
<!--docs end-->

