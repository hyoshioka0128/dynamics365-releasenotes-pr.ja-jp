---
title: バッチ番号引当フォームの行の引当の機能強化
description: バッチ番号引当プロセスを強化します。
author: relnotes
ms.reviewer: kamaybac
ms.date: 06/02/2020
ms.assetid: 10a89655-8772-ea11-a811-000d3a579c38
ms.topic: article
ms.service: business-applications
ms.author: perlynne
dynamics365pdf: true
ms.openlocfilehash: cbcdba9b48acaedf8f76eb38d6bd26923ba1669e
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3441647"
---
# <a name="line-reservation-enhancements-for-the-batch-number-reservation-form"></a><span data-ttu-id="9c185-103">バッチ番号引当フォームの行の引当の機能強化</span><span class="sxs-lookup"><span data-stu-id="9c185-103">Line reservation enhancements for the batch number reservation form</span></span>


| <span data-ttu-id="9c185-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="9c185-104">Enabled for</span></span>    |  <span data-ttu-id="9c185-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="9c185-105">Public preview</span></span> | <span data-ttu-id="9c185-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="9c185-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="9c185-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="9c185-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="9c185-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9c185-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9c185-109">2020 年 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="9c185-109">Apr 17, 2020</span></span>| <span data-ttu-id="9c185-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="9c185-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="9c185-111">2020 年 5 月 26 日</span><span class="sxs-lookup"><span data-stu-id="9c185-111">May 26, 2020</span></span>|






## <a name="feature-details"></a><span data-ttu-id="9c185-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="9c185-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="9c185-113">この機能では、**バッチ引当**ページに新しい**行の引当**ボタンが追加されます。</span><span class="sxs-lookup"><span data-stu-id="9c185-113">This feature adds a new **Reserve lines** button to the **Batch reservation** page.</span></span> <span data-ttu-id="9c185-114">これにより、ユーザーは選択した任意の数の行すべてに特定のバッチ番号を一度に引き当てることができます。</span><span class="sxs-lookup"><span data-stu-id="9c185-114">It lets users reserve specific batch numbers for any number of selected lines all at once.</span></span> <span data-ttu-id="9c185-115">この新しいボタンは、倉庫管理プロセスに対して有効になっている品目を操作する際の**行の引当**ボタンに代わるものです。</span><span class="sxs-lookup"><span data-stu-id="9c185-115">This new button replaces the **Reserve line** button when you are working with items that are enabled for the warehouse management process.</span></span>

<span data-ttu-id="9c185-116">**倉庫管理プロセスの使用**が有効になっている保管分析コード グループに関連付けられた品目に対してバッチ番号を引き当てるには、**バッチ引当**ページを使用します。</span><span class="sxs-lookup"><span data-stu-id="9c185-116">Use the **Batch reservation** page to reserve batch numbers for items associated with a storage dimension group that has **Use warehouse management processes** enabled.</span></span> <span data-ttu-id="9c185-117">これにより、場所分析コードの上にバッチ番号在庫分析コードが定義されている引当階層を使用して、特定のバッチ番号を引き当てることができます。</span><span class="sxs-lookup"><span data-stu-id="9c185-117">It lets you reserve specific batch numbers by using a reservation hierarchy with the batch number inventory dimension defined above the location dimension.</span></span> <span data-ttu-id="9c185-118">また、場所分析コードの下にバッチ番号分析コードが定義されているときに特定のバッチ番号を引き当てる必要がある場合は、*柔軟な倉庫レベルの分析コード引当*機能を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="9c185-118">If you also need to reserve specific batch numbers when having the batch number dimension defined as below the location dimension, you must also enable the *Flexible warehouse-level dimension reservation* feature.</span></span>

<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="9c185-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="9c185-119">See also</span></span>

<!--docs start-->
<span data-ttu-id="9c185-120">[販売注文に対する同一バッチの引当](https://docs.microsoft.com/dynamics365/supply-chain/sales-marketing/reserve-same-batch-sales-order) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="9c185-120">[Reserve the same batch for a sales order](https://docs.microsoft.com/dynamics365/supply-chain/sales-marketing/reserve-same-batch-sales-order) (docs)</span></span>
<!--docs end-->
