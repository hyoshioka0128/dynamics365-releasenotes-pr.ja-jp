---
title: Service Fabric 配置での Commerce 支払パッケージのサポート
description: この機能により、ISV、顧客、およびパートナーは、オンプレミス環境および Service Fabric 環境で Service Fabric インフラストラクチャを使用して配置できる Dynamics 365 Commerce の支払パッケージを作成できます。
author: mugunthanm
ms.reviewer: rhaertle
ms.date: 04/14/2020
ms.assetid: 8bde666f-094d-ea11-a812-000d3a579c39
ms.topic: article
ms.service: business-applications
ms.author: mumani
dynamics365pdf: true
ms.openlocfilehash: 19321d10137660d4ac878359a9d3c82c7a12de6b
ms.sourcegitcommit: ffd2a9b81763d82b9121a2bb5a738441bafd62c8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/29/2020
ms.locfileid: "3320415"
---
# <a name="commerce-payment-packaging-support-in-service-fabric-deployments"></a><span data-ttu-id="7ea7a-103">Service Fabric 配置での Commerce 支払パッケージのサポート</span><span class="sxs-lookup"><span data-stu-id="7ea7a-103">Commerce payment packaging support in Service Fabric deployments</span></span>
[!include[dynamics365-commerce banner](../includes/dynamics365-commerce.md)]

| <span data-ttu-id="7ea7a-104">有効対象</span><span class="sxs-lookup"><span data-stu-id="7ea7a-104">Enabled for</span></span>    |  <span data-ttu-id="7ea7a-105">パブリック プレビュー</span><span class="sxs-lookup"><span data-stu-id="7ea7a-105">Public preview</span></span> | <span data-ttu-id="7ea7a-106">一般提供</span><span class="sxs-lookup"><span data-stu-id="7ea7a-106">General availability</span></span> | 
| ---------- | :----------: |:----------: |
|<span data-ttu-id="7ea7a-107">エンド ユーザー、自動的</span><span class="sxs-lookup"><span data-stu-id="7ea7a-107">End users, automatically</span></span>|<span data-ttu-id="7ea7a-108">![この機能はリリース済みです。](/dynamics365-release-plan/media/green-checkmark.png "この機能はリリース済みです。")</span><span class="sxs-lookup"><span data-stu-id="7ea7a-108">![This feature is released.](/dynamics365-release-plan/media/green-checkmark.png "This feature is released.")</span></span> <span data-ttu-id="7ea7a-109">2020 年 3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="7ea7a-109">Mar 31, 2020</span></span>| <span data-ttu-id="7ea7a-110">近日発表</span><span class="sxs-lookup"><span data-stu-id="7ea7a-110">To be announced</span></span>|


## <a name="business-value"></a><span data-ttu-id="7ea7a-111">ビジネス バリュー</span><span class="sxs-lookup"><span data-stu-id="7ea7a-111">Business value</span></span>
<!-- bv start -->
<span data-ttu-id="7ea7a-112">この機能により、支払パッケージをオンプレミス環境に配置できます。</span><span class="sxs-lookup"><span data-stu-id="7ea7a-112">This features allows payment packages to be deployed to on-premises environments.</span></span> <span data-ttu-id="7ea7a-113">以前は、支払拡張機能パッケージはクラウド環境でのみサポートされていたため、顧客はオンプレミス環境の Dynamics 365 Commerce で支払拡張機能を使用できませんでした。</span><span class="sxs-lookup"><span data-stu-id="7ea7a-113">Previously, payment extension packages were only supported in cloud environments, blocking customers from using  payment extensions in Dynamics 365 Commerce in on-premises environments.</span></span>
<!-- bv end -->



## <a name="feature-details"></a><span data-ttu-id="7ea7a-114">機能の詳細</span><span class="sxs-lookup"><span data-stu-id="7ea7a-114">Feature details</span></span>
<!--feature detail start -->
<span data-ttu-id="7ea7a-115">拡張機能を使用して、Dynamics 365 Commerce で新しい支払パッケージを作成し、拡張モデルへの参照として支払ライブラリを追加し、カスタマイズを行うことができます。</span><span class="sxs-lookup"><span data-stu-id="7ea7a-115">Extensions can be used to create new payment packages in Dynamics 365 Commerce, add the payment libraries as a reference to the extension model, and do customizations.</span></span> <span data-ttu-id="7ea7a-116">すべての支払拡張機能モジュールは、名前が RetailPaymentConnectors で始まる (これが接頭辞として付加されている) 必要があります。</span><span class="sxs-lookup"><span data-stu-id="7ea7a-116">All payment extension modules must begin with (or be prefixed with) the name RetailPaymentConnectors.</span></span> <span data-ttu-id="7ea7a-117">モデルで別の接頭辞が使用される場合、それは支払モジュールとは見なされません。</span><span class="sxs-lookup"><span data-stu-id="7ea7a-117">If the model uses a different prefix, then it will not be considered to be a payment module.</span></span> <span data-ttu-id="7ea7a-118">カスタマイズ後、配置可能なパッケージを作成し、Dynamics Lifecycle Services (LCS) を使用して配置できます。</span><span class="sxs-lookup"><span data-stu-id="7ea7a-118">After the customization, you can create the deployable package and deploy it using Dynamics Lifecycle Services (LCS).</span></span>
<!--feature detail end -->










## <a name="see-also"></a><span data-ttu-id="7ea7a-119">関連項目</span><span class="sxs-lookup"><span data-stu-id="7ea7a-119">See also</span></span>

<!--docs start-->
<span data-ttu-id="7ea7a-120">[Service Fabric 配置でのアプリケーション エクスプローラー用支払パッケージの作成](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/payment-connector-package) (ドキュメント)</span><span class="sxs-lookup"><span data-stu-id="7ea7a-120">[Create payment packaging for Application Explorer in Service Fabric deployments](https://docs.microsoft.com/dynamics365/commerce/dev-itpro/payment-connector-package) (docs)</span></span>
<!--docs end-->
