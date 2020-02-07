---
title: 会計統合フレームワークに基づく、フランス向け小売トランザクションのデジタル署名
description: キャッシュ レジスターに関するフランスの現地規制では、すべての小売販売にデジタル署名をし、署名の抜粋をその販売の顧客用領収書に印刷することが義務付けられています。 この新機能は、会計統合フレームワークを拡張することで、デジタル署名の要件に対応するものです。
author: relnotes
ms.reviewer: josaw
ms.date: 01/10/2020
ms.assetid: f0bed236-e115-ea11-a811-000d3a8f075c
ms.topic: article
ms.service: business-applications
ms.author: epopov
dynamics365pdf: true
ms.openlocfilehash: 44ca5590f50e3ecd231dacd4142a9c40a4703254
ms.sourcegitcommit: ceff5b6bef71093d51a3afb60b3fecd4cd8a11c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/25/2020
ms.locfileid: "2986646"
---
# <a name="digital-signing-of-retail-transactions-for-france-based-on-the-fiscal-integration-framework"></a><span data-ttu-id="cbe5f-104">会計統合フレームワークに基づく、フランス向け小売トランザクションのデジタル署名</span><span class="sxs-lookup"><span data-stu-id="cbe5f-104">Digital signing of retail transactions for France based on the fiscal integration framework</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="cbe5f-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="cbe5f-105">Enabled for</span></span>    |  <span data-ttu-id="cbe5f-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="cbe5f-106">Public preview</span></span> | <span data-ttu-id="cbe5f-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="cbe5f-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="cbe5f-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="cbe5f-108">End users by admins, makers, or analysts</span></span>|-| <span data-ttu-id="cbe5f-109">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="cbe5f-109">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="cbe5f-110">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="cbe5f-110">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="cbe5f-111">フランス向けの小売トランザクションのデジタル署名機能は、現地のキャッシュ レジスター規制に準拠した POS ソリューションを構築するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="cbe5f-111">The digital signing of retail transactions for France can be used by customers to build their POS solutions that are compliant with local cash register regulations.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="cbe5f-112">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="cbe5f-112">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="cbe5f-113">フランス向け小売トランザクションのデジタル署名機能は、[会計統合フレームワーク](https://docs.microsoft.com/dynamics365/retail/localizations/fiscal-integration-for-retail-channel)を使用するように改良されました。つまり、組み込みの会計統合機能がすべてサポートされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="cbe5f-113">The digital signing of retail transactions for France now takes advantage of the [fiscal integration framework](https://docs.microsoft.com/dynamics365/retail/localizations/fiscal-integration-for-retail-channel), meaning it supports all of the built-in fiscal integration capabilities.</span></span> <span data-ttu-id="cbe5f-114">この機能は、事前構築済みのソリューションに含まれていますが、使用するには構成を行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="cbe5f-114">It is included in the out-of-the-box solution but needs to be configured to be used.</span></span> <span data-ttu-id="cbe5f-115">この機能により、さまざまな現金持ち帰り販売や顧客注文シナリオで、デジタル署名を使用して販売を会計登録できるようになるほか、さまざまなタイプの監査イベントを会計登録できるようになります。</span><span class="sxs-lookup"><span data-stu-id="cbe5f-115">The feature enables fiscal registration of sales by means of digital signing in various cash-and-carry sales and customer order scenarios, as well as fiscal registration of audit events of various types.</span></span>

<span data-ttu-id="cbe5f-116">Retail 会計統合フレームワークを使用することで、多国籍の小売業者は、事業を展開する国や地域のさまざまな会計規制に準拠した、共通の POS ソリューションを構築することができます。</span><span class="sxs-lookup"><span data-stu-id="cbe5f-116">The Retail fiscal integration framework enables multinational retailers to build common POS solutions that are compliant with different local fiscal regulations in the countries or regions that they operate in.</span></span>
<!--feature detail end -->









