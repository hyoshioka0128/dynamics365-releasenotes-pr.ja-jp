---
title: 在庫バッファを定義および利用して、eコマースで在庫レベルの表示を促進する
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 03/24/2020
ms.assetid: 4a2e53c8-a3ca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: boycez
dynamics365pdf: true
ms.openlocfilehash: 5187bc2f74b0efc72289bd41167465710c78ae3b
ms.sourcegitcommit: ae0a3b37ccd4a7b687b0b3258fe36d74b149a47c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/03/2020
ms.locfileid: "3219515"
---
# <a name="define-and-utilize-inventory-buffers-to-drive-inventory-level-displays-in-e-commerce"></a><span data-ttu-id="ca0e5-102">在庫バッファを定義および利用して、eコマースで在庫レベルの表示を促進する</span><span class="sxs-lookup"><span data-stu-id="ca0e5-102">Define and utilize inventory buffers to drive inventory level displays in e-commerce</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="ca0e5-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="ca0e5-103">Enabled for</span></span>    |  <span data-ttu-id="ca0e5-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="ca0e5-104">Public preview</span></span> | <span data-ttu-id="ca0e5-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="ca0e5-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="ca0e5-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="ca0e5-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="ca0e5-107">2020 年 5 月</span><span class="sxs-lookup"><span data-stu-id="ca0e5-107">May 2020</span></span>| <span data-ttu-id="ca0e5-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="ca0e5-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="ca0e5-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="ca0e5-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="ca0e5-110">オムニチャネル環境では在庫がすばやく移動するため、正確な手持在庫の評価を取得することが困難な場合があります。</span><span class="sxs-lookup"><span data-stu-id="ca0e5-110">Because inventory moves quickly in an omnichannel environment, it can be difficult to get an accurate assessment of stock on hand.</span></span> <span data-ttu-id="ca0e5-111">小売業者によっては、実際の手持在庫数量を表示する代わりに、現在の在庫状態を示すだけで問題なく、商品が品薄または在庫切れになる可能性があるという警告を顧客に表示する場合もあります。</span><span class="sxs-lookup"><span data-stu-id="ca0e5-111">Instead of viewing actual on-hand quantity, some retailers are fine with being presented with an informational message that explains the current stock status and gives a warning to customers that an item quantity is potentially low or out of stock.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="ca0e5-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="ca0e5-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="ca0e5-113">この機能を使用すると、販売計画時に在庫バッファーを定義しておいて、在庫バッファーから抽出された在庫レベル インジケーターに API でアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="ca0e5-113">This feature provides users with the ability to define inventory buffers during merchandising, and API access to the inventory level indicators that are derived from the inventory buffers.</span></span>
<!--feature detail end -->









