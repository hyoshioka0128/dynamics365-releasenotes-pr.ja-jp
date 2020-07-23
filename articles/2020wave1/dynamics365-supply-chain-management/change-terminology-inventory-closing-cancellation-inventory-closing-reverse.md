---
title: 在庫決算キャンセルの用語を在庫決算破棄に変更
description: 在庫決算キャンセルの用語を在庫決算破棄に変更します。
author: RichardLuan
ms.reviewer: kamaybac
ms.date: 06/24/2020
ms.assetid: 3a55c727-02a7-ea11-a812-000d3a563be2
ms.topic: article
ms.service: business-applications
ms.author: riluan
dynamics365pdf: true
ms.openlocfilehash: 739b450b0b15e9a4d5eb062d9e19a2c7d5d8b95b
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3524113"
---
# <a name="change-the-terminology-of-inventory-closing-cancellation-to-inventory-closing-reverse"></a><span data-ttu-id="cf020-103">"在庫決算キャンセル" の用語を "在庫決算破棄" に変更</span><span class="sxs-lookup"><span data-stu-id="cf020-103">Change the terminology of "inventory closing cancellation" to "inventory closing reverse"</span></span>
[!include[dynamics365-supply-chain-management banner](../includes/dynamics365-supply-chain-management.md)]

| <span data-ttu-id="cf020-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="cf020-104">Enabled for</span></span>    |  <span data-ttu-id="cf020-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cf020-105">Public preview</span></span> | <span data-ttu-id="cf020-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="cf020-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="cf020-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="cf020-107">End users, automatically</span></span>|<span data-ttu-id="cf020-108">2020 年 8 月</span><span class="sxs-lookup"><span data-stu-id="cf020-108">Aug 2020</span></span>| <span data-ttu-id="cf020-109">2020 年 9 月</span><span class="sxs-lookup"><span data-stu-id="cf020-109">Sep 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="cf020-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="cf020-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="cf020-111">ラベルを変更して、在庫決算操作を元に戻すコマンドをユーザーが理解しやすくします。</span><span class="sxs-lookup"><span data-stu-id="cf020-111">Changes a label to make the command for reversing an inventory close operation easier for users to understand.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="cf020-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cf020-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cf020-113">**決算と調整**ページには、ユーザーが選択した在庫決算操作を "キャンセル" できるボタンがあります。ただし、まだ実行中の在庫決算操作をユーザーがキャンセルしようとすると、データの破損を防ぐために要求がブロックされます。</span><span class="sxs-lookup"><span data-stu-id="cf020-113">The **Closing and adjustment** page includes a button that enables users to "cancel" a selected inventory close operation; however, if a user tries to cancel an inventory close operation while it is still running, the request is blocked to prevent potential data corruption.</span></span> <span data-ttu-id="cf020-114">代わりに、システムは選択された決算操作を完了後に*元に戻し*ます。</span><span class="sxs-lookup"><span data-stu-id="cf020-114">Instead, the system will *reverse* the selected close operation after it has finished.</span></span> <span data-ttu-id="cf020-115">混乱を避けるため、この機能に関連するボタンのラベルとその他のラベルを**キャンセル**から**破棄**に変更しました。</span><span class="sxs-lookup"><span data-stu-id="cf020-115">To avoid confusion, we have relabeled of the button and other labels related to this functionality from **Cancellation** to **Reverse**.</span></span> 

<span data-ttu-id="cf020-116">この変更はリリース 10.0.13 以降は既定で適用されますが、機能が "[決算と調整] のキャンセルのラベルを取消に変更" という名前になっている Supply Chain Management の**機能管理**ページにも表示されます。</span><span class="sxs-lookup"><span data-stu-id="cf020-116">This change is applied by default starting with release 10.0.13, but it is also visible on the **Feature management** page in Supply Chain Management where the feature is named  "Change the label of Cancellation in Closing and adjustment to Reverse."</span></span> <span data-ttu-id="cf020-117">以前のラベルの方が好ましい場合は、機能管理を使用してこの機能をオフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="cf020-117">You can use feature management to turn the feature off if you prefer the previous labeling.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="cf020-118">関連項目</span><span class="sxs-lookup"><span data-stu-id="cf020-118">See also</span></span>

<!--docs start-->
<span data-ttu-id="cf020-119">[在庫決算](https://docs.microsoft.com/dynamics365/supply-chain/cost-management/inventory-close) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="cf020-119">[Inventory close](https://docs.microsoft.com/dynamics365/supply-chain/cost-management/inventory-close) (docs)</span></span>
<!--docs end-->
