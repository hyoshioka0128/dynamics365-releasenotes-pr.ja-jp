---
title: POS で部分的に履行された顧客の注文を編集する
description: この機能により、販売時点管理 (POS) ユーザーは、POS または eコマース アプリケーションで作成され、既に部分的に履行または請求されている顧客注文を編集できます。
author: hhainesms
ms.reviewer: josaw
ms.date: 03/24/2020
ms.assetid: 75db56df-c91b-ea11-a811-000d3a8f0752
ms.topic: article
ms.service: business-applications
ms.author: hhaines
dynamics365pdf: true
ms.openlocfilehash: 231bddad45c4e743e262b72d9cde30756a3fdb79
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219504"
---
# <a name="editing-partially-fulfilled-customer-orders-in-pos"></a><span data-ttu-id="3b0db-103">POS で部分的に履行された顧客の注文を編集する</span><span class="sxs-lookup"><span data-stu-id="3b0db-103">Editing partially fulfilled customer orders in POS</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="3b0db-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="3b0db-104">Enabled for</span></span>    |  <span data-ttu-id="3b0db-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="3b0db-105">Public preview</span></span> | <span data-ttu-id="3b0db-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="3b0db-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="3b0db-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="3b0db-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="3b0db-108">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="3b0db-108">May 2020</span></span>| <span data-ttu-id="3b0db-109">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="3b0db-109">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="3b0db-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="3b0db-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="3b0db-111">POS ユーザーは、販売時点管理 (POS) アプリケーションから顧客注文を処理および管理し、未処理の販売明細行を変更および調整できる必要があります。</span><span class="sxs-lookup"><span data-stu-id="3b0db-111">POS users need to be able to work with and manage a customer order from the point of sale (POS) application and make changes and adjustments to unprocessed sales lines.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="3b0db-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="3b0db-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="3b0db-113">現在提供中のアプリケーションでは、POS または eコマースで作成された顧客注文を編集できるのは、注文がまだ未処理の場合、つまり注文の数量が注文の履行または請求プロセスにリリースされていない場合だけです。</span><span class="sxs-lookup"><span data-stu-id="3b0db-113">In the current in-market application, POS or e-commerce-created customer orders can only be edited if the order is still open, meaning no quantities on the order have been released to order fulfillment or invoicing processes.</span></span> <span data-ttu-id="3b0db-114">この機能により、POS のユーザーは、当初 POS または eコマース アプリケーションで作成され、部分的に履行された注文を編集できます。</span><span class="sxs-lookup"><span data-stu-id="3b0db-114">This feature will allow users in POS to edit orders that were originally created in POS or an e-commerce application and are partially fulfilled.</span></span> <span data-ttu-id="3b0db-115">ユーザーは、部分的に履行された顧客注文に明細を追加したり、全量がまだ処理されていない明細を編集または無効化したり、場合によっては明細の数量の一部が既に履行または請求された明細に制限付きで変更を加えることができます。</span><span class="sxs-lookup"><span data-stu-id="3b0db-115">Users will also be able to add additional lines to partially fulfilled customer orders, edit or void lines where the full quantity is still unprocessed, and in some cases make limited changes to lines where some of the quantity on the line has already been fulfilled or invoiced.</span></span>

<span data-ttu-id="3b0db-116">この機能では、POS ユーザーはコール センター チャネルによって作成された注文を編集できません。</span><span class="sxs-lookup"><span data-stu-id="3b0db-116">This feature does not provide POS users the ability to edit orders created by the call center channel.</span></span> <span data-ttu-id="3b0db-117">その機能は 2020 年リリース ウェーブ 2 で計画されています。</span><span class="sxs-lookup"><span data-stu-id="3b0db-117">That capability is planned for 2020 release wave 2.</span></span>
<!--feature detail end -->









