---
title: 在庫バッファーを定義および利用して、eコマースで在庫レベルの表示を促進する
description: この機能は、在庫バッファーと在庫レベルを定義および利用して、eコマースでの在庫利用可能性の表示を促進するのに役立ちます。
author: relnotes
ms.reviewer: josaw
ms.date: 05/21/2020
ms.assetid: 4a2e53c8-a3ca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: boycez
dynamics365pdf: true
ms.openlocfilehash: 527e7b3b4bcc4e4052e6d071ab6cfa36a640fd88
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3415745"
---
# <a name="define-and-utilize-inventory-buffers-to-drive-inventory-level-displays-in-e-commerce"></a><span data-ttu-id="b7c54-103">在庫バッファーを定義および利用して、eコマースで在庫レベルの表示を促進する</span><span class="sxs-lookup"><span data-stu-id="b7c54-103">Define and utilize inventory buffers to drive inventory level displays in e-commerce</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="b7c54-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="b7c54-104">Enabled for</span></span>    |  <span data-ttu-id="b7c54-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="b7c54-105">Public preview</span></span> | <span data-ttu-id="b7c54-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="b7c54-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="b7c54-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="b7c54-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="b7c54-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="b7c54-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="b7c54-109">2020 年 5 月 18 日</span><span class="sxs-lookup"><span data-stu-id="b7c54-109">May 18, 2020</span></span>| <span data-ttu-id="b7c54-110">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="b7c54-110">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="b7c54-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="b7c54-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="b7c54-112">オムニチャネル環境では在庫がすばやく移動するため、正確な手持在庫の評価を取得することが困難な場合があります。</span><span class="sxs-lookup"><span data-stu-id="b7c54-112">Because inventory moves quickly in an omnichannel environment, it can be difficult to get an accurate assessment of stock on hand.</span></span> <span data-ttu-id="b7c54-113">小売業者によっては、実際の手持在庫数量を表示する代わりに、現在の在庫状態を示すだけで問題なく、商品が品薄または在庫切れになる可能性があるという警告を顧客に表示する場合もあります。</span><span class="sxs-lookup"><span data-stu-id="b7c54-113">Instead of viewing actual on-hand quantity, some retailers are fine with being presented with an informational message that explains the current stock status and gives a warning to customers that an item quantity is potentially low or out of stock.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="b7c54-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="b7c54-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="b7c54-115">この機能を使用すると、販売計画時に在庫バッファーおよび在庫レベルのプロファイルを定義しておいて、在庫バッファーから抽出された在庫レベル インジケーターに API でアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="b7c54-115">This feature provides users with the ability to define inventory buffers and inventory level profiles during merchandising, and API access to the inventory level indicators that are derived from the inventory buffers.</span></span>
<!--feature detail end -->









