---
title: '拡張されたローカライズ (イタリア): 無料で配送される商品の税金請求書'
description: Dynamics 365 Finance が、以前はイタリアのパートナー Cluster Reply によって提供された、拡張されたローカライズ (イタリア) (EXIL) アドインでのみ利用可能であった、イタリア語固有の機能セットが利用できるように拡張されました。
author: relnotes
ms.reviewer: kfend
ms.date: 12/17/2019
ms.assetid: 4237fdd6-efdb-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
dynamics365pdf: true
ms.openlocfilehash: ebd92fda06cfd5e455f27609542c59fb7eb3b616
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986755"
---
# <a name="extended-italian-localization-tax-invoice-for-goods-delivered-for-free"></a><span data-ttu-id="94209-103">拡張されたローカライズ (イタリア): 無料で配送される商品の税金請求書</span><span class="sxs-lookup"><span data-stu-id="94209-103">Extended Italian localization: tax invoice for goods delivered for free</span></span>
[!include[dynamics365-finance banner](../includes/dynamics365-finance.md)]

| <span data-ttu-id="94209-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="94209-104">Enabled for</span></span>    |  <span data-ttu-id="94209-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="94209-105">Public preview</span></span> | <span data-ttu-id="94209-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="94209-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="94209-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="94209-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="94209-108">2020 年 2 月</span><span class="sxs-lookup"><span data-stu-id="94209-108">Feb 2020</span></span>| <span data-ttu-id="94209-109">2020 年 4 月</span><span class="sxs-lookup"><span data-stu-id="94209-109">Apr 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="94209-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="94209-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="94209-111">イタリアに Dynamics 365 Finance を展開するグローバルおよびローカルの顧客は、拡張されたローカライズ (イタリア) (EXIL) アドインやその他イタリアの市場で利用できる類似の機能のアドインを適用することなく、厳選された競争力のあるイタリア語の規制機能をそのまま利用できます。</span><span class="sxs-lookup"><span data-stu-id="94209-111">Global and local customers who deploy Dynamics 365 Finance in Italy receive selected regulatory and competitive Italian features out of the box without the need to apply the Extended Italian Localization (EXIL) add-in or any other add-in with similar features available in the Italian market.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="94209-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="94209-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="94209-113">商品が無料で顧客に届けられるときでも、税金を支払う義務が発生します。</span><span class="sxs-lookup"><span data-stu-id="94209-113">When goods are delivered for free to a customer, there is still an obligation to pay taxes.</span></span> <span data-ttu-id="94209-114">これは、次の 2 つの場合に発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="94209-114">There are two cases where this can occur:</span></span>

- <span data-ttu-id="94209-115">会社が消費税を支払う。</span><span class="sxs-lookup"><span data-stu-id="94209-115">The company pays the sales tax.</span></span> <span data-ttu-id="94209-116">商品は理由コードが**無料**の納品書と共に顧客に発送されます。</span><span class="sxs-lookup"><span data-stu-id="94209-116">The goods are shipped to the customer with a delivery note that includes the reason code **Free**.</span></span> <span data-ttu-id="94209-117">会社は、ヘッダーに**無料の請求書**と明記されている、商品の価格が印刷されている、消費税が計算されている、かつ請求書の合計が税額に等しい、自己請求書を発行します。</span><span class="sxs-lookup"><span data-stu-id="94209-117">The company issues a self-invoice where the text **Free invoice** is clearly printed on the header, the value of goods is printed, the sales tax is calculated, and the total of the invoice is equal to the tax amount.</span></span>
- <span data-ttu-id="94209-118">顧客が消費税を支払う。</span><span class="sxs-lookup"><span data-stu-id="94209-118">The customer pays the sales tax.</span></span> <span data-ttu-id="94209-119">商品は理由コードが**無料**の納品書と共に顧客に発送されます。</span><span class="sxs-lookup"><span data-stu-id="94209-119">The goods are shipped to the customer with a delivery note with the reason code **Free**.</span></span> <span data-ttu-id="94209-120">その後、納品書が顧客に請求されます。</span><span class="sxs-lookup"><span data-stu-id="94209-120">The delivery note is then invoiced to the customer.</span></span> <span data-ttu-id="94209-121">請求書は、ヘッダーに**無料の請求書**と明記されている、商品の価格が印刷されている、消費税が計算されている、かつ請求書の合計が税額に等しくなっています。</span><span class="sxs-lookup"><span data-stu-id="94209-121">On the invoice, the text **Free invoice** is clearly printed on the header, the value of goods is printed, the sales tax is calculated, and the total of the invoice is equal to the tax amount.</span></span>

<!--feature detail end -->









