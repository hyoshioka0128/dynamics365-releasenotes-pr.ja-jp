---
title: '拡張されたローカライズ (イタリア): 無料で配送される商品の税金請求書'
description: Dynamics 365 Finance が、以前はイタリアのパートナー Cluster Reply によって提供された、拡張されたローカライズ (イタリア) (EXIL) アドインでのみ利用可能であった、イタリア語固有の機能セットが利用できるように拡張されました。
author: relnotes
ms.reviewer: kfend
ms.date: 04/07/2020
ms.assetid: 4237fdd6-efdb-e911-a812-000d3a4f1168
ms.topic: article
ms.service: business-applications
ms.author: mrolecki
dynamics365pdf: true
ms.openlocfilehash: e5aba90c34586946d6bd71f2fadf4064b4cff3a6
ms.sourcegitcommit: 63b2eea9aebeb28f4541e14b396a3be552aca0f5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/10/2020
ms.locfileid: "3255455"
---
# <a name="extended-italian-localization-tax-invoice-for-goods-delivered-for-free"></a><span data-ttu-id="83571-103">拡張されたローカライズ (イタリア): 無料で配送される商品の税金請求書</span><span class="sxs-lookup"><span data-stu-id="83571-103">Extended Italian localization: Tax invoice for goods delivered for free</span></span>


| <span data-ttu-id="83571-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="83571-104">Enabled for</span></span>    |  <span data-ttu-id="83571-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="83571-105">Public preview</span></span> | <span data-ttu-id="83571-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="83571-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="83571-107">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="83571-107">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="83571-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="83571-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="83571-109">2020 年 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="83571-109">Feb 3, 2020</span></span>| <span data-ttu-id="83571-110">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="83571-110">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="83571-111">2020 年 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="83571-111">Apr 3, 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="83571-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="83571-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="83571-113">イタリアに Dynamics 365 Finance を展開するグローバルおよびローカルの顧客は、拡張されたローカライズ (イタリア) (EXIL) アドインやその他イタリアの市場で利用できる類似の機能のアドインを適用することなく、厳選された競争力のあるイタリア語の規制機能をそのまま利用できます。</span><span class="sxs-lookup"><span data-stu-id="83571-113">Global and local customers who deploy Dynamics 365 Finance in Italy receive selected regulatory and competitive Italian features out of the box without the need to apply the Extended Italian Localization (EXIL) add-in or any other add-in with similar features available in the Italian market.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="83571-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="83571-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="83571-115">商品が無料で顧客に届けられるときでも、税金を支払う義務が発生します。</span><span class="sxs-lookup"><span data-stu-id="83571-115">When goods are delivered for free to a customer, there is still an obligation to pay taxes.</span></span> <span data-ttu-id="83571-116">これは、次の 2 つの場合に発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="83571-116">There are two cases where this can occur:</span></span>

- <span data-ttu-id="83571-117">会社が消費税を支払う。</span><span class="sxs-lookup"><span data-stu-id="83571-117">The company pays the sales tax.</span></span> <span data-ttu-id="83571-118">商品は理由コードが**無料**の納品書と共に顧客に発送されます。</span><span class="sxs-lookup"><span data-stu-id="83571-118">The goods are shipped to the customer with a delivery note that includes the reason code **Free**.</span></span> <span data-ttu-id="83571-119">会社は、ヘッダーに**無料の請求書**と明記されている、商品の価格が印刷されている、消費税が計算されている、かつ請求書の合計が税額に等しい、自己請求書を発行します。</span><span class="sxs-lookup"><span data-stu-id="83571-119">The company issues a self-invoice where the text **Free invoice** is clearly printed on the header, the value of goods is printed, the sales tax is calculated, and the total of the invoice is equal to the tax amount.</span></span>
- <span data-ttu-id="83571-120">顧客が消費税を支払う。</span><span class="sxs-lookup"><span data-stu-id="83571-120">The customer pays the sales tax.</span></span> <span data-ttu-id="83571-121">商品は理由コードが**無料**の納品書と共に顧客に発送されます。</span><span class="sxs-lookup"><span data-stu-id="83571-121">The goods are shipped to the customer with a delivery note with the reason code **Free**.</span></span> <span data-ttu-id="83571-122">その後、納品書が顧客に請求されます。</span><span class="sxs-lookup"><span data-stu-id="83571-122">The delivery note is then invoiced to the customer.</span></span> <span data-ttu-id="83571-123">請求書は、ヘッダーに**無料の請求書**と明記されている、商品の価格が印刷されている、消費税が計算されている、かつ請求書の合計が税額に等しくなっています。</span><span class="sxs-lookup"><span data-stu-id="83571-123">On the invoice, the text **Free invoice** is clearly printed on the header, the value of goods is printed, the sales tax is calculated, and the total of the invoice is equal to the tax amount.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="83571-124">関連項目</span><span class="sxs-lookup"><span data-stu-id="83571-124">See also</span></span>

<!--docs start-->
<span data-ttu-id="83571-125">[無料で配送される商品の税金請求書](https://docs.microsoft.com/dynamics365/finance/localizations/emea-ita-exil-goods-for-free) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="83571-125">[Tax invoice for goods delivered for free](https://docs.microsoft.com/dynamics365/finance/localizations/emea-ita-exil-goods-for-free) (docs)</span></span>
<!--docs end-->
