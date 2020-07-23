---
title: すぐに使用できる Adyen コネクタで PSD2.0 要件をサポート
description: 'Adyen 用のすぐに使用できる支払いコネクタは、Adyen が提供する更新された SDK のサポートを取得します。 このバージョンの支払いコネクタでは、PSD2.0 に含まれる強力な顧客認証 (Strong Customer Authentication: SCA) 規定で定められている支払いリダイレクトを含む、PSD2.0 支払い要件のサポートが追加されます。'
author: relnotes
ms.reviewer: josaw
ms.date: 06/24/2020
ms.assetid: ed913be9-6e8e-ea11-a811-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: rubendel
dynamics365pdf: true
ms.openlocfilehash: fab14068cc5133f47902db94523e49648540a776
ms.sourcegitcommit: b4383db1666141e3c62ef493ca522cd5ae34e1f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/01/2020
ms.locfileid: "3522859"
---
# <a name="support-psd20-requirements-in-the-out-of-the-box-adyen-connector"></a><span data-ttu-id="e2c51-104">すぐに使用できる Adyen コネクタで PSD2.0 要件をサポート</span><span class="sxs-lookup"><span data-stu-id="e2c51-104">Support PSD2.0 requirements in the out-of-the-box Adyen connector</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="e2c51-105">有効対象</span><span class="sxs-lookup"><span data-stu-id="e2c51-105">Enabled for</span></span>    |  <span data-ttu-id="e2c51-106">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="e2c51-106">Public preview</span></span> | <span data-ttu-id="e2c51-107">一般提供</span><span class="sxs-lookup"><span data-stu-id="e2c51-107">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="e2c51-108">エンド ユーザー、管理者/作成者/アナリストによる有効化</span><span class="sxs-lookup"><span data-stu-id="e2c51-108">End users by admins, makers, or analysts</span></span>|<span data-ttu-id="e2c51-109">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="e2c51-109">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="e2c51-110">2020 年 5 月 18 日</span><span class="sxs-lookup"><span data-stu-id="e2c51-110">May 18, 2020</span></span>| <span data-ttu-id="e2c51-111">2020 年 7 月</span><span class="sxs-lookup"><span data-stu-id="e2c51-111">Jul 2020</span></span>|


## <a name="business-value"></a><span data-ttu-id="e2c51-112">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="e2c51-112">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="e2c51-113">欧州の PSD2.0 要件では、チェックアウト時にカード所有者を銀行で直接認証できるようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e2c51-113">European PSD2.0 requirements mandate that cardholders can be authenticated directly with their bank at the time of checkout.</span></span> <span data-ttu-id="e2c51-114">この機能により、銀行が顧客を認証するために必要なリダイレクトのサポートが追加されます。</span><span class="sxs-lookup"><span data-stu-id="e2c51-114">This feature adds support for the redirect required for a customer to be authenticated by their bank.</span></span> <span data-ttu-id="e2c51-115">この機能では、この強力な顧客認証のサポートだけでなく、Adyen が提供する新しい SDK のサポートが追加されます。これにより、利用可能な支払い方法に関してチェックアウト時の柔軟性が向上します。</span><span class="sxs-lookup"><span data-stu-id="e2c51-115">In addition to adding support for this strong customer authentication, this feature adds support for a newer SDK provided by Adyen, which provides more flexibility during checkout with regard to available payment methods.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="e2c51-116">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="e2c51-116">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="e2c51-117">この機能により、バージョン "V002" を指定するためのオプションが Adyen 支払いコネクタ セットアップに追加されます。</span><span class="sxs-lookup"><span data-stu-id="e2c51-117">This feature adds an option in the Adyen payment connector setup to specify version "V002".</span></span> <span data-ttu-id="e2c51-118">オンライン ストアの支払いアカウントのセットアップでその設定が変更されると、チェックアウト プロセスでは Adyen Web Drop-in SDK を使用して支払いを作成します。</span><span class="sxs-lookup"><span data-stu-id="e2c51-118">When that setting is changed in the payment account setup for the online store, the checkout process will use the Adyen Web Drop-in SDK to create payments.</span></span> <span data-ttu-id="e2c51-119">このバージョンの支払いコネクタを使用すると、ストアフロントの業者は PSD2.0 準拠の支払いを処理できます。</span><span class="sxs-lookup"><span data-stu-id="e2c51-119">This version of the payment connector allows storefront merchants to process PSD2.0-compliant payments.</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="e2c51-120">関連項目</span><span class="sxs-lookup"><span data-stu-id="e2c51-120">See also</span></span>

<!--docs start-->
<span data-ttu-id="e2c51-121">[Adyen コネクタを使用した強力な顧客認証 (SCA)](https://docs.microsoft.com/dynamics365/commerce/adyen_redirect) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="e2c51-121">[Strong Customer Authentication (SCA) using the Adyen connector](https://docs.microsoft.com/dynamics365/commerce/adyen_redirect) (docs)</span></span>
<!--docs end-->
