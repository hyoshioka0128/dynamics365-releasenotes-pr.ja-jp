---
title: 在庫バッファを定義および利用して、eコマースで在庫レベルの表示を促進する
description: ''
author: relnotes
ms.reviewer: josaw
ms.date: 01/10/2020
ms.assetid: 4a2e53c8-a3ca-e911-a968-000d3a4f3883
ms.topic: article
ms.service: business-applications
ms.author: boycez
dynamics365pdf: true
ms.openlocfilehash: fbd00330289117f918d20447b9aa93aad6c9e966
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986811"
---
# <a name="define-and-utilize-inventory-buffers-to-drive-inventory-level-displays-in-e-commerce"></a><span data-ttu-id="a7788-102">在庫バッファを定義および利用して、eコマースで在庫レベルの表示を促進する</span><span class="sxs-lookup"><span data-stu-id="a7788-102">Define and utilize inventory buffers to drive inventory level displays in e-commerce</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="a7788-103">有効対象</span><span class="sxs-lookup"><span data-stu-id="a7788-103">Enabled for</span></span>    |  <span data-ttu-id="a7788-104">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="a7788-104">Public preview</span></span> | <span data-ttu-id="a7788-105">一般提供</span><span class="sxs-lookup"><span data-stu-id="a7788-105">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="a7788-106">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="a7788-106">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="a7788-107">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="a7788-107">Apr 2020</span></span>| <span data-ttu-id="a7788-108">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="a7788-108">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="a7788-109">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="a7788-109">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="a7788-110">オムニチャネル環境では在庫がすばやく移動するため、正確な手持在庫の評価を取得することが困難な場合があります。</span><span class="sxs-lookup"><span data-stu-id="a7788-110">Because inventory moves quickly in an omnichannel environment, it can be difficult to get an accurate on-hand assessment of stock on hand.</span></span> <span data-ttu-id="a7788-111">小売業者によっては、実際の推定手持在庫数量を表示する代わりに、現在の在庫ステータスを示すだけで問題ない場合もあります。つまり、Commerce Headquarters (HQ) によって示された利用可能手持在庫値が、指定されたバッファ値よりも低い場合に、商品が品薄または在庫切れになる可能性があるという警告メッセージを顧客に表示するという方法もあります。</span><span class="sxs-lookup"><span data-stu-id="a7788-111">Instead of viewing actual estimated on-hand quantity, some retailers are fine with being presented with an informational message that explains the current stock status and gives a warning to customers that an item quantity is potentially low or out of stock if the available on-hand value provided by Commerce headquarters (HQ) is lower than a designated buffer value.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="a7788-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="a7788-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="a7788-113">この機能を使用すると、販売計画時に在庫バッファを定義しておいて、在庫バッファから抽出された在庫レベル インジケーターに API でアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="a7788-113">This feature provides users with the ability to define inventory buffers during merchandising, and API access to the inventory level indicators that are derived from the inventory buffers.</span></span>
<!--feature detail end -->









